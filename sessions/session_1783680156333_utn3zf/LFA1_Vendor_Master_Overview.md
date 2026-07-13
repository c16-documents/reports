## 1LFA1 — Vendor Master (General Data)

**LFA1** is the central SAP table storing **general vendor master data** — the client-level information that applies across all company codes and purchasing organizations. Every vendor in your SAP system has exactly one record in LFA1, identified by the vendor number (`LIFNR`).

Key Concept

LFA1 holds data that is _independent_ of organizational units — name, address, tax numbers, industry classification. Company-code-specific data (payment terms, reconciliation accounts) lives in **LFB1**.

## 2Top 3 Fields

Field

Description

Example

**LIFNR**

Vendor Number (Primary Key)

`0000001000`

**NAME1**

Vendor Name (Line 1)

`Acme Corporation`

**LAND1**

Country Key

`US`, `DE`, `IN`

## 3Vendor Master Table Hierarchy

The vendor master is split across three levels to support SAP's organizational structure:

graph TD LFA1\["**LFA1**  
General Data  
(Client Level)"\] LFB1\["**LFB1**  
Company Code Data  
(Payment Terms, Recon Account)"\] LFC1\["**LFC1**  
Transaction Figures  
(Balances, Turnover)"\] LFA1 -->|"1 : N"| LFB1 LFB1 -->|"1 : N"| LFC1 style LFA1 fill:#7FB3E0,color:#fff style LFB1 fill:#7FB3E0,color:#fff style LFC1 fill:#7FB3E0,color:#fff

Table

Level

Key Fields

Purpose

**LFA1**

Client

LIFNR

Name, address, tax IDs, industry

**LFB1**

Company Code

LIFNR + BUKRS

Payment terms, recon account, payment methods

**LFC1**

Company Code + Year

LIFNR + BUKRS + GJAHR

Cumulative transaction figures (debit/credit totals)

Code Quality Note

For new developments, use CDS views **I\_Supplier** and **I\_SupplierCompany** instead of direct LFA1/LFB1 access. These are Released APIs (Level A) compatible with S/4HANA and ABAP Cloud.