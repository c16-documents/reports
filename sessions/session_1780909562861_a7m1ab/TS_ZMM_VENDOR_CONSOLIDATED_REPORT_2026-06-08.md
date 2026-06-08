  GDC Technical Specification - ZMM\_VENDOR\_CONSOLIDATED\_REPORT :root { --primary: #003366; --accent: #7FB3E0; --ink: #2c3e50; --bg: #f8f9fa; } \* { box-sizing: border-box; margin: 0; padding: 0; } body { font-family: 'Segoe UI', Arial, sans-serif; color: var(--ink); background: var(--bg); line-height: 1.6; } .doc-wrapper { max-width: 900px; margin: 0 auto; background: #fff; box-shadow: 0 2px 20px rgba(0,0,0,0.1); } .header-banner { background: linear-gradient(135deg, var(--primary), #004080); color: #fff; padding: 30px 40px; text-align: center; } .header-banner h1 { font-size: 1.8em; margin-bottom: 8px; } .header-banner .subtitle { font-size: 1.1em; opacity: 0.9; } .content { padding: 40px; } h2 { color: var(--primary); font-size: 1.3em; margin: 30px 0 15px 0; padding-bottom: 8px; border-bottom: 3px solid var(--accent); } h2:first-of-type { margin-top: 0; } p { margin-bottom: 12px; } table { width: 100%; border-collapse: collapse; margin: 15px 0; font-size: 0.9em; } table th, table td { border: 1px solid #ddd; padding: 10px 12px; text-align: left; } table th { background: var(--primary); color: #fff; font-weight: 600; } table tr:nth-child(even) { background: #f8fafc; } table tr:hover { background: #edf2f7; } .data-table th { width: 35%; background: #e8f4fc; color: var(--ink); font-weight: 600; } .data-table td { width: 65%; } .grid-table { margin: 15px 0; } .grid-table td { padding: 8px 12px; border: 1px solid #ddd; } .grid-table .label { background: #f0f4f8; font-weight: 500; width: 25%; } .grid-table .value { width: 25%; } .flow-diagram { background: #f8f9fa; border: 1px solid #e2e8f0; border-radius: 8px; padding: 20px; margin: 15px 0; text-align: center; } .flow-box { display: inline-block; background: var(--primary); color: #fff; padding: 10px 20px; border-radius: 6px; margin: 5px 10px; font-size: 0.85em; } .flow-arrow { display: inline-block; color: var(--accent); font-size: 1.5em; vertical-align: middle; } pre { background: #f5f5f5; border-left: 4px solid var(--accent); padding: 15px; overflow-x: auto; font-family: 'Consolas', monospace; font-size: 0.85em; margin: 15px 0; border-radius: 0 8px 8px 0; } ul, ol { margin: 15px 0 15px 25px; } li { margin-bottom: 6px; } .footer { background: #f8f9fa; padding: 20px 40px; text-align: center; font-size: 0.85em; color: #666; border-top: 1px solid #e2e8f0; } .badge { display: inline-block; padding: 3px 10px; border-radius: 12px; font-size: 0.8em; font-weight: 500; } .badge-complex { background: #e74c3c; color: #fff; } .badge-mm { background: var(--primary); color: #fff; } @media print { .doc-wrapper { box-shadow: none; } h2 { page-break-after: avoid; } table { page-break-inside: avoid; } } :root{--c16-purple-1:#003366;--c16-purple-2:#7FB3E0;--c16-primary:#003366;--c16-secondary:#7FB3E0;--c16-ink:#1f2937;--c16-sub:#4b5563;--c16-rule:#e5e7eb;--c16-accent:#faf5ff;}@page { size: A4; margin: 20mm 18mm 20mm 18mm; } \*, \*::before, \*::after { box-sizing: border-box; margin: 0; padding: 0; } body { font-family: 'Segoe UI', Calibri, Arial, sans-serif; font-size: 10.5pt; line-height: 1.55; color: #1f2937; background: #f4f5f6; -webkit-print-color-adjust: exact; print-color-adjust: exact; } .doc-wrapper { max-width: 1000px; margin: 24px auto; background: #ffffff; box-shadow: 0 1px 8px rgba(0,0,0,0.08); border-radius: 14px; overflow: hidden; } /\* ── Header ─────────────────────────────────────────────── \*/ .doc-header { background: #003366; color: #ffffff; padding: 28px 36px 24px 36px; border-bottom: 4px solid #7FB3E0; } .doc-header-top { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 14px; } .doc-header h1 { font-size: 20pt; font-weight: 600; letter-spacing: -0.3px; margin: 0 0 4px 0; line-height: 1.2; color: #ffffff; } .doc-header .doc-subtitle { font-size: 10.5pt; color: #7FB3E0; font-weight: 400; } .doc-classification { font-size: 8.5pt; letter-spacing: 1.2px; text-transform: uppercase; padding: 3px 12px; border-radius: 2px; border: 1px solid #7FB3E0; background: transparent; color: #7FB3E0; } /\* ── Meta strip ─────────────────────────────────────────── \*/ .doc-meta { padding: 16px 36px; background: #faf5ff; border-bottom: 1px solid #e5e7eb; font-size: 9.5pt; color: #4b5563; } .doc-meta table { width: 100%; border-collapse: collapse; } .doc-meta td { padding: 3px 12px 3px 0; vertical-align: top; } .doc-meta .meta-label { font-weight: 600; color: #003366; white-space: nowrap; width: 120px; } .doc-meta .meta-value { color: #1f2937; } /\* ── Body ──────────────────────────────────────────────── \*/ .doc-body { padding: 24px 36px; } .doc-body h2 { font-size: 14pt; font-weight: 600; color: #003366; border-bottom: 2px solid #003366; padding-bottom: 6px; margin: 32px 0 16px 0; page-break-after: avoid; } .doc-body h2:first-child { margin-top: 0; } .doc-body h2 .sec-num { display: inline-block; background: #003366; color: #FFFFFF; font-size: 10pt; width: 26px; height: 26px; line-height: 26px; text-align: center; border-radius: 3px; margin-right: 10px; vertical-align: middle; } .doc-body h3 { font-size: 11.5pt; font-weight: 600; color: #003366; margin: 22px 0 10px 0; padding-bottom: 4px; border-bottom: 1px solid #e5e7eb; } .doc-body h4 { font-size: 10.5pt; font-weight: 600; color: #1f2937; margin: 16px 0 8px 0; } .doc-body p { color: #4b5563; margin: 8px 0; } /\* ── KPI table (4 columns of big numbers) ────────────────── \*/ .kpi-table { width: 100%; border-collapse: collapse; margin: 16px 0 20px 0; page-break-inside: avoid; } .kpi-table td { width: 25%; text-align: center; padding: 14px 8px; border: 1px solid #D0D4D8; background: #F7F8FA; vertical-align: top; } .kpi-value { font-size: 22pt; font-weight: 700; color: #003366; display: block; line-height: 1.1; } .kpi-label { font-size: 8.5pt; color: #4b5563; text-transform: uppercase; letter-spacing: 0.5px; display: block; margin-top: 4px; } /\* ── Data tables ─────────────────────────────────────────── \*/ table.data-table { width: 100%; border-collapse: collapse; margin: 12px 0 20px 0; font-size: 9.5pt; page-break-inside: avoid; } table.data-table thead th { background: #003366; color: #FFFFFF; font-weight: 600; font-size: 9pt; text-transform: uppercase; letter-spacing: 0.3px; padding: 8px 10px; text-align: left; border: 1px solid #003366; } table.data-table tbody td { padding: 7px 10px; border: 1px solid #e5e7eb; vertical-align: top; } table.data-table tbody tr:nth-child(even) { background: #F7F8FA; } table.data-table tbody tr:hover { background: #edf1f5; } /\* ── Severity / level classes ────────────────────────────── \*/ .sev-critical { color: #b91c1c; font-weight: 600; } .sev-high { color: #C2410C; font-weight: 600; } .sev-medium { color: #a16207; font-weight: 600; } .sev-low { color: #15803D; font-weight: 600; } .level-a { color: #15803D; font-weight: 600; } .level-b { color: #1d4ed8; font-weight: 600; } .level-c { color: #C2410C; font-weight: 600; } .level-d { color: #b91c1c; font-weight: 600; } /\* ── Callouts ────────────────────────────────────────────── \*/ .callout { border-left: 4px solid #003366; background: #F0F4F8; padding: 12px 16px; margin: 14px 0; font-size: 10.5pt; } .callout.callout-warn { border-left-color: #C2410C; background: #FEF3EE; } .callout.callout-success { border-left-color: #15803D; background: #F0FDF4; } .callout.callout-crit { border-left-color: #b91c1c; background: #fdecea; } .callout .callout-title { font-weight: 700; color: #003366; margin-bottom: 4px; font-size: 10.5pt; } .callout.callout-warn .callout-title { color: #C2410C; } .callout.callout-success .callout-title { color: #15803D; } .callout.callout-crit .callout-title { color: #b91c1c; } /\* ── Collapsibles ────────────────────────────────────────── \*/ details { margin: 12px 0; border: 1px solid #e5e7eb; border-radius: 3px; background: #ffffff; } details summary { padding: 10px 14px; background: #faf5ff; font-weight: 600; font-size: 10.5pt; color: #003366; cursor: pointer; border-bottom: 1px solid #e5e7eb; list-style: none; } details summary::-webkit-details-marker { display: none; } details summary::before { content: "\\25B6\\00a0\\00a0"; font-size: 8pt; color: #003366; } details\[open\] summary::before { content: "\\25BC\\00a0\\00a0"; } details\[open\] summary { background: #e2e8f0; } details > div, details > p { padding: 12px 14px; } /\* ── Code / pre ──────────────────────────────────────────── \*/ pre { background: #f5f5f5; border: 1px solid #e5e7eb; border-left: 3px solid #003366; padding: 10px 14px; font-family: 'JetBrains Mono',monospace; font-size: 9pt; overflow-x: auto; margin: 10px 0; line-height: 1.45; } code { font-family: 'JetBrains Mono',monospace; font-size: 9pt; background: #f0f0f0; padding: 1px 4px; border-radius: 2px; } /\* ── TOC ─────────────────────────────────────────────────── \*/ .toc { background: #faf5ff; border: 1px solid #e5e7eb; border-radius: 8px; padding: 16px 24px; margin: 24px 0; } .toc ul { list-style: none; padding-left: 0; margin: 8px 0 0; } .toc a { color: #003366; text-decoration: none; } .toc a:hover { text-decoration: underline; } .toc .toc-num { display: inline-block; width: 26px; height: 20px; line-height: 20px; text-align: center; background: #003366; color: #fff; border-radius: 3px; font-size: 8pt; margin-right: 8px; } /\* ── Footer ──────────────────────────────────────────────── \*/ .doc-footer { background: #F7F8FA; color: #666666; border-top: 2px solid #003366; padding: 14px 36px; font-size: 8.5pt; } .footer-brand { font-weight: 700; color: #003366; } /\* ── Print refinements ────────────────────────────────────── \*/ @media print { body { background: #fff; font-size: 10pt; } .doc-wrapper { box-shadow: none; border: 0; margin: 0; max-width: 100%; } .doc-header { border-radius: 0; } .doc-body h2 { page-break-after: avoid; } details summary { background: #eee; } .toc { display: block; page-break-after: always; } }

![C16](data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAMCAgMCAgMDAwMEAwMEBQgFBQQEBQoHBwYIDAoMDAsKCwsNDhIQDQ4RDgsLEBYQERMUFRUVDA8XGBYUGBIUFRT/2wBDAQMEBAUEBQkFBQkUDQsNFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBT/wAARCAAZAGQDASIAAhEBAxEB/8QAHAABAAICAwEAAAAAAAAAAAAAAAQHBggBAgUJ/8QAKRAAAQMEAAYCAgMBAAAAAAAAAQIDBAAFBhEHCBITITEUQSJRCRVhMv/EABcBAQEBAQAAAAAAAAAAAAAAAAACAQP/xAAeEQADAQACAgMAAAAAAAAAAAAAAQIRAxIxYRNR4f/aAAwDAQACEQMRAD8A+ntKUoBUG/XdvH7Hcbo6xIlNQYzspbERouvOBCCopbQPKlHWgPs6qd6qtMv4ux5sfNcdwGXEyLiJYY6e7ZW9rVGccTtHd9JH47IHV5Oh7NXEO6Uoi6US6Zk3DXO4vE7ArHlcKBcLXEu0YSmod1Y7ElpJJGlo2dHxsedEEEe6yRSghJUohKQNkk6AH2TVM8OOLz+JYLiUXi2/GxHJ7tMFrt7ExJaM1ZOmUgDqCXCNbSSNePXVWJ/yKXq+WLlLzF2xrdZcecixJjrJIUiK48lLvkegdhJ/xR/ddb4XPL8fvPtfpEcivjV+t9livczXC2Ow/KczW2otrDyo7l2Id/r0up9o+X0dnq2NaC978e6sqNJamR2n2HEusuoS424k+FJI2CP8IINU1wYwzFsv5P8ADsWeZYexS6YjHjSGUFIQUORx3VfoKCytXV9KG/qqj5oc6y3h3n3L7a8XziSjEciv8KG5GhIaSX47XxwOqQj8nUOJcJI8JOx7GqlQqrrJXZpazbPIsltGIWeRdr7dIdmtccbemz30sstj62pRA8/Q9n6rjGslt2X2WPdrTIMq3yOrtPFpbXWASNhK0pOvHg60R5GxWm3FqTf+Kv8AIljODfLhRbTjFhVerWxdYq5UT5qmyflFgLR3VoKkhO1AJ7ZI87BtXk/5i8i45sZ5Z8vgQY+S4deDa5My1pWmLLG3EpWlKyopO2l7GyNFJ8eRW1xZPYK9eGw9KUrgdBSlKAUpSgFQIeP2u3XSfcotthxrjcOgzJjMdCHpPQNI7iwNr6R4GydVPpQEC64/a76uEu5WyHcFwX0yoqpcdDpjvJBCXG+oHpWNnSho+a7Xuy2/JLPNtV1hMXG2TWVR5MSSgLaebUNKSpJ9giptK3QUnjXKPhmJW1djt10ypvDVrUs4i5fXl2vSiSpvtn8y2STtvr6VbIIIJ36nE3lmw/i3kNjvN/kXz5NhdS/aGoF0XFZt7ienS2UIACTtCD9+v14q2KVXet3Seq8Fc5bwGxrMMixzJZDtzg5fYGFRoOSW+X2p/aUkpW24rpKXUq6lEhaSNkka3XpcKOD2K8Fcdes2KW4w2JMhcyXIfeU/JmSF/wDbzzqiVLUf2fA9ACs0pWdm1mm4vIpSlSaKUpQH/9k=)

Your Autonomous SAP Team

# GDC Technical Specification

ZMM\_VENDOR\_CONSOLIDATED\_REPORT — Vendor Consolidated Report

MM Module Complex

## Purpose of the document

The purpose of this document is to document the technical specification for the custom ABAP report **ZMM\_VENDOR\_CONSOLIDATED\_REPORT**, a comprehensive vendor master data extraction and analysis tool. This program consolidates vendor information from multiple SAP tables including LFA1, LFB1, LFM1, ADRC, ADR6, ADRCT, and custom Z-tables (ZVENDOR\_BLOCK, ZMM\_VENDOR\_MSME, ZMM\_VENDOR\_BEE) to provide a unified view of vendor data including contact details, payment terms, risk categorization, blacklist status, MSME certification, and BEE compliance levels.

This document, once approved by the appropriate authorities as mentioned in section "Document Control," forms the official documentation of the technical solution and is the basis for further maintenance.

## Revision History

Version

Date

Author

Derivation/Comments

1.0

2024-04-02

Ragunath Loganathan (RA20350211)

Initial creation - Added MSME Certificate Number field

2.0

2024-05-21

Polabathina Bhavani (PO20312220)

Added Group Customer field functionality

3.0

2024-06-24

Polabathina Bhavani (PO20312220)

Removed unwanted code, error corrections

4.0

2024-07-03

Polabathina Bhavani (PO20312220)

Production issue fix - data not fetching

5.0

2024-10-11

Polabathina Bhavani (PO20312220)

Added secondary input fields, 24 vendor account groups filter, blacklisted vendor logic

6.0

2025-05-02

Jeevan Sagar (IN20546163)

Added BEE\_Level field for BEE compliance tracking

## Review History

Version

Date

Reviewer

Remarks

1.0

2024-04-02

Jasmin

Functional review completed

2.0

2024-05-21

Manoranjan

Group Customer requirement review

5.0

2024-10-11

Manoranjan

Secondary fields enhancement review

6.0

2025-05-02

Bijay

BEE Level field requirement review

## Approval History

Version

Date

Approver

Remarks

1.0

2024-04-02

Jasmin

Initial approval - Charm No. 4000004597

2.0

2024-05-21

Manoranjan

Approved - Charm No. 4000005275

5.0

2024-10-11

Manoranjan

Approved - Charm No. 4000006028, 4000006474

6.0

2025-05-02

Bijay

Approved - Charm No. 4000008627

## This document is effective from the Approval date

This technical specification is effective from **2025-05-02** (Version 6.0 approval date). All development and maintenance activities shall be performed in accordance with this document.

## Object Overview

**Object ID**

ZMM\_VENDOR\_CONSOLIDATED\_REPORT

**Business Process**

Vendor Master Data Management / Procurement Reporting

**Object Title**

Vendor Consolidated Report

**Object Description**

Comprehensive vendor master data extraction report that consolidates vendor information from multiple SAP tables including general data, addresses, contact details, payment terms, risk categorization, blacklist status, MSME certification, and BEE compliance levels. Provides flexible selection criteria with status filters and secondary input fields.

**SAP Release**

ECC 7.40

**SAP Module**

MM (Materials Management)

**Cycle of Testing**

C1 / C2 / C3 / C4

**Required Development Completion Date**

2025-05-02

**Complexity of Object**

Complex

**Transaction run**

Real-time

**Type of Enhancement**

Custom Report Program

**Priority**

High

**Similar SAP Transaction**

XK03, MK03

**Similar SAP Program**

RFLVEND01

## TS Control

**TS Author and Phone Number**

Jeevan Sagar (IN20546163)

**Process Owner and Phone Number**

Bijay

**TS Approved By**

Bijay

**TS Approval date**

2025-05-02

**Other Contact and Phone Number**

Polabathina Bhavani (PO20312220)

**Other Contact and Phone Number**

Manoranjan

## Program Attributes

**Enhancement Type Selection:**

Enhancement Object

Not applicable

Function Exit

Not applicable

Include

Not applicable

Screen Exit

Not applicable

Menu Exit

Not applicable

Badi

Not applicable

New Transaction

To be created via SE93

Search Help

Standard vendor search help (KRED)

Area Menu

Not applicable

Custom Dialog Screens

Selection Screen only

Index

Not applicable

**Technical Identifiers:**

Transaction Code

To be assigned (recommended: ZMM\_VCR)

Message Class

Standard messages / Inline messages

**SAP Tables Read:**

SAP Tables Read

**LFA1** - Vendor Master (General Data)  
**LFB1** - Vendor Master (Company Code Data)  
**LFM1** - Vendor Master (Purchasing Organization Data)  
**ADRC** - Address Data (Central Address)  
**ADR6** - Email Addresses  
**ADRCT** - Address Communication Remarks (SPOC)  
**BUT000** - Business Partner General Data  
**BUT050** - Business Partner Relationships (Group Vendor)  
**CVI\_VEND\_LINK** - Vendor to Business Partner Link  
**TVARVC** - Variant Configuration (ZMM\_VEND\_ACC\_GROUP)

Custom Tables

**ZVENDOR\_BLOCK** - Vendor Blacklist Status  
**ZMM\_VENDOR\_MSME** - MSME Certification Data  
**ZMM\_VENDOR\_BEE** - BEE Compliance Level Data

## Technical Flow Diagram

Selection Screen Input

→

Input Validation

→

TVARVC Lookup (Account Groups)

  
  
↓  
  

LFA1 Data Fetch

→

CVI\_VEND\_LINK / BUT000 / BUT050

→

ADRC / ADR6 / ADRCT

  
  
↓  
  

LFB1 / LFM1

→

Z-Tables (Block/MSME/BEE)

→

Build Final Table

  
  
↓  
  

Apply Filters (Status/Blacklist)

→

Build Field Catalog

→

REUSE\_ALV\_GRID\_DISPLAY

## Processing Logic

**1\. AT SELECTION-SCREEN OUTPUT Event:**

*   Initialize dropdown list boxes for secondary filter parameters using VRM\_SET\_VALUES function module
*   Populate P\_STATUS with ACTIVE/INACTIVE options
*   Populate P\_BLACK, P\_BEGRU, P\_BEGRU1, P\_BRSCH with YES/NO options

**2\. START-OF-SELECTION Event - Input Validation:**

*   Validate that only one secondary filter (P\_STATUS, P\_BLACK, P\_BEGRU, P\_BEGRU1, P\_BRSCH) is selected at a time
*   Display error message if multiple secondary filters are selected simultaneously
*   Convert selection values from key codes to descriptive text (1→ACTIVE, 2→INACTIVE, etc.)

**3\. Data Selection Logic:**

\* If no primary selection criteria provided, load vendor account groups from TVARVC
IF s\_ktokk IS INITIAL AND s\_erdat IS INITIAL AND s\_gvend IS INITIAL 
  AND s\_lifnr IS INITIAL AND all secondary filters are initial.
  SELECT low FROM tvarvc INTO s\_ktokk WHERE name = 'ZMM\_VEND\_ACC\_GROUP'.
ENDIF.

\* Primary data fetch from LFA1 based on criteria
SELECT lifnr, adrnr, name1, ort01, ktokk, erdat, ernam...
  FROM lfa1 INTO lt\_lfa1
  WHERE criteria matches selection screen inputs.

\* Fetch related data using FOR ALL ENTRIES pattern
- CVI\_VEND\_LINK: Get Partner GUID for vendors
- BUT000: Get Business Partner numbers
- BUT050: Get Group Vendor relationships
- ADRC: Get address details (street, city, postal code, region)
- LFB1: Get payment terms (ZTERM)
- LFM1: Get currency (WAERS)
- ADR6: Get email addresses (SMTP\_ADDR)
- ADRCT: Get Wipro SPOC remarks
- ZVENDOR\_BLOCK: Get blacklist status (VFLAG)
- ZMM\_VENDOR\_MSME: Get MSME certificate numbers
- ZMM\_VENDOR\_BEE: Get BEE compliance levels
  

**4\. Data Processing - Build Final Internal Table:**

*   Loop through LFA1 data and populate LS\_FINAL structure
*   Read related tables using binary search (tables are pre-sorted by key)
*   Determine vendor status (ACTIVE/INACTIVE) based on blocking flags (SPERR, SPERM, SPERQ)
*   Determine blacklist status from ZVENDOR\_BLOCK table
*   Append to final table LT\_FINAL

**5\. Secondary Filter Application:**

*   If P\_STATUS is provided: Delete records not matching status (ACTIVE/INACTIVE)
*   If P\_BLACK is provided: Delete records not matching blacklist status
*   If P\_BEGRU is provided: Filter based on authorization group field
*   If P\_BEGRU1 is provided: Filter based on secondary authorization group
*   If P\_BRSCH is provided: Filter based on industry sector

**6\. Output Display:**

*   Build field catalog dynamically using LAYOUT\_BUILD subroutine
*   Display output using REUSE\_ALV\_GRID\_DISPLAY function module

## Reusable Code

The following function modules are used that can be reused across similar reports:

Function Module

Purpose

VRM\_SET\_VALUES

Set values for dropdown list boxes on selection screen

REUSE\_ALV\_FIELDCATALOG\_MERGE

Merge field catalog for ALV display

REUSE\_ALV\_GRID\_DISPLAY

Display ALV grid output

## Internal Tables

Name

Description

LT\_FINAL

Final output table containing consolidated vendor data (TYPE TABLE OF TY\_FINAL)

LT\_LFA1

Vendor master general data from LFA1

LT\_PARTNER\_GUID

Vendor to Business Partner link from CVI\_VEND\_LINK

LT\_PARTNER

Business Partner data from BUT000

LT\_GROUP\_VENDOR

Group vendor relationships from BUT050

LT\_ADRC

Address central data from ADRC

LT\_ZTERM

Payment terms from LFB1

LT\_WAERS

Currency from LFM1

LT\_ADR6

Email addresses from ADR6

LT\_ADRCT

SPOC remarks from ADRCT

LT\_ZVENDOR\_BLOCK1

Blacklist status from ZVENDOR\_BLOCK

LT\_ZMM\_VENDOR\_MSME

MSME certificate numbers from ZMM\_VENDOR\_MSME

LT\_ZMM\_VENDOR\_BEE

BEE compliance levels from ZMM\_VENDOR\_BEE

LT\_FCAT

Field catalog for ALV display (TYPE SLIS\_T\_FIELDCAT\_ALV)

LIST

Dropdown values for VRM listboxes (TYPE VRM\_VALUES)

## Messages

Message Class

Message ID

Message Text

Inline

E

Please select only one input from last 5 secondary fields

Inline

E

No data available in ZMM\_VEND\_ACC\_GROUP variant

Inline

S

No data found for the given selection criteria

## Text Elements

Name

Text Description

TEXT-000

Selection Parameters (Selection screen block title)

S\_KTOKK

Vendor Account Group

S\_ERDAT

Creation Date

S\_GVEND

Group Vendor

S\_LIFNR

Vendor Number

P\_STATUS

Status (Active/Inactive)

P\_BLACK

Blacklisted

P\_BEGRU

Authorization Group 1

P\_BEGRU1

Authorization Group 2

P\_BRSCH

Industry Sector

## Subroutines

Name

Description

LAYOUT\_BUILD

Builds the ALV field catalog dynamically. Sets field positions, column headers, and display properties for all output fields including vendor number, name, address, contact details, payment terms, risk codes, MSME certificate, BEE level, and status flags.

## Security

**Authorization Requirements:**

*   **F\_LFA1\_BEK** - Authorization object for vendor master display (Activity 03)
*   **F\_LFA1\_GRP** - Authorization object for vendor account groups
*   **S\_TCODE** - Transaction code authorization (if transaction code assigned)

**Note:** The report currently does not implement explicit AUTHORITY-CHECK statements. It is recommended to add authorization checks for:

*   Vendor account group access (KTOKK)
*   Company code access for LFB1 data
*   Authorization group field (BEGRU) restrictions

## Upgrade

**S/4HANA Migration Considerations:**

*   **TABLES Declaration:** The program uses TABLES declarations for LFA1, ADRC, ADR6, ADRCT, LFB1, LFM1, BUT050. These should be replaced with explicit type declarations for S/4HANA compatibility.
*   **TYPE-POOLS: VRM** - Deprecated in newer releases. Consider using class-based dropdown handling.
*   **Business Partner Migration:** In S/4HANA, vendor data is primarily managed via Business Partner (BP). The CVI\_VEND\_LINK and BUT000/BUT050 tables remain compatible.
*   **Custom Z-Tables:** ZVENDOR\_BLOCK, ZMM\_VENDOR\_MSME, ZMM\_VENDOR\_BEE need to be migrated with the report. Consider creating CDS views for these tables.
*   **REUSE\_ALV\_GRID\_DISPLAY:** Level B compatibility (works in S/4HANA on-premise). For ABAP Cloud/BTP, migrate to CL\_SALV\_TABLE or RAP-based Fiori app.

## Future Enhancements

*   **Modernization to CL\_SALV\_TABLE:** Replace REUSE\_ALV\_GRID\_DISPLAY with object-oriented ALV (CL\_SALV\_TABLE) for better maintainability
*   **CDS View Layer:** Create CDS views to consolidate vendor data at database level, reducing ABAP processing
*   **Fiori App Migration:** Develop a Fiori List Report app with filter bar and export capabilities
*   **Performance Optimization:** Implement parallel processing for large vendor volumes
*   **Additional Fields:** Consider adding vendor banking details, tax exemption status, and supplier evaluation scores
*   **Excel Export:** Add native Excel download functionality using CL\_SALV\_TABLE export methods

## Assumptions in Technical Design

*   The TVARVC variant ZMM\_VEND\_ACC\_GROUP contains the list of valid vendor account groups to be included in the report when no explicit selection is made
*   Vendor status (ACTIVE/INACTIVE) is determined by the combination of blocking flags: SPERR (central), SPERM (purchasing), SPERQ (quality)
*   Blacklist status is maintained in custom table ZVENDOR\_BLOCK with field VFLAG
*   MSME certificate numbers are maintained in custom table ZMM\_VENDOR\_MSME
*   BEE compliance levels are maintained in custom table ZMM\_VENDOR\_BEE
*   Only one secondary filter can be applied at a time to ensure consistent result sets
*   Group vendor relationships are maintained in BUT050 table via Business Partner framework

## Open Issues in Technical Design

*   **Authorization Checks:** No explicit AUTHORITY-CHECK statements implemented - security risk for sensitive vendor data
*   **Error Handling:** Empty error handling blocks after VRM\_SET\_VALUES calls - should log errors
*   **Code Duplication:** Similar SELECT patterns repeated multiple times with slight variations - should be refactored into reusable methods
*   **Performance:** Multiple FOR ALL ENTRIES SELECT statements executed sequentially - consider optimizing with JOINs or parallel execution
*   **Hardcoded Values:** Selection screen validation logic contains hardcoded parameter names - should use constants

## Unit Test Plan

Scenario #

Input Selection Criteria

Expected Result

1

No selection criteria provided (all fields blank)

Report loads vendor account groups from TVARVC (ZMM\_VEND\_ACC\_GROUP) and displays all vendors matching those groups

2

S\_KTOKK = 'ZDOM' (single account group)

Only vendors with account group ZDOM are displayed

3

S\_ERDAT = 01.01.2024 to 31.12.2024

Only vendors created within the date range are displayed

4

P\_STATUS = 'ACTIVE'

Only active vendors (no blocking flags set) are displayed

5

P\_STATUS = 'INACTIVE'

Only inactive vendors (at least one blocking flag set) are displayed

6

P\_BLACK = 'YES'

Only blacklisted vendors (VFLAG = 'X' in ZVENDOR\_BLOCK) are displayed

7

P\_STATUS = 'ACTIVE' AND P\_BLACK = 'YES' (multiple secondary filters)

Error message: "Please select only one input from last 5 secondary fields"

8

S\_LIFNR = '0000001000' (specific vendor)

Only the specified vendor is displayed with all consolidated data including MSME cert, BEE level

9

S\_GVEND = '1234567890' (group vendor filter)

Only vendors belonging to the specified group vendor are displayed

10

S\_KTOKK = 'XXXX' (invalid/non-existent account group)

No data found message displayed, ALV grid empty

## Related Documentation (attach OSS notes, emails, download of existing report, etc)

*   **Charm No. 4000004597** - Initial MSME Certificate Number field requirement (Transport: WS1K997027)
*   **Charm No. 4000005275** - Group Customer field addition (Transport: WS1K9A014E)
*   **Charm No. 4000005596** - Code cleanup and error removal (Transport: WS1K9A02YZ)
*   **Charm No. 4000005680** - Production data fetch issue fix (Transports: WS1K9A03GW, WS1K9A04RP)
*   **Charm No. 4000006028, 4000006474** - Secondary input fields and account group filter (Transports: WS1K9A05EB, WS1K9A06LT, WS1K9A07DO, WS1K9A08IU, WS1K9A09D0)
*   **Charm No. 4000008627** - BEE Level field addition (Transport: WS1K9A0HO1)

**Document Control**

Generated by C16 — Your Autonomous SAP Team

Document Date: 2026-06-08 | System: ECC 7.40 | Client: 800