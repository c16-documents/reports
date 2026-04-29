  C16 Enterprise Migration Framework — 6-Layer S/4HANA Transformation :root { --c16-purple: #6B3FA0; --c16-pink: #B5567A; --c16-gold: #C97B3A; --c16-dark: #1a1a2e; --c16-light: #f8f9fa; --green: #27ae60; --blue: #3498db; --orange: #e67e22; --red: #e74c3c; --amber: #f39c12; --teal: #00b894; } \* { margin: 0; padding: 0; box-sizing: border-box; } body { font-family: 'Segoe UI', -apple-system, BlinkMacSystemFont, Arial, sans-serif; color: #2c3e50; background: #e9ecef; line-height: 1.7; font-size: 15px; } .doc-wrapper { max-width: 1140px; margin: 0 auto; background: #fff; box-shadow: 0 4px 24px rgba(0,0,0,0.12); } /\* ── Header Banner ── \*/ .header-banner { background: linear-gradient(135deg, #C97B3A 0%, #B5567A 40%, #6B3FA0 100%); color: #fff; padding: 48px 56px; position: relative; overflow: hidden; } .header-banner::after { content: ''; position: absolute; top: -50%; right: -20%; width: 600px; height: 600px; border-radius: 50%; background: rgba(255,255,255,0.04); } .header-banner img { height: 50px; margin-bottom: 14px; border-radius: 8px; } .header-banner h1 { font-size: 2.2em; font-weight: 700; margin-bottom: 8px; } .header-banner .subtitle { font-size: 1.15em; opacity: 0.92; margin-bottom: 18px; } .header-banner .meta-badges { display: flex; gap: 12px; flex-wrap: wrap; } .header-banner .badge { background: rgba(255,255,255,0.18); padding: 5px 16px; border-radius: 20px; font-size: 0.85em; backdrop-filter: blur(4px); border: 1px solid rgba(255,255,255,0.2); } /\* ── Content Area ── \*/ .content { padding: 40px 56px; } /\* ── Section Headers ── \*/ .section-header { display: flex; align-items: center; gap: 14px; margin: 48px 0 20px; padding-bottom: 10px; border-bottom: 3px solid var(--c16-pink); } .section-header:first-child { margin-top: 0; } .section-number { background: var(--c16-pink); color: #fff; width: 36px; height: 36px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 700; font-size: 0.95em; flex-shrink: 0; } .section-header h2 { color: var(--c16-purple); font-size: 1.55em; font-weight: 700; } /\* ── Sub-Section Headers ── \*/ h3 { color: var(--c16-purple); font-size: 1.2em; margin: 30px 0 12px; padding-left: 14px; border-left: 4px solid var(--c16-pink); } h4 { color: #444; font-size: 1.05em; margin: 20px 0 8px; } p { margin-bottom: 14px; } /\* ── Tables ── \*/ table { width: 100%; border-collapse: collapse; margin: 16px 0 24px; font-size: 0.92em; } thead th { background: var(--c16-purple); color: #fff; padding: 11px 14px; text-align: left; font-weight: 600; } tbody td { padding: 10px 14px; border-bottom: 1px solid #eee; vertical-align: top; } tbody tr:nth-child(even) { background: #f8fafc; } tbody tr:hover { background: #edf2f7; } /\* ── Collapsible Sections ── \*/ details { margin: 16px 0; border: 1px solid #e2e8f0; border-radius: 8px; overflow: hidden; } details summary { padding: 14px 20px; background: #f0f4f8; cursor: pointer; font-weight: 600; color: var(--c16-purple); display: flex; align-items: center; gap: 10px; user-select: none; transition: background 0.2s; } details summary:hover { background: #e2e8f0; } details summary::marker { color: var(--c16-pink); } details\[open\] summary { border-bottom: 1px solid #e2e8f0; } details .detail-content { padding: 20px; } /\* ── Code Blocks ── \*/ pre { background: #1e1e2e; color: #cdd6f4; padding: 20px; border-radius: 8px; overflow-x: auto; font-family: 'Cascadia Code', 'Fira Code', 'Consolas', monospace; font-size: 0.88em; line-height: 1.65; margin: 12px 0 20px; border-left: 4px solid var(--c16-pink); } code { font-family: 'Cascadia Code', 'Fira Code', 'Consolas', monospace; font-size: 0.92em; } p code, li code, td code { background: #f0f0f5; padding: 2px 7px; border-radius: 4px; color: var(--c16-purple); } /\* ── KPI / Metric Cards ── \*/ .kpi-row { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 16px; margin: 20px 0 28px; } .kpi-card { background: linear-gradient(135deg, #f8f9fa, #eef1f5); border-radius: 12px; padding: 22px; text-align: center; border: 1px solid #e2e8f0; transition: transform 0.2s; } .kpi-card:hover { transform: translateY(-3px); box-shadow: 0 6px 16px rgba(0,0,0,0.08); } .kpi-value { font-size: 2em; font-weight: 800; color: var(--c16-purple); } .kpi-label { font-size: 0.85em; color: #666; margin-top: 4px; } /\* ── Badges ── \*/ .badge-retire { background: var(--green); color: #fff; padding: 3px 12px; border-radius: 12px; font-size: 0.82em; font-weight: 600; } .badge-remediate { background: var(--blue); color: #fff; padding: 3px 12px; border-radius: 12px; font-size: 0.82em; font-weight: 600; } .badge-clean { background: var(--c16-purple); color: #fff; padding: 3px 12px; border-radius: 12px; font-size: 0.82em; font-weight: 600; } .badge-level-a { background: var(--green); color: #fff; padding: 2px 10px; border-radius: 12px; font-size: 0.82em; } .badge-level-b { background: var(--blue); color: #fff; padding: 2px 10px; border-radius: 12px; font-size: 0.82em; } .badge-level-c { background: var(--orange); color: #fff; padding: 2px 10px; border-radius: 12px; font-size: 0.82em; } .badge-level-d { background: var(--red); color: #fff; padding: 2px 10px; border-radius: 12px; font-size: 0.82em; } .badge-effort-1 { background: #d4edda; color: #155724; padding: 3px 12px; border-radius: 12px; font-size: 0.82em; font-weight: 600; } .badge-effort-2 { background: #d1ecf1; color: #0c5460; padding: 3px 12px; border-radius: 12px; font-size: 0.82em; font-weight: 600; } .badge-effort-3 { background: #fff3cd; color: #856404; padding: 3px 12px; border-radius: 12px; font-size: 0.82em; font-weight: 600; } .badge-effort-4 { background: #f8d7da; color: #721c24; padding: 3px 12px; border-radius: 12px; font-size: 0.82em; font-weight: 600; } .badge-effort-5 { background: #e74c3c; color: #fff; padding: 3px 12px; border-radius: 12px; font-size: 0.82em; font-weight: 600; } .badge-phase { background: rgba(107,63,160,0.1); color: var(--c16-purple); padding: 3px 12px; border-radius: 12px; font-size: 0.8em; font-weight: 600; border: 1px solid rgba(107,63,160,0.25); } /\* ── Coverage badges ── \*/ .coverage-fit { background: #27ae60; color: #fff; padding: 2px 10px; border-radius: 12px; font-size: 0.85em; } .coverage-config { background: #3498db; color: #fff; padding: 2px 10px; border-radius: 12px; font-size: 0.85em; } .coverage-extension { background: #e67e22; color: #fff; padding: 2px 10px; border-radius: 12px; font-size: 0.85em; } .coverage-gap { background: #e74c3c; color: #fff; padding: 2px 10px; border-radius: 12px; font-size: 0.85em; } /\* ── Callout Boxes ── \*/ .callout { padding: 20px 24px; border-radius: 10px; margin: 20px 0; } .callout-insight { background: linear-gradient(135deg, #f0e6ff, #f5f0ff); border-left: 5px solid var(--c16-purple); } .callout-warning { background: #fff8e1; border-left: 5px solid var(--amber); } .callout-success { background: #f0fff4; border-left: 5px solid var(--green); } .callout-critical { background: #fff5f5; border-left: 5px solid var(--red); } .callout-title { font-weight: 700; font-size: 1.05em; margin-bottom: 8px; } /\* ── Layer Cards ── \*/ .layer-card { border: 2px solid #e2e8f0; border-radius: 14px; padding: 28px; margin: 20px 0; position: relative; transition: border-color 0.3s, box-shadow 0.3s; } .layer-card:hover { border-color: var(--c16-purple); box-shadow: 0 4px 20px rgba(107,63,160,0.1); } .layer-card .layer-number { position: absolute; top: -18px; left: 24px; background: var(--c16-purple); color: #fff; width: 36px; height: 36px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 800; font-size: 1.1em; } .layer-card .layer-title { font-size: 1.3em; font-weight: 700; color: var(--c16-purple); margin-bottom: 4px; } .layer-card .layer-question { font-style: italic; color: #666; margin-bottom: 14px; font-size: 1.05em; } /\* ── Effort Spectrum ── \*/ .effort-bar { display: flex; border-radius: 8px; overflow: hidden; height: 40px; margin: 16px 0; box-shadow: 0 2px 8px rgba(0,0,0,0.08); } .effort-bar div { display: flex; align-items: center; justify-content: center; color: #fff; font-size: 0.8em; font-weight: 600; transition: flex 0.3s; } /\* ── Flow Connector ── \*/ .flow-connector { text-align: center; padding: 8px 0; color: var(--c16-purple); font-size: 1.5em; } /\* ── Mermaid ── \*/ .mermaid { margin: 20px 0; text-align: center; } /\* ── TOC ── \*/ .toc { background: #f8f9fa; border: 1px solid #e2e8f0; border-radius: 10px; padding: 24px 32px; margin: 24px 0 36px; } .toc h3 { border: none; padding: 0; margin: 0 0 14px; color: var(--c16-purple); } .toc ol { padding-left: 20px; } .toc li { margin: 6px 0; } .toc a { color: var(--c16-purple); text-decoration: none; font-weight: 500; } .toc a:hover { text-decoration: underline; } /\* ── Decision Tree ── \*/ .decision-tree { background: #f8f9fa; border: 2px solid #e2e8f0; border-radius: 12px; padding: 28px; margin: 20px 0; } /\* ── Timeline ── \*/ .timeline-phase { display: flex; align-items: stretch; gap: 0; margin: 24px 0; } .timeline-block { flex: 1; padding: 16px; text-align: center; color: #fff; position: relative; } .timeline-block::after { content: '→'; position: absolute; right: -12px; top: 50%; transform: translateY(-50%); font-size: 1.4em; color: #666; z-index: 2; } .timeline-block:last-child::after { display: none; } .timeline-label { font-weight: 700; font-size: 1.05em; } .timeline-desc { font-size: 0.82em; opacity: 0.9; margin-top: 4px; } /\* ── Quote Box ── \*/ .quote-box { background: linear-gradient(135deg, #f0e6ff, #ede4ff); border-left: 5px solid var(--c16-purple); padding: 24px 28px; border-radius: 0 12px 12px 0; margin: 24px 0; font-size: 1.1em; font-style: italic; color: #333; } .quote-box .attribution { font-style: normal; font-size: 0.85em; color: #666; margin-top: 10px; text-align: right; } /\* ── Footer ── \*/ .doc-footer { background: var(--c16-dark); color: rgba(255,255,255,0.7); padding: 32px 56px; font-size: 0.85em; } .doc-footer a { color: rgba(255,255,255,0.9); } /\* ── Print ── \*/ @media print { body { background: #fff; } .doc-wrapper { box-shadow: none; } details { break-inside: avoid; } details\[open\] .detail-content { display: block !important; } .header-banner { -webkit-print-color-adjust: exact; print-color-adjust: exact; } .no-print { display: none; } } /\* ── Responsive ── \*/ @media (max-width: 768px) { .header-banner, .content, .doc-footer { padding: 24px; } .kpi-row { grid-template-columns: 1fr 1fr; } .timeline-phase { flex-direction: column; } .timeline-block::after { display: none; } }

![C16](data:image/jpeg;base64,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)

# The 6-Layer S/4HANA Transformation Framework

Enterprise-Grade Migration Methodology — From AS-IS Discovery to Clean Core Certification

Framework v2.0 — April 2026 Applicable: Any SAP ECC → S/4HANA Migration Powered by C16 AI Platform Process-Agnostic (O2C, P2P, R2R, MTO, HR, WM)

### 📋 Table of Contents

1.  [The Problem — Why Traditional Approaches Fail](#problem)
2.  [Design Principles — 7 Rules That Shape the Framework](#principles)
3.  [The 6-Layer Framework — At a Glance](#framework-overview)
4.  [The Clean Core Effort Spectrum — Not Everything Is a Rewrite](#effort-spectrum)
5.  [The Triage Decision Engine — Retire / Remediate / Clean Core](#triage)
6.  [Layer 1: Complete AS-IS Discovery](#layer-1)
7.  [Layer 2: S/4HANA Standard Delta](#layer-2)
8.  [Layer 3: Fit-to-Standard Analysis](#layer-3)
9.  [Layer 4: Remediation & Clean Core Build](#layer-4)
10.  [Layer 5: Certification & Validation](#layer-5)
11.  [Layer 6: Handoff & Go-Live Readiness](#layer-6)
12.  [The Journey — Progressive Clean Core](#journey)
13.  [C16 Platform Capability Matrix](#c16-capability)
14.  [Execution Timeline — Reference Plan](#timeline)
15.  [Cross-Process Examples](#examples)
16.  [Value Proposition & ROI](#roi)

1

## The Problem — Why Traditional Approaches Fail

Every S/4HANA migration faces the same dilemma. Enterprises run two extremes — and both fail:

Approach A

**"Remediate Everything"**  
Fast to go-live, but stuck at Level B/C.  
Technical debt accumulates. No cloud path. Every upgrade becomes harder.

Approach B

**"Clean Core Everything"**  
Perfect target state, but 3-5 year timeline.  
Business says no. Budget exhausted. Go-live delayed.

This Framework

**"Triage & Transform"**  
Go-live on time. 70-80% Level A at launch.  
Remaining objects converted in post-go-live waves.

Traditional migration assessments also suffer from **three structural gaps** that this framework eliminates:

Gap

What Happens

Consequence

**Standard process blindness**

Teams analyse custom code but never study what S/4HANA standard itself changes

Fit-to-Standard mapping targets the WRONG baseline

**Configuration afterthought**

Config migration planned in the last 2 weeks before cutover

Missing pricing procedures, broken output determination, wrong partner functions

**No validation layer**

Remediated code deployed without E2E proof

Defects discovered in UAT or — worse — in production

💡 The Core Insight

You cannot do a proper Fit-to-Standard analysis until you understand **both sides** — what the customer has today (Layer 1) AND what S/4HANA changes regardless of custom code (Layer 2). Mapping customs against an unknown target is guesswork, not engineering.

2

## Design Principles — 7 Rules That Shape the Framework

#

Principle

What It Means

How It's Enforced

**P1**

Understand both sides before mapping

Know the AS-IS (Layer 1) AND the TO-BE standard (Layer 2) before classifying anything

Layer 3 requires Layer 1 + 2 outputs as mandatory inputs

**P2**

Configuration is first-class

Config migration is discovered, mapped, and validated — not an afterthought

Config discovered in Layer 1, delta in Layer 2, migrated in Layer 4

**P3**

One comprehensive discovery

Discover everything once — customs, config, org structure, integrations, data profile

Layer 1 covers ALL dimensions, not just custom code

**P4**

Layers feed forward

Each layer's output is the next layer's mandatory input. No skipping, no backtracking.

Explicit input/output contracts defined per layer

**P5**

Never write throwaway code

If Clean Core effort is within 1 day of remediation, build Clean Core immediately

Effort Level 1-2 objects go straight to Level A

**P6**

Triage, don't mandate

Not every object needs the same treatment. Retire / Remediate / Clean Core is decided per object.

Layer 3 produces a lane recommendation per object

**P7**

Prove it works

Every transformation must be validated — not just deployed and hoped for the best

Layer 5 certification + Layer 6 E2E validation

3

## The 6-Layer Framework — At a Glance

graph LR L1\["**Layer 1**  
Complete AS-IS  
Discovery"\] L2\["**Layer 2**  
S/4HANA Standard  
Delta"\] L3\["**Layer 3**  
Fit-to-Standard  
Analysis"\] L4\["**Layer 4**  
Remediation &  
Clean Core Build"\] L5\["**Layer 5**  
Certification &  
Validation"\] L6\["**Layer 6**  
Handoff &  
Go-Live Readiness"\] L1 --> L2 --> L3 --> L4 --> L5 --> L6 style L1 fill:#27ae60,stroke:#1e8449,color:#fff style L2 fill:#2980b9,stroke:#1a5276,color:#fff style L3 fill:#8e44ad,stroke:#6c3483,color:#fff style L4 fill:#e67e22,stroke:#ca6f1e,color:#fff style L5 fill:#16a085,stroke:#117864,color:#fff style L6 fill:#2c3e50,stroke:#1a252f,color:#fff

Layer 1

**What do we have?**

Layer 2

**What changes regardless?**

Layer 3

**What fits, what gaps?**

Layer 4

**Do the work right**

Layer 5

**Prove it's right**

Layer 6

**Hand it over**

### Phase Grouping

Phase

Layers

Purpose

Output

DISCOVER

Layer 1 + Layer 2

Understand BOTH sides — AS-IS and TO-BE baseline

Complete inventory + standard delta register

ANALYSE

Layer 3

Map every object and config item — classify and triage

Fit-to-Standard matrix + triage decisions

BUILD

Layer 4

Execute: retire, configure, remediate, or build Clean Core

Deployable code + config guides + retirement docs

PROVE

Layer 5 + Layer 6

Certify Clean Core, validate E2E, package for go-live

Certification scorecard + test results + handoff package

### Data Flow — Input/Output Contracts

graph TD subgraph "Layer 1: Complete AS-IS" L1O1\["Custom Object Inventory"\] L1O2\["Config Snapshot"\] L1O3\["Org Structure Map"\] L1O4\["Integration Map"\] L1O5\["Data Profile"\] end subgraph "Layer 2: Standard Delta" L2O1\["Transaction Replacement Map"\] L2O2\["Field Change Register"\] L2O3\["Config Delta"\] L2O4\["New Capabilities"\] L2O5\["Simplification Items"\] end subgraph "Layer 3: Fit-to-Standard" L3O1\["FIT/GAP per requirement"\] L3O2\["Triage Decision per object"\] L3O3\["Coverage % per step"\] L3O4\["Effort Level per object"\] end subgraph "Layer 4: Remediation & Build" L4O1\["Retired Object Register"\] L4O2\["Config Migration Guide"\] L4O3\["Remediated Code"\] L4O4\["Clean Core Code"\] end subgraph "Layer 5: Certification" L5O1\["CC Scorecard"\] L5O2\["ATC Results"\] L5O3\["Test Scenarios"\] end subgraph "Layer 6: Handoff" L6O1\["Go-Live Package"\] end L1O1 --> L3O1 L1O2 --> L3O1 L2O1 --> L3O1 L2O2 --> L3O1 L2O3 --> L3O1 L3O1 --> L4O1 L3O2 --> L4O3 L3O4 --> L4O4 L4O3 --> L5O1 L4O4 --> L5O1 L5O1 --> L6O1 L5O3 --> L6O1 style L1O1 fill:#27ae60,color:#fff style L2O1 fill:#2980b9,color:#fff style L3O1 fill:#8e44ad,color:#fff style L4O3 fill:#e67e22,color:#fff style L5O1 fill:#16a085,color:#fff style L6O1 fill:#2c3e50,color:#fff

4

## The Clean Core Effort Spectrum — Not Everything Is a Rewrite

The most damaging misconception in S/4HANA migration is that Clean Core equals "rewrite everything from scratch." In reality, Clean Core encompasses a **spectrum of 5 effort levels**, and the majority of objects require only trivial changes.

💡 The Key Insight

**80% of Clean Core conversions are NOT full rewrites.** They're table name swaps, API call replacements, or BAdI re-containers. Only 5-8% of objects require a ground-up rebuild. This changes the economics of "Remediate now, Clean Core later" — because for most objects, Clean Core costs almost the same as remediation.

### The 5 Effort Levels

Level

Description

Typical Effort

% of Objects

What Changes

Level 1

**One-Line Swap**

30 minutes

~35%

Replace table/view name in SELECT. Logic untouched.

Level 2

**Small Block Replace**

2-4 hours

~25%

Replace unreleased FM with released API. Map 5-10 parameters.

Level 3

**Medium Refactor**

1-3 days

~20%

Move logic from user exit to Released BAdI. Same business logic, new container.

Level 4

**Significant Rewrite**

1-2 weeks

~12%

Replace entire approach (e.g., BDC → API). New code structure.

Level 5

**Full Rebuild**

2-4 weeks

~5-8%

Custom framework deeply coupled to SAP internals. Architecture redesign.

### Effort Distribution — The Real Picture

Level 1 — 35%

Level 2 — 25%

Level 3 — 20%

L4 — 12%

L5

← 80% of objects need less than 3 days of effort →

### Examples Per Effort Level

🟢 Effort Level 1 — One-Line Swap (30 minutes)

The simplest Clean Core conversion. Replace a direct table access with the released CDS view. Your business logic, variables, processing — all untouched.

#### Example: Customer Master Read

**Before (Level C — direct table access):**

SELECT SINGLE kunnr name1 land1 FROM kna1
  INTO (lv\_customer, lv\_name, lv\_country)
  WHERE kunnr = lv\_input.

**After (Level A — released CDS view):**

SELECT SINGLE Customer, CustomerName, Country FROM I\_Customer
  INTO (@lv\_customer, @lv\_name, @lv\_country)
  WHERE Customer = @lv\_input.

**What changed:** Table name (`kna1` → `I_Customer`), field names mapped, added `@` host variable escaping. One line. 30 minutes including testing.

#### More Examples at This Level

Before

After

Change

`SELECT FROM lfa1`

`SELECT FROM I_Supplier`

Table → CDS view

`SELECT FROM mara`

`SELECT FROM I_Product`

Table → CDS view

`SELECT FROM ekko`

`SELECT FROM I_PurchaseOrder`

Table → CDS view

`SELECT FROM vbak`

`SELECT FROM I_SalesOrder`

Table → CDS view

`SELECT FROM bkpf`

`SELECT FROM I_JournalEntry`

Table → CDS view

🔵 Effort Level 2 — Small Block Replace (2-4 hours)

Replace an unreleased function module or BAPI with its released successor. The calling program's logic stays the same — you map parameters and adjust the call block.

#### Example: Sales Order Creation

**Before (Level B — unreleased FM):**

CALL FUNCTION 'SD\_SALESDOCUMENT\_CREATE'
  EXPORTING
    sales\_header\_in     = ls\_header
  TABLES
    sales\_items\_in      = lt\_items
    sales\_schedules\_in  = lt\_schedules
  EXCEPTIONS
    error\_message       = 1.

**After (Level A — released API):**

CALL FUNCTION 'BAPI\_SALESORDER\_CREATEFROMDAT2'
  EXPORTING
    order\_header\_in     = ls\_header\_bapi
  TABLES
    order\_items\_in      = lt\_items\_bapi
    order\_schedules\_in  = lt\_schedules\_bapi
    return              = lt\_return.

CALL FUNCTION 'BAPI\_TRANSACTION\_COMMIT'
  EXPORTING wait = 'X'.

**What changed:** FM name, parameter structure mapping (5-10 fields), added BAPI commit. The logic that BUILDS the header and items? Untouched. 2-4 hours including testing.

#### More Examples at This Level

Scenario

Before

After

Create Purchase Order

`ME_CREATE_PO`

`BAPI_PO_CREATE1`

Create Material Document

`MB_CREATE_GOODS_MOVEMENT`

`BAPI_GOODSMVT_CREATE`

Read Business Partner

`SELECT FROM kna1/lfa1`

`BAPI_BUPA_CENTRAL_GETDETAIL`

Post FI Document

`POSTING_INTERFACE_DOCUMENT`

`BAPI_ACC_DOCUMENT_POST`

🟡 Effort Level 3 — BAdI/Extension Swap (1-3 days)

The business logic is sound — it just lives in the wrong container. Move it from a user exit or classic BAdI into a Released BAdI. The logic is 90% reusable; you change the wrapper.

#### Example: Sales Order Save Validation

**Before (Level C — classic user exit):**

\* Inside MV45AFZZ include
FORM USEREXIT\_SAVE\_DOCUMENT\_PREPARE.
  " 200 lines of custom credit check logic
  SELECT SINGLE \* FROM knb1 WHERE kunnr = vbak-kunnr AND bukrs = vbak-bukrs.
  IF lv\_credit\_used > lv\_credit\_limit.
    MESSAGE e001(zsd) WITH vbak-kunnr.
  ENDIF.
ENDFORM.

**After (Level A — released BAdI):**

CLASS zcl\_sd\_order\_check DEFINITION PUBLIC FINAL CREATE PUBLIC.
  PUBLIC SECTION.
    INTERFACES if\_sd\_sales\_doc\_check.  " Released BAdI interface
ENDCLASS.

CLASS zcl\_sd\_order\_check IMPLEMENTATION.
  METHOD if\_sd\_sales\_doc\_check~check.
    " SAME 200 lines of credit check logic — moved here
    SELECT SINGLE \* FROM I\_CustomerCompany
      WHERE Customer = iv\_customer AND CompanyCode = iv\_bukrs.
    IF lv\_credit\_used > lv\_credit\_limit.
      APPEND VALUE #( type = 'E' id = 'ZSD' number = '001' ) TO ct\_messages.
    ENDIF.
  ENDMETHOD.
ENDCLASS.

**What changed:** Container (FORM → CLASS METHOD), interface (user exit → Released BAdI), one table reference (`knb1` → `I_CustomerCompany`). The core 200 lines of credit check logic? Moved as-is with minor syntax adjustments.

🟠 Effort Level 4 — Significant Rewrite (1-2 weeks)

The entire technical approach is obsolete. Screen-based automation (BDC), custom report writers, or procedural batch programs that cannot be patched — they must be redesigned.

#### Example: Mass Sales Order Upload via BDC

**Before (Level D — BDC screen recording):**

\* 500+ lines of BDCDATA construction
PERFORM bdc\_field USING 'VBAK-AUART' 'OR'.
PERFORM bdc\_field USING 'VBAK-VKORG' '1000'.
PERFORM bdc\_field USING 'KUAGV-KUNNR' lv\_customer.
...
CALL TRANSACTION 'VA01' USING lt\_bdcdata
  MODE 'N'
  UPDATE 'S'.

**After (Level A — released OData API):**

\* 50 lines of clean API call
DATA(lo\_http) = cl\_web\_http\_client\_manager=>create\_by\_http\_destination(
  i\_destination = cl\_http\_destination\_provider=>create\_by\_comm\_arrangement(
    comm\_scenario = 'Z\_SD\_ORDER\_CREATE' ) ).

lo\_http->get\_http\_request( )->set\_header\_field(
  i\_name = 'Content-Type' i\_value = 'application/json' ).

" Build payload from upload data
lo\_http->execute( if\_web\_http\_client=>post ).

**What changed:** Everything. BDC is fundamentally incompatible with Fiori — there are no screens to "play." The entire program is replaced with API calls. However, the DATA PREPARATION logic (reading Excel, building header/items) often survives intact.

🔴 Effort Level 5 — Full Rebuild (2-4 weeks)

Custom frameworks that deeply penetrate SAP internals — custom pricing engines, custom workflow engines, custom material determination, or custom availability check frameworks. These must be redesigned from architecture level.

#### Example: Custom Pricing Engine Bypassing Condition Technique

**Before:** 2,000+ lines across 5 includes. Reads V-tables directly, maintains its own condition memory, bypasses standard PRICING calls. Deeply coupled to internal pricing structures (KOMK, KOMP, KOMV).

**After:** Must be redesigned using standard condition technique + Released BAdI for custom pricing logic. Different architecture. New data flow. Requires functional specification, not just code conversion.

**This is rare** — typically 5-8% of custom objects. These are the ones that justify deferring to post-go-live.

### The Economic Crossover

This effort spectrum reveals a critical insight that changes migration strategy:

Effort Level

Clean Core Effort

Remediation Effort

Delta

Decision

Level 1

30 minutes

30 minutes

**Zero**

Clean Core NOW

Level 2

2-4 hours

1-2 hours

+2 hours

Clean Core NOW

Level 3

1-3 days

0.5-1 day

+1-2 days

⚖️ Decision Point

Level 4

1-2 weeks

2-3 days

+1 week

Remediate NOW

Level 5

2-4 weeks

1 week

+2 weeks

Remediate NOW

✅ The Crossover Rule

**For Level 1-2 objects (60% of the total), Clean Core costs almost the same as remediation.** There is no reason to remediate these to Level B/C and plan a second pass later. Just do it right the first time.

5

## The Triage Decision Engine — Retire / Remediate / Clean Core

Every custom object discovered in Layer 1 must be triaged into one of three lanes. The triage happens in Layer 3 (Fit-to-Standard Analysis) and determines the execution path in Layer 4.

### The Three Lanes

🗑️

RETIRE

**S/4 standard replaces it**  
Zero code work. Document and switch off.  
~30-40% of objects typically.

🔧

REMEDIATE

**Fix to work on S/4**  
Effort Level 4-5 objects. Minimum changes.  
Level B/C now, Clean Core post-go-live.  
~15-25% of objects.

✨

CLEAN CORE

**Build it right, first time**  
Effort Level 1-3 objects + strategic objects.  
Level A from day one.  
~35-50% of objects.

### The Decision Tree

graph TD A\["Custom Object Found"\] --> B{"Does S/4 standard  
replace this?"} B -->|Yes| C\["🟢 RETIRE"\] B -->|No| D{"What Effort Level  
(1-5)?"} D -->|"Level 1-2  
(≤4 hours)"| E\["🟣 CLEAN CORE NOW  
Same effort as remediation"\] D -->|"Level 3  
(1-3 days)"| F{"Is it strategic  
for the business?"} D -->|"Level 4-5  
(1+ weeks)"| G\["🔵 REMEDIATE NOW  
Clean Core post-go-live"\] F -->|"Yes — keep  
long term"| H\["🟣 CLEAN CORE NOW"\] F -->|"No — tactical  
/ short term"| I\["🔵 REMEDIATE NOW"\] style C fill:#27ae60,color:#fff style E fill:#6B3FA0,color:#fff style G fill:#3498db,color:#fff style H fill:#6B3FA0,color:#fff style I fill:#3498db,color:#fff

### Typical Distribution

Based on enterprise migration patterns across multiple industries:

Retire — 35%

Remediate — 20%

Clean Core — 45%

Result: **80% Level A at go-live** (35% retired + 45% Clean Core built)

### Sales Order Example — Triage Applied

📋 View Sales Order Triage Example (8 objects)

Custom Object

Purpose

Effort

Lane

Rationale

`Z_SD_ORDER_BDC`

Mass order upload via BDC

L1

RETIRE

API\_SALES\_ORDER\_SRV replaces it entirely

`USEREXIT_SAVE_DOC`

Credit check in MV45AFZZ

L3

CLEAN CORE

Strategic — move to Released BAdI

`ZZ_PROJECT_ID`

Custom field on VBAP

L1

CLEAN CORE

Key User custom field — same effort

`RV61A920`

Volume rebate pricing

L2

CLEAN CORE

Map to released pricing BAdI — 2 hours

`Z_SD_ATP_CUSTOM`

Custom ATP BAdI

L3

CLEAN CORE

Old BAdI deprecated, must use released

`Z_ORDER_CONFIRM_SF`

SmartForm confirmation

L4

REMEDIATE

SmartForm → Adobe = significant effort

`Z_SD_PRICING_ENGINE`

Custom pricing framework

L5

REMEDIATE

Deep kernel coupling — defer to post-go-live

`Z_EDI_ORDER_MAP`

IDoc ORDERS05 extension

L2

CLEAN CORE

Fix field mapping — 3 hours

**Result:** 1 Retire + 5 Clean Core + 2 Remediate = **75% Level A at go-live**

### Procure-to-Pay Example — Triage Applied

📋 View P2P Triage Example (7 objects)

Custom Object

Purpose

Effort

Lane

Rationale

`Z_MM_PR_UPLOAD`

Mass PR creation via BDC

L1

RETIRE

Fiori F1130 (Manage Purchase Requisitions) + API

`USEREXIT_ME_PROCESS`

PO validation in ME\_PROCESS\_PO

L3

CLEAN CORE

Move to Released BAdI ME\_PROCESS\_PO\_CUST

`Z_MM_VENDOR_REPORT`

Vendor consolidated ALV

L2

CLEAN CORE

Replace KNA1/LFA1 reads with I\_Supplier CDS

`Z_GR_AUTO_POST`

Auto GR posting via BAPI

L1

CLEAN CORE

Already uses BAPI — just swap to released version

`Z_MM_INVOICE_CHECK`

3-way match custom logic

L5

REMEDIATE

Deep coupling to MM tables — defer

`Z_MM_PRICE_COMP`

Price comparison report

L1

RETIRE

Standard Fiori analytical app F2231 replaces it

`Z_LSMW_VENDOR`

Vendor master upload via LSMW

L1

RETIRE

Migration Cockpit + API\_BUSINESS\_PARTNER

**Result:** 3 Retire + 3 Clean Core + 1 Remediate = **86% Level A at go-live**

### Finance (R2R) Example — Triage Applied

📋 View R2R Triage Example (6 objects)

Custom Object

Purpose

Effort

Lane

Rationale

`Z_FI_POST_DOCUMENT`

Custom FI posting program

L2

CLEAN CORE

Replace POSTING\_INTERFACE\_DOCUMENT with BAPI\_ACC\_DOCUMENT\_POST

`Z_FI_ASSET_UPLOAD`

Asset master upload via BDC AS01

L1

RETIRE

Migration Cockpit replaces it

`Z_FI_BALANCE_REPORT`

Custom trial balance ALV

L1

RETIRE

Fiori F0996 (Display Financial Statement) replaces it

`Z_FI_TAX_CALC`

Custom tax determination

L5

REMEDIATE

Complex tax logic — defer to post-go-live

`USEREXIT_FI_SUBST`

Account substitution rules

L3

CLEAN CORE

Move to BRF+ rules — strategic for finance

`Z_FI_PAYMENT_RUN`

Custom F110 wrapper

L2

CLEAN CORE

Replace with standard F110 + Released BAdI for custom logic

**Result:** 2 Retire + 3 Clean Core + 1 Remediate = **83% Level A at go-live**

6

## Layer 1: Complete AS-IS Discovery

1

Complete AS-IS Discovery

"What do we have — everything, not just custom code?"

Layer 1 is a **single, comprehensive discovery pass** that inventories the entire process landscape. Unlike traditional assessments that focus only on Z-programs, Layer 1 captures customs, configuration, org structure, integrations, and data profile in one scan.

### Discovery Dimensions

Dimension

What's Discovered

SAP Sources

**Custom Code**

Z/Y programs, classes, function groups, user exits, BAdI implementations, enhancement implementations

TADIR, MODSAP, SXS\_ATTR, SXC\_ATTR

**Custom Data Objects**

Z-tables, custom appends (ZZ/YY fields), custom domains, custom search helps

DD02L, DD03L (ZZ\* fields), DD01L

**Configuration**

Order types, pricing procedures, output determination, partner functions, credit config, release strategies

Process-specific config tables (see below)

**Org Structure**

Company codes, sales orgs, plants, purchasing orgs, shipping points, distribution channels

T001, TVKO, T001W, T024E, TVSTZ, TVKOV

**Integrations**

IDoc extensions, RFC destinations, OData services, file interfaces, workflow templates

EDIFCT, RFCDES, TADIR (IWSV/IWMO), SWF\_\*

**Output/Forms**

SmartForms, SAPscript, Adobe Forms, output condition records

STXFADM, NACE, TNAPR

**Data Profile**

Transaction volumes, date ranges, top document types, master data counts

Process-specific transaction tables

📋 Process-Specific Configuration Tables

Process

Config Tables

**Order-to-Cash (O2C)**

TVAK (order types), T683S (pricing procedures), TNAPR (output), T014 (credit areas), TBE1 (partner det.), TVLK (delivery types), TVFK (billing types), T184 (item categories)

**Procure-to-Pay (P2P)**

T161 (document types), T024 (purchasing groups), T162 (confirmation control), T16FS (release strategy), T166K (tolerance keys), T169 (movement types), NACE (output)

**Record-to-Report (R2R)**

T003 (document types), TBSL (posting keys), T004 (chart of accounts), T042Z (payment methods), T052 (payment terms), T007A (tax procedures), TTZZ (time zones)

**Manufacturing (PP)**

T399D (MTO profiles), T024F (MRP controllers), TCA01 (work centers), T430 (operations), OPJH (order types), T024D (material groups)

### Layer 1 Output

Deliverable

Format

Content

**Custom Object Inventory**

Table (grouped by process step)

Name, type, package, LOC, business purpose, tables accessed

**Config Snapshot**

Table (per config area)

Current config values, active/used flags, dependencies

**Org Structure Map**

Diagram + table

Hierarchical org chart with cross-assignments

**Integration Map**

Table

Direction, protocol, partner, custom objects, volume

**Process Flow**

Mermaid diagram

Step-by-step flow with custom touchpoints marked

**Data Profile**

KPI cards + summary

Transaction volumes, date ranges, concentration

### C16 Automation Level

Layer 1 is **100% automated by C16**. Connect to the customer's ECC system, run the discovery prompts, and the complete inventory is generated within 2-4 hours. No interviews. No spreadsheets. No assumptions.

7

## Layer 2: S/4HANA Standard Delta

2

S/4HANA Standard Delta

"What changes in S/4HANA even if we had zero custom code?"

This is the layer most migrations skip — and the reason they fail. Before mapping any custom object to a standard replacement, you must understand what the standard itself looks like in S/4HANA 2025. The delta between ECC standard and S/4HANA standard is substantial.

### Delta Categories

Category

What Changes

Example

**Transactions Replaced**

SAP GUI transactions replaced by Fiori apps

VA01 → Fiori F1814 (Manage Sales Orders)

**Tables Restructured**

Fields removed, renamed, or moved to new structures

MATNR extended from 18 to 40 characters

**Master Data Model**

Customer/Vendor merged into Business Partner

KNA1 + LFA1 → BUT000 (with compatibility views)

**Simplification Items**

SAP-documented functional changes (Note 2313884)

Credit Management → FSCM integration

**New Capabilities**

Functions available in S/4 that didn't exist in ECC

Advanced ATP, Output Management 2.0, Embedded Analytics

**Config Changes**

Configuration parameters that must be adjusted

Output determination → Output Management migration

**Deprecated Functions**

Features removed or no longer supported

Classic credit management merged into FSCM

📋 O2C Standard Delta — Detailed Example

Process Step

ECC Standard

S/4HANA 2025

Impact

Order Creation

VA01 (SAP GUI)

F1814 (Fiori) + API\_SALES\_ORDER\_SRV

UX change, API-first architecture

Customer Master

XD01/VD01 → KNA1, KNVV

BP transaction → BUT000, I\_Customer CDS

Master data model change — BP migration required

Credit Check

FD32 + VKM1 (classic)

UKM\_BP (FSCM Credit Mgmt) + F1498 Fiori app

New credit engine — config must migrate

Pricing

V/06 condition technique

Simplified condition tables + F1893 Fiori app

Condition table structure simplified

ATP Check

Standard ATP (CO06)

Advanced ATP + aATP (optional)

New capabilities available

Output

NACE + SmartForms

Output Management 2.0 + Adobe Forms + BTP Forms

Completely new output framework

Delivery

VL01N (SAP GUI)

F1703 (Fiori) + API\_OUTBOUND\_DELIVERY\_SRV

UX change, API available

Billing

VF01 (SAP GUI)

F0861 (Fiori) + API\_BILLING\_DOCUMENT\_SRV

UX change, API available

Payment

F-28/F110

F0711 (Fiori) + API\_INCOMING\_PAYMENT\_SRV

UX change, FSCM integration

Reporting

Custom ALV reports

Embedded Analytics (CDS + Fiori tiles)

Reporting paradigm shift

📋 P2P Standard Delta — Detailed Example

Process Step

ECC Standard

S/4HANA 2025

Impact

Purchase Requisition

ME51N (SAP GUI)

F1130 (Fiori) + API\_PURCHASEREQUISITION\_SRV

UX change, self-service enabled

Purchase Order

ME21N (SAP GUI)

F0842 (Fiori) + API\_PURCHASEORDER\_SRV

UX change, API-first

Vendor Master

XK01/MK01 → LFA1, LFB1

BP transaction → BUT000, I\_Supplier CDS

BP migration required

Goods Receipt

MIGO (SAP GUI)

F0842N (Fiori) + API\_MATERIAL\_DOCUMENT\_SRV

UX change

Invoice Verification

MIRO (SAP GUI)

F0859 (Fiori) + API\_SUPPLIERINVOICE\_SRV

UX change, 3-way match enhanced

Payment Run

F110 (SAP GUI)

F0711 / F1609 (Fiori) + FSCM integration

FSCM credit/payment integration

Material Master

MM01 → MARA, MARC

F0842A (Fiori) + I\_Product CDS

MATNR 40 chars, simplified views

MRP

MD01/MD02

MRP Live (MD01N) + Fiori F1983

HANA-optimized MRP engine

### Layer 2 Output

Deliverable

Content

**Transaction Replacement Map**

ECC transaction → Fiori App ID + Released API

**Field Change Register**

Removed, renamed, extended fields per table

**Simplification Item Impact**

All items from SAP Note 2313884 affecting this process

**Config Delta**

Config parameters that must change (output, credit, pricing, etc.)

**New Capabilities Register**

S/4 functions the customer can NOW adopt

**BP Migration Scope**

Customer/vendor tables requiring BP migration

8

## Layer 3: Fit-to-Standard Analysis

3

Fit-to-Standard Analysis

"What fits, what gaps — and what's the right lane for each object?"

This is the decision layer. Armed with the complete AS-IS inventory (Layer 1) and the S/4HANA standard baseline (Layer 2), Layer 3 classifies every custom object and configuration item, then triages each into the right execution lane.

### Dual Classification

Layer 3 produces **two classifications per object**:

Classification

Purpose

Values

**Fit-to-Standard**

Can S/4 standard replace this?

FIT FIT WITH CONFIG FIT WITH EXTENSION GAP

**Triage Lane**

What action for this object?

RETIRE REMEDIATE CLEAN CORE

### Classification → Triage Mapping

Fit-to-Standard

Effort Level

→ Triage Lane

FIT

Any

RETIRE — standard replaces it

FIT WITH CONFIG

Level 1-2

CLEAN CORE — configure using released tooling

FIT WITH CONFIG

Level 3+

CLEAN CORE or REMEDIATE — depends on strategic value

FIT WITH EXTENSION

Level 1-3

CLEAN CORE — build compliant extension

FIT WITH EXTENSION

Level 4-5

REMEDIATE — defer Clean Core

GAP

Level 1-3

CLEAN CORE — build with released APIs

GAP

Level 4-5

REMEDIATE — make it work, improve later

### Layer 3 Output — The Master Triage Matrix

This is the single most important deliverable of the entire framework. Every subsequent layer executes based on this matrix:

#

Object

Process Step

Fit-to-Standard

Effort Level

Lane

Standard Alternative

1

`Z_SD_ORDER_BDC`

Order Creation

FIT

L1

RETIRE

API\_SALES\_ORDER\_SRV

2

`USEREXIT_SAVE_DOC`

Order Creation

FIT WITH EXT

L3

CLEAN CORE

Released BAdI SD\_SALES\_DOC\_CHECK

3

`RV61A920`

Pricing

FIT WITH CONFIG

L2

CLEAN CORE

Released Pricing BAdI

4

`Z_SD_PRICING_FW`

Pricing

GAP

L5

REMEDIATE

No standard — defer

... continues for every object discovered in Layer 1 ...

### Coverage Calculations

Layer 3 calculates coverage at multiple levels:

Metric

Formula

Purpose

**Standard Coverage %**

(FIT + FIT WITH CONFIG) ÷ Total Objects

How much does S/4 standard cover out-of-the-box?

**Extended Coverage %**

(FIT + CONFIG + EXTENSION) ÷ Total

How much can be covered with compliant extensions?

**Level A at Go-Live %**

(Retire + Clean Core objects) ÷ Total

Projected Clean Core percentage at launch

**Post-Go-Live Backlog**

Count of REMEDIATE lane objects

How many objects need future conversion waves?

### Verdict Thresholds

Overall Coverage

Verdict

What It Means

≥ 90%

**ADOPT**

Standard covers almost everything — minimal custom work

≥ 70%

**SIMPLIFY**

Standard covers most — configuration + minor extensions

50-70%

**MODERNIZE**

Significant extensions needed — but standard is the foundation

< 50%

**KEEP**

Heavy customisation — justified custom with progressive improvement

9

## Layer 4: Remediation & Clean Core Build

4

Remediation & Clean Core Build

"Do the work — and do it right the first time where it makes sense."

Layer 4 executes the triage decisions from Layer 3 through three parallel sub-lanes. The critical design principle: **never write throwaway code**. If Clean Core effort is within 1 day of remediation effort, build Clean Core immediately.

### Sub-Lane 4A: Retire

Action

Deliverable

Document the retirement decision

Retirement justification per object

Map to standard replacement

Fiori App ID + API name + CDS view

Identify users/roles affected

User impact assessment

Document data migration path

How historical data remains accessible

Create switch-off plan

Sequence for decommissioning

### Sub-Lane 4B: Remediate (Level B/C — Minimum Changes)

Fix Type

What Changes

Example

**BP migration references**

KNA1/LFA1 direct reads → compatibility views or BP APIs

`SELECT FROM kna1` → `SELECT FROM kna1` (compatibility view exists)

**Deprecated FM replacement**

Obsolete FMs → successor FMs (not necessarily Released)

`WS_UPLOAD` → `GUI_UPLOAD`

**Field changes**

Removed/moved fields adjusted

MATNR length handling (18→40)

**Syntax compatibility**

ABAP statements that won't compile on S/4

Removed TABLES declarations, obsolete WRITE formats

⚠️ Remediated Objects Are Technical Debt

Every remediated (Level B/C) object is tagged in the backlog for progressive Clean Core conversion in post-go-live waves. Layer 5 tracks this backlog and Layer 6 schedules the waves.

### Sub-Lane 4C: Clean Core Build (Level A — Right the First Time)

Pattern

ECC Pattern

Clean Core Pattern

Effort

**Table Access**

SELECT FROM standard\_table

SELECT FROM I\_CDS\_View (released)

Level 1

**API Call**

CALL FUNCTION 'unreleased\_fm'

CALL FUNCTION 'BAPI\_\*' (released)

Level 2

**Enhancement**

User exit / Classic BAdI

Released BAdI implementation

Level 3

**Custom Fields**

ZZ\* append on standard table

Key User Extensibility (custom fields app)

Level 2

**Business Rules**

Hardcoded IF/ELSE in ABAP

BRF+ decision tables (business-maintainable)

Level 3

**Integration**

Custom RFC / IDoc extension

Event Mesh + Integration Suite

Level 3

**Reporting**

Custom ALV report (REUSE\_ALV)

CDS analytical view + Fiori tile

Level 2

**Output**

SmartForm / SAPscript

Adobe Form + Output Management 2.0

Level 4

### Layer 4 Output

Deliverable

Content

**Retirement Register**

Objects retired, standard replacement, user impact, data path

**Config Migration Guide**

Step-by-step SPRO/IMG configuration changes required

**BP Migration Approach**

Customer/vendor conversion scope, field mapping, synchronisation rules

**Remediated Code**

S/4-compatible code (Level B/C) — deployable, tested

**Clean Core Code**

Level A code — Released BAdIs, APIs, CDS views — deployable, tested

**Technical Debt Backlog**

Remediated objects tagged for post-go-live Clean Core waves

10

## Layer 5: Certification & Validation

5

Certification & Validation

"Prove everything is cloud-ready and working."

Layer 5 does NOT rewrite anything — that work was done in Layer 4. Layer 5 **verifies** that the work was done correctly. It certifies Clean Core compliance, validates functionality, and produces the evidence package.

### Certification Activities

Check

Tool/Method

Pass Criteria

**Clean Core Score**

ATC with ABAP\_CLOUD\_READINESS variant

All Clean Core objects = Level A (zero B/C/D findings)

**Released API Verification**

Cloudification catalog check per dependency

Every external reference is in the SAP released API list

**Syntax Check**

ADT syntax validation

Zero compilation errors

**ATC Quality**

ATC full variant (not just cloud readiness)

Zero critical findings, warnings documented

**Unit Tests**

ABAP Unit test execution

All test classes pass

**Regression Scenarios**

C16-generated test scenarios from code analysis

Business-critical paths covered

### The Progression Scorecard

The hero metric — the one number that tells the board "how far along are we?"

Level

Before (Layer 1)

After (Layer 4)

Target (Post-Go-Live)

Level A — Cloud-Ready

0%

70-80%

90%+

Level B — Classic API

30%

10-15%

5%

Level C — Non-Compliant

50%

5-10%

2%

Level D — Critical

20%

0%

0%

### Layer 5 Output

Deliverable

Content

**Clean Core Certification Report**

Per-object Level A/B/C/D score with evidence

**Progression Scorecard**

Before/After KPI with % at each level

**ATC Results Package**

Full ATC findings for audit trail

**Test Scenario Library**

Business test cases per process step

**Technical Debt Register**

Remediated objects with scheduled Clean Core wave

11

## Layer 6: Handoff & Go-Live Readiness

6

Handoff & Go-Live Readiness

"Package everything for the implementation team and go-live."

Layer 6 assembles the transformation outputs into a structured handoff package that the customer's implementation team (internal or SI partner) can execute. It also defines the post-go-live progressive Clean Core roadmap.

### Handoff Package Contents

Package Section

Content

Consumer

**Transformation Summary**

Executive overview: scope, objects, coverage, Level A %, timeline

Steering Committee

**Retirement Package**

Objects to decommission, switch-off sequence, standard replacements

Functional Leads

**Config Migration Guide**

Step-by-step SPRO/IMG configuration for S/4HANA

Functional Consultants

**BP Migration Plan**

Customer/vendor conversion scope, field mapping, sync rules

Master Data Team

**Code Deployment Package**

All remediated + Clean Core code with activation sequence

ABAP Development Team

**Test Scenario Library**

Business test cases per process step with expected results

Testing / QA Team

**Clean Core Scorecard**

Level A/B/C/D per object with evidence trail

Architecture / Governance

**Technical Debt Backlog**

Remediated objects with priority and scheduled wave

Post-Go-Live Team

**Post-Go-Live Roadmap**

Quarterly wave plan to reach 90% Level A

CTO / Architecture

### Post-Go-Live Progressive Clean Core Roadmap

gantt title Progressive Clean Core — Post-Go-Live Waves dateFormat YYYY-MM-DD axisFormat %b %Y section Go-Live S/4HANA Go-Live :milestone, m1, 2026-06-01, 0d section Wave 1 (Q3 2026) Level 3 objects (5-8) :w1a, 2026-07-01, 60d Validation & ATC :w1b, after w1a, 14d section Wave 2 (Q4 2026) Level 3-4 objects (5-8) :w2a, 2026-10-01, 60d Validation & ATC :w2b, after w2a, 14d section Wave 3 (Q1 2027) Level 4 objects (3-5) :w3a, 2027-01-15, 60d Validation & ATC :w3b, after w3a, 14d section Wave 4 (Q2 2027) Level 5 objects (2-3) :w4a, 2027-04-01, 90d Final Certification :w4b, after w4a, 14d section Target 90% Level A Target :milestone, m2, 2027-07-01, 0d

Each wave targets 5-8 objects, prioritised by business value and dependency order. The target is **90% Level A within 12 months of go-live**.

12

## The Journey — Progressive Clean Core

Clean Core is a journey, not a gate. You don't need 100% Level A to go live. You need everything **working** on S/4HANA, strategic objects at Level A, and a roadmap to progressively convert the rest.

graph LR subgraph "PRE-GO-LIVE" A\["35% RETIRED  
(Lane: Retire)"\] B\["45% LEVEL A  
(Lane: Clean Core)"\] C\["20% LEVEL B/C  
(Lane: Remediate)"\] end subgraph "POST-GO-LIVE" D\["Wave 1  
Q3: +5%"\] E\["Wave 2  
Q4: +5%"\] F\["Wave 3  
Q1: +5%"\] G\["Wave 4  
Q2: +5%"\] end H\["TARGET  
90% Level A"\] A --> H B --> H C --> D --> E --> F --> G --> H style A fill:#27ae60,color:#fff style B fill:#6B3FA0,color:#fff style C fill:#3498db,color:#fff style H fill:#27ae60,color:#fff

"Go live with everything WORKING on S/4HANA. Go live with 70-80% at Clean Core Level A. Convert the remaining 20% in quarterly waves. Reach 90% Level A within 12 months of go-live."

— The Practical Path to Clean Core

### Progression Timeline

Milestone

Level A %

What Happened

**ECC Baseline**

0%

Starting point — all custom code

**Layer 3 Complete**

0% (planned)

Every object triaged — 35% marked Retire, 45% marked Clean Core

**Layer 4 Complete**

~80%

Retirements executed, Clean Core objects built, remediated objects working

**Go-Live**

~80%

Everything working on S/4, 80% already Level A

**Go-Live +6 months**

~87%

Waves 1-2 converted additional objects

**Go-Live +12 months**

~93%

Waves 3-4 completed — target reached

13

## C16 Platform Capability Matrix

C16 automates the analysis-heavy layers (1-3, 5) and generates the build artifacts for Layer 4. Layer 6 is a packaging exercise. Here's the honest capability breakdown:

Capability

Layer

Automation

How

Discover all custom objects

1

✅ Full Auto

Scans TADIR, MODSAP, SXS\_ATTR, DD03L across entire system

Read and understand source code

1

✅ Full Auto

Fetches every line, extracts business purpose, maps tables

Read configuration tables

1

✅ Full Auto

Queries all process-specific config tables

Map org structure

1

✅ Full Auto

Reads T001, T001W, TVKO, T024E and all org assignments

Identify S/4HANA standard changes

2

✅ Full Auto

Reads simplification items (Note 2313884), field changes, Fiori catalog

Map Fiori apps and released APIs

2

✅ Full Auto

Searches SAP API Hub, knows complete Fiori app catalog

Classify FIT/GAP per requirement

3

✅ Full Auto

AI-powered classification from source code analysis

Classify Effort Level (1-5)

3

✅ Full Auto

Pattern detection: table swap, API swap, BAdI swap, BDC, framework

Triage decision (Retire/Remediate/CC)

3

⚡ Auto-Recommend

C16 recommends lane, customer confirms strategic objects

Generate remediated code

4

✅ Full Auto

Produces S/4-compatible ABAP, verified field references

Generate Clean Core code

4

✅ Full Auto

Released BAdI classes, API calls, CDS view references

Config migration guide

4

⚡ Guided

Documents what needs to change. Customer executes in SPRO.

BP migration approach

4

⚡ Guided

Analyses scope and field mapping. Migration tooling runs separately.

SmartForm → Adobe conversion

4

✅ Full Auto

Downloads SmartForm, generates XDP, deploys Adobe Form

BRF+ rule extraction

4

⚡ Guided

Extracts hardcoded rules from ABAP. BRF+ config is manual.

Clean Core certification

5

✅ Full Auto

ATC cloud readiness, dependency classification, scoring

Test scenario generation

5

✅ Full Auto

Generates scenarios from code analysis. Execution is customer.

E2E test execution

5

📋 Advisory

Customer executes tests in their test system

Handoff package assembly

6

✅ Full Auto

Aggregates all layer outputs into structured package

Cutover planning

6

📋 Advisory

Customer's PMO/SI owns cutover execution

✅ Bottom Line

**18 of 21 capabilities** are either fully automated or guided by C16. Only 3 capabilities (E2E test execution, cutover planning, BRF+ configuration) require customer-side execution without C16 automation.

14

## Execution Timeline — Reference Plan

Timeline varies by process complexity and custom object count. This reference is for a single business process (e.g., O2C or P2P) with 50-100 custom objects.

gantt title 6-Layer Execution — Single Process Area dateFormat YYYY-MM-DD axisFormat %b %d section Phase 1: DISCOVER Layer 1 - Complete AS-IS :l1, 2026-05-01, 5d Layer 2 - Standard Delta :l2, after l1, 5d Review Gate 1 :milestone, rg1, after l2, 0d section Phase 2: ANALYSE Layer 3 - Fit-to-Standard :l3, after l2, 10d Triage Decisions (with customer) :td, after l3, 3d Review Gate 2 :milestone, rg2, after td, 0d section Phase 3: BUILD Lane A - Retire (documentation) :l4a, after td, 5d Lane B - Remediate (code) :l4b, after td, 15d Lane C - Clean Core (code) :l4c, after td, 20d Config Migration Guide :l4d, after td, 10d Review Gate 3 :milestone, rg3, after l4c, 0d section Phase 4: PROVE Layer 5 - Certification :l5, after l4c, 5d Layer 6 - Handoff Package :l6, after l5, 5d Final Review Gate :milestone, rg4, after l6, 0d

### Time Comparison

Approach

Duration (per process)

Consultants Needed

Output Quality

**Traditional (manual)**

6-8 weeks

2-3 senior consultants

Interview-based, subjective, incomplete discovery

**Tool-assisted (smartShift etc.)**

3-4 weeks

1-2 consultants + tool

Code-level only, no config/process analysis

**C16 6-Layer Framework**

8-10 working days

1 consultant + C16

Code + config + process, exhaustive discovery, deployable artifacts

15

## Cross-Process Examples

The 6-Layer Framework is process-agnostic. It works identically across all SAP process areas. The only difference is the configuration tables and standard alternatives that Layer 1-3 reference.

🛒 Order-to-Cash (O2C) — Entry: Inquiry / Exit: Payment Received

#### Process Steps

Inquiry (VA11) → Quotation (VA21) → Sales Order (VA01) → Pricing (VK11) → ATP Check → Credit Check (VKM1) → Delivery (VL01N) → Goods Issue → Billing (VF01) → Payment (F-28)

#### Typical Custom Object Distribution

Process Step

Typical # Objects

Common Customs

Order Creation

15-25

User exits (MV45AFZZ), BAdIs, custom fields, BDC uploads

Pricing

10-15

Custom pricing routines (RV61A\*), custom condition types

Delivery

5-10

Delivery BAdIs, packing logic, route determination

Billing

5-10

Billing BAdIs, custom invoice forms, tax determination

Output

5-8

SmartForms, SAPscript, custom print programs

Integration

5-10

EDI (ORDERS05), RFC to CRM/portal, OData services

#### Key S/4HANA Changes

Customer Master → Business Partner (BP). Credit Management → FSCM. Output → Output Management 2.0. All transactions → Fiori apps.

📦 Procure-to-Pay (P2P) — Entry: Purchase Requisition / Exit: Payment Run

#### Process Steps

Purchase Requisition (ME51N) → Approval/Release → Purchase Order (ME21N) → Goods Receipt (MIGO) → Invoice Verification (MIRO) → Payment Run (F110)

#### Typical Custom Object Distribution

Process Step

Typical # Objects

Common Customs

PR/PO Creation

10-20

ME\_PROCESS\_PO BAdI, release strategy exits, BDC uploads

Goods Receipt

5-10

GR posting customisation, quality inspection integration

Invoice Verification

5-10

3-way match custom logic, tolerance handling

Payment

3-5

Custom payment method handling, bank statement processing

Vendor Master

5-8

Custom vendor reports, vendor evaluation logic

Reporting

5-10

Custom ALV reports, spend analysis programs

#### Key S/4HANA Changes

Vendor Master → Business Partner (BP). MRP → MRP Live (HANA-optimised). Material Number → 40 characters. Central Purchasing possible. All transactions → Fiori apps.

📊 Record-to-Report (R2R) — Entry: Journal Posting / Exit: Financial Statements

#### Process Steps

Journal Entry (FB01) → Period-End Close (FAGL\_FC) → Reconciliation → Intercompany → Tax Reporting → Financial Statements

#### Typical Custom Object Distribution

Process Step

Typical # Objects

Common Customs

Journal Posting

5-10

Substitution/validation rules, custom posting programs

Period-End

5-8

Custom close programs, accrual automation

Asset Accounting

3-5

Custom depreciation reports, asset upload programs

Tax

3-5

Custom tax determination, tax reporting programs

Reporting

10-15

Custom financial reports, balance confirmations

Integration

3-5

Bank statement processing, tax authority interfaces

#### Key S/4HANA Changes

Universal Journal (ACDOCA) replaces multiple summary tables. New GL active by default. Asset Accounting simplified. Real-time consolidation possible. Embedded Analytics replaces most custom reports.

🏭 Make-to-Order (MTO) — Entry: Sales Order / Exit: Settlement

#### Process Steps

Sales Order (VA01) → BOM Explosion (CS01) → MRP → Production Order (CO01) → Shop Floor Confirmation (CO11N) → Goods Issue → Delivery → Settlement

#### Typical Custom Object Distribution

Process Step

Typical # Objects

Common Customs

BOM/Routing

5-10

BOM BAdIs, custom routing logic, variant configuration

Production Order

10-15

CO01 enhancements, capacity planning custom logic

Shop Floor

5-8

Confirmation RFCs, cost collection, work centre integration

Material Staging

5-10

Custom reservation programs, warehouse integration

Settlement

3-5

Custom settlement rules, variance analysis

#### Key S/4HANA Changes

PP/DS replaces classic MRP for MTO. Embedded PP/DS in S/4. Real-time capacity checks. Fiori apps for production operator. HANA-optimised MRP Live.

👥 Hire-to-Retire (HR) — Entry: Hiring / Exit: Termination

#### Process Steps

Recruitment → Hiring (PA40) → Org Management (PPOME) → Time Management (PA61) → Payroll (PC00\_M\*) → Benefits → Separation

#### Key S/4HANA / SuccessFactors Considerations

Many customers move to SuccessFactors for core HR. Payroll can stay on-premise or move to Employee Central Payroll. The 6-Layer Framework maps customs against SuccessFactors standard + on-premise retention.

16

## Value Proposition & ROI

75%

Faster than manual assessment  
(10 days vs 6-8 weeks per process)

100%

Code coverage  
(reads every line, not interview-based)

80%

Level A at go-live  
(not 0% with "future roadmap")

6

Complete layers  
(code + config + process + validation)

### What Sets This Apart

Differentiator

Traditional Approach

C16 6-Layer Framework

**Discovery method**

Interviews + workshop + spreadsheets

Automated system scan — reads every line of code and config table

**Coverage**

Finds objects people remember

Finds objects nobody remembers — buried enhancements, forgotten exits

**Standard baseline**

Assumed (often wrong)

Explicitly mapped — Layer 2 documents every S/4 standard change

**Configuration**

Afterthought (last 2 weeks)

First-class — discovered, delta'd, and migration-planned from day one

**Triage**

Binary: migrate or rewrite

Three lanes: Retire / Remediate / Clean Core — with effort level precision

**Code output**

Recommendations only

Deployable code — remediated and Clean Core, ready for transport

**Clean Core strategy**

"We'll do it later" (never happens)

80% done at go-live + scheduled post-go-live waves with tracking

**Validation**

None (hope for the best)

Layer 5 certification + test scenarios + ATC evidence

"The difference between a 6-week manual assessment and a 10-day C16 assessment isn't just speed — it's completeness. C16 reads 100% of the code. A consultant reads the code that people point them to. The bugs, the risk, the migration failures — they live in the code nobody pointed to."

**C16 Enterprise 6-Layer S/4HANA Migration Framework** — Version 2.0 — April 2026

This framework is process-agnostic and applicable to any SAP ECC → S/4HANA migration across all industry sectors.

Generated by **C16 AI Platform** — Enterprise SAP Intelligence

Methodology powered by: automated TADIR/MODSAP/SXS\_ATTR system scanning, SAP Simplification List (Note 2313884) mapping, SAP API Hub integration, Clean Core cloudification catalog classification, ATC ABAP\_CLOUD\_READINESS analysis, and AI-powered source code understanding. No interviews required.

mermaid.initialize({ startOnLoad: true, theme: 'base', themeVariables: { primaryColor: '#6B3FA0', primaryTextColor: '#fff', primaryBorderColor: '#B5567A', lineColor: '#B5567A', secondaryColor: '#f0e6ff', tertiaryColor: '#f8f9fa' } });

**C16 — AI-Powered SAP Analysis**  
_Generated by C16. This document is AI-generated and should be validated by a qualified SAP consultant before implementation. All data sourced from the connected SAP system._