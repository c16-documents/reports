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

## 1 Document Control

Item

Value

Document

Functional Specification: Vendor Bank Details Validation & Formatting Utility

Object (proposed)

`ZCL_VENDOR_BANK_VALIDATOR` (global ABAP class). Exception class proposed: `ZCX_VENDOR_BANK_ERROR`

Object type

Reusable utility class (no UI, no transaction, no database writes)

Module

FI-AP / MM vendor master (bank data)

Target system

SAP ECC, SAP\_BASIS 740, client 800. Design is compatible with SAP\_BASIS 740 (no CDS-in-ABAP, AMDP, RAP or enums)

Version / Date

1.0 Draft, 23-Oct-2026

Status

Draft for business review

No FS template is uploaded, so this document uses the standard C16 FS layout. The class name is a proposal. No custom class with this name exists yet: a search for `ZCL%BANK%` returned 14 unrelated objects, mostly OData DPC/MPC classes and training classes.

## 2 Business Background & Objective

Several programs and interfaces create or check vendor bank details: vendor uploads, payment-run pre-checks, interface inbound validation and data-quality reports. Each one re-implements its own checks today, or skips them. The result is inconsistent bank data in the vendor master (table `LFBK`). That leads to rejected payment files and manual rework in Accounts Payable.

The objective is **one central, reusable class** that any custom program can call to:

1.  **Validate** a vendor's bank country, bank key and bank account number against the country rules configured in SAP (OY17 / table `T005`) and against the bank master (FI01 / table `BNKA`).
2.  **Format** these values consistently: normalised for storage, masked for display, and as IBAN where the country supports it.
3.  Return **clear, translatable messages** that the caller can show, log or reject on.

## 3 Current-State Evidence (live system, client 800)

### 3.1 Volume

Vendor bank records (LFBK)

Countries in sample

Bank master hits for sample keys

1,231

DE, FR, DK, IN

14 BNKA rows (same key under several countries)

### 3.2 Sample vendor bank records (LFBK, first 15 rows)

Vendor

Bank Country

Bank Key

Bank Account

Control key

Observation

_(blank)_

_(blank)_

_(blank)_

_(blank)_

Empty record: no vendor, no bank data

_(blank)_

IN

B 111

8888777788787

No vendor. Bank key contains a gap and is not in BNKA

0000000001

DE

56565656

88888888

Valid against DE rules; bank exists

0000000008

DE

50000001

21214343

Valid; bank "Eurobank" exists

0000000010

FR

3000200650

11111111111

11

Length rules OK; uses control key (RIB key)

0000000025

DK

1234

12345678

Bank "Danske Bank A/S" exists; SWIFT DABADKKK

0000000100

DE

30080000

1234321

Valid (7-digit account ≤ 14)

0000000111

DE

23022200

1234567

Valid

0000000200

DE

23022200

98765896

Valid

0000000300

DE

20050000

8484636

Valid. Key 20050000 also exists under AR (Citibank)

0000001000

DE

10050033

90010000

Valid (vendor has 2 bank records)

0000001000

DE

19652993

10003299

Valid

0000001001

DE

50020200

35471446

Valid

0000001002

DE

23984899

12345678

Valid; account holder maintained

0000001003

DE

23984899

564839

Valid

### 3.3 Country check rules configured (T005, OY17)

Country

Bank Key type (BNKEY)

Bank key length / rule

Bank number length / rule

Account length / rule

Bank data flag (XPRBK)

DE

1 – Bank number

00 / –

08 / 4

14 / 2

X

AT

1 – Bank number

00 / –

05 / 4

11 / 2

X

FR

1 – Bank number

00 / –

10 / 4

11 / 3

IT

1 – Bank number

00 / –

10 / 4

12 / 5

X

ES

1 – Bank number

00 / –

08 / 4

10 / 4

X

GB

1 – Bank number

00 / –

06 / 1

08 / 1

US

1 – Bank number

00 / –

09 / 4

13 / 0

CA

1 – Bank number

10 / 5

10 / 5

10 / 5

CH

1 – Bank number

07 / 2

07 / 2

18 / 5

X

BE

4 – Assign externally

03 / 3

00 / –

14 / 3

X

NL

4 – Assign externally

05 / 1

00 / –

10 / 4

X

IN

4 – Assign externally

11 / 1

15 / 5

00 / –

### 3.4 Check-rule values (domain PR005)

Rule

Meaning (DDIC text)

Utility behaviour

1

Maximum value length, without gaps

len ≤ L; no blanks

2

Maximum value length, numerical, without gaps

len ≤ L; digits only

3

Length to be kept to exactly, without gaps

len = L; no blanks

4

Length to be kept to exactly, numerical, without gaps

len = L; digits only

5

Maximum value length

len ≤ L (blanks allowed)

6

Maximum value length, numerical

len ≤ L; digits and blanks only

7

Length to be kept to exactly

len = L

8

Length to be kept to exactly, numerical

len = L; digits and blanks only

9

Check against country-specific edit format

Delegate to the SAP standard check (see FR-07)

0 / blank

No check (0 is "Deactivate check" for USA)

Skip the rule check (length L is still informative only)

**Findings that justify this utility:** (1) There are LFBK records with no vendor number, one of them fully blank. (2) The IN record uses bank key `B 111`, which breaks the IN rule 1 ("without gaps") and has no BNKA entry. (3) The same bank key (e.g. `20050000`, `1234`) exists under several countries (DE/AR, DK/IN/UG). The bank key is only unique **together with the bank country**, so every lookup must use both.

## 4 Scope

### 4.1 In scope

*   Validation of bank country (`BANKS`), bank key (`BANKL`), bank account (`BANKN`) and, optionally, bank control key (`BKONT`).
*   Normalisation (storage format), display formatting (masked and full) and IBAN derivation.
*   A single "validate all" call that returns every finding at once, so the caller does not stop at the first error.
*   Read-only access to the configuration and master data in `T005`, `BNKA`, `TIBAN` and `LFBK`.

### 4.2 Out of scope

*   Creating or changing vendor master or bank master data. The class never writes to the database.
*   Payment-medium formats (DMEE), house-bank data and customer bank data. The design could be extended to `KNBK` later.
*   Any UI, selection screen or report. Callers own the presentation.
*   External bank-directory or IBAN web-service lookups.

## 5 Data Objects Used (DDIC-verified)

Table

Field

Data element

Label (DD04T)

Type / length

Use

LFBK

LIFNR

LIFNR

Vendor

CHAR 10

Vendor-level check (optional input)

LFBK

BANKS

BANKS

Bank Country

CHAR 3

Input

LFBK

BANKL

BANKK

Bank Key

CHAR 15

Input

LFBK

BANKN

BANKN

Bank Account

CHAR 18

Input

LFBK

BKONT

BKONT

Bank control key

CHAR 2

Optional input (IBAN / FR, ES, IT)

LFBK

BKREF

BKREF

Reference details

CHAR 20

Overflow for accounts over 18 characters (information only)

LFBK

KOINH

KOINH\_FI

Account holder

CHAR 60

Optional completeness warning

T005

BNKEY

BNKEY

Bank Key

CHAR 1

How the bank key is assigned (1 = bank number, 4 = external, …)

T005

LNBKS / PRBKS

LNBKS\_005 / PRBKS\_005

Length of Bank Key / Check rule for bank key

NUMC 2 / CHAR 1

Bank key rule

T005

LNBLZ / PRBLZ

LNBLZ\_005 / PRBLZ\_005

Bank number length / Check rule for bank number

NUMC 2 / CHAR 1

Bank number rule (applies to the key when BNKEY = 1)

T005

LNBKN / PRBKN

LNBKN\_005 / PRBKN\_005

Bank account number length / Check rule for bank acct no.

NUMC 2 / CHAR 1

Account rule

T005

XPRBK

XPRBK\_005

Bank data

CHAR 1

Country needs additional country-specific bank checks

BNKA

BANKS, BANKL

BANKS, BANKK

Bank Country, Bank Key

CHAR 3, 15

Bank master existence (key = country + key)

BNKA

BANKA / SWIFT / BNKLZ

BANKA / SWIFT / BANKL

Bank name / SWIFT/BIC / Bank number

CHAR 60 / 11 / 15

Enrichment and IBAN input

BNKA

LOEVM

LOEVM

Deletion flag

CHAR 1

Reject banks flagged for deletion

TIBAN

IBAN, BANKS, BANKL, BANKN, BKONT

IBAN, …

IBAN

CHAR 34

Look up an IBAN already stored for the account

## 6 Functional Requirements

### 6.1 Validation requirements

ID

Requirement

Rule / logic

Severity on failure

FR-01

Bank country is mandatory and must exist

BANKS not initial and found in T005 (key LAND1). Input is converted to upper case first.

Error

FR-02

Bank key is mandatory

BANKL not initial after trimming.

Error

FR-03

Bank key format follows the country rule

If T005-BNKEY = 1 (bank key = bank number): apply LNBLZ/PRBLZ to the key. Otherwise apply LNBKS/PRBKS. Use the check-rule logic in §3.4.

Error

FR-04

Bank key exists in the bank master

Read BNKA with **BANKS + BANKL** (never BANKL alone). Not found → error. Found with LOEVM = 'X' → error "bank flagged for deletion".

Error

FR-05

Bank account is mandatory where the country uses accounts

If T005-LNBKN = 00 and PRBKN is blank (e.g. IN), the account is not rule-checked, but an empty account still gives a warning.

Error (Warning for LNBKN = 00)

FR-06

Bank account format follows the country rule

Apply LNBKN/PRBKN using the §3.4 logic. Rule 0 or blank → no check.

Error

FR-07

Country-specific standard checks

Call the SAP standard function `BANK_NUMBER_CHECK` (verified signature: BANK\_ACCOUNT, BANK\_COUNTRY, BANK\_NUMBER; exceptions DATA\_MISSING, NOT\_VALID) so SAP's own country algorithms also run. Required when rule = 9 or T005-XPRBK = 'X'; recommended always. Its exceptions are mapped to the class's own messages.

Error

FR-08

Control key plausibility

If BKONT is supplied: max 2 characters, no gaps. For countries that use control keys (e.g. FR, sample vendor 0000000010 with BKONT 11), a missing BKONT gives a warning.

Warning

FR-09

Vendor-level duplicate check (optional)

When a vendor (LIFNR) is supplied, report if the same BANKS + BANKL + BANKN already exists in LFBK for a _different_ vendor. This can point to fraud or a duplicate vendor.

Warning

FR-10

Collect all findings

`VALIDATE_ALL` runs every check and returns the complete list (no early exit), with an overall valid / invalid flag.

–

### 6.2 Formatting requirements

ID

Requirement

Example (from live data)

FR-11

**Normalise** for storage: convert country to upper case, trim leading and trailing blanks, remove common separators (space, "-", "/", ".") from the key and account _only when the country rule is "without gaps" or numerical_. No zero-padding unless the rule is "exact length, numerical" and the business enables padding (open point OP-02).

"de" → "DE"; "5656-5656" → "56565656"

FR-12

**Mask** the account for display: show only the last 4 characters and mask the rest with "\*". The mask length equals the original length.

"88888888" → "\*\*\*\*8888"

FR-13

**Display string**: "<country> / <bank key> / <account (masked by default)> – <bank name>"

"DE / 56565656 / \*\*\*\*8888 – City-Bank Hamburg"

FR-14

**IBAN**: first read TIBAN for an IBAN already stored for BANKS/BANKL/BANKN/BKONT. Otherwise derive it with the SAP standard function `CONVERT_BANK_ACCOUNT_2_IBAN` (verified: I\_BANK\_ACCOUNT, I\_BANK\_CONTROL\_KEY, I\_BANK\_COUNTRY, I\_BANK\_NUMBER = BNKA-BNKLZ, I\_BANK\_KEY; E\_IBAN; exception NO\_CONVERSION). If no conversion is possible, return an empty IBAN plus an information message, not an error.

DE / 56565656 / 88888888 → IBAN derived by the SAP standard algorithm

FR-15

**Bank details enrichment**: return bank name, SWIFT/BIC and bank number from BNKA.

DK / 1234 → "Danske Bank A/S", DABADKKK

FR-16

Formatting methods never change their input. They return new values.

–

## 7 Proposed Public Interface (functional view)

The developer finalises the exact signatures in the Technical Specification. All types refer to DDIC data elements (BANKS, BANKK, BANKN, BKONT, LIFNR, IBAN, BANKA, SWIFT, BAPIRET2).

Method

Inputs

Outputs

Purpose

`VALIDATE_ALL`

Bank country, bank key, bank account, control key (opt.), vendor (opt.)

Valid flag + message table (BAPIRET2)

Runs FR-01 to FR-10 in one call

`VALIDATE_BANK_COUNTRY`

Bank country

Valid flag + messages

FR-01

`VALIDATE_BANK_KEY`

Bank country, bank key

Valid flag + messages

FR-02 to FR-04

`VALIDATE_ACCOUNT_NUMBER`

Bank country, bank key, account, control key (opt.)

Valid flag + messages

FR-05 to FR-08

`NORMALIZE`

Bank country, bank key, account

Normalised values

FR-11

`MASK_ACCOUNT`

Account

Masked account

FR-12

`FORMAT_FOR_DISPLAY`

Bank country, bank key, account, show-full flag (default off)

Display string

FR-13

`GET_IBAN`

Bank country, bank key, account, control key

IBAN + messages

FR-14

`GET_BANK_DETAILS`

Bank country, bank key

Bank name, SWIFT/BIC, bank number, found flag

FR-15

**Testability (required):** All database reads (T005, BNKA, TIBAN, LFBK) sit behind a local data-access interface that is injected through the constructor. ABAP Unit tests can then supply fake configuration and edge-case rows. On SAP\_BASIS 740 the SQL test-double framework is not available, so a classic dependency-injection fake is required. Country rules are buffered per call sequence, with one T005 read per country per instance.

## 8 Processing Logic – `VALIDATE_ALL`

#mermaid-1792739274211{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1792739274211 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1792739274211 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1792739274211 .error-icon{fill:#552222;}#mermaid-1792739274211 .error-text{fill:#552222;stroke:#552222;}#mermaid-1792739274211 .edge-thickness-normal{stroke-width:1px;}#mermaid-1792739274211 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1792739274211 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1792739274211 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1792739274211 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1792739274211 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1792739274211 .marker{fill:#666;stroke:#666;}#mermaid-1792739274211 .marker.cross{stroke:#666;}#mermaid-1792739274211 svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-1792739274211 p{margin:0;}#mermaid-1792739274211 .label{font-family:"trebuchet ms",verdana,arial,sans-serif;color:#000000;}#mermaid-1792739274211 .cluster-label text{fill:#333;}#mermaid-1792739274211 .cluster-label span{color:#333;}#mermaid-1792739274211 .cluster-label span p{background-color:transparent;}#mermaid-1792739274211 .label text,#mermaid-1792739274211 span{fill:#000000;color:#000000;}#mermaid-1792739274211 .node rect,#mermaid-1792739274211 .node circle,#mermaid-1792739274211 .node ellipse,#mermaid-1792739274211 .node polygon,#mermaid-1792739274211 .node path{fill:#eee;stroke:#999;stroke-width:1px;}#mermaid-1792739274211 .rough-node .label text,#mermaid-1792739274211 .node .label text,#mermaid-1792739274211 .image-shape .label,#mermaid-1792739274211 .icon-shape .label{text-anchor:middle;}#mermaid-1792739274211 .node .katex path{fill:#000;stroke:#000;stroke-width:1px;}#mermaid-1792739274211 .rough-node .label,#mermaid-1792739274211 .node .label,#mermaid-1792739274211 .image-shape .label,#mermaid-1792739274211 .icon-shape .label{text-align:center;}#mermaid-1792739274211 .node.clickable{cursor:pointer;}#mermaid-1792739274211 .root .anchor path{fill:#666!important;stroke-width:0;stroke:#666;}#mermaid-1792739274211 .arrowheadPath{fill:#333333;}#mermaid-1792739274211 .edgePath .path{stroke:#666;stroke-width:2.0px;}#mermaid-1792739274211 .flowchart-link{stroke:#666;fill:none;}#mermaid-1792739274211 .edgeLabel{background-color:white;text-align:center;}#mermaid-1792739274211 .edgeLabel p{background-color:white;}#mermaid-1792739274211 .edgeLabel rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1792739274211 .labelBkg{background-color:rgba(255, 255, 255, 0.5);}#mermaid-1792739274211 .cluster rect{fill:hsl(0, 0%, 98.9215686275%);stroke:#707070;stroke-width:1px;}#mermaid-1792739274211 .cluster text{fill:#333;}#mermaid-1792739274211 .cluster span{color:#333;}#mermaid-1792739274211 div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:12px;background:hsl(-160, 0%, 93.3333333333%);border:1px solid #707070;border-radius:2px;pointer-events:none;z-index:100;}#mermaid-1792739274211 .flowchartTitleText{text-anchor:middle;font-size:18px;fill:#000000;}#mermaid-1792739274211 rect.text{fill:none;stroke-width:0;}#mermaid-1792739274211 .icon-shape,#mermaid-1792739274211 .image-shape{background-color:white;text-align:center;}#mermaid-1792739274211 .icon-shape p,#mermaid-1792739274211 .image-shape p{background-color:white;padding:2px;}#mermaid-1792739274211 .icon-shape .label rect,#mermaid-1792739274211 .image-shape .label rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1792739274211 .label-icon{display:inline-block;height:1em;overflow:visible;vertical-align:-0.125em;}#mermaid-1792739274211 .node .label-icon path{fill:currentColor;stroke:revert;stroke-width:revert;}#mermaid-1792739274211 :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}

No

Yes

No

Yes

Yes

No

Input: BANKS, BANKL, BANKN, BKONT, LIFNR

Normalise inputs FR-11

BANKS filled and in T005?

Error: invalid bank country

Return valid flag = no E messages, plus full message table

Read country rules: BNKEY, LNBKS/PRBKS, LNBLZ/PRBLZ, LNBKN/PRBKN, XPRBK

BANKL filled?

Error: bank key missing

Apply key rule: BNKEY=1 uses LNBLZ/PRBLZ, else LNBKS/PRBKS

Read BNKA by BANKS + BANKL; check LOEVM

Apply account rule LNBKN/PRBKN

Call BANK\_NUMBER\_CHECK if XPRBK=X or rule 9

Control key plausibility FR-08

LIFNR supplied?

Duplicate account at other vendor? FR-09

1.  Normalise all inputs (FR-11). Validation always runs on the normalised values.
2.  Country check. If it fails, stop the country-dependent checks because there are no rules to apply, and return.
3.  Bank key checks (format rule, then BNKA existence and deletion flag).
4.  Account checks (format rule, then the standard country check).
5.  Optional checks (control key, duplicate at another vendor).
6.  Overall result is valid if no message has type E or A. Warnings (W) and information (I) do not make the result invalid.

## 9 Messages

Proposed message class `ZVBANK`. All texts are T100 messages, so they are translatable. Numbers are proposals.

No.

Type

Text

Trigger

001

E

Bank country &1 is missing or does not exist

FR-01

002

E

Bank key is missing

FR-02

003

E

Bank key &1 violates rule &2 (length &3) for country &4

FR-03

004

E

Bank key &1 does not exist in the bank master for country &2

FR-04

005

E

Bank &1 / &2 is flagged for deletion

FR-04

006

E

Bank account is missing

FR-05

007

E

Bank account violates rule &1 (length &2) for country &3

FR-06

008

E

Bank account is not valid for country &1 (SAP country check)

FR-07 (NOT\_VALID)

009

W

Bank control key missing or implausible for country &1

FR-08

010

W

Account already used by vendor &1

FR-09

011

I

No IBAN can be derived for this account

FR-14

012

W

Bank account not checked: country &1 has no account rule

FR-05

## 10 Error Handling

*   Business validation failures are **returned as messages** and never raised as exceptions. The caller decides whether to block, warn or log.
*   Technical failures, such as an unexpected exception from a standard function, raise `ZCX_VENDOR_BANK_ERROR` (inherits from CX\_STATIC\_CHECK, T100-based). The original exception is attached as PREVIOUS.
*   The class never shows a popup and never uses MESSAGE ... TYPE 'E'. It is safe for batch jobs, RFC and background runs.
*   Empty input never causes a short dump. Every read handles "not found" explicitly.

## 11 Authorisation & Data Protection

*   The class reads configuration and master data and does not perform its own authority check. The **calling program** is responsible for vendor-level authorisation (e.g. F\_LFA1\_BEK / F\_LFA1\_BUK) before it passes vendor data.
*   Bank account numbers are sensitive personal and financial data. Display formatting is **masked by default** (FR-12/13). Full display needs the caller to pass the show-full flag explicitly.
*   Account numbers are never written to application logs in clear text. Callers that log messages should use the masked form.

## 12 Non-Functional Requirements

Area

Requirement

Performance

One validation runs in under 50 ms. Country rules and bank master entries are buffered inside the instance. Mass callers can reuse one instance for thousands of records, e.g. all 1,231 LFBK rows.

Compatibility

SAP\_BASIS 740: inline declarations and constructor expressions allowed; no REDUCE, enums, AMDP, CDS-in-ABAP or RAP.

Reusability

Independent of vendor vs customer. Bank checks take only country, key and account, so they can be reused later for KNBK.

Quality

ATC clean (no priority 1/2 findings). ABAP Unit coverage of every FR, using the injected data-access fake.

Translation

All user-facing texts are T100 messages; no hard-coded literals.

## 13 Test Scenarios (grounded in live data)

#

Category

Input (country / key / account / control)

Expected result

T01

Positive

DE / 56565656 / 88888888 (vendor 0000000001)

Valid. Key: 8 digits = DE rule 4 exact 8. Account: 8 digits, within DE rule 2 max 14. Bank "City-Bank Hamburg"

T02

Positive

DE / 30080000 / 1234321 (vendor 0000000100)

Valid (7-digit account allowed under the "maximum" rule)

T03

Positive

FR / 3000200650 / 11111111111 / 11 (vendor 0000000010)

Valid on length rules (key exact 10 numeric; account exact 11). Bank "Credit Lyonnais"

T04

Negative

IN / "B 111" / 8888777788787 (LFBK record with no vendor)

Error 003 (IN rule 1 "without gaps") and Error 004 (not in BNKA for IN)

T05

Negative

blank / blank / blank (empty LFBK record)

Error 001; country-dependent checks skipped; no dump

T06

Negative

DE / 5656565 (7 digits) / 88888888

Error 003: DE requires exactly 8 numeric digits

T07

Negative

DE / 56565656 / 8888A888

Error 007: DE account rule 2 is numerical

T08

Boundary

DE / 56565656 / 14-digit account vs 15-digit account

14 digits valid; 15 digits → Error 007

T09

Boundary

AR / 20050000 vs DE / 20050000

Both found, but with different banks (Citibank vs Deutsche Bank Hamburg). Proves the lookup uses country + key

T10

Edge

US / <valid key> / any account

US account rule "0" → no format check on the account

T11

Edge

IN / valid key / blank account

Warning 012 only (IN has no account rule); result still valid

T12

Formatting

MASK\_ACCOUNT( "88888888" )

"\*\*\*\*8888"

T13

Formatting

NORMALIZE( "de" / " 5656-5656 " / "8888 8888" )

"DE" / "56565656" / "88888888"

T14

Formatting

GET\_BANK\_DETAILS( DK / 1234 )

"Danske Bank A/S", SWIFT DABADKKK

T15

Duplicate

Vendor 0000001003 with DE / 23984899 / 12345678

Warning 010: account already used by vendor 0000001002

T16

Regression

VALIDATE\_ALL on T04 input

Returns _both_ errors (003 and 004), with no early exit

## 14 Assumptions & Open Points

ID

Topic

Question / Assumption

Owner

OP-01

Naming

Confirm the class name `ZCL_VENDOR_BANK_VALIDATOR`, the exception class `ZCX_VENDOR_BANK_ERROR`, message class `ZVBANK` and the target package.

Dev lead

OP-02

Zero-padding

Should normalisation left-pad numeric "exact length" keys or accounts (e.g. DE bank key, FR account) or reject them as too short? Default assumption: reject, no padding.

AP business

OP-03

XPRBK meaning

Assumed meaning: XPRBK = 'X' requires the additional SAP country check (FR-07). Confirm against OY17 for the countries in use.

FI config

OP-04

Duplicates

Should a duplicate account at another vendor (FR-09) be a warning or a hard error?

AP / Compliance

OP-05

Data clean-up

The LFBK records with blank vendor numbers (§3.2) are a data-quality issue outside this object. Raise a separate clean-up item.

Master data team

OP-06

DK rules

The DK check rules were not part of the T005 extract above. Include them in the TS once confirmed.

FI config

## 15 Approval

Role

Name

Date

Signature

Business Owner (AP)

FI Functional Lead

Development Lead

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