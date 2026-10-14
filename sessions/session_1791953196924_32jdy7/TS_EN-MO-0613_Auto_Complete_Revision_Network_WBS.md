  TS EN MO 0613 Auto Complete Revision Network WBS @page { size: A4; margin: 20mm 18mm 20mm 18mm; } \* { box-sizing: border-box; margin: 0; padding: 0; } body { font-family: 'Segoe UI', Calibri, Arial, sans-serif; font-size: 10.5pt; line-height: 1.55; color: #1a1a1a; background: #f4f5f6; -webkit-print-color-adjust: exact; print-color-adjust: exact; } .doc-wrapper { max-width: 1100px; margin: 24px auto; background: #ffffff; box-shadow: 0 1px 8px rgba(0,0,0,0.08); border: 1px solid #d0d4d8; } /\* HEADER \*/ .doc-header { background: #003366; color: #ffffff; padding: 28px 36px 24px 36px; border-bottom: 4px solid #7fb3e0; } .doc-header-top { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 14px; } .doc-logo img { height: 40px; display: block; } .doc-classification { font-size: 8.5pt; letter-spacing: 1.2px; text-transform: uppercase; color: #7fb3e0; border: 1px solid #7fb3e0; padding: 3px 12px; border-radius: 2px; white-space: nowrap; } .doc-header h1 { font-size: 22pt; font-weight: 600; letter-spacing: -0.3px; margin: 0 0 4px 0; line-height: 1.2; } .doc-header .doc-subtitle { font-size: 11pt; color: #7fb3e0; font-weight: 400; } /\* META \*/ .doc-meta { padding: 16px 36px; background: #f7f8fa; border-bottom: 1px solid #d0d4d8; font-size: 9.5pt; color: #444; } .doc-meta table { width: 100%; border-collapse: collapse; } .doc-meta td { padding: 3px 12px 3px 0; vertical-align: top; } .doc-meta .meta-label { font-weight: 600; color: #003366; width: 90px; } /\* BODY \*/ .doc-body { padding: 28px 36px 36px 36px; background: #ffffff; } .doc-body p { margin: 8px 0; } .doc-body h2 { font-size: 14pt; color: #003366; margin: 24px 0 12px 0; padding-bottom: 6px; border-bottom: 2px solid #7fb3e0; display: flex; align-items: center; gap: 10px; } .doc-body h2 .sec-num { display: inline-block; background: #003366; color: white; font-size: 11pt; font-weight: 700; padding: 2px 9px; border-radius: 3px; line-height: 1; min-width: 26px; text-align: center; } .doc-body h3 { font-size: 11.5pt; color: #003366; margin: 18px 0 8px 0; font-weight: 600; } .doc-body h4 { font-size: 10.5pt; color: #1a5c8a; margin: 12px 0 6px 0; font-weight: 600; } .doc-body ul, .doc-body ol { margin: 8px 0 8px 22px; } .doc-body li { margin: 4px 0; } /\* TABLES \*/ table.data { width: 100%; border-collapse: collapse; margin: 10px 0 14px 0; font-size: 9.5pt; } table.data th, table.data td { border: 1px solid #d0d4d8; padding: 7px 10px; text-align: left; vertical-align: top; } table.data th { background: #003366; color: white; font-weight: 600; letter-spacing: 0.2px; } table.data tr:nth-child(even) td { background: #f7f8fa; } table.data td.center { text-align: center; } /\* CALLOUTS \*/ .callout { background: #f0f6fa; border-left: 4px solid #1a5c8a; padding: 12px 16px; margin: 14px 0; font-size: 10pt; color: #1f2937; } .callout.tip { border-left-color: #15803D; background: #f0fdf4; } .callout.warning { border-left-color: #C2410C; background: #fff7ed; } /\* PILLS — Clean Core levels \*/ .pill { display: inline-block; font-size: 8.5pt; font-weight: 600; padding: 2px 9px; border-radius: 10px; letter-spacing: 0.3px; white-space: nowrap; } .pill-a { background: #dcfce7; color: #15803D; } .pill-b { background: #dbeafe; color: #1D4ED8; } .pill-c { background: #fef3c7; color: #A16207; } .pill-d { background: #fee2e2; color: #B91C1C; } /\* SYSTEM PILLS — engagement context strip under the header \*/ .doc-pills { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 14px; } .doc-pills .doc-pill { display: inline-flex; align-items: center; gap: 6px; font-size: 8.5pt; font-weight: 500; padding: 4px 12px; border-radius: 16px; background: rgba(255, 255, 255, 0.12); border: 1px solid rgba(255, 255, 255, 0.28); color: #ffffff; letter-spacing: 0.2px; white-space: nowrap; } .doc-pills .doc-pill .doc-pill-icon { font-size: 9pt; opacity: 0.9; } .doc-pills .doc-pill.danger { background: rgba(254, 226, 226, 0.18); border-color: rgba(254, 226, 226, 0.35); } .doc-pills .doc-pill.warn { background: rgba(254, 243, 199, 0.15); border-color: rgba(254, 243, 199, 0.35); } /\* KPI STRIP — volume counters under the pills \*/ .doc-kpi-strip { display: flex; flex-wrap: wrap; gap: 18px; margin-top: 14px; padding-top: 12px; border-top: 1px solid rgba(255, 255, 255, 0.18); font-size: 9pt; color: rgba(255, 255, 255, 0.92); } .doc-kpi-strip .doc-kpi { display: inline-flex; align-items: center; gap: 5px; white-space: nowrap; } .doc-kpi-strip .doc-kpi-icon { font-size: 10.5pt; } .doc-kpi-strip .doc-kpi-value { font-weight: 700; color: #ffffff; } .doc-kpi-strip .doc-kpi-label { color: rgba(255, 255, 255, 0.78); } /\* PHASE TIMELINE \*/ .phase { border-left: 3px solid #7fb3e0; padding: 10px 16px; margin: 10px 0; background: #f7f8fa; } .phase strong { color: #003366; } .phase .phase-dur { color: #1a5c8a; font-size: 9pt; } /\* DOC FOOTER (inside wrapper) \*/ .doc-footer { background: #f7f8fa; border-top: 1px solid #d0d4d8; padding: 16px 36px; font-size: 9pt; color: #555; } .doc-footer table { width: 100%; } .doc-footer .footer-right { text-align: right; color: #003366; font-weight: 600; } @media print { body { background: white; } .doc-wrapper { box-shadow: none; border: none; margin: 0; max-width: 100%; } h2, h3 { page-break-after: avoid; } table.data { page-break-inside: avoid; } .phase, .callout { page-break-inside: avoid; } }

![C16](data:image/png;base64,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)

Reference

# TS EN MO 0613 Auto Complete Revision Network WBS

Topic

TS EN MO 0613 Auto Complete Revision Network WBS

Date

14 October 2026

Audience

CIOs, SAP program leaders, transformation architects

Author

C16 — AI for SAP operational efficiency

Scope

Version

1.0

## 1 Document Organization

### 1.1 Document Log

Version

Status

Date

Created By

Role

Comments

0.1

Draft

2026-10-14

C16 Auto-Generated

Author

Initial TS draft based on FSD EN-MO-0613 v0.1 (Muralikrishna K, 10-Sep-2026)

### 1.2 Integration, Document Reference

S. No.

Referred Document Name

Version

URL

1

FSD\_EN-MO-0613 Auto Complete Network, WBS and Revision

0.1

Project Polaris Lodestar Phase 2A repository

2

Email Template MO-0595

—

Referenced for WBS TECO email notification

## 2 Code Quality

Final Solution

Category

Comments

Custom batch program using standard BAPIs (BAPI\_BUS2002\_SET\_STATUS, BAPI\_BUS2054\_SET\_STATUS) and partner BAPI (/AXONEBX/GET\_REV\_CLOSE)

**Tier 3 — Legacy Development**

Classic ABAP executable with standard BAPIs for status changes. Level B compliance (classic APIs). Compatible with S/4HANA on-premise. A Fiori Tile for monitoring is planned separately per SIA Code Quality Strategy. No direct DML on standard tables — all updates via BAPIs.

## 3 Program Attributes

Attribute

Value

**Program Title**

Auto Complete Revision, Network and WBS

**Program Name**

ZEN\_MO\_0613\_AUTO\_COMPLETE

**Program Type**

Executable (REPORT type — background batch job)

**Package**

ZPM\_POLARIS\_P2A

**Authorization Group**

As per BU decision

**RICEFWA ID**

EN-MO-0613

**Project**

Polaris Lodestar Phase 2A

**Application System**

S/4HANA

Attribute

Value

**Transaction Code**

N/A — Background batch job (SM36/SM37)

**Include Programs**

N/A

**Function Modules**

/AXONEBX/GET\_REV\_CLOSE, BAPI\_BUS2002\_SET\_STATUS, BAPI\_BUS2054\_SET\_STATUS, BAPI\_TRANSACTION\_COMMIT

**Message Class**

ZPM\_AUTOCOMPLETE (custom) + BAPI return messages (BAPIRETURN1)

Attribute

Value

**SAP Tables Read**

T352R (Revisions), JEST (Object Status), DIWPS\_RV\_CR (Revision Check Records), QMEL (Notifications), AUFK (Orders/WBS), T325R (Revision-Network link)

**Custom Tables**

N/A — No custom tables required

**Custom Indexes**

N/A

**CDS Views**

N/A — Not applicable for this batch program

**OData Service**

N/A — Background batch job

**Business Object**

BUS2002 (Network), BUS2054 (WBS Element)

**Fiori App Name**

To be developed as per SIA Code Quality Strategy (Fiori Tile for job monitoring)

### 3.1 Selection Screen

**Block: Revision Selection Criteria**

P/S

Type / Field Name

Mandatory

Default

Parameter ID

Search Help

Screen Text

S

T352R-REVNR

No

—

S\_REVNR

Standard (REVNI)

Revision Number

S

T352R-REVTY

No

—

S\_REVTY

Standard (DIWPS\_REVTY\_CORE)

Revision Type

S

T352R-REVBD

No

—

S\_REVBD

Standard (Date)

Revision Start Date

S

T352R-REVED

No

—

S\_REVED

Standard (Date)

Revision End Date

S

T352R-IWERK

No

—

S\_IWERK

Standard (IWERK)

Planning Plant of Revision

S

T352R-VAPLZ

No

—

S\_VAPLZ

Standard (GEWRK)

Main Workcenter for Revision

S

T352R-VAWRK

No

—

S\_VAWRK

Standard (WERGW)

Main Workcenter Plant

S

T352R-ZZ\_ESLOT\_START

No

—

S\_ESLOTS

Standard (Date)

eSLOT Start Date

S

T352R-ZZ\_ESLOT\_END

No

—

S\_ESLOTE

Standard (Date)

eSLOT End Date

P

TYPE I (Integer)

No

60

P\_DAYS

N/A

XX Days Threshold (Days from current date)

### 3.2 Validation of Selection Criteria

1\. At least one selection criterion must be provided — error message ZPM\_AUTOCOMPLETE 010 if all fields are blank.

2\. P\_DAYS must be a positive integer > 0. Default value = 60.

3\. Date ranges: S\_REVBD low ≤ high; S\_ESLOTS low ≤ S\_ESLOTE high.

4\. Planning Plant (S\_IWERK) validated against T001W for existence.

### 3.3 CDS Views / AMDP / Table Function

Not applicable for this object. This is a background batch program using classic ABAP with standard BAPIs.

### 3.4 Authorization Requirements

**Definition:** Standard SAP authorization objects used. BAPIs enforce internal authorization.

Auth Object

Field

Value

Activity

S\_TCODE

TCD

ZEN\_MO\_0613

16 (Execute)

I\_IWERK

IWERK

Plant values from selection screen

02 (Change)

**DCL Details:** Not applicable — classic ABAP batch program.

**BTP Details:** Not applicable — S/4HANA on-premise program.

### 3.5 Technical Flow Diagram

#mermaid-1791953878348{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1791953878348 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1791953878348 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1791953878348 .error-icon{fill:#552222;}#mermaid-1791953878348 .error-text{fill:#552222;stroke:#552222;}#mermaid-1791953878348 .edge-thickness-normal{stroke-width:1px;}#mermaid-1791953878348 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1791953878348 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1791953878348 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1791953878348 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1791953878348 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1791953878348 .marker{fill:#666;stroke:#666;}#mermaid-1791953878348 .marker.cross{stroke:#666;}#mermaid-1791953878348 svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-1791953878348 p{margin:0;}#mermaid-1791953878348 .label{font-family:"trebuchet ms",verdana,arial,sans-serif;color:#000000;}#mermaid-1791953878348 .cluster-label text{fill:#333;}#mermaid-1791953878348 .cluster-label span{color:#333;}#mermaid-1791953878348 .cluster-label span p{background-color:transparent;}#mermaid-1791953878348 .label text,#mermaid-1791953878348 span{fill:#000000;color:#000000;}#mermaid-1791953878348 .node rect,#mermaid-1791953878348 .node circle,#mermaid-1791953878348 .node ellipse,#mermaid-1791953878348 .node polygon,#mermaid-1791953878348 .node path{fill:#eee;stroke:#999;stroke-width:1px;}#mermaid-1791953878348 .rough-node .label text,#mermaid-1791953878348 .node .label text,#mermaid-1791953878348 .image-shape .label,#mermaid-1791953878348 .icon-shape .label{text-anchor:middle;}#mermaid-1791953878348 .node .katex path{fill:#000;stroke:#000;stroke-width:1px;}#mermaid-1791953878348 .rough-node .label,#mermaid-1791953878348 .node .label,#mermaid-1791953878348 .image-shape .label,#mermaid-1791953878348 .icon-shape .label{text-align:center;}#mermaid-1791953878348 .node.clickable{cursor:pointer;}#mermaid-1791953878348 .root .anchor path{fill:#666!important;stroke-width:0;stroke:#666;}#mermaid-1791953878348 .arrowheadPath{fill:#333333;}#mermaid-1791953878348 .edgePath .path{stroke:#666;stroke-width:2.0px;}#mermaid-1791953878348 .flowchart-link{stroke:#666;fill:none;}#mermaid-1791953878348 .edgeLabel{background-color:white;text-align:center;}#mermaid-1791953878348 .edgeLabel p{background-color:white;}#mermaid-1791953878348 .edgeLabel rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1791953878348 .labelBkg{background-color:rgba(255, 255, 255, 0.5);}#mermaid-1791953878348 .cluster rect{fill:hsl(0, 0%, 98.9215686275%);stroke:#707070;stroke-width:1px;}#mermaid-1791953878348 .cluster text{fill:#333;}#mermaid-1791953878348 .cluster span{color:#333;}#mermaid-1791953878348 div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:12px;background:hsl(-160, 0%, 93.3333333333%);border:1px solid #707070;border-radius:2px;pointer-events:none;z-index:100;}#mermaid-1791953878348 .flowchartTitleText{text-anchor:middle;font-size:18px;fill:#000000;}#mermaid-1791953878348 rect.text{fill:none;stroke-width:0;}#mermaid-1791953878348 .icon-shape,#mermaid-1791953878348 .image-shape{background-color:white;text-align:center;}#mermaid-1791953878348 .icon-shape p,#mermaid-1791953878348 .image-shape p{background-color:white;padding:2px;}#mermaid-1791953878348 .icon-shape .label rect,#mermaid-1791953878348 .image-shape .label rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1791953878348 .label-icon{display:inline-block;height:1em;overflow:visible;vertical-align:-0.125em;}#mermaid-1791953878348 .node .label-icon path{fill:currentColor;stroke:revert;stroke-width:revert;}#mermaid-1791953878348 :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}

No

Yes

No

Yes

No

Yes

No

Yes

No

Yes

Yes

No

Done

START: Read Selection Parameters

SELECT Revisions from T352R

For Each Revision

Check Status = REL via JEST  
STAT=I0002, INACT≠X

Check REVED ≤ SY-DATUM - P\_DAYS

Get Notifications/Orders  
from DIWPS\_RV\_CR

All Notifications  
NOCO? I0072

Log Error: Open items  
Skip revision

All Orders  
CLSD? I0046

Close Revision  
/AXONEBX/GET\_REV\_CLOSE + COMMIT

Network linked?

Log: Revision closed  
without network

All other revisions  
for network CLSD?

Log Error: Revision open  
Skip network TECO

TECO Network  
BAPI\_BUS2002\_SET\_STATUS + COMMIT

All other networks  
for WBS TECO?

Log Error: Network open  
Skip WBS TECO

TECO WBS  
BAPI\_BUS2054\_SET\_STATUS + COMMIT

Plant = ECE2?

Send Email to EC FI  
via CL\_BCS / SO15 / MO-0595

Log success only

Display/Spool  
Consolidated Log via CL\_SALV\_TABLE

END

### 3.6 UI Details

Not applicable — this is a background batch program with no interactive UI. The selection screen is used only for variant maintenance in SM36. A Fiori Tile for job monitoring is planned separately per SIA Code Quality Strategy.

### 3.7 Processing Logic

**STEP 1 — FETCH REVISIONS:**

SELECT REVNR, REVTY, REVBD, REVED, IWERK, VAPLZ, VAWRK, OBJNR, AUFNR, ZZ\_ESLOT\_START, ZZ\_ESLOT\_END FROM T352R INTO TABLE lt\_revisions WHERE REVNR IN S\_REVNR AND REVTY IN S\_REVTY AND REVBD IN S\_REVBD AND REVED IN S\_REVED AND IWERK IN S\_IWERK AND VAPLZ IN S\_VAPLZ AND VAWRK IN S\_VAWRK. Filter additionally by ZZ\_ESLOT\_START IN S\_ESLOTS AND ZZ\_ESLOT\_END IN S\_ESLOTE.

**STEP 2 — FILTER BY STATUS (REL) AND AGE:**

FOR ALL ENTRIES IN lt\_revisions: SELECT OBJNR, STAT FROM JEST WHERE OBJNR = lt\_revisions-OBJNR AND STAT = 'I0002' AND INACT <> 'X'. Additionally filter: REVED ≤ SY-DATUM - P\_DAYS (default 60 days).

**STEP 3 — GET LINKED NOTIFICATIONS AND ORDERS:**

FOR ALL ENTRIES IN lt\_released\_revisions: SELECT WPID, NOTIFID, ORDER\_NO FROM DIWPS\_RV\_CR WHERE WPID = lt\_released\_revisions-REVNR. Note: DIWPS\_RV\_CR field WPID maps to revision number (data element REVNI, CHAR 8).

**STEP 4 — CHECK NOTIFICATION STATUS (NOCO = I0072):**

For each notification: SELECT QMNUM, OBJNR FROM QMEL WHERE QMNUM = notification-id. Then check JEST for STAT = 'I0072' AND INACT <> 'X'. If ANY notification lacks NOCO → mark revision as 'cannot close', log ZPM\_AUTOCOMPLETE 001.

**STEP 5 — CHECK ORDER STATUS (CLSD = I0046):**

For each order: SELECT AUFNR, OBJNR FROM AUFK WHERE AUFNR = order-no. Then check JEST for STAT = 'I0046' AND INACT <> 'X'. If ANY order lacks CLSD → mark revision as 'cannot close', log ZPM\_AUTOCOMPLETE 001.

**STEP 6 — CLOSE REVISION (CLSD):**

If all notifications NOCO and all orders CLSD: CALL FUNCTION '/AXONEBX/GET\_REV\_CLOSE' EXPORTING I\_REVNR = lv\_revnr I\_WERKS = lv\_iwerk. On success → BAPI\_TRANSACTION\_COMMIT WAIT='X'. Log ZPM\_AUTOCOMPLETE 004. If no linked network (T352R-AUFNR is initial) → Log ZPM\_AUTOCOMPLETE 007, continue to next revision.

**STEP 7 — CLOSE NETWORK (TECO = I0045):**

Get network AUFNR from T352R for the closed revision. Check other revisions linked to same network: SELECT REVNR FROM T325R WHERE AUFNR = lv\_network AND REVNR <> current. For each other revision, check JEST for CLSD (I0046). If ALL other revisions CLSD: CALL FUNCTION 'BAPI\_BUS2002\_SET\_STATUS' EXPORTING NUMBER = lv\_network SET\_SYSTEM\_STATUS = 'I0045'. Check RETURN (TYPE BAPIRETURN1 — fields: TYPE, ID, NUMBER, MESSAGE, MESSAGE\_V1..V4). On success → COMMIT. Log ZPM\_AUTOCOMPLETE 005.

**STEP 8 — CLOSE WBS (TECO = I0045):**

Get WBS element: SELECT PSPEL FROM AUFK WHERE AUFNR = lv\_network. PSPEL is NUMC 8 (data element PS\_PSP\_ELE). Convert to external format via CONVERSION\_EXIT\_ABPSP\_OUTPUT for BAPI parameter WBS\_ELEMENT (PS\_POSID, CHAR 24). Check other networks for same WBS. If ALL networks TECO: Populate lt\_wbs\_status TYPE BAPI\_WBS\_MNT\_SYSTEM\_STATUS (WBS\_ELEMENT = external, SET\_SYSTEM\_STATUS = 'TECO'). CALL FUNCTION 'BAPI\_BUS2054\_SET\_STATUS' TABLES I\_WBS\_SYSTEM\_STATUS = lt\_wbs\_status. Check RETURN. COMMIT. Log ZPM\_AUTOCOMPLETE 006.

**STEP 9 — EMAIL NOTIFICATION (Plant ECE2 only):**

If WBS TECO'd AND T352R-IWERK = 'ECE2': Read distribution list SO15 for EC FI email addresses. Send email via CL\_BCS using MO-0595 template. Log ZPM\_AUTOCOMPLETE 008 on success, 009 on failure.

**STEP 10 — DISPLAY LOG:**

Consolidate all messages. Log columns: Revision No | Network No | WBS Element | Step | Status (S/E/W/I) | Message Text. If SY-BATCH = 'X' → output to spool. If foreground → display via CL\_SALV\_TABLE.

### 3.8 Reusable Code

Method / Subroutine

Description

CHECK\_OBJECT\_STATUS

Generic method: checks if OBJNR has a specific system status in JEST (INACT ≠ 'X'). Params: IV\_OBJNR TYPE J\_OBJNR, IV\_STATUS TYPE J\_STATUS → RV\_HAS\_STATUS TYPE ABAP\_BOOL. Reused for REL, NOCO, CLSD, TECO.

GET\_LINKED\_ITEMS

Retrieves linked Notifications (NOTIFID) and Orders (ORDER\_NO) from DIWPS\_RV\_CR for a given revision (WPID).

CLOSE\_REVISION

Calls /AXONEBX/GET\_REV\_CLOSE BAPI with I\_REVNR and I\_WERKS. Handles BAPI return messages and commit/rollback.

CLOSE\_NETWORK

Validates all linked revisions are CLSD via T325R, then calls BAPI\_BUS2002\_SET\_STATUS with SET\_SYSTEM\_STATUS = 'I0045'.

CLOSE\_WBS

Validates all linked networks are TECO, converts WBS internal PSPEL → external format, calls BAPI\_BUS2054\_SET\_STATUS.

SEND\_EMAIL\_ECE2

CL\_BCS email wrapper: reads SO15 distribution list, sends using MO-0595 template. Only for plant ECE2.

BUILD\_LOG\_OUTPUT

Consolidates processing messages into ALV-compatible internal table. Renders via CL\_SALV\_TABLE (foreground) or spool (background).

CONVERT\_WBS\_ELEMENT

Wrapper for CONVERSION\_EXIT\_ABPSP\_OUTPUT to convert internal PSPEL (NUMC 8) → external WBS (CHAR 24) for BAPI.

### 3.9 Messages

Message Class

ID

Type

Message Text

ZPM\_AUTOCOMPLETE

001

E

Notification &1 and Order &2 are open — cannot close revision &3.

ZPM\_AUTOCOMPLETE

002

E

Revision &1 is open — cannot TECO network &2.

ZPM\_AUTOCOMPLETE

003

E

Network &1 not yet TECO — cannot close WBS &2.

ZPM\_AUTOCOMPLETE

004

S

Revision &1 successfully closed (CLSD).

ZPM\_AUTOCOMPLETE

005

S

Network &1 successfully completed (TECO).

ZPM\_AUTOCOMPLETE

006

S

WBS Element &1 successfully completed (TECO).

ZPM\_AUTOCOMPLETE

007

I

Revision &1 closed without network.

ZPM\_AUTOCOMPLETE

008

S

Email notification sent to EC FI for WBS &1 (Plant ECE2).

ZPM\_AUTOCOMPLETE

009

W

Email notification failed for WBS &1 — &2.

ZPM\_AUTOCOMPLETE

010

I

No data found matching selection criteria.

Additionally, standard BAPI return messages (BAPIRETURN1) from /AXONEBX/GET\_REV\_CLOSE, BAPI\_BUS2002\_SET\_STATUS, and BAPI\_BUS2054\_SET\_STATUS are captured and logged.

### 3.10 Subroutines

See Section 3.8 Reusable Code for the full method/subroutine inventory.

## 4 Report Output

### 4.1 Output Method

ALV Grid display via CL\_SALV\_TABLE (foreground execution) or spool output (background batch job via SM37).

### 4.2 Main Heading

**Auto Complete Revision, Network and WBS — Execution Log**

### 4.3 Sub Heading

Run Date: SY-DATUM | Run Time: SY-UZEIT | User: SY-UNAME | Variant: SY-SLSET

### 4.4 Layout / UI Design

#

Column

Technical Field

Type

Length

Description

1

Revision No

REVNR

CHAR

8

Revision number processed

2

Network No

AUFNR

CHAR

12

Linked network number

3

WBS Element

WBS\_ELEMENT

CHAR

24

Linked WBS element (external format)

4

Step

STEP

CHAR

20

Processing step (Revision/Network/WBS/Email)

5

Status

MSGTY

CHAR

1

Message type (S=Success, E=Error, W=Warning, I=Info)

6

Message Text

MESSAGE

CHAR

220

BAPI return message or custom message text

### 4.5 Totaling

Footer line: **End of Log — Total Processed: XXX | Success: YYY | Errors: ZZZ**

### 4.6 Sorting

Default sort: by Revision Number (ascending), then by Step (Revision → Network → WBS → Email).

### 4.7 Page Break

Standard page breaks as required to prevent overflow. No special page break requirements.

### 4.8 Error Handling

1\. BAPI RETURN TYPE='E'/'A' → log error, BAPI\_TRANSACTION\_ROLLBACK, skip to next object.  
2\. Open Notification/Order → ZPM\_AUTOCOMPLETE 001.  
3\. Open Revision for Network → ZPM\_AUTOCOMPLETE 002.  
4\. Open Network for WBS → ZPM\_AUTOCOMPLETE 003.  
5\. Revision without Network → ZPM\_AUTOCOMPLETE 007 (informational).  
6\. Email failure → ZPM\_AUTOCOMPLETE 009 (warning, no rollback of WBS TECO).  
7\. No data → ZPM\_AUTOCOMPLETE 010.

### 4.9 Report Header & Footer

**Header:** 'Auto Complete Revision, Network and WBS — Execution Log'  
**Sub:** Run Date | Run Time | User | Variant  
**Footer:** 'End of Log — Total: XXX | Success: YYY | Errors: ZZZ'

## 5 Assumptions in Technical Design

1\. All service orders are assumed to be closed (CLSD) within 60 days from revision end date — controlled by P\_DAYS parameter (default 60).  
2\. Service Orders and Notifications are linked to Revision via DIWPS\_RV\_CR table (WPID = Revision Number, data element REVNI, CHAR 8).  
3\. Network is linked to Revision via T352R-AUFNR field (data element NW\_AUFNR, CHAR 12).  
4\. WBS Element is linked to Network via AUFK-PSPEL field (data element PS\_PSP\_ELE, NUMC 8).  
5\. BAPI /AXONEBX/GET\_REV\_CLOSE is available on target S/4HANA system (Axone partner namespace).  
6\. Distribution list SO15 for EC FI email recipients is maintained.  
7\. Email template MO-0595 is available and configured.  
8\. BAPI\_TRANSACTION\_COMMIT (WAIT='X') is called after each successful status change.  
9\. Sequential processing — no parallel processing required.  
10\. BAPI\_BUS2002\_SET\_STATUS NUMBER parameter typed as BAPI\_NETWORK\_LIST-NETWORK (NW\_AUFNR, CHAR 12).  
11\. BAPI\_BUS2054\_SET\_STATUS WBS\_ELEMENT typed as PS\_POSID (CHAR 24, external format — requires CONVERSION\_EXIT\_ABPSP\_OUTPUT).

## 6 Open Issues in Technical Design

#

Issue

Status

Resolution

1

/AXONEBX/GET\_REV\_CLOSE BAPI not found on connected ECC system — partner BAPI from Axone namespace

Open

Confirm availability and exact interface on target S/4HANA system

2

FS references both DIWPS\_RV\_CR and DIWPA\_RV\_CR. DIWPA\_RV\_CR returned no fields on this system.

Resolved

Confirmed: DIWPS\_RV\_CR contains WPID, NOTIFID, ORDER\_NO. Use DIWPS\_RV\_CR.

3

T325R table (Revision-Network link) returned no fields on connected ECC system

Open

Confirm existence on target S/4HANA. Alternative: use T352R-AUFNR directly.

4

Email template MO-0595 format and variable placeholders unknown

Open

Obtain template specifications from functional team

5

BAPI\_BUS2054\_SET\_STATUS WBS\_ELEMENT format — internal vs external

Resolved

BAPI expects external format (PS\_POSID CHAR 24). Use CONVERSION\_EXIT\_ABPSP\_OUTPUT.

6

TECO status code for Network/WBS

Resolved

Confirmed: I0045 is the standard SAP TECO system status code.

## 7 Unit Test Results

Scenario #

Input / Selection Criteria

Expected Result

Pass/Fail

1

Revision with linked open Notifications and Service Orders (not completed).

System ignores revision for auto close and logs informational message listing open items.

—

2

Revision with all Notifications completed (NOCO) and all Service Orders closed (CLSD).

System closes the revision (CLSD) via /AXONEBX/GET\_REV\_CLOSE and logs success message.

—

3

Revision with linked network; network linked to multiple revisions — all other revisions closed.

System TECOs the network via BAPI\_BUS2002\_SET\_STATUS and logs success.

—

4

Network linked to multiple revisions — at least one other revision still open.

System skips network TECO and logs error indicating which revision is open.

—

5

WBS linked to single TECO network; no other networks linked to WBS.

System TECOs the WBS via BAPI\_BUS2054\_SET\_STATUS and logs success.

—

6

WBS linked to multiple networks; at least one network not yet TECO.

System skips WBS TECO and logs error for the open network.

—

7

Plant ECE2 revision closed, WBS TECO'd — email trigger test.

System sends email notification to EC FI distribution list (SO15) using MO-0595 template.

—

8

Non-ECE2 plant revision closed, WBS TECO'd — no email test.

System does NOT send email. Only logs the successful WBS TECO.

—

9

Revision validated for close but has no linked network.

System closes revision and logs informational message 'Revision XXXXX closed without network'.

—

10

No revisions match selection criteria (no released revisions within XX days threshold).

System displays 'No data found matching selection criteria' and exits gracefully.

—

## 8 Related Documentation

#

Document

Version

Notes

1

FSD\_EN-MO-0613 Auto Complete Network, WBS and Revision

0.1

Source functional specification (Muralikrishna K, 10-Sep-2026)

2

Email Template MO-0595

—

Used for WBS TECO notification email to EC FI

3

Project Polaris Lodestar Phase 2A

—

Parent project

4

Reviewed by: Shigeo Yamaguchi

0.1

FS review completed 22-Sep-2026

## 9 BAPI Interface Reference (Verified from SAP)

### 9.1 BAPI\_BUS2002\_SET\_STATUS (Network Status Change)

Direction

Parameter

Type

Structure

Optional

IMPORTING

NUMBER

BAPI\_NETWORK\_LIST-NETWORK

NW\_AUFNR (CHAR 12)

No

IMPORTING

SET\_SYSTEM\_STATUS

BAPI\_SYSTEM\_STATUS-SYSTEM\_STATUS

CHAR 4

Yes

IMPORTING

UNDO\_SYSTEM\_STATUS

BAPI\_SYSTEM\_STATUS-SYSTEM\_STATUS

CHAR 4

Yes

IMPORTING

SET\_USER\_STATUS

BAPI\_USER\_STATUS-USER\_STATUS

CHAR 4

Yes

IMPORTING

UNDO\_USER\_STATUS

BAPI\_USER\_STATUS-USER\_STATUS

CHAR 4

Yes

EXPORTING

RETURN

BAPIRETURN1

TYPE, ID, NUMBER, MESSAGE, MESSAGE\_V1..V4

No

TABLES

I\_ACTIVITY\_SYSTEM\_STATUS

BAPI\_ACT\_MNT\_SYSTEM\_STATUS

Activity-level status

Yes

TABLES

I\_ACTIVITY\_USER\_STATUS

BAPI\_ACT\_MNT\_USER\_STATUS

Activity-level user status

Yes

TABLES

E\_RESULT

BAPI\_STATUS\_RESULT

Status change results

Yes

### 9.2 BAPI\_BUS2054\_SET\_STATUS (WBS Element Status Change)

Direction

Parameter

Type

Structure

Optional

EXPORTING

RETURN

BAPIRETURN1

TYPE, ID, NUMBER, MESSAGE, MESSAGE\_V1..V4

No

TABLES

I\_WBS\_SYSTEM\_STATUS

BAPI\_WBS\_MNT\_SYSTEM\_STATUS

WBS\_ELEMENT (PS\_POSID CHAR 24) + SET\_SYSTEM\_STATUS (CHAR 4)

Yes

TABLES

I\_WBS\_USER\_STATUS

BAPI\_WBS\_MNT\_USER\_STATUS

WBS user status

Yes

TABLES

E\_RESULT

BAPI\_STATUS\_RESULT

Status change results

Yes

### 9.3 BAPI\_TRANSACTION\_COMMIT

Direction

Parameter

Type

Notes

IMPORTING

WAIT

BAPITA-WAIT

Set to 'X' for synchronous commit

EXPORTING

RETURN

BAPIRET2

Commit result

**⚠️ Open Issue:** The BAPI /AXONEBX/GET\_REV\_CLOSE referenced in the Functional Specification is from the Axone partner namespace and was **not found** on the connected ECC system. Its exact interface (IMPORTING/EXPORTING parameters, RETURN structure) must be confirmed on the target S/4HANA system before development begins.

**C16 — AI for SAP operational efficiency**  |  Document version 1.0  |  14 October 2026

C16.ai

**Disclaimer & Important Notices**

**1.  AI-Generated Content.** This document was generated by **C16**, an automated AI-powered SAP analysis platform operated by **PEOL Technologies Private Limited**, based on data sourced from the connected SAP system at the time of generation. The contents have not been individually reviewed by a human consultant prior to publication.

**2.  Validation Required; Customer Responsibility.** All findings, scores, classifications, recommendations, timelines, and roadmap items are **advisory in nature** and must be reviewed and validated by qualified SAP functional and technical subject-matter experts before any action is taken. Migration, remediation, configuration, and implementation decisions remain the **sole responsibility of the customer**.

**3.  Demonstration System Notice.** Where this document was produced from an **IDES, sandbox, training, or demonstration** SAP system, the configurations, data volumes, transactions, and custom objects analysed do not represent any real production customer environment. Such content is provided for **illustration and template purposes only**; actual findings, scores, and recommendations in a customer engagement will vary materially.

**4.  No Warranty; No Liability.** This document is provided **“as is.”** PEOL Technologies Private Limited makes no representation or warranty of any kind, express or implied, including (without limitation) any warranty as to accuracy, completeness, merchantability, non-infringement, or fitness for a particular purpose. In no event shall PEOL Technologies Private Limited be liable for any direct, indirect, incidental, consequential, or special damages arising from the use of, or reliance upon, this document.

**5.  SAP Trademarks & Partnership.** _SAP_, _SAP S/4HANA_, _SAP ECC_, _SAP ERP_, _ABAP_, _SAP HANA_, _SAP Fiori_, _BAPI_, _BAdI_, _Business Partner_, and other SAP product names referenced in this document are trademarks or registered trademarks of **SAP SE** in Germany and other countries. **PEOL Technologies Private Limited is an SAP Partner; C16 is PEOL’s own product, not an SAP product.** References to SAP products, transactions, tables, notes, and methodologies are made solely for analytical and educational purposes.

**6.  Confidentiality.** Where this document contains customer-specific information, it is **confidential** and intended solely for the named recipient. It may not be reproduced, distributed, or disclosed to any third party without the prior written consent of PEOL Technologies Private Limited.

**7.  Copyright.** © 2026 PEOL Technologies Private Limited. All rights reserved. “C16”, “C16.ai”, and the C16 logo are trademarks of PEOL Technologies Private Limited.