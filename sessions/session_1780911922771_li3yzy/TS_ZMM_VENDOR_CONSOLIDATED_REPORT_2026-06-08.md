  Technical Specification - ZMM\_VENDOR\_CONSOLIDATED\_REPORT :root { --primary: #003366; --accent: #7FB3E0; --success: #27ae60; --warning: #f39c12; --danger: #e74c3c; --light-bg: #f8f9fa; --border: #dee2e6; } \* { box-sizing: border-box; } body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.6; color: #2c3e50; background: #e9ecef; margin: 0; padding: 20px; } .doc-wrapper { max-width: 1100px; margin: 0 auto; background: #fff; box-shadow: 0 4px 20px rgba(0,0,0,0.12); border-radius: 8px; overflow: hidden; } .header-banner { background: linear-gradient(135deg, var(--primary) 0%, var(--accent) 100%); color: #fff; padding: 40px; text-align: center; } .header-banner h1 { margin: 15px 0 10px; font-size: 28px; font-weight: 600; } .header-banner .subtitle { font-size: 16px; opacity: 0.9; } .header-banner .doc-meta { margin-top: 20px; font-size: 14px; opacity: 0.85; } .content { padding: 40px; } h2 { color: var(--primary); border-bottom: 3px solid var(--accent); padding-bottom: 10px; margin: 40px 0 20px; font-size: 20px; } h2:first-of-type { margin-top: 0; } h3 { color: var(--primary); margin: 25px 0 15px; font-size: 16px; } table { width: 100%; border-collapse: collapse; margin: 15px 0 25px; font-size: 14px; } table th { background: var(--primary); color: #fff; padding: 12px 15px; text-align: left; font-weight: 600; } table td { padding: 10px 15px; border: 1px solid var(--border); } table tr:nth-child(even) { background: #f8fafc; } table tr:hover { background: #edf2f7; } .data-table th { background: var(--light-bg); color: var(--primary); font-weight: 600; width: 35%; border: 1px solid var(--border); } .data-table td { width: 65%; } .checkbox-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; margin: 15px 0; } .checkbox-item { display: flex; align-items: center; gap: 8px; padding: 8px 12px; background: var(--light-bg); border-radius: 4px; } .checkbox-item .box { width: 18px; height: 18px; border: 2px solid var(--border); border-radius: 3px; display: flex; align-items: center; justify-content: center; font-weight: bold; color: var(--success); } .checkbox-item.checked .box { background: var(--success); border-color: var(--success); color: #fff; } .info-box { background: #e8f4fd; border-left: 4px solid var(--accent); padding: 15px 20px; margin: 20px 0; border-radius: 0 4px 4px 0; } .flow-diagram { background: var(--light-bg); border: 1px solid var(--border); border-radius: 8px; padding: 30px; margin: 20px 0; text-align: center; } .flow-diagram img { max-width: 100%; height: auto; } pre { background: #f5f5f5; border-left: 4px solid var(--accent); padding: 15px; overflow-x: auto; font-family: 'Consolas', 'Monaco', monospace; font-size: 13px; line-height: 1.5; border-radius: 0 4px 4px 0; } code { background: #f0f0f0; padding: 2px 6px; border-radius: 3px; font-family: 'Consolas', 'Monaco', monospace; font-size: 13px; } .badge { display: inline-block; padding: 4px 12px; border-radius: 12px; font-size: 12px; font-weight: 600; } .badge-complex { background: var(--warning); color: #fff; } .badge-mm { background: var(--primary); color: #fff; } ul, ol { margin: 10px 0; padding-left: 25px; } li { margin: 8px 0; } .footer { background: var(--light-bg); padding: 20px 40px; border-top: 1px solid var(--border); font-size: 12px; color: #666; text-align: center; } @media print { body { background: #fff; padding: 0; } .doc-wrapper { box-shadow: none; } .header-banner { -webkit-print-color-adjust: exact; print-color-adjust: exact; } } :root{--c16-purple-1:#003366;--c16-purple-2:#7FB3E0;--c16-primary:#003366;--c16-secondary:#7FB3E0;--c16-ink:#1f2937;--c16-sub:#4b5563;--c16-rule:#e5e7eb;--c16-accent:#faf5ff;}@page { size: A4; margin: 20mm 18mm 20mm 18mm; } \*, \*::before, \*::after { box-sizing: border-box; margin: 0; padding: 0; } body { font-family: 'Segoe UI', Calibri, Arial, sans-serif; font-size: 10.5pt; line-height: 1.55; color: #1f2937; background: #f4f5f6; -webkit-print-color-adjust: exact; print-color-adjust: exact; } .doc-wrapper { max-width: 1000px; margin: 24px auto; background: #ffffff; box-shadow: 0 1px 8px rgba(0,0,0,0.08); border-radius: 14px; overflow: hidden; } /\* ── Header ─────────────────────────────────────────────── \*/ .doc-header { background: #003366; color: #ffffff; padding: 28px 36px 24px 36px; border-bottom: 4px solid #7FB3E0; } .doc-header-top { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 14px; } .doc-header h1 { font-size: 20pt; font-weight: 600; letter-spacing: -0.3px; margin: 0 0 4px 0; line-height: 1.2; color: #ffffff; } .doc-header .doc-subtitle { font-size: 10.5pt; color: #7FB3E0; font-weight: 400; } .doc-classification { font-size: 8.5pt; letter-spacing: 1.2px; text-transform: uppercase; padding: 3px 12px; border-radius: 2px; border: 1px solid #7FB3E0; background: transparent; color: #7FB3E0; } /\* ── Meta strip ─────────────────────────────────────────── \*/ .doc-meta { padding: 16px 36px; background: #faf5ff; border-bottom: 1px solid #e5e7eb; font-size: 9.5pt; color: #4b5563; } .doc-meta table { width: 100%; border-collapse: collapse; } .doc-meta td { padding: 3px 12px 3px 0; vertical-align: top; } .doc-meta .meta-label { font-weight: 600; color: #003366; white-space: nowrap; width: 120px; } .doc-meta .meta-value { color: #1f2937; } /\* ── Body ──────────────────────────────────────────────── \*/ .doc-body { padding: 24px 36px; } .doc-body h2 { font-size: 14pt; font-weight: 600; color: #003366; border-bottom: 2px solid #003366; padding-bottom: 6px; margin: 32px 0 16px 0; page-break-after: avoid; } .doc-body h2:first-child { margin-top: 0; } .doc-body h2 .sec-num { display: inline-block; background: #003366; color: #FFFFFF; font-size: 10pt; width: 26px; height: 26px; line-height: 26px; text-align: center; border-radius: 3px; margin-right: 10px; vertical-align: middle; } .doc-body h3 { font-size: 11.5pt; font-weight: 600; color: #003366; margin: 22px 0 10px 0; padding-bottom: 4px; border-bottom: 1px solid #e5e7eb; } .doc-body h4 { font-size: 10.5pt; font-weight: 600; color: #1f2937; margin: 16px 0 8px 0; } .doc-body p { color: #4b5563; margin: 8px 0; } /\* ── KPI table (4 columns of big numbers) ────────────────── \*/ .kpi-table { width: 100%; border-collapse: collapse; margin: 16px 0 20px 0; page-break-inside: avoid; } .kpi-table td { width: 25%; text-align: center; padding: 14px 8px; border: 1px solid #D0D4D8; background: #F7F8FA; vertical-align: top; } .kpi-value { font-size: 22pt; font-weight: 700; color: #003366; display: block; line-height: 1.1; } .kpi-label { font-size: 8.5pt; color: #4b5563; text-transform: uppercase; letter-spacing: 0.5px; display: block; margin-top: 4px; } /\* ── Data tables ─────────────────────────────────────────── \*/ table.data-table { width: 100%; border-collapse: collapse; margin: 12px 0 20px 0; font-size: 9.5pt; page-break-inside: avoid; } table.data-table thead th { background: #003366; color: #FFFFFF; font-weight: 600; font-size: 9pt; text-transform: uppercase; letter-spacing: 0.3px; padding: 8px 10px; text-align: left; border: 1px solid #003366; } table.data-table tbody td { padding: 7px 10px; border: 1px solid #e5e7eb; vertical-align: top; } table.data-table tbody tr:nth-child(even) { background: #F7F8FA; } table.data-table tbody tr:hover { background: #edf1f5; } /\* ── Severity / level classes ────────────────────────────── \*/ .sev-critical { color: #b91c1c; font-weight: 600; } .sev-high { color: #C2410C; font-weight: 600; } .sev-medium { color: #a16207; font-weight: 600; } .sev-low { color: #15803D; font-weight: 600; } .level-a { color: #15803D; font-weight: 600; } .level-b { color: #1d4ed8; font-weight: 600; } .level-c { color: #C2410C; font-weight: 600; } .level-d { color: #b91c1c; font-weight: 600; } /\* ── Callouts ────────────────────────────────────────────── \*/ .callout { border-left: 4px solid #003366; background: #F0F4F8; padding: 12px 16px; margin: 14px 0; font-size: 10.5pt; } .callout.callout-warn { border-left-color: #C2410C; background: #FEF3EE; } .callout.callout-success { border-left-color: #15803D; background: #F0FDF4; } .callout.callout-crit { border-left-color: #b91c1c; background: #fdecea; } .callout .callout-title { font-weight: 700; color: #003366; margin-bottom: 4px; font-size: 10.5pt; } .callout.callout-warn .callout-title { color: #C2410C; } .callout.callout-success .callout-title { color: #15803D; } .callout.callout-crit .callout-title { color: #b91c1c; } /\* ── Collapsibles ────────────────────────────────────────── \*/ details { margin: 12px 0; border: 1px solid #e5e7eb; border-radius: 3px; background: #ffffff; } details summary { padding: 10px 14px; background: #faf5ff; font-weight: 600; font-size: 10.5pt; color: #003366; cursor: pointer; border-bottom: 1px solid #e5e7eb; list-style: none; } details summary::-webkit-details-marker { display: none; } details summary::before { content: "\\25B6\\00a0\\00a0"; font-size: 8pt; color: #003366; } details\[open\] summary::before { content: "\\25BC\\00a0\\00a0"; } details\[open\] summary { background: #e2e8f0; } details > div, details > p { padding: 12px 14px; } /\* ── Code / pre ──────────────────────────────────────────── \*/ pre { background: #f5f5f5; border: 1px solid #e5e7eb; border-left: 3px solid #003366; padding: 10px 14px; font-family: 'JetBrains Mono',monospace; font-size: 9pt; overflow-x: auto; margin: 10px 0; line-height: 1.45; } code { font-family: 'JetBrains Mono',monospace; font-size: 9pt; background: #f0f0f0; padding: 1px 4px; border-radius: 2px; } /\* ── TOC ─────────────────────────────────────────────────── \*/ .toc { background: #faf5ff; border: 1px solid #e5e7eb; border-radius: 8px; padding: 16px 24px; margin: 24px 0; } .toc ul { list-style: none; padding-left: 0; margin: 8px 0 0; } .toc a { color: #003366; text-decoration: none; } .toc a:hover { text-decoration: underline; } .toc .toc-num { display: inline-block; width: 26px; height: 20px; line-height: 20px; text-align: center; background: #003366; color: #fff; border-radius: 3px; font-size: 8pt; margin-right: 8px; } /\* ── Footer ──────────────────────────────────────────────── \*/ .doc-footer { background: #F7F8FA; color: #666666; border-top: 2px solid #003366; padding: 14px 36px; font-size: 8.5pt; } .footer-brand { font-weight: 700; color: #003366; } /\* ── Print refinements ────────────────────────────────────── \*/ @media print { body { background: #fff; font-size: 10pt; } .doc-wrapper { box-shadow: none; border: 0; margin: 0; max-width: 100%; } .doc-header { border-radius: 0; } .doc-body h2 { page-break-after: avoid; } details summary { background: #eee; } .toc { display: block; page-break-after: always; } }

![C16](data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAMCAgMCAgMDAwMEAwMEBQgFBQQEBQoHBwYIDAoMDAsKCwsNDhIQDQ4RDgsLEBYQERMUFRUVDA8XGBYUGBIUFRT/2wBDAQMEBAUEBQkFBQkUDQsNFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBT/wAARCAAZAGQDASIAAhEBAxEB/8QAHAABAAICAwEAAAAAAAAAAAAAAAQHBggBAgUJ/8QAKRAAAQMEAAYCAgMBAAAAAAAAAQIDBAAFBhEHCBITITEUQSJRCRVhMv/EABcBAQEBAQAAAAAAAAAAAAAAAAACAQP/xAAeEQADAQACAgMAAAAAAAAAAAAAAQIRAxIxYRNR4f/aAAwDAQACEQMRAD8A+ntKUoBUG/XdvH7Hcbo6xIlNQYzspbERouvOBCCopbQPKlHWgPs6qd6qtMv4ux5sfNcdwGXEyLiJYY6e7ZW9rVGccTtHd9JH47IHV5Oh7NXEO6Uoi6US6Zk3DXO4vE7ArHlcKBcLXEu0YSmod1Y7ElpJJGlo2dHxsedEEEe6yRSghJUohKQNkk6AH2TVM8OOLz+JYLiUXi2/GxHJ7tMFrt7ExJaM1ZOmUgDqCXCNbSSNePXVWJ/yKXq+WLlLzF2xrdZcecixJjrJIUiK48lLvkegdhJ/xR/ddb4XPL8fvPtfpEcivjV+t9livczXC2Ow/KczW2otrDyo7l2Id/r0up9o+X0dnq2NaC978e6sqNJamR2n2HEusuoS424k+FJI2CP8IINU1wYwzFsv5P8ADsWeZYexS6YjHjSGUFIQUORx3VfoKCytXV9KG/qqj5oc6y3h3n3L7a8XziSjEciv8KG5GhIaSX47XxwOqQj8nUOJcJI8JOx7GqlQqrrJXZpazbPIsltGIWeRdr7dIdmtccbemz30sstj62pRA8/Q9n6rjGslt2X2WPdrTIMq3yOrtPFpbXWASNhK0pOvHg60R5GxWm3FqTf+Kv8AIljODfLhRbTjFhVerWxdYq5UT5qmyflFgLR3VoKkhO1AJ7ZI87BtXk/5i8i45sZ5Z8vgQY+S4deDa5My1pWmLLG3EpWlKyopO2l7GyNFJ8eRW1xZPYK9eGw9KUrgdBSlKAUpSgFQIeP2u3XSfcotthxrjcOgzJjMdCHpPQNI7iwNr6R4GydVPpQEC64/a76uEu5WyHcFwX0yoqpcdDpjvJBCXG+oHpWNnSho+a7Xuy2/JLPNtV1hMXG2TWVR5MSSgLaebUNKSpJ9giptK3QUnjXKPhmJW1djt10ypvDVrUs4i5fXl2vSiSpvtn8y2STtvr6VbIIIJ36nE3lmw/i3kNjvN/kXz5NhdS/aGoF0XFZt7ienS2UIACTtCD9+v14q2KVXet3Seq8Fc5bwGxrMMixzJZDtzg5fYGFRoOSW+X2p/aUkpW24rpKXUq6lEhaSNkka3XpcKOD2K8Fcdes2KW4w2JMhcyXIfeU/JmSF/wDbzzqiVLUf2fA9ACs0pWdm1mm4vIpSlSaKUpQH/9k=)

# GDC Technical Specification

ZMM\_VENDOR\_CONSOLIDATED\_REPORT

MM - Materials Management Complex

Document Version: 1.0 | Date: 2026-06-08

## Purpose of the document

The purpose of this document is to document the SAP ABAP custom report **ZMM\_VENDOR\_CONSOLIDATED\_REPORT** which provides a consolidated view of vendor master data across multiple SAP tables including LFA1, ADRC, ADR6, ADRCT, LFB1, LFM1, CVI\_VEND\_LINK, BUT000, BUT050, and custom tables ZVENDOR\_BLOCK and ZMM\_VENDOR\_MSME. This document once approved by the appropriate authorities as mentioned in section "Document Control" forms the official documentation of the technical solution and is the basis for further maintenance.

This report consolidates vendor information including general data, address details, company code data, purchasing organization data, group vendor relationships, blacklist status, MSME certification details, and BEE level classifications into a single ALV output for comprehensive vendor analysis and reporting purposes.

## Revision History

Version

Date

Author

Derivation/Comments

1.0

2024-03-24

VINOD

Initial creation of vendor consolidated report

1.1

2024-04-02

Ragunath Loganathan (RA20350211)

Added MSME Certificate Number field (Charm: 4000004597)

1.2

2024-05-21

Polabathina Bhavani (PO20312220)

Added Group Customer field (Charm: 4000005275)

1.3

2024-06-24

Polabathina Bhavani (PO20312220)

Removed unwanted code error (Charm: 4000005596)

1.4

2024-07-03

Polabathina Bhavani (PO20312220)

Production issue - data not fetching fix (Charm: 4000005680)

1.5

2024-09-03

Polabathina Bhavani (PO20312220)

Addition of secondary input fields, 24 vendor account groups filter, blacklisted vendors logic (Charm: 4000006028, 4000006474)

1.6

2025-05-02

Jeevan Sagar (IN20546163)

Added BEE\_Level field (Charm: 4000008627)

## Review History

Version

Date

Reviewer

Remarks

1.0

2024-03-24

Technical Lead

Initial technical review completed

1.5

2024-10-11

Manoranjan (Functional)

Reviewed secondary filter field requirements

1.6

2025-05-02

Bijay (Functional)

BEE Level field addition reviewed

## Approval History

Version

Date

Approver

Remarks

1.0

2024-03-24

Project Manager

Approved for development

1.6

2025-05-02

Project Manager

Approved with BEE Level enhancement

## This document is effective from the Approval date

This Technical Specification document becomes effective upon approval and serves as the authoritative reference for the ZMM\_VENDOR\_CONSOLIDATED\_REPORT program. All development, testing, and maintenance activities must be aligned with the specifications documented herein.

## Object Overview

Object ID

ZMM\_VENDOR\_CONSOLIDATED\_REPORT

Business Process

MM - Vendor Master Data Management and Reporting

Object Title

Vendor Consolidated Report

Object Description

A comprehensive ALV report that consolidates vendor master data from multiple SAP tables (LFA1, ADRC, ADR6, ADRCT, LFB1, LFM1) and custom tables (ZVENDOR\_BLOCK, ZMM\_VENDOR\_MSME, ZMM\_VENDOR\_BEE) along with Business Partner relationships (BUT000, BUT050, CVI\_VEND\_LINK) to provide a single view of vendor information including general data, addresses, contact information, payment terms, currencies, blacklist status, MSME certification, and BEE level classification.

SAP Release

ECC 7.40 (SAP\_BASIS 740, Kernel 753)

SAP Module

MM (Materials Management) - Vendor Master

Cycle of Testing

C3

Required Development Completion Date

2024-03-24

Complexity of Object

Complex

Transaction run

Real-time (Online Report)

Type of Enhancement

Custom Report with ALV Grid Display

Priority

High

Similar SAP Transaction

XK03 (Display Vendor), FK03 (Display Vendor FI), MK03 (Display Vendor MM)

Similar SAP Program

RFKEPL00 (Vendor List), RFLAT200 (Vendor Master Changes)

## TS Control

TS Author and Phone Number

C16 Technical Specification Generator

Process Owner and Phone Number

Manoranjan (Functional Consultant), Bijay (Functional Consultant)

TS Approved By

To be confirmed

TS Approval date

2026-06-08

Other Contact and Phone Number

Jasmin (Functional - MSME Requirements)

Developer Contact

Polabathina Bhavani (PO20312220), Ragunath Loganathan (RA20350211), Jeevan Sagar (IN20546163)

## Program Attributes

### Enhancement Type

Enhancement Object

Function Exit

Include

Screen Exit

Menu Exit

BAdI

X New Transaction

Search Help

Area Menu

Custom Dialog Screens

Index

### Transaction and Message Details

Transaction Code

To be assigned (recommend: ZMMVCR01)

Message Class

Standard messages via MESSAGE statement with inline text

### SAP Tables Read

Table

Description

Key Fields Used

LFA1

Vendor Master (General Section)

LIFNR, ADRNR, NAME1, KTOKK, ERDAT, SPERR, SPERM, SPERQ, BEGRU, BRSCH

ADRC

Address Repository

ADDRNUMBER, COUNTRY, STREET, STR\_SUPPL1-3, POST\_CODE1, REGION

ADR6

Email Addresses

ADDRNUMBER, SMTP\_ADDR

ADRCT

Address Remarks

ADDRNUMBER, REMARK (WIPRO SPOC ID)

LFB1

Vendor Master (Company Code)

LIFNR, ZTERM

LFM1

Vendor Master (Purchasing Organization)

LIFNR, WAERS

CVI\_VEND\_LINK

Vendor-BP Assignment

VENDOR, PARTNER\_GUID

BUT000

Business Partner General Data

PARTNER\_GUID, PARTNER

BUT050

BP Relationships

PARTNER1, PARTNER2 (Group Vendor)

KNA1

Customer Master (General)

KUNNR, KTOKD (for linked customers)

TVARVC

Table of Variants Variables

NAME = 'ZMM\_VEND\_ACC\_GROUP' (variant configuration)

### Custom Tables

Table

Description

Fields Used

ZVENDOR\_BLOCK

Vendor Blacklist Status

LIFNR, VFLAG

ZMM\_VENDOR\_MSME

Vendor MSME Certification

LIFNR, MSME\_CERT\_NUM

ZMM\_VENDOR\_BEE

Vendor BEE Level Classification

LIFNR, BEE\_LEVEL

## Technical Flow Diagram

┌─────────────────────────────────────────────────────────────────────────────┐
│  SELECTION SCREEN  │
│  ┌────────────────────────────────────────────────────────────────────────┐ │
│  │ Primary Filters:  │ │
│  │  S\_KTOKK (Vendor Account Group)  │ │
│  │  S\_ERDAT (Creation Date)  │ │
│  │  S\_GVEND (Group Vendor)  │ │
│  │  S\_LIFNR (Vendor Number)  │ │
│  │ Secondary Filters (mutually exclusive):  │ │
│  │  P\_STATUS (Active/Inactive)  │ │
│  │  P\_BLACK  (Blacklisted Yes/No)  │ │
│  │  P\_BEGRU  (Auth Group 1 Yes/No)  │ │
│  │  P\_BEGRU1 (Auth Group 2 Yes/No)  │ │
│  │  P\_BRSCH  (Industry Code Yes/No)  │ │
│  └────────────────────────────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────────────────────────┘
  │
  ▼
┌─────────────────────────────────────────────────────────────────────────────┐
│  AT SELECTION-SCREEN OUTPUT  │
│  ┌────────────────────────────────────────────────────────────────────────┐ │
│  │ VRM\_SET\_VALUES for dropdown listboxes:  │ │
│  │  P\_STATUS: ACTIVE / INACTIVE  │ │
│  │  P\_BLACK:  YES / NO  │ │
│  │  P\_BEGRU:  YES / NO  │ │
│  │  P\_BEGRU1: YES / NO  │ │
│  │  P\_BRSCH:  YES / NO  │ │
│  └────────────────────────────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────────────────────────┘
  │
  ▼
┌─────────────────────────────────────────────────────────────────────────────┐
│  START-OF-SELECTION  │
│  ┌────────────────────────────────────────────────────────────────────────┐ │
│  │ 1. Validate secondary filter mutual exclusivity  │ │
│  │ 2. Convert dropdown key values to text values  │ │
│  │ 3. If no filters: Load account groups from TVARVC ZMM\_VEND\_ACC\_GROUP  │ │
│  └────────────────────────────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────────────────────────┘
  │
  ▼
┌─────────────────────────────────────────────────────────────────────────────┐
│  DATA RETRIEVAL  │
│  ┌────────────────────────────────────────────────────────────────────────┐ │
│  │ SELECT from LFA1 (main vendor data)  │ │
│  │  ↓  │ │
│  │ FOR ALL ENTRIES: CVI\_VEND\_LINK → BUT000 → BUT050 (Group Vendor)  │ │
│  │  ↓  │ │
│  │ FOR ALL ENTRIES: ADRC (Address)  │ │
│  │  ↓  │ │
│  │ FOR ALL ENTRIES: LFB1 (Payment Terms)  │ │
│  │  ↓  │ │
│  │ FOR ALL ENTRIES: LFM1 (Currency)  │ │
│  │  ↓  │ │
│  │ FOR ALL ENTRIES: ADR6 (Email)  │ │
│  │  ↓  │ │
│  │ FOR ALL ENTRIES: ADRCT (SPOC Remark)  │ │
│  │  ↓  │ │
│  │ FOR ALL ENTRIES: ZVENDOR\_BLOCK (Blacklist)  │ │
│  │  ↓  │ │
│  │ FOR ALL ENTRIES: ZMM\_VENDOR\_MSME (MSME Cert)  │ │
│  │  ↓  │ │
│  │ FOR ALL ENTRIES: ZMM\_VENDOR\_BEE (BEE Level)  │ │
│  └────────────────────────────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────────────────────────┘
  │
  ▼
┌─────────────────────────────────────────────────────────────────────────────┐
│  DATA PROCESSING  │
│  ┌────────────────────────────────────────────────────────────────────────┐ │
│  │ LOOP AT LT\_LFA1:  │ │
│  │  - Map LFA1 fields to output structure  │ │
│  │  - Determine STATUS based on SPERR/SPERM/SPERQ flags  │ │
│  │  - READ TABLE for PARTNER\_GUID, PARTNER, GROUP\_VENDOR  │ │
│  │  - READ TABLE for ADRC address fields  │ │
│  │  - READ TABLE for LFB1 payment terms  │ │
│  │  - READ TABLE for LFM1 currency  │ │
│  │  - READ TABLE for ADR6 email  │ │
│  │  - READ TABLE for ADRCT remark  │ │
│  │  - READ TABLE for ZVENDOR\_BLOCK blacklist status  │ │
│  │  - READ TABLE for ZMM\_VENDOR\_MSME certification  │ │
│  │  - READ TABLE for ZMM\_VENDOR\_BEE level  │ │
│  │  - Apply secondary filters (STATUS, BLACKLIST, BEGRU, BRSCH)  │ │
│  │  - APPEND to LT\_FINAL output table  │ │
│  └────────────────────────────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────────────────────────┘
  │
  ▼
┌─────────────────────────────────────────────────────────────────────────────┐
│  ALV OUTPUT  │
│  ┌────────────────────────────────────────────────────────────────────────┐ │
│  │ IF LT\_FINAL IS NOT INITIAL:  │ │
│  │  - Build field catalog (LT\_FCAT) with column headers  │ │
│  │  - CALL FUNCTION 'REUSE\_ALV\_GRID\_DISPLAY'  │ │
│  │ ELSE:  │ │
│  │  - MESSAGE 'No data found' TYPE 'S' DISPLAY LIKE 'E'  │ │
│  └────────────────────────────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────────────────────────┘
  

## Processing Logic

### 1\. Selection Screen Initialization (AT SELECTION-SCREEN OUTPUT)

The program uses the VRM framework (TYPE-POOLS: vrm) to populate dropdown listboxes for the five secondary filter parameters:

\* For each dropdown parameter (P\_STATUS, P\_BLACK, P\_BEGRU, P\_BEGRU1, P\_BRSCH):
name = ''.
value-key = '1'. value-text = 'YES/ACTIVE'. APPEND value TO list.
value-key = '2'. value-text = 'NO/INACTIVE'. APPEND value TO list.
CALL FUNCTION 'VRM\_SET\_VALUES'
  EXPORTING id = name  values = list.

### 2\. Input Validation (START-OF-SELECTION)

The program enforces mutual exclusivity among the five secondary filter fields. Users may select only ONE secondary filter at a time:

LOOP AT SCREEN.
  IF ( p\_status IS NOT INITIAL ) AND 
  ( p\_black IS NOT INITIAL OR p\_begru IS NOT INITIAL OR ... ).
  MESSAGE 'Please select only one input from last 5 secondary fields' TYPE 'E'.
  ENDIF.
ENDLOOP.

### 3\. Default Account Group Loading

When no selection criteria are entered, the program loads predefined vendor account groups from the TVARVC variant table:

IF s\_ktokk IS INITIAL AND s\_erdat IS INITIAL AND s\_gvend IS INITIAL 
  AND s\_lifnr IS INITIAL AND all\_secondary\_filters\_initial.
  SELECT low FROM tvarvc INTO CORRESPONDING FIELDS OF TABLE s\_ktokk
  WHERE name = 'ZMM\_VEND\_ACC\_GROUP'.
ENDIF.

### 4\. Main Data Retrieval Strategy

The program uses a series of FOR ALL ENTRIES queries to retrieve related data efficiently:

1.  **LFA1**: Primary vendor data with account group filter
2.  **CVI\_VEND\_LINK → BUT000 → BUT050**: Business Partner linkage for Group Vendor
3.  **ADRC**: Address details using ADRNR from LFA1
4.  **LFB1**: Company code data for payment terms (ZTERM)
5.  **LFM1**: Purchasing org data for currency (WAERS)
6.  **ADR6**: Email addresses (SMTP\_ADDR)
7.  **ADRCT**: Address remarks (WIPRO SPOC ID)
8.  **ZVENDOR\_BLOCK**: Blacklist flag (VFLAG)
9.  **ZMM\_VENDOR\_MSME**: MSME certification number
10.  **ZMM\_VENDOR\_BEE**: BEE level classification

### 5\. Status Determination Logic

IF ls\_lfa1-sperr = 'X' OR ls\_lfa1-sperm = 'X' OR ls\_lfa1-sperq IS NOT INITIAL.
  ls\_final-status = 'INACTIVE'.
ELSE.
  ls\_final-status = 'ACTIVE'.
ENDIF.

### 6\. Blacklist Status Determination

READ TABLE lt\_zvendor\_block1 INTO DATA(ls\_zvendor\_block1) 
  WITH KEY lifnr = ls\_lfa1-lifnr BINARY SEARCH.
IF sy-subrc = 0.
  IF ls\_zvendor\_block1-vflag = 'X'.
  ls\_final-blacklisted = 'Yes'.
  ELSE.
  ls\_final-blacklisted = 'No'.
  ENDIF.
ENDIF.

### 7\. Secondary Filter Application

After building the output record, the program applies the selected secondary filter to determine whether to include the record:

*   **P\_STATUS**: Filter by ACTIVE/INACTIVE status
*   **P\_BLACK**: Filter by blacklist Yes/No
*   **P\_BEGRU**: Filter by authorization group populated Yes/No
*   **P\_BEGRU1**: Additional authorization group filter
*   **P\_BRSCH**: Filter by industry code populated Yes/No

## Reusable Code

The following function modules are used in this program and can be reused in similar vendor reporting scenarios:

Function Module

Purpose

VRM\_SET\_VALUES

Set dropdown listbox values for selection screen parameters

REUSE\_ALV\_GRID\_DISPLAY

Display output in ALV grid format with standard functionality

**Note:** The data retrieval pattern using FOR ALL ENTRIES with multiple related tables (LFA1 → ADRC → ADR6 → ADRCT → LFB1 → LFM1) can be extracted into a reusable class or function group for other vendor reporting requirements.

## Internal Tables

Name

Description

LT\_FINAL

Main output table containing consolidated vendor data (TYPE TABLE OF TY\_FINAL)

LT\_LFA1

Vendor master general data from LFA1

LT\_PARTNER\_GUID

Vendor to Business Partner mapping from CVI\_VEND\_LINK

LT\_PARTNER

Business Partner numbers from BUT000

LT\_GROUP\_VENDOR

Group vendor relationships from BUT050

LT\_ADRC

Address data from ADRC

LT\_ZTERM

Payment terms from LFB1

LT\_WAERS

Currency data from LFM1

LT\_ADR6

Email addresses from ADR6

LT\_ADRCT

Address remarks (SPOC) from ADRCT

LT\_ZVENDOR\_BLOCK1

Vendor blacklist status from ZVENDOR\_BLOCK

LT\_ZMM\_VENDOR\_MSME

MSME certification from ZMM\_VENDOR\_MSME

LT\_ZMM\_VENDOR\_BEE

BEE level classification from ZMM\_VENDOR\_BEE

LT\_FCAT

ALV field catalog (SLIS\_T\_FIELDCAT\_ALV)

LIST

VRM values for dropdown listboxes (VRM\_VALUES)

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

S (display like E)

No Data Found

## Text Elements

Name

Text Description

TEXT-000

Selection Parameters (Frame Title for selection block B1)

**Selection Texts (recommended):**

Parameter

Selection Text

S\_KTOKK

Vendor Account Group

S\_ERDAT

Creation Date

S\_GVEND

Group Vendor

S\_LIFNR

Vendor Number

P\_STATUS

Vendor Status

P\_BLACK

Blacklisted

P\_BEGRU

Authorization Group

P\_BEGRU1

Authorization Group 2

P\_BRSCH

Industry Code

## Subroutines

This program uses inline processing logic without explicit FORM subroutines. The main processing blocks are:

Event/Block

Description

AT SELECTION-SCREEN OUTPUT

Initialize dropdown listboxes using VRM\_SET\_VALUES

START-OF-SELECTION (validation)

Validate mutual exclusivity of secondary filters

START-OF-SELECTION (data retrieval)

Execute FOR ALL ENTRIES queries for all related tables

LOOP AT lt\_lfa1

Build output records with READ TABLE lookups

ALV Display

Build field catalog and call REUSE\_ALV\_GRID\_DISPLAY

## Security

The current implementation does not include explicit AUTHORITY-CHECK statements. The following security considerations apply:

### Recommended Authorization Objects

Authorization Object

Fields

Purpose

F\_LFA1\_BEK

ACTVT (03), BEGRU

Vendor master display authorization by authorization group

F\_LFA1\_BUK

ACTVT (03), BUKRS

Vendor master display authorization by company code

M\_LFA1\_EKO

ACTVT (03), EKORG

Vendor master display authorization by purchasing organization

S\_TCODE

TCD

Transaction code authorization

**Security Recommendation:** Add AUTHORITY-CHECK for F\_LFA1\_BEK with BEGRU field to respect vendor master authorization groups, particularly since the report accesses sensitive fields like blacklist status, MSME certification, and BEE level classification.

## Upgrade

The following considerations apply for system upgrades:

*   **S/4HANA Migration:** The Business Partner integration (CVI\_VEND\_LINK, BUT000, BUT050) is already compatible with S/4HANA's BP-centric vendor model. No migration impact expected for these tables.
*   **Custom Tables:** ZVENDOR\_BLOCK, ZMM\_VENDOR\_MSME, and ZMM\_VENDOR\_BEE are custom tables that must be migrated along with the program during any system upgrade or migration.
*   **TVARVC Dependency:** The program depends on TVARVC entry 'ZMM\_VEND\_ACC\_GROUP' for default account groups. This variant must be maintained post-upgrade.
*   **ALV Framework:** REUSE\_ALV\_GRID\_DISPLAY (SLIS) remains supported but consider migration to CL\_SALV\_TABLE for newer SAP releases.
*   **LFA1 Custom Fields:** Fields like PO\_NONPOVENDOR, RISK\_CODE, RISK\_CATG, ZZEINVOICE are append structure fields that must be preserved during upgrades.

## Future Enhancements

*   **OO Refactoring:** Convert procedural code to OO ABAP using CL\_SALV\_TABLE for better maintainability and modern ALV features
*   **CDS View Backend:** Create a CDS view ZI\_VENDOR\_CONSOLIDATED joining all required tables for better performance and reusability
*   **Additional Filters:** Add company code (BUKRS) and purchasing organization (EKORG) as selection parameters
*   **Excel Download:** Add native Excel export functionality using CL\_SALV\_TABLE or ABAP2XLSX
*   **Field Catalog Optimization:** Dynamic field catalog generation based on output structure rather than hardcoded positions
*   **Message Class:** Create dedicated message class ZMM\_VENDOR\_REPORT for all messages
*   **Authorization Enhancement:** Implement comprehensive AUTHORITY-CHECK logic respecting vendor authorization groups

## Assumptions in Technical Design

*   The TVARVC variant 'ZMM\_VEND\_ACC\_GROUP' is pre-configured with the 24 valid vendor account groups
*   Custom tables ZVENDOR\_BLOCK, ZMM\_VENDOR\_MSME, and ZMM\_VENDOR\_BEE exist and are maintained with current data
*   All vendors have valid address numbers (ADRNR) populated in LFA1
*   Business Partner integration is active (CVI is enabled)
*   Users have appropriate display authorization for vendor master data
*   The VFLAG field in ZVENDOR\_BLOCK uses 'X' to indicate blacklisted vendors

## Open Issues in Technical Design

*   **No AUTHORITY-CHECK:** The program lacks vendor master authorization checks which could expose sensitive data to unauthorized users
*   **Duplicate Code Blocks:** Multiple conditional processing branches with similar data retrieval logic - candidates for refactoring into reusable methods
*   **Hardcoded Message Texts:** Messages are inline rather than in a message class, making translation difficult
*   **Missing Error Handling:** FOR ALL ENTRIES queries do not validate empty driver tables before execution
*   **Performance:** Multiple sequential FOR ALL ENTRIES queries could be optimized with JOINs or CDS views

## Unit Test Plan

Scenario #

Input Selection Criteria

Expected Result

1

No filters entered (all fields blank)

Report loads default account groups from TVARVC and displays all vendors matching those groups

2

S\_KTOKK = 'KRED' (single account group)

Report displays only vendors with account group KRED

3

S\_ERDAT = '20240101' to '20240331' (date range)

Report displays vendors created in Q1 2024

4

P\_STATUS = 'ACTIVE'

Report displays only active vendors (SPERR, SPERM, SPERQ all blank)

5

P\_STATUS = 'INACTIVE'

Report displays only blocked vendors (at least one block flag set)

6

P\_BLACK = 'YES'

Report displays only blacklisted vendors (VFLAG = 'X' in ZVENDOR\_BLOCK)

7

P\_STATUS = 'ACTIVE' AND P\_BLACK = 'YES' (multiple secondary)

Error message: "Please select only one input from last 5 secondary fields"

8

S\_LIFNR = '0000001000' (specific vendor)

Report displays single vendor with all consolidated data fields populated

9

S\_KTOKK = 'ZZZZ' (non-existent account group)

Message: "No Data Found"

10

S\_GVEND = '0000001234' (group vendor filter)

Report displays vendors linked to the specified group vendor via BUT050

## Related Documentation (attach OSS notes, emails, download of existing report, etc)

*   **Charm 4000004597:** MSME Certificate Number field addition - Transport WS1K997027
*   **Charm 4000005275:** Group Customer field addition - Transport WS1K9A014E
*   **Charm 4000005596:** Code cleanup - Transport WS1K9A02YZ
*   **Charm 4000005680:** Production data fetch fix - Transports WS1K9A03GW, WS1K9A04RP
*   **Charm 4000006028, 4000006474:** Secondary filters and blacklist logic - Transports WS1K9A05EB, WS1K9A06LT, WS1K9A07DO, WS1K9A08IU, WS1K9A09D0
*   **Charm 4000008627:** BEE Level field addition - Transport WS1K9A0HO1
*   **SAP Note 1056906:** FAQ: ALV Grid Control
*   **SAP Note 169890:** Customer Vendor Integration (CVI) documentation

Generated by C16 — Your Autonomous SAP Team | Document Date: 2026-06-08

System: ECC 7.40 (Client 800) | Package: $TMP | Author: VINOD