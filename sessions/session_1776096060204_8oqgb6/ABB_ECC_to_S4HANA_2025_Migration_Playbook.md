  ABB ECC → S/4HANA 2025 Migration Playbook :root { --primary: #6B3FA0; --primary-light: #8B5FBF; --primary-dark: #4A2870; --accent: #B5567A; --accent-light: #D4849E; --gold: #C97B3A; --gold-light: #E8A84C; --dark: #1a1a2e; --dark-mid: #16213e; --dark-light: #1e2a4a; --text-light: #e8e8f0; --text-muted: #a0a0b8; --success: #27ae60; --warning: #f39c12; --danger: #e74c3c; --info: #3498db; --card-bg: rgba(255,255,255,0.06); --card-border: rgba(255,255,255,0.12); --glass-bg: rgba(255,255,255,0.04); } \* { margin:0; padding:0; box-sizing:border-box; } body { font-family: 'Segoe UI', system-ui, -apple-system, sans-serif; background: var(--dark); color: var(--text-light); overflow: hidden; height: 100vh; width: 100vw; } /\* ── Slide Container ── \*/ .deck { position: relative; width:100vw; height:100vh; overflow:hidden; } .slide { position: absolute; top:0; left:0; width:100%; height:100%; display: flex; flex-direction: column; opacity:0; visibility:hidden; transition: opacity 0.5s ease, transform 0.5s ease; transform: translateX(60px); overflow-y: auto; padding: 0; } .slide.active { opacity:1; visibility:visible; transform:translateX(0); } .slide.exit-left { opacity:0; transform:translateX(-60px); } .slide-inner { flex:1; padding: 50px 60px 100px 60px; max-width: 1400px; margin:0 auto; width:100%; } /\* ── Background Patterns ── \*/ .bg-hero { background: linear-gradient(135deg, #1a1a2e 0%, #2d1b4e 30%, #1e2a4a 60%, #1a1a2e 100%); } .bg-phase1 { background: linear-gradient(160deg, #1a1a2e 0%, #1b2e3e 50%, #1a2840 100%); } .bg-phase2 { background: linear-gradient(160deg, #1a1a2e 0%, #2d1b3e 50%, #251a3e 100%); } .bg-phase3 { background: linear-gradient(160deg, #1a1a2e 0%, #3e2b1b 50%, #2e2018 100%); } .bg-phase4 { background: linear-gradient(160deg, #1a1a2e 0%, #1b3e2d 50%, #182e25 100%); } .bg-default { background: linear-gradient(160deg, #1a1a2e 0%, #1e2a4a 50%, #1a1a2e 100%); } /\* ── Decorative Elements ── \*/ .slide::before { content: ''; position: absolute; top: -200px; right: -200px; width: 500px; height: 500px; background: radial-gradient(circle, rgba(107,63,160,0.08) 0%, transparent 70%); border-radius: 50%; pointer-events: none; } .slide::after { content: ''; position: absolute; bottom: -200px; left: -100px; width: 400px; height: 400px; background: radial-gradient(circle, rgba(181,86,122,0.06) 0%, transparent 70%); border-radius: 50%; pointer-events: none; } /\* ── Typography ── \*/ .slide-badge { display: inline-block; background: linear-gradient(135deg, var(--primary), var(--accent)); color: #fff; padding: 5px 16px; border-radius: 20px; font-size: 0.75rem; font-weight: 600; letter-spacing: 1.5px; text-transform: uppercase; margin-bottom: 16px; } .slide-title { font-size: 2.4rem; font-weight: 700; margin-bottom: 8px; line-height: 1.2; background: linear-gradient(135deg, #fff 0%, #c8b8e8 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; } .slide-subtitle { font-size: 1.1rem; color: var(--text-muted); margin-bottom: 36px; font-weight: 400; } h3 { font-size: 1.15rem; font-weight: 600; color: var(--accent-light); margin: 28px 0 14px 0; display: flex; align-items: center; gap: 8px; } h3 .icon { font-size: 1.2rem; } /\* ── Hero Slide ── \*/ .hero-container { display: flex; flex-direction: column; align-items: center; justify-content: center; text-align: center; min-height: 80vh; position: relative; } .hero-logo { font-size: 3rem; margin-bottom: 12px; } .hero-title { font-size: 3.2rem; font-weight: 800; background: linear-gradient(135deg, #fff 0%, #d4b8ff 40%, #ff9ec4 70%, #ffc87a 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; margin-bottom: 12px; line-height: 1.15; } .hero-sub { font-size: 1.25rem; color: var(--text-muted); margin-bottom: 40px; max-width: 700px; } .hero-stats { display: flex; gap: 24px; flex-wrap: wrap; justify-content: center; } .hero-stat { background: var(--card-bg); border: 1px solid var(--card-border); border-radius: 16px; padding: 20px 28px; min-width: 130px; backdrop-filter: blur(10px); } .hero-stat .num { font-size: 2.2rem; font-weight: 800; background: linear-gradient(135deg, var(--gold-light), var(--gold)); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; } .hero-stat .lbl { font-size: 0.78rem; color: var(--text-muted); text-transform: uppercase; letter-spacing: 1px; margin-top: 4px; } .hero-version { margin-top: 30px; font-size: 0.8rem; color: var(--text-muted); opacity: 0.6; } /\* ── Cards ── \*/ .card-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 18px; margin: 16px 0; } .card-grid-3 { grid-template-columns: repeat(3, 1fr); } .card-grid-5 { grid-template-columns: repeat(5, 1fr); } .card-grid-4 { grid-template-columns: repeat(4, 1fr); } .card-grid-2 { grid-template-columns: repeat(2, 1fr); } .card { background: var(--card-bg); border: 1px solid var(--card-border); border-radius: 14px; padding: 22px; transition: border-color 0.3s, transform 0.2s, box-shadow 0.3s; position: relative; overflow: hidden; } .card:hover { border-color: rgba(181,86,122,0.3); transform: translateY(-2px); box-shadow: 0 8px 30px rgba(107,63,160,0.15); } .card-icon { font-size: 2rem; margin-bottom: 10px; display: block; } .card-number { position: absolute; top: 14px; right: 16px; background: linear-gradient(135deg, var(--primary), var(--accent)); color: #fff; width: 30px; height: 30px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 0.8rem; font-weight: 700; } .card h4 { font-size: 1rem; font-weight: 700; color: #fff; margin-bottom: 6px; } .card p { font-size: 0.85rem; color: var(--text-muted); line-height: 1.5; } .card-accent-top { border-top: 3px solid var(--accent); } .card-accent-gold { border-top: 3px solid var(--gold); } .card-accent-success { border-top: 3px solid var(--success); } .card-accent-info { border-top: 3px solid var(--info); } .card-accent-danger { border-top: 3px solid var(--danger); } /\* ── Phase Flow ── \*/ .phase-flow { display: flex; align-items: center; justify-content: center; gap: 0; margin: 30px 0; flex-wrap: wrap; } .phase-node { text-align: center; padding: 18px 24px; border-radius: 14px; min-width: 180px; position: relative; } .phase-node.p1 { background: linear-gradient(135deg, rgba(52,152,219,0.15), rgba(52,152,219,0.05)); border: 1px solid rgba(52,152,219,0.3); } .phase-node.p2 { background: linear-gradient(135deg, rgba(107,63,160,0.15), rgba(107,63,160,0.05)); border: 1px solid rgba(107,63,160,0.3); } .phase-node.p3 { background: linear-gradient(135deg, rgba(201,123,58,0.15), rgba(201,123,58,0.05)); border: 1px solid rgba(201,123,58,0.3); } .phase-node.p4 { background: linear-gradient(135deg, rgba(39,174,96,0.15), rgba(39,174,96,0.05)); border: 1px solid rgba(39,174,96,0.3); } .phase-node .phase-icon { font-size: 1.8rem; margin-bottom: 6px; } .phase-node .phase-name { font-weight: 700; font-size: 0.95rem; color: #fff; } .phase-node .phase-weeks { font-size: 0.75rem; color: var(--text-muted); margin-top: 4px; } .phase-arrow { font-size: 1.5rem; color: var(--text-muted); margin: 0 6px; } /\* ── Tables ── \*/ .data-table { width: 100%; border-collapse: collapse; margin: 14px 0; font-size: 0.85rem; } .data-table thead th { background: rgba(107,63,160,0.25); color: #fff; padding: 10px 14px; text-align: left; font-weight: 600; font-size: 0.8rem; text-transform: uppercase; letter-spacing: 0.5px; border-bottom: 2px solid rgba(107,63,160,0.3); } .data-table thead th:first-child { border-radius: 8px 0 0 0; } .data-table thead th:last-child { border-radius: 0 8px 0 0; } .data-table tbody td { padding: 10px 14px; border-bottom: 1px solid rgba(255,255,255,0.05); color: var(--text-light); } .data-table tbody tr:hover { background: rgba(107,63,160,0.08); } .data-table tbody tr:nth-child(even) { background: rgba(255,255,255,0.02); } /\* ── Badges ── \*/ .badge { display: inline-block; padding: 3px 10px; border-radius: 12px; font-size: 0.72rem; font-weight: 600; letter-spacing: 0.3px; } .badge-fit { background: rgba(39,174,96,0.2); color: #5ced96; } .badge-config { background: rgba(52,152,219,0.2); color: #74c0fc; } .badge-extend { background: rgba(243,156,18,0.2); color: #ffd06a; } .badge-gap { background: rgba(231,76,60,0.2); color: #ff8a7a; } .badge-a { background: rgba(39,174,96,0.2); color: #5ced96; } .badge-b { background: rgba(52,152,219,0.2); color: #74c0fc; } .badge-c { background: rgba(243,156,18,0.2); color: #ffd06a; } .badge-d { background: rgba(231,76,60,0.2); color: #ff8a7a; } .badge-retire { background: rgba(231,76,60,0.15); color: #ff8a7a; } .badge-replace { background: rgba(52,152,219,0.15); color: #74c0fc; } .badge-refit { background: rgba(243,156,18,0.15); color: #ffd06a; } .badge-rewrite { background: rgba(181,86,122,0.15); color: #e8a0bb; } .badge-retain { background: rgba(39,174,96,0.15); color: #5ced96; } .badge-critical { background: rgba(231,76,60,0.2); color: #ff8a7a; } .badge-high { background: rgba(243,156,18,0.2); color: #ffd06a; } .badge-medium { background: rgba(52,152,219,0.2); color: #74c0fc; } .badge-low { background: rgba(39,174,96,0.2); color: #5ced96; } .badge-phase { background: linear-gradient(135deg, var(--primary), var(--accent)); color: #fff; } /\* ── Expandable Details ── \*/ details { background: var(--card-bg); border: 1px solid var(--card-border); border-radius: 10px; margin: 10px 0; overflow: hidden; } details summary { padding: 12px 18px; cursor: pointer; font-weight: 600; font-size: 0.9rem; color: var(--accent-light); display: flex; align-items: center; gap: 8px; transition: background 0.2s; list-style: none; } details summary::-webkit-details-marker { display: none; } details summary::before { content: '▸'; font-size: 0.8rem; transition: transform 0.2s; display: inline-block; } details\[open\] summary::before { transform: rotate(90deg); } details summary:hover { background: rgba(255,255,255,0.04); } details .detail-body { padding: 0 18px 16px 18px; font-size: 0.85rem; line-height: 1.6; color: var(--text-muted); } details .detail-body ul { padding-left: 20px; margin: 8px 0; } details .detail-body li { margin: 4px 0; } details .detail-body li::marker { color: var(--accent); } /\* ── Gate Boxes ── \*/ .gate-box { background: linear-gradient(135deg, rgba(107,63,160,0.12), rgba(181,86,122,0.08)); border: 2px solid rgba(181,86,122,0.3); border-radius: 16px; padding: 24px 28px; margin: 20px 0; position: relative; } .gate-box::before { content: '🚦'; position: absolute; top: -14px; left: 24px; font-size: 1.5rem; background: var(--dark); padding: 0 8px; } .gate-box h4 { color: var(--accent-light); font-size: 1.05rem; margin-bottom: 10px; } .gate-box .checklist { list-style: none; padding: 0; } .gate-box .checklist li { padding: 5px 0; padding-left: 26px; position: relative; font-size: 0.88rem; color: var(--text-light); } .gate-box .checklist li::before { content: '☐'; position: absolute; left: 0; color: var(--gold); font-size: 1rem; } /\* ── Callout ── \*/ .callout { background: rgba(201,123,58,0.1); border-left: 4px solid var(--gold); border-radius: 0 10px 10px 0; padding: 16px 20px; margin: 16px 0; font-size: 0.88rem; color: var(--text-light); } .callout strong { color: var(--gold-light); } .callout-info { background: rgba(52,152,219,0.1); border-left-color: var(--info); } .callout-info strong { color: #74c0fc; } .callout-danger { background: rgba(231,76,60,0.1); border-left-color: var(--danger); } .callout-danger strong { color: #ff8a7a; } .callout-success { background: rgba(39,174,96,0.1); border-left-color: var(--success); } .callout-success strong { color: #5ced96; } /\* ── Timeline ── \*/ .timeline { position: relative; padding-left: 40px; margin: 20px 0; } .timeline::before { content: ''; position: absolute; left: 14px; top: 0; bottom: 0; width: 2px; background: linear-gradient(to bottom, var(--info), var(--primary), var(--gold), var(--success)); } .timeline-item { position: relative; padding: 12px 0 20px 20px; } .timeline-item::before { content: ''; position: absolute; left: -32px; top: 16px; width: 12px; height: 12px; border-radius: 50%; border: 2px solid var(--accent); background: var(--dark); } .timeline-item.active::before { background: var(--accent); box-shadow: 0 0 10px rgba(181,86,122,0.5); } .timeline-item .tl-date { font-size: 0.75rem; color: var(--gold-light); font-weight: 600; text-transform: uppercase; letter-spacing: 1px; } .timeline-item .tl-title { font-size: 0.95rem; font-weight: 700; color: #fff; margin: 4px 0; } .timeline-item .tl-desc { font-size: 0.82rem; color: var(--text-muted); line-height: 1.5; } /\* ── RACI Grid ── \*/ .raci-cell { font-weight: 700; text-align: center; } .raci-r { color: #ff8a7a; } .raci-a { color: #ffd06a; } .raci-c { color: #74c0fc; } .raci-i { color: var(--text-muted); } /\* ── Risk Row ── \*/ .risk-row td:first-child { font-weight: 600; color: #fff; } /\* ── Navigation ── \*/ .nav-bar { position: fixed; bottom: 0; left: 0; right: 0; background: rgba(26,26,46,0.95); backdrop-filter: blur(20px); border-top: 1px solid rgba(255,255,255,0.08); display: flex; align-items: center; justify-content: space-between; padding: 12px 30px; z-index: 100; } .nav-dots { display: flex; gap: 8px; align-items: center; } .nav-dot { width: 10px; height: 10px; border-radius: 50%; background: rgba(255,255,255,0.15); cursor: pointer; transition: all 0.3s; border: none; padding: 0; } .nav-dot.active { background: linear-gradient(135deg, var(--primary), var(--accent)); transform: scale(1.3); box-shadow: 0 0 10px rgba(181,86,122,0.4); } .nav-dot:hover:not(.active) { background: rgba(255,255,255,0.3); } .nav-btn { background: var(--card-bg); border: 1px solid var(--card-border); color: #fff; padding: 8px 20px; border-radius: 8px; cursor: pointer; font-size: 0.85rem; font-weight: 600; transition: all 0.3s; display: flex; align-items: center; gap: 6px; } .nav-btn:hover { background: rgba(107,63,160,0.3); border-color: var(--primary); } .nav-btn:disabled { opacity: 0.3; cursor: default; } .slide-counter { font-size: 0.8rem; color: var(--text-muted); font-weight: 600; min-width: 60px; text-align: center; } /\* ── Utility ── \*/ .two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin: 14px 0; } .mt-1 { margin-top: 10px; } .mt-2 { margin-top: 20px; } .mb-1 { margin-bottom: 10px; } .mb-2 { margin-bottom: 20px; } .text-center { text-align: center; } .separator { height: 1px; background: linear-gradient(to right, transparent, var(--card-border), transparent); margin: 20px 0; } .tag-list { display: flex; flex-wrap: wrap; gap: 8px; margin: 8px 0; } .tag { background: rgba(107,63,160,0.15); border: 1px solid rgba(107,63,160,0.25); color: var(--primary-light); padding: 4px 12px; border-radius: 20px; font-size: 0.75rem; font-weight: 600; } /\* ── Code Blocks ── \*/ .code-block { background: rgba(0,0,0,0.3); border: 1px solid rgba(255,255,255,0.08); border-radius: 8px; padding: 14px 18px; font-family: 'Cascadia Code', 'Fira Code', monospace; font-size: 0.8rem; color: #c8d6e5; overflow-x: auto; margin: 10px 0; line-height: 1.6; } /\* ── Print ── \*/ @media print { .nav-bar { display: none; } .slide { position: relative; opacity:1; visibility:visible; transform:none; page-break-after: always; overflow: visible; height: auto; } body { overflow: visible; height: auto; } .deck { overflow: visible; height: auto; } } /\* ── Responsive ── \*/ @media (max-width: 900px) { .slide-inner { padding: 30px 24px 90px 24px; } .slide-title { font-size: 1.8rem; } .hero-title { font-size: 2.2rem; } .card-grid-3, .card-grid-4, .card-grid-5 { grid-template-columns: 1fr 1fr; } .two-col { grid-template-columns: 1fr; } .phase-flow { flex-direction: column; } .phase-arrow { transform: rotate(90deg); } } @media (max-width: 600px) { .card-grid-3, .card-grid-4, .card-grid-5, .card-grid { grid-template-columns: 1fr; } .hero-stats { flex-direction: column; align-items: center; } }

🚀

ABB ECC → S/4HANA 2025  
Migration Playbook

A comprehensive, phase-gated execution guide — covering business process mapping, Fit-to-Standard analysis, Clean Core remediation, and production cutover.

4

Phases

21

Plays

4

Decision Gates

~13

Months

8

Workstreams

C16 Migration Playbook v2.0 — April 2026

Context

Why Migrate Now?

ECC mainstream maintenance ends 2027. S/4HANA 2025 is SAP's strategic platform with AI, Clean Core, and cloud extensibility.

⚠️

#### ECC Risks (Staying Put)

*   Mainstream maintenance ends **2027**
*   No new features or innovation
*   Growing technical debt in custom code
*   Vendor/Customer master on legacy model (KNA1/LFA1)
*   Multiple redundant tables (BSEG, MSEG, MKPF)
*   Limited analytics (BW dependency)
*   No cloud extensibility or AI capabilities

✨

#### S/4HANA 2025 Benefits

*   Unified Business Partner model (BUT000)
*   Single journal (ACDOCA) — real-time finance
*   Simplified data model (MATDOC replaces MSEG+MKPF)
*   Embedded Analytics via CDS views
*   SAP Joule AI copilot integration
*   Clean Core extensibility (BTP, RAP, Key User)
*   600+ Fiori apps — modern UX

**🎯 ABB's Top Priorities:** SAP Fit-to-Standard and Clean Core compliance. This playbook is designed to maximize standard adoption and minimize custom code carry-forward.

Framework

The 4-Phase Migration Journey

Every custom object, business process, and interface follows this path — with decision gates between each phase.

🔍

DISCOVER

Weeks 1–6

→

📊

ASSESS

Weeks 5–12

→

🔧

REMEDIATE

Weeks 10–28

→

🚀

MIGRATE

Weeks 26–52

#### Phase 1: DISCOVER

Inventory all business processes, custom code, interfaces, forms, and data volumes in ECC. Build the complete landscape picture.

Plays 1–4 Gate 1

#### Phase 2: ASSESS

Map every ECC process to S/4HANA standard. Classify custom code (Level A–D). Run Fit-to-Standard workshops per module.

Plays 5–8 Gate 2

#### Phase 3: REMEDIATE

Close gaps. Retire/Replace/Refit/Rewrite custom code. Execute BP migration prep. Convert interfaces and forms.

Plays 9–14 Gate 3

#### Phase 4: MIGRATE

System build, data migration, 8-layer testing, user training, cutover rehearsal, go-live, and hypercare.

Plays 15–21 Gate 4

Governance

Workstream RACI & Governance

Clear ownership across 8 workstreams. Every activity has exactly one Accountable owner.

Workstream

Steering

Program Mgr

Functional

Technical

Data Team

Testing

Training

Change Mgmt

Business Process Mapping

A

R

R

C

I

I

I

C

Custom Code Remediation

I

A

C

R

I

C

I

I

Data Migration

I

A

C

R

R

C

I

I

Fit-to-Standard Workshops

A

R

R

C

I

I

C

R

Integration & Interfaces

I

A

C

R

C

R

I

I

Testing & Validation

I

A

R

R

C

R

I

C

Training & Adoption

A

C

R

I

I

I

R

R

Go-Live & Hypercare

A

R

R

R

R

R

C

R

R = Responsible  |  A = Accountable  |  C = Consulted  |  I = Informed

Phase 1 · Weeks 1–6

🔍 DISCOVER — Current State Inventory

Build a complete picture of ABB's ECC landscape — processes, customizations, interfaces, data volumes.

1 📋

#### Play 1: Business Process Catalogue

Interview process owners across all modules. Document every transaction used, process variant, and business rule.

Show Checklist

*   Run **ST03N** — extract top 200 transactions by usage (last 12 months)
*   Map each transaction to its SAP module (MM, SD, FI/CO, PP, PM, QM, HR, WM)
*   Interview 2-3 process owners per module (30-min sessions)
*   Document process variants — e.g., "PO with subcontracting" vs "standard PO"
*   Capture frequency: daily / weekly / monthly / quarterly / annual
*   Record integration touchpoints (upstream/downstream systems)
*   Output: **Process Catalogue spreadsheet** with ~50-200 processes

2 🧩

#### Play 2: Custom Code Inventory

Scan TADIR for all Z/Y objects. Categorize by type, module, and usage frequency.

Show Checklist

*   Query TADIR: `obj_name LIKE 'Z%' OR obj_name LIKE 'Y%'` for all object types
*   Group by type: PROG, CLAS, FUGR, TRAN, TABL, VIEW, ENHS, WDYN, SSFO, FORM
*   Cross-reference with ST03N usage data — flag objects with **zero usage in 12 months**
*   Scan MODSAP for active customer exits
*   Scan SXS\_ATTR for BAdI implementations
*   Check SPAU/SPDD for SAP standard modifications
*   Output: **Custom Code Register** — expect 5,000-30,000 objects for ABB's scale

3 🔗

#### Play 3: Interface & Integration Map

Catalogue all inbound/outbound interfaces: IDocs, RFC, SOAP, files, middleware connections.

Show Checklist

*   Query WE20/WE21 for IDoc partner profiles and ports
*   Query SM59 for RFC destinations (type 3 = ABAP, type H = HTTP, type G = External)
*   Inventory PI/PO interfaces (if SAP PI/PO is in use)
*   Document file-based interfaces (FTP, SFTP, shared drives)
*   Map source → target for each interface
*   Classify: Keep Modernize Replace
*   Output: **Interface Register** with ~50-300 interfaces

4 📊

#### Play 4: Data Volume & Archiving Assessment

Measure table sizes for migration sizing. Identify archiving opportunities to reduce migration scope.

Show Checklist

*   Run DB02 — top 100 tables by row count and size
*   Focus on: BKPF/BSEG, EKKO/EKPO, VBAK/VBAP, MSEG/MKPF, CDPOS/CDHDR
*   Calculate total data volume (GB) for migration window estimation
*   Identify candidates for archiving BEFORE migration (change docs, old orders, completed POs)
*   Assess Z-table data: migrate, transform, or discard?
*   Output: **Data Volume Report** + **Archiving Recommendations**

#### 🚦 GATE 1 — Discovery Complete

*   Process Catalogue covers all 8+ modules with process owner sign-off
*   Custom Code Register is complete — all Z/Y objects inventoried with usage data
*   Interface Register covers all inbound/outbound connections
*   Data Volume Report delivered with archiving recommendations
*   Enhancement Register (customer exits, BAdIs, modifications) is complete

Phase 2 · Weeks 5–12

📊 ASSESS — Fit-to-Standard Analysis

For every ECC business process, determine if S/4HANA 2025 standard covers it — and identify gaps.

### 🎯 Fit-to-Standard Classification Framework

#### ✅ FIT

S/4HANA standard does this **as-is**. No customization needed. Adopt standard process directly.

Target: 60-70% of processes

#### 🔧 FIT + CONFIG

Standard covers it with **configuration**. No code — just IMG settings, BRF+ rules, or Key User adaptation.

Target: 15-20% of processes

#### 🔶 FIT + EXTEND

Standard covers ~70-80%. Needs a **Clean Core extension** — BAdI, RAP, or BTP side-by-side.

Target: 10-15% of processes

#### 🔴 GAP

**No standard equivalent.** Custom solution required — but must use Clean Core patterns (Released APIs, RAP).

Target: <5% of processes

📝 Play 5: Fit-to-Standard Workshop Template (Per Module)

**Participants:** Process Owner, Functional Consultant, Technical Lead, Change Manager

**Duration:** 4 hours per module

**Steps:**

1.  **Process Walkthrough** — Owner demos the current ECC process (live or recording)
2.  **Requirement Decomposition** — Break into R1, R2, R3… discrete requirements
3.  **Standard Matching** — For each requirement, search SAP Fiori Apps Library + Best Practices Explorer
4.  **Gap Identification** — Requirements with no standard match = GAP
5.  **Disposition Decision** — Classify each: FIT / FIT+CONFIG / FIT+EXTEND / GAP
6.  **Coverage Calculation** — Compute % of requirements covered by standard
7.  **Workshop Output** — Signed-off Fit-to-Standard matrix per module

📊 Play 6: Clean Core Classification (Level A–D)

Level

Meaning

Pattern Example

Action

Level A

Cloud-ready — Released APIs only

CDS views, RAP BOs, Released BAPIs

✅ Keep as-is

Level B

Classic stable — works on S/4 on-prem

REUSE\_ALV, classic BAPIs, stable RFCs

⚠️ Modernize when feasible

Level C

Non-compliant — unreleased APIs

Direct SELECT on SAP tables, unreleased FMs

🔴 Must remediate

Level D

Critical — deprecated/removed

SAPscript, removed tables (KONV→PRCD\_ELEMENTS), classic WM

🚨 Will BREAK — mandatory fix

**Tools:** SAP Readiness Check, ATC with ABAP\_CLOUD\_READINESS variant, or C16 auto-classification (if connected).

Phase 2 · Mapping

ECC → S/4HANA Process Mapping

Module-by-module mapping of ECC transactions to S/4HANA standard Fiori apps and APIs.

📦 Materials Management (MM)

ECC Process

ECC TCode

S/4HANA Standard

Fiori App

Status

Create Purchase Requisition

ME51N

Manage Purchase Requisitions

F1132

FIT

Create Purchase Order

ME21N

Manage Purchase Orders (V2)

F0842

FIT

Goods Receipt

MIGO

Post Goods Receipt for PO

F0875

FIT

Invoice Verification

MIRO

Create Supplier Invoice

F0859

FIT

Vendor Evaluation

ME61

Supplier Evaluation

F2669

CONFIG

Vendor Master Report

ZMM001

Manage Supplier (BP)

F1739

EXTEND

MSME Classification

Custom

No standard equivalent

—

GAP

PO Enhancement (BAdI)

ME21N+

BAdI: MM\_PUR\_S4\_PO

—

EXTEND

💰 Sales & Distribution (SD)

ECC Process

ECC TCode

S/4HANA Standard

Fiori App

Status

Create Sales Order

VA01

Manage Sales Orders

F6588

FIT

Delivery Processing

VL01N

Create Outbound Delivery

F1704

FIT

Billing

VF01

Create Billing Documents

F2580

FIT

Credit Management

FD32/UKM

SAP Credit Management (FSCM)

F3880

CONFIG

Available-to-Promise

CO09

Advanced ATP (aATP)

F2093

EXTEND

Output Determination

NACE

BRF+ / Output Management

—

CONFIG

📒 Finance (FI/CO)

ECC Process

ECC TCode

S/4HANA Standard

Fiori App

Status

GL Posting

FB50

Post General Journal Entry

F0717

FIT

AP Invoice

FB60

Post Supplier Invoice

F0859

FIT

AR Invoice

FB70

Create Customer Invoice

F2566

FIT

Bank Reconciliation

FEBP

Advanced Payment Management

F4580

CONFIG

Asset Accounting

AS01

Manage Fixed Assets

F2899

FIT

Cost Center Reporting

KSB1

ACDOCA Embedded Analytics

F1603

FIT

CO-PA Reporting

KE30

Universal Journal (ACDOCA)

F3715

CONFIG

🏭 Production, Plant Maintenance & Quality (PP/PM/QM)

ECC Process

ECC TCode

S/4HANA Standard

Fiori App

Status

Production Order

CO01

Manage Production Orders

F3823

FIT

MRP Run

MD01

MRP Live (ppMRP)

F3059

CONFIG

Maintenance Order

IW31

Manage Maintenance Orders

F3581

FIT

Quality Inspection

QA01

Manage Quality Inspections

F3264

FIT

Classic WM

LT01

Embedded EWM

F5193

EXTEND

Phase 2 · SAP Note 2313884

S/4HANA Simplification Impact

The 12 highest-impact items from the SAP Simplification List that will affect ABB's migration.

#

Simplification Item

ECC → S/4HANA Change

Impact

ABB Risk

1

Business Partner Migration

KNA1/LFA1 → BUT000 (BP)

CRITICAL

All vendor/customer reports, interfaces, and enhancements

2

Universal Journal

BSEG → ACDOCA for reporting

CRITICAL

All FI reports querying BSEG/BSIS/BSAS

3

Material Document

MSEG/MKPF → MATDOC

HIGH

Custom inventory reports

4

Material Ledger

Mandatory activation

HIGH

Costing, CO-PA, profit analysis

5

CO-PA

Costing-based → Account-based only

HIGH

Custom CO-PA reports

6

Warehouse Management

LE-WM removed → EWM only

CRITICAL

If ABB uses classic WM

7

Credit Management

FD32 → SAP Credit Mgmt (FSCM)

MEDIUM

Custom credit check logic

8

Output Management

NACE → BRF+ / OM

MEDIUM

Custom output types and forms

9

Condition Tables

KONV → PRCD\_ELEMENTS

HIGH

Custom pricing reports on KONV

10

MRP

Classic → MRP Live

MEDIUM

Custom MRP enhancements

11

Asset Accounting

Classic → New Asset Accounting

MEDIUM

Custom depreciation reports

12

ABAP Dictionary

Pooled/Cluster tables → transparent

LOW

Custom code on BSEG (cluster → transparent)

**🚨 #1 Risk: Business Partner Migration.** Every program, interface, and report that touches LFA1 (vendor) or KNA1 (customer) must be re-mapped to the Business Partner model. This affects potentially hundreds of custom objects at ABB's scale.

#### 🚦 GATE 2 — Assessment Complete

*   Fit-to-Standard matrix signed off for every module
*   Every custom object classified Level A/B/C/D
*   Every custom object assigned a disposition: RETIRE / REPLACE / REFIT / REWRITE / RETAIN
*   Gap register complete with complexity ratings
*   Simplification impact assessed per ABB-specific scenario
*   Migration approach confirmed (Greenfield / Brownfield / Bluefield)

Phase 3 · Disposition

🔧 The 5 Rs — Custom Code Disposition

Every custom object gets exactly ONE disposition. This determines its migration path.

#### 🗑️ RETIRE

S/4HANA standard replaces it entirely. Decommission the Z-object.

**Effort:** Low  
**Target:** 30-40%

#### 🔄 REPLACE

Standard covers 90%+. Minor config replaces the custom logic.

**Effort:** Low-Med  
**Target:** 15-20%

#### 🛠️ REFIT

Standard covers 70-89%. Needs Clean Core extension (BAdI, RAP, Key User).

**Effort:** Medium  
**Target:** 15-20%

#### ✍️ REWRITE

Logic is unique but code is Level C/D. Rewrite using Released APIs (CDS, RAP).

**Effort:** High  
**Target:** 10-15%

#### ✅ RETAIN

Already Level A/B. Unique IP, validated on S/4. Keep as-is.

**Effort:** Minimal  
**Target:** 5-10%

### 📋 Known ABB Programs — Preliminary Disposition

Program

Purpose

Likely Level

Disposition

Rationale

ZMM\_PO\_ENHANCE

PO Enhancement (BAdI)

C

REFIT

Migrate to S/4 BAdI MM\_PUR\_S4\_PO using Released APIs

Z\_VENDOR\_SCORE

Vendor Scoring Report

C

REPLACE

Standard Supplier Evaluation (ME61) + Fiori F2669

ZMM001

Custom Vendor Transaction

C

RETIRE

Manage Supplier (F1739) covers standard vendor views

ZMM\_VENDOR\_REPORT

Vendor Master Report

C

REWRITE

Complex custom logic — rewrite with CDS + Fiori Elements

ZMM\_VENDOR\_MSME

MSME Classification

C

REWRITE

GAP — no standard. Build as RAP BO with E\_Supplier extension

**⚡ C16 Accelerator:** Once connected to ABB's ECC, C16 can auto-classify ALL custom objects and assign preliminary dispositions in hours — including per-program Clean Core analysis with remediation code.

Phase 3 · Weeks 10–28

🔧 REMEDIATE — Execution Sprints

Close gaps, retire obsolete code, rewrite non-compliant objects. 2-week sprints with clear deliverables.

9

#### Play 9: Quick Wins

Retire unused objects (zero ST03N usage). Delete dead code. Archive obsolete reports.

Sprint Template

*   **Day 1-2:** Identify zero-usage objects from Phase 1 data
*   **Day 3-5:** Confirm with process owners: "Is this used outside SAP GUI?" (batch jobs, external calls)
*   **Day 6-8:** Mark confirmed unused objects for deletion
*   **Day 9-10:** Execute deletion in DEV → transport to QAS
*   **Expected outcome:** 30-40% of custom objects retired

10

#### Play 10: BP Migration Prep

The #1 risk item. Prepare vendor/customer master data for Business Partner conversion.

6-Step BP Migration

1.  **Activate CVI** — Customer Vendor Integration synchronization
2.  **Data Cleansing** — Deduplicate vendors, fix addresses, validate tax IDs
3.  **BP Number Range** — Decide: same numbers or new range?
4.  **BP Grouping** — Map vendor account groups (KTOKK) → BP groupings
5.  **Custom Fields** — Map LFA1/KNA1 appends → CI\_\* or E\_\* extension includes
6.  **Test Migration** — Run CVI sync on sandbox, validate BP records

11

#### Play 11: Code Remediation

Rewrite Level C/D objects using Released APIs. Convert direct table access to CDS views.

Remediation Patterns

ECC Pattern

S/4 Clean Core Pattern

`SELECT * FROM lfa1`

`SELECT FROM I_Supplier` (CDS)

`SELECT * FROM kna1`

`SELECT FROM I_Customer` (CDS)

`SELECT * FROM bseg`

`SELECT FROM I_JournalEntry` (CDS)

`SELECT * FROM mseg`

`SELECT FROM I_MaterialDocumentItem` (CDS)

`CALL FUNCTION 'BAPI_PO_CREATE1'`

Released API: `I_PurchaseOrderTP` (RAP BO)

`REUSE_ALV_GRID_DISPLAY`

CDS + Fiori Elements List Report

Customer Exit (CMOD)

BAdI implementation (Released BAdI)

SAPscript / SmartForm

Adobe Form (SFP) or Output Mgmt

12

#### Play 12: Interface Modernization

Convert legacy interfaces to Released APIs. Replace RFC with OData where applicable.

Interface Migration Paths

*   **IDoc → IDoc:** Keep stable IDocs. Update segments if tables changed.
*   **BAPI RFC → Released API:** Replace BAPI\_VENDOR\_\* with BP APIs
*   **File upload → OData:** Modern API-based integration
*   **PI/PO → Integration Suite:** If moving to BTP
*   **Direct RFC → Event Mesh:** Decoupled, async integration

13

#### Play 13: Forms Migration

Convert SAPscript → Adobe Forms. Migrate SmartForms to SFP or Output Management.

Conversion Approach

*   **SAPscript:** Manual redesign in Adobe Form Designer (SFP)
*   **SmartForm:** C16 automated conversion pipeline (SmartForm XML → XDP → Adobe Form)
*   **Adobe Forms:** Validate compatibility — most carry forward
*   **Output Management:** Configure BRF+ rules for output determination

14

#### Play 14: Gap Solutions

Build Clean Core solutions for identified GAPS — using RAP, CDS, BTP extensions.

Gap Closure Architecture

*   **MSME Classification (GAP):** Custom RAP BO with E\_Supplier extension + Fiori Elements app
*   **Vendor Blacklist (GAP):** Custom CDS entity + Released BAdI for PO validation
*   **Consolidated Vendor View (GAP):** CDS view composing I\_Supplier + I\_SupplierCompany + I\_SupplierPurchasingOrg + custom extensions
*   All gap solutions MUST use Released APIs only (Level A target)

#### 🚦 GATE 3 — Remediation Complete

*   All RETIRE objects decommissioned and confirmed by process owners
*   All REWRITE objects rebuilt with Level A/B APIs, syntax-checked, unit tested
*   BP migration dry-run successful in sandbox
*   All interfaces validated against S/4HANA API compatibility
*   All GAP solutions built and functionally tested
*   ATC ABAP\_CLOUD\_READINESS check passes for all remediated objects

Phase 3 · Critical Path

Business Partner Migration

The #1 risk item in any ECC → S/4HANA migration. Every vendor and customer record must become a Business Partner.

**🚨 Why This Is #1 Risk:** ABB likely has thousands of vendors and customers. Every Z-program, report, interface, and enhancement that touches LFA1 (vendor) or KNA1 (customer) must be re-mapped to the Business Partner model. A missed reference = runtime dump in S/4HANA.

### 🏗️ Architecture: ECC vs S/4HANA

#### ❌ ECC Model (Being Replaced)

Vendors: LFA1 → LFB1 → LFM1 → LFBK Customers: KNA1 → KNB1 → KNVV → KNBK Contacts: KNVK (customer only) Addresses: ADRC (shared)

#### ✅ S/4HANA Model (Target)

Business Partner: BUT000 (central) ├── Roles: BUT100 (organization) ├── Addresses: BUT020 → ADRC ├── Bank Details: BUT0BK ├── Tax Numbers: DFKKBPTAXNUM ├── Relationships: BUT050/BUT051 │ ├── CDS Views (Released): │ ├── I\_Supplier (vendor role) │ ├── I\_Customer (customer role) │ ├── I\_BusinessPartner (all) │ └── I\_BPContactToFuncAndDept

### 📋 Custom Code Impact Scan

Search Pattern

What It Finds

Action Required

`SELECT * FROM LFA1`

All vendor master reads

Replace with `I_Supplier` CDS view

`SELECT * FROM KNA1`

All customer master reads

Replace with `I_Customer` CDS view

`BAPI_VENDOR_CREATE`

Vendor creation interfaces

Replace with `API_BUSINESS_PARTNER`

`BAPI_CUSTOMER_CREATEFROMDATA`

Customer creation interfaces

Replace with `API_BUSINESS_PARTNER`

`KTOKK` / `KTOKD`

Account group references

Map to BP Grouping (BU\_GROUP)

`LIFNR` type checks

Vendor number handling

Validate BP number range compatibility

**💡 CVI Compatibility Views:** S/4HANA provides compatibility views (LFA1, KNA1 as CDS views) that allow legacy SELECTs to continue working. However, these are **not Released APIs** — they're Level B at best. For Clean Core, always use I\_Supplier / I\_Customer.

Phase 4 · Weeks 26–52

🚀 MIGRATE — Build, Test, Go-Live

System build, data migration, 8-layer testing, user training, and production cutover.

15

#### Play 15: System Build

Provision S/4HANA 2025 sandbox and DEV systems. Configure baseline per Fit-to-Standard output.

Build Checklist

*   Install S/4HANA 2025 FPS01 (Feature Pack Stack 01)
*   Activate Business Partner (CVI sync)
*   Activate Material Ledger (mandatory)
*   Configure ACDOCA (ledger groups, CO-PA characteristics)
*   Set up Fiori Launchpad + role-based catalogs
*   Create ABAP Cloud packages (ABAP Language Version 2)
*   Deploy remediated custom objects

16

#### Play 16: Data Migration

Migrate master data, transactional data, and open items using SAP Migration Cockpit.

Migration Objects

*   **Master Data:** Business Partners (vendors + customers via CVI), Materials, GL Accounts, Cost Centers, Profit Centers
*   **Open Items:** Open AP/AR invoices, open POs, open deliveries
*   **Balances:** GL balances (FAGLFLEXT → ACDOCA), asset balances (ANLC), inventory balances
*   **Historical:** Decide cutoff — migrate N years of history? Or archive and start fresh?
*   **Custom Tables:** Z-table data — transform/cleanse during migration
*   **Tool:** SAP S/4HANA Migration Cockpit (LTMC) with XML/CSV templates

17

#### Play 17: 8-Layer Testing

Comprehensive testing from unit through cutover rehearsal.

Test Layers

Layer

Scope

Owner

L1: Unit Test

Individual objects — syntax, ATC, ABAP Unit

Technical

L2: Integration Test

End-to-end process flows (PR→PO→GR→IV→Pay)

Functional

L3: Migration Test

Data migration dry run — completeness, accuracy

Data Team

L4: Interface Test

All inbound/outbound interfaces

Technical

L5: Performance Test

Volume testing with production-scale data

Technical

L6: UAT

Business user acceptance — all critical processes

Business

L7: Regression Test

Automated test scripts for ~200 critical scenarios

QA Team

L8: Cutover Rehearsal

Full dress rehearsal of go-live weekend

All Teams

18

#### Play 18: User Training

Role-based training on new Fiori UX, changed processes, and new data model.

19

#### Play 19: Cutover Runbook

Hour-by-hour production cutover plan with rollback criteria.

Cutover Sequence

1.  **T-4 weeks:** Final regression test pass in QAS
2.  **T-2 weeks:** Cutover rehearsal in PRE-PROD
3.  **T-0 Friday PM:** Lock ECC users, final data export
4.  **T-0 Saturday:** Data migration execution, delta load
5.  **T-0 Sunday AM:** Validation scripts, smoke tests
6.  **T-0 Sunday PM:** Go/No-Go decision (Steering Committee)
7.  **T+1 Monday:** Production go-live with war room support
8.  **T+1 to T+4 weeks:** Hypercare — dedicated support team

20

#### Play 20: Hypercare

4 weeks of dedicated support post go-live. Daily triage calls. Incident SLA tracking.

#### 🚦 GATE 4 — Go-Live Readiness

*   All 8 test layers passed with zero P1/P2 defects open
*   Data migration validation: 100% of master data records reconciled
*   All interfaces tested end-to-end with partner systems
*   Cutover rehearsal completed within planned window
*   User training completion rate ≥ 95% for critical roles
*   Rollback plan tested and approved
*   Steering Committee sign-off: GO

Roadmap

13-Month Migration Timeline

Phase-gated execution from May 2026 to June 2027.

May – June 2026 (Weeks 1–6)

🔍 Phase 1: DISCOVER

Process catalogue, custom code inventory, interface map, data volume assessment. **Gate 1** at end of Week 6.

June – August 2026 (Weeks 5–12)

📊 Phase 2: ASSESS

Fit-to-Standard workshops per module, Clean Core classification, gap analysis, simplification impact. **Gate 2** at end of Week 12. Migration approach confirmed.

August – December 2026 (Weeks 10–28)

🔧 Phase 3: REMEDIATE

Quick wins (retire 30-40%), BP migration prep, code remediation sprints (2-week cycles), interface conversion, forms migration, gap solutions built. **Gate 3** at end of Week 28.

September 2026 (within Phase 3)

🏗️ Milestone: S/4HANA Sandbox Available

S/4HANA 2025 sandbox provisioned. Remediated objects deployed and validated. BP migration dry-run #1.

December 2026 – April 2027 (Weeks 26–44)

🚀 Phase 4a: BUILD & TEST

Production system build, data migration execution, 8-layer testing (unit → UAT → performance → cutover rehearsal).

March – April 2027

🎓 User Training

Role-based Fiori training. Process change workshops. Super-user certification.

May 2027 (Week 48)

🎯 Cutover Rehearsal

Full dress rehearsal of go-live weekend. Validate timing, rollback, and data reconciliation. **Gate 4** — Go/No-Go decision.

June 2027 (Week 52)

🚀 GO-LIVE

Production cutover. ECC locked Friday PM → S/4HANA live Monday AM. 4-week hypercare with dedicated war room.

Risk Management

Risk Register — 8 Key Risks

Proactive risk identification with mitigation strategies for each.

#

Risk

Probability

Impact

Severity

Mitigation

R1

BP migration data quality issues

High

Critical

CRITICAL

Start CVI sync + data cleansing in Phase 1. Run 3 migration dry-runs before cutover.

R2

Custom code volume exceeds remediation capacity

High

High

CRITICAL

Use C16 for automated classification + code generation. Retire aggressively (target 40%).

R3

Classic WM → EWM scope underestimated

Medium

Critical

HIGH

Assess WM usage in Phase 1. If extensive, plan dedicated EWM workstream.

R4

ACDOCA performance on high-volume FI data

Medium

High

HIGH

Archiving strategy before migration. Performance test with production-scale data.

R5

Interface partners unable to adapt in time

Medium

High

HIGH

Notify partners in Phase 1. Provide test environments early. Use compatibility adapters.

R6

User adoption resistance (GUI → Fiori)

Medium

Medium

MEDIUM

Early Fiori demos in Phase 2. Super-user program. Role-based training with hands-on labs.

R7

Co-PA migration to account-based only

Low

High

MEDIUM

Assess current CO-PA usage. Map characteristics to ACDOCA fields in Phase 2.

R8

Cutover window exceeded

Low

Critical

MEDIUM

2 cutover rehearsals. Clear rollback criteria. Parallel run option as safety net.

Acceleration

⚡ C16 Migration Accelerator

What C16 can automate once connected to ABB's ECC system — turning weeks of manual work into hours.

📊

#### Auto-Classify All Z/Y Objects

Scan 5,000–30,000 custom objects. Assign Clean Core level (A/B/C/D) and disposition (5 Rs) automatically.

Manual: 4-8 weeks → C16: 4-8 hours

🔍

#### Per-Program Deep Analysis

For each program: architecture, tables, dependencies, duplication, auth gaps, performance anti-patterns, CDS replacements.

Manual: 2-4 hours each → C16: 2-3 minutes each

🎯

#### Fit-to-Standard Mapping

Decompose each program into requirements, map to Fiori apps and Released APIs, calculate coverage %, recommend disposition.

Manual: 1-2 days each → C16: 5-10 minutes each

🛡️

#### Simplification List Check

Cross-reference every custom object against SAP Note 2313884. Flag breaking changes per program.

Manual: tedious lookup → C16: automated per object

✍️

#### Remediation Code Generation

Generate Clean Core ABAP — CDS views, RAP BOs, Fiori Elements apps — to replace legacy Level C/D code.

Manual: days per program → C16: hours per program

📄

#### SmartForm → Adobe Conversion

Automated conversion pipeline: download SmartForm XML → parse → generate XDP → deploy Adobe Form.

Manual: 1-2 days each → C16: 5-10 minutes each

**🎯 Bottom Line:** Connecting C16 to ABB's ECC can compress Phase 1 (Discovery) from **6 weeks to ~1 week** and Phase 2 (Assessment) from **8 weeks to ~2-3 weeks**. This alone saves **~2-3 months** from the overall timeline.

Appendix A

Table Migration Reference

Key ECC tables and their S/4HANA replacements. Critical for custom code remediation.

ECC Table

Description

S/4HANA Table/View

Released CDS View

Impact

LFA1

Vendor Master (General)

BUT000 (via BP)

I\_Supplier

CRITICAL

LFB1

Vendor Master (Company)

BUT000 + role

I\_SupplierCompany

CRITICAL

KNA1

Customer Master (General)

BUT000 (via BP)

I\_Customer

CRITICAL

KNB1

Customer Master (Company)

BUT000 + role

I\_CustomerCompany

CRITICAL

BSEG

Accounting Doc Segment

ACDOCA (reporting)

I\_JournalEntry

HIGH

BSIS/BSAS

GL Line Items

ACDOCA

I\_GLAccountLineItem

HIGH

BSIK/BSAK

Vendor Line Items

ACDOCA

I\_OperationalAcctgDocItem

HIGH

BSID/BSAD

Customer Line Items

ACDOCA

I\_OperationalAcctgDocItem

HIGH

MSEG

Material Doc Segment

MATDOC

I\_MaterialDocumentItem

HIGH

MKPF

Material Doc Header

MATDOC

I\_MaterialDocumentHeader

HIGH

KONV

Pricing Conditions

PRCD\_ELEMENTS

I\_PricingElement

HIGH

MARA

Material Master (General)

MARA (kept)

I\_Product

MEDIUM

EKKO

PO Header

EKKO (kept)

I\_PurchaseOrder

MEDIUM

VBAK

Sales Order Header

VBAK (kept)

I\_SalesOrder

MEDIUM

**💡 Rule of Thumb:** Tables marked **CRITICAL** are structurally replaced — any SELECT on the old table may fail or return wrong data. Tables marked **HIGH** have new combined tables but compatibility views exist. Tables marked **MEDIUM** are kept but should use CDS views for Clean Core compliance.

Next Steps

Immediate Actions — Week 1

Start the migration journey with these 5 concrete actions.

1 🔌

#### Connect C16 to ABB's ECC

Provide RFC + ADT access. C16 auto-classifies the entire landscape in hours, not weeks.

2 📊

#### Run SAP Readiness Check

Available via SAP Launchpad (free). First-cut compatibility report against S/4HANA 2025.

3 📋

#### Export ST03N Usage Data

Identify which of ABB's custom programs are actually used. Dead code = instant retirement.

4 👥

#### Nominate Process Owners

One owner per module for Fit-to-Standard workshops. They approve every disposition decision.

5 🎯

#### Decide Migration Approach

Greenfield, Brownfield, or Bluefield? This shapes everything downstream.

Ready to Turn This Playbook Into a Precision Execution Plan?

Connect C16 to ABB's ECC system, and every estimate becomes a verified number. Every disposition becomes a data-backed decision. Every remediation comes with generated code.

21 Plays 4 Decision Gates 8 Test Layers 5 Rs Framework Clean Core Level A Target

Generated by C16 · April 2026 · Migration Playbook v2.0

← Previous

1 / 17

Next →

// ── Slide Engine ── const slides = document.querySelectorAll('.slide'); const totalSlides = slides.length; let currentSlide = 0; // Build nav dots const dotsContainer = document.getElementById('navDots'); for (let i = 0; i < totalSlides; i++) { const dot = document.createElement('button'); dot.className = 'nav-dot' + (i === 0 ? ' active' : ''); dot.onclick = () => goToSlide(i); dot.title = 'Slide ' + (i + 1); dotsContainer.appendChild(dot); } function goToSlide(index) { if (index < 0 || index >= totalSlides || index === currentSlide) return; const oldSlide = slides\[currentSlide\]; const newSlide = slides\[index\]; // Direction const direction = index > currentSlide ? 1 : -1; // Remove old oldSlide.classList.remove('active'); oldSlide.classList.add(direction > 0 ? 'exit-left' : ''); setTimeout(() => { oldSlide.classList.remove('exit-left'); oldSlide.style.transform = direction > 0 ? 'translateX(60px)' : 'translateX(-60px)'; }, 500); // Show new newSlide.style.transform = direction > 0 ? 'translateX(60px)' : 'translateX(-60px)'; newSlide.classList.add('active'); newSlide.scrollTop = 0; // Update dots document.querySelectorAll('.nav-dot').forEach((d, i) => { d.classList.toggle('active', i === index); }); // Update counter document.getElementById('slideCounter').textContent = (index + 1) + ' / ' + totalSlides; // Update buttons document.getElementById('prevBtn').disabled = (index === 0); document.getElementById('nextBtn').disabled = (index === totalSlides - 1); currentSlide = index; } function navigate(dir) { goToSlide(currentSlide + dir); } // Keyboard navigation document.addEventListener('keydown', (e) => { if (e.key === 'ArrowRight' || e.key === 'ArrowDown') { e.preventDefault(); navigate(1); } if (e.key === 'ArrowLeft' || e.key === 'ArrowUp') { e.preventDefault(); navigate(-1); } if (e.key === 'Home') { e.preventDefault(); goToSlide(0); } if (e.key === 'End') { e.preventDefault(); goToSlide(totalSlides - 1); } }); // Touch/swipe support let touchStartX = 0; let touchStartY = 0; document.addEventListener('touchstart', (e) => { touchStartX = e.changedTouches\[0\].screenX; touchStartY = e.changedTouches\[0\].screenY; }, { passive: true }); document.addEventListener('touchend', (e) => { const dx = e.changedTouches\[0\].screenX - touchStartX; const dy = e.changedTouches\[0\].screenY - touchStartY; if (Math.abs(dx) > Math.abs(dy) && Math.abs(dx) > 50) { navigate(dx < 0 ? 1 : -1); } }, { passive: true }); // Init document.getElementById('prevBtn').disabled = true;