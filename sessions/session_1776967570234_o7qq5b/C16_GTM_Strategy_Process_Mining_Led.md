  C16 Go-to-Market Strategy — Process Mining-Led Land & Expand @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap'); :root { --c16-copper: #C97B3A; --c16-rose: #B5567A; --c16-purple: #6B3FA0; --c16-dark: #1a1a2e; --c16-light: #f8f9fc; --accent-green: #27ae60; --accent-blue: #3498db; --accent-orange: #e67e22; --accent-red: #e74c3c; --text-primary: #2c3e50; --text-secondary: #5a6c7d; } \* { margin: 0; padding: 0; box-sizing: border-box; } body { font-family: 'Inter', 'Segoe UI', Arial, sans-serif; color: var(--text-primary); background: #e9ecef; line-height: 1.7; font-size: 15px; } .doc-wrapper { max-width: 1140px; margin: 0 auto; background: #fff; box-shadow: 0 4px 24px rgba(0,0,0,0.10); border-radius: 12px; overflow: hidden; } /\* === HEADER BANNER === \*/ .header-banner { background: linear-gradient(135deg, var(--c16-copper), var(--c16-rose), var(--c16-purple)); color: #fff; padding: 50px 48px 40px; position: relative; overflow: hidden; } .header-banner::before { content: ''; position: absolute; top: -60%; right: -20%; width: 500px; height: 500px; border-radius: 50%; background: rgba(255,255,255,0.06); } .header-banner::after { content: ''; position: absolute; bottom: -40%; left: -10%; width: 400px; height: 400px; border-radius: 50%; background: rgba(255,255,255,0.04); } .header-banner img { height: 55px; margin-bottom: 16px; border-radius: 10px; position: relative; z-index: 2; } .header-banner h1 { font-size: 2.4em; font-weight: 800; letter-spacing: -0.5px; margin-bottom: 6px; position: relative; z-index: 2; } .header-banner .subtitle { font-size: 1.15em; font-weight: 300; opacity: 0.92; position: relative; z-index: 2; margin-bottom: 16px; } .header-banner .version-badge { display: inline-block; background: rgba(255,255,255,0.18); border: 1px solid rgba(255,255,255,0.3); border-radius: 20px; padding: 4px 16px; font-size: 0.82em; font-weight: 500; position: relative; z-index: 2; } /\* === META BAR === \*/ .meta-bar { background: #f0f2f5; padding: 16px 48px; display: flex; flex-wrap: wrap; gap: 28px; border-bottom: 1px solid #e2e6ea; font-size: 0.88em; } .meta-item { display: flex; align-items: center; gap: 6px; } .meta-label { font-weight: 600; color: var(--c16-purple); } .meta-value { color: var(--text-secondary); } /\* === TOC === \*/ .toc { padding: 32px 48px; background: #fafbfd; border-bottom: 2px solid var(--c16-purple); } .toc h2 { font-size: 1.15em; font-weight: 700; color: var(--c16-purple); margin-bottom: 14px; text-transform: uppercase; letter-spacing: 1px; } .toc-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 6px 40px; } .toc a { color: var(--text-primary); text-decoration: none; font-size: 0.92em; padding: 4px 0; display: block; border-bottom: 1px dotted #ddd; transition: color 0.2s; } .toc a:hover { color: var(--c16-purple); } .toc .toc-num { display: inline-block; width: 28px; height: 28px; background: var(--c16-rose); color: #fff; border-radius: 50%; text-align: center; line-height: 28px; font-size: 0.78em; font-weight: 700; margin-right: 8px; } /\* === SECTIONS === \*/ .section { padding: 40px 48px; border-bottom: 1px solid #eef0f3; } .section:last-child { border-bottom: none; } .section-title { font-size: 1.55em; font-weight: 700; color: var(--c16-purple); margin-bottom: 24px; padding-bottom: 12px; border-bottom: 3px solid var(--c16-rose); display: flex; align-items: center; gap: 14px; } .section-num { display: inline-flex; align-items: center; justify-content: center; width: 38px; height: 38px; background: var(--c16-rose); color: #fff; border-radius: 50%; font-size: 0.75em; font-weight: 800; flex-shrink: 0; } h3 { font-size: 1.15em; font-weight: 700; color: var(--c16-dark); margin: 28px 0 12px; padding-left: 14px; border-left: 4px solid var(--c16-copper); } h4 { font-size: 1.02em; font-weight: 600; color: var(--c16-purple); margin: 20px 0 10px; } p { margin-bottom: 14px; } /\* === TABLES === \*/ table { width: 100%; border-collapse: collapse; margin: 16px 0 24px; font-size: 0.92em; } thead th { background: var(--c16-purple); color: #fff; padding: 12px 14px; text-align: left; font-weight: 600; font-size: 0.88em; text-transform: uppercase; letter-spacing: 0.5px; } tbody td { padding: 10px 14px; border-bottom: 1px solid #eee; } tbody tr:nth-child(even) { background: #f8fafc; } tbody tr:hover { background: #edf2f7; } /\* === CALLOUT BOXES === \*/ .callout { border-radius: 10px; padding: 22px 26px; margin: 20px 0; } .callout-insight { background: linear-gradient(135deg, #f0e6ff, #e8f4fd); border-left: 5px solid var(--c16-purple); } .callout-warning { background: #fff8e6; border-left: 5px solid var(--accent-orange); } .callout-success { background: #f0faf4; border-left: 5px solid var(--accent-green); } .callout-critical { background: #fef0f0; border-left: 5px solid var(--accent-red); } .callout-title { font-weight: 700; font-size: 1.02em; margin-bottom: 8px; display: flex; align-items: center; gap: 8px; } /\* === KPI CARDS === \*/ .kpi-row { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 16px; margin: 20px 0; } .kpi-card { background: linear-gradient(135deg, #f8f9fc, #eef0f5); border-radius: 12px; padding: 22px; text-align: center; border: 1px solid #e0e4ea; transition: transform 0.2s; } .kpi-card:hover { transform: translateY(-2px); } .kpi-value { font-size: 2em; font-weight: 800; color: var(--c16-purple); margin-bottom: 4px; } .kpi-label { font-size: 0.82em; color: var(--text-secondary); font-weight: 500; text-transform: uppercase; letter-spacing: 0.5px; } /\* === BADGES === \*/ .badge { display: inline-block; padding: 3px 12px; border-radius: 14px; font-size: 0.8em; font-weight: 600; color: #fff; } .badge-land { background: var(--accent-green); } .badge-expand { background: var(--accent-blue); } .badge-scale { background: var(--c16-purple); } .badge-critical { background: var(--accent-red); } .badge-high { background: var(--accent-orange); } .badge-medium { background: var(--accent-blue); } /\* === PHASE CARDS === \*/ .phase-card { border-radius: 12px; padding: 28px; margin: 20px 0; border: 2px solid; } .phase-land { border-color: var(--accent-green); background: linear-gradient(135deg, #f0faf4, #e8f8ed); } .phase-expand { border-color: var(--accent-blue); background: linear-gradient(135deg, #eef6fd, #e4f0fa); } .phase-scale { border-color: var(--c16-purple); background: linear-gradient(135deg, #f0e6ff, #ebe0fa); } .phase-title { font-size: 1.3em; font-weight: 800; margin-bottom: 8px; } .phase-subtitle { font-size: 0.92em; color: var(--text-secondary); margin-bottom: 16px; font-style: italic; } /\* === FLOW ARROWS === \*/ .flow-container { display: flex; align-items: center; justify-content: center; gap: 0; margin: 30px 0; flex-wrap: wrap; } .flow-step { background: linear-gradient(135deg, var(--c16-purple), var(--c16-rose)); color: #fff; padding: 16px 28px; border-radius: 10px; text-align: center; font-weight: 600; font-size: 0.92em; min-width: 160px; } .flow-arrow { font-size: 1.8em; color: var(--c16-copper); padding: 0 8px; font-weight: 300; } /\* === QUOTE BOX === \*/ .quote-box { background: var(--c16-dark); color: #fff; padding: 30px 36px; border-radius: 12px; margin: 24px 0; position: relative; } .quote-box::before { content: '"'; position: absolute; top: 10px; left: 16px; font-size: 4em; opacity: 0.15; font-family: Georgia, serif; } .quote-text { font-size: 1.1em; font-style: italic; line-height: 1.7; margin-bottom: 10px; } .quote-attr { font-size: 0.88em; opacity: 0.7; text-align: right; } /\* === PERSONA CARD === \*/ .persona-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 18px; margin: 20px 0; } .persona-card { border-radius: 10px; padding: 22px; border: 1px solid #e0e4ea; background: #fafbfd; } .persona-role { font-weight: 700; color: var(--c16-purple); font-size: 1.05em; margin-bottom: 4px; } .persona-pain { font-size: 0.88em; color: var(--accent-red); font-weight: 500; margin-bottom: 8px; } .persona-message { font-size: 0.9em; color: var(--text-secondary); } /\* === PLAYBOOK STEP === \*/ .playbook-step { display: flex; gap: 20px; margin: 18px 0; padding: 20px; background: #fafbfd; border-radius: 10px; border: 1px solid #e8eaef; } .step-num { width: 44px; height: 44px; background: linear-gradient(135deg, var(--c16-copper), var(--c16-rose)); color: #fff; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 800; font-size: 1.1em; flex-shrink: 0; } .step-content { flex: 1; } .step-title { font-weight: 700; font-size: 1.02em; margin-bottom: 6px; } .step-detail { font-size: 0.92em; color: var(--text-secondary); } /\* === COMPARISON TABLE === \*/ .vs-table { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin: 20px 0; } .vs-card { border-radius: 10px; padding: 24px; border: 2px solid; } .vs-before { border-color: var(--accent-red); background: #fef8f8; } .vs-after { border-color: var(--accent-green); background: #f6fef9; } .vs-label { font-weight: 800; font-size: 0.82em; text-transform: uppercase; letter-spacing: 1px; margin-bottom: 12px; } /\* === OBJECTION HANDLER === \*/ .objection-card { background: #fff; border: 1px solid #e0e4ea; border-radius: 10px; margin: 14px 0; overflow: hidden; } .objection-q { background: #fef0f0; padding: 14px 20px; font-weight: 600; font-size: 0.95em; color: var(--accent-red); border-left: 4px solid var(--accent-red); } .objection-a { padding: 14px 20px; font-size: 0.92em; color: var(--text-primary); border-left: 4px solid var(--accent-green); background: #f6fef9; } /\* === TIMELINE === \*/ .timeline { position: relative; padding-left: 36px; margin: 20px 0; } .timeline::before { content: ''; position: absolute; left: 14px; top: 0; bottom: 0; width: 3px; background: linear-gradient(var(--accent-green), var(--accent-blue), var(--c16-purple)); border-radius: 3px; } .timeline-item { position: relative; margin-bottom: 24px; padding: 16px 20px; background: #fafbfd; border-radius: 10px; border: 1px solid #e8eaef; } .timeline-item::before { content: ''; position: absolute; left: -28px; top: 20px; width: 12px; height: 12px; border-radius: 50%; background: var(--c16-rose); border: 3px solid #fff; } .timeline-label { font-weight: 700; color: var(--c16-purple); font-size: 0.88em; margin-bottom: 4px; } /\* === FOOTER === \*/ .doc-footer { background: var(--c16-dark); color: rgba(255,255,255,0.7); padding: 32px 48px; font-size: 0.85em; } .doc-footer strong { color: rgba(255,255,255,0.9); } /\* === PRINT === \*/ @media print { body { background: #fff; } .doc-wrapper { box-shadow: none; max-width: 100%; } .header-banner { -webkit-print-color-adjust: exact; print-color-adjust: exact; } .section { page-break-inside: avoid; } .toc { page-break-after: always; } } /\* === RESPONSIVE === \*/ @media (max-width: 768px) { .header-banner, .section, .meta-bar, .toc { padding-left: 24px; padding-right: 24px; } .toc-grid, .persona-grid, .vs-table { grid-template-columns: 1fr; } .flow-container { flex-direction: column; } .flow-arrow { transform: rotate(90deg); } .kpi-row { grid-template-columns: 1fr 1fr; } }

![C16](data:image/jpeg;base64,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)

# C16 Go-to-Market Sales Strategy

Process Mining-Led Land & Expand — Crossing the Chasm with Data, Not Demos

Strategic Playbook v2.0 — April 2026

Framework:Crossing the Chasm (Moore) + The Challenger Sale (Dixon & Adamson)

Lead Wedge:Process Mining & Business Intelligence

Target:Enterprise SAP Customers (ECC → S/4HANA migration wave)

Prepared:23 April 2026

## 📋 Strategic Contents

[1 The Core Thesis — Why Process Mining Leads](#thesis) [2 Crossing the Chasm — The Technology Adoption Problem](#chasm) [3 Beachhead Market Selection](#beachhead) [4 The Whole Product — Process Mining as the Trojan Horse](#whole-product) [5 Land & Expand — The Three-Phase Revenue Engine](#land-expand) [6 The Challenger Sale — Teaching Customers What They're Missing](#challenger) [7 Buyer Personas & Stakeholder Mapping](#personas) [8 The 60-Minute Demo Playbook — "Show, Don't Tell"](#playbook) [9 Objection Handling Matrix](#objections) [10 Competitive Positioning — C16 vs. The Field](#competitive) [11 Pricing Architecture — Process Mining Entry Point](#pricing) [12 Sales Metrics & Success Criteria](#metrics) [13 The Customer Journey — From Curiosity to Champion](#customer-journey) [14 Content Strategy & Demand Generation](#content) [15 Channel & Partnership Strategy](#channels) [16 90-Day Launch Plan](#90day)

1 The Core Thesis — Why Process Mining Leads

"The biggest risk isn't that the technology doesn't work — it's that you can't prove value before the budget committee loses patience. Process Mining gives you a win in the first meeting, not the first quarter."

— The C16 Sales Thesis

C16 is not one product — it's an **agentic platform** with 18 specialized capabilities spanning process intelligence, code analysis, Clean Core migration, RAP/Fiori generation, SmartForm conversion, and more. But here's the strategic problem: _pitching everything at once overwhelms conservative enterprise SAP buyers and diffuses your value proposition into noise._

The solution comes from Geoffrey Moore's _Crossing the Chasm_: **pick one killer use case, dominate it, then expand.** That use case is **Process Mining**.

### Why Process Mining Is the Perfect Lead Wedge

Dimension

Process Mining

Code Analysis / Clean Core

Code Generation / RAP

**Time to Value**

⚡ Minutes — connect to SAP, get instant insights

⏱️ Hours — need to identify programs, run analysis

📅 Days/Weeks — requires architecture decisions

**Buyer Persona**

🎯 Business (CFO, VP Ops, Process Owner)

👨‍💻 Technical (Development Lead, Basis)

👨‍💻 Technical (Development Team)

**Budget Authority**

✅ Business budget — larger, less scrutinized

⚠️ IT budget — constrained, needs justification

❌ IT capital — requires project approval

**Risk Perception**

🟢 Zero — read-only, no code changes

🟡 Low — analysis only, no production impact

🔴 High — deploying code to SAP = change management

**Stakeholder Count**

1-2 (process owner + sponsor)

3-4 (dev lead + manager + QA + basis)

6+ (architecture board, change advisory, testing)

**"Wow Factor"**

🔥 Extremely high — visual, instant, actionable

📊 Moderate — technical audience appreciates depth

📋 Variable — depends on project context

**Competitive Moat**

🏰 High — no competitor does live SAP process mining in a chat interface

🏰 Medium — Panaya, Tricentis overlap

🏰 Medium — SAP Build Code, Copilot competition

💡 The Strategic Insight

Process Mining sells to the **business buyer** who controls the larger budget and has shorter approval cycles. Once C16 is installed and trusted for process intelligence, the technical capabilities (Clean Core, code generation, migration) become **natural next steps** — proposed by the customer, not pushed by the vendor.

### The Fundamental Sales Equation

🔍 Process Mining  
LAND

→

📊 Clean Core Analysis  
EXPAND

→

🏗️ Code Modernization  
SCALE

→

🚀 Full Platform  
TRANSFORM

This document lays out the complete GTM strategy built on this equation: **Lead with insight (process mining), expand with assessment (Clean Core), scale with action (code generation), and transform with the full platform.**

2 Crossing the Chasm — The Technology Adoption Problem

Geoffrey Moore's _Crossing the Chasm_ (1991, revised 2014) describes the most dangerous phase for any disruptive technology: the gap between early adopters (who buy on vision) and the early majority (who buy on proven results and peer references). C16 is squarely in this chasm moment.

### Where C16 Sits on the Technology Adoption Lifecycle

Segment

% of Market

Buying Motivation

C16 Status

**Innovators**

2.5%

Technology for its own sake

✅ Already sold — they found you on Twitter/GitHub

**Early Adopters**

13.5%

Strategic advantage, willing to take risk

✅ Converting now — they see the S/4HANA migration wave

**THE CHASM**

—

_"Show me who else is using this successfully"_

**⚡ WE ARE HERE**

**Early Majority (Pragmatists)**

34%

Proven ROI, reference customers, low risk

🎯 Target — Process Mining is the bridge

**Late Majority**

34%

Industry standard, necessary to compete

📅 Year 2-3 — after market proof

**Laggards**

16%

Forced adoption only

📅 Year 4+ — when SAP mandates it

### Why Enterprise SAP Buyers Are the Hardest Chasm to Cross

Moore describes pragmatist buyers as people who want _"the whole product"_ — not just technology, but a complete solution including implementation, support, references, and integration with their existing world. SAP buyers are the **ultimate pragmatists**:

🏢 They Run Mission-Critical Systems

SAP is the financial and operational backbone. A bad tool deployment can mean blocked invoices, failed GR postings, or compliance violations. They don't experiment on production.

📋 They Have Governance Layers

Change Advisory Boards, Architecture Review Boards, Security reviews, Procurement processes. A tool that "looks cool in a demo" must survive 3-6 months of committee scrutiny.

🤝 They Trust SAP and Big SIs

Their default vendor relationship is SAP + Deloitte/Accenture/TCS. A startup must prove it's not going away and won't break their SAP system.

💰 They Measure ROI in Person-Days

The currency is FTE reduction and project acceleration. "AI-powered" means nothing. "Reduced our Clean Core assessment from 6 months to 2 weeks" means everything.

🚨 The Chasm Mistake to Avoid

**Do NOT lead with "C16 is an AI agent for SAP."** That triggers every risk alarm in the pragmatist's brain: _"Unproven technology + mission-critical system = career risk."_ Instead, lead with: **"C16 gives you complete visibility into your SAP processes in 60 minutes."** That's a benefit, not a technology claim.

### Moore's Prescription: The D-Day Strategy

Moore's solution to the chasm is a **D-Day invasion strategy**: pick one narrow beachhead segment, dominate it completely, then use that as a base to expand into adjacent segments. This is NOT about targeting the largest market — it's about targeting the _most winnable_ market where you can achieve 100% market leadership quickly.

For C16, the beachhead is: **Mid-to-large enterprises in active S/4HANA migration planning that need process visibility before they can scope their migration.**

3 Beachhead Market Selection

### Moore's Beachhead Criteria Applied to C16

Moore says the ideal beachhead has four characteristics: (1) the customer has a _compelling reason to buy_, (2) the customer has _budget available_, (3) you can deliver a _complete solution_, and (4) there is _no established alternative_. Let's apply these:

Criterion

Application to C16 Process Mining

Score

**Compelling Reason to Buy**

SAP ECC end-of-life (2027) creates urgency. Companies MUST understand their current-state processes before scoping S/4HANA migration. Without process mining, they spend 3-6 months in workshops manually mapping processes — C16 does it in hours.

⭐⭐⭐⭐⭐

**Budget Available**

S/4HANA migrations are $5M-$100M+ projects. The discovery/scoping phase alone is budgeted at $200K-$1M. C16's process mining replaces a significant portion of this spend at 10-20% of the cost.

⭐⭐⭐⭐⭐

**Complete Solution ("Whole Product")**

C16 Process Mining delivers: O2C analysis, P2P cycle times, vendor diagnostics, data quality scorecards, inventory intelligence — all from a single SAP connection. No additional tools, middleware, or data extraction required. The report is the deliverable.

⭐⭐⭐⭐⭐

**No Established Alternative**

Celonis and Signavio require months-long implementations, data pipeline setup, and $500K+ investment. Consulting firms use manual workshops. C16 delivers process mining through a _conversational interface connected directly to SAP_ — no one else does this.

⭐⭐⭐⭐⭐

✅ Beachhead Verdict: Perfect Score

C16's process mining capability hits all four of Moore's criteria at the highest level. This is not a marginal beachhead — it's a **burning platform**. Every company on ECC _must_ understand their processes before migrating. C16 is the fastest, cheapest, most complete way to do that.

### Target Segment Definition

$500M—$10B

Revenue Sweet Spot

ECC 6.0

Current SAP Version

2026-2028

Planned Migration Window

500-5,000

Custom Z-Objects

#### Primary Beachhead: S/4HANA Migration Discovery Phase

**Who:** Mid-to-large enterprises (revenue $500M-$10B) currently on SAP ECC 6.0, in the planning or discovery phase of their S/4HANA migration. They've engaged (or are about to engage) a system integrator and need to understand their current-state processes, custom code landscape, and data quality before scoping the migration.

#### Secondary Beachhead: Operational Excellence Programs

**Who:** Companies already on S/4HANA (or mid-migration) that have ongoing process improvement mandates from the C-suite. They're looking for continuous process monitoring, not just a one-time migration assessment.

#### Industry Verticals (in order of attack)

#

Industry

Why First

Key Processes

1

**Manufacturing (Discrete & Process)**

Largest SAP installed base, complex P2P and PP flows, most Z-customization

P2P, O2C, PP, QM, WM

2

**Consumer Products / Retail**

High O2C volume, pricing complexity, distribution challenges

O2C, SD Pricing, Inventory

3

**Pharmaceuticals / Life Sciences**

Regulatory compliance (GxP), batch traceability, validated systems

QM, PP, MM Batch, FI Compliance

4

**Oil & Gas / Mining**

Complex PM/asset management, high vendor spend, remote operations

PM, P2P, Joint Venture Accounting

5

**Utilities**

IS-U migration complexity, meter-to-cash processes

IS-U, FI, P2P

4 The Whole Product — Process Mining as the Trojan Horse

Moore defines the _Whole Product_ as everything the customer needs to achieve their compelling reason to buy — not just the core technology, but the complete solution including services, support, documentation, and integration. For pragmatists, an incomplete whole product is a dealbreaker.

### C16's Process Mining Whole Product Map

Layer

What It Includes

Status

**Generic Product**  
(What you ship)

C16 platform with live SAP connection, 18 agent capabilities, natural language interface

READY

**Expected Product**  
(Minimum to meet buyer expectations)

• O2C process mining with cycle times, variants, and bottleneck detection  
• P2P procurement cycle analysis (PR → PO → GR → Invoice → Payment)  
• Vendor/customer master data quality scoring  
• Inventory intelligence (stock levels, movement patterns, dead stock)  
• Beautiful HTML reports with KPIs, charts, and actionable findings  
• Zero installation — SaaS, browser-based, connects to SAP in 15 minutes

READY

**Augmented Product**  
(What differentiates you)

• Conversational interface — ask questions in English, get answers from live SAP data  
• Custom Z-program discovery and Clean Core scoring (bridge to EXPAND phase)  
• Fit-to-Standard analysis linking process gaps to standard SAP solutions  
• Real-time — not batch ETL. Ask a question, get the answer in seconds, not tomorrow  
• Multi-process correlation — link P2P bottlenecks to vendor master data gaps

READY

**Potential Product**  
(Future expansion — the EXPAND & SCALE plays)

• Code generation and deployment (ABAP, RAP, CDS, Fiori Elements)  
• SmartForm → Adobe Form conversion  
• WebDynpro → Fiori migration  
• CAP application scaffolding  
• Continuous process monitoring (always-on, alert-based)  
• AI-driven remediation execution

PHASE 2-3

💡 The Trojan Horse Strategy

Process Mining is the **Trojan Horse** that gets C16 inside the enterprise. It's non-threatening (read-only), immediately valuable (instant reports), and speaks the language of business stakeholders (cycle times, costs, bottlenecks). But once inside, C16's findings _naturally create demand for its other capabilities_:

• "Your P2P cycle is slow because 47 vendors have missing bank details" → **Data Quality Agent activates**  
• "You have 1,299 custom programs — 60% are Clean Core Level C" → **Clean Core Analysis Agent activates**  
• "This process uses 18 BDC recordings that should be BAPI calls" → **Code Modernization Agent activates**  
• "Your ALV reports could be Fiori apps" → **RAP/Fiori Generation Agent activates**

**The customer doesn't buy the platform — they discover it.**

### The "Discovery → Diagnosis → Prescription" Motion

This is the fundamental selling motion borrowed from medicine. A doctor doesn't sell you surgery in the first visit — they run diagnostics, show you the X-ray, explain the problem, and _then_ recommend treatment. C16's sales motion is identical:

🔬 Discovery  
"Let me show you what's happening in your SAP"

→

🩺 Diagnosis  
"Here's why your processes are slow/broken"

→

💊 Prescription  
"Here's how C16 fixes it"

The critical insight: **Phase 1 (Discovery) happens in the first meeting, not after a 6-month POC.** You connect C16 to the customer's SAP system (or a representative sandbox), and within 60 minutes they see their actual P2P cycle times, their actual data quality gaps, their actual process bottlenecks. No other tool in the market can do this.

5 Land & Expand — The Three-Phase Revenue Engine

🟢 Phase 1: LAND — Process Mining Intelligence

"Give them X-ray vision into their SAP. Make them addicted to the insight."

#### Objective

Get C16 connected to the customer's SAP system and deliver a high-value Process Intelligence Report within the first engagement. Create an emotional "aha moment" that makes the customer feel they can't go back to not having this visibility.

#### Capabilities Deployed

Capability

What It Delivers

Buyer Impact

O2C Process Mining

Order-to-cash cycle times, process variants, bottleneck detection, blocked orders analysis

CFO sees where revenue is stuck in the pipeline

P2P Cycle Analysis

PR-to-payment cycle times, vendor concentration risk, open PO exposure

CPO sees procurement inefficiency in hard numbers

Vendor Master Intelligence

Data quality scoring, blocked vendor analysis, missing bank details, duplicate detection

Compliance team sees risk exposure immediately

Inventory Intelligence

Stock levels, dead stock identification, movement patterns, plant-level analysis

Supply chain team sees working capital waste

Payment Analytics

Open payables aging, payment method distribution, early payment discount capture rate

Treasury team sees cash optimization opportunities

#### Revenue Model

**Free Tier:** One-time process health check (single process, limited depth) — lead generation tool.  
**Paid Tier:** Full process mining subscription — all processes, unlimited queries, scheduled reports.  
**ACVs:** $30K-$80K/year for process mining alone. Entry price is _deliberately low_ — the goal is LAND, not maximize initial revenue.

#### Key Metric

< 60 min

Time to First Insight

$30K-$80K

Land ACV

4-6 weeks

Sales Cycle

🔵 Phase 2: EXPAND — Assessment & Clean Core Analysis

"Process mining found the symptoms. Now let's diagnose the root causes in your custom code."

#### The Natural Bridge

Every Process Mining report surfaces findings that _point directly to custom code and configuration issues_. This is not a hard sell — it's a natural conversation:

🔍 Process Mining Finding

"Your P2P cycle averages 45 days vs. industry benchmark of 28 days. 60% of the delay is between GR posting and invoice verification."

"You have 1,299 custom Z-programs. Without classification, you can't scope your S/4HANA migration."

"Your vendor master has 23% incomplete records — missing bank details, payment terms, and tax codes."

💊 C16 Next-Best-Action

"Let me analyze the 14 custom programs involved in your GR/IR process. I'll show you which are Clean Core compliant and which need modernization."

"I can classify all 1,299 programs by Clean Core level (A/B/C/D) in a single afternoon — not the 6 months your SI quoted."

"I can build a data quality remediation report and generate the correction programs to fix these gaps."

#### Capabilities Unlocked

Capability

What It Delivers

Triggered By

Clean Core Analysis

CC1-CC8 scoring, dependency trees, API classification (Level A/B/C/D)

Custom program landscape discovery

Fit-to-Standard

Per-requirement standard vs. custom mapping with specific Fiori App IDs

Process gap findings that may have standard solutions

Mass Code Review

Batch analysis of all Z-programs with severity ranking

"How many programs need work before migration?"

S/4HANA Simplification Impact

Table-level impact analysis against SAP Note 2313884

Custom programs using deprecated tables

Data Quality Diagnostics

Field-level completeness, duplicate detection, referential integrity

Master data gaps found in process mining

#### Revenue Model

**Upsell from Land:** Add Clean Core and Assessment modules to existing subscription.  
**ACVs:** $80K-$200K/year — the account value doubles or triples from the LAND phase.  
**SI Partnerships:** C16 assessment output becomes the _input_ for the SI's migration scope. Position as accelerator, not competitor.

$80K-$200K

Expand ACV

3x

Revenue Expansion Multiple

2-4 months

Time to Expand

🟣 Phase 3: SCALE — Code Modernization & Continuous Platform

"You've seen the problems. You've assessed the landscape. Now let's fix it — at machine speed."

#### The Trust Escalation

By this phase, C16 has been in the account for 4-8 months. The customer has seen dozens of accurate process reports and hundreds of accurate code analyses. **Trust has been earned** — the customer is now willing to let C16 generate code, deploy to SAP, and execute remediation. This would have been impossible in the first meeting.

#### Capabilities Unlocked

Capability

What It Delivers

Trust Level Required

ABAP Code Factory

Generate complete programs, classes, includes — deploy to SAP

High — customer trusts C16 with write access

RAP/Fiori Generation

CDS views, behavior definitions, service bindings, Fiori Elements apps

High — architecture decisions delegated to C16

SmartForm → Adobe Conversion

Automated SmartForm analysis, XDP generation, deployment

Medium-High — output forms are testable

WebDynpro → Fiori Migration

Analyze WebDynpro, generate RAP + Fiori replacement

High — UI replacement is visible to end users

Performance Optimization

Code-to-data pushdown, CDS generation, AMDP for hot paths

Medium — performance is measurable

Continuous Process Monitoring

Always-on process mining, alert on anomalies, trend tracking

Medium — natural extension of LAND phase

#### Revenue Model

**Enterprise Platform License:** Full C16 platform with all 18 agents, unlimited users, unlimited SAP connections.  
**ACVs:** $200K-$500K+/year — the account is now a strategic partnership, not a tool subscription.  
**Professional Services:** C16-led migration sprints (using the platform) at premium rates.

$200K-$500K+

Scale ACV

5-8x

Total Expansion from Land

6-12 months

Time to Full Platform

6 The Challenger Sale — Teaching Customers What They're Missing

Dixon and Adamson's _The Challenger Sale_ research found that the highest-performing B2B salespeople don't build relationships first — they **teach, tailor, and take control**. This is C16's natural selling methodology because the product _is_ the teaching tool.

### The Three T's Applied to C16

#### 1\. TEACH — Reframe How They Think About SAP Migration

⚠️ The Conventional Wisdom (What Customers Believe)

"S/4HANA migration is a **technical project**. We need to assess our custom code, plan the conversion, and test. Our SI will handle it with ABAP consultants and testing tools."

✅ The C16 Reframe (What We Teach Them)

"S/4HANA migration is a **process transformation**. If you don't understand your current processes — where they deviate from standard, why they deviate, and what the business impact of each deviation is — you'll migrate _all your problems_ to a new platform at 10x the cost. **Process intelligence must come first, not code analysis.**"

This reframe is powerful because it's **true**. Every failed S/4HANA migration in history failed because of process gaps, not technical gaps. Customers who hear this reframe immediately recognize their own risk — and recognize that C16 addresses it.

#### The Challenger Teaching Pitch (Process Mining-Led)

1

The Warmer — Common Ground

"Every SAP customer we talk to is dealing with the same challenge: ECC end-of-life is coming, the board wants a migration plan, but no one can agree on the scope because no one has complete visibility into what's actually happening in the system."

2

The Reframe — Challenge Their Thinking

"Most companies start their migration by hiring 20 ABAP consultants to read custom code. That's starting at the wrong end. You wouldn't renovate a building by counting bricks — you'd start by understanding how people use the building. The same is true for SAP: **understand your processes first, then assess the code that supports them.**"

3

Rational Drowning — The Cost of the Status Quo

"Companies that skip process discovery spend an average of 2.3x their original migration budget on rework. They convert custom programs that should have been retired, miss configuration changes that could eliminate customization, and discover process gaps during UAT when it's 10x more expensive to fix. The average S/4HANA migration overrun is 42% — and it's almost entirely caused by inadequate discovery."

4

Emotional Impact — Make It Personal

"Imagine presenting to your board that the migration is 40% over budget because you didn't know your P2P process had 23 variants instead of 3 — and 18 of those variants were caused by custom ABAP programs that could have been replaced by standard configuration. That's a career-defining moment, and not in a good way."

5

The New Way — C16 as the Solution

"What if you could see all of that — every process variant, every bottleneck, every data quality gap, every unnecessary customization — in a single afternoon? Not in a 6-month discovery workshop, but _right now_, while we're on this call? Let me show you."

6

The Live Proof — "Let's Do It Now"

**THIS IS WHERE C16 WINS.** You connect to their SAP system (sandbox or QA) and run a live process mining analysis. In 60 minutes, they see their actual data, their actual process bottlenecks, their actual data quality gaps. No PowerPoint. No promises. Just proof. No other vendor in the SAP ecosystem can do this in a first meeting.

#### 2\. TAILOR — Speak Each Stakeholder's Language

The Challenger Sale emphasizes tailoring your message to each stakeholder's specific concerns. C16's process mining reports do this automatically — the same platform generates different insights for different audiences. See the Buyer Personas section below.

#### 3\. TAKE CONTROL — Own the Buying Process

The Challenger seller doesn't wait for the customer to define evaluation criteria — they set the criteria. C16's process mining creates the evaluation framework: "Any tool you evaluate should be measured on (1) time to first insight, (2) accuracy of process variant detection, (3) ability to connect process findings to custom code, and (4) actionability of recommendations." These criteria are C16's strengths and competitors' weaknesses.

7 Buyer Personas & Stakeholder Mapping

### The Process Mining Buying Committee

The beauty of leading with process mining is that the buying committee is **smaller and more business-oriented** than a code analysis or migration tool sale. Here are the key personas:

👔 VP of Operations / Process Excellence Lead

Pain: "I can't see what's actually happening in our SAP processes. I rely on anecdotal reports from process owners."

**C16 Message:** "You'll have real-time visibility into every process variant, every bottleneck, and every exception. Your monthly ops review will be data-driven, not story-driven."

💰 CFO / VP Finance

Pain: "Our S/4HANA migration budget keeps growing and I don't trust the estimates. I need to know what we're actually dealing with."

**C16 Message:** "C16 will show you exactly which processes are standard-fit (cheap to migrate), which need configuration (moderate), and which have deep customization (expensive). You'll have the data to challenge your SI's estimates."

🖥️ CIO / IT Director

Pain: "We have 1,300 custom programs. My SI says it'll take 18 months to assess them. I need a faster path."

**C16 Message:** "Start with process mining to identify which programs matter — the ones in active process flows. Then let C16 assess those first, in days not months. 40-60% of custom programs are unused — don't waste time assessing dead code."

📊 S/4HANA Program Manager

Pain: "I'm responsible for the migration timeline and budget. I need a credible discovery phase deliverable, and I need it fast."

**C16 Message:** "C16's process mining report IS your discovery deliverable. It covers process variants, data quality, custom code landscape, and fit-to-standard — in weeks, not quarters. Your steering committee gets the business case faster."

### Stakeholder Influence Map

Role

Influence

Concern

C16 Answer

Phase

**VP Operations**

🔴 Champion

Process visibility

Live process mining dashboards

LAND

**CFO**

🔴 Budget Holder

Migration cost control

Scope accuracy → budget predictability

LAND

**CIO**

🔴 Decision Maker

Technical risk, vendor viability

Read-only connection, SOC2, no code changes in LAND

LAND

**Program Manager**

🟡 Influencer

Timeline, deliverable quality

Weeks not months for discovery

LAND

**ABAP Dev Lead**

🟡 Technical Gatekeeper

"Will this replace my team?"

"C16 amplifies your team 10x, doesn't replace them"

EXPAND

**SAP Basis Admin**

🟡 Technical Gatekeeper

System security, performance

Read-only RFC, no performance impact, no batch loads

LAND

**Security / Compliance**

🟡 Veto Power

Data access, audit trail

Principle of least privilege, S\_RFC scope, audit log

LAND

**SI Partner**

🟢 Potential Blocker OR Ally

"Threat to our scope/revenue"

C16 accelerates their discovery → earlier project start → they bill sooner

EXPAND

8 The 60-Minute Demo Playbook — "Show, Don't Tell"

🎯 The #1 Rule: NEVER Demo with Mock Data

C16's killer advantage is that it works on **real data, in real time**. Every demo must use the customer's actual SAP system (sandbox/QA). If they won't provide access, use a representative industry reference system. Mock data demos are categorically forbidden — they reduce C16 to "just another slideware tool."

### Pre-Demo Setup (15 minutes before the call)

Step

Action

Time

1

Confirm SAP connection is live (run `Test Connection`)

2 min

2

Pre-run one P2P or O2C analysis to cache data and verify results are interesting

5 min

3

Check custom program count — have the "1,299 programs" number ready

2 min

4

Identify 2-3 "hero findings" — a blocked vendor, a slow process step, a data quality gap

5 min

5

Prepare a follow-up question that bridges to Clean Core (e.g., "want to see why this process is slow?")

1 min

### The 60-Minute Demo Script

Minutes 0-5 — Context Setting

**Objective:** Establish the problem frame (Challenger reframe).  
**Script:** "Before I show you C16, let me share what we see across the SAP landscape. Companies planning S/4HANA migrations typically discover that their understanding of their own processes is 30-50% incomplete. They think they have 3 order-to-cash variants — they actually have 15. They think their P2P cycle is 30 days — it's actually 45 in some company codes. This gap between perception and reality is what causes migration overruns. Today, I'm going to give you complete visibility into YOUR system."

Minutes 5-20 — Process Mining (The Hook)

**Objective:** Deliver the "aha moment" with their real data.  
**Actions:**

*   Run O2C Process Mining: "Show me the order-to-cash cycle for the last 2 years"
*   Show cycle time breakdown: Order → Delivery → Billing → Payment
*   Highlight the longest stage: "Look — 38% of your cycle time is between delivery and billing. That's revenue you've earned but can't recognize."
*   Show process variants: "You have 7 distinct O2C variants. Here are the top 3 by volume..."

**Expected Reaction:** The VP of Ops leans forward. The CFO asks "can we drill into that?" The CIO is intrigued but cautious.

Minutes 20-35 — Data Quality & P2P (Deepening the Hook)

**Objective:** Show multi-dimensional analysis — process mining isn't just one report.  
**Actions:**

*   Run Vendor Master Data Quality: "Let me check your vendor data health"
*   Show completeness scorecard: "23% of your vendors are missing bank details — that means 23% of your payments require manual intervention"
*   Run P2P Cycle: "Now let's look at procurement..."
*   Show open PO exposure: "$4.2M in open POs older than 90 days with no GR — that's either delivery risk or dead POs consuming budget"

**Expected Reaction:** The CFO says "I didn't know that number." The Program Manager is furiously taking notes.

Minutes 35-45 — The Bridge to Expand (Plant the Seed)

**Objective:** Naturally connect process findings to custom code — don't sell it, discover it together.  
**Actions:**

*   "Let me see why your P2P cycle is slow in that segment..."
*   Show custom program discovery: "You have 1,299 custom programs. Let me search for the ones involved in procurement..."
*   Pick one program: "This program — Z\_MM\_VENDOR\_REPORT — runs 400 times per week. It's using obsolete patterns and direct table access. If you're planning S/4HANA, this is a Level C program that needs modernization."
*   DON'T go deep on code: "I can do a full Clean Core analysis on every one of these — but that's a deeper engagement. For now, I want you to see the connection: _process bottlenecks have code root causes, and C16 sees both._"

**Expected Reaction:** The CIO says "how many of those 1,299 are Level C?" (This is the expansion trigger.)

Minutes 45-55 — Business Case (Quantify the Value)

**Objective:** Translate findings into dollars.  
**Script:**

*   "Based on what we've seen today: your O2C delay between delivery and billing represents approximately $X in deferred revenue recognition per quarter"
*   "Your 23% vendor data incompleteness creates an estimated $Y in manual payment processing overhead per year"
*   "Your 1,299 custom programs need assessment before migration. At consultant rates, that's $Z over 12-18 months. C16 can do the initial classification in days."

Minutes 55-60 — Close (Next Steps)

**Objective:** Establish the next action — not "think about it," but a specific commitment.  
**Script:** "I'd like to leave C16 connected to your sandbox for 2 weeks. Your team can ask it any question about your SAP processes — no cost, no commitment. At the end of 2 weeks, I'll compile a comprehensive Process Health Report and we'll review it together. Fair?"

**Expected Outcome:** 80%+ agree to a free trial period because it's zero risk, zero effort, and they've already seen the value.

9 Objection Handling Matrix

### Security & Access Objections

❓ "We can't give an AI tool access to our SAP system."

✅ "I understand — that's exactly the right instinct. C16 connects via a **dedicated service user with principle-of-least-privilege permissions**. For process mining, we need only RFC read access to specific tables — no write access, no debug, no developer rights. We provide the exact role definition (S\_RFC scoped to specific function modules) so your basis team maintains full control. The connection uses TLS 1.3 encrypted HTTPS — the same protocol your SI uses for their tools."

❓ "What about GDPR? Does C16 store our data?"

✅ "C16 processes data in-session and does not persist your SAP data after the session ends. The generated reports contain aggregated insights, not raw data extracts. We can operate entirely within your network perimeter if needed. We're pursuing SOC 2 Type II certification and can sign a DPA (Data Processing Agreement) that specifies data handling, residency, and deletion policies."

### Value & ROI Objections

❓ "We already have Celonis for process mining."

✅ "Celonis is excellent for continuous, enterprise-wide process monitoring — and it requires 6-12 months of implementation, a dedicated data pipeline, and $500K+ annual investment. C16 is different: it's an **instant, conversational process intelligence** layer that connects directly to SAP and delivers insights in minutes. Think of Celonis as the MRI machine and C16 as the doctor's stethoscope — one is for deep ongoing monitoring, the other is for immediate diagnosis. Most importantly, C16 goes beyond process mining — it connects process findings to custom code analysis and remediation. Celonis can tell you your P2P is slow; C16 can tell you _which custom program is causing it_ and generate the fix."

❓ "Our SI already does process discovery as part of the migration."

✅ "They absolutely do — and C16 makes them faster and more accurate. SI discovery workshops typically take 3-6 months of interviews, documentation reviews, and manual mapping. C16 can pre-populate 80% of that discovery in 2 weeks. Your SI still does the validation, the business process redesign, and the change management — but they start from a data-driven baseline instead of a blank whiteboard. We position C16 as an **accelerator for your SI**, not a replacement. In fact, several SIs are starting to use C16 as part of their own methodology."

❓ "We don't have budget for another tool."

✅ "Two responses. First, the process mining entry point is $30K-$80K/year — less than two weeks of SI consulting. If C16 accelerates your discovery by even one month, the ROI is 5-10x. Second, C16 doesn't come from the 'new tools' budget — it comes from the migration project budget as a **discovery accelerator**. Your migration project already has a discovery phase budgeted at $200K-$1M. C16 replaces a portion of that spend and delivers better results."

### Technical Objections

❓ "AI hallucinates. How do we trust the findings?"

✅ "This is the most important question, and I'm glad you asked it. C16 is not a generic AI chatting about SAP — it's an **agentic system connected to your live SAP data**. Every number in a C16 report comes from an actual SAP table query that you can verify. The report cites the specific tables, fields, and record counts. When C16 says 'you have 47 blocked vendors' — that's a count from LFA1 WHERE SPERR = 'X', not a guess. We call this our 'zero fabrication' architecture: every claim must be tool-verified with a traceable source."

❓ "We're on ECC 6.0 — does C16 work with that?"

✅ "Absolutely. C16's process mining works on ECC 6.0, ECC 7.40, S/4HANA on-premise, and S/4HANA Cloud. The connection uses standard RFC and OData interfaces that exist in all SAP versions. In fact, C16 automatically detects your system version and adapts its capabilities — on ECC, it focuses on process mining and ABAP analysis. On S/4HANA, it adds CDS views, RAP generation, and Fiori Elements capabilities."

### Competitive Objections

❓ "SAP has Joule / Build Code / Signavio — why do we need a third party?"

✅ "SAP's tools are excellent within their lanes. Joule is a general copilot for SAP UX — it doesn't do process mining or code analysis. Build Code assists with ABAP development — it doesn't assess your existing 1,300 custom programs. Signavio is a process modeling tool — it doesn't connect to your live SAP data for real-time analysis. C16 is the **only tool that bridges all three**: live process mining → custom code assessment → code generation and deployment. It's the connective tissue between process and technology that SAP's point solutions don't provide."

10 Competitive Positioning — C16 vs. The Field

### Competitive Landscape Matrix

Capability

C16

Celonis

Signavio (SAP)

Panaya

SAP Build Code

Generic AI (Copilot etc.)

**Live SAP Process Mining**

✅ Real-time, conversational

✅ Batch ETL, dashboard

⚠️ Modeling, not live mining

❌

❌

❌

**Time to First Insight**

⚡ 60 minutes

📅 3-6 months implementation

📅 2-4 months modeling

📅 2-4 weeks scan

N/A

❌ No SAP access

**Clean Core Code Analysis**

✅ Deep (CC1-CC8, per-line)

❌

❌

⚠️ Shallow (table-level)

❌

❌

**Code Generation & Deploy**

✅ Full ABAP/RAP/Fiori

❌

❌

❌

⚠️ Snippets only

⚠️ No SAP deploy

**Process → Code Linkage**

✅ Connects bottleneck to Z-program

❌ Process only

❌ Process only

❌ Code only

❌ Code only

❌

**Natural Language Interface**

✅ Full conversational

❌ Dashboard UI

❌ Diagram UI

❌ Wizard UI

⚠️ Code assist only

✅ But no SAP depth

**Investment Required**

$30K-$500K/yr

$500K-$2M+/yr

$200K-$500K/yr

$100K-$300K/yr

Included (BTP)

$20-$50/user/mo

💡 C16's Unique Position: The Only Tool That Bridges Process and Code

Every competitor lives in one world — either process (Celonis, Signavio) or code (Panaya, Build Code). C16 is the **only platform that sees both and connects them**. When C16's process mining finds a bottleneck, it can trace it to the custom ABAP program causing it, analyze that program's Clean Core compliance, and generate the fix. This process-to-code linkage is C16's moat — it's architecturally impossible for point solutions to replicate without years of development.

### Positioning Statement

For SAP enterprise customers planning or executing S/4HANA migrations, C16 is the AI-powered process intelligence and code modernization platform that delivers instant visibility into SAP processes and custom code — connecting business bottlenecks to technical root causes for the first time. Unlike Celonis (process only), Panaya (code only), or SAP Build Code (development only), C16 bridges process mining, code analysis, and code generation in a single conversational interface.

— C16 Positioning Statement (Geoffrey Moore's positioning template)

11 Pricing Architecture — Process Mining Entry Point

### Tier Structure

Tier

Capabilities

Target

Annual Price

Phase

**🔍 Discover**

• Process Mining (O2C, P2P, R2R)  
• Data Quality Scorecards  
• Inventory Intelligence  
• Natural Language Queries  
• HTML Report Generation

VP Ops, CFO  
Business budget

**$30K — $80K**

LAND

**📊 Assess**

Everything in Discover, plus:  
• Clean Core Analysis (all Z-programs)  
• Fit-to-Standard Assessment  
• S/4HANA Simplification Impact  
• Mass Code Review  
• Dependency Analysis

CIO, Dev Lead  
IT/Migration budget

**$80K — $200K**

EXPAND

**🏗️ Transform**

Everything in Assess, plus:  
• ABAP Code Generation & Deploy  
• RAP/CDS/Fiori Generation  
• SmartForm Conversion  
• WebDynpro Migration  
• Performance Optimization  
• Continuous Process Monitoring

CIO, Program Mgr  
Migration project budget

**$200K — $500K+**

SCALE

### Pricing Psychology

The pricing is deliberately structured to minimize friction at the LAND phase:

*   **$30K is below most procurement thresholds** — can be approved by a VP without board/committee
*   **Discover tier is 90%+ margin** — it's process mining with no implementation cost. Use this as a strategic loss-leader if needed for marquee accounts.
*   **The 3x expansion from Discover → Assess is natural** — the findings from process mining create the demand for code assessment. You're not asking for more budget; the data is asking for it.
*   **Transform tier is priced against SI alternatives** — if the customer would spend $2M with an SI for migration execution, $300K for C16's platform that accelerates the migration by 30-40% is an easy ROI case.

### Free Tier Strategy

🆓 The "Process Health Check" — Free Lead Generator

Offer a **no-cost, no-commitment Process Health Check**: connect C16 to a customer's SAP sandbox for one session, run process mining on one process (O2C or P2P), and deliver a summary report. This is the top-of-funnel motion that creates pipeline.

**Why it works:** It costs nothing to deliver (15 minutes of setup), generates a high-quality deliverable the customer keeps, and creates the "aha moment" that drives conversion to Discover tier. Target: 70%+ conversion from free health check to paid trial.

12 Sales Metrics & Success Criteria

### Pipeline Metrics

Metric

Target

Measurement

**Time to First Value**

< 60 minutes

Time from SAP connection to first actionable insight delivered

**Free Health Check → Discover Conversion**

\> 70%

% of free health check recipients who convert to paid Discover tier

**Discover → Assess Expansion Rate**

\> 60%

% of Discover customers who expand to Assess within 6 months

**Assess → Transform Expansion Rate**

\> 40%

% of Assess customers who expand to Transform within 12 months

**LAND Sales Cycle**

4-6 weeks

First meeting to signed Discover contract

**Net Revenue Retention**

\> 150%

Annual revenue from existing customers / revenue from those customers 12 months ago

**Logo Churn**

< 5%

Annual customer loss rate

### Leading Indicators (Weekly Tracking)

Indicator

What It Tells You

Alert Threshold

Free Health Checks Delivered

Top of funnel activity

< 5/week = increase outbound

Demo-to-Trial Conversion

Quality of demo execution

< 50% = retrain sales team

Process Mining Queries/Customer/Week

Product engagement / stickiness

< 10 queries = at-risk account

Expansion Trigger Events

"Clean Core" or "code analysis" requests from Discover customers

Track as pipeline leading indicator

SI Partner Referrals

Channel development health

Track monthly — target 30%+ of pipeline from partners by Month 12

13 The Customer Journey — From Curiosity to Champion

### The 12-Month Customer Lifecycle

Month 0 — First Contact (Free Health Check)

**Trigger:** Customer sees a C16 process mining demo at a conference, reads a case study, or gets an outbound email with a specific insight about their industry's SAP challenges.

**Action:** 60-minute live demo using their SAP sandbox. Deliver a Process Health Check report.

**Outcome:** Customer has a tangible report showing 3-5 findings they didn't know about. Internal champion emerges (usually the VP Ops or Program Manager).

Month 1 — Discover Tier Purchase

**Trigger:** Champion shares the health check report internally. CFO or CIO asks "can we get more of this?"

**Action:** Sign Discover tier ($30K-$80K). Deploy C16 with read-only SAP access. Train 3-5 power users.

**Outcome:** Customer starts asking C16 questions daily. Process mining becomes part of their weekly ops review. Usage data shows engagement.

Month 3-4 — The Expansion Trigger

**Trigger:** Process mining reveals that bottlenecks are caused by custom programs and data quality issues. Customer asks "can C16 analyze our custom code too?"

**Action:** Deliver a sample Clean Core analysis on one high-impact program. Show the CC score, findings, and remediation path. The customer sees the connection between process mining and code modernization.

**Outcome:** Customer upgrades to Assess tier. CIO and Dev Lead are now engaged alongside business users.

Month 4-6 — Assessment Phase

**Action:** C16 analyzes all 1,299 (or however many) custom programs. Delivers mass code review, Clean Core classification, Fit-to-Standard mapping. Customer has complete migration discovery documentation.

**Outcome:** Customer uses C16's assessment output as the basis for their SI's migration scope. C16's data feeds directly into the project plan. SI engagement accelerates by 2-3 months.

Month 6-8 — The Scale Trigger

**Trigger:** Migration execution begins. Customer's developers need to refactor 200+ custom programs. SI estimates 18 months. Customer asks "can C16 generate the clean code?"

**Action:** Demonstrate code generation on one program — from analysis to deployed Clean Core ABAP in 30 minutes. Customer sees 90% time reduction.

**Outcome:** Customer upgrades to Transform tier. C16 is now a strategic platform, not a tool. Annual value: $200K-$500K+.

Month 8-12 — Champion & Reference

**Outcome:** Customer becomes a reference account, speaks at SAP events about their migration acceleration, introduces C16 to peer companies. The flywheel begins.

💡 The Psychological Ratchet

Each phase creates information the customer can't unsee. Once they've seen their process bottlenecks, they need to understand why. Once they understand their custom code landscape, they need to fix it. Once they see C16 can generate code, manual refactoring feels insane. **Each phase makes the next phase feel inevitable, not like a sales expansion.**

14 Content Strategy & Demand Generation

### Content Pillars (Process Mining-Led)

Pillar

Purpose

Formats

Example Titles

**1\. Process Intelligence Thought Leadership**

Establish C16 as the authority on SAP process visibility. Attract the VP Ops / Process Excellence audience.

Blog posts, LinkedIn articles, webinars

• "Why Your S/4HANA Migration Will Fail Without Process Mining"  
• "The 5 SAP Process Bottlenecks That Cost Manufacturers $10M/Year"  
• "P2P Cycle Time: Why Industry Benchmarks Are Lying to You"

**2\. Migration Intelligence**

Position C16 as essential for S/4HANA readiness. Attract the CIO / Program Manager audience.

Whitepapers, case studies, ROI calculators

• "The $2M Mistake: How Incomplete Discovery Causes Migration Overruns"  
• "From 1,300 Custom Programs to Clean Core: A Data-Driven Approach"  
• "Process-Led Migration: Why Business Discovery Must Come Before Code Analysis"

**3\. Live Demo Content**

Show, don't tell. Demonstrate C16's process mining on real(istic) SAP data.

YouTube demos, interactive sandboxes, conference presentations

• "60 Seconds to O2C Insight: C16 Live Demo"  
• "Finding $4M in Open PO Exposure — C16 Process Mining in Action"  
• "From Bottleneck to Root Cause in One Conversation"

**4\. Technical Depth (for EXPAND)**

Build credibility with the ABAP development community. Support the expansion to Clean Core.

SCN blog posts, GitHub examples, SAP Community tutorials

• "Clean Core Scoring: How C16 Classifies Your Custom ABAP"  
• "From REUSE\_ALV to CL\_SALV\_TABLE: C16's Automated Refactoring"  
• "The Process-to-Code Bridge: Connecting Bottlenecks to Z-Programs"

### Demand Generation Funnel

Stage

Tactic

Conversion Mechanism

Volume Target (Monthly)

**Awareness**

LinkedIn ads (VP Ops, CIO targeting), SAP conference sponsorships, thought leadership content

Whitepaper download → email nurture

500 MQLs

**Interest**

Webinar: "See Your SAP Processes in 60 Minutes" (monthly), YouTube demos, SCN blog posts

Webinar attendee → demo request

100 demo requests

**Evaluation**

Free Process Health Check (live demo with their SAP), 2-week trial

Health check report → Discover tier proposal

30 health checks

**Purchase**

ROI-driven proposal, procurement support, security questionnaire completion

Signed contract

8-12 new logos

### The Killer Content Asset: The "SAP Process Health Index"

📊 Annual Industry Report — "The State of SAP Processes"

Publish an annual report aggregating (anonymized) insights from C16's process mining across industries. Include benchmarks: average O2C cycle time by industry, average P2P cycle, average custom program count, average Clean Core score. This becomes the **industry reference** that every SAP customer wants to benchmark against — and positions C16 as the data authority.

**Distribution:** Gated download requiring company name + SAP version. Perfect lead gen tool.

15 Channel & Partnership Strategy

### The SI Partnership Paradox — and How to Resolve It

System Integrators (Deloitte, Accenture, TCS, Infosys, Wipro, Cognizant, IBM) are both C16's **biggest channel opportunity** and **biggest competitive threat**. The paradox:

⚠️ The Threat

SIs bill $200-$500/hour for SAP consultants doing manual discovery and code analysis. C16 automates this. If SIs see C16 as a revenue threat, they'll block it from every deal.

✅ The Opportunity

SIs struggle to staff SAP migration projects — there aren't enough ABAP developers. C16 makes their existing teams 5-10x more productive. If SIs see C16 as a force multiplier, they'll embed it in every engagement.

### The "Accelerator, Not Competitor" Positioning

SI Concern

C16 Response

Evidence

"C16 replaces our discovery consultants"

C16 accelerates discovery from 6 months to 2 weeks — your consultants do business process redesign and change management instead. Higher-value work, same billing.

C16 generates the discovery _input_; SI consultants generate the transformation _output_.

"C16 replaces our ABAP developers"

You can't hire enough ABAP developers. C16 makes each developer 5x more productive. Bill the same rate, deliver 5x faster, take on more projects.

Global ABAP developer shortage is 35%+ and worsening.

"C16 reduces our project scope/revenue"

Faster discovery → earlier project start → faster billing. C16 also surfaces scope items that manual discovery misses (data quality gaps, hidden process variants), which increases total project scope.

Process mining typically finds 30-50% more migration scope than manual workshops.

### Partner Tiers

Tier

Partner Type

Model

Target Partners

**Strategic**

Global SIs

Joint GTM, embedded in SI methodology, revenue share

Deloitte, Accenture, IBM

**Growth**

Regional SIs / SAP Gold Partners

Reseller + implementation partner, margin on C16 license

Infosys, TCS, Wipro, Cognizant, Capgemini

**Technology**

Adjacent platforms

Integration partnerships, joint solutions

Celonis (complementary), ServiceNow, Tricentis

**Community**

Independent SAP consultants / boutiques

Free or discounted C16 access, affiliate model

SAP Community influencers, freelance Basis/ABAP experts

### The SI Playbook: "C16 Inside"

The ultimate partnership model is **"C16 Inside"** — where the SI's migration methodology incorporates C16 as the standard discovery and assessment engine. The SI brands their methodology (e.g., "Deloitte S/4HANA Accelerated Discovery powered by C16"), and C16 gets deployed in every engagement. This is how to scale from direct sales to channel-driven growth.

💡 The SAP Partnership

Long-term, the ideal endgame is an **SAP partnership** — C16 listed on SAP Store, endorsed by SAP's S/4HANA migration team, embedded in SAP's own migration methodology. This requires: (1) proven customer references, (2) Clean Core compliance of C16 itself, (3) integration with SAP BTP, and (4) SAP's recognition that C16 accelerates their own goal of moving customers to S/4HANA. Process mining is the door — SAP wants customers to migrate, C16 helps them do it faster.

16 90-Day Launch Plan

### Phase 1: Days 1-30 — Foundation

Week

Action

Owner

Deliverable

1-2

Build "Free Process Health Check" package — standardize the 60-min demo, create the report template, build the landing page

Marketing + Product

Health Check landing page live

1-2

Create the Challenger Teaching Pitch deck — 15 slides max, built on the reframe narrative from Section 6

Sales + CEO

Pitch deck finalized

2-3

Identify 20 target accounts (beachhead criteria from Section 3), research their SAP landscape, ECC version, migration timeline

Sales

Target account list with research

3-4

Produce first 3 thought leadership pieces (LinkedIn articles on process mining for S/4HANA)

Marketing

3 published articles

3-4

Record 2 YouTube demo videos: "60 Seconds to O2C Insight" and "P2P Process Mining in Action"

Product + Marketing

2 videos published

4

Build ROI calculator (input: company revenue, # custom programs, planned migration date → output: C16 value)

Sales + Product

Calculator tool live on website

### Phase 2: Days 31-60 — Outbound & First Wins

Week

Action

Owner

Target

5-6

Launch outbound campaign: personalized emails to 20 target accounts using the Challenger reframe

Sales

10 demo meetings booked

5-6

Host first webinar: "Why Process Discovery Must Come Before Code Analysis"

Marketing

50+ attendees, 15 demo requests

6-7

Deliver first 5-10 Free Process Health Checks

Sales + Solutions

7+ health checks delivered

7-8

Close first 2-3 Discover tier deals from health check conversions

Sales

$60K-$240K ARR

8

Approach 3 SIs with "C16 Inside" partnership proposal, using early customer wins as evidence

Partnerships

1 SI LOI signed

### Phase 3: Days 61-90 — Scale & Iterate

Week

Action

Owner

Target

9-10

Publish first case study from Discover tier customer

Marketing + Customer

1 case study live

9-10

First expansion trigger: Discover customer asks about Clean Core analysis

CSM + Sales

1 expansion pipeline created

10-11

Scale outbound: expand target list to 50 accounts, add 2nd BDR

Sales

20 demo meetings/month

11-12

Submit to SAP App Center / SAP Store

Partnerships

Application submitted

12

Month 3 review: pipeline, conversion rates, expansion triggers, product feedback

All

Board-ready metrics deck

### Day 90 Success Criteria

5-8

Discover Tier Customers

$150K-$500K

ARR

1-2

Expansion Pipeline Accounts

1

SI Partnership LOI

1

Published Case Study

\> 70%

Health Check Conversion Rate

🎯 The North Star Metric for Year 1

**Net Revenue Retention > 150%.** This single metric proves the Land & Expand model works. If existing customers are expanding from $50K to $75K+ within 12 months, the business model is validated and the chasm is being crossed. Every other metric is a leading indicator of this one.

**C16 Go-to-Market Strategy — Process Mining-Led Land & Expand**  
Strategic Playbook v2.0 | April 2026  
  
**Frameworks Applied:** Crossing the Chasm (Geoffrey A. Moore, 1991/2014), The Challenger Sale (Matthew Dixon & Brent Adamson, 2011)  
**Key Thesis:** Lead with Process Mining (instant value, business buyer, zero risk) → Expand to Clean Core Assessment (natural bridge from process findings) → Scale to Full Platform (code generation, migration execution).  
**Prepared by:** C16 Strategic Advisory  
  
_This document is a living strategy that should be revisited monthly as market feedback, customer conversations, and competitive dynamics evolve. The process mining-led approach is validated by the principle that pragmatist buyers need to see value before they trust vision._

**C16 — AI-Powered SAP Analysis**  
_Generated by C16. This document is AI-generated and should be validated by a qualified SAP consultant before implementation. All data sourced from the connected SAP system._