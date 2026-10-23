  TS ZMM PR RFQ ARIBA Auto PR to RFQ @page { size: A4; margin: 20mm 18mm 20mm 18mm; } \* { box-sizing: border-box; margin: 0; padding: 0; } body { font-family: 'Segoe UI', Calibri, Arial, sans-serif; font-size: 10.5pt; line-height: 1.55; color: #1a1a1a; background: #f4f5f6; -webkit-print-color-adjust: exact; print-color-adjust: exact; } .doc-wrapper { max-width: 1100px; margin: 24px auto; background: #ffffff; box-shadow: 0 1px 8px rgba(0,0,0,0.08); border: 1px solid #d0d4d8; } /\* HEADER \*/ .doc-header { background: #003366; color: #ffffff; padding: 28px 36px 24px 36px; border-bottom: 4px solid #7fb3e0; } .doc-header-top { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 14px; } .doc-logo img { height: 40px; display: block; } .doc-classification { font-size: 8.5pt; letter-spacing: 1.2px; text-transform: uppercase; color: #7fb3e0; border: 1px solid #7fb3e0; padding: 3px 12px; border-radius: 2px; white-space: nowrap; } .doc-header h1 { font-size: 22pt; font-weight: 600; letter-spacing: -0.3px; margin: 0 0 4px 0; line-height: 1.2; } .doc-header .doc-subtitle { font-size: 11pt; color: #7fb3e0; font-weight: 400; } /\* META \*/ .doc-meta { padding: 16px 36px; background: #f7f8fa; border-bottom: 1px solid #d0d4d8; font-size: 9.5pt; color: #444; } .doc-meta table { width: 100%; border-collapse: collapse; } .doc-meta td { padding: 3px 12px 3px 0; vertical-align: top; } .doc-meta .meta-label { font-weight: 600; color: #003366; width: 90px; } /\* BODY \*/ .doc-body { padding: 28px 36px 36px 36px; background: #ffffff; } .doc-body p { margin: 8px 0; } .doc-body h2 { font-size: 14pt; color: #003366; margin: 24px 0 12px 0; padding-bottom: 6px; border-bottom: 2px solid #7fb3e0; display: flex; align-items: center; gap: 10px; } .doc-body h2 .sec-num { display: inline-block; background: #003366; color: white; font-size: 11pt; font-weight: 700; padding: 2px 9px; border-radius: 3px; line-height: 1; min-width: 26px; text-align: center; } .doc-body h3 { font-size: 11.5pt; color: #003366; margin: 18px 0 8px 0; font-weight: 600; } .doc-body h4 { font-size: 10.5pt; color: #1a5c8a; margin: 12px 0 6px 0; font-weight: 600; } .doc-body ul, .doc-body ol { margin: 8px 0 8px 22px; } .doc-body li { margin: 4px 0; } /\* TABLES \*/ table.data { width: 100%; border-collapse: collapse; margin: 10px 0 14px 0; font-size: 9.5pt; } table.data th, table.data td { border: 1px solid #d0d4d8; padding: 7px 10px; text-align: left; vertical-align: top; } table.data th { background: #003366; color: white; font-weight: 600; letter-spacing: 0.2px; } table.data tr:nth-child(even) td { background: #f7f8fa; } table.data td.center { text-align: center; } /\* CALLOUTS \*/ .callout { background: #f0f6fa; border-left: 4px solid #1a5c8a; padding: 12px 16px; margin: 14px 0; font-size: 10pt; color: #1f2937; } .callout.tip { border-left-color: #15803D; background: #f0fdf4; } .callout.warning { border-left-color: #C2410C; background: #fff7ed; } /\* PILLS — Clean Core levels \*/ .pill { display: inline-block; font-size: 8.5pt; font-weight: 600; padding: 2px 9px; border-radius: 10px; letter-spacing: 0.3px; white-space: nowrap; } .pill-a { background: #dcfce7; color: #15803D; } .pill-b { background: #dbeafe; color: #1D4ED8; } .pill-c { background: #fef3c7; color: #A16207; } .pill-d { background: #fee2e2; color: #B91C1C; } /\* SYSTEM PILLS — engagement context strip under the header \*/ .doc-pills { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 14px; } .doc-pills .doc-pill { display: inline-flex; align-items: center; gap: 6px; font-size: 8.5pt; font-weight: 500; padding: 4px 12px; border-radius: 16px; background: rgba(255, 255, 255, 0.12); border: 1px solid rgba(255, 255, 255, 0.28); color: #ffffff; letter-spacing: 0.2px; white-space: nowrap; } .doc-pills .doc-pill .doc-pill-icon { font-size: 9pt; opacity: 0.9; } .doc-pills .doc-pill.danger { background: rgba(254, 226, 226, 0.18); border-color: rgba(254, 226, 226, 0.35); } .doc-pills .doc-pill.warn { background: rgba(254, 243, 199, 0.15); border-color: rgba(254, 243, 199, 0.35); } /\* KPI STRIP — volume counters under the pills \*/ .doc-kpi-strip { display: flex; flex-wrap: wrap; gap: 18px; margin-top: 14px; padding-top: 12px; border-top: 1px solid rgba(255, 255, 255, 0.18); font-size: 9pt; color: rgba(255, 255, 255, 0.92); } .doc-kpi-strip .doc-kpi { display: inline-flex; align-items: center; gap: 5px; white-space: nowrap; } .doc-kpi-strip .doc-kpi-icon { font-size: 10.5pt; } .doc-kpi-strip .doc-kpi-value { font-weight: 700; color: #ffffff; } .doc-kpi-strip .doc-kpi-label { color: rgba(255, 255, 255, 0.78); } /\* PHASE TIMELINE \*/ .phase { border-left: 3px solid #7fb3e0; padding: 10px 16px; margin: 10px 0; background: #f7f8fa; } .phase strong { color: #003366; } .phase .phase-dur { color: #1a5c8a; font-size: 9pt; } /\* DOC FOOTER (inside wrapper) \*/ .doc-footer { background: #f7f8fa; border-top: 1px solid #d0d4d8; padding: 16px 36px; font-size: 9pt; color: #555; } .doc-footer table { width: 100%; } .doc-footer .footer-right { text-align: right; color: #003366; font-weight: 600; } @media print { body { background: white; } .doc-wrapper { box-shadow: none; border: none; margin: 0; max-width: 100%; } h2, h3 { page-break-after: avoid; } table.data { page-break-inside: avoid; } .phase, .callout { page-break-inside: avoid; } }

![C16](data:image/png;base64,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)

Reference

# TS ZMM PR RFQ ARIBA Auto PR to RFQ

Topic

TS ZMM PR RFQ ARIBA Auto PR to RFQ

Date

23 October 2026

Audience

CIOs, SAP program leaders, transformation architects

Author

C16 — AI for SAP operational efficiency

Scope

Version

1.0

**<<Customer Name>>**  
**<<Project Name>>**

**TECHNICAL SPECIFICATION – REPORT**  
**ZMM\_PR\_RFQ\_ARIBA – Automatic PR to S/4HANA RFQ Conversion and Ariba Publishing**

**Target system:** SAP S/4HANA. The release and deployment type are still open (OP-00). This TS assumes S/4HANA on-premise or RISE Private Cloud 2022+ with classic extensibility. All S/4HANA API, BO and service names are marked **TBV (to be verified on target)**; they could not be validated against the connected ECC system (SAP\_BASIS 740). If the target is S/4HANA Public Cloud or ABAP Cloud (Tier 1), the frame must be redesigned as an application job in ABAP Cloud. Section 6 has the details.

## 1 Document Organization

This section provides details about this document, previous version(s) of this document and the document(s) referred.

### 1.1 Document Log

Version

Status

Date

Version Created by

Role

Comments

0.1

Draft

2026-10-23

C16

Author

Initial technical design derived from FS\_ZMM\_PR\_RFQ\_ARIBA v0.1

Reviewer

Pending technical lead review

### 1.2 Integration, Document Reference

S. No.

Referred Document Name

Referred Document Version

Referred Document URL (Optional)

1

FS\_ZMM\_PR\_RFQ\_ARIBA – Automatic PR to RFQ (functional specification)

0.1

Documents panel

2

S/4HANA ↔ SAP Ariba Sourcing integration setup guide (customer landscape)

TBD

—

3

Requirement workshop answers (rounds 1–4)

23-Oct-2026

—

## 2 Code Quality

Final Solution

Category

Comments

Custom executable report (local classes) using released S/4HANA interfaces for RFQ create/publish, standard read APIs for PR/source list/supplier, and 2 custom tables

Level B (classic extensibility, on-prem / RISE Private Cloud). Writes are Level A where a released RFQ BO is used.

No modification, no implicit enhancement, no direct DML on standard tables. RFQ is created only through the released RFQ business object/API (TBV). The classic report frame, selection screen, ALV and SM30 view are accepted classic extensibility on on-prem / RISE Private Cloud. The design is **not** ABAP Cloud ready: on Public Cloud / Tier 1 the report frame, selection screen and SALV display would block, and the program would have to become an Application Job + Fiori log.

## 3 Program Attributes

Attribute

Value

Program title

Automatic PR to RFQ conversion with Ariba publishing

Program Name

ZMM\_PR\_RFQ\_ARIBA

Program Type

Executable (background-enabled), single program with local classes

Package

TBD by customer (e.g. ZMM\_SOURCING)

Authorization Group

ZMMP (proposed, program authorization group via S\_PROGRAM)

Transaction Code

ZMM\_PRRFQ (report transaction). Maintenance transaction ZMM\_PRRFQ\_MAP for the mapping view.

Include Programs

None (single program with local classes lcl\_selection, lcl\_processor, lcl\_log, lcl\_output)

Function Modules

READ\_TEXT; ENQUEUE\_EZMM\_PRRFQ / DEQUEUE\_EZMM\_PRRFQ (generated); BAL\_LOG\_CREATE, BAL\_LOG\_MSG\_ADD, BAL\_DB\_SAVE (application log). Text write to RFQ via BO text entity or SAVE\_TEXT (TBV).

Message Class

ZMM\_PRRFQ

SAP Tables Read

EBAN (PR items; or released read view for PR items, TBV), EORD (source list), LFA1 / LFB1 / LFM1 (supplier blocks; or released supplier views, TBV), T024 (purchasing groups), T001W / T001K (plant → company code), T024W (plant ↔ purchasing org assignment), EKKO / EKPO (existing RFQ check, BSTYP = 'A'), STXH/STXL via READ\_TEXT

Custom Tables

ZMM\_PRRFQ\_ORGMAP (customising, delivery class C); ZMM\_PRRFQ\_LOG (application, delivery class A)

Custom Indexes

None on standard tables. ZMM\_PRRFQ\_LOG secondary index on RUN\_ID.

CDS Views

No custom CDS. Released standard read views may be consumed for PR / supplier / source list if available on target (TBV).

OData Service

None exposed. Consumed: RFQ business object via EML (released RFQ RAP BO, TBV). Alternative: RFQ OData API (API\_RFQ\_PROCESS\_SRV, TBV).

Business Object

Standard S/4HANA Request for Quotation BO (RAP, TBV). No BOPF.

Fiori App Name

Not applicable (report). Buyers follow up in the standard RFQ app.

Group Name

Not applicable

Catalog Name

Not applicable

### 3.1 Selection Screen

**Block B01: PR selection**. **Block B02: RFQ parameters**. **Block B03: Processing control**. Every field is typed against its dictionary field (Rule 3), and selection texts use "Dictionary reference" so labels come from the data element texts.

Parameter / Select Options

Type / Field Name

Mandatory

Default Value

Parameter ID

Search Help

Selection Screen Text

S – S\_EKGRP

EBAN-EKGRP

Yes

001

EKG

Standard (T024)

Dictionary reference

S – S\_EKORG

EBAN-EKORG

No

—

EKO

Standard

Dictionary reference

S – S\_WERKS

EBAN-WERKS

No

—

WRK

Standard

Dictionary reference

S – S\_BSART

EBAN-BSART

No

NB

BAR

Standard

Dictionary reference

S – S\_BANFN

EBAN-BANFN

No

—

BAN

Standard

Dictionary reference

S – S\_MATKL

EBAN-MATKL

No

—

MKL

Standard

Dictionary reference

S – S\_BADAT

EBAN-BADAT (date)

No

sy-datum − 30 to sy-datum (set in INITIALIZATION; OP-03)

—

Calendar

Dictionary reference

P – P\_DLDAYS

ZMM\_DE\_RFQ\_DEADLINE\_DAYS (new data element, NUMC 3)

Yes

030

—

—

Dictionary reference ("Quotation deadline (days)")

P – P\_MAXBID

ZMM\_DE\_RFQ\_MAX\_BIDDERS (new data element, NUMC 1)

Yes

3

—

—

Dictionary reference ("Max. suppliers per RFQ")

P – P\_PUBL (checkbox)

XFELD

No

X

—

—

Publish RFQ to Ariba (text symbol)

P – P\_TEST (checkbox)

XFELD

No

X online. Space in job variant.

—

—

Test mode (simulation) (text symbol)

### 3.2 Validation of Selection Criteria

*   **AT SELECTION-SCREEN ON S\_EKGRP:** must not be initial (E, ZMM\_PRRFQ 002). Every single value must exist in T024 (E, 003).
*   **AT SELECTION-SCREEN ON S\_EKORG / S\_WERKS:** single values must exist in T024E / T001W (E, 004).
*   **P\_DLDAYS:** 1–365 (E, 005).
*   **P\_MAXBID:** 1–9. Business default 3 (E, 006).
*   **Mapping completeness:** for each purchasing group in S\_EKGRP with no entry in ZMM\_PRRFQ\_ORGMAP, warning 007 (online only). Items needing derivation will be skipped.
*   **Background check:** if sy-batch = abap\_true and P\_TEST = abap\_true, write info 008 to the log ("Job running in test mode – no RFQs created").
*   **Authorisation:** AUTHORITY-CHECK on M\_ANFR\_EKO (ACTVT 01) for each single EKORG value entered. Item-level checks are repeated during processing (3.4).
*   **Run lock:** at START-OF-SELECTION, ENQUEUE\_EZMM\_PRRFQ (exclusive, mode E, scope client). If foreign lock, E 009 and the run stops.

### 3.3 CDS Views/AMDP/Table Function

No custom CDS view, AMDP or table function is created. The program uses Open SQL reads (or released standard read views where available on the target, TBV). The selection and join logic is documented below because it defines the data model.

#### 3.3.1 Selection Condition

*   **EBAN (PR items):** EKGRP IN s\_ekgrp, EKORG IN s\_ekorg, WERKS IN s\_werks, BSART IN s\_bsart, BANFN IN s\_banfn, MATKL IN s\_matkl, BADAT IN s\_badat.
    *   Not deleted: LOEKZ = space.
    *   Not closed: EBAKZ = space.
    *   Released: FRGRL = space (release complete or not subject to release; OP-02).
    *   Open: STATU = 'N' (not yet processed; TBV on S/4), EBELN = space, KONNR = space.
    *   Open quantity: MENGE − BSMNG > 0.
    *   Item category: PSTYP IN lr\_pstyp (default standard '0' only; OP-04).
*   **ZMM\_PRRFQ\_LOG:** exclude BANFN/BNFPO with STATUS IN ('C','P'), i.e. RFQ created or published.
*   **EKPO (existing RFQ):** exclude PR items already referenced by an RFQ item: EKPO-BANFN/BNFPO with EKKO-BSTYP = 'A' and LOEKZ = space.
*   **EORD (source list):** MATNR/WERKS FOR ALL ENTRIES of PR items (driver checked not initial, R-RT09). VDATU ≤ sy-datum ≤ BDATU, NOTKZ = space (not blocked), EKORG = derived org or space.
*   **Supplier checks:** LFA1 (SPERM purchasing block, SPERR posting block, LOEVM deletion flag), LFM1 (SPERM per EKORG), LFB1 (SPERR per BUKRS). Fields to be verified via DD03L on the target before coding.

#### 3.3.2 Join Condition

*   EBAN → ZMM\_PRRFQ\_ORGMAP: EBAN-EKGRP = ORGMAP-EKGRP (AND ORGMAP-WERKS = EBAN-WERKS or ORGMAP-WERKS = space, plant-specific entry first).
*   EBAN → T001W → T001K: EBAN-WERKS = T001W-WERKS; T001W-BWKEY = T001K-BWKEY (gives BUKRS).
*   Derived org check: T024W-WERKS = EBAN-WERKS AND T024W-EKORG = derived org.
*   EBAN → EORD: EBAN-MATNR = EORD-MATNR AND EBAN-WERKS = EORD-WERKS.
*   Bidder → LFA1 / LFM1 (LIFNR + EKORG) / LFB1 (LIFNR + BUKRS).
*   EBAN → EKPO/EKKO: EKPO-BANFN = EBAN-BANFN AND EKPO-BNFPO = EBAN-BNFPO; EKKO-EBELN = EKPO-EBELN AND EKKO-BSTYP = 'A'.

#### 3.3.3 Fields

Table

Fields read

EBAN

BANFN, BNFPO, BSART, EKGRP, EKORG, WERKS, LGORT, MATNR, MATKL, TXZ01, MENGE, BSMNG, MEINS, LFDAT, BADAT, LIFNR (desired), FLIEF (fixed), KNTTP, PSTYP, WAERS, PREIS, PEINH, FRGRL, FRGKZ, STATU

EORD

MATNR, WERKS, ZEORD, LIFNR, EKORG, VDATU, BDATU, FLIFN (fixed source), NOTKZ (blocked)

LFA1 / LFM1 / LFB1

LIFNR, SPERM, SPERR, LOEVM / LIFNR, EKORG, SPERM / LIFNR, BUKRS, SPERR

T001W / T001K / T024W

WERKS, BWKEY / BWKEY, BUKRS / WERKS, EKORG

ZMM\_PRRFQ\_ORGMAP

EKGRP, WERKS, EKORG, ACTIVE

EKBE / EBKN

EBKN (account assignment of PR item) when KNTTP ≠ space, to copy to the RFQ item

#### 3.3.4 Additional Details

**New DDIC objects.** Every field uses a data element, and labels come from the data elements (D1):

Object

Fields (key\*)

Settings

ZMM\_PRRFQ\_ORGMAP

MANDT\*, EKGRP\* (EKGRP), WERKS\* (WERKS\_D, space = all plants), EKORG (EKORG), ACTIVE (XFELD), changed by/on (AENAM / AEDAT)

Delivery class C. Table maintenance generator, authorisation group ZMM. Log data changes = X.

ZMM\_PRRFQ\_LOG

MANDT\*, BANFN\* (BANFN), BNFPO\* (BNFPO), RUN\_ID\* (SYSUUID\_C32 via data element ZMM\_DE\_PRRFQ\_RUNID), RFQ\_EBELN (EBELN), RFQ\_NAME (ZMM\_DE\_RFQ\_NAME, CHAR 40), EKORG, ORG\_SOURCE (ZMM\_DE\_ORG\_SOURCE: P = PR, M = mapping), BIDDER1-3 (LIFNR), STATUS (ZMM\_DE\_PRRFQ\_STATUS: C created, P published, F publish failed, S skipped, E error), MSGTXT (BAPI\_MSG), ERNAM, ERDAT, ERZET

Delivery class A. Secondary index on RUN\_ID. Archiving / retention 2 years (housekeeping report out of scope).

EZMM\_PRRFQ

Lock object on ZMM\_PRRFQ\_LOG (MANDT only)

Run lock

Application log

Object ZMM, subobject PRRFQ (SLG0)

External ID = RUN\_ID

#### 3.3.5 GIT Repository Details

Development Details

GIT Location

Not applicable (ABAP transport-based). An abapGit repository is optional if used by the customer.

GIT URL

Not applicable

### 3.4 Authorization Requirements

#### 3.4.1 Definition

Standard authorisation objects only. No custom authorisation object is required.

*   **M\_ANFR\_EKO**: RFQ purchasing org
*   **M\_ANFR\_EKG**: RFQ purchasing group
*   **M\_ANFR\_WRK**: RFQ plant
*   **M\_ANFR\_BSA**: RFQ document type
*   **M\_BANF\_EKG / M\_BANF\_WRK**: display PR
*   **S\_TCODE**: ZMM\_PRRFQ / ZMM\_PRRFQ\_MAP
*   **S\_PROGRAM**: group ZMMP
*   **S\_TABU\_NAM**: ZMM\_PRRFQ\_ORGMAP (maintenance)
*   **S\_APPL\_LOG**: display application log

The S/4HANA RFQ BO performs its own instance authorisation on create (TBV).

#### 3.4.2 Defined Fields

Object

Field

Values

M\_ANFR\_EKO

ACTVT / EKORG

01 (create), 02 (change for publish) / orgs in scope

M\_ANFR\_EKG

ACTVT / EKGRP

01, 02 / 001

M\_ANFR\_WRK

ACTVT / WERKS

01, 02 / plants in scope

M\_ANFR\_BSA

ACTVT / BSART

01, 02 / RFQ type in use

M\_BANF\_EKG, M\_BANF\_WRK

ACTVT

03

S\_TABU\_NAM

ACTVT / TABLE

02, 03 / ZMM\_PRRFQ\_ORGMAP

#### 3.4.3 Procedure

For each candidate PR item, after org derivation, the program runs AUTHORITY-CHECK on M\_ANFR\_EKO (EKORG = derived org, ACTVT 01), M\_ANFR\_EKG (EKGRP) and M\_ANFR\_WRK (WERKS). If sy-subrc ≠ 0, the item is skipped with E 020 "No authorisation to create RFQ for org &1 / group &2 / plant &3".

The job user gets a dedicated role, e.g. Z\_MM\_PRRFQ\_BATCH, containing the values above for the scoped orgs. Key users get Z\_MM\_PRRFQ\_MAP for mapping maintenance.

#### 3.4.4 DCL Details

Not applicable. No custom CDS view or DCL. Standard DCL of released read views (if used) applies.

#### 3.4.5 BTP Details

xs-security Configuration

Not applicable (no BTP component)

IDP Setup

Not applicable

BTP Role Collections

Not applicable. Middleware roles for Ariba connectivity are owned by the integration team.

### 3.5 Technical Flow Diagram

SAP Ariba SourcingOutput Mgmt / Outbound serviceS/4HANA RFQ BO (TBV)ZMM\_PRRFQ\_ORGMAPPR / Source list / Supplier dataZMM\_PR\_RFQ\_ARIBAJob / UserSAP Ariba SourcingOutput Mgmt / Outbound serviceS/4HANA RFQ BO (TBV)ZMM\_PRRFQ\_ORGMAPPR / Source list / Supplier dataZMM\_PR\_RFQ\_ARIBAJob / User#mermaid-1792758311581{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1792758311581 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1792758311581 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1792758311581 .error-icon{fill:#552222;}#mermaid-1792758311581 .error-text{fill:#552222;stroke:#552222;}#mermaid-1792758311581 .edge-thickness-normal{stroke-width:1px;}#mermaid-1792758311581 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1792758311581 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1792758311581 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1792758311581 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1792758311581 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1792758311581 .marker{fill:#666;stroke:#666;}#mermaid-1792758311581 .marker.cross{stroke:#666;}#mermaid-1792758311581 svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-1792758311581 p{margin:0;}#mermaid-1792758311581 .actor{stroke:hsl(0, 0%, 83%);fill:#eee;}#mermaid-1792758311581 text.actor>tspan{fill:#333;stroke:none;}#mermaid-1792758311581 .actor-line{stroke:hsl(0, 0%, 83%);}#mermaid-1792758311581 .innerArc{stroke-width:1.5;stroke-dasharray:none;}#mermaid-1792758311581 .messageLine0{stroke-width:1.5;stroke-dasharray:none;stroke:#333;}#mermaid-1792758311581 .messageLine1{stroke-width:1.5;stroke-dasharray:2,2;stroke:#333;}#mermaid-1792758311581 #arrowhead path{fill:#333;stroke:#333;}#mermaid-1792758311581 .sequenceNumber{fill:white;}#mermaid-1792758311581 #sequencenumber{fill:#333;}#mermaid-1792758311581 #crosshead path{fill:#333;stroke:#333;}#mermaid-1792758311581 .messageText{fill:#333;stroke:none;}#mermaid-1792758311581 .labelBox{stroke:hsl(0, 0%, 83%);fill:#eee;}#mermaid-1792758311581 .labelText,#mermaid-1792758311581 .labelText>tspan{fill:#333;stroke:none;}#mermaid-1792758311581 .loopText,#mermaid-1792758311581 .loopText>tspan{fill:#333;stroke:none;}#mermaid-1792758311581 .loopLine{stroke-width:2px;stroke-dasharray:2,2;stroke:hsl(0, 0%, 83%);fill:hsl(0, 0%, 83%);}#mermaid-1792758311581 .note{stroke:#999;fill:#666;}#mermaid-1792758311581 .noteText,#mermaid-1792758311581 .noteText>tspan{fill:#fff;stroke:none;}#mermaid-1792758311581 .activation0{fill:#f4f4f4;stroke:#666;}#mermaid-1792758311581 .activation1{fill:#f4f4f4;stroke:#666;}#mermaid-1792758311581 .activation2{fill:#f4f4f4;stroke:#666;}#mermaid-1792758311581 .actorPopupMenu{position:absolute;}#mermaid-1792758311581 .actorPopupMenuPanel{position:absolute;fill:#eee;box-shadow:0px 8px 16px 0px rgba(0,0,0,0.2);filter:drop-shadow(3px 5px 2px rgb(0 0 0 / 0.4));}#mermaid-1792758311581 .actor-man line{stroke:hsl(0, 0%, 83%);fill:#eee;}#mermaid-1792758311581 .actor-man circle,#mermaid-1792758311581 line{stroke:hsl(0, 0%, 83%);fill:#eee;stroke-width:2px;}#mermaid-1792758311581 :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}opt\[P\_PUBL = X\]loop\[per RFQ group\]alt\[Test mode\]\[Productive\]Start (variant, P\_TEST, P\_PUBL)Validate selection, ENQUEUE run lock, create BAL logSelect released open PR items (bulk)Derive / check purchasing orgSource list + supplier block data (FOR ALL ENTRIES)Determine bidders (max 3), group itemsALV simulation resultMODIFY ENTITIES create RFQ + items + bidders + textsCOMMIT ENTITIESExecute Publish action + COMMITOutput triggered (RFQ, Ariba channel)Outbound RFQ messageWrite ZMM\_PRRFQ\_LOG + BAL messagesALV result, BAL\_DB\_SAVE, DEQUEUE

### 3.6 UI Details

Classic selection screen and SALV result list only. There is no Fiori or UI5 application.

#### 3.6.1 UI Mock Screens

Application Name

ZMM\_PR\_RFQ\_ARIBA (transaction ZMM\_PRRFQ)

Site

SAP GUI / Web GUI

URL

Not applicable

Mockup

Selection screen with blocks B01–B03 (section 3.1) and ALV list (section 4.4)

#### 3.6.2 Navigations

Source View

Target View / URL

Pattern

ALV – double-click on PR number

Display PR (ME53N)

SET PARAMETER ID 'BAN' + CALL TRANSACTION 'ME53N' AND SKIP FIRST SCREEN, after AUTHORITY-CHECK for S\_TCODE

ALV – double-click on RFQ number

Standard RFQ display (Manage RFQs app / transaction, TBV on target)

RFQ number as parameter

#### 3.6.3 Actions

Application

Screen(s)

Action

Type

Action Description

ZMM\_PR\_RFQ\_ARIBA

Result ALV

Display application log

Button

Opens SLG1-style log for the current RUN\_ID (BAL\_DSP\_LOG\_DISPLAY)

ZMM\_PR\_RFQ\_ARIBA

Selection screen

Value help on S\_EKGRP / S\_EKORG / S\_WERKS

Value help

Standard DDIC search help

#### 3.6.4 Validations

Application

Screen(s)

Field/Button

Validation Logic – Method, function details

ZMM\_PR\_RFQ\_ARIBA

Selection

S\_EKGRP, S\_EKORG, S\_WERKS, P\_DLDAYS, P\_MAXBID

lcl\_selection=>validate. See section 3.2.

#### 3.6.5 Other Details

Job scheduling: SM36 job ZMM\_PR\_RFQ\_ARIBA\_DAILY, daily 06:00 (system time), variant DAILY\_PROD (S\_EKGRP = 001, P\_TEST = space, P\_PUBL = X, S\_BADAT dynamic: current date − 30 to current date). Spool list retained.

### 3.7 Processing Logic

**Data model:** PR item (EBAN) 1:n source list entries (EORD) per material/plant. PR item n:1 RFQ group. RFQ group 1:n bidders (max 3). PR item 1:1 log record per run.

1.  **INITIALIZATION:** default S\_BADAT = sy-datum − 30 … sy-datum. Default S\_EKGRP = 001 and S\_BSART = NB.
2.  **START-OF-SELECTION – init:** lock the run (ENQUEUE\_EZMM\_PRRFQ; on foreign lock, E 009 and stop). Generate RUN\_ID (cl\_system\_uuid). Create BAL log (object ZMM / sub PRRFQ, extnumber = RUN\_ID).
3.  **select\_pr\_items:** one SELECT on EBAN with the criteria in 3.3.1, into typed table gt\_pr. If initial, S 010 "No eligible PR items found" and end the run normally (log saved).
4.  **exclude\_processed:** read ZMM\_PRRFQ\_LOG (STATUS C/P) and EKPO/EKKO RFQ references for gt\_pr keys (FOR ALL ENTRIES, driver checked not initial). Delete matches from gt\_pr. Count logged as I 011.
5.  **derive\_purch\_org:** read ZMM\_PRRFQ\_ORGMAP (ACTIVE = X) into a hashed table keyed by EKGRP + WERKS. Per item:
    *   EKORG initial: look up (EKGRP, WERKS), then (EKGRP, space). If found, set EKORG and ORG\_SOURCE = 'M'. Otherwise status S, E 012.
    *   EKORG filled: ORG\_SOURCE = 'P'. If a mapping exists and differs, W 013 (D-15).
    *   Check T024W (plant ↔ org). If no assignment, E 014 and skip.
6.  **derive\_company\_code:** T001W-BWKEY → T001K-BUKRS per plant (buffered hashed table).
7.  **check\_authority:** per item, see 3.4.3. Skip with E 020.
8.  **determine\_bidders:** bulk-read EORD, LFA1, LFM1, LFB1 for all candidate suppliers. Per item:
    *   Supplier 1 = FLIEF, otherwise LIFNR.
    *   Candidates 2..n = EORD entries (same MATNR / WERKS, EKORG = derived or space, valid on sy-datum, NOTKZ = space), sorted FLIFN DESC, ZEORD ASC.
    *   Remove duplicates and supplier 1.
    *   Remove blocked suppliers: LFA1-SPERM / SPERR / LOEVM, LFM1-SPERM (EKORG), LFB1-SPERR (BUKRS). W 015 per supplier.
    *   Remove suppliers not Ariba-enabled (is\_ariba\_enabled, OP-13; TBV source). W 016.
    *   Take the first P\_MAXBID.
    *   0 suppliers: status S, E 017.
    *   Fewer than P\_MAXBID: W 018 (D-14).
    *   Text item (MATNR initial): supplier 1 only.
9.  **group\_items:** build group key = BANFN + EKORG + EKGRP + BUKRS + sorted bidder list (concatenated). Assign items to groups (sorted table gt\_group).
10.  **Test mode branch:** if P\_TEST = X, fill the simulated RFQ name ("SIMULATION"), deadline and status 'T' (test), display the ALV and stop. No commit and no log table write; the BAL log is saved for traceability.
11.  **create\_rfq per group** (released RFQ BO via EML; entity, field and action names TBV on target):
     *   Header: RFQ type, company code, purchasing org, purchasing group, currency.
     *   RFQ name = build\_rfq\_name: 'RFQ' + timestamp (YYYYMMDDhhmmss of run start, system time zone) + '-' + run counter (2 digits, incremented per RFQ).
     *   Quotation latest submission date = sy-datum + P\_DLDAYS (date guard R-RT03).
     *   Items: create-by-association, with PR reference (BANFN/BNFPO), material, short text, material group, plant, storage location, open quantity (MENGE − BSMNG), unit, delivery date = LFDAT, account assignment (EBKN) when KNTTP ≠ space.
     *   Bidders: create-by-association, 1–3 suppliers.
     *   Delivery date check: if LFDAT < deadline, W 019.
     *   MODIFY ENTITIES … FAILED / REPORTED, then COMMIT ENTITIES (one LUW per RFQ group).
     *   If failed / reported errors: ROLLBACK ENTITIES, status E for all group items, E 021 + BO messages to BAL. Continue with the next group.
     *   Read back the RFQ number (late numbering mapping from COMMIT ENTITIES … MAPPED / CONVERT KEY, TBV).
12.  **copy\_texts:** READ\_TEXT on the PR header (object EBANH, id B01) and items (object EBAN, ids per text determination). Append the standard header text (SO10 text, name from constant / OP-10). Write to RFQ header and item text entities in the same create call where the BO supports text associations (TBV). Otherwise use SAVE\_TEXT on the RFQ text objects after commit. Missing text is not an error (no message).
13.  **publish\_rfq:** if P\_PUBL = X, EXECUTE the Publish action on the created RFQ, then COMMIT ENTITIES. Success: status P, S 022. Failure: status F, E 023 + BO messages. The RFQ is kept. The output to Ariba is raised by standard output determination on publish (IP-02); the program does not call the outbound service directly.
14.  **write\_log:** INSERT ZMM\_PRRFQ\_LOG rows for all processed/skipped items (per group, after the RFQ commit, in the same LUW as the next commit or via a separate COMMIT WORK). BAL\_LOG\_MSG\_ADD for every message with context (BANFN/BNFPO).
15.  **END-OF-SELECTION:** BAL\_DB\_SAVE. Display ALV (online or spool). Summary message S 024 "&1 RFQs created, &2 published, &3 items skipped, &4 errors". DEQUEUE\_EZMM\_PRRFQ.

**Performance:** no SELECT inside loops. All reads are bulk with FOR ALL ENTRIES (driver not initial) into hashed tables. Packages of 100 RFQs per commit are not needed because there is one commit per RFQ. Expected volume is low (one purchasing group).

**Coding rules:** local classes only (no FORM). Typed DDIC structures. Every SELECT uses the same Open SQL syntax style. Every arithmetic and date operation has a guard. No direct UPDATE on EBAN or EKKO; PR status is updated by the RFQ BO through the PR reference.

### 3.8 Reusable Code

*   **lcl\_log** (BAL wrapper: create, add message, add BO REPORTED messages, save). Candidate for a global class ZCL\_MM\_APPL\_LOG if the customer has none.
*   **build\_rfq\_name** and **is\_ariba\_enabled**: candidates for global utility class ZCL\_MM\_SOURCING\_UTIL if other sourcing developments need them.
*   Standard reuse: READ\_TEXT, BAL\_\* function modules, released RFQ BO.

### 3.9 Messages

Message Class

Message ID

Message Text

ZMM\_PRRFQ

001

Report selection fetched no data

ZMM\_PRRFQ

002

Enter at least one purchasing group

ZMM\_PRRFQ

003

Purchasing group &1 does not exist

ZMM\_PRRFQ

004

Purchasing organisation / plant &1 does not exist

ZMM\_PRRFQ

005

Quotation deadline days must be between 1 and 365

ZMM\_PRRFQ

006

Maximum number of suppliers must be between 1 and 9

ZMM\_PRRFQ

007

No purchasing org mapping maintained for purchasing group &1

ZMM\_PRRFQ

008

Job running in test mode – no RFQs will be created

ZMM\_PRRFQ

009

Program is already running (locked by &1)

ZMM\_PRRFQ

010

No eligible purchase requisition items found

ZMM\_PRRFQ

011

&1 PR items excluded – already converted to RFQ

ZMM\_PRRFQ

012

PR &1/&2: no purchasing org and no mapping for group &3

ZMM\_PRRFQ

013

PR &1/&2: PR purchasing org &3 differs from mapping &4 – PR value kept

ZMM\_PRRFQ

014

PR &1/&2: purchasing org &3 not assigned to plant &4

ZMM\_PRRFQ

015

Supplier &1 excluded – blocked (&2)

ZMM\_PRRFQ

016

Supplier &1 excluded – not enabled for SAP Ariba

ZMM\_PRRFQ

017

PR &1/&2: no eligible supplier found – item skipped

ZMM\_PRRFQ

018

PR &1/&2: only &3 supplier(s) found – RFQ created with fewer suppliers

ZMM\_PRRFQ

019

PR &1/&2: delivery date &3 is before quotation deadline &4

ZMM\_PRRFQ

020

No authorisation to create RFQ for org &1 / group &2 / plant &3

ZMM\_PRRFQ

021

RFQ creation failed for PR &1 – see detailed messages

ZMM\_PRRFQ

022

RFQ &1 (&2) created and published

ZMM\_PRRFQ

023

RFQ &1 created but publishing failed – publish manually

ZMM\_PRRFQ

024

&1 RFQs created, &2 published, &3 items skipped, &4 errors

### 3.10 Subroutines

Local class methods are used instead of FORM routines.

Name

Description

lcl\_selection=>validate

Selection-screen checks (3.2)

lcl\_processor->select\_pr\_items RETURNING tt\_pr

Bulk read of eligible PR items

lcl\_processor->exclude\_processed CHANGING ct\_pr

Removes items already converted (log table / existing RFQ)

lcl\_processor->derive\_purch\_org CHANGING ct\_pr

Org derivation and warnings (D-12, D-15)

lcl\_processor->derive\_company\_code

Plant → company code

lcl\_processor->check\_authority IMPORTING is\_pr RETURNING rv\_ok

M\_ANFR\_\* checks per item

lcl\_processor->determine\_bidders CHANGING ct\_pr

PR supplier + source list, block and Ariba checks, max P\_MAXBID

lcl\_processor->is\_ariba\_enabled IMPORTING iv\_lifnr RETURNING rv\_enabled

Ariba enablement check (source TBV, OP-13)

lcl\_processor->group\_items RETURNING tt\_group

Builds RFQ groups

lcl\_processor->build\_rfq\_name RETURNING rv\_name

RFQ + timestamp + counter

lcl\_processor->create\_rfq IMPORTING is\_group EXPORTING ev\_ebeln

EML create + commit / rollback

lcl\_processor->copy\_texts

PR texts + standard header text to RFQ

lcl\_processor->publish\_rfq IMPORTING iv\_ebeln RETURNING rv\_ok

Publish action + commit

lcl\_log->add / add\_bo\_messages / save

Application log handling

lcl\_processor->write\_log

Writes ZMM\_PRRFQ\_LOG

lcl\_output->display

SALV result list (bulkhead TRY pattern)

## 4 Report Output

### 4.1 Output Method

Online: SALV grid (CL\_SALV\_TABLE: Level B classic ALV, compatible on on-prem / RISE Private). Background: ALV list to spool. Application log in SLG1 (object ZMM / PRRFQ). Excel download through the standard ALV function.

### 4.2 Main Heading

"Automatic PR to RFQ Conversion – Run Result" (text symbol).

### 4.3 Sub Heading

Run ID, run date/time, user, mode (Test / Productive), publish flag, and summary counts (created / published / skipped / errors), shown in the ALV header (top-of-list).

### 4.4 Layout / UI Design

Col

Field

Label source

1

STATUS\_ICON

Text symbol "Status"

2

BANFN

DDIC (BANFN)

3

BNFPO

DDIC (BNFPO)

4

MATNR

DDIC

5

TXZ01

DDIC

6

WERKS

DDIC

7

EKGRP

DDIC

8

EKORG

DDIC

9

ORG\_SOURCE

DDIC (ZMM\_DE\_ORG\_SOURCE)

10–12

BIDDER1, BIDDER2, BIDDER3

DDIC (LIFNR) + column suffix 1/2/3 (text symbols)

13

RFQ\_EBELN

DDIC (EBELN)

14

RFQ\_NAME

DDIC (ZMM\_DE\_RFQ\_NAME)

15

DEADLINE

DDIC (quotation deadline data element, TBV)

16

LFDAT

DDIC

17

STATUS

DDIC (ZMM\_DE\_PRRFQ\_STATUS)

18

MSGTY

DDIC (SYMSGTY)

19

MSGTXT

DDIC (BAPI\_MSG)

### 4.5 Totaling

No amount totals. Counts per STATUS appear in the header (4.3), and the ALV aggregation function is available.

### 4.6 Sorting

Default sort: STATUS (errors first), BANFN, BNFPO. All columns can be sorted by the user.

### 4.7 Page Break

Not applicable (ALV). Spool uses the standard ALV list format.

### 4.8 Error Handling

Error

Handling

User sees

Run already active

ENQUEUE fails, run stops

E 009. Job ends with error status.

Item-level data issues (org, supplier, authorisation)

Item skipped. Status S/E in log.

ALV row red/yellow, BAL message

RFQ BO create failure

ROLLBACK ENTITIES for that group only. Processing continues.

E 021 + BO REPORTED messages

Publish failure / integration error

RFQ kept, status F

E 023. Republish in standard RFQ app after the fix (IP-07).

Outbound message failure after publish

Outside program. Standard message monitoring.

Support monitors daily (IP-07)

Unexpected exception

TRY … CATCH cx\_root around each group. Logged. Next group continues.

E 021 with exception text

ALV factory error

CATCH cx\_salv\_msg → E message. Log is still saved.

Message, log in SLG1

### 4.9 Report Header & Footer

Project standard header. No deviation. Footer shows run ID and summary counts.

## 5 Assumptions in Technical Design

1.  The target is S/4HANA on-premise or RISE Private Cloud 2022+ with classic extensibility (OP-00).
2.  A released RFQ business object or API supports create (header, items with PR reference, bidders, texts) and the Publish action on the target release (TBV). Fallback: RFQ OData API called locally.
3.  The Ariba Sourcing integration is live (D-11). Publishing triggers the outbound message through standard output determination, so no custom outbound call is needed.
4.  "001" is purchasing group 001 (D-13). "Keep them and warn" means the existing PR purchasing org is kept with a warning when it differs from the mapping (D-15).
5.  "Released only" is implemented as release indicator complete (FRGRL = space). PRs without a release strategy are included unless OP-02 decides otherwise.
6.  RFQ name uses the system time zone and a run counter suffix for uniqueness. The name fits the RFQ name field length (≤ 40 characters, TBV).
7.  Deadline = creation date + 30 calendar days.
8.  Standard RFQ defaulting provides payment terms and Incoterms. "Standard terms" are attached as a standard header text.
9.  Field names of EBAN / EORD / LFA1 / LFM1 / LFB1 listed in 3.3 are verified via DD03L on the target before coding.
10.  Daily volume for purchasing group 001 is low (hundreds of items). No parallel processing is required.

## 6 Open Issues in Technical Design

ID

Issue

Impact

Owner

OP-00

Target S/4HANA release and deployment type. If Public Cloud / ABAP Cloud: redesign as Application Job + released APIs only. No SELECT on EBAN/EORD/LFA1, no selection screen or SALV.

High (architecture)

Customer IT

TI-01

Exact released RFQ BO entity, field and action names (create, bidders, texts, PR reference, Publish) on the target

High

Developer (verify on target)

TI-02

Source of "Ariba-enabled" supplier flag (Business Network ID mapping)

Medium

Integration

TI-03

PR text object/IDs and RFQ text IDs on target. Standard header text name.

Low

MM functional

TI-04

Grouping rule confirmation (OP-05)

Medium

Business

TI-05

Item categories / account assignment scope (OP-04). Service items would need a different item structure.

Medium

Business

TI-06

Fit-to-standard: standard PR-to-Ariba sourcing request flow could replace parts of this program

Medium

Solution architect

TI-07

Retention / housekeeping for ZMM\_PRRFQ\_LOG and BAL logs

Low

Basis

## 7 Unit Test Results

Planned scenarios. The **Actual** column stays "Not run" until executed on the target system with target data. No results are claimed.

Scenario #

Input Selection Criteria

Expected Result

Actual Test Pass/Fail

1

S\_EKGRP = 001, released PR with org, fixed supplier + 2 valid source list suppliers, P\_TEST = space

1 RFQ, 3 bidders, name RFQ<ts>-01, deadline +30, delivery date = PR, published (status P)

Not run

2

Same as 1 with P\_TEST = X

ALV simulation. No RFQ. No log rows.

Not run

3

PR without org, mapping 001 → org exists

Org from mapping, ORG\_SOURCE = M, RFQ created

Not run

4

PR without org, no mapping

Item skipped, E 012

Not run

5

PR org ≠ mapping org

PR org kept, W 013

Not run

6

PR not released (FRGRL = X)

Not selected

Not run

7

Only PR supplier, no source list

RFQ with 1 bidder, W 018

Not run

8

Source list supplier purchasing-blocked

Excluded, W 015

Not run

9

Expired source list entries only, no PR supplier

Item skipped, E 017

Not run

10

Supplier not Ariba-enabled

Excluded, W 016

Not run

11

Publish fails (integration inactive in test)

RFQ exists unpublished, status F, E 023

Not run

12

Re-run immediately

Items excluded, I 011. No duplicate RFQ.

Not run

13

Two RFQ groups in one run

Names -01 and -02, unique

Not run

14

Delivery date < deadline

RFQ created, W 019

Not run

15

User without M\_ANFR\_EKO for org

Items skipped, E 020

Not run

16

Second job started while first running

E 009, second job stops

Not run

17

BO create error (e.g. invalid material for plant)

Rollback of that RFQ only, E 021. Other groups processed.

Not run

## 8 Related Documentation

1.  Functional Specification FS\_ZMM\_PR\_RFQ\_ARIBA v0.1 (Documents panel)
2.  Customer S/4HANA ↔ SAP Ariba Sourcing integration configuration documentation (to be attached)
3.  Released Objects list of the target S/4HANA system (RFQ BO / API verification, TI-01)
4.  Transport requests: to be added at build

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