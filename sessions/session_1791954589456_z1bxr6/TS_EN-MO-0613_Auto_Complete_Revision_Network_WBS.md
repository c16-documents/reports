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

Created by

Role

Comments

0.1

Draft

2026-10-14

C16 AI Generator

Author

Initial draft — Technical Specification generated from FSD EN-MO-0613 v0.1 (Muralikrishna K, 10 Sep 2026)

### 1.2 Integration, Document Reference

S. No.

Referred Document Name

Version

1

FSD\_EN-MO-0613 Auto Complete Revision, Network and WBS

0.1 (10 Sep 2026)

2

MO-0595 Email Template — WBS TECO notification

Current

3

SO15 Distribution List — EC FI email addresses

Current

## 2 Code Quality

Final Solution

Category

Comments

Custom program using standard BAPIs

**Tier 1 — Cloud Development**

Uses standard BAPIs (BAPI\_BUS2002\_SET\_STATUS, BAPI\_BUS2054\_SET\_STATUS) and partner BAPI (/AXONEBX/GET\_REV\_CLOSE). All data reads from standard SAP tables (T352R, JEST, AUFK, QMEL, DIWPS\_RV\_CR). Conforms to SIA Code Quality strategy. Fiori Tile planned for monitoring.

## 3 Program Attributes

**Program Title**

Auto Complete Revision, Network and WBS

**Program Name**

ZEN\_MO\_0613\_REV\_AUTO\_CLOSE

**Program Type**

Executable

**Package**

ZEN\_PM (To be defined by project team)

**Authorization Group**

As per BU decision

**Transaction Code**

N/A — Runs as daily batch job via SM36/SM37

**Include Programs**

N/A

**Function Modules**

/AXONEBX/GET\_REV\_CLOSE, BAPI\_BUS2002\_SET\_STATUS, BAPI\_BUS2054\_SET\_STATUS, BAPI\_TRANSACTION\_COMMIT

**Message Class**

Standard BAPI return messages (BAPIRETURN1) + Custom application messages

**SAP Tables Read**

T352R (Revision Header), JEST (Object Status), AUFK (Order Master), QMEL (Notification Header), DIWPS\_RV\_CR (Revision Work Packages), T325R (Revision-Network Assignment)

**Custom Tables**

N/A

**Custom Indexes**

N/A

**CDS Views**

N/A — Background executable; no CDS views required

**OData Service**

N/A

**Business Object**

BUS2002 (Network), BUS2054 (WBS Element)

**Fiori App Name**

To be developed as per SIA Code Quality strategy

### 3.1 Selection Screen

P/S

Type / Field Name

Mandatory

Default

Parameter ID

Search Help

Selection Screen Text

S

T352R-REVNR

No

—

S\_REVNR

Standard

Revision Number

S

T352R-REVTY

No

—

S\_REVTY

Standard

Revision Type

S

T352R-REVBD

No

—

S\_REVBD

Standard

Revision Start Date

S

T352R-REVED

No

—

S\_REVED

Standard

Revision End Date

S

T352R-IWERK

No

—

S\_IWERK

Standard

Planning Plant of Revision

S

T352R-VAPLZ

No

—

S\_VAPLZ

Standard

Main Workcenter for Revision

S

T352R-VAWRK

No

—

S\_VAWRK

Standard

Main Workcenter Plant

S

T352R-ZZ\_ESLOT\_START

No

—

S\_ESLOTS

Standard

eSLOT Start Date

S

T352R-ZZ\_ESLOT\_END

No

—

S\_ESLOTE

Standard

eSLOT End Date

P

TYPE I (Default: 60)

No

60

P\_DAYS

N/A

XX Days Threshold

### 3.2 Validation of Selection Criteria

**1\. Revision Status (REL):** T352R-OBJNR → JEST check: STAT = I0002 (Released) with INACT ≠ 'X'. JEST confirmed: OBJNR (CHAR 22, DE: J\_OBJNR), STAT (CHAR 5, DE: J\_STATUS), INACT (CHAR 1, DE: J\_INACT).

**2\. Age Threshold:** T352R-REVED ≤ SY-DATUM − P\_DAYS (default 60 days).

**3\. Notification Completion (NOCO):** All linked notifications (DIWPS\_RV\_CR-NOTIFID, DE: QMNUM) must have JEST STAT = I0072. QMEL-OBJNR (DE: QMOBJNR) used for JEST lookup.

**4\. Order Closure (CLSD):** All linked orders (DIWPS\_RV\_CR-ORDER\_NO, DE: AUFNR) must have JEST STAT = I0046. AUFK-OBJNR (DE: J\_OBJNR) used for JEST lookup.

**5.** If ANY notification or order is open → revision skipped with error message.

### 3.3 CDS Views / AMDP / Table Function

Not applicable — this is a background executable program that processes status changes via standard BAPIs. No CDS views, AMDP, or table functions are required.

### 3.4 Authorization Requirements

Authorization is managed at the batch job scheduling level as per BU decision. The BAPIs called enforce their own standard SAP authorization checks internally.

**Recommended authorization objects:**

Auth Object

Field

Value

Purpose

S\_BTCH\_JOB

JOBACTION

RELE

Batch job scheduling and release

I\_IWERK

IWERK

ECE2 or \* (per BU)

Plant-level access control

B\_USERSTAT

ACTVT

02 (Change)

Status changes on objects

**DCL Details:** Not applicable. **BTP Details:** Not applicable — on-premise S/4HANA program.

### 3.5 Technical Flow Diagram

#mermaid-1791955246137{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1791955246137 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1791955246137 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1791955246137 .error-icon{fill:#552222;}#mermaid-1791955246137 .error-text{fill:#552222;stroke:#552222;}#mermaid-1791955246137 .edge-thickness-normal{stroke-width:1px;}#mermaid-1791955246137 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1791955246137 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1791955246137 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1791955246137 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1791955246137 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1791955246137 .marker{fill:#666;stroke:#666;}#mermaid-1791955246137 .marker.cross{stroke:#666;}#mermaid-1791955246137 svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-1791955246137 p{margin:0;}#mermaid-1791955246137 .label{font-family:"trebuchet ms",verdana,arial,sans-serif;color:#000000;}#mermaid-1791955246137 .cluster-label text{fill:#333;}#mermaid-1791955246137 .cluster-label span{color:#333;}#mermaid-1791955246137 .cluster-label span p{background-color:transparent;}#mermaid-1791955246137 .label text,#mermaid-1791955246137 span{fill:#000000;color:#000000;}#mermaid-1791955246137 .node rect,#mermaid-1791955246137 .node circle,#mermaid-1791955246137 .node ellipse,#mermaid-1791955246137 .node polygon,#mermaid-1791955246137 .node path{fill:#eee;stroke:#999;stroke-width:1px;}#mermaid-1791955246137 .rough-node .label text,#mermaid-1791955246137 .node .label text,#mermaid-1791955246137 .image-shape .label,#mermaid-1791955246137 .icon-shape .label{text-anchor:middle;}#mermaid-1791955246137 .node .katex path{fill:#000;stroke:#000;stroke-width:1px;}#mermaid-1791955246137 .rough-node .label,#mermaid-1791955246137 .node .label,#mermaid-1791955246137 .image-shape .label,#mermaid-1791955246137 .icon-shape .label{text-align:center;}#mermaid-1791955246137 .node.clickable{cursor:pointer;}#mermaid-1791955246137 .root .anchor path{fill:#666!important;stroke-width:0;stroke:#666;}#mermaid-1791955246137 .arrowheadPath{fill:#333333;}#mermaid-1791955246137 .edgePath .path{stroke:#666;stroke-width:2.0px;}#mermaid-1791955246137 .flowchart-link{stroke:#666;fill:none;}#mermaid-1791955246137 .edgeLabel{background-color:white;text-align:center;}#mermaid-1791955246137 .edgeLabel p{background-color:white;}#mermaid-1791955246137 .edgeLabel rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1791955246137 .labelBkg{background-color:rgba(255, 255, 255, 0.5);}#mermaid-1791955246137 .cluster rect{fill:hsl(0, 0%, 98.9215686275%);stroke:#707070;stroke-width:1px;}#mermaid-1791955246137 .cluster text{fill:#333;}#mermaid-1791955246137 .cluster span{color:#333;}#mermaid-1791955246137 div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:12px;background:hsl(-160, 0%, 93.3333333333%);border:1px solid #707070;border-radius:2px;pointer-events:none;z-index:100;}#mermaid-1791955246137 .flowchartTitleText{text-anchor:middle;font-size:18px;fill:#000000;}#mermaid-1791955246137 rect.text{fill:none;stroke-width:0;}#mermaid-1791955246137 .icon-shape,#mermaid-1791955246137 .image-shape{background-color:white;text-align:center;}#mermaid-1791955246137 .icon-shape p,#mermaid-1791955246137 .image-shape p{background-color:white;padding:2px;}#mermaid-1791955246137 .icon-shape .label rect,#mermaid-1791955246137 .image-shape .label rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1791955246137 .label-icon{display:inline-block;height:1em;overflow:visible;vertical-align:-0.125em;}#mermaid-1791955246137 .node .label-icon path{fill:currentColor;stroke:revert;stroke-width:revert;}#mermaid-1791955246137 :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}

Yes

No

Yes

No

1\. Read Selection Parameters

2\. Fetch Revisions from T352R

3\. Filter: JEST REL Status + Age Check

4\. Get Linked Objects from DIWPS\_RV\_CR

5\. Check Notifications: QMEL → JEST I0072 NOCO

6\. Check Orders: AUFK → JEST I0046 CLSD

All NOCO + CLSD?

7\. Close Revision via /AXONEBX/GET\_REV\_CLOSE

Log Error: Open items exist

8\. Close Network via BAPI\_BUS2002\_SET\_STATUS TECO

9\. Close WBS via BAPI\_BUS2054\_SET\_STATUS TECO

Plant = ECE2?

10\. Send Email via SO15 / MO-0595

11\. Display Log / Spool Output

### 3.6 UI Details

Not applicable — the program runs as a background batch job. A Fiori Tile for execution monitoring is planned as a separate development per SIA Code Quality strategy.

### 3.7 Processing Logic

**STEP 1 — Data Selection:**

SELECT REVNR, REVTY, REVBD, REVED, IWERK, VAPLZ, VAWRK, AUFNR, OBJNR FROM T352R WHERE matching selection criteria. Field types confirmed from live system: REVNR (CHAR 8, DE: REVNI), REVTY (CHAR 2, DE: DIWPS\_REVTY\_CORE), REVED (DATS 8, DE: REVED), IWERK (CHAR 4, DE: IWERK), AUFNR (CHAR 12, DE: NW\_AUFNR), OBJNR (CHAR 22, DE: J\_OBJNR).

**STEP 2 — REL Status Validation:**

For each revision, read JEST WHERE OBJNR = T352R-OBJNR AND INACT ≠ 'X'. Check STAT = I0002 (Released). Also verify REVED ≤ SY-DATUM − P\_DAYS. Sample data confirmed: JEST records with STAT=I0002 and INACT='' exist in the system (e.g., OBJNR 'RV100000000006').

**STEP 3 — Get Linked Objects:**

Read DIWPS\_RV\_CR WHERE WPID = revision\_number. Confirmed fields from live system: WPID (CHAR 8, DE: REVNI), NOTIFID (CHAR 12, DE: QMNUM), ORDER\_NO (CHAR 12, DE: AUFNR). Table has 30 fields total including IWERK, QMART, ARCH\_ORDER.

**STEP 4 — Notification Status Check (NOCO):**

For each NOTIFID: SELECT OBJNR FROM QMEL WHERE QMNUM = notification\_number (QMEL-OBJNR DE: QMOBJNR). Then SELECT STAT FROM JEST WHERE OBJNR = QMEL-OBJNR AND INACT ≠ 'X'. Check STAT = I0072 (NOCO). If ANY notification is not NOCO → skip revision.

**STEP 5 — Order Status Check (CLSD):**

For each ORDER\_NO: SELECT OBJNR FROM AUFK WHERE AUFNR = order\_number (AUFK-OBJNR DE: J\_OBJNR). Then SELECT STAT FROM JEST WHERE OBJNR = AUFK-OBJNR AND INACT ≠ 'X'. Check STAT = I0046 (CLSD). If ANY order is not CLSD → skip revision.

**STEP 6 — Close Revision (CLSD):**

CALL FUNCTION '/AXONEBX/GET\_REV\_CLOSE' EXPORTING I\_REVNR = revision\_number, I\_WERKS = planning\_plant. Evaluate return and log result.

**STEP 7 — Network Closure Logic (TECO):**

Read T352R-AUFNR (network, CHAR 12, DE: NW\_AUFNR). Check if network is linked to other revisions via T325R. For each other revision (excluding current), verify JEST STAT = I0046 (CLSD). If ALL are CLSD:

CALL FUNCTION 'BAPI\_BUS2002\_SET\_STATUS' EXPORTING NUMBER = network\_number (TYPE BAPI\_NETWORK\_LIST-NETWORK), SET\_SYSTEM\_STATUS = 'I0045' (TECO). IMPORTING RETURN = ls\_return (TYPE BAPIRETURN1: TYPE CHAR 1, ID CHAR 20, NUMBER NUMC 3, MESSAGE CHAR 220, MESSAGE\_V1–V4 CHAR 50). Then CALL FUNCTION 'BAPI\_TRANSACTION\_COMMIT' EXPORTING WAIT = 'X'.

If revision has no linked network → log info: 'Revision XXXXX closed without network'.

**STEP 8 — WBS Closure Logic (TECO):**

Read AUFK-PSPEL (NUMC 8, DE: PS\_PSP\_ELE) for the WBS element. Check if WBS is linked to other networks via AUFK-PSPEL. For each other network (excluding current), verify JEST status for TECO (I0045). If ALL are TECO:

CALL FUNCTION 'BAPI\_BUS2054\_SET\_STATUS' TABLES I\_WBS\_SYSTEM\_STATUS (TYPE BAPI\_WBS\_MNT\_SYSTEM\_STATUS). IMPORTING RETURN = ls\_return (TYPE BAPIRETURN1). Then CALL FUNCTION 'BAPI\_TRANSACTION\_COMMIT' EXPORTING WAIT = 'X'.

**STEP 9 — Email Notification:**

If WBS successfully set to TECO AND T352R-IWERK = 'ECE2': Read SO15 distribution list for EC FI email addresses. Send email using MO-0595 template via CL\_BCS or SO\_NEW\_DOCUMENT\_SEND\_API1.

**STEP 10 — Log Output:**

Display all collected log entries as a tabular spool list with columns: Revision No | Network No | WBS Element | Action (CLSD/TECO) | Result (Success/Error/Info) | Message Text. Stored as spool in background execution.

### 3.8 Reusable Code

**CHECK\_OBJECT\_STATUS** — Reusable JEST status checker for any OBJNR + target status code.

**BAPI\_ERROR\_HANDLER** — Evaluates BAPIRETURN1 structure and populates log table.

**SEND\_NOTIFICATION\_EMAIL** — Reads SO15 distribution list and sends email per MO-0595 template.

### 3.9 Messages

Message Class

Type

Message Text

BAPIRETURN1

E/S/I

Standard BAPI return messages from all three BAPIs

Custom

E

Notification and order are open — cannot close revision &1

Custom

E

Revision(s) are open — cannot close network &1

Custom

E

Network &1 not yet closed — cannot close WBS &2

Custom

S

Revision &1 closed successfully (CLSD)

Custom

S

Network &1 completed successfully (TECO)

Custom

S

WBS &1 completed successfully (TECO)

Custom

I

Revision &1 closed without network

Custom

I

No revisions found matching the selection criteria

Custom

S

Email sent to EC FI for WBS &1 completion (Plant ECE2)

### 3.10 Subroutines / Methods

Name

Description

CHECK\_OBJECT\_STATUS

Reads JEST for given OBJNR; checks if target status (I0002/I0072/I0046/I0045) is active (INACT ≠ 'X'). Returns TRUE/FALSE.

GET\_LINKED\_OBJECTS

Reads DIWPS\_RV\_CR for revision WPID; returns internal tables of NOTIFID and ORDER\_NO.

CLOSE\_REVISION

Calls /AXONEBX/GET\_REV\_CLOSE with I\_REVNR + I\_WERKS; evaluates BAPI return; logs result.

CLOSE\_NETWORK

Calls BAPI\_BUS2002\_SET\_STATUS (NUMBER = network, SET\_SYSTEM\_STATUS = 'I0045' TECO); calls BAPI\_TRANSACTION\_COMMIT; logs result.

CLOSE\_WBS

Calls BAPI\_BUS2054\_SET\_STATUS (I\_WBS\_SYSTEM\_STATUS with SYSTEM\_STATUS = 'I0045' TECO); calls BAPI\_TRANSACTION\_COMMIT; logs result.

SEND\_WBS\_EMAIL

Reads SO15 distribution list for EC FI; constructs email from MO-0595 template; sends via CL\_BCS.

DISPLAY\_LOG

Outputs collected log table as tabular spool list (Revision | Network | WBS | Action | Result | Message).

## 4 Report Output

### 4.1 Output Method

Background spool output — the program runs as a daily batch job and all results are written to the spool (viewable via SM37/SP01). In foreground execution, the log is displayed as a WRITE list.

### 4.2 Main Heading

Auto Complete Revision, Network and WBS — Execution Log

### 4.3 Sub Heading

Executed on: SY-DATUM / SY-UZEIT | User: SY-UNAME | Variant: (selection variant name)

### 4.4 Layout / UI Design — Log Output Columns

#

Field Name

Column Header

Visible

1

REVNR

Revision Number

Yes

2

REVTY

Revision Type

Yes

3

IWERK

Planning Plant

Yes

4

AUFNR

Network Number

Yes

5

PSPEL

WBS Element

Yes

6

STATUS

Action Taken (CLSD/TECO)

Yes

7

RESULT

Result (Success/Error/Info)

Yes

8

MESSAGE

BAPI Return Message Text

Yes

### 4.5 Totaling

Summary line at end of log: Total Revisions Processed | Total Revisions Closed | Total Networks Completed (TECO) | Total WBS Completed (TECO) | Total Errors

### 4.6 Sorting

Default sort by Revision Number ascending.

### 4.7 Page Break

Not applicable — spool output with continuous log entries.

### 4.8 Error Handling

1\. **BAPI Return Handling:** After each BAPI call, check RETURN-TYPE. TYPE = 'E' or 'A' → log error, skip to next object, call BAPI\_TRANSACTION\_ROLLBACK. TYPE = 'S' or blank → call BAPI\_TRANSACTION\_COMMIT EXPORTING WAIT = 'X'.

2\. **Exception Handling:** Wrap BAPI calls in TRY/CATCH CX\_ROOT as safety net.

3\. **Partial Processing:** If revision close fails, do NOT attempt network or WBS closure for that revision.

4\. **Logging:** Every step logs result to internal table with Status (Success/Error/Info) and Message Text.

5\. **Spool Storage:** Complete log written to spool for audit trail (viewable via SP01).

### 4.9 Report Header & Footer

**Header:** 'Auto Complete Revision, Network and WBS — EN-MO-0613'

**Footer:** 'End of execution log — Total records processed: &1'

## 5 Assumptions in Technical Design

1\. All service orders are expected to be closed (CLSD) within 60 days from revision end date (configurable via P\_DAYS parameter).

2\. The BAPI /AXONEBX/GET\_REV\_CLOSE is a partner-provided BAPI from the AXONE extension and must be available in the target system.

3\. The distribution list SO15 for EC FI must be maintained in the system before the email feature is activated.

4\. The MO-0595 email template must be configured and available.

5\. DIWPS\_RV\_CR table stores the revision-to-notification and revision-to-order linkages (confirmed on live system: WPID, NOTIFID, ORDER\_NO fields exist with 30 fields total).

6\. T325R stores revision-to-network assignment (not confirmed on connected ECC system — must be verified on target S/4HANA system).

7\. BAPI\_TRANSACTION\_COMMIT with WAIT = 'X' is called after each successful status change for synchronous database commit.

8\. ZZ\_ESLOT\_START and ZZ\_ESLOT\_END are custom append fields on T352R — their existence must be confirmed on the target system.

## 6 Open Issues in Technical Design

#

Issue

Status

Action Required

1

T325R table returned no fields via batch\_field\_lookup on connected ECC system

Open

Confirm field names on target S/4HANA system

2

/AXONEBX/GET\_REV\_CLOSE is a partner namespace BAPI

Open

Confirm availability and interface on target system

3

ZZ\_ESLOT\_START and ZZ\_ESLOT\_END on T352R are custom appends

Open

Confirm field existence on target system

4

Fiori Tile development for monitoring

Out of scope

Separate Technical Specification required

5

TECO status code I0045

Open

Confirm correct status code on target system

## 7 Unit Test Results

Scenario #

Input / Test Condition

Expected Result

Pass/Fail

1

Revision with linked Notifications and Service Orders NOT yet completed

System ignores revision for auto close with error message

—

2

Revision with all linked Notifications completed (NOCO) and all Orders closed (CLSD)

System closes revision (CLSD) with success message

—

3

Revision with network; network linked to multiple revisions (all other revisions CLSD)

System completes network (TECO)

—

4

WBS linked to network; all networks under WBS are TECO; Planning plant ECE2

System completes WBS (TECO) and sends email to EC FI

—

5

Network linked to multiple revisions; at least one revision NOT closed

System ignores network; error message logged

—

6

WBS TECO for planning plant ECE2

Email sent to distribution list SO15 using MO-0595 template

—

7

Revision without any linked network

Revision closed; info message: 'Revision XXXXX closed without network'

—

8

No matching revisions found for selection criteria

Informational message displayed

—

9

BAPI returns error on revision/network/WBS close attempt

Error logged; processing continues with remaining objects

—

10

Background batch execution — full run

Spool contains complete log of all processed revisions, networks, and WBS elements

—

## 8 Related Documentation

#

Document

Purpose

1

FSD\_EN-MO-0613 Auto Complete Revision, Network and WBS — v0.1 (10 Sep 2026)

Source Functional Specification

2

MO-0595 Email Template

WBS TECO email notification content

3

SO15 Distribution List

EC FI email addresses for WBS completion notification

4

SAP Documentation: BAPI\_BUS2002\_SET\_STATUS

Network status change BAPI (confirmed: NUMBER, SET\_SYSTEM\_STATUS, RETURN params)

5

SAP Documentation: BAPI\_BUS2054\_SET\_STATUS

WBS element status change BAPI (confirmed: I\_WBS\_SYSTEM\_STATUS table, RETURN)

6

SAP Documentation: BAPI\_TRANSACTION\_COMMIT

Synchronous commit (confirmed: WAIT param, BAPIRET2 return)

**BAPI Interface Summary (Verified from Live SAP System)**  
**BAPI\_BUS2002\_SET\_STATUS** (Network): IMPORTING — NUMBER (BAPI\_NETWORK\_LIST-NETWORK), SET\_SYSTEM\_STATUS (BAPI\_SYSTEM\_STATUS-SYSTEM\_STATUS, optional), UNDO\_SYSTEM\_STATUS (optional), SET\_USER\_STATUS (optional), UNDO\_USER\_STATUS (optional). EXPORTING — RETURN (BAPIRETURN1). TABLES — E\_RESULT (BAPI\_STATUS\_RESULT), I\_ACTIVITY\_SYSTEM\_STATUS, I\_ACTIVITY\_USER\_STATUS.  
  
**BAPI\_BUS2054\_SET\_STATUS** (WBS): EXPORTING — RETURN (BAPIRETURN1). TABLES — I\_WBS\_SYSTEM\_STATUS (BAPI\_WBS\_MNT\_SYSTEM\_STATUS), I\_WBS\_USER\_STATUS (BAPI\_WBS\_MNT\_USER\_STATUS), E\_RESULT (BAPI\_STATUS\_RESULT).  
  
**BAPI\_TRANSACTION\_COMMIT**: IMPORTING — WAIT (BAPITA-WAIT, optional). EXPORTING — RETURN (BAPIRET2).

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