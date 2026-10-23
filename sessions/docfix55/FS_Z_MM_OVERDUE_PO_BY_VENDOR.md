  FS Z MM OVERDUE PO BY VENDOR @page { size: A4; margin: 20mm 18mm 20mm 18mm; } \* { box-sizing: border-box; margin: 0; padding: 0; } body { font-family: 'Segoe UI', Calibri, Arial, sans-serif; font-size: 10.5pt; line-height: 1.55; color: #1a1a1a; background: #f4f5f6; -webkit-print-color-adjust: exact; print-color-adjust: exact; } .doc-wrapper { max-width: 1100px; margin: 24px auto; background: #ffffff; box-shadow: 0 1px 8px rgba(0,0,0,0.08); border: 1px solid #d0d4d8; } /\* HEADER \*/ .doc-header { background: #003366; color: #ffffff; padding: 28px 36px 24px 36px; border-bottom: 4px solid #7fb3e0; } .doc-header-top { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 14px; } .doc-logo img { height: 40px; display: block; } .doc-classification { font-size: 8.5pt; letter-spacing: 1.2px; text-transform: uppercase; color: #7fb3e0; border: 1px solid #7fb3e0; padding: 3px 12px; border-radius: 2px; white-space: nowrap; } .doc-header h1 { font-size: 22pt; font-weight: 600; letter-spacing: -0.3px; margin: 0 0 4px 0; line-height: 1.2; } .doc-header .doc-subtitle { font-size: 11pt; color: #7fb3e0; font-weight: 400; } /\* META \*/ .doc-meta { padding: 16px 36px; background: #f7f8fa; border-bottom: 1px solid #d0d4d8; font-size: 9.5pt; color: #444; } .doc-meta table { width: 100%; border-collapse: collapse; } .doc-meta td { padding: 3px 12px 3px 0; vertical-align: top; } .doc-meta .meta-label { font-weight: 600; color: #003366; width: 90px; } /\* BODY \*/ .doc-body { padding: 28px 36px 36px 36px; background: #ffffff; } .doc-body p { margin: 8px 0; } .doc-body h2 { font-size: 14pt; color: #003366; margin: 24px 0 12px 0; padding-bottom: 6px; border-bottom: 2px solid #7fb3e0; display: flex; align-items: center; gap: 10px; } .doc-body h2 .sec-num { display: inline-block; background: #003366; color: white; font-size: 11pt; font-weight: 700; padding: 2px 9px; border-radius: 3px; line-height: 1; min-width: 26px; text-align: center; } .doc-body h3 { font-size: 11.5pt; color: #003366; margin: 18px 0 8px 0; font-weight: 600; } .doc-body h4 { font-size: 10.5pt; color: #1a5c8a; margin: 12px 0 6px 0; font-weight: 600; } .doc-body ul, .doc-body ol { margin: 8px 0 8px 22px; } .doc-body li { margin: 4px 0; } /\* TABLES \*/ table.data { width: 100%; border-collapse: collapse; margin: 10px 0 14px 0; font-size: 9.5pt; } table.data th, table.data td { border: 1px solid #d0d4d8; padding: 7px 10px; text-align: left; vertical-align: top; } table.data th { background: #003366; color: white; font-weight: 600; letter-spacing: 0.2px; } table.data tr:nth-child(even) td { background: #f7f8fa; } table.data td.center { text-align: center; } /\* CALLOUTS \*/ .callout { background: #f0f6fa; border-left: 4px solid #1a5c8a; padding: 12px 16px; margin: 14px 0; font-size: 10pt; color: #1f2937; } .callout.tip { border-left-color: #15803D; background: #f0fdf4; } .callout.warning { border-left-color: #C2410C; background: #fff7ed; } /\* PILLS — Clean Core levels \*/ .pill { display: inline-block; font-size: 8.5pt; font-weight: 600; padding: 2px 9px; border-radius: 10px; letter-spacing: 0.3px; white-space: nowrap; } .pill-a { background: #dcfce7; color: #15803D; } .pill-b { background: #dbeafe; color: #1D4ED8; } .pill-c { background: #fef3c7; color: #A16207; } .pill-d { background: #fee2e2; color: #B91C1C; } /\* SYSTEM PILLS — engagement context strip under the header \*/ .doc-pills { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 14px; } .doc-pills .doc-pill { display: inline-flex; align-items: center; gap: 6px; font-size: 8.5pt; font-weight: 500; padding: 4px 12px; border-radius: 16px; background: rgba(255, 255, 255, 0.12); border: 1px solid rgba(255, 255, 255, 0.28); color: #ffffff; letter-spacing: 0.2px; white-space: nowrap; } .doc-pills .doc-pill .doc-pill-icon { font-size: 9pt; opacity: 0.9; } .doc-pills .doc-pill.danger { background: rgba(254, 226, 226, 0.18); border-color: rgba(254, 226, 226, 0.35); } .doc-pills .doc-pill.warn { background: rgba(254, 243, 199, 0.15); border-color: rgba(254, 243, 199, 0.35); } /\* KPI STRIP — volume counters under the pills \*/ .doc-kpi-strip { display: flex; flex-wrap: wrap; gap: 18px; margin-top: 14px; padding-top: 12px; border-top: 1px solid rgba(255, 255, 255, 0.18); font-size: 9pt; color: rgba(255, 255, 255, 0.92); } .doc-kpi-strip .doc-kpi { display: inline-flex; align-items: center; gap: 5px; white-space: nowrap; } .doc-kpi-strip .doc-kpi-icon { font-size: 10.5pt; } .doc-kpi-strip .doc-kpi-value { font-weight: 700; color: #ffffff; } .doc-kpi-strip .doc-kpi-label { color: rgba(255, 255, 255, 0.78); } /\* PHASE TIMELINE \*/ .phase { border-left: 3px solid #7fb3e0; padding: 10px 16px; margin: 10px 0; background: #f7f8fa; } .phase strong { color: #003366; } .phase .phase-dur { color: #1a5c8a; font-size: 9pt; } /\* DOC FOOTER (inside wrapper) \*/ .doc-footer { background: #f7f8fa; border-top: 1px solid #d0d4d8; padding: 16px 36px; font-size: 9pt; color: #555; } .doc-footer table { width: 100%; } .doc-footer .footer-right { text-align: right; color: #003366; font-weight: 600; } @media print { body { background: white; } .doc-wrapper { box-shadow: none; border: none; margin: 0; max-width: 100%; } h2, h3 { page-break-after: avoid; } table.data { page-break-inside: avoid; } .phase, .callout { page-break-inside: avoid; } }

![C16](data:image/png;base64,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)

Reference

# FS Z MM OVERDUE PO BY VENDOR

Topic

FS Z MM OVERDUE PO BY VENDOR

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

Attribute

Value

Document Type

Functional Specification (FS)

Object ID (proposed)

Z\_MM\_OVERDUE\_PO\_VENDOR

Object Title

Overdue Purchase Orders by Vendor

WRICEF Type

R – Report

Module

MM – Purchasing (P2P)

Target System

SAP ECC 6.0, SAP\_BASIS 740, client 800

Transaction Code (proposed)

ZMM\_OVDPO

Version

1.0 – Draft for review

Date

23 October 2026

Priority / Complexity

Medium / Medium

### 1.1 Revision History

Version

Date

Author

Description

1.0

23-Oct-2026

C16 (draft)

First draft, written from the business requirement

—

—

—

Business review / sign-off (pending)

### 1.2 Approvals

Role

Name

Date

Signature

Business Process Owner (Procurement)

TBD

Functional Lead MM

TBD

Technical Lead ABAP

TBD

## 2 Business Requirement

### 2.1 Requirement Statement

Procurement needs a report that lists **overdue purchase orders grouped by vendor** for one **company code**. Users enter their criteria on a selection screen. The result appears in an interactive ALV grid, so buyers and supply-chain managers can see which vendors are late, by how many days, and how much open value is affected. They can then expedite or escalate.

### 2.2 Business Objectives

*   See all late deliveries for each vendor and company code in one place.
*   Rank vendors by overdue open value and by days late, so expediting effort goes where it matters most.
*   Replace manual work in ME2M / ME2L and spreadsheet consolidation.
*   Support vendor-performance discussions with objective ageing buckets.

### 2.3 Scope

In Scope

Out of Scope

Standard purchase orders (document category F)

Contracts, scheduling agreements, RFQs (BSTYP K / L / A)

Overdue checks at schedule-line level (delivery date vs key date)

Invoice / payment overdue status (handled by AP ageing)

One company code per run (mandatory)

Cross-company-code consolidation in a single run

Display in ALV, with export to Excel through standard ALV functions

Automatic vendor e-mails or reminder output (possible later phase)

Online and background execution (with a layout variant)

Changing POs (the report is read-only)

### 2.4 Users & Frequency

User Group

Usage

Frequency

Buyers / Purchasing Group

Daily expediting list

Daily (online)

Procurement Manager

Vendor escalation, KPI review

Weekly

Supply Chain Planning

Material-availability risk

Ad hoc

## 3 Definitions & Business Rules

### 3.1 Definition of "Overdue"

A PO schedule line is **overdue** if **all** of these are true:

1.  Header: `EKKO-BUKRS = P_BUKRS`, `EKKO-BSTYP = 'F'`, `EKKO-LOEKZ = space`.
2.  Item: `EKPO-LOEKZ = space` (not deleted or blocked) and `EKPO-ELIKZ = space` (delivery not completed).
3.  Schedule line: `EKET-EINDT < P_KEYDT` (delivery date before the key date; default key date = today). Lines where `EINDT` is initial (00000000) are skipped.
4.  Open quantity > 0, where `Open Qty = EKET-MENGE − EKET-WEMNG`.
5.  Days overdue ≥ `P_MINDAY` (default 1).

### 3.2 Calculated Fields

Field

Formula

Rule

Open Quantity

EKET-MENGE − EKET-WEMNG

Only rows with a result > 0 are kept

Days Overdue

P\_KEYDT − EKET-EINDT

Integer; if the result is negative, set to 0 and exclude

Open Value

Open Qty × EKPO-NETPR / EKPO-PEINH

If PEINH = 0, use 1. Result in the PO currency (EKKO-WAERS). Use a wide packed type (P LENGTH 15 DECIMALS 2) to avoid overflow

Ageing Bucket

Based on Days Overdue

1–30 · 31–60 · 61–90 · >90 days

Traffic Light

Based on Ageing Bucket

Yellow 1–30 · Orange 31–60 · Red >60

### 3.3 Key Business Rules

*   **BR-01 Currency:** Open values are never totalled across currencies. Vendor subtotals are built per vendor _and_ per currency (EKKO-WAERS).
*   **BR-02 Granularity:** The detail level is the schedule line (EBELN / EBELP / ETENR). One PO item can have several overdue schedule lines.
*   **BR-03 Vendor:** The vendor is EKKO-LIFNR. The name comes from LFA1-NAME1. Vendors with a central posting block (LFA1-SPERR) or purchasing block (LFA1-SPERM) are still listed, with a "Blocked" indicator.
*   **BR-04 Number formats:** EBELN and LIFNR are 10 characters and MATNR is 18 characters (ECC). They are shown with conversion exits (leading zeros suppressed).
*   **BR-05 Read-only:** The report changes no data.

## 4 Selection Screen

### 4.1 Block 1 – Organisational Data

Technical Name

Label

Type / Reference

Kind

Mandatory

Default

P\_BUKRS

Company Code

EKKO-BUKRS (BUKRS, CHAR 4)

Parameter

Yes

User parameter BUK

S\_EKORG

Purchasing Organization

EKKO-EKORG (EKORG, CHAR 4)

Select-option

No

—

S\_EKGRP

Purchasing Group

EKKO-EKGRP (BKGRP, CHAR 3)

Select-option

No

—

S\_WERKS

Plant

EKPO-WERKS (EWERK, CHAR 4)

Select-option

No

—

### 4.2 Block 2 – Document / Vendor Data

Technical Name

Label

Type / Reference

Kind

Mandatory

Default

S\_LIFNR

Vendor

EKKO-LIFNR (ELIFN, CHAR 10)

Select-option

No

—

S\_EBELN

Purchasing Document

EKKO-EBELN (EBELN, CHAR 10)

Select-option

No

—

S\_BSART

PO Document Type

EKKO-BSART (ESART, CHAR 4)

Select-option

No

—

S\_MATNR

Material

EKPO-MATNR (MATNR, CHAR 18)

Select-option

No

—

S\_BEDAT

PO Date

EKKO-BEDAT (EBDAT, DATS)

Select-option

No

—

### 4.3 Block 3 – Overdue Criteria & Output

Technical Name

Label

Type / Reference

Kind

Mandatory

Default

S\_EINDT

Delivery Date

EKET-EINDT (EINDT, DATS)

Select-option

No

—

P\_KEYDT

Key Date (overdue as of)

SY-DATUM (DATS)

Parameter

Yes

Today

P\_MINDAY

Minimum Days Overdue

INT4 (0–9999)

Parameter

No

1

P\_DETAIL / P\_SUMM

Output: Detail (schedule lines) / Vendor Summary

Radio-button group

Radio

—

Detail

P\_VARI

ALV Layout

SLIS\_VARI / DISVARIANT-VARIANT

Parameter (F4 help)

No

User default layout

Each organisational or master-data field uses its DDIC type (CHAR keys are never typed as dates). Only P\_KEYDT, S\_BEDAT and S\_EINDT are date fields.

### 4.4 Validation of Selection Criteria

#

Check

Event

Message Type

Message Text

V1

P\_BUKRS exists in T001

AT SELECTION-SCREEN ON P\_BUKRS

E

Company code &1 does not exist

V2

User is authorised for at least one purchasing org in S\_EKORG (M\_BEST\_EKO)

AT SELECTION-SCREEN

E

No authorization for purchasing organization &1

V3

P\_KEYDT is not initial

AT SELECTION-SCREEN ON P\_KEYDT

E

Enter a valid key date

V4

P\_MINDAY ≥ 0

AT SELECTION-SCREEN ON P\_MINDAY

E

Minimum days overdue cannot be negative

V5

Upper bound of S\_EINDT is ≤ P\_KEYDT

AT SELECTION-SCREEN

W

Delivery dates after the key date are never overdue

V6

P\_VARI layout exists for the report

AT SELECTION-SCREEN ON P\_VARI

E

Layout &1 does not exist

## 5 Data Sources

### 5.1 SAP Tables Read (verified against the target dictionary)

Table

Description

Key Fields Used

Fields Read

EKKO

Purchasing Document Header

EBELN

EBELN, BUKRS, BSTYP, BSART, LOEKZ, LIFNR, EKORG, EKGRP, BEDAT, WAERS, ZTERM

EKPO

Purchasing Document Item

EBELN, EBELP

EBELP, LOEKZ, ELIKZ, MATNR, TXZ01, WERKS, LGORT, MENGE, MEINS, NETPR, PEINH, NETWR, MATKL

EKET

Schedule Lines

EBELN, EBELP, ETENR

ETENR, EINDT, MENGE, WEMNG

LFA1

Vendor Master (General)

LIFNR

NAME1, ORT01, LAND1, SPERR, SPERM

T001

Company Codes

BUKRS

BUTXT, WAERS (validation and header text)

T024

Purchasing Groups

EKGRP

EKNAM (buyer name, optional column)

### 5.2 Company Codes in the Target System (sample from T001)

BUKRS

Name

Currency

Country

1000

BestRun Germany

EUR

DE

1010

BestRun INDIA 1010

INR

IN

1710

BestRun INDIA

INR

IN

2000

BestRun UK

GBP

GB

2200

BestRun France

EUR

FR

0006

BestRun US INC New GL

USD

US

The company codes use different local currencies (EUR, INR, GBP, USD, SGD). This is why rule BR-01 (no blending of currencies) is required.

### 5.3 Entity Relationships

#mermaid-1792751260627{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1792751260627 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1792751260627 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1792751260627 .error-icon{fill:#552222;}#mermaid-1792751260627 .error-text{fill:#552222;stroke:#552222;}#mermaid-1792751260627 .edge-thickness-normal{stroke-width:1px;}#mermaid-1792751260627 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1792751260627 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1792751260627 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1792751260627 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1792751260627 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1792751260627 .marker{fill:#666;stroke:#666;}#mermaid-1792751260627 .marker.cross{stroke:#666;}#mermaid-1792751260627 svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-1792751260627 p{margin:0;}#mermaid-1792751260627 .entityBox{fill:#eee;stroke:#999;}#mermaid-1792751260627 .relationshipLabelBox{fill:hsl(-160, 0%, 93.3333333333%);opacity:0.7;background-color:hsl(-160, 0%, 93.3333333333%);}#mermaid-1792751260627 .relationshipLabelBox rect{opacity:0.5;}#mermaid-1792751260627 .labelBkg{background-color:rgba(237.9999999999, 237.9999999999, 237.9999999999, 0.5);}#mermaid-1792751260627 .edgeLabel .label{fill:#999;font-size:14px;}#mermaid-1792751260627 .label{font-family:"trebuchet ms",verdana,arial,sans-serif;color:#000000;}#mermaid-1792751260627 .edge-pattern-dashed{stroke-dasharray:8,8;}#mermaid-1792751260627 .node rect,#mermaid-1792751260627 .node circle,#mermaid-1792751260627 .node ellipse,#mermaid-1792751260627 .node polygon{fill:#eee;stroke:#999;stroke-width:1px;}#mermaid-1792751260627 .relationshipLine{stroke:#666;stroke-width:1;fill:none;}#mermaid-1792751260627 .marker{fill:none!important;stroke:#666!important;stroke-width:1;}#mermaid-1792751260627 .edgeLabel{background-color:white;}#mermaid-1792751260627 .edgeLabel .label rect{fill:white;}#mermaid-1792751260627 .edgeLabel .label text{fill:#000000;}#mermaid-1792751260627 :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}

BUKRS

LIFNR

EBELN

EBELN+EBELP

EKGRP

T001

EKKO

LFA1

EKPO

EKET

T024

## 6 Processing Logic

#mermaid-1792751262779{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1792751262779 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1792751262779 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1792751262779 .error-icon{fill:#552222;}#mermaid-1792751262779 .error-text{fill:#552222;stroke:#552222;}#mermaid-1792751262779 .edge-thickness-normal{stroke-width:1px;}#mermaid-1792751262779 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1792751262779 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1792751262779 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1792751262779 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1792751262779 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1792751262779 .marker{fill:#666;stroke:#666;}#mermaid-1792751262779 .marker.cross{stroke:#666;}#mermaid-1792751262779 svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-1792751262779 p{margin:0;}#mermaid-1792751262779 .label{font-family:"trebuchet ms",verdana,arial,sans-serif;color:#000000;}#mermaid-1792751262779 .cluster-label text{fill:#333;}#mermaid-1792751262779 .cluster-label span{color:#333;}#mermaid-1792751262779 .cluster-label span p{background-color:transparent;}#mermaid-1792751262779 .label text,#mermaid-1792751262779 span{fill:#000000;color:#000000;}#mermaid-1792751262779 .node rect,#mermaid-1792751262779 .node circle,#mermaid-1792751262779 .node ellipse,#mermaid-1792751262779 .node polygon,#mermaid-1792751262779 .node path{fill:#eee;stroke:#999;stroke-width:1px;}#mermaid-1792751262779 .rough-node .label text,#mermaid-1792751262779 .node .label text,#mermaid-1792751262779 .image-shape .label,#mermaid-1792751262779 .icon-shape .label{text-anchor:middle;}#mermaid-1792751262779 .node .katex path{fill:#000;stroke:#000;stroke-width:1px;}#mermaid-1792751262779 .rough-node .label,#mermaid-1792751262779 .node .label,#mermaid-1792751262779 .image-shape .label,#mermaid-1792751262779 .icon-shape .label{text-align:center;}#mermaid-1792751262779 .node.clickable{cursor:pointer;}#mermaid-1792751262779 .root .anchor path{fill:#666!important;stroke-width:0;stroke:#666;}#mermaid-1792751262779 .arrowheadPath{fill:#333333;}#mermaid-1792751262779 .edgePath .path{stroke:#666;stroke-width:2.0px;}#mermaid-1792751262779 .flowchart-link{stroke:#666;fill:none;}#mermaid-1792751262779 .edgeLabel{background-color:white;text-align:center;}#mermaid-1792751262779 .edgeLabel p{background-color:white;}#mermaid-1792751262779 .edgeLabel rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1792751262779 .labelBkg{background-color:rgba(255, 255, 255, 0.5);}#mermaid-1792751262779 .cluster rect{fill:hsl(0, 0%, 98.9215686275%);stroke:#707070;stroke-width:1px;}#mermaid-1792751262779 .cluster text{fill:#333;}#mermaid-1792751262779 .cluster span{color:#333;}#mermaid-1792751262779 div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:12px;background:hsl(-160, 0%, 93.3333333333%);border:1px solid #707070;border-radius:2px;pointer-events:none;z-index:100;}#mermaid-1792751262779 .flowchartTitleText{text-anchor:middle;font-size:18px;fill:#000000;}#mermaid-1792751262779 rect.text{fill:none;stroke-width:0;}#mermaid-1792751262779 .icon-shape,#mermaid-1792751262779 .image-shape{background-color:white;text-align:center;}#mermaid-1792751262779 .icon-shape p,#mermaid-1792751262779 .image-shape p{background-color:white;padding:2px;}#mermaid-1792751262779 .icon-shape .label rect,#mermaid-1792751262779 .image-shape .label rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1792751262779 .label-icon{display:inline-block;height:1em;overflow:visible;vertical-align:-0.125em;}#mermaid-1792751262779 .node .label-icon path{fill:currentColor;stroke:revert;stroke-width:revert;}#mermaid-1792751262779 :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}

No

Yes

No

Yes

Detail

Summary

Selection screen input

Validations V1-V6 OK?

Read EKKO + EKPO + EKET for the company code, filtered by selection

Keep lines with EINDT before key date and open qty above 0

Any rows?

Message: no overdue POs found

Authorization filter: purchasing org, group, plant, doc type

Read vendor names from LFA1 for distinct LIFNR

Calculate days overdue, open value, ageing bucket, traffic light

Output mode

ALV schedule-line list, sorted by vendor, subtotals per vendor and currency

Aggregate per vendor and currency, then show ALV summary

### 6.1 Step-by-Step Logic

1.  **Initialisation:** Set P\_KEYDT = SY-DATUM, P\_MINDAY = 1, read the default ALV layout, and set frame titles.
2.  **Data selection (single DB round trip):** Use an INNER JOIN EKKO → EKPO (EBELN) → EKET (EBELN, EBELP) with these conditions: `EKKO-BUKRS = P_BUKRS`, `BSTYP = 'F'`, `EKKO-LOEKZ = space`, `EKPO-LOEKZ = space`, `EKPO-ELIKZ = space`, `EKET-EINDT < P_KEYDT`, `EKET-EINDT <> '00000000'`, and all select-options. Select only the columns listed in §5.1 (no SELECT \*).
3.  **Open-quantity filter:** In ABAP, drop rows where MENGE − WEMNG ≤ 0.
4.  **Authorization filter:** Remove rows the user is not allowed to display (see §8) and count them for the information message.
5.  **Vendor master:** If the result is not empty, read LFA1 with FOR ALL ENTRIES on the distinct LIFNR values into a hashed table, then do key reads (no SELECT inside a LOOP).
6.  **Calculations:** Calculate the fields in §3.2. Guard every division (PEINH = 0 → 1). Ignore negative day values.
7.  **Min-days filter:** Drop rows where Days Overdue < P\_MINDAY.
8.  **Summary mode:** Group by LIFNR + WAERS. Output: number of POs, number of schedule lines, total open value, maximum days overdue, average days overdue, and open value per ageing bucket.
9.  **Output:** Show the result in CL\_SALV\_TABLE (see §7).

### 6.2 Performance Considerations

*   The company code is mandatory, so the header read is always restricted. EKET has no index on EINDT, so filtering on EINDT through the join is acceptable when BUKRS / EKORG are restricted.
*   Expected volume: ≤ 50,000 schedule lines per company code. Recommend running in background for full company codes with no other restriction.
*   Use FOR ALL ENTRIES only after an IS NOT INITIAL check on the driver table.

## 7 Output – ALV Layout

### 7.1 Detail Mode (default)

#

Column

Source

Sort / Subtotal

Notes

1

Traffic Light

Calculated

—

Icon / colour by ageing bucket

2

Vendor

EKKO-LIFNR

Sort 1, subtotal

Hotspot → XK03 (display vendor)

3

Vendor Name

LFA1-NAME1

—

4

Blocked

LFA1-SPERR / SPERM

—

Checkbox display

5

Currency

EKKO-WAERS

Sort 2, subtotal

Reference for open value

6

Purchasing Document

EKKO-EBELN

Sort 3

Hotspot → ME23N

7

Item

EKPO-EBELP

Sort 4

8

Schedule Line

EKET-ETENR

—

9

Document Type

EKKO-BSART

—

10

Purch. Org / Group

EKKO-EKORG / EKGRP

—

11

Plant

EKPO-WERKS

—

12

Material / Short Text

EKPO-MATNR / TXZ01

—

13

PO Date

EKKO-BEDAT

—

14

Delivery Date

EKET-EINDT

—

15

Scheduled Qty

EKET-MENGE

—

Unit EKPO-MEINS

16

Received Qty

EKET-WEMNG

—

17

Open Qty

Calculated

—

18

Net Price / Price Unit

EKPO-NETPR / PEINH

—

19

Open Value

Calculated

Sum

Per currency only

20

Days Overdue

Calculated

Max on subtotal

21

Ageing Bucket

Calculated

—

Text 1–30 / 31–60 / 61–90 / >90

### 7.2 Summary Mode

Column

Description

Vendor / Name / Currency

Grouping keys

No. of POs / No. of Schedule Lines

Distinct EBELN count / row count

Total Open Value

Sum of the open value (per currency)

Value 1–30 / 31–60 / 61–90 / >90

Open value per ageing bucket

Max / Avg Days Overdue

Worst and average lateness

Default sort in summary mode: Total Open Value, descending (the worst vendors appear first).

### 7.3 ALV Features

*   Standard toolbar (sort, filter, sum, Excel export, layout save) through `CL_SALV_TABLE` (classic SAP GUI ALV, compatible with SAP\_BASIS 740).
*   Column headers come from the DDIC data-element texts. Only the calculated columns have explicit short, medium and long texts.
*   Header line: Company Code + Name (T001-BUTXT), Key Date, number of records.
*   Hotspots: EBELN → ME23N, LIFNR → XK03 (display only).
*   Saving user-specific and global layouts is allowed.

## 8 Authorization Requirements

Auth Object

Field(s)

Value

Purpose

S\_TCODE

TCD

ZMM\_OVDPO

Start the transaction

M\_BEST\_EKO

EKORG, ACTVT

Purch. org, 03

Display POs per purchasing organization

M\_BEST\_EKG

EKGRP, ACTVT

Purch. group, 03

Display POs per purchasing group

M\_BEST\_WRK

WERKS, ACTVT

Plant, 03

Display POs per plant

M\_BEST\_BSA

BSART, ACTVT

Doc type, 03

Display POs per document type

Rows the user is not authorised for are removed without an error. At the end, an information message says how many rows were excluded.

## 9 Messages

No.

Type

Text

When

001

E

Company code &1 does not exist

V1

002

E

No authorization for purchasing organization &1

V2

003

E

Enter a valid key date

V3

004

E

Minimum days overdue cannot be negative

V4

005

W

Delivery dates after the key date are never overdue

V5

006

S

No overdue purchase orders found for the selection

Empty result

007

I

&1 records hidden due to missing authorization

After the authorization filter

008

E

Layout &1 does not exist

V6

Proposed message class: **ZMM\_OVDPO**.

## 10 Error Handling

Situation

Handling

What the User Sees

No data selected

Exit before the ALV is built

Message 006 (status bar)

ALV factory fails

CATCH cx\_salv\_msg

Error message, report ends

Column config fails

CATCH cx\_salv\_not\_found (does not stop the report)

Warning; ALV is still shown

Arithmetic overflow / division

PEINH guard, wide packed type, TRY/CATCH cx\_sy\_arithmetic\_error

Row flagged; processing continues

Initial delivery date

Excluded at selection

Not listed (never shown as "infinitely overdue")

## 11 Technical Design Notes (for the TS)

*   One executable program with local classes (no FORM/PERFORM): `lcl_report` (orchestration), `lif_data_access` / `lcl_db_access` (SELECT seam), `lcl_alv` (display).
*   START-OF-SELECTION stays thin and only orchestrates. The business logic is in methods that ABAP Unit can test (a fake data-access class supplies edge-case rows; CL\_OSQL\_TEST\_ENVIRONMENT is not available on SAP\_BASIS 740).
*   Structure fields that receive table columns are typed `TYPE <table>-<field>`. Totals use P LENGTH 15 DECIMALS 2.
*   Background run supported: the ALV prints as a spool list. The layout is taken from P\_VARI.

## 12 Test Scenarios

ID

Type

Scenario

Input

Expected Result

T01

Positive

Overdue PO lines exist for the company code

P\_BUKRS = 1000, key date = today

ALV lists overdue schedule lines, grouped by vendor with subtotals per currency

T02

Positive

Summary mode

As T01 + P\_SUMM

One row per vendor and currency, sorted by open value descending

T03

Positive

Partially received line

Line with MENGE 100, WEMNG 40

Open Qty = 60; open value = 60 × NETPR / PEINH

T04

Negative

Invalid company code

P\_BUKRS = 9999

Error 001; report does not run

T05

Negative

Fully delivered item

EKPO-ELIKZ = X

Line not listed

T06

Negative

Deleted item

EKPO-LOEKZ = L

Line not listed

T07

Boundary

Delivery date = key date

EINDT = P\_KEYDT

Not overdue; not listed

T08

Boundary

Ageing bucket edges

Days overdue 30 / 31 / 60 / 61 / 90 / 91

Correct bucket for each value

T09

Boundary

Price unit 0

PEINH = 0

Treated as 1; no dump

T10

Edge

Vendor with POs in two currencies

EUR + USD POs

Two separate subtotals; no blended total

T11

Edge

No overdue data

Future key-date filter

Message 006

T12

Authorization

User without M\_BEST\_EKO for one purchasing org

Restricted test user

Those rows are hidden; message 007

T13

Reconciliation

Compare with standard

Same PO in ME2L / ME2M (selection parameter WE101)

Open quantities match the standard report

T14

Performance

Full company code in background

P\_BUKRS only

Finishes within agreed SLA (TBD, e.g. < 5 min)

## 13 Assumptions, Dependencies & Open Points

### 13.1 Assumptions

*   "Overdue" means a late _delivery_ (goods receipt), not a late invoice or payment.
*   The schedule-line delivery date (EKET-EINDT) is the agreed due date. The statistical date (SLFDT) is not used.
*   The goods-receipt quantity on the schedule line (EKET-WEMNG) is maintained reliably.

### 13.2 Open Points for Business Sign-off

#

Question

Owner

Status

OP-1

Include stock transport orders (document type UB) or exclude them by default?

Procurement

Open

OP-2

Add a grace period (e.g. GR processing time EKPO-WEBAZ) before a line counts as overdue?

Procurement

Open

OP-3

Should the open value also be converted to company-code currency, as an additional column?

Finance

Open

OP-4

Performance SLA for background runs

IT / Basis

Open

OP-5

Is vendor e-mail / reminder output needed in a later phase?

Procurement

Open

## 14 Standard SAP Alternatives Considered

Standard Option

Gap

ME2M / ME2L / ME2N with parameter WE101

No overdue-day calculation, no ageing buckets, no vendor summary with per-currency subtotals

ME91F (Urging / reminders)

Focuses on output and reminders, not an analytical overview by vendor

Vendor evaluation (ME61 / ME6H)

Gives scores, not an operational list of open late lines

Conclusion: a custom report is justified. The design is read-only and uses standard tables only (classic Level B, compatible with ECC / SAP\_BASIS 740 and S/4HANA on-premise).

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