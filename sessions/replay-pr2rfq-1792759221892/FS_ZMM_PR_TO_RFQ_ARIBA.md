  FS ZMM PR TO RFQ ARIBA @page { size: A4; margin: 20mm 18mm 20mm 18mm; } \* { box-sizing: border-box; margin: 0; padding: 0; } body { font-family: 'Segoe UI', Calibri, Arial, sans-serif; font-size: 10.5pt; line-height: 1.55; color: #1a1a1a; background: #f4f5f6; -webkit-print-color-adjust: exact; print-color-adjust: exact; } .doc-wrapper { max-width: 1100px; margin: 24px auto; background: #ffffff; box-shadow: 0 1px 8px rgba(0,0,0,0.08); border: 1px solid #d0d4d8; } /\* HEADER \*/ .doc-header { background: #003366; color: #ffffff; padding: 28px 36px 24px 36px; border-bottom: 4px solid #7fb3e0; } .doc-header-top { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 14px; } .doc-logo img { height: 40px; display: block; } .doc-classification { font-size: 8.5pt; letter-spacing: 1.2px; text-transform: uppercase; color: #7fb3e0; border: 1px solid #7fb3e0; padding: 3px 12px; border-radius: 2px; white-space: nowrap; } .doc-header h1 { font-size: 22pt; font-weight: 600; letter-spacing: -0.3px; margin: 0 0 4px 0; line-height: 1.2; } .doc-header .doc-subtitle { font-size: 11pt; color: #7fb3e0; font-weight: 400; } /\* META \*/ .doc-meta { padding: 16px 36px; background: #f7f8fa; border-bottom: 1px solid #d0d4d8; font-size: 9.5pt; color: #444; } .doc-meta table { width: 100%; border-collapse: collapse; } .doc-meta td { padding: 3px 12px 3px 0; vertical-align: top; } .doc-meta .meta-label { font-weight: 600; color: #003366; width: 90px; } /\* BODY \*/ .doc-body { padding: 28px 36px 36px 36px; background: #ffffff; } .doc-body p { margin: 8px 0; } .doc-body h2 { font-size: 14pt; color: #003366; margin: 24px 0 12px 0; padding-bottom: 6px; border-bottom: 2px solid #7fb3e0; display: flex; align-items: center; gap: 10px; } .doc-body h2 .sec-num { display: inline-block; background: #003366; color: white; font-size: 11pt; font-weight: 700; padding: 2px 9px; border-radius: 3px; line-height: 1; min-width: 26px; text-align: center; } .doc-body h3 { font-size: 11.5pt; color: #003366; margin: 18px 0 8px 0; font-weight: 600; } .doc-body h4 { font-size: 10.5pt; color: #1a5c8a; margin: 12px 0 6px 0; font-weight: 600; } .doc-body ul, .doc-body ol { margin: 8px 0 8px 22px; } .doc-body li { margin: 4px 0; } /\* TABLES \*/ table.data { width: 100%; border-collapse: collapse; margin: 10px 0 14px 0; font-size: 9.5pt; } table.data th, table.data td { border: 1px solid #d0d4d8; padding: 7px 10px; text-align: left; vertical-align: top; } table.data th { background: #003366; color: white; font-weight: 600; letter-spacing: 0.2px; } table.data tr:nth-child(even) td { background: #f7f8fa; } table.data td.center { text-align: center; } /\* CALLOUTS \*/ .callout { background: #f0f6fa; border-left: 4px solid #1a5c8a; padding: 12px 16px; margin: 14px 0; font-size: 10pt; color: #1f2937; } .callout.tip { border-left-color: #15803D; background: #f0fdf4; } .callout.warning { border-left-color: #C2410C; background: #fff7ed; } /\* PILLS — Clean Core levels \*/ .pill { display: inline-block; font-size: 8.5pt; font-weight: 600; padding: 2px 9px; border-radius: 10px; letter-spacing: 0.3px; white-space: nowrap; } .pill-a { background: #dcfce7; color: #15803D; } .pill-b { background: #dbeafe; color: #1D4ED8; } .pill-c { background: #fef3c7; color: #A16207; } .pill-d { background: #fee2e2; color: #B91C1C; } /\* SYSTEM PILLS — engagement context strip under the header \*/ .doc-pills { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 14px; } .doc-pills .doc-pill { display: inline-flex; align-items: center; gap: 6px; font-size: 8.5pt; font-weight: 500; padding: 4px 12px; border-radius: 16px; background: rgba(255, 255, 255, 0.12); border: 1px solid rgba(255, 255, 255, 0.28); color: #ffffff; letter-spacing: 0.2px; white-space: nowrap; } .doc-pills .doc-pill .doc-pill-icon { font-size: 9pt; opacity: 0.9; } .doc-pills .doc-pill.danger { background: rgba(254, 226, 226, 0.18); border-color: rgba(254, 226, 226, 0.35); } .doc-pills .doc-pill.warn { background: rgba(254, 243, 199, 0.15); border-color: rgba(254, 243, 199, 0.35); } /\* KPI STRIP — volume counters under the pills \*/ .doc-kpi-strip { display: flex; flex-wrap: wrap; gap: 18px; margin-top: 14px; padding-top: 12px; border-top: 1px solid rgba(255, 255, 255, 0.18); font-size: 9pt; color: rgba(255, 255, 255, 0.92); } .doc-kpi-strip .doc-kpi { display: inline-flex; align-items: center; gap: 5px; white-space: nowrap; } .doc-kpi-strip .doc-kpi-icon { font-size: 10.5pt; } .doc-kpi-strip .doc-kpi-value { font-weight: 700; color: #ffffff; } .doc-kpi-strip .doc-kpi-label { color: rgba(255, 255, 255, 0.78); } /\* PHASE TIMELINE \*/ .phase { border-left: 3px solid #7fb3e0; padding: 10px 16px; margin: 10px 0; background: #f7f8fa; } .phase strong { color: #003366; } .phase .phase-dur { color: #1a5c8a; font-size: 9pt; } /\* DOC FOOTER (inside wrapper) \*/ .doc-footer { background: #f7f8fa; border-top: 1px solid #d0d4d8; padding: 16px 36px; font-size: 9pt; color: #555; } .doc-footer table { width: 100%; } .doc-footer .footer-right { text-align: right; color: #003366; font-weight: 600; } @media print { body { background: white; } .doc-wrapper { box-shadow: none; border: none; margin: 0; max-width: 100%; } h2, h3 { page-break-after: avoid; } table.data { page-break-inside: avoid; } .phase, .callout { page-break-inside: avoid; } }

![C16](data:image/png;base64,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)

Reference

# FS ZMM PR TO RFQ ARIBA

Topic

FS ZMM PR TO RFQ ARIBA

Date

23 October 2026

Audience

CIOs, SAP program leaders, transformation architects

Author

C16 — AI for SAP operational efficiency

Scope

Version

1.0

## 0 Document Control

Attribute

Value

Document

Functional Specification – Automatic Conversion of Purchase Requisitions to S/4HANA RFQs with Ariba Publishing

Proposed object ID

ZMM\_PR\_TO\_RFQ (new S/4HANA object, name to be confirmed against customer naming convention)

Module / Process

MM-PUR – Sourcing (Purchase Requisition → Request for Quotation → Ariba Sourcing)

Object type

Enhancement / Batch program (scheduled job and online run)

Target system

SAP S/4HANA (on-premise / private cloud) with live SAP Ariba Sourcing integration – release to be confirmed

Version

0.9 – Draft for customer review

Date

23-Oct-2026

Status

Draft – open items in Section 15

**Validation note:** The system available during analysis is SAP ECC 6.0 (SAP\_BASIS 740, client 800). It has been used only to confirm classic purchasing data structures (EBAN, EORD, T024) that are unchanged in S/4HANA. Every S/4HANA-specific object in this document (RFQ API, Ariba communication scenario, RFQ fields) is marked _“verify on target”_ and must be confirmed on the S/4HANA development system before build.

## 1 Business Requirement

Buyers currently create Requests for Quotation (RFQs) manually from purchase requisitions (PRs). The customer wants this step automated: qualifying PRs are converted into S/4HANA RFQs without manual entry, each RFQ invites three suppliers, and the RFQ is published to suppliers through SAP Ariba Sourcing, which is already live and integrated with S/4HANA.

### 1.1 Business benefits

*   No manual RFQ creation for routine sourcing; buyers focus on evaluating quotations.
*   Consistent RFQ data: same naming, deadline and header terms on every RFQ.
*   Faster PR-to-quotation cycle; RFQ goes to Ariba on the same day the PR qualifies.
*   Full audit trail from PR to RFQ to Ariba event in the application log.

## 2 Scope

### 2.1 In scope

*   Selection of open, released, non-deleted PR items that are not yet referenced on an RFQ or PO.
*   Determination of three suppliers per RFQ (PR supplier plus up to two from source list / info records).
*   Derivation of the purchasing organisation from the purchasing group.
*   Creation of the S/4HANA RFQ (new RFQ object, not the classic ME41 RFQ) using SAP's released RFQ interface.
*   Publishing the RFQ, which triggers the standard S/4HANA → Ariba Sourcing outbound integration.
*   Test (simulation) mode, result list, application log and rerun of failed items.
*   Documentation of all S/4HANA-side integration points (Section 9).

### 2.2 Out of scope

*   Configuration of SAP Ariba, the Ariba event template, or SAP Integration Suite (managed gateway) mappings – assumed live and working.
*   Supplier quotation entry, comparison and award (handled in Ariba and returned via standard integration).
*   Conversion of awarded quotations into purchase orders.
*   Custom output forms, email or EDI – Ariba is the only sending channel.
*   Reuse of the ECC objects ZRP\_PR\_TO\_RFQ / transaction Z\_PR\_RFQ (ECC stub without logic; not transferable).

## 3 Decisions Log (customer answers)

#

Topic

Decision

Source

D1

Supplier source

Supplier entered on the PR is the leading supplier

Customer answer

D2

Suppliers per RFQ

3 suppliers

Customer answer

D3

Remaining 2 suppliers

Option (a): PR supplier + 2 from source list / purchasing info records

Customer answer (Point 1 – a)

D4

RFQ object

New S/4HANA RFQ (Manage RFQs object)

Customer answer

D5

Quotation deadline

RFQ creation date + 30 calendar days

Customer answer

D6

RFQ name

“RFQ” + current timestamp (see FR-07 for uniqueness rule)

Customer answer

D7

Delivery date

Copied from the PR item

Customer answer

D8

Header texts and terms

Standard defaults (RFQ type, supplier master, purchasing org)

Customer answer

D9

Send automatically

Yes

Customer answer

D10

Sending channel

Published and sent through Ariba

Customer answer

D11

Ariba integration

Assumed live; S/4HANA-side integration points must be fully documented

Customer answer (Point 2)

D12

Purchasing organisation

Taken from the purchasing group

Customer answer (Point 3)

## 4 Process Overview

#mermaid-1792759476286{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1792759476286 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1792759476286 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1792759476286 .error-icon{fill:#552222;}#mermaid-1792759476286 .error-text{fill:#552222;stroke:#552222;}#mermaid-1792759476286 .edge-thickness-normal{stroke-width:1px;}#mermaid-1792759476286 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1792759476286 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1792759476286 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1792759476286 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1792759476286 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1792759476286 .marker{fill:#666;stroke:#666;}#mermaid-1792759476286 .marker.cross{stroke:#666;}#mermaid-1792759476286 svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-1792759476286 p{margin:0;}#mermaid-1792759476286 .label{font-family:"trebuchet ms",verdana,arial,sans-serif;color:#000000;}#mermaid-1792759476286 .cluster-label text{fill:#333;}#mermaid-1792759476286 .cluster-label span{color:#333;}#mermaid-1792759476286 .cluster-label span p{background-color:transparent;}#mermaid-1792759476286 .label text,#mermaid-1792759476286 span{fill:#000000;color:#000000;}#mermaid-1792759476286 .node rect,#mermaid-1792759476286 .node circle,#mermaid-1792759476286 .node ellipse,#mermaid-1792759476286 .node polygon,#mermaid-1792759476286 .node path{fill:#eee;stroke:#999;stroke-width:1px;}#mermaid-1792759476286 .rough-node .label text,#mermaid-1792759476286 .node .label text,#mermaid-1792759476286 .image-shape .label,#mermaid-1792759476286 .icon-shape .label{text-anchor:middle;}#mermaid-1792759476286 .node .katex path{fill:#000;stroke:#000;stroke-width:1px;}#mermaid-1792759476286 .rough-node .label,#mermaid-1792759476286 .node .label,#mermaid-1792759476286 .image-shape .label,#mermaid-1792759476286 .icon-shape .label{text-align:center;}#mermaid-1792759476286 .node.clickable{cursor:pointer;}#mermaid-1792759476286 .root .anchor path{fill:#666!important;stroke-width:0;stroke:#666;}#mermaid-1792759476286 .arrowheadPath{fill:#333333;}#mermaid-1792759476286 .edgePath .path{stroke:#666;stroke-width:2.0px;}#mermaid-1792759476286 .flowchart-link{stroke:#666;fill:none;}#mermaid-1792759476286 .edgeLabel{background-color:white;text-align:center;}#mermaid-1792759476286 .edgeLabel p{background-color:white;}#mermaid-1792759476286 .edgeLabel rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1792759476286 .labelBkg{background-color:rgba(255, 255, 255, 0.5);}#mermaid-1792759476286 .cluster rect{fill:hsl(0, 0%, 98.9215686275%);stroke:#707070;stroke-width:1px;}#mermaid-1792759476286 .cluster text{fill:#333;}#mermaid-1792759476286 .cluster span{color:#333;}#mermaid-1792759476286 div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:12px;background:hsl(-160, 0%, 93.3333333333%);border:1px solid #707070;border-radius:2px;pointer-events:none;z-index:100;}#mermaid-1792759476286 .flowchartTitleText{text-anchor:middle;font-size:18px;fill:#000000;}#mermaid-1792759476286 rect.text{fill:none;stroke-width:0;}#mermaid-1792759476286 .icon-shape,#mermaid-1792759476286 .image-shape{background-color:white;text-align:center;}#mermaid-1792759476286 .icon-shape p,#mermaid-1792759476286 .image-shape p{background-color:white;padding:2px;}#mermaid-1792759476286 .icon-shape .label rect,#mermaid-1792759476286 .image-shape .label rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1792759476286 .label-icon{display:inline-block;height:1em;overflow:visible;vertical-align:-0.125em;}#mermaid-1792759476286 .node .label-icon path{fill:currentColor;stroke:revert;stroke-width:revert;}#mermaid-1792759476286 :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}

Yes

No

No

Yes

No

Yes

Yes

No

Scheduled job / online run

Select open released PR items

Already on RFQ or PO?

Skip and log

Derive purchasing org from purchasing group

Org found?

Error log

Determine suppliers: PR supplier + source list + info records

At least 1 supplier?

Group items into RFQs

Test mode?

Show simulated result

Create S/4HANA RFQ via released API

Publish RFQ

Standard outbound to Ariba Sourcing

Ariba sourcing event created / suppliers invited

Quotations and award return via standard integration

Result list and application log

## 5 Functional Requirements

ID

Requirement

Priority

FR-01

The program runs as a scheduled background job (default daily) and online with a preview list.

Must

FR-02

Select only eligible PR items according to Section 6.

Must

FR-03

Derive the purchasing organisation from the PR item's purchasing group (Section 7).

Must

FR-04

Determine up to 3 suppliers per RFQ (Section 8).

Must

FR-05

Create one S/4HANA RFQ per grouping key (Section 8.3) with the PR item reference on each RFQ item.

Must

FR-06

Quotation deadline = system date of creation + 30 days (parameter, default 30).

Must

FR-07

RFQ name = “RFQ” + timestamp YYYYMMDDhhmmss. If more than one RFQ is created in a run, append a 3-digit running suffix (e.g. RFQ20261023143005-001) to keep names unique. The final format is subject to the RFQ name field length on target (verify on target).

Must

FR-08

Copy delivery date, material / short text, quantity, unit, plant, storage location, material group and account assignment from the PR item.

Must

FR-09

Header terms (payment terms, Incoterms, currency) and header texts are defaulted by standard; the program does not hard-code them.

Must

FR-10

After successful creation, publish the RFQ so the standard integration sends it to Ariba.

Must

FR-11

Test mode (default ON online) simulates all steps and shows the result without saving.

Must

FR-12

Write every PR item outcome to the application log and the result list.

Must

FR-13

Failed items are picked up again in the next run (no manual reset needed) as long as they are still eligible.

Should

FR-14

Optional email summary to the purchasing group mailbox at the end of a background run.

Could

## 6 Selection Screen and PR Eligibility

### 6.1 Selection screen

Field

Type

Reference field

Mandatory

Default

Purchasing group

Select-option

EBAN-EKGRP

Yes

–

Plant

Select-option

EBAN-WERKS

No

–

PR document type

Select-option

EBAN-BSART

No

–

Purchase requisition

Select-option

EBAN-BANFN

No

–

Material group

Select-option

EBAN-MATKL

No

–

PR creation date

Select-option

EBAN-BADAT

No

–

Quotation deadline (days)

Parameter

Integer

Yes

30

Number of suppliers

Parameter

Integer

Yes

3

Minimum suppliers to create RFQ

Parameter

Integer

Yes

1 (open item OI-02)

Publish to Ariba

Checkbox

–

No

X

Test mode

Checkbox

–

No

X (online)

All selection fields carry the DDIC type of their reference field; no field is typed or validated as a date unless it is a date field (BADAT).

### 6.2 Eligibility rules (all must be true)

Rule

Condition

Field(s)

E1

Item not deleted

EBAN-LOEKZ = blank

E2

Item not closed

EBAN-EBAKZ = blank

E3

Released, where a release strategy applies

EBAN-FRGKZ is a “released” indicator, or no release strategy (EBAN-FRGST blank)

E4

Not yet converted to a PO

EBAN-EBELN blank and ordered quantity EBAN-BSMNG < EBAN-MENGE

E5

Not yet referenced on an RFQ

No RFQ item references the PR item (S/4HANA RFQ follow-on document check – verify on target)

E6

No contract or fixed source already assigned

EBAN-KONNR blank (item can go straight to PO otherwise)

E7

Not processed by a running Ariba event

PR item not already sent to Ariba Sourcing as a PR (verify on target)

E8

Standard or service item category supported

EBAN-PSTYP in supported list (open item OI-05)

Reference only (ECC analysis system): about 7,233 open PR lines without a PO; 7,220 have a blank release indicator. Rule E3 therefore treats “no release strategy” as eligible. Volumes on S/4HANA must be reconfirmed.

## 7 Purchasing Organisation Derivation

Per decision D12, the purchasing organisation is taken from the purchasing group.

**Finding:** in SAP standard, a purchasing group (table T024) is **not** assigned to a purchasing organisation. T024 contains only EKGRP, EKNAM, telephone, fax, email and output device – no EKORG field (confirmed in DDIC). A direct “take org from purchasing group” therefore needs a maintained mapping.

### 7.1 Derivation logic

1.  **Primary:** read custom mapping table _ZMM\_EKGRP\_EKORG_ (purchasing group → purchasing organisation, plus optional company code) maintained through a maintenance view in customizing.
2.  **Consistency check:** the derived purchasing org must be assigned to the PR item's plant (standard org assignment, T024W). If not, the item is logged as an error.
3.  **Fallback (open item OI-03):** if no mapping exists, use EBAN-EKORG when filled on the PR; otherwise log error “No purchasing organisation for purchasing group &1”.

Field

Key

Description

MANDT

X

Client

EKGRP

X

Purchasing group

EKORG

Purchasing organisation

BUKRS

Company code (optional, for RFQ header)

## 8 Supplier Determination and Grouping

### 8.1 Supplier sequence (decision D3, option a)

Step

Source

Rule

1

PR fixed supplier

EBAN-FLIEF, if filled

2

PR desired supplier

EBAN-LIFNR, if filled and different from step 1

3

Source list

EORD for material + plant, valid on run date (VDATU ≤ today ≤ BDATU), not blocked (NOTKZ blank), purchasing org = derived org or blank; fixed source (FLIFN = X) first

4

Purchasing info records

Info records for material (or material group for text items) + derived purchasing org + plant, not flagged for deletion; most recently changed first

*   Stop once the configured number of suppliers (default 3) is reached; duplicates are removed.
*   Exclude suppliers that are blocked for purchasing (central or purchasing-org level) or have no Ariba supplier ID / are not enabled for Ariba sourcing (verify field on target).
*   If fewer than 3 are found but at least the minimum (default 1), the RFQ is created and a warning is logged (open item OI-02).
*   If no supplier is found, the item is not converted and is logged as an error.

### 8.2 Supplier on the PR is mandatory?

Decision D1 makes the PR supplier the lead supplier. Assumption: a PR item without a PR supplier is still processed using steps 3–4 only (open item OI-04).

### 8.3 Grouping of PR items into RFQs

Items are combined into one RFQ when **all** of the following are equal: purchase requisition number, derived purchasing organisation, purchasing group, plant, currency and the determined supplier set. Otherwise a separate RFQ is created. Reason: S/4HANA RFQ bidders are held at header level, so all items in one RFQ must go to the same suppliers (open item OI-01 – confirm meaning of customer answer “10 – Yes”).

## 9 S/4HANA Integration Points

This section documents every touchpoint on the S/4HANA side, from reading the PR to receiving results from Ariba. Ariba-side configuration is out of scope and assumed live (decision D11).

### 9.1 Integration landscape

SAP Ariba SourcingSAP Integration Suite (managed gateway)Outbound service / message monitorS/4HANA RFQ BOPurchase Requisition (EBAN)ZMM\_PR\_TO\_RFQ (S/4HANA)SAP Ariba SourcingSAP Integration Suite (managed gateway)Outbound service / message monitorS/4HANA RFQ BOPurchase Requisition (EBAN)ZMM\_PR\_TO\_RFQ (S/4HANA)#mermaid-1792759479059{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1792759479059 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1792759479059 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1792759479059 .error-icon{fill:#552222;}#mermaid-1792759479059 .error-text{fill:#552222;stroke:#552222;}#mermaid-1792759479059 .edge-thickness-normal{stroke-width:1px;}#mermaid-1792759479059 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1792759479059 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1792759479059 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1792759479059 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1792759479059 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1792759479059 .marker{fill:#666;stroke:#666;}#mermaid-1792759479059 .marker.cross{stroke:#666;}#mermaid-1792759479059 svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-1792759479059 p{margin:0;}#mermaid-1792759479059 .actor{stroke:hsl(0, 0%, 83%);fill:#eee;}#mermaid-1792759479059 text.actor>tspan{fill:#333;stroke:none;}#mermaid-1792759479059 .actor-line{stroke:hsl(0, 0%, 83%);}#mermaid-1792759479059 .innerArc{stroke-width:1.5;stroke-dasharray:none;}#mermaid-1792759479059 .messageLine0{stroke-width:1.5;stroke-dasharray:none;stroke:#333;}#mermaid-1792759479059 .messageLine1{stroke-width:1.5;stroke-dasharray:2,2;stroke:#333;}#mermaid-1792759479059 #arrowhead path{fill:#333;stroke:#333;}#mermaid-1792759479059 .sequenceNumber{fill:white;}#mermaid-1792759479059 #sequencenumber{fill:#333;}#mermaid-1792759479059 #crosshead path{fill:#333;stroke:#333;}#mermaid-1792759479059 .messageText{fill:#333;stroke:none;}#mermaid-1792759479059 .labelBox{stroke:hsl(0, 0%, 83%);fill:#eee;}#mermaid-1792759479059 .labelText,#mermaid-1792759479059 .labelText>tspan{fill:#333;stroke:none;}#mermaid-1792759479059 .loopText,#mermaid-1792759479059 .loopText>tspan{fill:#333;stroke:none;}#mermaid-1792759479059 .loopLine{stroke-width:2px;stroke-dasharray:2,2;stroke:hsl(0, 0%, 83%);fill:hsl(0, 0%, 83%);}#mermaid-1792759479059 .note{stroke:#999;fill:#666;}#mermaid-1792759479059 .noteText,#mermaid-1792759479059 .noteText>tspan{fill:#fff;stroke:none;}#mermaid-1792759479059 .activation0{fill:#f4f4f4;stroke:#666;}#mermaid-1792759479059 .activation1{fill:#f4f4f4;stroke:#666;}#mermaid-1792759479059 .activation2{fill:#f4f4f4;stroke:#666;}#mermaid-1792759479059 .actorPopupMenu{position:absolute;}#mermaid-1792759479059 .actorPopupMenuPanel{position:absolute;fill:#eee;box-shadow:0px 8px 16px 0px rgba(0,0,0,0.2);filter:drop-shadow(3px 5px 2px rgb(0 0 0 / 0.4));}#mermaid-1792759479059 .actor-man line{stroke:hsl(0, 0%, 83%);fill:#eee;}#mermaid-1792759479059 .actor-man circle,#mermaid-1792759479059 line{stroke:hsl(0, 0%, 83%);fill:#eee;stroke-width:2px;}#mermaid-1792759479059 :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}IP-01 Read eligible PR itemsIP-02 Create RFQ (released API)IP-03 Publish RFQIP-04 Outbound RFQ messageIP-05 SOAP / HTTPSSourcing event created, suppliers invitedSupplier quotations / awardIP-06 Inbound quotation / RFQ statusIP-07 Application log + monitoring

### 9.2 Integration point catalogue

ID

Integration point

Direction

S/4HANA object (verify on target)

Trigger

Key data

Error handling / monitoring

IP-01

Read purchase requisition items

Internal read

EBAN (or released CDS view for purchase requisition items)

Program run

PR, item, material, quantity, delivery date, plant, purchasing group, PR supplier

Application log

IP-02

Create RFQ

Internal API

SAP released RFQ interface – candidates: RFQ RAP business object interface (EML) or OData API “Request for Quotation” (API\_RFQ\_PROCESS\_SRV). Selection depends on S/4HANA release and Released Objects list.

Per grouping key

Header: RFQ type, name, purchasing org, purchasing group, company code, quotation deadline, bidders. Item: PR reference, material, quantity, delivery date, plant

API return messages → application log; rollback of that RFQ only

IP-03

Publish RFQ

Internal API

Standard “Publish” action of the RFQ business object (same as Manage RFQs app)

After successful create (if “Publish to Ariba” is set)

RFQ number

If publish fails the RFQ stays in “Not Published” status; logged and re-attempted in the next run

IP-04

Outbound RFQ message to Ariba

S/4HANA → Ariba

Standard outbound service for RFQ to Ariba Sourcing, triggered by publish via output management / integration scenario (communication scenario for SAP Ariba Sourcing integration)

Publish

Full RFQ incl. bidders and items

Message Monitoring (SRT\_MONI / Message Dashboard / AIF where configured)

IP-05

Transport to Ariba

S/4HANA → SAP Integration Suite → Ariba

Communication arrangement / logical port (SOAMANAGER), Ariba realm and certificates

Asynchronous

SOAP over HTTPS

Integration Suite monitoring; S/4HANA message restart

IP-06

Inbound quotations / award

Ariba → S/4HANA

Standard inbound service creating supplier quotations against the RFQ and updating RFQ status

Ariba award / event close

Supplier quotation, prices, award flag

Message Monitoring; not changed by this development

IP-07

Logging and monitoring

Internal

Application log object ZMM / sub-object PR\_RFQ (SLG1); job log

Every run

PR, item, RFQ, suppliers, status, message

Buyer / key-user review

### 9.3 Prerequisites on S/4HANA (confirm live)

*   Communication arrangement / logical ports for SAP Ariba Sourcing integration active in the target client.
*   RFQ document type used for Ariba-relevant RFQs configured and flagged for external sourcing (verify setting name on target).
*   Suppliers in scope replicated / enabled in Ariba (Ariba supplier ID maintained).
*   Output / integration determination for RFQ publish set up for channel Ariba.
*   Integration user and roles for the background job user (Section 12).

## 10 RFQ Field Mapping

RFQ field (S/4HANA)

Source

Rule

RFQ type

Constant / parameter

Ariba-relevant RFQ type (open item OI-06)

RFQ name

System

“RFQ” + YYYYMMDDhhmmss \[+ “-nnn”\] (FR-07)

Purchasing organisation

ZMM\_EKGRP\_EKORG

Section 7

Purchasing group

EBAN-EKGRP

Copy

Company code

Mapping table / plant assignment

Derived

Quotation deadline

System date

Today + 30 days

Bidders

Section 8

Up to 3 suppliers

Header texts, payment terms, Incoterms, currency

Standard defaults

Not set by program

Item – PR reference

EBAN-BANFN / BNFPO

Copy (creates document flow)

Item – material / short text

EBAN-MATNR / TXZ01

Copy

Item – material group

EBAN-MATKL

Copy

Item – quantity / unit

EBAN-MENGE − BSMNG / MEINS

Open quantity

Item – delivery date

EBAN-LFDAT

Copy (D7)

Item – plant / storage location

EBAN-WERKS / LGORT

Copy

Item – account assignment

EBAN-KNTTP + EBKN

Copy where supported by the RFQ API

Rule: if the PR delivery date is earlier than the quotation deadline, the RFQ is still created and a warning is logged (open item OI-07).

## 11 Output, Logging and Error Handling

### 11.1 Result list (online and spool)

Columns: PR, PR item, material, short text, plant, purchasing group, purchasing org, suppliers 1–3, RFQ number, RFQ name, published (Y/N), status icon, message. Column headers come from the DDIC field labels.

### 11.2 Error scenarios

Scenario

Result

Message type

No purchasing org for purchasing group

Item skipped

Error

Purchasing org not assigned to plant

Item skipped

Error

No supplier found

Item skipped

Error

Fewer suppliers than requested

RFQ created

Warning

RFQ API returns error

That RFQ rolled back; other RFQs continue

Error

Publish fails

RFQ kept unpublished; retried next run

Warning

PR item locked by another user

Item skipped; retried next run

Warning

No authorization

Item skipped

Error

No eligible PR items

Run ends normally

Information

All messages are held in a dedicated message class; no hard-coded texts.

## 12 Authorizations

*   Program start: transaction code / report authorization group.
*   Read PR: M\_BANF\_EKG (purchasing group), M\_BANF\_WRK (plant).
*   Create and publish RFQ: RFQ authorization by document type, purchasing org and purchasing group (M\_ANFR\_BSA, M\_ANFR\_EKO, M\_ANFR\_EKG, M\_ANFR\_WRK) – verify the S/4HANA RFQ authorization objects on target.
*   Background job user: technical user with the above plus the business role for RFQ processing; no SAP\_ALL.

## 13 Non-Functional Requirements

Area

Requirement

Scheduling

Daily background job (time to be agreed), plus ad-hoc online run

Volume

Must handle a first run of several thousand PR items; commit per RFQ, package processing of 500 items

Performance

< 30 minutes for 5,000 PR items excluding Ariba transfer time

Restartability

Re-running the job never creates duplicate RFQs (rule E5)

Code Quality

Released S/4HANA RFQ API only – no batch input, no direct table updates, no modifications

Parallel runs

Job locks itself per purchasing group to prevent two runs on the same PRs

## 14 Test Scenarios

#

Scenario

Expected result

T01

PR item with PR supplier, source list with 2 other suppliers

1 RFQ, 3 bidders, published to Ariba

T02

PR supplier only, no source list, 2 info records

1 RFQ, 3 bidders

T03

Only 1 supplier found

RFQ with 1 bidder, warning logged

T04

No supplier found

No RFQ, error logged

T05

Purchasing group without org mapping

No RFQ, error logged

T06

PR with 3 items, same supplier set

1 RFQ with 3 items

T07

PR with 2 items, different supplier sets

2 RFQs

T08

Two RFQs created in the same second

Unique names with -001 / -002

T09

Rerun after success

No duplicate RFQ

T10

Test mode

Simulated list, nothing saved

T11

PR deleted / not released / already on PO

Not selected

T12

Delivery date before deadline

RFQ created, warning

T13

Publish fails (integration down)

RFQ unpublished, retried next run

T14

End-to-end

Ariba event visible, quotations returned to S/4HANA RFQ

T15

User without RFQ authorization

Items rejected with authorization error

## 15 Open Items

ID

Open item

Assumption used in this FS

Owner

OI-01

Meaning of answer “10 – Yes” (combine items vs. collective number)

Combine items of the same PR with identical org data and supplier set

Customer

OI-02

Fewer than 3 suppliers found

Create RFQ if ≥ 1 supplier, warning

Customer

OI-03

Purchasing group → org mapping (not standard)

New table ZMM\_EKGRP\_EKORG; fallback to PR purchasing org

Customer / Functional

OI-04

PR items without a PR supplier

Process with source list / info records only

Customer

OI-05

Supported item categories (standard, service, limit)

Standard items only in phase 1

Customer

OI-06

RFQ document type for Ariba

One fixed Ariba-relevant type, as parameter

Functional

OI-07

Delivery date earlier than quotation deadline

Create RFQ, warning

Customer

OI-08

S/4HANA release and target system access

All S/4HANA objects marked “verify on target”

Basis

OI-09

Fit-to-standard: PR direct to Ariba Sourcing (no RFQ in S/4HANA)

Custom build approved by customer

Customer / Architect

## 16 Approvals

Role

Name

Date

Signature

Business owner (Procurement)

Functional consultant MM

Integration / Ariba lead

Technical lead

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