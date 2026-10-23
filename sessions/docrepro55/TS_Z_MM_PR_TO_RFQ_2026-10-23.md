  TS Z MM PR TO RFQ 2026 10 23 @page { size: A4; margin: 20mm 18mm 20mm 18mm; } \* { box-sizing: border-box; margin: 0; padding: 0; } body { font-family: 'Segoe UI', Calibri, Arial, sans-serif; font-size: 10.5pt; line-height: 1.55; color: #1a1a1a; background: #f4f5f6; -webkit-print-color-adjust: exact; print-color-adjust: exact; } .doc-wrapper { max-width: 1100px; margin: 24px auto; background: #ffffff; box-shadow: 0 1px 8px rgba(0,0,0,0.08); border: 1px solid #d0d4d8; } /\* HEADER \*/ .doc-header { background: #003366; color: #ffffff; padding: 28px 36px 24px 36px; border-bottom: 4px solid #7fb3e0; } .doc-header-top { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 14px; } .doc-logo img { height: 40px; display: block; } .doc-classification { font-size: 8.5pt; letter-spacing: 1.2px; text-transform: uppercase; color: #7fb3e0; border: 1px solid #7fb3e0; padding: 3px 12px; border-radius: 2px; white-space: nowrap; } .doc-header h1 { font-size: 22pt; font-weight: 600; letter-spacing: -0.3px; margin: 0 0 4px 0; line-height: 1.2; } .doc-header .doc-subtitle { font-size: 11pt; color: #7fb3e0; font-weight: 400; } /\* META \*/ .doc-meta { padding: 16px 36px; background: #f7f8fa; border-bottom: 1px solid #d0d4d8; font-size: 9.5pt; color: #444; } .doc-meta table { width: 100%; border-collapse: collapse; } .doc-meta td { padding: 3px 12px 3px 0; vertical-align: top; } .doc-meta .meta-label { font-weight: 600; color: #003366; width: 90px; } /\* BODY \*/ .doc-body { padding: 28px 36px 36px 36px; background: #ffffff; } .doc-body p { margin: 8px 0; } .doc-body h2 { font-size: 14pt; color: #003366; margin: 24px 0 12px 0; padding-bottom: 6px; border-bottom: 2px solid #7fb3e0; display: flex; align-items: center; gap: 10px; } .doc-body h2 .sec-num { display: inline-block; background: #003366; color: white; font-size: 11pt; font-weight: 700; padding: 2px 9px; border-radius: 3px; line-height: 1; min-width: 26px; text-align: center; } .doc-body h3 { font-size: 11.5pt; color: #003366; margin: 18px 0 8px 0; font-weight: 600; } .doc-body h4 { font-size: 10.5pt; color: #1a5c8a; margin: 12px 0 6px 0; font-weight: 600; } .doc-body ul, .doc-body ol { margin: 8px 0 8px 22px; } .doc-body li { margin: 4px 0; } /\* TABLES \*/ table.data { width: 100%; border-collapse: collapse; margin: 10px 0 14px 0; font-size: 9.5pt; } table.data th, table.data td { border: 1px solid #d0d4d8; padding: 7px 10px; text-align: left; vertical-align: top; } table.data th { background: #003366; color: white; font-weight: 600; letter-spacing: 0.2px; } table.data tr:nth-child(even) td { background: #f7f8fa; } table.data td.center { text-align: center; } /\* CALLOUTS \*/ .callout { background: #f0f6fa; border-left: 4px solid #1a5c8a; padding: 12px 16px; margin: 14px 0; font-size: 10pt; color: #1f2937; } .callout.tip { border-left-color: #15803D; background: #f0fdf4; } .callout.warning { border-left-color: #C2410C; background: #fff7ed; } /\* PILLS — Clean Core levels \*/ .pill { display: inline-block; font-size: 8.5pt; font-weight: 600; padding: 2px 9px; border-radius: 10px; letter-spacing: 0.3px; white-space: nowrap; } .pill-a { background: #dcfce7; color: #15803D; } .pill-b { background: #dbeafe; color: #1D4ED8; } .pill-c { background: #fef3c7; color: #A16207; } .pill-d { background: #fee2e2; color: #B91C1C; } /\* SYSTEM PILLS — engagement context strip under the header \*/ .doc-pills { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 14px; } .doc-pills .doc-pill { display: inline-flex; align-items: center; gap: 6px; font-size: 8.5pt; font-weight: 500; padding: 4px 12px; border-radius: 16px; background: rgba(255, 255, 255, 0.12); border: 1px solid rgba(255, 255, 255, 0.28); color: #ffffff; letter-spacing: 0.2px; white-space: nowrap; } .doc-pills .doc-pill .doc-pill-icon { font-size: 9pt; opacity: 0.9; } .doc-pills .doc-pill.danger { background: rgba(254, 226, 226, 0.18); border-color: rgba(254, 226, 226, 0.35); } .doc-pills .doc-pill.warn { background: rgba(254, 243, 199, 0.15); border-color: rgba(254, 243, 199, 0.35); } /\* KPI STRIP — volume counters under the pills \*/ .doc-kpi-strip { display: flex; flex-wrap: wrap; gap: 18px; margin-top: 14px; padding-top: 12px; border-top: 1px solid rgba(255, 255, 255, 0.18); font-size: 9pt; color: rgba(255, 255, 255, 0.92); } .doc-kpi-strip .doc-kpi { display: inline-flex; align-items: center; gap: 5px; white-space: nowrap; } .doc-kpi-strip .doc-kpi-icon { font-size: 10.5pt; } .doc-kpi-strip .doc-kpi-value { font-weight: 700; color: #ffffff; } .doc-kpi-strip .doc-kpi-label { color: rgba(255, 255, 255, 0.78); } /\* PHASE TIMELINE \*/ .phase { border-left: 3px solid #7fb3e0; padding: 10px 16px; margin: 10px 0; background: #f7f8fa; } .phase strong { color: #003366; } .phase .phase-dur { color: #1a5c8a; font-size: 9pt; } /\* DOC FOOTER (inside wrapper) \*/ .doc-footer { background: #f7f8fa; border-top: 1px solid #d0d4d8; padding: 16px 36px; font-size: 9pt; color: #555; } .doc-footer table { width: 100%; } .doc-footer .footer-right { text-align: right; color: #003366; font-weight: 600; } @media print { body { background: white; } .doc-wrapper { box-shadow: none; border: none; margin: 0; max-width: 100%; } h2, h3 { page-break-after: avoid; } table.data { page-break-inside: avoid; } .phase, .callout { page-break-inside: avoid; } }

![C16](data:image/png;base64,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)

Reference

# TS Z MM PR TO RFQ 2026 10 23

Topic

TS Z MM PR TO RFQ 2026 10 23

Date

23 October 2026

Audience

CIOs, SAP program leaders, transformation architects

Author

C16 — AI for SAP operational efficiency

Scope

Version

1.0

**<Customer: Best Run (ECC client 800)>** · **Project: MM Sourcing Automation**  
**TECHNICAL SPECIFICATION – REPORT**  
**Z\_MM\_PR\_TO\_RFQ – Convert Open Purchase Requisitions to RFQs**

# 1 Document Organization

This section provides details about this document, previous version(s) of this document and the document(s) referred.

## 1.1 Document Log

## Following table mentions the version changes and the processer(s):

Version

1.0

Status

Draft

Date

2026-10-23

Version Created by

C16 (generated from FS\_Z\_MM\_PR\_TO\_RFQ\_2026-10-23)

Role

Author

Comments

Initial technical design based on the functional specification and live ECC data model (client 800).

## 1.2 Integration, Document Reference

S. No.

Referred Document Name

Referred Document Version

Referred Document URL (Optional)

1

FS\_Z\_MM\_PR\_TO\_RFQ\_2026-10-23 – Functional Specification

1.0 Draft

Documents panel

2

SAP standard transaction ME41 (Create RFQ, reference to purchase requisition)

ECC 6.0 / SAP\_BASIS 740

–

# 2 Code Quality

Final Solution

Classic executable ABAP report with local classes. Requisitions are read via Open SQL on EBAN/T001W/T001K. RFQs are created through standard transaction ME41 (CALL TRANSACTION, batch input), wrapped behind a local interface so it can later be swapped for a released API.

Category

Level C – classic extensibility (not Code Quality)

Comments

Verified on the live system (TFDIR): no RFQ-creation BAPI (BAPI\_RFQ\_\*) exists on this ECC release. Only display BAPIs exist (BAPI\_PR\_GETDETAIL, BAPI\_REQUISITION\_GETDETAIL). Batch input on ME41 is the only standard-logic path. It works on ECC on-prem and must be re-evaluated for S/4HANA: check the target release for a released RFQ API.

# 3 Program Attributes

Program title

Convert Open Purchase Requisitions to RFQs

Program Name

Z\_MM\_PR\_TO\_RFQ

Program Type

Executable (type 1)

Package

To be confirmed by the user before build (proposed: customer MM package; $TMP for prototype)

Authorization Group

Not assigned (program-level checks via AUTHORITY-CHECK, see 3.4)

Transaction Code

ZMM\_PR2RFQ (proposed)

Include Programs

None – single program with local classes (ECC 7.40 standard)

Function Modules

None directly. Uses CALL TRANSACTION 'ME41' USING bdcdata. ALV via CL\_SALV\_TABLE.

Message Class

ZMM\_PR2RFQ (new – class ZMM does not exist on this system, verified in T100A)

SAP Tables Read

EBAN, T001W, T001K, T001, T024E, T161, LFA1, LFM1, EKKO (post-check of created RFQ)

Custom Tables

None

Custom Indexes

None required. EBAN is read via EKORG plus status fields; volume in the largest org is about 4,600 open lines (approximate).

CDS Views

Not applicable – ECC SAP\_BASIS 740, classic Open SQL

OData Service

Not applicable

Business Object

Not applicable (no BOPF)

Fiori App Name

Not applicable – SAP GUI report

Group Name

Not applicable

Catalog Name

Not applicable

## 3.1 Selection Screen

Parameter / Select Options

15 fields in 4 blocks (B01 Organizational Data, B02 Requisition Selection, B03 RFQ Data, B04 Processing) – detail below

Type / Field Name

Typed against the DDIC field (TYPE table-field / FOR work area of that type)

Mandatory

P\_BUKRS, P\_EKORG, P\_RFQTY, P\_ANGDT; S\_LIFNR mandatory only when P\_TEST is blank (checked in AT SELECTION-SCREEN)

Default Value

P\_RFQTY = AN, P\_ANGDT = sy-datum + 14, P\_TEST = X

ParameterID

BUK (company code), EKO (purchasing org), BAN (PR), EKG (purchasing group), WRK (plant), MAT (material), LIF (vendor)

P / S

P = parameter, S = select-option

Yes / No

See Mandatory column below

Parameter / Select Options

Type / Field Name

Mandatory

Default Value

Parameter ID

Search Help

Selection Screen Text

P P\_BUKRS

T001-BUKRS

Yes

–

BUK

Standard (C\_T001)

Company Code

P P\_EKORG

T024E-EKORG

Yes

–

EKO

Standard (H\_T024E)

Purchasing Organization

S S\_BANFN

FOR gs\_eban-banfn (EBAN-BANFN)

No

–

BAN

Standard

Purchase Requisition

S S\_BSART

FOR gs\_eban-bsart

No

–

–

Standard

PR Document Type

S S\_EKGRP

FOR gs\_eban-ekgrp

No

–

EKG

Standard

Purchasing Group

S S\_WERKS

FOR gs\_eban-werks

No

–

WRK

Standard

Plant

S S\_MATNR

FOR gs\_eban-matnr

No

–

MAT

Standard

Material

S S\_MATKL

FOR gs\_eban-matkl

No

–

–

Standard

Material Group

S S\_BADAT

FOR gs\_eban-badat (DATS)

No

–

–

Calendar

Requisition Date

S S\_LFDAT

FOR gs\_eban-lfdat (DATS)

No

–

–

Calendar

Delivery Date

P P\_RFQTY

EKKO-BSART

Yes

AN

–

Standard

RFQ Type

P P\_ANGDT

EKKO-ANGDT (DATS)

Yes

sy-datum + 14 (INITIALIZATION)

–

Calendar

Quotation Deadline

S S\_LIFNR

FOR gs\_lfa1-lifnr, NO INTERVALS

Yes when P\_TEST blank

–

LIF

Standard (KRED)

Vendors to Invite

P P\_TEST

AS CHECKBOX

No

X

–

–

Test Run (no update)

P P\_LAYO

DISVARIANT-VARIANT

No

–

–

F4 via CL\_SALV\_LAYOUT\_SERVICE=>F4\_LAYOUTS

Layout

Frame titles use the implicit FRAME TITLE variables (≤ 8 characters: gv\_tit1…gv\_tit4), assigned in INITIALIZATION. No explicit DATA declaration for them.

## 3.2 Validation of Selection Criteria

All checks run in AT SELECTION-SCREEN (method lcl\_processor->validate\_selection) through the data-access interface, so ABAP Unit can test them.

#

Field

Check

Message

V1

P\_BUKRS

SELECT SINGLE bukrs, butxt FROM t001 WHERE bukrs = @p\_bukrs

E 001

V2

P\_EKORG

SELECT SINGLE ekorg, ekotx, bukrs FROM t024e. Not found → E 002. T024E-BUKRS ≠ P\_BUKRS and not blank → E 003. Blank → W 004 (cross-company org).

E 002 / E 003 / W 004

V3

P\_EKORG

AUTHORITY-CHECK OBJECT 'M\_ANFR\_EKO' ID 'ACTVT' FIELD '01' ID 'EKORG' FIELD p\_ekorg

E 005

V4

P\_RFQTY

SELECT SINGLE bsart FROM t161 WHERE bstyp = 'A' AND bsart = @p\_rfqty (live values: AB, AN, DIR, PUB). Also AUTHORITY-CHECK M\_ANFR\_BSA.

E 006

V5

P\_ANGDT

P\_ANGDT is not initial and P\_ANGDT ≥ sy-datum (genuine DATS field)

E 007

V6

S\_LIFNR

When P\_TEST is blank, S\_LIFNR\[\] must not be initial

E 008

V7

S\_LIFNR

For each vendor: LFA1 exists, LFA1-SPERM/SPERR/LOEVM blank; LFM1 exists for P\_EKORG with SPERM/LOEVM blank

E 009 (vendor named in MSGV1)

## 3.3 CDS Views/AMDP/Table Function

Not applicable for this object – the target system is ECC SAP\_BASIS 740, and the selection is classic Open SQL in a local data-access class. The selection logic is documented below for completeness.

### 3.3.1 Selection Condition

EBAN-EKORG = P\_EKORG · T001K-BUKRS = P\_BUKRS · EBAN-BSTYP = 'B' · EBAN-LOEKZ = space · EBAN-EBAKZ = space · EBAN-STATU = 'N' · EBAN-FRGRL = space · EBAN-BLCKD = space · EBAN-PSTYP ≠ '9' · BANFN/BSART/EKGRP/WERKS/MATNR/MATKL/BADAT/LFDAT IN the select-options. Post-filter in ABAP: MENGE > BSMNG (open quantity > 0).

### 3.3.2 Join Condition

EBAN INNER JOIN T001W ON T001W-WERKS = EBAN-WERKS INNER JOIN T001K ON T001K-BWKEY = T001W-BWKEY. Both joins are on full primary keys (WERKS, BWKEY), so each EBAN row matches exactly one row and there's no fan-out. Verified mapping: plants 1000/1100/1200/1300 → company code 1000; 3000/3200 → company code 3000.

### 3.3.3 Fields

EBAN: BANFN, BNFPO, BSART, EKGRP, WERKS, MATNR, MATKL, TXZ01, MENGE, BSMNG, MEINS, BADAT, LFDAT. LFA1: LIFNR, NAME1, SPERR, SPERM, LOEVM. LFM1: LIFNR, EKORG, SPERM, LOEVM.

### 3.3.4 Additional Details

All column-backed structure fields are typed TYPE <table>-<field>. Open quantity is typed TYPE eban-menge (single-line value, not an accumulator). Counters for totals are TYPE i.

### 3.3.5 GIT Repository Details

GIT Location

Not applicable – ABAP repository object (abapGit-serialized through the deployment pipeline)

GIT URL

Not applicable

## 3.4 Authorization Requirements

### 3.4.1 Definition

Standard SAP RFQ authorization objects are used; no custom object is needed. ME41 applies its own checks during batch input. The report checks the same objects up front so the user gets a clear message before any document is attempted.

### 3.4.2 Defined Fields

Object

Fields / Values

When

S\_TCODE

TCD = ZMM\_PR2RFQ

Start of transaction

M\_ANFR\_EKO

ACTVT 01, EKORG = P\_EKORG

Selection screen (V3)

M\_ANFR\_BSA

ACTVT 01, BSART = P\_RFQTY

Selection screen (V4)

M\_ANFR\_EKG

ACTVT 01, EKGRP = PR purchasing group

Per RFQ group, before creation

M\_ANFR\_WRK

ACTVT 01, WERKS = PR plant

Per PR line, before creation

M\_BANF\_EKO

ACTVT 03, EKORG = P\_EKORG

Before reading requisitions

### 3.4.3 Procedure

Example: a buyer in org 1000, purchasing group 002, plant 1000, RFQ type AN needs M\_ANFR\_EKO(EKORG 1000, ACTVT 01), M\_ANFR\_EKG(EKGRP 002, 01), M\_ANFR\_WRK(WERKS 1000, 01) and M\_ANFR\_BSA(BSART AN, 01). A missing org/type authorization stops the run (E 005/E 006). A missing group or plant authorization marks only the affected lines red (message E 012) and processing continues.

### 3.4.4 DCL Details

Not applicable for this object – no CDS access control on ECC.

### 3.4.5 BTP Details

xs-security Configuration

Not applicable – on-premise SAP GUI report

IDP Setup

Not applicable

BTP Role Collections

Not applicable

## 3.5 Technical Flow Diagram

#mermaid-1792750556413{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1792750556413 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1792750556413 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1792750556413 .error-icon{fill:#552222;}#mermaid-1792750556413 .error-text{fill:#552222;stroke:#552222;}#mermaid-1792750556413 .edge-thickness-normal{stroke-width:1px;}#mermaid-1792750556413 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1792750556413 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1792750556413 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1792750556413 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1792750556413 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1792750556413 .marker{fill:#666;stroke:#666;}#mermaid-1792750556413 .marker.cross{stroke:#666;}#mermaid-1792750556413 svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-1792750556413 p{margin:0;}#mermaid-1792750556413 .label{font-family:"trebuchet ms",verdana,arial,sans-serif;color:#000000;}#mermaid-1792750556413 .cluster-label text{fill:#333;}#mermaid-1792750556413 .cluster-label span{color:#333;}#mermaid-1792750556413 .cluster-label span p{background-color:transparent;}#mermaid-1792750556413 .label text,#mermaid-1792750556413 span{fill:#000000;color:#000000;}#mermaid-1792750556413 .node rect,#mermaid-1792750556413 .node circle,#mermaid-1792750556413 .node ellipse,#mermaid-1792750556413 .node polygon,#mermaid-1792750556413 .node path{fill:#eee;stroke:#999;stroke-width:1px;}#mermaid-1792750556413 .rough-node .label text,#mermaid-1792750556413 .node .label text,#mermaid-1792750556413 .image-shape .label,#mermaid-1792750556413 .icon-shape .label{text-anchor:middle;}#mermaid-1792750556413 .node .katex path{fill:#000;stroke:#000;stroke-width:1px;}#mermaid-1792750556413 .rough-node .label,#mermaid-1792750556413 .node .label,#mermaid-1792750556413 .image-shape .label,#mermaid-1792750556413 .icon-shape .label{text-align:center;}#mermaid-1792750556413 .node.clickable{cursor:pointer;}#mermaid-1792750556413 .root .anchor path{fill:#666!important;stroke-width:0;stroke:#666;}#mermaid-1792750556413 .arrowheadPath{fill:#333333;}#mermaid-1792750556413 .edgePath .path{stroke:#666;stroke-width:2.0px;}#mermaid-1792750556413 .flowchart-link{stroke:#666;fill:none;}#mermaid-1792750556413 .edgeLabel{background-color:white;text-align:center;}#mermaid-1792750556413 .edgeLabel p{background-color:white;}#mermaid-1792750556413 .edgeLabel rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1792750556413 .labelBkg{background-color:rgba(255, 255, 255, 0.5);}#mermaid-1792750556413 .cluster rect{fill:hsl(0, 0%, 98.9215686275%);stroke:#707070;stroke-width:1px;}#mermaid-1792750556413 .cluster text{fill:#333;}#mermaid-1792750556413 .cluster span{color:#333;}#mermaid-1792750556413 div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:12px;background:hsl(-160, 0%, 93.3333333333%);border:1px solid #707070;border-radius:2px;pointer-events:none;z-index:100;}#mermaid-1792750556413 .flowchartTitleText{text-anchor:middle;font-size:18px;fill:#000000;}#mermaid-1792750556413 rect.text{fill:none;stroke-width:0;}#mermaid-1792750556413 .icon-shape,#mermaid-1792750556413 .image-shape{background-color:white;text-align:center;}#mermaid-1792750556413 .icon-shape p,#mermaid-1792750556413 .image-shape p{background-color:white;padding:2px;}#mermaid-1792750556413 .icon-shape .label rect,#mermaid-1792750556413 .image-shape .label rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1792750556413 .label-icon{display:inline-block;height:1em;overflow:visible;vertical-align:-0.125em;}#mermaid-1792750556413 .node .label-icon path{fill:currentColor;stroke:revert;stroke-width:revert;}#mermaid-1792750556413 :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}

fail

ok

none

rows

yes

no

INITIALIZATION

AT SELECTION-SCREEN: validate\_selection

Checks V1-V7

MESSAGE E - back to screen

select\_open\_prs

Rows after filter?

MESSAGE S 010 DISPLAY LIKE I

build\_groups vendor x EKGRP

P\_TEST?

status = simulated

auth check per group

lif\_rfq\_creator create\_rfq

map EBELN / messages to lines

lcl\_alv\_view display CL\_SALV\_TABLE

End

## 3.6 UI Details

Classic SAP GUI selection screen plus CL\_SALV\_TABLE full-screen ALV. No Fiori/UI5 components.

### 3.6.1 UI Mock Screens

Application Name

Z\_MM\_PR\_TO\_RFQ (SAP GUI, transaction ZMM\_PR2RFQ)

Site

Not applicable – SAP GUI

URL

Not applicable

Mockup

Selection screen: 4 framed blocks as listed in 3.1. Output: full-screen ALV with a header grid (see 4.2–4.4).

### 3.6.2 Navigations

Source View

Target View / URL

Pattern

ALV column BANFN (hotspot)

ME53N – Display Purchase Requisition

SET PARAMETER ID 'BAN' FIELD banfn; CALL TRANSACTION 'ME53N' AND SKIP FIRST SCREEN (with S\_TCODE check)

ALV column EBELN (hotspot)

ME43 – Display RFQ

SET PARAMETER ID 'ANF' FIELD ebeln; CALL TRANSACTION 'ME43' AND SKIP FIRST SCREEN (with S\_TCODE check)

### 3.6.3 Actions

Application

Screen(s)

Action

Type

Action Description

Z\_MM\_PR\_TO\_RFQ

Selection screen 1000

Execute (F8)

Button

Runs validation, selection and (if P\_TEST blank) RFQ creation

Z\_MM\_PR\_TO\_RFQ

Selection screen 1000

F4 on P\_LAYO

Value help

CL\_SALV\_LAYOUT\_SERVICE=>F4\_LAYOUTS for saved layouts

Z\_MM\_PR\_TO\_RFQ

ALV

Standard toolbar

Button

Sort, filter, export to spreadsheet, layout save (set\_all = abap\_true)

Z\_MM\_PR\_TO\_RFQ

ALV

Hotspot click

Event

ON LINK\_CLICK of CL\_SALV\_EVENTS\_TABLE → navigation in 3.6.2

### 3.6.4 Validations

Application

Screen(s)

Field/Button

Validation Logic – Method, function details

Z\_MM\_PR\_TO\_RFQ

1000

P\_BUKRS, P\_EKORG, P\_RFQTY, P\_ANGDT, S\_LIFNR

lcl\_processor->validate\_selection → V1–V7 in 3.2, via lif\_data\_access methods

### 3.6.5 Other Details

Selection-screen texts are maintained as selection texts in the text pool. Frame titles are set in INITIALIZATION.

## 3.7 Processing Logic

**Design for testability.** START-OF-SELECTION only builds the selection structure, creates the processor with injected dependencies, calls run and displays the result. All database access sits behind **lif\_data\_access** and RFQ creation behind **lif\_rfq\_creator**. ABAP Unit uses classic dependency-injection fakes; CL\_OSQL\_TEST\_ENVIRONMENT is not used because it isn't available on SAP\_BASIS 740.

**Step 1 – INITIALIZATION.** gv\_tit1..4 = block titles; P\_ANGDT = sy-datum + 14; P\_RFQTY = 'AN'; P\_TEST = 'X'.

**Step 2 – AT SELECTION-SCREEN.** Build ty\_selection from the screen fields. lcl\_processor->validate\_selection runs V1–V7. On failure, MESSAGE E with class ZMM\_PR2RFQ.

**Step 3 – Read requisitions** (lcl\_db\_access->select\_open\_prs):

SELECT e~banfn, e~bnfpo, e~bsart, e~ekgrp, e~werks, e~matnr, e~matkl,
  e~txz01, e~menge, e~bsmng, e~meins, e~badat, e~lfdat
  FROM eban AS e
  INNER JOIN t001w AS w ON w~werks = e~werks
  INNER JOIN t001k AS k ON k~bwkey = w~bwkey
  WHERE e~ekorg = @is\_sel-ekorg
  AND k~bukrs = @is\_sel-bukrs
  AND e~bstyp = 'B'  AND e~loekz = @space AND e~ebakz = @space
  AND e~statu = 'N'  AND e~frgrl = @space AND e~blckd = @space
  AND e~pstyp <> '9'
  AND e~banfn IN @is\_sel-r\_banfn AND e~bsart IN @is\_sel-r\_bsart
  AND e~ekgrp IN @is\_sel-r\_ekgrp AND e~werks IN @is\_sel-r\_werks
  AND e~matnr IN @is\_sel-r\_matnr AND e~matkl IN @is\_sel-r\_matkl
  AND e~badat IN @is\_sel-r\_badat AND e~lfdat IN @is\_sel-r\_lfdat
  INTO TABLE @rt\_prs.

Then DELETE rt\_prs WHERE menge <= bsmng and compute open\_qty = menge − bsmng. Empty result → MESSAGE S 010 DISPLAY LIKE 'I' and stop.

**Step 4 – Read vendors** (lcl\_db\_access->select\_vendors): LFA1 (LIFNR, NAME1, SPERR, SPERM, LOEVM) WHERE lifnr IN s\_lifnr; LFM1 (LIFNR, EKORG, SPERM, LOEVM) WHERE lifnr IN s\_lifnr AND ekorg = p\_ekorg. Stored in a HASHED table keyed by LIFNR.

**Step 5 – Build output and groups** (lcl\_processor->build\_groups): for each vendor × PR line, append one output row. Group key = LIFNR + EKGRP; each group becomes one RFQ. Sort by EKGRP, LIFNR, BANFN, BNFPO. In a test run without vendors, one row per PR line is shown with blank vendor and status Simulated.

**Step 6 – Test run.** Status icon = ICON\_YELLOW\_LIGHT, message 'Simulated – no RFQ created' (S 013). Go to step 9.

**Step 7 – Update run, per group:**

*   AUTHORITY-CHECK M\_ANFR\_EKG (EKGRP) and M\_ANFR\_WRK (each WERKS). Failure → lines red, E 012, next group.
*   Call io\_creator->create\_rfq( is\_header = {bsart, ekorg, ekgrp, lifnr, angdt, spras} it\_items = PR refs with open qty and LFDAT ) → ev\_ebeln, et\_return TYPE bapiret2\_t.
*   **lcl\_rfq\_creator\_bdc** implementation: builds BDCDATA for ME41 (initial screen: RFQ type, quotation deadline, purchasing org, purchasing group; Reference → Purchase requisition; select the PR items; vendor address screen with LIFNR; save). It then runs CALL TRANSACTION 'ME41' USING lt\_bdc OPTIONS FROM ls\_ctu (DISMODE 'N', UPDMODE 'S', DEFSIZE 'X') MESSAGES INTO lt\_msg. Messages are converted to BAPIRET2 via MESSAGE\_TEXT\_BUILD-equivalent formatting (MESSAGE ID … INTO lv\_text). The new RFQ number is taken from the success message variables; the exact screen numbers/fields and success message ID are recorded in SHDB during build (see Open Issues).
*   Post-check: SELECT SINGLE ebeln FROM ekko WHERE ebeln = @ev\_ebeln AND bstyp = 'A' to confirm the document exists. On success all group lines get ICON\_GREEN\_LIGHT, EBELN and message S 011. On failure, ICON\_RED\_LIGHT and the first E/A message from et\_return.
*   UPDMODE 'S' (synchronous) means each RFQ is committed by ME41 itself. No COMMIT WORK in the report, and no cross-group rollback; each RFQ is an independent LUW.

**Step 8 – Counters.** gv\_lines (TYPE i), gv\_rfq\_ok (TYPE i), gv\_err (TYPE i) for the header.

**Step 9 – Display** lcl\_alv\_view->display (see section 4).

**Data model / hierarchy:** EBAN (PR item) → T001W (plant → valuation area) → T001K (valuation area → company code); T024E (purchasing org → company code); T161 (RFQ type, BSTYP A); LFA1/LFM1 (vendor general / purchasing data); EKKO/EKPO (created RFQ; EKPO-BANFN/BNFPO hold the PR reference).

## 3.8 Reusable Code

No external reusable modules. The local interfaces lif\_data\_access and lif\_rfq\_creator are designed so the BDC implementation can later be replaced (for example by a released RFQ API on S/4HANA) without touching lcl\_processor or the tests.

## 3.9 Messages

Message Class

ZMM\_PR2RFQ (to be created in SE91)

Message Class

Message ID

Message Text

ZMM\_PR2RFQ

001

Company code &1 does not exist

ZMM\_PR2RFQ

002

Purchasing organization &1 does not exist

ZMM\_PR2RFQ

003

Purchasing organization &1 is assigned to company code &2, not &3

ZMM\_PR2RFQ

004

Purchasing organization &1 is cross-company (no company code assigned)

ZMM\_PR2RFQ

005

No authorization to create RFQs in purchasing organization &1

ZMM\_PR2RFQ

006

&1 is not a valid RFQ document type (or not authorized)

ZMM\_PR2RFQ

007

Quotation deadline must not be in the past

ZMM\_PR2RFQ

008

Enter at least one vendor for an update run

ZMM\_PR2RFQ

009

Vendor &1 does not exist, is blocked, or is not maintained for org &2

ZMM\_PR2RFQ

010

No open purchase requisitions match the selection

ZMM\_PR2RFQ

011

RFQ &1 created for vendor &2

ZMM\_PR2RFQ

012

No authorization for purchasing group &1 / plant &2

ZMM\_PR2RFQ

013

Simulated – no RFQ created (test run)

## 3.10 Subroutines

No FORM routines (company standard). The local class methods below replace subroutines.

Name

Description

LAYOUT\_BUILD

Implemented as lcl\_alv\_view->set\_columns – builds the ALV column layout and texts

Name

Description

lif\_data\_access~check\_company\_code / get\_purch\_org / check\_rfq\_type

Master-data reads for V1/V2/V4 (T001, T024E, T161)

lif\_data\_access~select\_open\_prs( is\_sel ) RETURNING rt\_prs

EBAN ⋈ T001W ⋈ T001K selection (step 3)

lif\_data\_access~select\_vendors( it\_lifnr, iv\_ekorg ) RETURNING rt\_vendors

LFA1 + LFM1 reads and block checks (V7)

lif\_rfq\_creator~create\_rfq( is\_header, it\_items ) EXPORTING ev\_ebeln, et\_return TYPE bapiret2\_t

RFQ creation seam; production implementation lcl\_rfq\_creator\_bdc (ME41)

lcl\_processor->constructor( io\_dao, io\_creator, is\_sel )

Dependency injection

lcl\_processor->validate\_selection RETURNING rt\_return

Checks V1–V7

lcl\_processor->run RETURNING rt\_output

Steps 3–8

lcl\_processor->build\_groups

Vendor × purchasing-group grouping

lcl\_alv\_view->display( ct\_output, is\_summary )

CL\_SALV\_TABLE factory, columns, sort, header, events, display

lcl\_alv\_view->on\_link\_click

Hotspot navigation to ME53N / ME43

# 4 Report Output

## 4.1 Output Method

Full-screen ALV (CL\_SALV\_TABLE) in dialog. Download to spreadsheet and print are available through the standard ALV toolbar. In background (SM36) the ALV is written to the spool list.

## 4.2 Main Heading

Main heading (ALV title): **Purchase Requisitions → RFQ Conversion**.

## 4.3 Sub Heading

Header grid (CL\_SALV\_FORM\_LAYOUT\_GRID via set\_top\_of\_list): Company code <BUKRS> <BUTXT> · Purchasing org <EKORG> <EKOTX> · Run mode TEST RUN / UPDATE RUN · RFQ type <BSART> · Quotation deadline <ANGDT> · Executed by <sy-uname> on <sy-datum> <sy-uzeit>.

## 4.4 Layout / UI Design

#

Field

Typed as

Notes

1

STATUS

icon\_d

Traffic light, icon column

2

BANFN

eban-banfn

Hotspot

3

BNFPO

eban-bnfpo

4

BSART

eban-bsart

5

EKGRP

eban-ekgrp

6

WERKS

eban-werks

7

MATNR

eban-matnr

8

TXZ01

eban-txz01

9

OPEN\_QTY

eban-menge

MENGE − BSMNG; quantity reference MEINS

10

MEINS

eban-meins

11

LFDAT

eban-lfdat

12

LIFNR

lfa1-lifnr

13

NAME1

lfa1-name1

14

EBELN

ekko-ebeln

Hotspot; blank in test run

15

MESSAGE

bapi\_msg

Long text set explicitly (non-DDIC label)

Column labels come from the DDIC data elements; only STATUS and MESSAGE get explicit texts. Zebra pattern and column optimization are on. Bulkhead TRY blocks: factory (fatal), columns (warning), sort (silent), display() outside all TRY blocks.

## 4.5 Totaling

No quantity totals (units differ per line). The header shows counts: PR lines selected, RFQs created, lines with errors (TYPE i counters).

## 4.6 Sorting

Default sort: EKGRP ↑, LIFNR ↑, BANFN ↑, BNFPO ↑ (add\_sort with sequence = if\_salv\_c\_sort=>sort\_up). Users can re-sort and save layouts.

## 4.7 Page Break

Not applicable for this object – ALV handles paging. No custom page breaks.

## 4.8 Error Handling

Error

Detection

User sees

Invalid selection / missing authorization

validate\_selection

E message, stays on selection screen

No data

Empty rt\_prs

S 010 displayed as information, no ALV

ME41 error (PR locked, vendor blocked, missing field)

E/A message in MESSAGES INTO table

Group lines red with the SAP message text; other groups continue

Phantom success (no RFQ number)

ev\_ebeln initial or EKKO post-check fails

Lines red: "RFQ not confirmed – check ME43"

ALV factory failure

CATCH cx\_salv\_msg

E message with exception text

Column config failure

CATCH cx\_salv\_not\_found

S message displayed as warning; list still shown

## 4.9 Report Header & Footer

Header as in 4.3. No footer; the project default applies.

# 5 Assumptions in Technical Design

*   No RFQ-creation BAPI exists on this ECC release (verified in TFDIR), so ME41 batch input is the creation method.
*   One RFQ per vendor × purchasing group (standard competitive-bidding pattern; ME41 holds one vendor per RFQ).
*   PRs with processing status A (already referenced by an RFQ) are excluded to prevent duplicates, e.g. PR 0010048199.
*   Company code is derived through plant → valuation area (T001W/T001K), because EBAN has no company-code field.
*   Code is written for SAP\_BASIS 740: new Open SQL syntax with @, inline declarations, no CDS/AMDP/REDUCE/enums.

# 6 Open Issues in Technical Design

#

Issue

Action

1

ME41 screen sequence (dynpro numbers, field names for reference-to-PR and item selection) and the success message carrying the RFQ number must be recorded in SHDB on this system.

Developer – record before build

2

Package and transport for the build.

User to confirm

3

Message class ZMM\_PR2RFQ and transaction ZMM\_PR2RFQ must be created.

Developer

4

982 open PR lines have no purchasing org and will never be selected.

MM business decision

5

S/4HANA readiness: replace lcl\_rfq\_creator\_bdc with a released RFQ API when the system is converted (verify on the target release).

Architecture

# 7 Unit Test Results

Not yet executed – the program has not been built. The planned ABAP Unit class ltc\_processor (FOR TESTING RISK LEVEL HARMLESS DURATION SHORT) uses ltd\_fake\_dao / ltd\_fake\_creator. Integration scenarios are grounded in live client-800 data.

Scenario #

10 scenarios planned (below)

Input Selection Criteria

See table below

Expected Result

See table below

Actual Test Pass/Fail

Not run

Scenario #

Input Selection Criteria

Expected Result

Actual Test Pass/Fail

1

BUKRS 1000, EKORG 1000, BANFN 0010011043–0010011045, P\_TEST = X

8 lines, yellow, no RFQ

Not run

2

As 1, vendors 0000001101 + 0000001102, RFQ type AN, P\_TEST blank

2 RFQs (EKGRP 002), 8 items each; EBAN-STATU → A

Not run

3

Re-run of 2

S 010 – no data

Not run

4

BUKRS 1000, EKORG 3000

E 003 (org 3000 → company code 3000)

Not run

5

BUKRS 1000, EKORG 1000, BANFN 0010013784

Selected (plant 1300 → company code 1000)

Not run

6

BUKRS 3000, EKORG 3000, BANFN 0010008603

1 line, material IT1008, plant 3000

Not run

7

P\_RFQTY = NB

E 006

Not run

8

P\_ANGDT = sy-datum − 1

E 007

Not run

9

Fake DAO returns line with MENGE = BSMNG (boundary)

Line excluded; empty → S 010

Not run

10

Fake creator returns E message / empty EBELN

Lines red, other groups processed

Not run

# 8 Related Documentation

FS\_Z\_MM\_PR\_TO\_RFQ\_2026-10-23 (functional specification). SAP transactions ME41 / ME43 / ME53N / ME57. Live data references: EBAN, T024E, T161, T001K, EKKO (client 800, read 23 Oct 2026).

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