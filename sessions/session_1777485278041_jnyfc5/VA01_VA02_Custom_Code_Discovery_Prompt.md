# Layer 1 Prompt — VA01/VA02 Custom Code Discovery

## Instructions

Map all custom code touching Sales Order Create and Change (VA01/VA02) in this ECC system.

**Scope:** ONLY what happens inside the sales order transaction.
**Entry point:** User opens VA01 or API call creates order.
**Exit point:** Sales order saved, confirmed, output triggered.

---

## Step 0: Raw Count Anchor

First, give me the **TOTAL raw count** of all custom extension objects (CEOs) touching these standard VA01/VA02 execution programs — before grouping by sub-step:

### ORDER PROCESSING CORE

| Program | Role |
|---------|------|
| `SAPMV45A` | Main module pool — VA01/VA02 |
| `SAPLV45A` | Function pool — all VA exit FMs live here |
| `V45A0001` | Enhancement FG — header data |
| `V45A0002` | Enhancement FG — pricing transfer |
| `V45A0003` | Enhancement FG — save/check |
| `V45A0004` | Enhancement FG — partner determination |
| `SDVAX001` | Enhancement project — bundles all VA exits |
| `MV45AFZZ` | Customer include — FORM routines |
| `MV45AIZZ` | Customer include — PAI |
| `MV45AOZZ` | Customer include — PBO |
| `MV45ATZZ` | Customer include — text |

### PRICING

| Program | Role |
|---------|------|
| `RV61A*` | VOFM pricing routines |
| `SAPLV61A` | Pricing function pool |

### SCHEDULE LINES / ATP

| Program | Role |
|---------|------|
| `SAPMV45E` | Schedule line processing |

### CREDIT CHECK

| Program | Role |
|---------|------|
| `RVKRED01` | Credit check during save |

### OUTPUT

| Program | Role |
|---------|------|
| `RV60A*` | Output determination routines |

Scan `MODSAP`, `SXS_ATTR`, `SXC_EXIT`, `ENLFDIR`, `D010TAB` cross-references and `TADIR` for any Z/Y object linked to these programs.

**Show:** Total CEO count, then break down by sub-step.

---

## Step 1: Discover ALL Custom Objects by Sub-Step

### 1. ORDER ENTRY & PARTNERS

- User exits for header/item/partner (`MV45AFZZ`, `MV45AOZZ`)
- BAdI implementations for sales document creation
- Custom partner determination logic
- Z-programs creating orders via BAPI or BDC

### 2. FIELD MODIFICATION

- `USEREXIT_FIELD_MODIFICATION` and similar
- Screen layout BAdIs
- Custom field defaults and visibility rules

### 3. PRICING

- Custom pricing routines (`RV61A*`)
- Custom condition types and access sequences
- Pricing BAdI implementations
- Manual condition handling

### 4. AVAILABILITY CHECK

- ATP BAdI implementations (`BADI_ATP_CUST`)
- Custom availability check logic
- Safety stock overrides

### 5. CREDIT CHECK

- Custom credit check logic
- Credit management BAdIs
- Approval workflows for credit blocks

### 6. VALIDATION & BUSINESS RULES

- `USEREXIT_SAVE_DOCUMENT_PREPARE`
- `SD_SALES_DOCUMENT_CHECK` BAdI
- Custom incompletion checks
- Hardcoded IF/ELSE business rules

### 7. SAVE & OUTPUT

- `USEREXIT_SAVE_DOCUMENT`
- Order confirmation forms (SmartForm, SAPscript, Adobe)
- Output determination config (NACE)
- Workflow triggers on order save

### 8. CUSTOM FIELDS & TABLES

- ZZ/YY appends on `VBAK`, `VBAP`, `VBEP`, `VBKD`
- Custom Z-tables read/written during order processing
- Custom structures passed between exits

---

## Step 2: Cross-Cutting Integration Objects

Also find:

- Z-programs that create/change orders via `BAPI_SALESORDER_CREATEFROMDAT2`
- Z-programs that use `CALL TRANSACTION 'VA01'` or `'VA02'`
- OData services for sales order create/change
- IDoc processing for inbound `ORDERS05`
- RFC functions receiving orders from external systems

---

## Step 3: Output Format

For each object tell me:

| Column | Description |
|--------|-------------|
| **Name** | Object name |
| **Type** | Program, BAdI, exit, form, append, table, OData, etc. |
| **Sub-step** | Which sub-step (1-8) or Integration |
| **Description** | What it does in plain English |
| **Lines** | Lines of code |
| **Tables** | Which SAP tables it reads/writes |

Show as **tables grouped by sub-step**.

---

## Excluded Programs (and why)

These were considered but excluded from the scan perimeter:

| Program | Reason Excluded |
|---------|-----------------|
| `V45P` | Not a real standard program in VA01/VA02 processing |
| `VKMP` | Condition maintenance (pricing admin) — not order processing |
| `MCS1` | CO-PA Profitability Analysis — executes in billing, not VA01/VA02 |
| `FDCB` | FI-side credit config — `RVKRED01` covers the SO-side credit check |
| `SAPFV45*` | Vague — replaced by specific names (`SAPLV45A`, `SAPLV61A`) |

---

## Notes

- **Don't generate a document yet** — show results as tables in chat
- The raw count at the top serves as a **denominator check** — sub-step totals should sum to the raw count (with objects appearing in multiple sub-steps noted)
- Focus on objects that execute **inside** the VA01/VA02 call stack — not objects that merely read VBAK/VBAP for reporting purposes
