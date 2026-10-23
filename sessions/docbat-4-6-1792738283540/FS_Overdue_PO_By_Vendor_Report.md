  FS Overdue PO By Vendor Report @page { size: A4; margin: 20mm 18mm 20mm 18mm; } \* { box-sizing: border-box; margin: 0; padding: 0; } body { font-family: 'Segoe UI', Calibri, Arial, sans-serif; font-size: 10.5pt; line-height: 1.55; color: #1a1a1a; background: #f4f5f6; -webkit-print-color-adjust: exact; print-color-adjust: exact; } .doc-wrapper { max-width: 1100px; margin: 24px auto; background: #ffffff; box-shadow: 0 1px 8px rgba(0,0,0,0.08); border: 1px solid #d0d4d8; } /\* HEADER \*/ .doc-header { background: #003366; color: #ffffff; padding: 28px 36px 24px 36px; border-bottom: 4px solid #7fb3e0; } .doc-header-top { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 14px; } .doc-logo img { height: 40px; display: block; } .doc-classification { font-size: 8.5pt; letter-spacing: 1.2px; text-transform: uppercase; color: #7fb3e0; border: 1px solid #7fb3e0; padding: 3px 12px; border-radius: 2px; white-space: nowrap; } .doc-header h1 { font-size: 22pt; font-weight: 600; letter-spacing: -0.3px; margin: 0 0 4px 0; line-height: 1.2; } .doc-header .doc-subtitle { font-size: 11pt; color: #7fb3e0; font-weight: 400; } /\* META \*/ .doc-meta { padding: 16px 36px; background: #f7f8fa; border-bottom: 1px solid #d0d4d8; font-size: 9.5pt; color: #444; } .doc-meta table { width: 100%; border-collapse: collapse; } .doc-meta td { padding: 3px 12px 3px 0; vertical-align: top; } .doc-meta .meta-label { font-weight: 600; color: #003366; width: 90px; } /\* BODY \*/ .doc-body { padding: 28px 36px 36px 36px; background: #ffffff; } .doc-body p { margin: 8px 0; } .doc-body h2 { font-size: 14pt; color: #003366; margin: 24px 0 12px 0; padding-bottom: 6px; border-bottom: 2px solid #7fb3e0; display: flex; align-items: center; gap: 10px; } .doc-body h2 .sec-num { display: inline-block; background: #003366; color: white; font-size: 11pt; font-weight: 700; padding: 2px 9px; border-radius: 3px; line-height: 1; min-width: 26px; text-align: center; } .doc-body h3 { font-size: 11.5pt; color: #003366; margin: 18px 0 8px 0; font-weight: 600; } .doc-body h4 { font-size: 10.5pt; color: #1a5c8a; margin: 12px 0 6px 0; font-weight: 600; } .doc-body ul, .doc-body ol { margin: 8px 0 8px 22px; } .doc-body li { margin: 4px 0; } /\* TABLES \*/ table.data { width: 100%; border-collapse: collapse; margin: 10px 0 14px 0; font-size: 9.5pt; } table.data th, table.data td { border: 1px solid #d0d4d8; padding: 7px 10px; text-align: left; vertical-align: top; } table.data th { background: #003366; color: white; font-weight: 600; letter-spacing: 0.2px; } table.data tr:nth-child(even) td { background: #f7f8fa; } table.data td.center { text-align: center; } /\* CALLOUTS \*/ .callout { background: #f0f6fa; border-left: 4px solid #1a5c8a; padding: 12px 16px; margin: 14px 0; font-size: 10pt; color: #1f2937; } .callout.tip { border-left-color: #15803D; background: #f0fdf4; } .callout.warning { border-left-color: #C2410C; background: #fff7ed; } /\* PILLS — Clean Core levels \*/ .pill { display: inline-block; font-size: 8.5pt; font-weight: 600; padding: 2px 9px; border-radius: 10px; letter-spacing: 0.3px; white-space: nowrap; } .pill-a { background: #dcfce7; color: #15803D; } .pill-b { background: #dbeafe; color: #1D4ED8; } .pill-c { background: #fef3c7; color: #A16207; } .pill-d { background: #fee2e2; color: #B91C1C; } /\* SYSTEM PILLS — engagement context strip under the header \*/ .doc-pills { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 14px; } .doc-pills .doc-pill { display: inline-flex; align-items: center; gap: 6px; font-size: 8.5pt; font-weight: 500; padding: 4px 12px; border-radius: 16px; background: rgba(255, 255, 255, 0.12); border: 1px solid rgba(255, 255, 255, 0.28); color: #ffffff; letter-spacing: 0.2px; white-space: nowrap; } .doc-pills .doc-pill .doc-pill-icon { font-size: 9pt; opacity: 0.9; } .doc-pills .doc-pill.danger { background: rgba(254, 226, 226, 0.18); border-color: rgba(254, 226, 226, 0.35); } .doc-pills .doc-pill.warn { background: rgba(254, 243, 199, 0.15); border-color: rgba(254, 243, 199, 0.35); } /\* KPI STRIP — volume counters under the pills \*/ .doc-kpi-strip { display: flex; flex-wrap: wrap; gap: 18px; margin-top: 14px; padding-top: 12px; border-top: 1px solid rgba(255, 255, 255, 0.18); font-size: 9pt; color: rgba(255, 255, 255, 0.92); } .doc-kpi-strip .doc-kpi { display: inline-flex; align-items: center; gap: 5px; white-space: nowrap; } .doc-kpi-strip .doc-kpi-icon { font-size: 10.5pt; } .doc-kpi-strip .doc-kpi-value { font-weight: 700; color: #ffffff; } .doc-kpi-strip .doc-kpi-label { color: rgba(255, 255, 255, 0.78); } /\* PHASE TIMELINE \*/ .phase { border-left: 3px solid #7fb3e0; padding: 10px 16px; margin: 10px 0; background: #f7f8fa; } .phase strong { color: #003366; } .phase .phase-dur { color: #1a5c8a; font-size: 9pt; } /\* DOC FOOTER (inside wrapper) \*/ .doc-footer { background: #f7f8fa; border-top: 1px solid #d0d4d8; padding: 16px 36px; font-size: 9pt; color: #555; } .doc-footer table { width: 100%; } .doc-footer .footer-right { text-align: right; color: #003366; font-weight: 600; } @media print { body { background: white; } .doc-wrapper { box-shadow: none; border: none; margin: 0; max-width: 100%; } h2, h3 { page-break-after: avoid; } table.data { page-break-inside: avoid; } .phase, .callout { page-break-inside: avoid; } }

![C16](data:image/png;base64,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)

Reference

# FS Overdue PO By Vendor Report

Topic

FS Overdue PO By Vendor Report

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

Field

Value

Document Title

Functional Specification — Overdue Purchase Orders by Vendor Report

WRICEF ID

FS-MM-RPT-001

Object Type

Report (ABAP Executable Program)

Proposed Program Name

Z\_MM\_OVERDUE\_PO\_VENDOR

Module

MM — Materials Management (Purchasing)

SAP System

ECC 6.0 (SAP\_BASIS 740), Client 800

Author

C16 Platform

Version

1.0

Date

23 October 2026

Status

Draft

### Revision History

Version

Date

Author

Change Description

1.0

23-Oct-2026

C16 Platform

Initial draft

## 2 Business Purpose & Scope

### 2.1 Business Problem

Procurement and accounts-payable teams need visibility into purchase orders where vendor deliveries are overdue — i.e., the scheduled delivery date has passed but the ordered quantity has not been fully received. Without a consolidated view, buyers must manually check individual PO schedule lines in ME2M or ME2N, making it difficult to prioritise follow-ups, measure vendor reliability, and escalate chronic late deliveries.

### 2.2 Business Objective

Provide a single ALV report that:

*   Lists all open (non-deleted) PO line items whose delivery date has passed without full goods receipt, for a user-specified company code
*   Groups and sorts results by vendor so the buyer can see which suppliers have the most overdue lines
*   Calculates the number of overdue days per schedule line and the outstanding quantity still expected
*   Allows optional filtering by purchasing organisation, purchasing group, vendor, PO number, plant, PO date range, and a user-defined overdue-days threshold
*   Enables the user to download, sort, filter, and total within the ALV grid

### 2.3 Scope

In Scope

Out of Scope

Standard purchase orders (BSTYP = 'F')

Contracts, scheduling agreements, RFQs

Open items only (delivery-complete flag ELIKZ ≠ 'X')

Fully delivered / closed POs

Non-deleted POs and line items (LOEKZ = '')

Deleted POs

ALV grid output with standard toolbar

Email/workflow notifications

ECC 6.0 / SAP\_BASIS 740 compatibility

S/4HANA-specific features (RAP, CDS)

### 2.4 Key Stakeholders

Role

Interest

Buyer / Purchasing Agent

Follow up on late deliveries, vendor expediting

Purchasing Manager

Vendor performance monitoring, escalation decisions

Supply Chain / Logistics

Production impact assessment of late materials

Accounts Payable

Anticipate upcoming invoice matching for overdue GR

## 3 Functional Requirements

### 3.1 Selection Screen

The user enters filter criteria on a single selection screen before executing the report. All fields except Company Code are optional.

#

Field Label

Technical Field

Type

Input Control

Mandatory

Default

1

Company Code

EKKO-BUKRS

PARAMETER

Single value with F4 help

Yes

—

2

Purchasing Organisation

EKKO-EKORG

SELECT-OPTIONS

Multiple values / ranges

No

—

3

Purchasing Group

EKKO-EKGRP

SELECT-OPTIONS

Multiple values / ranges

No

—

4

Vendor

EKKO-LIFNR

SELECT-OPTIONS

Multiple values / ranges

No

—

5

Purchase Order Number

EKKO-EBELN

SELECT-OPTIONS

Multiple values / ranges

No

—

6

Plant

EKPO-WERKS

SELECT-OPTIONS

Multiple values / ranges

No

—

7

PO Date (from/to)

EKKO-BEDAT

SELECT-OPTIONS

Date range

No

—

8

Minimum Overdue Days

User-defined

PARAMETER

Numeric ≥ 1

No

1

**Validation:** If the user enters a Minimum Overdue Days value less than 1, display error message "Minimum overdue days must be at least 1" and prevent execution.

### 3.2 Processing Logic (Business Rules)

### 3.2.1 Rule 1 — Identify Open PO Items

Select all purchase order line items that satisfy ALL of the following conditions:

*   Document category is a standard PO: `EKKO-BSTYP = 'F'`
*   PO header is not deleted: `EKKO-LOEKZ = ''`
*   PO item is not deleted: `EKPO-LOEKZ = ''`
*   PO item delivery is not complete: `EKPO-ELIKZ ≠ 'X'`
*   PO matches the user's company code: `EKKO-BUKRS = P_BUKRS`
*   PO matches any optional filters entered (EKORG, EKGRP, LIFNR, EBELN, WERKS, BEDAT range)

### 3.2.2 Rule 2 — Determine Delivery Due Date

For each selected PO item, read the schedule line delivery date from `EKET-EINDT` (delivery date at schedule-line level). If a PO item has multiple schedule lines, each schedule line is evaluated individually — one PO item may produce multiple output rows.

### 3.2.3 Rule 3 — Calculate Overdue Status

A schedule line is **overdue** when:

*   The delivery date (`EKET-EINDT`) is earlier than today's date (`SY-DATUM`), AND
*   The delivered quantity (`EKET-WEMNG`) is less than the scheduled quantity (`EKET-MENGE`)

Calculate:

*   **Overdue Days** = `SY-DATUM − EKET-EINDT` (number of calendar days)
*   **Outstanding Quantity** = `EKET-MENGE − EKET-WEMNG`

Exclude schedule lines where Overdue Days is less than the user-specified Minimum Overdue Days threshold.

### 3.2.4 Rule 4 — Enrich with Vendor & PO Details

For each qualifying schedule line, retrieve:

*   Vendor name from `LFA1-NAME1` (joined via `EKKO-LIFNR = LFA1-LIFNR`)
*   Vendor city from `LFA1-ORT01`
*   Material number from `EKPO-MATNR`
*   Short text from `EKPO-TXZ01`
*   PO net value from `EKPO-NETWR` (for informational context)
*   Order unit from `EKPO-MEINS`

### 3.2.5 Rule 5 — Sort and Group

The output is sorted by:

1.  **Vendor Number** (ascending) — primary sort with subtotals
2.  **Overdue Days** (descending) — most overdue lines appear first within each vendor
3.  **PO Number / Item / Schedule Line** (ascending)

### 3.3 Output Layout

The report displays results in a full-screen ALV grid (CL\_SALV\_TABLE) with the standard toolbar (export, filter, sort, print). The output table contains the following columns:

#

Column Header

Source Field

Data Type

Width

Notes

1

Vendor

EKKO-LIFNR

CHAR 10

10

Subtotal break

2

Vendor Name

LFA1-NAME1

CHAR 35

30

—

3

City

LFA1-ORT01

CHAR 35

20

—

4

PO Number

EKKO-EBELN

CHAR 10

10

—

5

PO Item

EKPO-EBELP

NUMC 5

5

—

6

Schedule Line

EKET-ETENR

NUMC 4

5

—

7

Material

EKPO-MATNR

CHAR 18

18

—

8

Description

EKPO-TXZ01

CHAR 40

30

Short text

9

Plant

EKPO-WERKS

CHAR 4

5

—

10

PO Date

EKKO-BEDAT

DATS

10

—

11

Delivery Date

EKET-EINDT

DATS

10

—

12

Overdue Days

Calculated

INT

6

SY-DATUM − EINDT

13

Scheduled Qty

EKET-MENGE

QUAN 13,3

13

—

14

Delivered Qty

EKET-WEMNG

QUAN 13,3

13

—

15

Outstanding Qty

Calculated

QUAN 13,3

13

MENGE − WEMNG

16

Order Unit

EKPO-MEINS

UNIT 3

4

—

17

Net Value

EKPO-NETWR

CURR 13,2

15

PO item value

18

Currency

EKKO-WAERS

CUKY 5

5

—

19

Purch. Org.

EKKO-EKORG

CHAR 4

5

—

20

Purch. Group

EKKO-EKGRP

CHAR 3

5

—

### 3.4 Colour-Coding (Row Highlighting)

To draw attention to critically overdue items, rows are colour-coded based on the Overdue Days value:

Overdue Days

Colour

Meaning

1 – 30 days

Yellow

Mildly overdue — monitor

31 – 60 days

Orange

Significantly overdue — follow up

61+ days

Red

Critically overdue — escalate

### 3.5 Header / Totals

*   The ALV title bar displays: **"Overdue Purchase Orders — Company Code: <BUKRS>"**
*   Subtotals on the Vendor field for: Outstanding Qty, Net Value
*   Grand totals at bottom for: Outstanding Qty, Net Value (per currency)
*   Record count shown in the ALV status bar

## 4 Data Sources

### 4.1 SAP Tables Read

Table

Description

Key Fields Used

Purpose

EKKO

Purchasing Document Header

EBELN, BUKRS, BSTYP, LIFNR, EKORG, EKGRP, BEDAT, LOEKZ, WAERS

PO header selection & filters

EKPO

Purchasing Document Item

EBELN, EBELP, MATNR, TXZ01, WERKS, NETWR, MEINS, ELIKZ, LOEKZ

PO line-item details & delivery-complete check

EKET

Scheduling Agreement Schedule Lines

EBELN, EBELP, ETENR, EINDT, MENGE, WEMNG

Delivery date & quantity comparison

LFA1

Vendor Master (General Section)

LIFNR, NAME1, ORT01

Vendor name & city enrichment

T001

Company Codes

BUKRS, BUTXT

F4 help & header display

### 4.2 Join Relationships

#mermaid-1792738440899{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1792738440899 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1792738440899 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1792738440899 .error-icon{fill:#552222;}#mermaid-1792738440899 .error-text{fill:#552222;stroke:#552222;}#mermaid-1792738440899 .edge-thickness-normal{stroke-width:1px;}#mermaid-1792738440899 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1792738440899 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1792738440899 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1792738440899 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1792738440899 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1792738440899 .marker{fill:#666;stroke:#666;}#mermaid-1792738440899 .marker.cross{stroke:#666;}#mermaid-1792738440899 svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-1792738440899 p{margin:0;}#mermaid-1792738440899 .label{font-family:"trebuchet ms",verdana,arial,sans-serif;color:#000000;}#mermaid-1792738440899 .cluster-label text{fill:#333;}#mermaid-1792738440899 .cluster-label span{color:#333;}#mermaid-1792738440899 .cluster-label span p{background-color:transparent;}#mermaid-1792738440899 .label text,#mermaid-1792738440899 span{fill:#000000;color:#000000;}#mermaid-1792738440899 .node rect,#mermaid-1792738440899 .node circle,#mermaid-1792738440899 .node ellipse,#mermaid-1792738440899 .node polygon,#mermaid-1792738440899 .node path{fill:#eee;stroke:#999;stroke-width:1px;}#mermaid-1792738440899 .rough-node .label text,#mermaid-1792738440899 .node .label text,#mermaid-1792738440899 .image-shape .label,#mermaid-1792738440899 .icon-shape .label{text-anchor:middle;}#mermaid-1792738440899 .node .katex path{fill:#000;stroke:#000;stroke-width:1px;}#mermaid-1792738440899 .rough-node .label,#mermaid-1792738440899 .node .label,#mermaid-1792738440899 .image-shape .label,#mermaid-1792738440899 .icon-shape .label{text-align:center;}#mermaid-1792738440899 .node.clickable{cursor:pointer;}#mermaid-1792738440899 .root .anchor path{fill:#666!important;stroke-width:0;stroke:#666;}#mermaid-1792738440899 .arrowheadPath{fill:#333333;}#mermaid-1792738440899 .edgePath .path{stroke:#666;stroke-width:2.0px;}#mermaid-1792738440899 .flowchart-link{stroke:#666;fill:none;}#mermaid-1792738440899 .edgeLabel{background-color:white;text-align:center;}#mermaid-1792738440899 .edgeLabel p{background-color:white;}#mermaid-1792738440899 .edgeLabel rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1792738440899 .labelBkg{background-color:rgba(255, 255, 255, 0.5);}#mermaid-1792738440899 .cluster rect{fill:hsl(0, 0%, 98.9215686275%);stroke:#707070;stroke-width:1px;}#mermaid-1792738440899 .cluster text{fill:#333;}#mermaid-1792738440899 .cluster span{color:#333;}#mermaid-1792738440899 div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:12px;background:hsl(-160, 0%, 93.3333333333%);border:1px solid #707070;border-radius:2px;pointer-events:none;z-index:100;}#mermaid-1792738440899 .flowchartTitleText{text-anchor:middle;font-size:18px;fill:#000000;}#mermaid-1792738440899 rect.text{fill:none;stroke-width:0;}#mermaid-1792738440899 .icon-shape,#mermaid-1792738440899 .image-shape{background-color:white;text-align:center;}#mermaid-1792738440899 .icon-shape p,#mermaid-1792738440899 .image-shape p{background-color:white;padding:2px;}#mermaid-1792738440899 .icon-shape .label rect,#mermaid-1792738440899 .image-shape .label rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1792738440899 .label-icon{display:inline-block;height:1em;overflow:visible;vertical-align:-0.125em;}#mermaid-1792738440899 .node .label-icon path{fill:currentColor;stroke:revert;stroke-width:revert;}#mermaid-1792738440899 :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}

EBELN

EBELN + EBELP

LIFNR

BUKRS

EKKO

EKPO

EKET

LFA1

T001

## 5 Authorization Requirements

Authorization Object

Field

Value

Purpose

M\_BEST\_BSA

BSART

\* (all PO types)

Access to purchasing documents by doc type

M\_BEST\_EKG

EKGRP

User's purchasing groups

Access to purchasing documents by purchasing group

M\_BEST\_EKO

EKORG

User's purchasing organisations

Access to purchasing documents by purchasing org

M\_BEST\_WRK

WERKS

User's plants

Access to purchasing documents by plant

F\_BKPF\_BUK

BUKRS

User's company codes

Access to financial documents by company code

**Note:** Authorization checks should verify at minimum that the user has display access (ACTVT = '03') to purchasing documents for the entered company code. If authorization fails, display an appropriate message and prevent data retrieval.

## 6 Messages

Msg #

Type

Trigger

Text

M01

E (Error)

Minimum Overdue Days < 1

"Minimum overdue days must be at least 1."

M02

I (Info)

No overdue POs found

"No overdue purchase orders found for company code &1 with the given selection criteria."

M03

S (Success)

Report displayed

"&1 overdue schedule line(s) found across &2 vendor(s)."

M04

E (Error)

Authorization check failed

"You are not authorized to display purchasing data for company code &1."

## 7 Error & Edge-Case Handling

Scenario

Expected Behaviour

No data matches the selection criteria

Display info message M02. Do not show an empty ALV — return to selection screen.

PO item has no schedule lines in EKET

Skip the item (no delivery date to evaluate).

EKET-EINDT is initial (00000000)

Skip the schedule line — a blank delivery date cannot be evaluated for overdue status.

EKET-MENGE = 0 and WEMNG = 0

Skip the schedule line — no ordered quantity means nothing is overdue.

EKET-WEMNG > EKET-MENGE (over-delivery)

Skip the schedule line — the item is already fulfilled (outstanding qty would be negative).

Vendor not found in LFA1

Show LIFNR with blank NAME1 and ORT01 — do not skip the line.

Company code not found in T001

Show error on selection screen — invalid company code.

## 8 Non-Functional Requirements

Requirement

Target

Performance

Report should execute within 30 seconds for up to 50,000 PO items. Use indexed access via BUKRS on EKKO and FOR ALL ENTRIES for EKET/LFA1 lookups.

Compatibility

ECC 6.0 / SAP\_BASIS 740 — no AMDP, no RAP, no CDS. CL\_SALV\_TABLE for ALV.

Concurrency

Read-only report — no locking required.

Transportability

Must be deployable via standard transport request to Q/P systems.

Language

All user-visible texts are translatable (text elements or message class).

## 9 Test Scenarios (Acceptance Criteria)

#

Scenario

Inputs

Expected Result

Type

TS-01

Basic positive — overdue POs exist

Company code with known overdue POs (e.g. 1000). Min overdue days = 1.

ALV displays overdue lines grouped by vendor, sorted by overdue days descending. Subtotals per vendor. Colour coding applied.

Positive

TS-02

No overdue POs

Company code where all deliveries are on time, or a future PO date range.

Info message M02 displayed. No ALV shown. User returns to selection screen.

Negative

TS-03

Vendor filter

Company code 1000 + specific vendor number.

Only POs for the specified vendor appear.

Positive

TS-04

Minimum overdue days threshold

Company code 1000, Min overdue days = 30.

Only schedule lines overdue by ≥ 30 days appear. Lines overdue 1–29 days are excluded.

Boundary

TS-05

Min overdue days = 0

P\_DAYS = 0

Error message M01. Report does not execute.

Negative

TS-06

PO with multiple schedule lines

PO with 3 schedule lines: 1 overdue, 1 on time, 1 fully delivered.

Only the 1 overdue schedule line appears. The on-time and delivered lines are excluded.

Edge case

TS-07

Over-delivered schedule line

PO where WEMNG > MENGE on a schedule line.

Schedule line is skipped — does not appear in output.

Edge case

TS-08

Multiple company codes in system

Run for 1000 (EUR), then 1010 (INR).

Each run shows only POs for the entered company code. Currency column reflects the correct currency.

Positive

TS-09

Colour coding verification

Company code with POs overdue by 5, 45, and 90 days.

5-day row = yellow, 45-day row = orange, 90-day row = red.

Positive

TS-10

ALV export

Execute report, then export to Excel via ALV toolbar.

Excel download completes with all columns and data intact.

Positive

## 10 Transaction Code & Execution

Item

Value

Program Name

Z\_MM\_OVERDUE\_PO\_VENDOR

Execution

Via SA38 / SE38 (no custom T-code initially; can be assigned later)

Package

To be determined at Technical Specification stage

Transport

To be determined at Technical Specification stage

Comparable SAP Standard

ME2M (PO per material), ME2N (PO per PO number) — this report adds overdue-days calculation and vendor-centric grouping not available in standard

## 11 Open Items & Assumptions

### Assumptions

*   The report evaluates overdue status as of the current system date (SY-DATUM). There is no requirement to evaluate as of a historical date.
*   Delivery date is taken from the PO schedule line (EKET-EINDT), not from inbound delivery or shipping notification dates.
*   Net value (EKPO-NETWR) is shown for informational context only; it represents the full item value, not the outstanding value. Outstanding value calculation (proportional to outstanding qty) is not in scope for this version.
*   Only standard purchase orders (BSTYP = 'F') are in scope. Contracts and scheduling agreements follow different fulfilment patterns.
*   The system has reliable schedule-line data in EKET for POs (SAP standard — maintained automatically by ME21N/ME22N).

### Open Items

#

Item

Decision Needed By

Impact

O-01

Should the report also calculate outstanding value (proportional NETWR based on outstanding qty / scheduled qty)?

Business owner

Adds a calculated column; requires division-by-zero guard for MENGE = 0

O-02

Should a custom transaction code be created for this report?

Basis / Change Management

Easier navigation for end users

O-03

Should the report include a "Send Reminder" button that triggers a workflow or email to the vendor contact?

Business owner

Significant scope increase — would be a separate WRICEF

O-04

Are there company-code-specific overdue thresholds (e.g. 1000 uses 7 days, 1010 uses 14 days) or is a single user-entered threshold sufficient?

Business owner

Would require a custom config table if company-specific

## 12 Appendix — Company Codes Available

The following company codes are configured in the target system and can be used for testing:

Company Code

Description

Currency

Country

0001

SAP A.G.

EUR

DE

0005

BestRun Germany new GL

EUR

DE

0006

BestRun US INC New GL

USD

US

1000

BestRun Germany

EUR

DE

1002

BestRun Singapore

SGD

SG

1010

BestRun INDIA 1010

INR

IN

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