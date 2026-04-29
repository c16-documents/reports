# Layer 2 Prompt — S/4HANA 2025 Standard Delta for VA01/VA02

## Pre-Requisite
Layer 1 discovery must be complete. You should have:
- Raw count of all custom objects
- Objects grouped by 8 sub-steps
- Standard program table (SAPMV45A, MV45AFZZ, RV61A*, etc.)

---

## The Prompt — Copy-Paste Ready

```
Now show me what S/4HANA 2025 offers as standard replacement 
for each of the 8 sub-steps where you found customs.

For each sub-step show:
- Which Fiori app covers this sub-step
- Which Released APIs exist
- Which Released BAdIs replace the SPECIFIC user exits found
  (map old exit → new BAdI by name)
- What's deprecated or removed
- What new capabilities exist (Key User, BRF+, Output Mgmt 2.0)

Also map against the standard programs from Layer 1:
- MV45AFZZ exits → which Released BAdI replaces each?
- MV45AIZZ exits → which Released BAdI replaces each?
- MV45AOZZ exits → which Released BAdI replaces each?
- MV45ATZZ exits → which Released BAdI replaces each?
- MV45AHZZ exits → which Released BAdI replaces each (if exists)?
- RV61A* pricing routines → what changes in S/4 pricing?
- RV45A* copy control routines → what changes in S/4?
- RVKRED01 credit check → what replaces it in FSCM?
- RV60A* output routines → what replaces it in Output Management 2.0?
- ES_SAPMV45A enhancement spot BAdIs → still released in S/4?
- BADI_SD_SALES → still released in S/4?
- BADI_SALESORDER_UPDATE → still released in S/4?
- BADI_ATP_CUST → still released in S/4?

Show as a table per sub-step with these columns:

| ECC Object | Type | S/4 Replacement | Replacement Type | Status |
|------------|------|-----------------|------------------|--------|
| (exit/BAdI/routine name) | (exit/BAdI/routine) | (Released BAdI/API/Fiori App) | (Released/Deprecated/Removed) | (Available/Changed/Gone) |

Then show a SUMMARY table:

| Sub-Step | Total Customs Found | Released BAdI Available | Released API Available | Fiori App | New Capability |
|----------|--------------------|-----------------------|----------------------|-----------|----------------|
| 1. Order Entry | N | YES/NO | YES/NO | F#### | ... |
| 2. Field Mod | N | YES/NO | YES/NO | F#### | ... |
| ... | | | | | |

Don't generate a document yet.
```

---

## What C16 Does With This Prompt

1. For each of the 8 sub-steps from Layer 1, searches S/4HANA 2025 standard catalog
2. Maps each specific user exit (e.g. `USEREXIT_SAVE_DOCUMENT_PREPARE`) to its Released BAdI successor
3. Maps each standard program (e.g. `RVKRED01`) to its S/4 replacement (e.g. FSCM Credit Management)
4. Checks each existing BAdI (e.g. `BADI_ATP_CUST`) for release status in S/4
5. Identifies Fiori apps per sub-step (e.g. F1814 for order creation)
6. Identifies new capabilities not available in ECC (Key User, BRF+, Output Mgmt 2.0)

---

## Why This Is Better Than a Generic Layer 2

| Aspect | Generic Prompt | This Prompt |
|--------|---------------|-------------|
| **Specificity** | "What does S/4 offer for sales order?" | Maps EACH exit/BAdI/routine by name |
| **Traceability** | General list of Fiori apps | Old object → new object mapping |
| **Validation** | No way to check completeness | Summary table shows coverage per sub-step |
| **Layer 3 ready** | Layer 3 must re-discover replacements | Layer 3 just reads the mapping table |

---

## After Reviewing Layer 2 Output

Next prompt is **Layer 3: Triage Portfolio** — classifies every custom object into RETIRE / CLEAN CORE NOW / REMEDIATE & SCHEDULE / REMEDIATE & DEFER.

---

## Swapping for Other Processes

| Process | Change the program mapping to |
|---------|-------------------------------|
| **Purchase Order (ME21N/ME22N)** | `SAPMM06E`, `MM06EFZ1`-`FZ4`, `EXIT_SAPMM06E_*`, `BADI_ME_PROCESS_PO`, `RV61A*` pricing |
| **Delivery (VL01N/VL02N)** | `SAPMV50A`, `MV50AFZ1`, `BADI_LE_DELIVERY`, `RV60A*` output |
| **Billing (VF01/VF02)** | `SAPMV60A`, `MV60AFZZ`, `BADI_BILLING_*`, `RV60A*` output |
| **Production Order (CO01/CO02)** | `SAPLCOKO`, `EXIT_SAPLCOKO_*`, `BADI_WORKORDER_*` |
| **Goods Movement (MIGO)** | `SAPMM07M`, `MB_MIGO_BADI`, `EXIT_SAPMM07M_*` |
