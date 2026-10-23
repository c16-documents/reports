  FS ZMM PR TO RFQ S4 Ariba @page { size: A4; margin: 20mm 18mm 20mm 18mm; } \* { box-sizing: border-box; margin: 0; padding: 0; } body { font-family: 'Segoe UI', Calibri, Arial, sans-serif; font-size: 10.5pt; line-height: 1.55; color: #1a1a1a; background: #f4f5f6; -webkit-print-color-adjust: exact; print-color-adjust: exact; } .doc-wrapper { max-width: 1100px; margin: 24px auto; background: #ffffff; box-shadow: 0 1px 8px rgba(0,0,0,0.08); border: 1px solid #d0d4d8; } /\* HEADER \*/ .doc-header { background: #003366; color: #ffffff; padding: 28px 36px 24px 36px; border-bottom: 4px solid #7fb3e0; } .doc-header-top { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 14px; } .doc-logo img { height: 40px; display: block; } .doc-classification { font-size: 8.5pt; letter-spacing: 1.2px; text-transform: uppercase; color: #7fb3e0; border: 1px solid #7fb3e0; padding: 3px 12px; border-radius: 2px; white-space: nowrap; } .doc-header h1 { font-size: 22pt; font-weight: 600; letter-spacing: -0.3px; margin: 0 0 4px 0; line-height: 1.2; } .doc-header .doc-subtitle { font-size: 11pt; color: #7fb3e0; font-weight: 400; } /\* META \*/ .doc-meta { padding: 16px 36px; background: #f7f8fa; border-bottom: 1px solid #d0d4d8; font-size: 9.5pt; color: #444; } .doc-meta table { width: 100%; border-collapse: collapse; } .doc-meta td { padding: 3px 12px 3px 0; vertical-align: top; } .doc-meta .meta-label { font-weight: 600; color: #003366; width: 90px; } /\* BODY \*/ .doc-body { padding: 28px 36px 36px 36px; background: #ffffff; } .doc-body p { margin: 8px 0; } .doc-body h2 { font-size: 14pt; color: #003366; margin: 24px 0 12px 0; padding-bottom: 6px; border-bottom: 2px solid #7fb3e0; display: flex; align-items: center; gap: 10px; } .doc-body h2 .sec-num { display: inline-block; background: #003366; color: white; font-size: 11pt; font-weight: 700; padding: 2px 9px; border-radius: 3px; line-height: 1; min-width: 26px; text-align: center; } .doc-body h3 { font-size: 11.5pt; color: #003366; margin: 18px 0 8px 0; font-weight: 600; } .doc-body h4 { font-size: 10.5pt; color: #1a5c8a; margin: 12px 0 6px 0; font-weight: 600; } .doc-body ul, .doc-body ol { margin: 8px 0 8px 22px; } .doc-body li { margin: 4px 0; } /\* TABLES \*/ table.data { width: 100%; border-collapse: collapse; margin: 10px 0 14px 0; font-size: 9.5pt; } table.data th, table.data td { border: 1px solid #d0d4d8; padding: 7px 10px; text-align: left; vertical-align: top; } table.data th { background: #003366; color: white; font-weight: 600; letter-spacing: 0.2px; } table.data tr:nth-child(even) td { background: #f7f8fa; } table.data td.center { text-align: center; } /\* CALLOUTS \*/ .callout { background: #f0f6fa; border-left: 4px solid #1a5c8a; padding: 12px 16px; margin: 14px 0; font-size: 10pt; color: #1f2937; } .callout.tip { border-left-color: #15803D; background: #f0fdf4; } .callout.warning { border-left-color: #C2410C; background: #fff7ed; } /\* PILLS — Clean Core levels \*/ .pill { display: inline-block; font-size: 8.5pt; font-weight: 600; padding: 2px 9px; border-radius: 10px; letter-spacing: 0.3px; white-space: nowrap; } .pill-a { background: #dcfce7; color: #15803D; } .pill-b { background: #dbeafe; color: #1D4ED8; } .pill-c { background: #fef3c7; color: #A16207; } .pill-d { background: #fee2e2; color: #B91C1C; } /\* SYSTEM PILLS — engagement context strip under the header \*/ .doc-pills { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 14px; } .doc-pills .doc-pill { display: inline-flex; align-items: center; gap: 6px; font-size: 8.5pt; font-weight: 500; padding: 4px 12px; border-radius: 16px; background: rgba(255, 255, 255, 0.12); border: 1px solid rgba(255, 255, 255, 0.28); color: #ffffff; letter-spacing: 0.2px; white-space: nowrap; } .doc-pills .doc-pill .doc-pill-icon { font-size: 9pt; opacity: 0.9; } .doc-pills .doc-pill.danger { background: rgba(254, 226, 226, 0.18); border-color: rgba(254, 226, 226, 0.35); } .doc-pills .doc-pill.warn { background: rgba(254, 243, 199, 0.15); border-color: rgba(254, 243, 199, 0.35); } /\* KPI STRIP — volume counters under the pills \*/ .doc-kpi-strip { display: flex; flex-wrap: wrap; gap: 18px; margin-top: 14px; padding-top: 12px; border-top: 1px solid rgba(255, 255, 255, 0.18); font-size: 9pt; color: rgba(255, 255, 255, 0.92); } .doc-kpi-strip .doc-kpi { display: inline-flex; align-items: center; gap: 5px; white-space: nowrap; } .doc-kpi-strip .doc-kpi-icon { font-size: 10.5pt; } .doc-kpi-strip .doc-kpi-value { font-weight: 700; color: #ffffff; } .doc-kpi-strip .doc-kpi-label { color: rgba(255, 255, 255, 0.78); } /\* PHASE TIMELINE \*/ .phase { border-left: 3px solid #7fb3e0; padding: 10px 16px; margin: 10px 0; background: #f7f8fa; } .phase strong { color: #003366; } .phase .phase-dur { color: #1a5c8a; font-size: 9pt; } /\* DOC FOOTER (inside wrapper) \*/ .doc-footer { background: #f7f8fa; border-top: 1px solid #d0d4d8; padding: 16px 36px; font-size: 9pt; color: #555; } .doc-footer table { width: 100%; } .doc-footer .footer-right { text-align: right; color: #003366; font-weight: 600; } @media print { body { background: white; } .doc-wrapper { box-shadow: none; border: none; margin: 0; max-width: 100%; } h2, h3 { page-break-after: avoid; } table.data { page-break-inside: avoid; } .phase, .callout { page-break-inside: avoid; } }

![C16](data:image/png;base64,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)

Reference

# FS ZMM PR TO RFQ S4 Ariba

Topic

FS ZMM PR TO RFQ S4 Ariba

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

Functional Specification – Automatic conversion of Purchase Requisitions to S/4HANA RFQs published to SAP Ariba Sourcing

WRICEF type

Report / Background job (E – Enhancement, Interface-relevant)

Proposed object name

ZMM\_PR\_TO\_RFQ\_S4 (to be confirmed – naming follows MM module convention)

Target platform

SAP S/4HANA (new Sourcing RFQ), integrated with SAP Ariba Sourcing (integration assumed live)

Version / Status

0.1 – Draft for customer review

Date

2026-10-23

Related documents

Technical Specification (to follow once the S/4HANA release is confirmed)

## 2 Business Requirement

Buyers currently create every Request for Quotation (RFQ) manually from purchase requisitions (PRs). The customer wants released PRs to be converted into RFQs automatically. Each RFQ is to be invited to up to three suppliers, published straight away, and sent to SAP Ariba Sourcing, where suppliers submit their quotations.

### 2.1 In scope

*   A scheduled background job that selects qualifying PR items in S/4HANA.
*   Deriving the purchasing organisation from the PR's purchasing group.
*   Determining up to 3 bidders, starting with the supplier entered on the PR.
*   Creating the S/4HANA RFQ with header, item, schedule-line and bidder data.
*   Publishing the RFQ, which triggers the standard outbound transfer to SAP Ariba Sourcing.
*   Processing log, test-run mode, reprocessing of failed items, and exclusion of PRs that already have an RFQ.

### 2.2 Out of scope

*   Configuring the S/4HANA ⇄ Ariba integration. It is assumed live and is documented here only as integration points.
*   Quotation comparison, award, and creating the PO or contract from the awarded quotation (standard S/4HANA / Ariba process).
*   Service PR items (item category D / lean services) in phase 1. See open item OI-05.
*   Decommissioning the existing ECC programs (ZHZL\_PR\_TO\_RFQ, ZBDC\_RFQ\_CREATE, ZBDC\_RFQ\_CREATE1, ZMM\_PR\_TO\_RFQ\_PO\*). This is noted for the migration plan only.

## 3 Customer Decisions Captured

#

Topic

Customer decision

Design consequence

D-01

Target object

New S/4HANA RFQ (Sourcing)

Built on the released S/4HANA RFQ API / business object. No BDC, no ME41, no internal function modules.

D-02

Supplier source

Supplier entered on the PR

The PR supplier is always bidder 1.

D-03

Number of suppliers

3 suppliers

Up to 3 bidders per RFQ (see §6.5 for how bidders 2 and 3 are found).

D-04

Quotation deadline

30 days from creation

Quotation deadline = RFQ creation date + 30 calendar days (parameter, default 30).

D-05

RFQ name

RFQ<today's timestamp>

RFQ name = `RFQ` + `YYYYMMDDhhmmss` (system time of creation).

D-06

Delivery date

Copy from PR

RFQ item delivery date = PR item delivery date.

D-07

Texts and terms

Standard header texts and terms

Taken from the standard RFQ text/terms defaults of the purchasing organisation (see §6.6).

D-08

Exclude already-converted PRs

Yes

A PR item that is referenced by an active RFQ item is not selected again.

D-09

Log / test run

Yes

ALV log per PR item, plus a simulation mode.

D-10

Output channel

Published and sent through Ariba

RFQ is published by the program. Transfer to Ariba Sourcing uses the standard integration. No print or e-mail output.

D-11

Trigger

Option (a) – scheduled background job

Executable report, scheduled periodically via SM36/Application Jobs. Can also be run online.

D-12

Ariba integration

Assume it is live

The FS documents every S/4HANA-side integration point (§8).

D-13

Purchasing organisation

Take from the purchasing group

Derived via a new custom mapping table (§6.4). This is needed because standard SAP has no purchasing group → purchasing organisation link.

**Why D-13 needs a custom table:** In SAP the purchasing group (table T024) has no purchasing organisation field. I checked: T024 has only EKGRP, EKNAM, EKTEL, LDEST, TELFX, TEL\_NUMBER, TEL\_EXTENS, SMTP\_ADDR. Purchasing groups are client-wide. Deriving the organisation from the plant is not a reliable alternative either. In the current system, plant 1000 is assigned to 5 purchasing organisations (0001, 1, 1000, 1710, C100) in T024W. So "org from purchasing group" can only be deterministic through a maintained mapping table.

## 4 Assumptions (to be confirmed by the customer)

#

Assumption

Impact if wrong

A-01

Target is SAP S/4HANA on-premise or RISE Private Cloud, release 2021 or higher, with the Sourcing RFQ (Manage RFQs) active.

API, field names and publish step change. The TS cannot be finalised.

A-02

Only PR items with completed release are selected. Classic release strategy: final release reached. Flexible workflow: processing status "Released".

Unreleased PRs would reach suppliers.

A-03

Both fixed supplier and desired supplier count as "supplier entered on the PR". Fixed supplier takes priority.

Most supplier-bearing PR lines carry a fixed supplier. In the current ECC data, 3,977 of the 7,704 open lines have a fixed supplier and 123 have a desired supplier. Excluding them would leave very few RFQs.

A-04

Bidders 2 and 3 come from the valid source list for material + plant, then from purchasing info records for material + purchasing organisation. Blocked suppliers are excluded.

If the customer has a custom PR field or table holding 3 suppliers, §6.5 changes.

A-05

If fewer than 3 bidders are found, the RFQ is still created with the available bidders (minimum 1) and a warning is logged.

Alternative: do not create, log an error.

A-06

Grouping: one RFQ per PR, split further by derived purchasing organisation and bidder set. Bidders are held at RFQ header level in S/4HANA.

Combining several PRs into one RFQ would change the grouping key.

A-07

PR items without a supplier are not processed. They are logged as "no supplier on PR".

Alternative: create the RFQ with source-list bidders only.

A-08

RFQ document type = the standard S/4HANA RFQ type configured for Sourcing. Held in the custom mapping table so it can vary by purchasing organisation.

Configuration only.

A-09

The RFQ name is exactly `RFQ`+timestamp. RFQs created in the same second share a name. The RFQ number remains the unique key.

If a unique name is needed, a suffix (e.g. PR number) is appended – see OI-04.

## 5 Process Flow

#mermaid-1792759885384{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1792759885384 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1792759885384 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1792759885384 .error-icon{fill:#552222;}#mermaid-1792759885384 .error-text{fill:#552222;stroke:#552222;}#mermaid-1792759885384 .edge-thickness-normal{stroke-width:1px;}#mermaid-1792759885384 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1792759885384 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1792759885384 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1792759885384 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1792759885384 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1792759885384 .marker{fill:#666;stroke:#666;}#mermaid-1792759885384 .marker.cross{stroke:#666;}#mermaid-1792759885384 svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-1792759885384 p{margin:0;}#mermaid-1792759885384 .label{font-family:"trebuchet ms",verdana,arial,sans-serif;color:#000000;}#mermaid-1792759885384 .cluster-label text{fill:#333;}#mermaid-1792759885384 .cluster-label span{color:#333;}#mermaid-1792759885384 .cluster-label span p{background-color:transparent;}#mermaid-1792759885384 .label text,#mermaid-1792759885384 span{fill:#000000;color:#000000;}#mermaid-1792759885384 .node rect,#mermaid-1792759885384 .node circle,#mermaid-1792759885384 .node ellipse,#mermaid-1792759885384 .node polygon,#mermaid-1792759885384 .node path{fill:#eee;stroke:#999;stroke-width:1px;}#mermaid-1792759885384 .rough-node .label text,#mermaid-1792759885384 .node .label text,#mermaid-1792759885384 .image-shape .label,#mermaid-1792759885384 .icon-shape .label{text-anchor:middle;}#mermaid-1792759885384 .node .katex path{fill:#000;stroke:#000;stroke-width:1px;}#mermaid-1792759885384 .rough-node .label,#mermaid-1792759885384 .node .label,#mermaid-1792759885384 .image-shape .label,#mermaid-1792759885384 .icon-shape .label{text-align:center;}#mermaid-1792759885384 .node.clickable{cursor:pointer;}#mermaid-1792759885384 .root .anchor path{fill:#666!important;stroke-width:0;stroke:#666;}#mermaid-1792759885384 .arrowheadPath{fill:#333333;}#mermaid-1792759885384 .edgePath .path{stroke:#666;stroke-width:2.0px;}#mermaid-1792759885384 .flowchart-link{stroke:#666;fill:none;}#mermaid-1792759885384 .edgeLabel{background-color:white;text-align:center;}#mermaid-1792759885384 .edgeLabel p{background-color:white;}#mermaid-1792759885384 .edgeLabel rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1792759885384 .labelBkg{background-color:rgba(255, 255, 255, 0.5);}#mermaid-1792759885384 .cluster rect{fill:hsl(0, 0%, 98.9215686275%);stroke:#707070;stroke-width:1px;}#mermaid-1792759885384 .cluster text{fill:#333;}#mermaid-1792759885384 .cluster span{color:#333;}#mermaid-1792759885384 div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:12px;background:hsl(-160, 0%, 93.3333333333%);border:1px solid #707070;border-radius:2px;pointer-events:none;z-index:100;}#mermaid-1792759885384 .flowchartTitleText{text-anchor:middle;font-size:18px;fill:#000000;}#mermaid-1792759885384 rect.text{fill:none;stroke-width:0;}#mermaid-1792759885384 .icon-shape,#mermaid-1792759885384 .image-shape{background-color:white;text-align:center;}#mermaid-1792759885384 .icon-shape p,#mermaid-1792759885384 .image-shape p{background-color:white;padding:2px;}#mermaid-1792759885384 .icon-shape .label rect,#mermaid-1792759885384 .image-shape .label rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1792759885384 .label-icon{display:inline-block;height:1em;overflow:visible;vertical-align:-0.125em;}#mermaid-1792759885384 .node .label-icon path{fill:currentColor;stroke:revert;stroke-width:revert;}#mermaid-1792759885384 :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}

Yes

No

No

Yes

Not found

Yes

No

Error

Error

Background job ZMM\_PR\_TO\_RFQ\_S4 starts

Select released, open PR items

Already in an active RFQ?

Skip - log Info

Supplier on PR?

Skip - log Warning

Derive Purchasing Org from Purchasing Group - ZMM\_EKGRP\_EKORG

Error - log

Determine bidders: PR supplier + source list + info records, max 3

Group items into RFQs: PR + Purch Org + Bidder set

Test run?

Simulate - log planned RFQs

Create RFQ via released RFQ API

Rollback - log Error

Publish RFQ

RFQ kept as Draft - log Error - reprocessable

Standard outbound to SAP Ariba Sourcing

Ariba Sourcing event - suppliers quote

Supplier quotations returned to S/4HANA

ALV / spool log

## 6 Functional Design

### 6.1 Trigger and scheduling

*   Executable report, run as a periodic background job (recommended: hourly during business hours, frequency to be confirmed). It can also be started online by a buyer with the same selection screen.
*   Saved selection variants per purchasing organisation or region are recommended, e.g. `ZRFQ_EU`, `ZRFQ_US`.
*   Two parallel runs on the same PRs must be prevented. The program locks each PR before processing and skips locked PRs with a log entry.

### 6.2 Selection screen

Type

Technical name

Reference (DDIC)

Mandatory

Default

Purpose

Select-option

S\_BANFN

EBAN-BANFN

No

–

Purchase requisition number

Select-option

S\_BSART

EBAN-BSART

No

–

PR document type

Select-option

S\_EKGRP

EBAN-EKGRP

No

–

Purchasing group (also drives purchasing organisation)

Select-option

S\_WERKS

EBAN-WERKS

No

–

Plant

Select-option

S\_MATKL

EBAN-MATKL

No

–

Material group

Select-option

S\_BADAT

EBAN-BADAT

No

–

PR request date

Select-option

S\_FRGDT

EBAN-FRGDT

No

–

PR release date (lets jobs pick up recently released PRs only)

Parameter

P\_DAYS

Integer (days)

Yes

30

Quotation deadline offset in days from creation (D-04)

Parameter

P\_MAXBID

Integer

Yes

3

Maximum number of bidders per RFQ (D-03). Allowed range 1–3.

Checkbox

P\_PUBL

Flag

No

X

Publish the RFQ right after creation (D-10). If unflagged, the RFQ stays in Draft.

Checkbox

P\_TEST

Flag

No

X

Test run – simulate only, nothing is created (D-09)

Checkbox

P\_REPROC

Flag

No

–

Reprocess mode – only re-publish RFQs created by this program that are still in Draft after a failed publish

### 6.3 Validation of selection criteria

*   P\_DAYS must be greater than 0 and at most 365. Otherwise an error message is shown.
*   P\_MAXBID must be between 1 and 3. Otherwise an error message is shown.
*   Online run: at least one of S\_BANFN, S\_EKGRP, S\_WERKS or S\_FRGDT must be filled, so a full scan of all PRs is not triggered by accident. In background with a variant this check is a warning only.
*   Authorisation check on the entered purchasing groups and plants (see §10). Values without authorisation are removed and logged.

### 6.4 Purchasing organisation derivation (D-13)

A new customer configuration table, **ZMM\_EKGRP\_EKORG** (maintenance view via SM30), maps the purchasing group to the purchasing organisation and RFQ defaults:

Field

Key

Reference

Description

MANDT

X

MANDT

Client

EKGRP

X

EKGRP

Purchasing group

WERKS

X

WERKS\_D

Plant – optional, blank = all plants. Supports a group that buys for several organisations by plant.

EKORG

EKORG

Purchasing organisation used on the RFQ

RFQ\_TYPE

RFQ document type

RFQ document type to create (A-08)

ACTIVE

Flag

Purchasing group active for automatic RFQ creation

**Derivation rule (deterministic):**

1.  Read ZMM\_EKGRP\_EKORG with PR purchasing group + PR plant.
2.  If no entry is found, read with PR purchasing group + blank plant.
3.  If still not found, or ACTIVE is not set: **error** "No purchasing organisation maintained for purchasing group &1". The PR item is not processed. No fallback to the PR's own purchasing organisation, so the result is always the same.
4.  Consistency check: the derived purchasing organisation must be assigned to the PR plant in standard configuration (plant ↔ purchasing org assignment). Otherwise an error is logged.
5.  Company code = company code of the purchasing organisation. If the organisation is cross-company, the company code of the plant is used.

### 6.5 Bidder determination (D-02, D-03)

1.  **Bidder 1** = fixed supplier of the PR item. If blank, the desired supplier of the PR item (A-03).
2.  **Bidders 2..P\_MAXBID** are filled in this order, skipping duplicates:
    1.  valid source list entries for material + plant on the RFQ creation date, not blocked
    2.  purchasing info records for material + derived purchasing organisation, not flagged for deletion
3.  Exclusions: suppliers with a central or purchasing-org posting/purchasing block, or a deletion flag. Suppliers not enabled for Ariba Sourcing (no Ariba Network ID mapping – see §8, IP-06) are also excluded, with a warning.
4.  If the final number of bidders is below P\_MAXBID, the RFQ is created and a warning is logged (A-05).
5.  Items without material (free-text items) get only the PR supplier as bidder.

### 6.6 RFQ header mapping

RFQ header field

Source / rule

RFQ type

ZMM\_EKGRP\_EKORG-RFQ\_TYPE

RFQ name

`RFQ` + system date/time at creation, format YYYYMMDDhhmmss (D-05)

Purchasing organisation

Derived (§6.4)

Purchasing group

PR item purchasing group

Company code

Derived (§6.4)

Quotation deadline

Creation date + P\_DAYS (default 30), time 23:59:59 in the user's time zone (D-04)

Bidders

§6.5

Document currency

Purchasing organisation / company code currency

Header texts

Standard RFQ header text defaults (D-07) – text types and default texts as configured for RFQ in S/4HANA

Terms (payment terms, Incoterms)

Standard defaults of the purchasing organisation / RFQ type. Not copied from a single supplier, because the RFQ has several bidders (D-07).

### 6.7 RFQ item mapping

RFQ item field

Source (PR item)

PR reference (number + item)

EBAN-BANFN / EBAN-BNFPO – mandatory, used for document flow and the D-08 exclusion

Material / short text

EBAN-MATNR / EBAN-TXZ01

Material group

EBAN-MATKL

Plant / storage location

EBAN-WERKS / EBAN-LGORT

Quantity / unit

Open quantity = EBAN-MENGE − EBAN-BSMNG; unit EBAN-MEINS

Delivery date

EBAN-LFDAT (D-06)

Account assignment category

EBAN-KNTTP (account assignment data copied from the PR)

Item texts

PR item texts copied

### 6.8 PR selection criteria

*   Item not deleted (EBAN-LOEKZ blank) and not closed (EBAN-EBAKZ blank).
*   Release completed (A-02).
*   Open quantity > 0 (EBAN-MENGE − EBAN-BSMNG).
*   Item category: standard / non-service items only in phase 1 (OI-05).
*   Not already referenced by an RFQ item that is active (not deleted, not completed/cancelled) – D-08.
*   Supplier present on the PR (A-07).
*   Purchasing group active in ZMM\_EKGRP\_EKORG.

### 6.9 Create and publish

1.  For each RFQ group: create the RFQ via the released S/4HANA RFQ API (business object / OData API – exact interface fixed in the TS for the target release). Commit per RFQ; rollback on error so partial RFQs are not left behind.
2.  If P\_PUBL = X: execute the _Publish_ operation on the created RFQ. If publishing fails, the RFQ stays in Draft, an error is logged with the RFQ number, and the RFQ can be re-published with P\_REPROC.
3.  Publishing triggers the standard outbound message to SAP Ariba Sourcing (§8). The program does not call Ariba directly.

### 6.10 Output / log

ALV list online, spool list in background. One row per PR item:

Column

Content

Status

Traffic light: green = created & published, yellow = created (Draft) / warning, red = error, grey = skipped / simulated

PR / item

Purchase requisition and item

Purchasing group / derived purchasing org

Input and derived value

RFQ number / RFQ name

Created RFQ

Bidder 1–3

Supplier numbers

Quotation deadline

Calculated deadline

Publish status

Published / Draft / Not attempted

Message

Message text from validation or API

Totals line: PR items read, skipped, RFQs created, RFQs published, errors. Log entries are also written to the application log (SLG1, object/sub-object to be defined in the TS) for job monitoring.

## 7 Error Handling and Messages

#

Type

Message

Behaviour

001

E

Quotation deadline days must be between 1 and 365

Selection screen stops

002

E

Number of bidders must be between 1 and 3

Selection screen stops

003

E

Enter at least one restriction (PR, purchasing group, plant or release date)

Online only

004

I

PR &1 item &2 already in RFQ &3 – skipped

Item skipped

005

W

PR &1 item &2 has no supplier – skipped

Item skipped

006

E

No purchasing organisation maintained for purchasing group &1

Item not processed

007

E

Purchasing org &1 not assigned to plant &2

Item not processed

008

W

Only &1 of &2 bidders found for PR &3 item &4

RFQ created

009

W

Supplier &1 blocked or not Ariba-enabled – not invited

Bidder skipped

010

E

RFQ creation failed: &1

Rollback, group logged

011

E

RFQ &1 created but publish failed: &2

RFQ stays in Draft, reprocessable

012

S

RFQ &1 created and published

–

013

W

PR &1 locked by another user/job – skipped

Picked up next run

Message texts are held in a message class (T100). Name defined in the TS.

## 8 Integration Points – S/4HANA Side (SAP Ariba Sourcing)

The integration is assumed live (D-12). The program only creates and publishes the RFQ; the standard integration handles the transfer. The S/4HANA-side points below must be in place and are the hand-over items for the integration team. Service and object names are to be confirmed against the target release in the TS.

ID

Integration point

Direction

S/4HANA object / setting

What this program relies on

Monitoring

IP-01

RFQ outbound to Ariba Sourcing

S/4 → Ariba

Standard RFQ outbound message triggered on publish (Ariba Sourcing integration scope)

Publish of a program-created RFQ triggers the outbound message exactly as a manually published RFQ does

Message monitoring (SRT\_MONI / AIF) and the RFQ's processing status

IP-02

Connectivity

S/4 → Integration middleware → Ariba

SOAMANAGER logical port / communication arrangement towards SAP Integration Suite (Ariba integration content) or the Cloud Integration Gateway

Endpoint active in every system of the landscape (Q and P)

SOAMANAGER / communication arrangement status

IP-03

Sourcing configuration

S/4

Customising that RFQs of the configured RFQ type are processed externally in Ariba Sourcing

RFQ\_TYPE in ZMM\_EKGRP\_EKORG must be an Ariba-relevant type

Config check in test phase

IP-04

Supplier quotations inbound

Ariba → S/4

Standard supplier quotation inbound message, created with reference to the RFQ

None (downstream). Listed so the end-to-end flow is tested.

Message monitoring; Manage Supplier Quotations

IP-05

Award / follow-on document

Ariba → S/4

Awarded quotation → PO or contract creation (standard)

PR reference on the RFQ item must be kept, so the follow-on document consumes the PR

Document flow PR → RFQ → Quotation → PO

IP-06

Supplier master alignment

S/4 ⇄ Ariba

Business Partner (supplier role) replicated to / mapped in Ariba (Ariba Network ID / SM vendor ID)

Every invited bidder must exist and be enabled in Ariba, otherwise the event fails on the Ariba side

Supplier replication monitoring

IP-07

Master data for items

S/4 → Ariba

Material, material group, plant and unit mapping to Ariba commodity / region codes

Item data copied from the PR must be mappable

Integration content error log

IP-08

Status feedback

Ariba → S/4

RFQ status updates (e.g. event published / completed) returned to S/4

Used by the D-08 exclusion only via RFQ status (active vs. completed)

RFQ status in Manage RFQs

IP-09

Error handling

S/4

Failed outbound messages are restarted in message monitoring – not by this program

Program logs publish success only; the transfer outcome is monitored in IP-01

Integration support runbook

Integration team action: confirm IP-01 to IP-08 for the target release, and confirm that an RFQ created via API and then published produces the same outbound message as one created in the Manage RFQs app.

## 9 New Custom Objects (functional view)

Object

Type

Purpose

ZMM\_PR\_TO\_RFQ\_S4

Executable report

Selection, derivation, creation, publish, log

ZMM\_EKGRP\_EKORG

Customising table + SM30 view

Purchasing group → purchasing org / RFQ type mapping

Message class

T100

Messages in §7

Application log object

SLG0

Job log persistence

Background job + variants

Job definition

Periodic scheduling

## 10 Authorisations

*   Run authorisation: S\_PROGRAM / report authorisation group, or a dedicated transaction code (e.g. ZMM\_RFQ\_AUTO) for online use.
*   PR access: M\_BANF\_EKG (purchasing group), M\_BANF\_WRK (plant), display activity.
*   RFQ creation and publish: the standard RFQ authorisation objects for document type, purchasing organisation and purchasing group, with create/change activities. The standard API performs these checks; the program checks in advance to give a clean log.
*   Background job user: a technical user holding the above for all purchasing organisations in scope.
*   Table ZMM\_EKGRP\_EKORG: maintenance restricted to the purchasing master-data team (S\_TABU\_NAM).

## 11 Non-Functional Requirements

*   Volume: expected PR item volume per run to be confirmed (OI-07). For reference, the current ECC system has 7,704 open, non-deleted PR lines. The design must handle at least that volume in one run with package-wise commits.
*   Performance: one database read for PR items, buffered reads for the mapping, source list and info records. One API call per RFQ.
*   Restartability: every run can be repeated safely. Already converted items are excluded (D-08) and Draft RFQs are re-published via P\_REPROC.
*   Code Quality: only released S/4HANA APIs; no modifications, no BDC, no direct updates of SAP tables.

## 12 Test Scenarios

#

Scenario

Expected result

T-01

Released PR, fixed supplier, 2 further source-list suppliers

1 RFQ with 3 bidders, deadline = today + 30, name RFQ<timestamp>, published, outbound message to Ariba successful

T-02

PR with desired supplier only, no source list or info record

RFQ with 1 bidder, warning 008

T-03

PR without supplier

Skipped, warning 005

T-04

Purchasing group not in ZMM\_EKGRP\_EKORG

Error 006, no RFQ

T-05

PR not released

Not selected

T-06

Second run over the same PR

Skipped, info 004 (D-08)

T-07

Test run (P\_TEST = X)

Log of planned RFQs, nothing created

T-08

Publish fails (e.g. integration endpoint inactive)

RFQ in Draft, error 011; re-run with P\_REPROC publishes it

T-09

Supplier blocked or not in Ariba

Bidder skipped, warning 009

T-10

PR with 2 items in different plants mapping to different purchasing orgs

2 RFQs (grouping A-06)

T-11

User without authorisation for a purchasing group

Items of that group not processed, logged

T-12

End-to-end: supplier quotes in Ariba, award

Supplier quotation in S/4 referencing the RFQ; PO references the PR

## 13 Open Items

#

Open item

Owner

OI-01

Confirm the S/4HANA release and deployment (on-premise / RISE Private Cloud) – needed for the TS (A-01)

Customer IT

OI-02

Confirm where bidders 2 and 3 come from: source list / info records, or a custom PR field or table (A-04)

Customer procurement

OI-03

Confirm that fixed-supplier PRs are in scope (A-03) and the rule when fewer than 3 bidders are found (A-05)

Customer procurement

OI-04

Is a duplicate RFQ name in the same second acceptable, or should the PR number be appended (A-09)?

Customer procurement

OI-05

Are service PRs in scope for a later phase?

Customer procurement

OI-06

Initial content of ZMM\_EKGRP\_EKORG (purchasing group → purchasing org, RFQ type)

Customer MM master data

OI-07

Expected volume per run and job frequency

Customer IT

OI-08

Integration team sign-off on IP-01 to IP-08

Integration team

OI-09

Plan for retiring the ECC programs ZHZL\_PR\_TO\_RFQ, ZBDC\_RFQ\_CREATE, ZBDC\_RFQ\_CREATE1 and ZMM\_PR\_TO\_RFQ\_PO\*

Customer IT

## 14 Evidence From the Current (ECC) System

Check

Finding

Relevance

Purchasing group table T024

No purchasing organisation field

Custom mapping table required (§6.4)

Plant ↔ purchasing org (T024W)

Plants with several organisations, e.g. plant 1000 → 0001, 1, 1000, 1710, C100; plant 0006 → 0006, 2, 3000, C100

Plant-based derivation is ambiguous

Open PR lines (EBAN)

7,704 open, non-deleted lines; 3,977 with fixed supplier; 123 with desired supplier

Volume sizing; A-03

Custom PR fields

EBAN carries custom fields ZZAPRDATE (approval date) and ZZUSER

Confirm whether a custom approval step must be respected in S/4HANA in addition to release (relates to A-02)

Existing custom programs

ZHZL\_PR\_TO\_RFQ, ZBDC\_RFQ\_CREATE, ZBDC\_RFQ\_CREATE1 (package Z\_SGGR), ZMM\_PR\_TO\_RFQ\_PO\* ($TMP)

ECC/BDC solutions; replaced by this design (OI-09)

## 15 Standard Alternative Considered

S/4HANA standard lets a buyer create an RFQ from PRs manually (Manage Purchase Requisitions / Manage RFQs). It has no scheduled job that creates and publishes RFQs automatically with derived bidders. The customer explicitly does not want manual creation, so a small custom job on top of the released RFQ API is justified. This is a Code Quality-compliant extension: no modification, released interfaces only.

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