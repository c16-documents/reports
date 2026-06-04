 body { font-family: 'Segoe UI', Arial, sans-serif; color: #2c3e50; background: #e9ecef; padding: 20px; line-height: 1.6; } .doc-wrapper { max-width: 1120px; background: white; margin: 0 auto; padding: 40px; box-shadow: 0 2px 10px rgba(0,0,0,0.1); } h2 { color: #003366; border-bottom: 3px solid #7FB3E0; padding-bottom: 10px; margin-top: 35px; margin-bottom: 20px; font-size: 20px; font-weight: 600; } h3 { color: #003366; margin-top: 16px; margin-bottom: 12px; font-size: 15px; font-weight: 600; } table { width: 100%; border-collapse: collapse; margin: 20px 0; font-size: 13px; } table thead { background: #003366; color: white; } table thead th { padding: 12px; text-align: left; font-weight: 600; border: 1px solid #003366; } table tbody tr:nth-child(even) { background: #f8fafc; } table tbody tr:hover { background: #edf2f7; } table td { padding: 12px; border: 1px solid #ddd; vertical-align: top; } .data-table td:first-child { font-weight: 600; background: #f0f4f8; width: 35%; } pre { background: #f5f5f5; border-left: 4px solid #7FB3E0; padding: 15px; overflow-x: auto; font-size: 12px; margin: 15px 0; } .footer { margin-top: 60px; padding-top: 20px; border-top: 1px solid #ddd; font-size: 12px; color: #666; text-align: center; } :root{--c16-purple-1:#003366;--c16-purple-2:#7FB3E0;--c16-primary:#003366;--c16-secondary:#7FB3E0;--c16-ink:#1f2937;--c16-sub:#4b5563;--c16-rule:#e5e7eb;--c16-accent:#faf5ff;}@page { size: A4; margin: 20mm 18mm 20mm 18mm; } \*, \*::before, \*::after { box-sizing: border-box; margin: 0; padding: 0; } body { font-family: 'Segoe UI', Calibri, Arial, sans-serif; font-size: 10.5pt; line-height: 1.55; color: #1f2937; background: #f4f5f6; -webkit-print-color-adjust: exact; print-color-adjust: exact; } .doc-wrapper { max-width: 1000px; margin: 24px auto; background: #ffffff; box-shadow: 0 1px 8px rgba(0,0,0,0.08); border-radius: 14px; overflow: hidden; } /\* ── Header ─────────────────────────────────────────────── \*/ .doc-header { background: #003366; color: #ffffff; padding: 28px 36px 24px 36px; border-bottom: 4px solid #7FB3E0; } .doc-header-top { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 14px; } .doc-header h1 { font-size: 20pt; font-weight: 600; letter-spacing: -0.3px; margin: 0 0 4px 0; line-height: 1.2; color: #ffffff; } .doc-header .doc-subtitle { font-size: 10.5pt; color: #7FB3E0; font-weight: 400; } .doc-classification { font-size: 8.5pt; letter-spacing: 1.2px; text-transform: uppercase; padding: 3px 12px; border-radius: 2px; border: 1px solid #7FB3E0; background: transparent; color: #7FB3E0; } /\* ── Meta strip ─────────────────────────────────────────── \*/ .doc-meta { padding: 16px 36px; background: #faf5ff; border-bottom: 1px solid #e5e7eb; font-size: 9.5pt; color: #4b5563; } .doc-meta table { width: 100%; border-collapse: collapse; } .doc-meta td { padding: 3px 12px 3px 0; vertical-align: top; } .doc-meta .meta-label { font-weight: 600; color: #003366; white-space: nowrap; width: 120px; } .doc-meta .meta-value { color: #1f2937; } /\* ── Body ──────────────────────────────────────────────── \*/ .doc-body { padding: 24px 36px; } .doc-body h2 { font-size: 14pt; font-weight: 600; color: #003366; border-bottom: 2px solid #003366; padding-bottom: 6px; margin: 32px 0 16px 0; page-break-after: avoid; } .doc-body h2:first-child { margin-top: 0; } .doc-body h2 .sec-num { display: inline-block; background: #003366; color: #FFFFFF; font-size: 10pt; width: 26px; height: 26px; line-height: 26px; text-align: center; border-radius: 3px; margin-right: 10px; vertical-align: middle; } .doc-body h3 { font-size: 11.5pt; font-weight: 600; color: #003366; margin: 22px 0 10px 0; padding-bottom: 4px; border-bottom: 1px solid #e5e7eb; } .doc-body h4 { font-size: 10.5pt; font-weight: 600; color: #1f2937; margin: 16px 0 8px 0; } .doc-body p { color: #4b5563; margin: 8px 0; } /\* ── KPI table (4 columns of big numbers) ────────────────── \*/ .kpi-table { width: 100%; border-collapse: collapse; margin: 16px 0 20px 0; page-break-inside: avoid; } .kpi-table td { width: 25%; text-align: center; padding: 14px 8px; border: 1px solid #D0D4D8; background: #F7F8FA; vertical-align: top; } .kpi-value { font-size: 22pt; font-weight: 700; color: #003366; display: block; line-height: 1.1; } .kpi-label { font-size: 8.5pt; color: #4b5563; text-transform: uppercase; letter-spacing: 0.5px; display: block; margin-top: 4px; } /\* ── Data tables ─────────────────────────────────────────── \*/ table.data-table { width: 100%; border-collapse: collapse; margin: 12px 0 20px 0; font-size: 9.5pt; page-break-inside: avoid; } table.data-table thead th { background: #003366; color: #FFFFFF; font-weight: 600; font-size: 9pt; text-transform: uppercase; letter-spacing: 0.3px; padding: 8px 10px; text-align: left; border: 1px solid #003366; } table.data-table tbody td { padding: 7px 10px; border: 1px solid #e5e7eb; vertical-align: top; } table.data-table tbody tr:nth-child(even) { background: #F7F8FA; } table.data-table tbody tr:hover { background: #edf1f5; } /\* ── Severity / level classes ────────────────────────────── \*/ .sev-critical { color: #b91c1c; font-weight: 600; } .sev-high { color: #C2410C; font-weight: 600; } .sev-medium { color: #a16207; font-weight: 600; } .sev-low { color: #15803D; font-weight: 600; } .level-a { color: #15803D; font-weight: 600; } .level-b { color: #1d4ed8; font-weight: 600; } .level-c { color: #C2410C; font-weight: 600; } .level-d { color: #b91c1c; font-weight: 600; } /\* ── Callouts ────────────────────────────────────────────── \*/ .callout { border-left: 4px solid #003366; background: #F0F4F8; padding: 12px 16px; margin: 14px 0; font-size: 10.5pt; } .callout.callout-warn { border-left-color: #C2410C; background: #FEF3EE; } .callout.callout-success { border-left-color: #15803D; background: #F0FDF4; } .callout.callout-crit { border-left-color: #b91c1c; background: #fdecea; } .callout .callout-title { font-weight: 700; color: #003366; margin-bottom: 4px; font-size: 10.5pt; } .callout.callout-warn .callout-title { color: #C2410C; } .callout.callout-success .callout-title { color: #15803D; } .callout.callout-crit .callout-title { color: #b91c1c; } /\* ── Collapsibles ────────────────────────────────────────── \*/ details { margin: 12px 0; border: 1px solid #e5e7eb; border-radius: 3px; background: #ffffff; } details summary { padding: 10px 14px; background: #faf5ff; font-weight: 600; font-size: 10.5pt; color: #003366; cursor: pointer; border-bottom: 1px solid #e5e7eb; list-style: none; } details summary::-webkit-details-marker { display: none; } details summary::before { content: "\\25B6\\00a0\\00a0"; font-size: 8pt; color: #003366; } details\[open\] summary::before { content: "\\25BC\\00a0\\00a0"; } details\[open\] summary { background: #e2e8f0; } details > div, details > p { padding: 12px 14px; } /\* ── Code / pre ──────────────────────────────────────────── \*/ pre { background: #f5f5f5; border: 1px solid #e5e7eb; border-left: 3px solid #003366; padding: 10px 14px; font-family: 'JetBrains Mono',monospace; font-size: 9pt; overflow-x: auto; margin: 10px 0; line-height: 1.45; } code { font-family: 'JetBrains Mono',monospace; font-size: 9pt; background: #f0f0f0; padding: 1px 4px; border-radius: 2px; } /\* ── TOC ─────────────────────────────────────────────────── \*/ .toc { background: #faf5ff; border: 1px solid #e5e7eb; border-radius: 8px; padding: 16px 24px; margin: 24px 0; } .toc ul { list-style: none; padding-left: 0; margin: 8px 0 0; } .toc a { color: #003366; text-decoration: none; } .toc a:hover { text-decoration: underline; } .toc .toc-num { display: inline-block; width: 26px; height: 20px; line-height: 20px; text-align: center; background: #003366; color: #fff; border-radius: 3px; font-size: 8pt; margin-right: 8px; } /\* ── Footer ──────────────────────────────────────────────── \*/ .doc-footer { background: #F7F8FA; color: #666666; border-top: 2px solid #003366; padding: 14px 36px; font-size: 8.5pt; } .footer-brand { font-weight: 700; color: #003366; } /\* ── Print refinements ────────────────────────────────────── \*/ @media print { body { background: #fff; font-size: 10pt; } .doc-wrapper { box-shadow: none; border: 0; margin: 0; max-width: 100%; } .doc-header { border-radius: 0; } .doc-body h2 { page-break-after: avoid; } details summary { background: #eee; } .toc { display: block; page-break-after: always; } }

![C16](data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAMCAgMCAgMDAwMEAwMEBQgFBQQEBQoHBwYIDAoMDAsKCwsNDhIQDQ4RDgsLEBYQERMUFRUVDA8XGBYUGBIUFRT/2wBDAQMEBAUEBQkFBQkUDQsNFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBT/wAARCAAZAGQDASIAAhEBAxEB/8QAHAABAAICAwEAAAAAAAAAAAAAAAQHBggBAgUJ/8QAKRAAAQMEAAYCAgMBAAAAAAAAAQIDBAAFBhEHCBITITEUQSJRCRVhMv/EABcBAQEBAQAAAAAAAAAAAAAAAAACAQP/xAAeEQADAQACAgMAAAAAAAAAAAAAAQIRAxIxYRNR4f/aAAwDAQACEQMRAD8A+ntKUoBUG/XdvH7Hcbo6xIlNQYzspbERouvOBCCopbQPKlHWgPs6qd6qtMv4ux5sfNcdwGXEyLiJYY6e7ZW9rVGccTtHd9JH47IHV5Oh7NXEO6Uoi6US6Zk3DXO4vE7ArHlcKBcLXEu0YSmod1Y7ElpJJGlo2dHxsedEEEe6yRSghJUohKQNkk6AH2TVM8OOLz+JYLiUXi2/GxHJ7tMFrt7ExJaM1ZOmUgDqCXCNbSSNePXVWJ/yKXq+WLlLzF2xrdZcecixJjrJIUiK48lLvkegdhJ/xR/ddb4XPL8fvPtfpEcivjV+t9livczXC2Ow/KczW2otrDyo7l2Id/r0up9o+X0dnq2NaC978e6sqNJamR2n2HEusuoS424k+FJI2CP8IINU1wYwzFsv5P8ADsWeZYexS6YjHjSGUFIQUORx3VfoKCytXV9KG/qqj5oc6y3h3n3L7a8XziSjEciv8KG5GhIaSX47XxwOqQj8nUOJcJI8JOx7GqlQqrrJXZpazbPIsltGIWeRdr7dIdmtccbemz30sstj62pRA8/Q9n6rjGslt2X2WPdrTIMq3yOrtPFpbXWASNhK0pOvHg60R5GxWm3FqTf+Kv8AIljODfLhRbTjFhVerWxdYq5UT5qmyflFgLR3VoKkhO1AJ7ZI87BtXk/5i8i45sZ5Z8vgQY+S4deDa5My1pWmLLG3EpWlKyopO2l7GyNFJ8eRW1xZPYK9eGw9KUrgdBSlKAUpSgFQIeP2u3XSfcotthxrjcOgzJjMdCHpPQNI7iwNr6R4GydVPpQEC64/a76uEu5WyHcFwX0yoqpcdDpjvJBCXG+oHpWNnSho+a7Xuy2/JLPNtV1hMXG2TWVR5MSSgLaebUNKSpJ9giptK3QUnjXKPhmJW1djt10ypvDVrUs4i5fXl2vSiSpvtn8y2STtvr6VbIIIJ36nE3lmw/i3kNjvN/kXz5NhdS/aGoF0XFZt7ienS2UIACTtCD9+v14q2KVXet3Seq8Fc5bwGxrMMixzJZDtzg5fYGFRoOSW+X2p/aUkpW24rpKXUq6lEhaSNkka3XpcKOD2K8Fcdes2KW4w2JMhcyXIfeU/JmSF/wDbzzqiVLUf2fA9ACs0pWdm1mm4vIpSlSaKUpQH/9k=)

Your Autonomous SAP Team

## Purpose of the document

The purpose of this document is to document the SAP code modification and processing logic for the Vendor Consolidated Report (ZMM\_VENDOR\_CONSOLIDATED\_REPORT). This enhancement provides a comprehensive consolidated view of vendor master data with enriched attributes including MSME certification, BEE levels, blacklisted status, and group vendor relationships. This document once approved by the appropriate authorities forms the official documentation of the technical solution and is the basis for further maintenance.

## Revision History

Version

Date

Author

Derivation/Comments

1.0

27/03/2024

Ragunath Loganathan

MSME Cert Number field (Charm 4000004597)

2.0

21/05/2024

Polabathina Bhavani

Group Customer field addition (Charm 4000005275)

3.0

24/06/2024

Polabathina Bhavani

Removed unwanted code error (Charm 4000005596)

4.0

03/07/2024

Polabathina Bhavani

Production issue data fetch (Charm 4000005680)

5.0

11/10/2024

Polabathina Bhavani

Secondary fields for 24 vendor account groups (Charm 4000006474)

6.0

02/05/2025

Jeevan Sagar

BEE\_Level field addition (Charm 4000008627)

## Date

Last updated: 02/05/2025

## Review History

Version

Date

Reviewer

Remarks

6.0

2026-04-28

C16 Technical Team

Technical specification generated from source code analysis

## Date

Review cycle: 2026-04-28

## Approval History

Version

Date

Approver

Remarks

6.0

YYYY-MM-DD

TBD

Pending approval from functional and technical leads

## Date

Approval date: Pending

## This document is effective from the Approval date

Once approved by authorized signatories, this technical specification becomes the binding reference document for implementation, testing, and maintenance of ZMM\_VENDOR\_CONSOLIDATED\_REPORT.

## Object Overview

### Object ID

ZMM\_VENDOR\_CONSOLIDATED\_REPORT (ABAP Report, type PROG)

### Business Process

Materials Management (MM) - Vendor Master Data Management, Procurement-to-Pay Cycle (P2P)

### Object Title

Vendor Consolidated Report

### Object Description

Executable ABAP report consolidating vendor master data (LFA1) with enriched attributes including address (ADRC), email (ADR6), remarks (ADRCT), payment terms (LFB1), currency (LFM1), group vendor relationships (BUT050), vendor blocking status (ZVENDOR\_BLOCK), MSME certification (ZMM\_VENDOR\_MSME), and BEE levels (ZMM\_VENDOR\_BEE). Supports dynamic filtering via selection screen with primary filters (vendor account group, creation date, group vendor, vendor number) and mutually exclusive secondary filters (status, blacklist, BEE group, risk category, industry).

### SAP Release

ECC 7.40 (Kernel 753)

### SAP Module

MM (Materials Management)

### Cycle of Testing

C3

### Required Development Completion Date

2025-05-02

### Complexity of Object

Complex

### Transaction run

Batch

### Type of Enhancement

Custom Report - New Transaction / New Program

### Priority

High

### Similar SAP Transaction

FK03 (Vendor Display), XK03 (Vendor Display - Purchasing)

### Similar SAP Program

RFIDVND (Vendor Report)

## TS Control

### TS Author and Phone Number

C16 Technical Review Team

### Process Owner and Phone Number

Materials Management Department (Functional Lead: Manoranjan)

### TS Approved By

TBD - Development Manager / Technical Lead

### TS Approval date

YYYY-MM-DD

### Other Contact and Phone Number

Polabathina Bhavani (PO20312220) - Primary Developer

### Other Contact and Phone Number

Jeevan Sagar (IN20546163) - Recent Enhancement Author (BEE Level, v6.0)

## Program Attributes

Enhancement Object

No

Function Exit

No

Include

No

Screen Exit

No

Menu Exit

No

Badi

No

New Transaction

Yes - Custom ABAP Report

Search Help

No

Area Menu

No

Custom Dialog Screens

No - Standard Selection Screen

Index

No

Transaction Code

ZMM (Message Class), TBD (Transaction Code)

Message Class

ZMM

SAP Tables Read

LFA1, ADRC, ADR6, ADRCT, LFB1, LFM1, BUT000, BUT050, CVI\_VEND\_LINK, ZVENDOR\_BLOCK, ZMM\_VENDOR\_MSME, ZMM\_VENDOR\_BEE, TVARVC

Custom Tables

ZVENDOR\_BLOCK, ZMM\_VENDOR\_MSME, ZMM\_VENDOR\_BEE

## Technical Flow Diagram

The program follows a sequential fetch-and-enrich pattern: SELECTION-SCREEN → VALIDATION → VARIANT-BASED DEFAULT FETCH → FOR ALL ENTRIES SELECT (11 tables in parallel) → ENRICH via LOOP and JOIN → ALV DISPLAY.

START-OF-SELECTION
  ├─ Load ZMM\_VEND\_ACC\_GROUP from TVARVC if filters empty
  ├─ SELECT LFA1 (vendor master) FOR ALL ENTRIES in s\_ktokk
  ├─ SELECT CVI\_VEND\_LINK (vendor-BP link) FOR ALL ENTRIES
  ├─ SELECT BUT000 (BP master) FOR ALL ENTRIES
  ├─ SELECT BUT050 (group vendor) FOR ALL ENTRIES
  ├─ SELECT ADRC, LFB1, LFM1, ADR6, ADRCT, ZVENDOR\_BLOCK, 
  │  ZMM\_VENDOR\_MSME, ZMM\_VENDOR\_BEE FOR ALL ENTRIES
  ├─ LOOP at lt\_lfa1 and populate lt\_final with joined data
  └─ Display lt\_final via ALV

## Processing Logic

Selection screen populated with LISTBOX parameters via VRM\_SET\_VALUES in AT SELECTION-SCREEN OUTPUT event. Secondary parameters (P\_STATUS, P\_BLACK, P\_BEGRU, P\_BEGRU1, P\_BRSCH) are mutually exclusive—error raised if multiple filled. Vendor status determined by SPERR/SPERM/SPERQ flags. Data fetch uses FOR ALL ENTRIES pattern with 11 parallel SELECTs, then enrichment via LOOP with O(n) sorted table lookups. Output displays 51-field consolidated vendor records via ALV framework.

## Reusable Code

VRM\_SET\_VALUES pattern for LISTBOX population. FOR ALL ENTRIES SELECT pattern for multi-table vendor enrichment. Mutual exclusivity validation logic for selection parameters. Can be extracted into reusable subroutines for other MM reports.

## Internal Tables

Name

Description

LT\_FINAL

Output table with 51 consolidated vendor fields for ALV display

LS\_FINAL

Work area for TY\_FINAL structure

LT\_LFA1

Vendor master from LFA1 (21 fields)

LT\_PARTNER\_GUID

Vendor-BP GUID mapping from CVI\_VEND\_LINK

LT\_PARTNER

Business Partner master from BUT000

LT\_GROUP\_VENDOR

Group vendor relationships from BUT050

LT\_ADRC

Address data from ADRC

LT\_ZTERM

Payment terms from LFB1

LT\_WAERS

Currency from LFM1

LT\_ADR6

Email from ADR6

LT\_ADRCT

Remarks from ADRCT

LT\_ZVENDOR\_BLOCK1

Block status from ZVENDOR\_BLOCK

LT\_ZMM\_VENDOR\_MSME

MSME certification from ZMM\_VENDOR\_MSME

LT\_ZMM\_VENDOR\_BEE

BEE level from ZMM\_VENDOR\_BEE (v6.0)

## Messages

Message Class

Message ID

Message Text

ZMM

001

Report Selection fetched no data

ZMM

Please select only one input from last 5 secondary fields

ZMM

No data available in ZMM\_VEND\_ACC\_GROUP variant

## Text Elements

Name

Text Description

000

Selection Criteria (SELECTION-SCREEN FRAME title)

## Subroutines

Name

Description

Not Applicable

Current version uses inline logic in event blocks, no PERFORM-based subroutines

## Security

**Authorization Objects Required:** S\_TCODE (transaction code), F\_LFA1\_BEK (vendor master - activity 03), S\_TABU\_NAM (table authorization). **Security Gap:** No row-level authorization filtering; all vendors matching selection criteria returned without org-level restriction checks. No audit logging for sensitive fields (tax IDs, payment terms). Recommend adding BAPI\_USER\_GET\_DETAIL filtering for plant/purchasing org level restrictions if required.

## Upgrade

**S/4HANA Migration:** TABLES declarations are legacy syntax; replace with DATA and CDS views (I\_Supplier). KTOKK field may migrate in S/4HANA; verify in target system. Custom tables (ZVENDOR\_BLOCK, ZMM\_VENDOR\_MSME, ZMM\_VENDOR\_BEE) must be transported. CVI\_VEND\_LINK availability varies; use standard BP-vendor linking if unavailable. ALV framework compatible with S/4HANA on-premise; migrate to Fiori Elements for Cloud and future-proofing.

## Future Enhancements

Modernize to RAP/Fiori Elements (S/4HANA 2020+). Implement CDS views for performance optimization (50-70% query time reduction estimated). Add ALV-to-Excel export, PDF generation, scheduled email delivery. Dynamic field customization via ALV variants. Vendor risk scoring integration with supply chain risk management. Audit logging for SOX/GDPR compliance.

## Assumptions in Technical Design

*   Variant ZMM\_VEND\_ACC\_GROUP exists in TVARVC with at least one vendor account group code
*   Custom tables ZVENDOR\_BLOCK, ZMM\_VENDOR\_MSME, ZMM\_VENDOR\_BEE present; missing tables result in blank fields only
*   1:1 relationship assumed between vendor (LFA1) and BP (BUT000) via CVI\_VEND\_LINK
*   ALV output framework (CL\_SALV\_TABLE or REUSE\_ALV\_GRID\_DISPLAY) available and functional
*   VRM\_SET\_VALUES function module available for LISTBOX population (standard ECC 7.40+)
*   User has appropriate authorization (F\_LFA1\_BEK activity 03) to view vendor data
*   No database-level filtering; all matching records fetched and filtered at application layer post-SELECT

## Open Issues in Technical Design …

**Secondary Parameter Validation Logic:** LOOP AT SCREEN contains 5 nested IF conditions—repetitive and error-prone; refactor into single subroutine. **Null Handling:** Missing related records result in blank fields; clarify expected user behavior. **Performance Risk:** FOR ALL ENTRIES pattern with 11 SELECTs may degrade for >10,000 vendors; consider CDS view or pagination. **Group Vendor Cardinality:** Confirm 1:1 relationship to BUT050 is enforced or handled correctly for multi-group vendors. **Email Truncation Risk:** ADR6-SMTP\_ADDR length verification needed. **Blacklist Derivation:** Source code truncated; clarify ZVENDOR\_BLOCK vs. LFA1 field logic. **Hardcoded Mappings:** Parameter value conversions ('1'→'ACTIVE') should be externalized to configuration table.

## Unit Test Plan…

Scenario #

Input Selection Criteria

Expected Result

TC-1

All filters empty

Load ZMM\_VEND\_ACC\_GROUP from TVARVC; display all vendors in those account groups with consolidated data

TC-2

s\_ktokk = 'ZHYD'

Display only ZHYD vendors; count matches SELECT result

TC-3

s\_erdat = '20240101' to '20240630'

Display vendors created Jan-Jun 2024

TC-4

p\_status = 'ACTIVE'

Display only active vendors (no SPERR/SPERM/SPERQ flags)

TC-5

p\_black = 'Yes'

Display only blacklisted vendors from ZVENDOR\_BLOCK

TC-6

p\_status = 'ACTIVE' AND p\_black = 'Yes'

Error "Please select only one input"; fields disabled

TC-7

s\_ktokk = 'ZXXXX' (non-existent)

Execute without error; display zero rows

TC-8

ZMM\_VEND\_ACC\_GROUP variant missing

Error "No data available in ZMM\_VEND\_ACC\_GROUP variant"; terminate

TC-9

Vendor with missing ADRC/ADR6/MSME records

Display vendor with blank address, email, MSME cert fields

TC-10

s\_lifnr = '1001'

Display only vendor 1001 with consolidated attributes

## Related Documentation (attach OSS notes, emails, download of existing report, etc)

Charm Requests: 4000004597, 4000005275, 4000005596, 4000005680, 4000006028, 4000006474, 4000008627. Transport Requests: WS1K997027, WS1K9A014E, WS1K9A02YZ, WS1K9A03GW, WS1K9A04RP, WS1K9A05EB–WS1K9A09D0, WS1K9A0HO1. Variant: TVARVC.ZMM\_VEND\_ACC\_GROUP. Custom Tables: ZVENDOR\_BLOCK, ZMM\_VENDOR\_MSME, ZMM\_VENDOR\_BEE. Related Transactions: FK03, XK03, FK04, FK02. ALV Framework: CL\_SALV\_TABLE or REUSE\_ALV\_GRID\_DISPLAY.

**Technical Specification Generated:** 2026-04-28

**System:** ECC 7.40, Kernel 753, Client 800

**Program Version:** 6.0 (BEE\_Level field, 02/05/2025)

_Specification derived from direct source code analysis. Review and validate all open issues and recommendations before implementation._

### �Process Owner and Phone Number

_Not applicable — section not populated by generator._

## Open Issues in Technical Design �

_Not applicable — section not populated by generator._

## Unit Test Plan�

_Not applicable — section not populated by generator._

**C16 — AI-Powered SAP Analysis**  
_Generated by C16. This document is AI-generated and should be validated by a qualified SAP consultant before implementation. All data sourced from the connected SAP system._