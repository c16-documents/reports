# ABB O2C — Layer 1 Discovery Prompt

## Context

This prompt replaces the original VA01/VA02-only Layer 1 prompt. It covers the **full ABB O2C scope** across 5 process areas, 12 business scenarios, 25+ enhancement hooks, and country-specific compliance — matching the ABB PoC scope document sections 3.1 through 3.6 and section 15.

---

## The Prompt (copy everything below this line)

---

```
Map ALL custom code touching the Order-to-Cash process
in this ECC system (REMSC ERP). This is a full end-to-end
O2C discovery — not just sales orders.

═══════════════════════════════════════════════════════════
PROCESS AREA 1: SALES ORDER (VA01/VA02/VA21/VA22/VA41/VA42)
═══════════════════════════════════════════════════════════

Scan these SPECIFIC enhancement includes for active code:
- MV45AFZZ (general: SAVE_DOCUMENT, SAVE_DOCUMENT_PREPARE,
  MOVE_FIELD_TO_VBAK/VBAP, CHECK_VBAK/VBAP)
- MV45AFZA (field selection, partner determination, dialog)
- MV45AFZB (pricing, item category, schedule line)
- MV45AFZD (field and dynpro exits)
- MV45AFZF (foreign trade, additional checks)
- MV45AFZH (schedule line exits)

Find BAdI implementations on:
- BADI_SD_SALES / BADI_SD_SALES_BASIC / BADI_SD_V46H_*
- BADI_SD_BATCH_ATP (ATP with batch determination)
- SD_SALES_DOCUMENT_CHECK (validation)
- Any Z BAdI impl on sales order processing

Find custom logic for these sub-processes:

1. ORDER ENTRY & PARTNERS
   - Partner determination overrides (VOPA config + custom)
   - Account group validations, AAG checks
   - Address validation logic
   - Payment terms / Incoterms / Billing Date defaults

2. PRICING DETERMINATION
   - Custom VOFM routines: requirements, formulas,
     condition base value, condition value, group key
   - Custom condition types (Z* in T685)
   - KOMK / KOMP / KOMG append fields
   - Condition exclusion logic
   - SPA (Special Price Agreement) linkage
   - Repricing scenarios (pricing type B/C/G/H)

3. TAX DETERMINATION
   - Country-specific tax exits (GST, VAT, SUT, WHT, TDS)
   - e-invoice triggers (India IRN, MX CFDI, IT FatturaPA,
     BR NFE, GR myDATA)
   - Tax classification overrides

4. ATP & SCHEDULING
   - BADI_ATP_CUST implementations
   - APO / aATP / gATP integration touch-points
   - Product allocation, backorder processing (BOP)
   - Multi-plant checks, alternate plant cascades
   - Schedule line synchronization (3rd party / IC chains)

5. GTS INTEGRATION
   - SPL screening, embargo checks
   - Licence determination
   - Compliance validation exits

6. CREDIT MANAGEMENT
   - Classic SD-CM exits and BAdIs
   - FSCM-CR integration touch-points
   - Central Finance credit check calls
   - Approval workflows for credit blocks

7. CONTROLLING INTEGRATION
   - CO-PA derivation (RA Key, Overhead Key)
   - Profit center substitution / redetermination
   - Account assignment logic

8. FIELD & SCREEN CONTROL
   - USEREXIT_FIELD_MODIFICATION
   - Custom sub-screens / tabs on VA01/VA02 dynpros
   - CI_INCLUDE-driven custom tabs
   - Field enablement / disablement / mandatory logic

9. VALIDATION & BUSINESS RULES
   - USEREXIT_SAVE_DOCUMENT_PREPARE
   - Incompletion checks (custom entries in V_TVKOZ)
   - Item category / requirement type redetermination
   - Plant determination overrides (country-specific)
   - Country of Origin determination
   - Hardcoded IF/ELSE business rules

10. COPY CONTROL
    - VOFM data transfer routines (header / item / sched line)
    - Copy control validations across doc types

11. SAVE & OUTPUT
    - USEREXIT_SAVE_DOCUMENT
    - Order confirmation forms (SmartForm, SAPscript, Adobe)
    - Output determination (NACE message types for V1)
    - Workflow triggers on order save
    - ALE/EDI output processing

12. RELEASE STRATEGY
    - Sales order release (status profiles, delivery blocks,
      billing blocks, reason for rejection as maker-checker)
    - CMR / DMR release strategy validations

═══════════════════════════════════════════════════════════
PROCESS AREA 2: DELIVERY (VL01N/VL02N/VL10A-H/VL06*/VL22)
═══════════════════════════════════════════════════════════

Scan these SPECIFIC enhancement includes:
- MV50AFZ1 / MV50AFZ2 (header / item exits)
- MV50AFZK / MV50AFZL (save / output / picking)
- MV56AFZZ (additional delivery logic)
- MV52EFZZ (returns delivery)

Find BAdI implementations on:
- LE_SHP_DELIVERY_PROC
- LE_SHP_TAB_CUST_HEAD / LE_SHP_TAB_CUST_ITEM (custom tabs)
- BADI_LE_SHIPMENT

Find custom logic for:
1. Delivery creation validations & split control
2. Picking & packing (HU, serial number, batch determination)
3. Batch status & expiry checks
4. PGI validations (movement type, posting period, acct determ)
5. POD relevance and processing
6. Returns delivery & reverse-PGI
7. Output (ASN, pick-list, packing slip, BoL)
8. TM / EWM / external WMS push during creation & PGI
9. Country compliance (e-way bill, e-AWB, customs export)
10. Mass processing programs (VL10*, VL06*, VL22 background)

═══════════════════════════════════════════════════════════
PROCESS AREA 3: BILLING (VF01/VF02/VF04/VF06/VF11/VFX3)
═══════════════════════════════════════════════════════════

Scan these SPECIFIC enhancement includes:
- RV60AFZZ (USEREXIT_FILL_VBRK_VBRP, USEREXIT_NUMBER_RANGE)
- RV60AFZA / RV60AFZB / RV60AFZC / RV60AFZD
- RV61AFZA / RV61AFZB (billing list / index)

Find BAdI implementations on:
- SD_CIN_LV60AU02 (country-specific tax in billing)
- BADI_SD_BILLING / SD_INVOICE_PROC
- BTE 503 / 1030 / 1040 / 5xx series (open FI events)

Find custom logic for:
1. Billing creation validations & split criteria
2. Intercompany billing & cross-company checks
3. Park & Post / Park & Release scenarios
4. Cancellation validations (VF11 posting period checks)
5. e-invoice generation & persistence (India IRN/QR,
   MX CFDI, IT FatturaPA, BR NFE, GR myDATA)
6. TDS / WHT validations
7. Exchange rate redetermination
8. Custom number range determination (country + doc type)
9. Revenue recognition / RAR linkage
10. CO-PA derivation on billing posting
11. Rebate settlement & retro-billing (VBOF, B1)
12. Output (invoice print/email, ALE/EDI INVOIC, PEPPOL)

═══════════════════════════════════════════════════════════
PROCESS AREA 4: CUSTOMER / BUSINESS PARTNER MASTER
═══════════════════════════════════════════════════════════

Find custom logic for:
1. Account group validations (KNA1-KTOKD)
2. Tax number validations (GSTIN, VAT, ABN, EIN, PAN)
3. Partner function determination (AG, WE, RG, ZC, ER)
4. CVI readiness checks (customer-vendor integration)
5. Duplicate customer checks & de-duplication
6. Custom classification fields
7. Custom screen tabs (general / company code / sales area)
8. MDG-C / MDG-S integration touch-points
9. RFC integrations (onboarding portals)

═══════════════════════════════════════════════════════════
PROCESS AREA 5: PRICING MASTER DATA
═══════════════════════════════════════════════════════════

Find custom logic for:
1. Custom condition types (Z* in T685) with access sequences
2. Field catalog amendments (pricing comm structure changes)
3. Mass pricing condition create/change/download programs

═══════════════════════════════════════════════════════════
CROSS-CUTTING: INTERFACES
═══════════════════════════════════════════════════════════

Find ALL inbound/outbound interfaces:
- IDoc: ORDERS05, ORDCHG, ORDRSP, SDPACK (order)
         DELVRY05/07, SHPMNT05 (delivery)
         INVOIC02 (billing)
- IDoc exits: IDOC_INPUT_ORDERS, IDOC_INPUT_ORDCHG,
  IDOC_OUTPUT_DELVRY, IDOC_INPUT_DELVRY,
  IDOC_OUTPUT_INVOIC, IDOC_INPUT_INVOIC
- IDoc BAdIs: IDOC_DATA_MAPPER, IDOC_APPL_SOURCE_DEFAULT
- RFC destinations touching O2C (Conga, Easy Order,
  eCommerce, OMS, partner portals)
- OData services for order/delivery/billing
- Web service / Proxy inbound channels
- Z-programs doing mass upload / batch creation

═══════════════════════════════════════════════════════════
CROSS-CUTTING: CUSTOM TABLES & APPENDS
═══════════════════════════════════════════════════════════

Find ALL:
- ZZ/YY append structures on: VBAK, VBAP, VBKD, VBPA,
  VBEP, LIKP, LIPS, VBRK, VBRP, KOMK, KOMP, KOMG,
  KOMV, KNA1, KNVV
- Custom Z-tables read/written during O2C processing
- Custom structures passed between exits

═══════════════════════════════════════════════════════════
CROSS-CUTTING: OUTPUT FORMS
═══════════════════════════════════════════════════════════

Find ALL:
- SmartForms for order confirmation, delivery note,
  invoice, credit/debit memo
- SAPscript forms still active in O2C
- Adobe Forms (SFP) for O2C documents
- Custom print programs (Z* drivers)
- Custom message types (ZA*, ZB* in NACE)

═══════════════════════════════════════════════════════════

For EACH discovered object, provide:
- Name, type (PROG/CLAS/FUGR/SXCI/ENHI/SFPF/TABL/EXIT)
- Process area (1-5) and sub-step number
- What it does in plain English
- Lines of code (where readable)
- Tables it reads/writes
- Country relevance (if detectable from code —
  look for country codes, plant groups, sales org filters)
- Last changed date (from TADIR/REPOSRC)

═══════════════════════════════════════════════════════════
BUSINESS SCENARIOS TO VALIDATE COVERAGE
═══════════════════════════════════════════════════════════

After discovery, confirm coverage of these 12 scenarios:
□ Make-to-Stock
□ Make-to-Order
□ Trading (Individual PO + Third-party)
□ Downpayment process
□ Sales Returns
□ Credit Memo / Debit Memo
□ FOC Orders (Free of Charge)
□ Free Samples
□ Scrap Sales
□ Service Process
□ Project Sales (PS WBS linked)
□ Intercompany Sales

Show results as tables grouped by Process Area,
then by sub-step within each area.
Flag any enhancement hook from the ABB scope document
Section 15 that has NO custom implementation found
(clean hook = good news for migration).
Don't generate a document yet.
```

---

## Mapping: ABB Scope Section → Prompt Section

| ABB Scope Section | Prompt Coverage |
|---|---|
| 3.1 Business Scenarios (12 types) | Business Scenarios checklist at bottom |
| 3.2 Order Management | Process Area 1 (12 sub-steps) |
| 3.3 Delivery | Process Area 2 (10 sub-steps) |
| 3.4 Billing | Process Area 3 (12 sub-steps) |
| 3.5 Customer / BP Master | Process Area 4 (9 sub-steps) |
| 3.6 Pricing Master | Process Area 5 (3 sub-steps) |
| 4.0 Interfaces | Cross-Cutting: Interfaces |
| 5.0 Custom Tables | Cross-Cutting: Custom Tables & Appends |
| 6.0 Forms / Output | Cross-Cutting: Output Forms |
| 15.0 Enhancement Hooks | Named includes per area (MV45AFZZ etc.) |
| Country-wise org | "Country relevance" field per object |

## What Changed vs. Old Prompt

| Dimension | Old (VA01/VA02 only) | New (Full ABB Scope) |
|---|---|---|
| Process areas | 1 (sales order) | 5 + 3 cross-cutting |
| Sub-steps | 8 | 46 total |
| Named includes | 0 | 25+ (MV45A*, MV50A*, RV60A*, RV61A*) |
| Business scenarios | 0 | 12 named scenarios |
| Country compliance | Not mentioned | e-invoice, GST, VAT, WHT, TDS, e-way bill |
| GTS / APO / FSCM | Not mentioned | Explicit sub-steps |
| VOFM routines | Not mentioned | Requirements, formulas, copy control, base value |
| IDoc types | Generic "ORDERS05" | 12 specific message types + exit names |
| Append tables | VBAK, VBAP only | 15 tables (VBAK through KNVV) |
| Output | "order confirmation" | Full NACE across order/delivery/billing |
