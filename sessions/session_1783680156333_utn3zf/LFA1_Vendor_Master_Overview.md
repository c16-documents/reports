## 1 What is LFA1?

**LFA1** is SAP's central **Vendor Master General Data** table. It stores client-level information about vendors that applies across all company codes — the "one source of truth" for vendor identity, address, and control data.

Key Insight

LFA1 holds data valid for the _entire client_, while company code-specific data (payment terms, reconciliation accounts) lives in LFB1, and transaction figures are stored in LFC1.

## 2 Top 3 Fields

Field

Description

Example

**LIFNR**

Vendor Account Number (Primary Key)

0000001000

**NAME1**

Vendor Name (Line 1)

Acme Supplies Ltd

**LAND1**

Country Key

US, DE, IN

## 3 Vendor Master Hierarchy

The vendor master follows a three-tier structure — from general data down to transaction figures:

graph TD subgraph Client Level LFA1\[**LFA1**  
General Data  
Name, Address, Control\] end subgraph Company Code Level LFB1\[**LFB1**  
Company Code Data  
Payment Terms, Recon Account\] end subgraph Transaction Level LFC1\[**LFC1**  
Transaction Figures  
Balances, Turnover\] end LFA1 -->|1 : N| LFB1 LFB1 -->|1 : N| LFC1 style LFA1 fill:#7FB3E0,stroke:#1f2937,color:#fff style LFB1 fill:#5a9bd4,stroke:#1f2937,color:#fff style LFC1 fill:#3d7fb8,stroke:#1f2937,color:#fff

## 4 Table Summary

Table

Level

Purpose

Key Fields

**LFA1**

Client

General vendor identity & address

LIFNR, NAME1, LAND1, ORT01, STRAS

**LFB1**

Company Code

Accounting & payment configuration

LIFNR, BUKRS, AKONT, ZTERM

**LFC1**

Transaction

Period-based transaction totals

LIFNR, BUKRS, GJAHR, UMSAV

Code Quality Note

For new S/4HANA development, use the released CDS views **I\_Supplier** and **I\_SupplierCompany** instead of direct LFA1/LFB1 access. This ensures upgrade safety and cloud readiness.