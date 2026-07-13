## 1 LFA1 — Vendor Master (General Data)

**LFA1** is the central SAP table storing _general vendor master data_ — information that applies across all company codes. This includes vendor identification, name, address, communication details, and control data. Every vendor in SAP has exactly one LFA1 record, making it the foundation of the vendor master hierarchy.

## 2 Top 3 Key Fields

Field

Description

Type

**LIFNR**

Vendor Account Number — Primary key identifying the vendor

CHAR(10)

**NAME1**

Vendor Name — Primary business name

CHAR(35)

**LAND1**

Country Key — Vendor's country of registration

CHAR(3)

## 3 Vendor Master Table Hierarchy

The vendor master is structured in three levels — general data (client-wide), company code data (accounting), and transaction figures (statistical):

erDiagram LFA1 ||--o{ LFB1 : "has company codes" LFB1 ||--o{ LFC1 : "has transaction figures" LFA1 { char LIFNR PK "Vendor Number" char NAME1 "Vendor Name" char LAND1 "Country" char ORT01 "City" char STRAS "Street" } LFB1 { char LIFNR PK "Vendor Number" char BUKRS PK "Company Code" char AKONT "Recon Account" char ZTERM "Payment Terms" char ZWELS "Payment Methods" } LFC1 { char LIFNR PK "Vendor Number" char BUKRS PK "Company Code" char GJAHR PK "Fiscal Year" curr UMSAV "Sales/Purchases" curr BABZG "Discount Taken" }

Relationship Summary

**LFA1** (1) → **LFB1** (many): One vendor can be extended to multiple company codes.  
**LFB1** (1) → **LFC1** (many): Each company code assignment tracks transaction figures by fiscal year.