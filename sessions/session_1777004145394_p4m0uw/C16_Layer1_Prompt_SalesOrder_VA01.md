# Layer 1 Prompt — Sales Order Create & Change (VA01/VA02)

## Copy-Paste This Into C16

---

```
Map all custom code touching Sales Order Create and Change 
(VA01/VA02) in this ECC system.

Scope: ONLY what happens inside the sales order transaction.
Entry point: User opens VA01 or API call creates order.
Exit point: Sales order saved, confirmed, output triggered.

Discover ALL custom objects for these sub-steps:

1. ORDER ENTRY & PARTNERS
   - User exits for header/item/partner (MV45AFZZ, MV45AOZZ)
   - BAdI implementations for sales document creation
   - Custom partner determination logic
   - Z-programs creating orders via BAPI or BDC

2. FIELD MODIFICATION
   - USEREXIT_FIELD_MODIFICATION and similar
   - Screen layout BAdIs
   - Custom field defaults and visibility rules

3. PRICING
   - Custom pricing routines (RV61A*)
   - Custom condition types and access sequences
   - Pricing BAdI implementations
   - Manual condition handling

4. AVAILABILITY CHECK
   - ATP BAdI implementations (BADI_ATP_CUST)
   - Custom availability check logic
   - Safety stock overrides

5. CREDIT CHECK
   - Custom credit check logic
   - Credit management BAdIs
   - Approval workflows for credit blocks

6. VALIDATION & BUSINESS RULES
   - USEREXIT_SAVE_DOCUMENT_PREPARE
   - SD_SALES_DOCUMENT_CHECK BAdI
   - Custom incompletion checks
   - Hardcoded IF/ELSE business rules

7. SAVE & OUTPUT
   - USEREXIT_SAVE_DOCUMENT
   - Order confirmation forms (SmartForm, SAPscript, Adobe)
   - Output determination config (NACE)
   - Workflow triggers on order save

8. CUSTOM FIELDS & TABLES
   - ZZ/YY appends on VBAK, VBAP, VBEP, VBKD
   - Custom Z-tables read/written during order processing
   - Custom structures passed between exits

Also find:
   - Z-programs that create/change orders via BAPI_SALESORDER_CREATEFROMDAT2
   - Z-programs that use CALL TRANSACTION 'VA01' or 'VA02'
   - OData services for sales order create/change
   - IDoc processing for inbound ORDERS05
   - RFC functions receiving orders from external systems

For each object tell me:
   - Name and type (program, BAdI, exit, form, append)
   - Which sub-step it belongs to (1-8 above)
   - What it does in plain English
   - Lines of code
   - Which tables it reads/writes

Show as tables grouped by sub-step.
Don't generate a document yet.
```

---

## What C16 Does With This Prompt

| Step | Action |
|------|--------|
| 1 | Scan MODSAP for user exits on SAPMV45A (VA01/VA02 main program) |
| 2 | Scan SXS_ATTR for BAdI implementations in SD sales document area |
| 3 | Scan TADIR for Z-programs calling VA01/VA02 (BAPI, BDC, RFC) |
| 4 | Scan DD03L for ZZ/YY appends on VBAK, VBAP, VBEP, VBKD |
| 5 | Scan NACE for custom output types on V1 (sales order application) |
| 6 | Read source code of each object found |
| 7 | Group by sub-step (1-8 above) |
| 8 | Show as tables |

---

## After Reviewing Layer 1 Output

Once you've reviewed what C16 found, proceed to Layer 2:

```
Now show me what S/4HANA 2025 offers as standard replacement 
for each sub-step you found customs in.

For each sub-step show:
- Which Fiori app covers this
- Which Released APIs exist
- Which Released BAdIs replace the user exits
- What's deprecated or removed
- What new capabilities exist

Show as a table per sub-step.
Don't generate a document yet.
```

---

## To Change Process Scope

Swap the first 3 lines:

| Process | Entry Point | Exit Point |
|---------|-------------|------------|
| **Purchase Order (ME21N/ME22N)** | User opens ME21N or API creates PO | PO saved, released, output triggered |
| **Production Order (CO01/CO02)** | User opens CO01 or auto-created from MRP | Production order released, confirmed |
| **Delivery (VL01N/VL02N)** | Delivery created from SO or manually | Goods issue posted, POD confirmed |
| **Billing (VF01/VF04)** | Billing doc created from delivery | Invoice posted, accounting doc created |
| **GL Posting (FB50/F-02)** | Journal entry created | Document posted, period updated |

Same prompt structure. Just change the transaction, entry/exit, and sub-steps.
