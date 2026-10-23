  FS ZCL VENDOR BANK VALIDATOR 2026 10 23 @page { size: A4; margin: 20mm 18mm 20mm 18mm; } \* { box-sizing: border-box; margin: 0; padding: 0; } body { font-family: 'Segoe UI', Calibri, Arial, sans-serif; font-size: 10.5pt; line-height: 1.55; color: #1a1a1a; background: #f4f5f6; -webkit-print-color-adjust: exact; print-color-adjust: exact; } .doc-wrapper { max-width: 1100px; margin: 24px auto; background: #ffffff; box-shadow: 0 1px 8px rgba(0,0,0,0.08); border: 1px solid #d0d4d8; } /\* HEADER \*/ .doc-header { background: #003366; color: #ffffff; padding: 28px 36px 24px 36px; border-bottom: 4px solid #7fb3e0; } .doc-header-top { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 14px; } .doc-logo img { height: 40px; display: block; } .doc-classification { font-size: 8.5pt; letter-spacing: 1.2px; text-transform: uppercase; color: #7fb3e0; border: 1px solid #7fb3e0; padding: 3px 12px; border-radius: 2px; white-space: nowrap; } .doc-header h1 { font-size: 22pt; font-weight: 600; letter-spacing: -0.3px; margin: 0 0 4px 0; line-height: 1.2; } .doc-header .doc-subtitle { font-size: 11pt; color: #7fb3e0; font-weight: 400; } /\* META \*/ .doc-meta { padding: 16px 36px; background: #f7f8fa; border-bottom: 1px solid #d0d4d8; font-size: 9.5pt; color: #444; } .doc-meta table { width: 100%; border-collapse: collapse; } .doc-meta td { padding: 3px 12px 3px 0; vertical-align: top; } .doc-meta .meta-label { font-weight: 600; color: #003366; width: 90px; } /\* BODY \*/ .doc-body { padding: 28px 36px 36px 36px; background: #ffffff; } .doc-body p { margin: 8px 0; } .doc-body h2 { font-size: 14pt; color: #003366; margin: 24px 0 12px 0; padding-bottom: 6px; border-bottom: 2px solid #7fb3e0; display: flex; align-items: center; gap: 10px; } .doc-body h2 .sec-num { display: inline-block; background: #003366; color: white; font-size: 11pt; font-weight: 700; padding: 2px 9px; border-radius: 3px; line-height: 1; min-width: 26px; text-align: center; } .doc-body h3 { font-size: 11.5pt; color: #003366; margin: 18px 0 8px 0; font-weight: 600; } .doc-body h4 { font-size: 10.5pt; color: #1a5c8a; margin: 12px 0 6px 0; font-weight: 600; } .doc-body ul, .doc-body ol { margin: 8px 0 8px 22px; } .doc-body li { margin: 4px 0; } /\* TABLES \*/ table.data { width: 100%; border-collapse: collapse; margin: 10px 0 14px 0; font-size: 9.5pt; } table.data th, table.data td { border: 1px solid #d0d4d8; padding: 7px 10px; text-align: left; vertical-align: top; } table.data th { background: #003366; color: white; font-weight: 600; letter-spacing: 0.2px; } table.data tr:nth-child(even) td { background: #f7f8fa; } table.data td.center { text-align: center; } /\* CALLOUTS \*/ .callout { background: #f0f6fa; border-left: 4px solid #1a5c8a; padding: 12px 16px; margin: 14px 0; font-size: 10pt; color: #1f2937; } .callout.tip { border-left-color: #15803D; background: #f0fdf4; } .callout.warning { border-left-color: #C2410C; background: #fff7ed; } /\* PILLS — Clean Core levels \*/ .pill { display: inline-block; font-size: 8.5pt; font-weight: 600; padding: 2px 9px; border-radius: 10px; letter-spacing: 0.3px; white-space: nowrap; } .pill-a { background: #dcfce7; color: #15803D; } .pill-b { background: #dbeafe; color: #1D4ED8; } .pill-c { background: #fef3c7; color: #A16207; } .pill-d { background: #fee2e2; color: #B91C1C; } /\* SYSTEM PILLS — engagement context strip under the header \*/ .doc-pills { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 14px; } .doc-pills .doc-pill { display: inline-flex; align-items: center; gap: 6px; font-size: 8.5pt; font-weight: 500; padding: 4px 12px; border-radius: 16px; background: rgba(255, 255, 255, 0.12); border: 1px solid rgba(255, 255, 255, 0.28); color: #ffffff; letter-spacing: 0.2px; white-space: nowrap; } .doc-pills .doc-pill .doc-pill-icon { font-size: 9pt; opacity: 0.9; } .doc-pills .doc-pill.danger { background: rgba(254, 226, 226, 0.18); border-color: rgba(254, 226, 226, 0.35); } .doc-pills .doc-pill.warn { background: rgba(254, 243, 199, 0.15); border-color: rgba(254, 243, 199, 0.35); } /\* KPI STRIP — volume counters under the pills \*/ .doc-kpi-strip { display: flex; flex-wrap: wrap; gap: 18px; margin-top: 14px; padding-top: 12px; border-top: 1px solid rgba(255, 255, 255, 0.18); font-size: 9pt; color: rgba(255, 255, 255, 0.92); } .doc-kpi-strip .doc-kpi { display: inline-flex; align-items: center; gap: 5px; white-space: nowrap; } .doc-kpi-strip .doc-kpi-icon { font-size: 10.5pt; } .doc-kpi-strip .doc-kpi-value { font-weight: 700; color: #ffffff; } .doc-kpi-strip .doc-kpi-label { color: rgba(255, 255, 255, 0.78); } /\* PHASE TIMELINE \*/ .phase { border-left: 3px solid #7fb3e0; padding: 10px 16px; margin: 10px 0; background: #f7f8fa; } .phase strong { color: #003366; } .phase .phase-dur { color: #1a5c8a; font-size: 9pt; } /\* DOC FOOTER (inside wrapper) \*/ .doc-footer { background: #f7f8fa; border-top: 1px solid #d0d4d8; padding: 16px 36px; font-size: 9pt; color: #555; } .doc-footer table { width: 100%; } .doc-footer .footer-right { text-align: right; color: #003366; font-weight: 600; } @media print { body { background: white; } .doc-wrapper { box-shadow: none; border: none; margin: 0; max-width: 100%; } h2, h3 { page-break-after: avoid; } table.data { page-break-inside: avoid; } .phase, .callout { page-break-inside: avoid; } }

![C16](data:image/png;base64,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)

Reference

# FS ZCL VENDOR BANK VALIDATOR 2026 10 23

Topic

FS ZCL VENDOR BANK VALIDATOR 2026 10 23

Date

23 October 2026

Audience

CIOs, SAP program leaders, transformation architects

Author

C16 — AI for SAP operational efficiency

Scope

Version

1.0

## 1 Business Objective

Vendor bank detail accuracy is critical to the integrity of the Accounts Payable payment cycle. Incorrect bank country codes, malformed bank keys, or invalid account numbers cause payment run failures, returned payments, and bank reconciliation exceptions. Today, validation of vendor bank details is performed ad-hoc across multiple custom programs and user exit routines, leading to inconsistent checks and duplicated logic.

The purpose of this utility class (**ZCL\_VENDOR\_BANK\_VALIDATOR**) is to provide a **single, reusable ABAP class** that centralises all validation and formatting logic for vendor bank details — bank country, bank key, and account number — so that any consuming program (vendor master maintenance, payment processing, data migration, or mass-update tools) can call one consistent API and receive standardised, auditable results.

### Scope

In Scope

Out of Scope

Validate bank country against SAP country master (T005)

Creating or modifying bank master records (BNKA)

Validate bank key existence in bank directory (BNKA)

Payment run execution or payment medium generation

Validate bank key length per country rules (T005-LNBLZ)

SEPA mandate management

Validate account number length per country rules (T005-LNBKN)

Bank statement processing

IBAN construction and check-digit validation (ISO 13616)

Electronic banking / payment file formatting

Format/normalise bank key and account number (leading zeros, trim)

Vendor master creation or update transactions (FK01/FK02)

Return structured validation result with messages

Authorization management or role assignment

## 2 Key Features and Functionality

### KF-001 — Bank Country Validation

**Purpose:** Confirm that the supplied bank country code is a valid, active country maintained in SAP.

**Method:** The class receives a bank country value (TYPE `BANKS`, CHAR 3). It performs a lookup against table **T005** (Country master) to verify the country code exists. If the country is flagged for deletion or does not exist, a structured error message is returned. On success, the country-specific bank key length (`T005-LNBLZ`) and account number length (`T005-LNBKN`) are cached for downstream validations KF-002 and KF-003.

### KF-002 — Bank Key Validation

**Purpose:** Confirm that the bank key (routing number / sort code / BLZ) is structurally correct and exists in the SAP bank directory.

**Method:**

*   **Length check:** The bank key (TYPE `BANKK`, CHAR 15) is validated against the country-specific maximum length stored in `T005-LNBLZ`. For example, Germany (DE) requires exactly 8 digits; the US requires 9 digits; the UK requires 6 digits; India allows up to 15 characters.
*   **Character check:** For countries that use purely numeric bank keys (DE, US, FR), the class verifies the bank key contains only digits. For countries with alphanumeric keys (IN, GB), alphanumeric characters are accepted.
*   **Existence check:** A lookup against table **BNKA** (Bank master) using the composite key `BANKS` + `BANKL` confirms the bank exists in the SAP bank directory. If not found, a warning (not an error) is returned — some organisations maintain vendors with banks not yet in BNKA. The caller decides severity.
*   **SWIFT/BIC enrichment:** If the bank exists in BNKA and has a populated `SWIFT` field, the SWIFT code is returned alongside the validation result for informational use by the caller.

### KF-003 — Account Number Validation

**Purpose:** Confirm that the vendor's bank account number is structurally valid for the given country.

**Method:**

*   **Length check:** The account number (TYPE `BANKN`, CHAR 18) is validated against the country-specific maximum length from `T005-LNBKN`. For example, DE allows up to 14 characters; US up to 13; GB up to 8; FR up to 11.
*   **Non-blank check:** An empty or all-spaces account number is rejected with an error.
*   **Character validation:** The class checks that the account number conforms to the character rules for the country (numeric-only for DE/US, alphanumeric for GB/IN).

### KF-004 — IBAN Construction and Validation

**Purpose:** For SEPA/IBAN-mandatory countries, construct the IBAN from bank country + bank key + account number, and validate its check digits per ISO 13616.

**Method:**

*   **IBAN construction:** The class assembles the IBAN from the country code (2 chars) + check digits (2 chars, computed per ISO 13616 Mod-97) + BBAN (bank key + account number, padded per country rules).
*   **Check-digit verification:** If the caller supplies a pre-existing IBAN (e.g. from table **TIBAN**), the class recalculates the check digits and compares. A mismatch produces an error.
*   **Cross-reference:** If an IBAN is constructed, the class optionally checks whether a matching entry exists in table **TIBAN** and returns the match status.

### KF-005 — Bank Detail Formatting and Normalisation

**Purpose:** Apply consistent formatting to bank keys and account numbers before storage or comparison.

**Method:**

*   **Leading-zero padding:** For numeric-only bank keys (DE, US, FR), pad with leading zeros to the country-required length.
*   **Trim and uppercase:** Remove leading/trailing whitespace from all fields. Convert bank country and bank key to uppercase.
*   **Account number normalisation:** Strip internal hyphens/dashes and spaces that users sometimes enter. Left-pad numeric account numbers with zeros to country-required length.

### KF-006 — Structured Validation Result

**Purpose:** Return a comprehensive, machine-readable validation result so that any consuming program can evaluate the outcome without parsing free text.

**Method:** The class returns a structure containing:

Field

Type

Description

VALID

ABAP\_BOOL

Overall pass/fail indicator (ABAP\_TRUE / ABAP\_FALSE)

BANKS\_VALID

ABAP\_BOOL

Bank country validation passed

BANKL\_VALID

ABAP\_BOOL

Bank key validation passed

BANKN\_VALID

ABAP\_BOOL

Account number validation passed

IBAN\_VALID

ABAP\_BOOL

IBAN validation passed (if applicable)

BANKS\_FORMATTED

BANKS (CHAR 3)

Normalised bank country code

BANKL\_FORMATTED

BANKK (CHAR 15)

Formatted bank key

BANKN\_FORMATTED

BANKN (CHAR 18)

Formatted account number

IBAN

IBAN (CHAR 34)

Constructed or validated IBAN

SWIFT

SWIFT (CHAR 11)

SWIFT/BIC code if found in BNKA

BANK\_NAME

BANKA (CHAR 60)

Bank name from BNKA (if bank exists)

MESSAGES

Table of BAPIRET2

Detailed validation messages (E/W/I/S)

## 3 Business Rules

### BR-001 — Country Code Must Exist in T005

**Key Features Addressed:** KF-001 (Bank Country Validation)

**Rule:** The bank country code supplied to the class must exist as an active record in table T005. If the country does not exist, the validation result is set to VALID = ABAP\_FALSE and an error message of type 'E' is appended to the MESSAGES table: _"Bank country '&1' is not maintained in the system"_.

**Implementation:** Perform `SELECT SINGLE LNBLZ LNBKN FROM T005 WHERE LAND1 = iv_banks`. If `sy-subrc <> 0`, set `BANKS_VALID = ABAP_FALSE` and append message. If found, cache LNBLZ and LNBKN for use in BR-002 and BR-003.

### BR-002 — Bank Key Length Per Country

**Key Features Addressed:** KF-002 (Bank Key Validation)

**Rule:** The bank key must not exceed the country-specific length defined in `T005-LNBLZ`. Country-specific lengths observed in the live system:

Country

LNBLZ (Max Bank Key Length)

Format

DE (Germany)

8

Numeric only

US (United States)

9

Numeric only

GB (United Kingdom)

6

Numeric only

FR (France)

10

Numeric only

IN (India)

15

Alphanumeric (IFSC code)

**Implementation:** If `strlen( iv_bankl ) > lv_lnblz`, set `BANKL_VALID = ABAP_FALSE` and append message: _"Bank key '&1' exceeds maximum length &2 for country &3"_. If `LNBLZ = '00'` (no length restriction), skip the length check.

### BR-003 — Account Number Length Per Country

**Key Features Addressed:** KF-003 (Account Number Validation)

**Rule:** The account number must not exceed the country-specific length defined in `T005-LNBKN`. Observed lengths:

Country

LNBKN (Max Account Number Length)

DE (Germany)

14

US (United States)

13

GB (United Kingdom)

8

FR (France)

11

IN (India)

No restriction (LNBKN = 00)

**Implementation:** If `strlen( iv_bankn ) > lv_lnbkn` and `lv_lnbkn > 0`, set `BANKN_VALID = ABAP_FALSE` and append message: _"Account number '&1' exceeds maximum length &2 for country &3"_.

### BR-004 — Bank Key Must Exist in Bank Directory

**Key Features Addressed:** KF-002 (Bank Key Validation)

**Rule:** The bank key is looked up in table BNKA using the composite key BANKS + BANKL. If not found, a **warning** (type 'W') is issued — not an error — because some organisations permit vendor bank details for banks not yet loaded into BNKA. The caller decides whether to treat the warning as a hard stop. If found, the bank name (BANKA) and SWIFT code are populated in the result.

**Implementation:** `SELECT SINGLE BANKA SWIFT FROM BNKA WHERE BANKS = iv_banks AND BANKL = iv_bankl`. If `sy-subrc <> 0`, append warning: _"Bank key '&1' in country '&2' not found in bank directory"_.

### BR-005 — Account Number Must Not Be Empty

**Key Features Addressed:** KF-003 (Account Number Validation)

**Rule:** A blank or initial account number is always rejected. An error message is appended: _"Account number must not be empty"_.

### BR-006 — IBAN Mod-97 Check Digit Validation

**Key Features Addressed:** KF-004 (IBAN Construction and Validation)

**Rule:** When constructing or validating an IBAN, the ISO 13616 Mod-97 algorithm is applied: move the first 4 characters to the end, convert letters to digits (A=10, B=11, … Z=35), compute modulo 97, and verify the result equals 1. If the check fails, set `IBAN_VALID = ABAP_FALSE` and append error: _"IBAN check digit validation failed for '&1'"_.

### BR-007 — Formatting Normalisation Rules

**Key Features Addressed:** KF-005 (Bank Detail Formatting)

**Rule:** Before any validation, the input values are normalised:

*   Leading and trailing whitespace is removed from all input fields.
*   Bank country is converted to uppercase.
*   Hyphens, dashes, and embedded spaces are removed from bank key and account number.
*   For countries with numeric-only bank keys: left-pad with zeros to the country-required length.
*   For countries with numeric-only account numbers: left-pad with zeros to the country-required length.

The formatted values are always returned in the result, even if validation fails, so the caller can see what the class normalised.

## 4 Process Flow

#mermaid-1792739308291{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1792739308291 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1792739308291 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1792739308291 .error-icon{fill:#552222;}#mermaid-1792739308291 .error-text{fill:#552222;stroke:#552222;}#mermaid-1792739308291 .edge-thickness-normal{stroke-width:1px;}#mermaid-1792739308291 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1792739308291 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1792739308291 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1792739308291 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1792739308291 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1792739308291 .marker{fill:#666;stroke:#666;}#mermaid-1792739308291 .marker.cross{stroke:#666;}#mermaid-1792739308291 svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-1792739308291 p{margin:0;}#mermaid-1792739308291 .label{font-family:"trebuchet ms",verdana,arial,sans-serif;color:#000000;}#mermaid-1792739308291 .cluster-label text{fill:#333;}#mermaid-1792739308291 .cluster-label span{color:#333;}#mermaid-1792739308291 .cluster-label span p{background-color:transparent;}#mermaid-1792739308291 .label text,#mermaid-1792739308291 span{fill:#000000;color:#000000;}#mermaid-1792739308291 .node rect,#mermaid-1792739308291 .node circle,#mermaid-1792739308291 .node ellipse,#mermaid-1792739308291 .node polygon,#mermaid-1792739308291 .node path{fill:#eee;stroke:#999;stroke-width:1px;}#mermaid-1792739308291 .rough-node .label text,#mermaid-1792739308291 .node .label text,#mermaid-1792739308291 .image-shape .label,#mermaid-1792739308291 .icon-shape .label{text-anchor:middle;}#mermaid-1792739308291 .node .katex path{fill:#000;stroke:#000;stroke-width:1px;}#mermaid-1792739308291 .rough-node .label,#mermaid-1792739308291 .node .label,#mermaid-1792739308291 .image-shape .label,#mermaid-1792739308291 .icon-shape .label{text-align:center;}#mermaid-1792739308291 .node.clickable{cursor:pointer;}#mermaid-1792739308291 .root .anchor path{fill:#666!important;stroke-width:0;stroke:#666;}#mermaid-1792739308291 .arrowheadPath{fill:#333333;}#mermaid-1792739308291 .edgePath .path{stroke:#666;stroke-width:2.0px;}#mermaid-1792739308291 .flowchart-link{stroke:#666;fill:none;}#mermaid-1792739308291 .edgeLabel{background-color:white;text-align:center;}#mermaid-1792739308291 .edgeLabel p{background-color:white;}#mermaid-1792739308291 .edgeLabel rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1792739308291 .labelBkg{background-color:rgba(255, 255, 255, 0.5);}#mermaid-1792739308291 .cluster rect{fill:hsl(0, 0%, 98.9215686275%);stroke:#707070;stroke-width:1px;}#mermaid-1792739308291 .cluster text{fill:#333;}#mermaid-1792739308291 .cluster span{color:#333;}#mermaid-1792739308291 div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:12px;background:hsl(-160, 0%, 93.3333333333%);border:1px solid #707070;border-radius:2px;pointer-events:none;z-index:100;}#mermaid-1792739308291 .flowchartTitleText{text-anchor:middle;font-size:18px;fill:#000000;}#mermaid-1792739308291 rect.text{fill:none;stroke-width:0;}#mermaid-1792739308291 .icon-shape,#mermaid-1792739308291 .image-shape{background-color:white;text-align:center;}#mermaid-1792739308291 .icon-shape p,#mermaid-1792739308291 .image-shape p{background-color:white;padding:2px;}#mermaid-1792739308291 .icon-shape .label rect,#mermaid-1792739308291 .image-shape .label rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1792739308291 .label-icon{display:inline-block;height:1em;overflow:visible;vertical-align:-0.125em;}#mermaid-1792739308291 .node .label-icon path{fill:currentColor;stroke:revert;stroke-width:revert;}#mermaid-1792739308291 :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}

No

Yes

Yes

No

Caller invokes VALIDATE method  
Input: BANKS, BANKL, BANKN, optional IBAN

Step 1: Normalise & Format  
(Trim, uppercase, strip hyphens,  
left-pad zeros)

Step 2: Validate Bank Country  
(T005 lookup → LNBLZ, LNBKN)

Country  
found?

Set BANKS\_VALID = FALSE  
Append error message  
Set VALID = FALSE

Step 3: Validate Bank Key  
(Length check vs LNBLZ,  
character check,  
BNKA existence check)

Step 4: Validate Account Number  
(Length check vs LNBKN,  
non-blank check,  
character check)

IBAN-mandatory  
country or  
IBAN supplied?

Step 5: Construct/Validate IBAN  
(ISO 13616 Mod-97,  
TIBAN cross-reference)

Skip IBAN processing

Step 6: Assemble Result  
(Merge all flags, formatted values,  
enriched bank name / SWIFT,  
messages)

Return Validation Result  
to Caller

## 5 Data Model

### 5.1 SAP Tables Read

Table

Description

Fields Used

Purpose

T005

Country master

LAND1, LNBLZ, LNBKN

Country-specific bank key and account number length rules

BNKA

Bank master

BANKS, BANKL, BANKA, SWIFT, ORT01, STRAS

Bank existence check, bank name and SWIFT enrichment

TIBAN

IBAN directory

BANKS, BANKL, BANKN, IBAN

IBAN cross-reference validation

LFBK

Vendor bank details

LIFNR, BANKS, BANKL, BANKN, BKONT, KOINH

Reference — consuming programs read vendor bank data from LFBK and pass it to this class

### 5.2 Class Interface

**Class name:** `ZCL_VENDOR_BANK_VALIDATOR`

### Public Methods

Method

Parameters

Direction

Type

Description

VALIDATE

IV\_BANKS

Importing

BANKS (CHAR 3)

Bank country code

IV\_BANKL

Importing

BANKK (CHAR 15)

Bank key / routing number

IV\_BANKN

Importing

BANKN (CHAR 18)

Bank account number

IV\_IBAN

Importing (optional)

IBAN (CHAR 34)

Pre-existing IBAN to validate (optional)

RS\_RESULT

Returning

ZS\_BANK\_VALIDATION\_RESULT

Structured validation result (see KF-006)

FORMAT

IV\_BANKS

Importing

BANKS (CHAR 3)

Bank country code

IV\_BANKL

Changing

BANKK (CHAR 15)

Bank key — formatted in place

IV\_BANKN

Changing

BANKN (CHAR 18)

Account number — formatted in place

CHECK\_IBAN

IV\_IBAN

Importing

IBAN (CHAR 34)

IBAN to validate

RV\_VALID

Returning

ABAP\_BOOL

ABAP\_TRUE if IBAN check digits are correct

ET\_MESSAGES

Exporting

BAPIRET2\_T

Validation messages

CONSTRUCT\_IBAN

IV\_BANKS

Importing

BANKS (CHAR 3)

Bank country code

IV\_BANKL

Importing

BANKK (CHAR 15)

Bank key

IV\_BANKN

Importing

BANKN (CHAR 18)

Account number

RV\_IBAN

Returning

IBAN (CHAR 34)

Constructed IBAN (empty if construction fails)

### 5.3 Custom Structure: ZS\_BANK\_VALIDATION\_RESULT

Component

Data Element / Type

Length

Description

VALID

ABAP\_BOOL

1

Overall validation passed (X = yes)

BANKS\_VALID

ABAP\_BOOL

1

Country validation passed

BANKL\_VALID

ABAP\_BOOL

1

Bank key validation passed

BANKN\_VALID

ABAP\_BOOL

1

Account number validation passed

IBAN\_VALID

ABAP\_BOOL

1

IBAN validation passed

BANKS\_FORMATTED

BANKS

3

Normalised bank country

BANKL\_FORMATTED

BANKK

15

Formatted bank key

BANKN\_FORMATTED

BANKN

18

Formatted account number

IBAN

IBAN

34

IBAN (constructed or validated)

SWIFT

SWIFT

11

SWIFT/BIC from bank directory

BANK\_NAME

BANKA

60

Bank name from BNKA

BANK\_CITY

ORT01\_GP

35

Bank city from BNKA

MESSAGES

BAPIRET2\_T

Table

All validation messages (E/W/I/S)

## 6 Assumptions

*   Table **T005** (Country master) is fully maintained with correct LNBLZ and LNBKN values for all countries where vendor payments are processed.
*   Table **BNKA** (Bank directory) is kept current — either loaded from an external bank data provider (e.g. Accuity, SIX) or manually maintained by the Treasury / Banking team.
*   Table **TIBAN** is maintained for vendors where IBAN validation or cross-referencing is required.
*   The class is called with a single set of bank details per invocation. Bulk / mass validation is the responsibility of the consuming program, which loops over vendor records (LFBK) and calls the class for each row.
*   The IBAN construction logic covers the European SEPA countries and common international formats. Countries with non-standard BBAN structures may require future extension.
*   Character-type rules (numeric-only vs. alphanumeric) for each country are configured as constants within the class. If new countries are onboarded, these constants must be extended.
*   The target system is SAP ECC 7.40 (SAP\_BASIS 740). The class uses ECC 7.40-compatible ABAP syntax only — no RAP, no CDS, no AMDP, no typed enums.

## 7 Dependencies

Dependency

Description

Impact

Country master (T005)

Must contain LNBLZ and LNBKN for all payment-relevant countries

Missing country data causes the class to reject valid bank details

Bank directory (BNKA)

Must be loaded and current

Missing bank records produce warnings — tolerable but degrades enrichment (no SWIFT, no bank name)

BAPI\_BANK\_GETDETAIL

Standard BAPI in function group 1011 — available on the connected system. The class may optionally delegate bank existence checks to this BAPI instead of direct BNKA reads.

If using BAPI delegation, the BAPI must be available and callable by the service user

Consuming programs

Any program that reads LFBK, performs data migration, or runs payment proposals can call this class

The class does not maintain data — it only validates and formats

## 8 Security

### Authorization Requirements

The utility class performs **read-only** operations against configuration and master data tables. No write operations are performed. Authorization checks are the responsibility of the **calling program**, not this utility class.

Role

Authorization Object

Fields

Notes

Vendor Master Viewer

F\_LFA1\_BUK

BUKRS, ACTVT (03 = Display)

Required by the calling program to read LFBK vendor bank details

Bank Master Viewer

F\_BNKA\_BUK

BUKRS, ACTVT (03 = Display)

Required to read BNKA bank directory. The utility class reads BNKA — the caller must ensure this authorization is held.

Payment Administrator

F\_REGU\_BUK

BUKRS, ACTVT

Not required by this class, but relevant for consuming programs that process payments after validation

**Note:** The utility class itself does not perform AUTHORITY-CHECK statements. It is a pure validation/formatting service. The responsibility for authorization enforcement lies with the calling program before invoking the class.

## 9 Test Design

### Functional Tests — Positive Cases

#

Test Name

Input

Expected Result

Features Covered

T-001

Valid German bank details

BANKS=DE, BANKL=30080000, BANKN=1234321

VALID=X, all sub-flags=X, BANKL\_FORMATTED=30080000 (8 digits, zero-padded), bank name populated from BNKA

KF-001, KF-002, KF-003, KF-005

T-002

Valid French bank details

BANKS=FR, BANKL=3000200650, BANKN=11111111111

VALID=X, BANKL length ≤ 10, BANKN length ≤ 11

KF-001, KF-002, KF-003

T-003

Valid US bank details

BANKS=US, BANKL=021000021, BANKN=1234567890123

VALID=X, BANKL length ≤ 9, BANKN length ≤ 13

KF-001, KF-002, KF-003

T-004

Valid Indian bank (alphanumeric IFSC)

BANKS=IN, BANKL=SBIN0001234, BANKN=1234567890

VALID=X, alphanumeric bank key accepted, LNBKN=00 → no account length restriction

KF-001, KF-002, KF-003

T-005

Valid IBAN check digit

IBAN=AE750350000000123456789

IBAN\_VALID=X, Mod-97 check passes

KF-004

T-006

IBAN construction from components

BANKS=AE, BANKL=60351010, BANKN=0123456789

Constructed IBAN matches TIBAN record AE750350000000123456789

KF-004

T-007

Formatting with leading spaces

BANKS=' de ', BANKL=' 1234 ', BANKN=' 567 '

BANKS\_FORMATTED=DE, BANKL trimmed and zero-padded, BANKN trimmed and zero-padded

KF-005

### Functional Tests — Negative Cases

#

Test Name

Input

Expected Result

Rules Covered

T-008

Invalid country code

BANKS=ZZ, BANKL=12345, BANKN=67890

VALID=FALSE, BANKS\_VALID=FALSE, error message "Bank country 'ZZ' is not maintained"

BR-001

T-009

Bank key too long for DE

BANKS=DE, BANKL=123456789 (9 digits), BANKN=1234

VALID=FALSE, BANKL\_VALID=FALSE, error "exceeds maximum length 8 for country DE"

BR-002

T-010

Account number too long for GB

BANKS=GB, BANKL=123456, BANKN=123456789 (9 digits)

VALID=FALSE, BANKN\_VALID=FALSE, error "exceeds maximum length 8 for country GB"

BR-003

T-011

Bank key not in BNKA

BANKS=DE, BANKL=99999999, BANKN=1234

VALID=TRUE (warning only), BANKL\_VALID=TRUE, warning message "not found in bank directory"

BR-004

T-012

Empty account number

BANKS=DE, BANKL=30080000, BANKN='' (blank)

VALID=FALSE, BANKN\_VALID=FALSE, error "Account number must not be empty"

BR-005

T-013

Invalid IBAN check digit

IBAN=DE00300800001234321 (wrong check digits)

IBAN\_VALID=FALSE, error "IBAN check digit validation failed"

BR-006

T-014

Non-numeric bank key for DE

BANKS=DE, BANKL=ABCD1234, BANKN=5678

VALID=FALSE, BANKL\_VALID=FALSE, error "Bank key must be numeric for country DE"

BR-002

T-015

All fields empty

BANKS='', BANKL='', BANKN=''

VALID=FALSE, all sub-flags FALSE, multiple error messages

BR-001, BR-005

### Boundary / Edge Cases

#

Test Name

Input

Expected Result

Notes

T-016

Bank key at exact max length

BANKS=DE, BANKL=12345678 (exactly 8)

BANKL\_VALID=TRUE — boundary length accepted

Boundary for BR-002

T-017

Account with embedded hyphens

BANKS=US, BANKL=021000021, BANKN=123-456-7890

Hyphens stripped, BANKN\_FORMATTED=1234567890, validated as 10 digits ≤ 13

BR-007 formatting

T-018

Country with no length restriction (IN)

BANKS=IN, BANKL=SBIN0001234, BANKN=12345678901234567 (17 chars)

BANKN\_VALID=TRUE — LNBKN=00 means no restriction

Boundary for BR-003

T-019

Lowercase country code

BANKS='de', BANKL=30080000, BANKN=1234

BANKS\_FORMATTED=DE, validation proceeds normally

BR-007 normalisation

## 10 Appendix — Live System Data Samples

### A. Bank Directory Sample (BNKA)

10 records from the connected ECC system (client 800) confirming table availability and data patterns:

Country

Bank Key

Bank Name

SWIFT

City

Street

AD

AD1

th goa main

AE

9345

SBI

AR

1200

Banco Citibank

Sarmiento 244

AR

20050000

Citibank

Buenos Aires

Florida 280

AT

10010

Deutsche Bank

Wien

Uferstraße 122

### B. Vendor Bank Details Sample (LFBK)

Vendor

Country

Bank Key

Account Number

Control Key

0000000001

DE

56565656

88888888

0000000010

FR

3000200650

11111111111

11

0000000025

DK

1234

12345678

0000000100

DE

30080000

1234321

0000000200

DE

23022200

98765896

### C. Country-Specific Length Rules (T005)

Country

Bank Key Max Length (LNBLZ)

Account No. Max Length (LNBKN)

DE

8

14

FR

10

11

GB

6

8

IN

15

No restriction (00)

US

9

13

**C16 — AI for SAP operational efficiency**  |  Document version 1.0  |  23 October 2026

C16.ai

**Disclaimer & Important Notices**

**1.  AI-Generated Content.** This document was generated by **C16**, an automated AI-powered SAP analysis platform operated by **PEOL Technologies Private Limited**, based on data sourced from the connected SAP system at the time of generation. The contents have not been individually reviewed by a human consultant prior to publication.

**2.  Validation Required; Customer Responsibility.** All findings, scores, classifications, recommendations, timelines, and roadmap items are **advisory in nature** and must be reviewed and validated by qualified SAP functional and technical subject-matter experts before any action is taken. Migration, remediation, configuration, and implementation decisions remain the **sole responsibility of the customer**.

**3.  Demonstration System Notice.** Where this document was produced from an **IDES, sandbox, training, or demonstration** SAP system, the configurations, data volumes, transactions, and custom objects analysed do not represent any real production customer environment. Such content is provided for **illustration and template purposes only**; actual findings, scores, and recommendations in a customer engagement will vary materially.

**4.  No Warranty; No Liability.** This document is provided **“as is.”** PEOL Technologies Private Limited makes no representation or warranty of any kind, express or implied, including (without limitation) any warranty as to accuracy, completeness, merchantability, non-infringement, or fitness for a particular purpose. In no event shall PEOL Technologies Private Limited be liable for any direct, indirect, incidental, consequential, or special damages arising from the use of, or reliance upon, this document.

**5.  SAP Trademarks & Partnership.** _SAP_, _SAP S/4HANA_, _SAP ECC_, _SAP ERP_, _ABAP_, _SAP HANA_, _SAP Fiori_, _BAPI_, _BAdI_, _Business Partner_, and other SAP product names referenced in this document are trademarks or registered trademarks of **SAP SE** in Germany and other countries. **PEOL Technologies Private Limited is an SAP Partner; C16 is PEOL’s own product, not an SAP product.** References to SAP products, transactions, tables, notes, and methodologies are made solely for analytical and educational purposes.

**6.  Confidentiality.** Where this document contains customer-specific information, it is **confidential** and intended solely for the named recipient. It may not be reproduced, distributed, or disclosed to any third party without the prior written consent of PEOL Technologies Private Limited.

**7.  Copyright.** © 2026 PEOL Technologies Private Limited. All rights reserved. “C16”, “C16.ai”, and the C16 logo are trademarks of PEOL Technologies Private Limited.