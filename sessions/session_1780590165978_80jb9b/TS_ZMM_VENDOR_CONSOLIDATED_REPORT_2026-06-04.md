 body { font-family: Segoe UI, Arial, sans-serif; color: #2c3e50; background: #e9ecef; margin: 0; padding: 20px; } .doc-wrapper { max-width: 1120px; background: white; margin: 0 auto; padding: 40px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); } h2 { color: #003366; border-bottom: 3px solid #7FB3E0; padding-bottom: 10px; margin-top: 30px; margin-bottom: 15px; } table { width: 100%; border-collapse: collapse; margin: 15px 0; } table thead { background-color: #003366; color: white; } table th, table td { padding: 12px; text-align: left; border: 1px solid #ddd; } table tbody tr:nth-child(even) { background-color: #f8fafc; } .data-table { margin: 15px 0; } .data-table th { background-color: transparent; color: inherit; font-weight: normal; width: 30%; } .data-table tbody tr:nth-child(even) { background-color: #f8fafc; } .data-table td { padding: 10px; border: 1px solid #ddd; } .doc-footer { margin-top: 50px; padding-top: 20px; border-top: 2px solid #ddd; color: #666; font-size: 0.9em; } p { line-height: 1.6; margin: 10px 0; } ul, ol { margin: 10px 0; padding-left: 30px; } li { margin: 5px 0; } .not-applicable { font-style: italic; color: #666; } :root{--c16-purple-1:#003366;--c16-purple-2:#7FB3E0;--c16-primary:#003366;--c16-secondary:#7FB3E0;--c16-ink:#1f2937;--c16-sub:#4b5563;--c16-rule:#e5e7eb;--c16-accent:#faf5ff;}@page { size: A4; margin: 20mm 18mm 20mm 18mm; } \*, \*::before, \*::after { box-sizing: border-box; margin: 0; padding: 0; } body { font-family: 'Segoe UI', Calibri, Arial, sans-serif; font-size: 10.5pt; line-height: 1.55; color: #1f2937; background: #f4f5f6; -webkit-print-color-adjust: exact; print-color-adjust: exact; } .doc-wrapper { max-width: 1000px; margin: 24px auto; background: #ffffff; box-shadow: 0 1px 8px rgba(0,0,0,0.08); border-radius: 14px; overflow: hidden; } /\* ── Header ─────────────────────────────────────────────── \*/ .doc-header { background: #003366; color: #ffffff; padding: 28px 36px 24px 36px; border-bottom: 4px solid #7FB3E0; } .doc-header-top { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 14px; } .doc-header h1 { font-size: 20pt; font-weight: 600; letter-spacing: -0.3px; margin: 0 0 4px 0; line-height: 1.2; color: #ffffff; } .doc-header .doc-subtitle { font-size: 10.5pt; color: #7FB3E0; font-weight: 400; } .doc-classification { font-size: 8.5pt; letter-spacing: 1.2px; text-transform: uppercase; padding: 3px 12px; border-radius: 2px; border: 1px solid #7FB3E0; background: transparent; color: #7FB3E0; } /\* ── Meta strip ─────────────────────────────────────────── \*/ .doc-meta { padding: 16px 36px; background: #faf5ff; border-bottom: 1px solid #e5e7eb; font-size: 9.5pt; color: #4b5563; } .doc-meta table { width: 100%; border-collapse: collapse; } .doc-meta td { padding: 3px 12px 3px 0; vertical-align: top; } .doc-meta .meta-label { font-weight: 600; color: #003366; white-space: nowrap; width: 120px; } .doc-meta .meta-value { color: #1f2937; } /\* ── Body ──────────────────────────────────────────────── \*/ .doc-body { padding: 24px 36px; } .doc-body h2 { font-size: 14pt; font-weight: 600; color: #003366; border-bottom: 2px solid #003366; padding-bottom: 6px; margin: 32px 0 16px 0; page-break-after: avoid; } .doc-body h2:first-child { margin-top: 0; } .doc-body h2 .sec-num { display: inline-block; background: #003366; color: #FFFFFF; font-size: 10pt; width: 26px; height: 26px; line-height: 26px; text-align: center; border-radius: 3px; margin-right: 10px; vertical-align: middle; } .doc-body h3 { font-size: 11.5pt; font-weight: 600; color: #003366; margin: 22px 0 10px 0; padding-bottom: 4px; border-bottom: 1px solid #e5e7eb; } .doc-body h4 { font-size: 10.5pt; font-weight: 600; color: #1f2937; margin: 16px 0 8px 0; } .doc-body p { color: #4b5563; margin: 8px 0; } /\* ── KPI table (4 columns of big numbers) ────────────────── \*/ .kpi-table { width: 100%; border-collapse: collapse; margin: 16px 0 20px 0; page-break-inside: avoid; } .kpi-table td { width: 25%; text-align: center; padding: 14px 8px; border: 1px solid #D0D4D8; background: #F7F8FA; vertical-align: top; } .kpi-value { font-size: 22pt; font-weight: 700; color: #003366; display: block; line-height: 1.1; } .kpi-label { font-size: 8.5pt; color: #4b5563; text-transform: uppercase; letter-spacing: 0.5px; display: block; margin-top: 4px; } /\* ── Data tables ─────────────────────────────────────────── \*/ table.data-table { width: 100%; border-collapse: collapse; margin: 12px 0 20px 0; font-size: 9.5pt; page-break-inside: avoid; } table.data-table thead th { background: #003366; color: #FFFFFF; font-weight: 600; font-size: 9pt; text-transform: uppercase; letter-spacing: 0.3px; padding: 8px 10px; text-align: left; border: 1px solid #003366; } table.data-table tbody td { padding: 7px 10px; border: 1px solid #e5e7eb; vertical-align: top; } table.data-table tbody tr:nth-child(even) { background: #F7F8FA; } table.data-table tbody tr:hover { background: #edf1f5; } /\* ── Severity / level classes ────────────────────────────── \*/ .sev-critical { color: #b91c1c; font-weight: 600; } .sev-high { color: #C2410C; font-weight: 600; } .sev-medium { color: #a16207; font-weight: 600; } .sev-low { color: #15803D; font-weight: 600; } .level-a { color: #15803D; font-weight: 600; } .level-b { color: #1d4ed8; font-weight: 600; } .level-c { color: #C2410C; font-weight: 600; } .level-d { color: #b91c1c; font-weight: 600; } /\* ── Callouts ────────────────────────────────────────────── \*/ .callout { border-left: 4px solid #003366; background: #F0F4F8; padding: 12px 16px; margin: 14px 0; font-size: 10.5pt; } .callout.callout-warn { border-left-color: #C2410C; background: #FEF3EE; } .callout.callout-success { border-left-color: #15803D; background: #F0FDF4; } .callout.callout-crit { border-left-color: #b91c1c; background: #fdecea; } .callout .callout-title { font-weight: 700; color: #003366; margin-bottom: 4px; font-size: 10.5pt; } .callout.callout-warn .callout-title { color: #C2410C; } .callout.callout-success .callout-title { color: #15803D; } .callout.callout-crit .callout-title { color: #b91c1c; } /\* ── Collapsibles ────────────────────────────────────────── \*/ details { margin: 12px 0; border: 1px solid #e5e7eb; border-radius: 3px; background: #ffffff; } details summary { padding: 10px 14px; background: #faf5ff; font-weight: 600; font-size: 10.5pt; color: #003366; cursor: pointer; border-bottom: 1px solid #e5e7eb; list-style: none; } details summary::-webkit-details-marker { display: none; } details summary::before { content: "\\25B6\\00a0\\00a0"; font-size: 8pt; color: #003366; } details\[open\] summary::before { content: "\\25BC\\00a0\\00a0"; } details\[open\] summary { background: #e2e8f0; } details > div, details > p { padding: 12px 14px; } /\* ── Code / pre ──────────────────────────────────────────── \*/ pre { background: #f5f5f5; border: 1px solid #e5e7eb; border-left: 3px solid #003366; padding: 10px 14px; font-family: 'JetBrains Mono',monospace; font-size: 9pt; overflow-x: auto; margin: 10px 0; line-height: 1.45; } code { font-family: 'JetBrains Mono',monospace; font-size: 9pt; background: #f0f0f0; padding: 1px 4px; border-radius: 2px; } /\* ── TOC ─────────────────────────────────────────────────── \*/ .toc { background: #faf5ff; border: 1px solid #e5e7eb; border-radius: 8px; padding: 16px 24px; margin: 24px 0; } .toc ul { list-style: none; padding-left: 0; margin: 8px 0 0; } .toc a { color: #003366; text-decoration: none; } .toc a:hover { text-decoration: underline; } .toc .toc-num { display: inline-block; width: 26px; height: 20px; line-height: 20px; text-align: center; background: #003366; color: #fff; border-radius: 3px; font-size: 8pt; margin-right: 8px; } /\* ── Footer ──────────────────────────────────────────────── \*/ .doc-footer { background: #F7F8FA; color: #666666; border-top: 2px solid #003366; padding: 14px 36px; font-size: 8.5pt; } .footer-brand { font-weight: 700; color: #003366; } /\* ── Print refinements ────────────────────────────────────── \*/ @media print { body { background: #fff; font-size: 10pt; } .doc-wrapper { box-shadow: none; border: 0; margin: 0; max-width: 100%; } .doc-header { border-radius: 0; } .doc-body h2 { page-break-after: avoid; } details summary { background: #eee; } .toc { display: block; page-break-after: always; } }

![C16](data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAMCAgMCAgMDAwMEAwMEBQgFBQQEBQoHBwYIDAoMDAsKCwsNDhIQDQ4RDgsLEBYQERMUFRUVDA8XGBYUGBIUFRT/2wBDAQMEBAUEBQkFBQkUDQsNFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBT/wAARCAAZAGQDASIAAhEBAxEB/8QAHAABAAICAwEAAAAAAAAAAAAAAAQHBggBAgUJ/8QAKRAAAQMEAAYCAgMBAAAAAAAAAQIDBAAFBhEHCBITITEUQSJRCRVhMv/EABcBAQEBAQAAAAAAAAAAAAAAAAACAQP/xAAeEQADAQACAgMAAAAAAAAAAAAAAQIRAxIxYRNR4f/aAAwDAQACEQMRAD8A+ntKUoBUG/XdvH7Hcbo6xIlNQYzspbERouvOBCCopbQPKlHWgPs6qd6qtMv4ux5sfNcdwGXEyLiJYY6e7ZW9rVGccTtHd9JH47IHV5Oh7NXEO6Uoi6US6Zk3DXO4vE7ArHlcKBcLXEu0YSmod1Y7ElpJJGlo2dHxsedEEEe6yRSghJUohKQNkk6AH2TVM8OOLz+JYLiUXi2/GxHJ7tMFrt7ExJaM1ZOmUgDqCXCNbSSNePXVWJ/yKXq+WLlLzF2xrdZcecixJjrJIUiK48lLvkegdhJ/xR/ddb4XPL8fvPtfpEcivjV+t9livczXC2Ow/KczW2otrDyo7l2Id/r0up9o+X0dnq2NaC978e6sqNJamR2n2HEusuoS424k+FJI2CP8IINU1wYwzFsv5P8ADsWeZYexS6YjHjSGUFIQUORx3VfoKCytXV9KG/qqj5oc6y3h3n3L7a8XziSjEciv8KG5GhIaSX47XxwOqQj8nUOJcJI8JOx7GqlQqrrJXZpazbPIsltGIWeRdr7dIdmtccbemz30sstj62pRA8/Q9n6rjGslt2X2WPdrTIMq3yOrtPFpbXWASNhK0pOvHg60R5GxWm3FqTf+Kv8AIljODfLhRbTjFhVerWxdYq5UT5qmyflFgLR3VoKkhO1AJ7ZI87BtXk/5i8i45sZ5Z8vgQY+S4deDa5My1pWmLLG3EpWlKyopO2l7GyNFJ8eRW1xZPYK9eGw9KUrgdBSlKAUpSgFQIeP2u3XSfcotthxrjcOgzJjMdCHpPQNI7iwNr6R4GydVPpQEC64/a76uEu5WyHcFwX0yoqpcdDpjvJBCXG+oHpWNnSho+a7Xuy2/JLPNtV1hMXG2TWVR5MSSgLaebUNKSpJ9giptK3QUnjXKPhmJW1djt10ypvDVrUs4i5fXl2vSiSpvtn8y2STtvr6VbIIIJ36nE3lmw/i3kNjvN/kXz5NhdS/aGoF0XFZt7ienS2UIACTtCD9+v14q2KVXet3Seq8Fc5bwGxrMMixzJZDtzg5fYGFRoOSW+X2p/aUkpW24rpKXUq6lEhaSNkka3XpcKOD2K8Fcdes2KW4w2JMhcyXIfeU/JmSF/wDbzzqiVLUf2fA9ACs0pWdm1mm4vIpSlSaKUpQH/9k=)

Your Autonomous SAP Team

## Purpose of the document

The purpose of this document is to document the SAP custom program modification ZMM\_VENDOR\_CONSOLIDATED\_REPORT and its technical specifications. This program enhances the standard SAP vendor master data functionality by consolidating vendor information with compliance, risk assessment, and certification data. This document forms the official technical documentation of the solution and is the basis for maintenance and future enhancements.

## Revision History

Version

Date

Author

Derivation/Comments

1.0

2024-02-04

Ragunath Loganathan

Added MSME Certificate field. Transport: WS1K997027

1.1

2024-05-21

Polabathina Bhavani

Group Customer field addition. Transport: WS1K9A014E

1.2

2024-06-24

Polabathina Bhavani

Removed unwanted code errors. Transport: WS1K9A02YZ

1.3

2024-07-03

Polabathina Bhavani

Production issue fixes. Transport: WS1K9A03GW

1.4

2024-10-11

Polabathina Bhavani

Major enhancements - Added input fields and blacklist logic. Transport: WS1K9A05EB

1.5

2025-05-02

Jeevan Sagar

Added BEE\_Level field. Transport: WS1K9A0HO1

## Review History

Version

Date

Reviewer

Remarks

To be completed during review cycle

## Approval History

Version

Date

Approver

Remarks

To be completed upon approval

## This document is effective from the Approval date

Upon approval by authorized stakeholders, this document becomes the official technical specification for ZMM\_VENDOR\_CONSOLIDATED\_REPORT.

## Object Overview

Object ID

ZMM\_VENDOR\_CONSOLIDATED\_REPORT

Business Process

Vendor Master Data Management (MM-Vendor)

Object Title

Consolidated Vendor Report with Compliance & Risk Assessment

Object Description

ABAP executable report consolidating vendor master data from LFA1, ADRC, and custom tables (ZVENDOR\_BLOCK, ZMM\_VENDOR\_MSME, ZMM\_VENDOR\_BEE) with filtered views based on vendor account groups, blacklist status, and certifications.

SAP Release

ECC 7.40 (Kernel 753)

SAP Module

MM (Materials Management) - Vendor Master

Cycle of Testing

C1 / C2 / C3 / C4

Required Development Completion Date

2025-05-02

Complexity of Object

Complex

Transaction run

Batch / Real-time

Type of Enhancement

Custom Report - Standard Functionality Enhancement

Priority

High

Similar SAP Transaction

XK03 (Display Vendor), XK01 (Create Vendor)

Similar SAP Program

SAPMF02K (Vendor Master Display)

## TS Control

TS Author and Phone Number

Jeevan Sagar (IN20546163), Polabathina Bhavani (PO20312220)

Process Owner and Phone Number

Manoranjan (FC), Bijay (FC)

TS Approved By

To be assigned

TS Approval date

YYYY-MM-DD

Other Contact and Phone Number

Development Team

## Program Attributes

Enhancement Object

Function Exit

Not applicable

Include

None - standalone report

Screen Exit

Selection Screen with dynamic dropdowns via VRM\_SET\_VALUES

Menu Exit

Not applicable

Badi

Not applicable

New Transaction

Not assigned

Search Help

Not applicable

Area Menu

Not applicable

Custom Dialog Screens

Not applicable

Index

Not applicable

Transaction Code

Execute via SE38 / SA38

Message Class

Inline MESSAGE statements

SAP Tables Read

LFA1, ADRC, ADR6, ADRCT, LFB1, LFM1, BUT050, CVI\_VEND\_LINK, BUT000, TVARVC

Custom Tables

ZVENDOR\_BLOCK, ZMM\_VENDOR\_MSME, ZMM\_VENDOR\_BEE

## Technical Flow Diagram

SELECTION-SCREEN INPUT (SELECT-OPTIONS: s\_ktokk, s\_erdat, s\_gvend, s\_lifnr; PARAMETERS: p\_status, p\_black, p\_begru, p\_begru1, p\_brsch) → AT SELECTION-SCREEN OUTPUT (Populate VRM dropdowns) → START-OF-SELECTION (Validate filters, read ZMM\_VEND\_ACC\_GROUP variant if empty, SELECT from LFA1 for all related tables via FOR ALL ENTRIES IN, apply secondary filter logic) → LAYOUT\_BUILD (Construct ALV field catalog, call REUSE\_ALV\_GRID\_DISPLAY) → DISPLAY REPORT

## Processing Logic

**Pseudo Code:** (1) Initialize vendor structure (ty\_final) with 50+ fields from LFA1 and custom tables. (2) AT SELECTION-SCREEN OUTPUT: Populate 5 dropdown parameters using VRM\_SET\_VALUES function for P\_STATUS (ACTIVE/INACTIVE), P\_BLACK (YES/NO), P\_BEGRU (YES/NO), P\_BEGRU1 (YES/NO), P\_BRSCH (YES/NO). (3) START-OF-SELECTION: Validate mutual exclusivity of secondary filters; if all parameters empty, read ZMM\_VEND\_ACC\_GROUP variant into s\_ktokk. (4) SELECT vendor data from LFA1 filtered by account group. (5) FOR EACH vendor, execute 11 parallel SELECTs for related data (CVI\_VEND\_LINK, BUT000, BUT050, ADRC, ADR6, ADRCT, LFB1, LFM1, ZVENDOR\_BLOCK, ZMM\_VENDOR\_MSME, ZMM\_VENDOR\_BEE); SORT result tables by key. (6) LOOP AT lt\_lfa1 to consolidate data into ty\_final structure. (7) Apply secondary filter logic (P\_STATUS→SPERR/SPERM/SPERQ flags, P\_BLACK→VFLAG, P\_BEGRU→BEGRU field, P\_BRSCH→BRSCH field). (8) Call LAYOUT\_BUILD to construct ALV field catalog and render REUSE\_ALV\_GRID\_DISPLAY output.

## Reusable Code

LAYOUT\_BUILD: Constructs SLIS field catalog for ALV grid display. VRM\_SET\_VALUES: SAP standard function for populating selection screen dropdowns (5 calls for different parameters). TVARVC variant reading logic: Can be extracted for reuse in other vendor reports. FOR ALL ENTRIES pattern: Efficient table join technique used across all related data fetches.

## Internal Tables

Name

Description

lt\_final

Final consolidated vendor data (TYPE TABLE OF ty\_final). Output for ALV display with 50+ fields.

lt\_lfa1

Vendor master from LFA1 (LIFNR, KTOKK, ERDAT, SPERR, SPERM, SPERQ, BEGRU, BRSCH, TELF1, TELF2, STCD1-5, etc.)

lt\_partner\_guid

Vendor-Partner GUID mapping from CVI\_VEND\_LINK (VENDOR, PARTNER\_GUID)

lt\_partner

Business partner master from BUT000 (PARTNER\_GUID, PARTNER)

lt\_group\_vendor

Business partner relationships from BUT050 (PARTNER1, PARTNER2 for hierarchy)

lt\_adrc

Address master from ADRC (ADDRNUMBER, COUNTRY, STREET, POSTAL\_CODE, REGION)

lt\_zterm

Payment terms from LFB1 (LIFNR, ZTERM)

lt\_waers

Currency from LFM1 (LIFNR, WAERS)

lt\_adr6

Email addresses from ADR6 (ADDRNUMBER, SMTP\_ADDR)

lt\_adrct

Address comments from ADRCT (ADDRNUMBER, REMARK)

lt\_zvendor\_block1

Vendor blacklist from ZVENDOR\_BLOCK (LIFNR, VFLAG where X=blacklisted)

lt\_zmm\_vendor\_msme

MSME certification from ZMM\_VENDOR\_MSME (LIFNR, MSME\_CERT\_NUM)

lt\_zmm\_vendor\_bee

BEE level from ZMM\_VENDOR\_BEE (LIFNR, BEE\_LEVEL)

lt\_fcat

ALV field catalog (SLIS\_T\_FIELDCAT\_ALV) for report column definitions

## Messages

Message Class

Message ID

Message Text

N/A

Inline E

No data available in ZMM\_VEND\_ACC\_GROUP variant

N/A

Inline E

Please select only one input from last 5 secondary fields

## Text Elements

Name

Text Description

TEXT-000

Selection Criteria (Block B1 frame title)

P\_STATUS

Status field label (ACTIVE/INACTIVE dropdown)

P\_BLACK

Blacklist field label (YES/NO dropdown)

P\_BEGRU

Vendor Group label (YES/NO dropdown)

P\_BEGRU1

Vendor Group1 label (YES/NO dropdown)

P\_BRSCH

Industry Key label (YES/NO dropdown)

## Subroutines

Name

Description

LAYOUT\_BUILD

Constructs SLIS field catalog defining vendor report columns with headers, widths, alignment. Calls REUSE\_ALV\_GRID\_DISPLAY to render interactive grid. Uses global lt\_final table. Called from START-OF-SELECTION.

## Security

**Authorization Requirements:** S\_TABU\_NAM for reading LFA1 and custom tables. S\_PURCHASE recommended for purchasing users. Once Z-transaction assigned, control via TCODE authorization. **Data Protection:** Email addresses (SMTP\_ADDR) and phone numbers (TELF1, TELF2) exposed in report output. No AUTHORITY-CHECK statement implemented; consider adding field-level authorization or email masking for exported reports.

## Upgrade

**S/4HANA Simplification Impact:** Program uses business partner tables (BUT000, BUT050) which are S/4HANA-compliant. Fields KTOKK (vendor account group) stable on ECC; for S/4HANA consider using I\_SUPPLIER CDS view. Custom tables ZVENDOR\_BLOCK, ZMM\_VENDOR\_MSME, ZMM\_VENDOR\_BEE persist across upgrades. ALV framework (REUSE\_ALV\_GRID\_DISPLAY) deprecated in S/4HANA; post-migration modernize to CL\_SALV\_TABLE or RAP/Fiori Elements. After support pack upgrade: test LFA1 and business partner table data retrieval; verify no custom table field changes; retest VRM\_SET\_VALUES functionality.

## Future Enhancements

*   **Fiori Elements Migration (Priority: High):** Convert from ALV to Fiori List Report + Object Page using RAP Managed BO with draft. Target: S/4HANA migration.
*   **CDS View Abstraction (Priority: Medium):** Create ZI\_VENDOR\_CONSOLIDATED CDS view consolidating vendor + compliance data for OData exposure and reuse.
*   **Batch Reporting (Priority: Low):** Enable scheduled execution with email distribution using SAP Job Scheduler SM36.
*   **Multi-Language Support (Priority: Low):** Internationalize selection screen labels for global organizations.

## Assumptions in Technical Design

*   ZMM\_VEND\_ACC\_GROUP variant exists in TVARVC and is properly maintained by business team.
*   Custom tables ZVENDOR\_BLOCK, ZMM\_VENDOR\_MSME, ZMM\_VENDOR\_BEE exist and are populated via maintenance transactions.
*   CVI\_VEND\_LINK maintains sync between LFA1 and BUT000 vendor data; no orphaned links.
*   BUT050 relationships follow hierarchy: PARTNER1 (child vendor), PARTNER2 (parent vendor).
*   ADRC, ADR6, ADRCT data for vendor address number (ADRNR) is complete; missing records result in NULL values.
*   ZTERM (payment terms) from LFB1 selected without company code filtering; only first matching record used per vendor.
*   Program runs on ECC 7.40 with adequate dialog work process availability.
*   Users have authorization to read vendor and custom tables; no row-level security enforced.

## Open Issues in Technical Design

*   **P1 - Multi-Company Code Handling:** Report selects LFB1 without company code filter. For vendors with multiple company codes, only one ZTERM selected. Clarification: Should report include all company codes?
*   **P2 - Blacklist Flag Semantics:** ZVENDOR\_BLOCK.VFLAG='X' meaning unclear. Confirm: Does 'X' indicate vendor is blacklisted or block is active?
*   **P3 - BEE\_LEVEL Values:** Field values not documented (e.g., STAR 1/2/3 or codes?). Add value mapping to output if needed.
*   **P4 - Secondary Filter Logic:** Mutual exclusivity validation uses nested IF statements. Refactor using CASE statement for maintainability.
*   **P5 - Performance at Scale:** FOR ALL ENTRIES works well up to ~10K vendors. Beyond 10K, consider batch processing or CDS pushdown.
*   **P6 - MSME/BEE Date Validity:** Program ignores certification expiry dates. Add date fields to custom tables if validity period is critical.
*   **P7 - Email Privacy:** SMTP\_ADDR exposed in report. Implement GDPR compliance; consider masking in exports.

## Unit Test Plan

Scenario #

Input Selection Criteria

Expected Result

TC001

All parameters empty

Report reads ZMM\_VEND\_ACC\_GROUP variant, displays all active vendors matching default account groups

TC002

s\_lifnr = '0000001000'

Single vendor displayed with all consolidated fields in ALV grid

TC003

s\_ktokk = '24'

All vendors with account group 24, sorted by LIFNR

TC004

s\_erdat = '2023-01-01' TO '2024-12-31'

Vendors created within date range

TC005

p\_status = '1' (ACTIVE)

Vendors with no SPERR/SPERM/SPERQ blocks

TC006

p\_status = '2' (INACTIVE)

Vendors with SPERR='X' OR SPERM='X' OR SPERQ='X'

TC007

p\_black = '1' (YES)

Only vendors with ZVENDOR\_BLOCK VFLAG='X'

TC011

p\_status = '1' AND p\_black = '1'

Error message; fields disabled; no data retrieved

TC012

All parameters empty, variant missing

Error message: 'No data available in ZMM\_VEND\_ACC\_GROUP variant'

TC013

s\_ktokk = '99' (non-existent group)

Report succeeds, displays empty ALV grid

## Related Documentation (attach OSS notes, emails, download of existing report, etc)

*   Functional Specification: Charm numbers 4000004597, 4000005275, 4000005596, 4000005680, 4000006028, 4000006474, 4000008627
*   Transports: WS1K997027, WS1K9A014E, WS1K9A02YZ, WS1K9A03GW, WS1K9A04RP, WS1K9A05EB, WS1K9A06LT, WS1K9A07DO, WS1K9A08IU, WS1K9A09D0, WS1K9A0HO1
*   Custom Tables: ZVENDOR\_BLOCK, ZMM\_VENDOR\_MSME, ZMM\_VENDOR\_BEE definitions
*   Variant: ZMM\_VEND\_ACC\_GROUP (TVARVC) contains default vendor account groups
*   ALV Reference: REUSE\_ALV\_GRID\_DISPLAY and SLIS\_FIELDCAT\_ALV structure documentation

**Verification Methodology:** This TS was generated from live SAP ECC 7.40 system (kernel 753) by analyzing program source ZMM\_VENDOR\_CONSOLIDATED\_REPORT. All technical details derived from active code. Change history and transports extracted from code comments. Accuracy as of 2026-06-04, version 1.5. Future code changes require document updates.

**System: ECC 7.40 (Kernel 753) | Generated: 2026-06-04 | Version: 1.0**

## Date

_Not applicable — section not populated by generator._

## Date

_Not applicable — section not populated by generator._

## Date

_Not applicable — section not populated by generator._

## Open Issues in Technical Design �

_Not applicable — section not populated by generator._

## Unit Test Plan�

_Not applicable — section not populated by generator._

**C16 — AI-Powered SAP Analysis**  
_Generated by C16. This document is AI-generated and should be validated by a qualified SAP consultant before implementation. All data sourced from the connected SAP system._