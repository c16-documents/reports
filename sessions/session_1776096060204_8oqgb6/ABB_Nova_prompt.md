  ABB ECC → S/4HANA Migration Analysis - AI Prompt body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.6; color: #2c3e50; background: #e9ecef; margin: 0; padding: 20px; } .doc-wrapper { max-width: 1120px; margin: 0 auto; background: white; border-radius: 12px; box-shadow: 0 8px 32px rgba(0,0,0,0.1); overflow: hidden; } .header-banner { background: linear-gradient(135deg, #C97B3A, #B5567A, #6B3FA0); color: white; padding: 40px; text-align: center; position: relative; } .header-banner h1 { margin: 0; font-size: 2.5em; font-weight: 700; text-shadow: 2px 2px 4px rgba(0,0,0,0.3); } .header-banner .subtitle { font-size: 1.2em; margin-top: 10px; opacity: 0.9; } .content { padding: 40px; } .section-title { color: #6B3FA0; font-size: 1.8em; font-weight: 600; margin: 30px 0 20px 0; padding-bottom: 10px; border-bottom: 3px solid #B5567A; position: relative; } .section-title::before { content: counter(section); counter-increment: section; background: #B5567A; color: white; width: 30px; height: 30px; border-radius: 50%; display: inline-flex; align-items: center; justify-content: center; font-weight: bold; margin-right: 15px; font-size: 0.8em; } body { counter-reset: section; } .prompt-box { background: #f8f9fa; border: 2px solid #6B3FA0; border-radius: 8px; padding: 25px; margin: 20px 0; font-family: 'Courier New', monospace; font-size: 0.95em; line-height: 1.5; white-space: pre-wrap; overflow-x: auto; } .highlight-box { background: linear-gradient(135deg, #f6fef9, #e8f5e8); border-left: 5px solid #27ae60; padding: 20px; margin: 20px 0; border-radius: 0 8px 8px 0; } .warning-box { background: linear-gradient(135deg, #fff5f5, #ffe8e8); border-left: 5px solid #e74c3c; padding: 20px; margin: 20px 0; border-radius: 0 8px 8px 0; } .info-box { background: linear-gradient(135deg, #f0f8ff, #e6f3ff); border-left: 5px solid #3498db; padding: 20px; margin: 20px 0; border-radius: 0 8px 8px 0; } table { width: 100%; border-collapse: collapse; margin: 20px 0; background: white; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.1); } th { background: #6B3FA0; color: white; padding: 15px; text-align: left; font-weight: 600; } td { padding: 12px 15px; border-bottom: 1px solid #eee; } tr:nth-child(even) { background: #f8fafc; } tr:hover { background: #edf2f7; } .badge { display: inline-block; padding: 4px 12px; border-radius: 20px; font-size: 0.85em; font-weight: 600; color: white; } .badge-success { background: #27ae60; } .badge-warning { background: #f39c12; } .badge-danger { background: #e74c3c; } .badge-info { background: #3498db; } ul, ol { padding-left: 25px; } li { margin: 8px 0; } .copy-button { background: #6B3FA0; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer; font-size: 0.9em; margin: 10px 0; transition: background 0.3s; } .copy-button:hover { background: #5a2d8a; } .footer { background: #2c3e50; color: white; padding: 30px; text-align: center; margin-top: 40px; } @media print { body { background: white; } .doc-wrapper { box-shadow: none; } .copy-button { display: none; } }

# ABB ECC → S/4HANA Migration Analysis

Complete AI Prompt for Migration Strategy & 6-Week POC

**Purpose:** This document contains a comprehensive AI prompt that captures all aspects of ABB's ECC to S/4HANA migration challenge, including the detailed 6-week POC plan. Copy and paste this prompt into any AI platform for complete analysis.

## Context Summary

ABB is planning to migrate from **26 ECC instances across different countries** to S/4HANA 2025. They have massive customization complexity (600+ enhancements just for sales order process as an example) and want to consolidate to ~15 instances with standardized processes. They're conducting a **6-week POC** with automated discovery tools to test methodology before scaling to all 26 countries.

## Key Challenges

Challenge

Scale

Impact

**Multiple ERP Instances**

26 countries

Each country has evolved different processes over 15+ years

**Massive Customization**

600+ enhancements for sales order alone

Estimated 100,000+ total enhancements across all processes

**Consolidation Goal**

26 → 15 instances

Need to standardize and harmonize business processes

**Clean Core Compliance**

All custom code

Must achieve Level A/B classification for S/4HANA compatibility

## Complete AI Prompt

**Instructions:** Copy the entire prompt below and paste it into any AI platform (ChatGPT, Claude, Gemini, etc.) for comprehensive analysis of ABB's migration challenge.

📋 Copy Complete Prompt

You are an expert SAP consultant analyzing ABB's ECC to S/4HANA migration. Here's the context and questions to address: BACKGROUND: - ABB has 26 ERP instances across different countries - 600+ enhancements just for sales order process (VA01/VA02/VA03) - this is one example - Total estimated 100,000+ enhancements across all processes globally - Goal: Consolidate 26 instances → 15 instances with standardized processes - Focus: Fit-to-Standard analysis and Clean Core compliance - 6-week POC planned with 2 ERP instances to test methodology before scaling to all 26 6-WEEK POC DETAILED PLAN: WEEK 1-2: ERP 1 DISCOVERY (e.g., Germany) - Connect to ERP 1 system (read-only RFC/ADT access) - Auto-scan ALL sales order customizations using automated discovery tool - Extract complete customization inventory with metadata (type, purpose, complexity, usage) - Map end-to-end sales order process flow (VA01 → delivery → billing) - Specific objects to scan: User Exits (CMOD/SMOD), BAdI implementations, Custom fields (VBAK/VBAP/VBUK/VBUP appends), Custom transactions (Z\*), Workflow customizations, Output determination (NACE), Pricing procedures (V/08, V/07), Copy controls (VTAA/VTAP), Custom reports on sales data - Success criteria: 95% of sales order enhancements discovered automatically WEEK 3-4: ERP 2 DISCOVERY & COMPARISON (e.g., India) - Connect to ERP 2 system with same discovery depth as ERP 1 - Run identical scan on ERP 2 sales order customizations - Generate side-by-side comparison matrix categorizing each customization as: \* IDENTICAL: Same enhancement in both systems \* SIMILAR: Same purpose, different implementation \* UNIQUE-ERP1: Only exists in country 1 \* UNIQUE-ERP2: Only exists in country 2 \* CONFLICTING: Different approaches to same business need - Success criteria: 60% of customizations can be harmonized between countries WEEK 5-6: ANALYSIS & TEMPLATE DESIGN - Categorize each customization using 5 Rs framework: \* RETIRE: Replaceable by standard S/4HANA functionality \* REPLACE: Use standard Fiori apps/processes \* REFIT: Standard covers 70%+, needs minor extension \* REWRITE: Keep custom but make Clean Core compliant \* RETAIN: Keep as-is (already compliant) - Design unified 2-country template covering 80% of both countries' needs - Estimate S/4HANA standard functionality coverage (target: 40% can be retired) - Create scaling estimates for effort/timeline/cost to apply to remaining 24 countries - Success criteria: Single template satisfies 80% of both countries' requirements POC SUCCESS METRICS: - Discovery Completeness: 95% of sales order customizations found automatically - Harmonization Potential: 60% can be standardized between 2 countries - Standard Coverage: 40% replaceable by S/4HANA standard functionality - Template Viability: 80% of both countries' needs met by single template - Scaling Confidence: Clear methodology to apply to remaining 24 countries POC SCOPE BOUNDARIES: IN SCOPE: - Sales Order process only (VA01, VA02, VA03 + related: VL01N delivery creation, VF01 billing) - 2 ERP instances only (representative countries) - Customization discovery & comparison (not actual remediation) - Template design for 2 countries (not full global template) - Effort estimation for scale-up (not detailed 26-country project plan) OUT OF SCOPE: - All other processes (MM, FI, PP, PM, HR, WM) - Remaining 24 ERP instances - Actual code remediation/migration - Full global template design - Detailed implementation project plan SPECIFIC QUESTIONS TO ANALYZE: 1. MIGRATION STRATEGY: - How to create a universal ECC → S/4HANA migration playbook that works for 3 scenarios: (A) Connected to ECC, (B) Connected to S/4HANA post-migration, (C) Offline with customer-provided data - What are the 4 phases: DISCOVER → ASSESS → REMEDIATE → MIGRATE - How to handle both on-premise S/4HANA and RISE with SAP (cloud) scenarios 2. AUTOMATED DISCOVERY DEPTH: - Beyond the obvious 9 categories listed in POC plan, what other objects need scanning? - How to discover: Custom Z-tables, Custom classes/function modules, Interface objects (IDocs, RFCs, OData), Authorization customizations, Configuration dependencies, Reporting ecosystem - How to map complete dependency trees and usage patterns 3. PRICING PROCEDURE CONSOLIDATION EXAMPLE: - Current state: Multiple country-specific procedures (ZGER01, ZIND01, ZBRA01, ZUSA01, ZCHN01) - Each has different EDI1 early payment discount logic: Germany 5%, India 3%, Brazil 2%, USA 4%, China 1% - How to consolidate into 1 global procedure (ZGLOBAL01) using enhanced access sequences? - How to replace hardcoded logic with condition records (VK11) for business user maintenance? 4. CODE vs CONFIG OPPORTUNITIES: - How to identify custom ABAP code replaceable by S/4HANA standard configuration? - Examples: Custom pricing logic → Advanced Pricing, Custom credit checks → SAP Credit Management, Custom output determination → Output Management + BRF+ - Pattern recognition for hardcoded business rules that can become configuration 5. FORMS MIGRATION COMPLEXITY: - Current: NACE-configured SmartForms/Adobe Forms with high complexity (200+ fields, 8 pages, 15 variants, multiple languages) - Migration paths: (A) Document Management, (B) Adobe Forms migration, (C) Fragmented forms architecture - Development effort estimates for each approach - How much manual effort vs automated conversion possible? 6. CHANNEL CONSISTENCY POST-OPTIMIZATION: - Will optimized solution work consistently across VA01 (manual), IDoc (EDI), and OData API (digital) channels? - How to ensure same pricing, validation, output, workflow regardless of entry channel? - Unified architecture design for all three channels 7. CLEAN CORE CLASSIFICATION: - How to classify custom objects as Level A (cloud-ready), B (classic API), C (non-compliant), D (critical)? - Different requirements: on-premise (Level B acceptable) vs RISE cloud (Level A mandatory) - What percentage of current customizations likely fall into each level? 8. POC VALIDATION APPROACH: - How to verify the 6-week POC methodology is sound? - What could go wrong and how to mitigate risks? - How to ensure 2 selected countries are representative of the other 24? - Go/No-Go decision criteria for proceeding with full program DELIVERABLES REQUESTED: - Comprehensive 6-week POC execution plan with daily/weekly activities - Technical approach for automated discovery and comparison - Consolidation strategies (pricing procedures, forms, business logic) - Effort estimates for different migration paths (on-premise vs cloud) - Success criteria, risk assessment, and scaling methodology - Template for applying POC learnings to remaining 24 countries Please provide detailed analysis addressing all these aspects with specific recommendations, effort estimates, implementation approaches, and a clear roadmap from POC to full program execution.

## Key Questions Summary

Category

Core Questions

Scale & Complexity

How to handle 26 ERP instances with 100,000+ total enhancements?

Discovery Methodology

What objects to scan beyond the obvious 9 categories?

Consolidation Strategy

How to merge 26 country-specific processes into 15 standardized ones?

Pricing Rationalization

How to consolidate 5+ pricing procedures into 1 global procedure?

Code vs Config

How to identify custom code replaceable by S/4HANA standard config?

Forms Migration

What's the effort for complex SmartForm → modern forms conversion?

Channel Unification

How to ensure VA01, IDoc, and OData work consistently post-optimization?

POC Scope

Should 6-week POC focus only on sales order process?

Clean Core Strategy

How do requirements differ for on-premise vs RISE cloud?

Automation Potential

What can be automated vs requires manual effort?

## Expected AI Response Structure

Any AI platform should address:

1.  **Strategic Framework** (4-phase migration approach)
2.  **Technical Deep-Dives** (pricing consolidation, forms migration, discovery methodology)
3.  **Effort Estimates** (weeks/hours for different approaches)
4.  **Risk Assessment** (what could go wrong, mitigation strategies)
5.  **Success Criteria** (measurable outcomes for POC and full program)
6.  **Scaling Strategy** (how to apply POC learnings to full 26-country program)

**Note:** This prompt captures all the complexity and nuance of ABB's migration challenge. It should generate comprehensive analysis from any capable AI platform, providing detailed recommendations for both the 6-week POC and the full migration program.

**ABB ECC → S/4HANA Migration Analysis Prompt**

Complete prompt for AI-powered migration strategy and POC planning

function copyPrompt() { const promptText = document.getElementById('aiPrompt').textContent; navigator.clipboard.writeText(promptText).then(function() { const button = document.querySelector('.copy-button'); const originalText = button.textContent; button.textContent = '✅ Copied!'; button.style.background = '#27ae60'; setTimeout(function() { button.textContent = originalText; button.style.background = '#6B3FA0'; }, 2000); }).catch(function(err) { console.error('Could not copy text: ', err); alert('Copy failed. Please select and copy the text manually.'); }); }