  C16 Demo Prompt Library \* { margin: 0; padding: 0; box-sizing: border-box; } body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); min-height: 100vh; padding: 20px; } .container { max-width: 1400px; margin: 0 auto; background: white; border-radius: 15px; box-shadow: 0 20px 40px rgba(0,0,0,0.1); overflow: hidden; } .header { background: linear-gradient(135deg, #C97B3A, #B5567A, #6B3FA0); color: white; padding: 30px; text-align: center; } .header h1 { font-size: 2.5em; margin-bottom: 10px; font-weight: 300; } .header p { font-size: 1.2em; opacity: 0.9; } .search-bar { padding: 20px; background: #f8f9fa; border-bottom: 1px solid #e9ecef; } .search-input { width: 100%; padding: 15px; border: 2px solid #ddd; border-radius: 8px; font-size: 16px; transition: border-color 0.3s; } .search-input:focus { outline: none; border-color: #6B3FA0; } .filters { padding: 20px; background: #f1f3f4; display: flex; gap: 15px; flex-wrap: wrap; align-items: center; } .filter-group { display: flex; align-items: center; gap: 10px; } .filter-select { padding: 8px 12px; border: 1px solid #ddd; border-radius: 5px; background: white; } .content { padding: 30px; } .prompt-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(400px, 1fr)); gap: 25px; } .prompt-card { border: 1px solid #e9ecef; border-radius: 12px; overflow: hidden; transition: transform 0.3s, box-shadow 0.3s; background: white; } .prompt-card:hover { transform: translateY(-5px); box-shadow: 0 10px 25px rgba(0,0,0,0.1); } .card-header { padding: 20px; background: linear-gradient(135deg, #f8f9fa, #e9ecef); border-bottom: 1px solid #dee2e6; } .card-title { font-size: 1.3em; font-weight: 600; color: #2c3e50; margin-bottom: 8px; } .card-meta { display: flex; gap: 10px; margin-bottom: 10px; } .badge { padding: 4px 12px; border-radius: 20px; font-size: 0.85em; font-weight: 500; } .badge-industry { background: #e3f2fd; color: #1976d2; } .badge-module { background: #f3e5f5; color: #7b1fa2; } .badge-complexity { background: #fff3e0; color: #f57c00; } .badge-complexity.high { background: #ffebee; color: #d32f2f; } .badge-complexity.medium { background: #fff8e1; color: #f9a825; } .badge-complexity.low { background: #e8f5e8; color: #388e3c; } .card-description { color: #6c757d; line-height: 1.5; margin-bottom: 15px; } .expected-outcomes { background: #f8f9fa; padding: 15px; border-radius: 8px; margin-bottom: 15px; } .expected-outcomes h4 { color: #495057; margin-bottom: 8px; font-size: 0.95em; } .expected-outcomes ul { list-style: none; padding-left: 0; } .expected-outcomes li { padding: 3px 0; color: #6c757d; font-size: 0.9em; } .expected-outcomes li:before { content: "✓ "; color: #28a745; font-weight: bold; } .card-body { padding: 20px; } .prompt-text { background: #f8f9fa; border: 1px solid #e9ecef; border-radius: 8px; padding: 15px; font-family: 'Courier New', monospace; font-size: 0.9em; line-height: 1.4; color: #495057; white-space: pre-wrap; max-height: 200px; overflow-y: auto; margin-bottom: 15px; } .card-actions { display: flex; gap: 10px; justify-content: flex-end; } .btn { padding: 10px 20px; border: none; border-radius: 6px; cursor: pointer; font-size: 0.9em; font-weight: 500; transition: all 0.3s; text-decoration: none; display: inline-block; text-align: center; } .btn-primary { background: #6B3FA0; color: white; } .btn-primary:hover { background: #5a2d85; transform: translateY(-2px); } .btn-secondary { background: #6c757d; color: white; } .btn-secondary:hover { background: #545b62; } .copy-notification { position: fixed; top: 20px; right: 20px; background: #28a745; color: white; padding: 15px 25px; border-radius: 8px; box-shadow: 0 5px 15px rgba(0,0,0,0.2); transform: translateX(400px); transition: transform 0.3s; z-index: 1000; } .copy-notification.show { transform: translateX(0); } .stats-bar { background: #e9ecef; padding: 15px 30px; display: flex; justify-content: space-between; align-items: center; font-size: 0.9em; color: #6c757d; } .hidden { display: none; } @media (max-width: 768px) { .prompt-grid { grid-template-columns: 1fr; } .filters { flex-direction: column; align-items: stretch; } .filter-group { justify-content: space-between; } }

# 🚀 C16 Demo Prompt Library

Ready-to-use prompts for live SAP demonstrations

Industry: All Industries Manufacturing Pharmaceutical Retail Automotive Oil & Gas Banking Utilities Generic

SAP Module: All Modules MM (Materials) SD (Sales) FI (Finance) CO (Controlling) PP (Production) WM (Warehouse) HR (Human Resources) Cross-Module

Complexity: All Levels Low (Quick Demo) Medium (Standard Demo) High (Deep Dive)

12 prompts available Last updated: April 2026

Vendor Master Data Quality Analysis

Manufacturing MM Medium

Comprehensive analysis of vendor master data quality issues including blocked vendors, missing payment terms, and incomplete address data.

#### Expected Analysis Results:

*   Blocked vendor count and reasons
*   Missing payment terms analysis
*   Address completeness assessment
*   Bank details validation
*   Compliance gap identification

I need a comprehensive vendor master data quality analysis for our procurement operations. Please investigate: 1. Blocked vendors and blocking reasons 2. Vendors with missing or incomplete payment terms 3. Address data completeness (street, city, postal code, country) 4. Missing bank account details for payment processing 5. Tax registration numbers and compliance data 6. Vendor classification and purchasing organization assignments Focus on data quality issues that impact procurement efficiency and compliance. Provide specific counts, examples, and remediation recommendations.

Copy Prompt

Purchase Order Cycle Time Analysis

Generic MM High

Deep dive into P2P process performance with cycle time analysis, bottleneck identification, and process mining insights.

#### Expected Analysis Results:

*   PR to PO conversion times
*   PO approval cycle analysis
*   Goods receipt delays
*   Invoice processing bottlenecks
*   Process variant analysis
*   Performance benchmarking

Analyze our complete Procure-to-Pay cycle performance and identify process bottlenecks: 1. Purchase Requisition to Purchase Order conversion times 2. PO approval workflow delays and stuck documents 3. Goods Receipt processing efficiency 4. Invoice-to-Payment cycle times 5. Three-way matching exceptions and resolution times 6. Vendor performance impact on cycle times 7. Seasonal patterns and volume impact analysis Generate a process mining report with cycle time distributions, bottleneck analysis, and specific recommendations for process optimization. Include comparative analysis across different purchasing groups and document types.

Copy Prompt

Sales Order Processing Diagnostic

Retail SD Medium

Order-to-Cash process analysis focusing on blocked orders, delivery delays, and billing issues.

#### Expected Analysis Results:

*   Blocked sales orders analysis
*   Credit hold impact assessment
*   Delivery performance metrics
*   Billing document status
*   Customer payment behavior

Perform a comprehensive Order-to-Cash process diagnostic: 1. Sales orders with delivery blocks and credit holds 2. Incomplete delivery analysis and backorder situations 3. Billing document processing delays and errors 4. Customer payment behavior and overdue analysis 5. Return order processing efficiency 6. Pricing condition issues and manual price changes 7. ATP (Available-to-Promise) check failures Provide insights into process efficiency, customer satisfaction impact, and revenue recognition delays. Include recommendations for improving order fulfillment rates and reducing cycle times.

Copy Prompt

Financial Close Process Analysis

Banking FI High

Month-end close process efficiency analysis with focus on manual adjustments, reconciliation delays, and reporting accuracy.

#### Expected Analysis Results:

*   Close timeline analysis
*   Manual journal entry patterns
*   Reconciliation bottlenecks
*   Intercompany clearing issues
*   Reporting accuracy metrics

Analyze our financial close process efficiency and identify automation opportunities: 1. Month-end close timeline analysis and critical path identification 2. Manual journal entries and recurring adjustments patterns 3. Account reconciliation delays and unreconciled items 4. Intercompany transactions and clearing issues 5. Foreign currency revaluation processing 6. Accrual and deferral posting accuracy 7. Financial reporting preparation bottlenecks Focus on process standardization opportunities, automation potential, and controls effectiveness. Provide specific recommendations for reducing close cycle time while maintaining accuracy and compliance.

Copy Prompt

Inventory Management Optimization

Manufacturing WM Medium

Warehouse and inventory optimization analysis including stock levels, movement patterns, and storage efficiency.

#### Expected Analysis Results:

*   Slow-moving inventory identification
*   Stock level optimization
*   Warehouse utilization analysis
*   Movement pattern insights
*   ABC classification review

Conduct a comprehensive inventory management analysis to optimize stock levels and warehouse operations: 1. Slow-moving and obsolete inventory identification 2. Stock level analysis against consumption patterns 3. Warehouse space utilization and storage bin optimization 4. Material movement frequency and picking efficiency 5. ABC classification accuracy and rebalancing needs 6. Safety stock levels vs actual demand variability 7. Inventory turnover ratios by material group and plant Provide actionable insights for reducing carrying costs, improving service levels, and optimizing warehouse layout. Include recommendations for inventory policy adjustments and process improvements.

Copy Prompt

Production Planning Efficiency Analysis

Automotive PP High

Manufacturing execution analysis focusing on production order efficiency, capacity utilization, and material availability.

#### Expected Analysis Results:

*   Production order status analysis
*   Capacity utilization metrics
*   Material shortage impact
*   Setup time optimization
*   Quality issue patterns

Analyze production planning and execution efficiency across our manufacturing operations: 1. Production order status and completion rate analysis 2. Work center capacity utilization and bottleneck identification 3. Material availability issues causing production delays 4. Setup and changeover time impact on efficiency 5. Quality inspection results and rework patterns 6. Planned vs actual production quantities and timing 7. Resource allocation effectiveness across production lines Generate insights into manufacturing performance, identify improvement opportunities, and provide recommendations for optimizing production schedules, reducing waste, and improving overall equipment effectiveness (OEE).

Copy Prompt

Custom Code Clean Core Assessment

Generic Cross-Module High

Comprehensive analysis of custom ABAP programs for S/4HANA readiness and Clean Core compliance.

#### Expected Analysis Results:

*   Clean Core compliance score
*   S/4HANA migration readiness
*   API replacement recommendations
*   Code quality assessment
*   Remediation roadmap

Analyze Z\_VENDOR\_CONSOLIDATED\_REPORT for Clean Core compliance and S/4HANA readiness: This is a comprehensive vendor reporting program that consolidates data from multiple sources. Please provide: 1. Clean Core compliance assessment with detailed scoring 2. Identification of non-compliant APIs and table accesses 3. S/4HANA migration impact analysis 4. Performance optimization opportunities 5. Standard SAP functionality that could replace custom code 6. Detailed remediation roadmap with effort estimates 7. Risk assessment for cloud migration Generate a complete analysis document with findings, recommendations, and next steps for modernization.

Copy Prompt

Master Data Governance Analysis

Pharma Cross-Module Medium

Cross-module master data quality assessment focusing on materials, vendors, and customers with regulatory compliance requirements.

#### Expected Analysis Results:

*   Data quality scorecards
*   Duplicate record identification
*   Compliance gap analysis
*   Data governance maturity
*   Standardization opportunities

Conduct a comprehensive master data governance analysis across materials, vendors, and customers: 1. Material master data completeness and accuracy assessment 2. Vendor master data quality including regulatory compliance fields 3. Customer master data standardization and duplicate analysis 4. Cross-system data consistency validation 5. Data governance process effectiveness evaluation 6. Regulatory compliance data completeness (FDA, EMA requirements) 7. Data stewardship role clarity and accountability Focus on pharmaceutical industry requirements including batch management, serialization readiness, and regulatory reporting capabilities. Provide recommendations for improving data quality processes and governance frameworks.

Copy Prompt

Authorization and Security Audit

Generic Cross-Module Medium

Security assessment focusing on user access rights, segregation of duties, and authorization object usage.

#### Expected Analysis Results:

*   Excessive privilege identification
*   SoD conflict detection
*   Unused authorization analysis
*   Critical access monitoring
*   Compliance gap assessment

Perform a comprehensive authorization and security audit of our SAP system: 1. User access rights analysis and excessive privilege identification 2. Segregation of duties (SoD) conflict detection and resolution 3. Critical authorization object usage and monitoring 4. Inactive user account cleanup opportunities 5. Role design effectiveness and optimization potential 6. Emergency access usage and approval workflow compliance 7. Custom transaction and program authorization gaps Provide insights into security posture, compliance with internal policies and external regulations (SOX, GDPR), and recommendations for improving access governance while maintaining operational efficiency.

Copy Prompt

Integration Landscape Assessment

Oil & Gas Cross-Module High

Complex integration analysis covering RFC connections, IDoc processing, and API usage patterns across the enterprise landscape.

#### Expected Analysis Results:

*   Integration point inventory
*   Performance bottleneck analysis
*   Error pattern identification
*   Modernization opportunities
*   API strategy recommendations

Analyze our complete integration landscape and identify modernization opportunities: 1. RFC connection usage patterns and performance analysis 2. IDoc processing efficiency and error handling effectiveness 3. Web service and API consumption patterns 4. Batch job dependencies and scheduling optimization 5. Real-time vs batch integration trade-offs 6. Integration monitoring and alerting effectiveness 7. Cloud integration readiness assessment Focus on identifying integration bottlenecks, single points of failure, and opportunities to modernize legacy interfaces with cloud-native APIs. Provide recommendations for improving integration reliability, performance, and maintainability.

Copy Prompt

System Performance Optimization

Utilities Cross-Module High

Comprehensive performance analysis including database optimization, custom code efficiency, and system resource utilization.

#### Expected Analysis Results:

*   Performance bottleneck identification
*   Database optimization opportunities
*   Custom code efficiency analysis
*   Resource utilization patterns
*   Optimization roadmap

Conduct a comprehensive system performance analysis and optimization assessment: 1. Database query performance analysis and optimization opportunities 2. Custom ABAP code efficiency review and improvement potential 3. System resource utilization patterns and capacity planning 4. Batch job performance and scheduling optimization 5. Memory consumption analysis and garbage collection patterns 6. Network latency impact on user experience 7. Archive and data retention strategy effectiveness Generate actionable recommendations for improving system performance, reducing response times, and optimizing resource utilization. Include both quick wins and strategic improvements with effort estimates and expected performance gains.

Copy Prompt

Quick Demo: Vendor Payment Analysis

Generic FI Low

Fast 5-minute demo showing vendor payment behavior analysis with immediate insights.

#### Expected Analysis Results:

*   Overdue payment summary
*   Payment term compliance
*   Cash flow impact analysis
*   Vendor relationship insights

Quick vendor payment analysis for immediate insights: 1. Overdue vendor payments and aging analysis 2. Payment term compliance and early payment discount utilization 3. Vendor payment behavior patterns and trends 4. Cash flow impact of payment timing optimization 5. Top vendors by payment volume and frequency Provide a concise summary with key metrics and actionable insights that can be presented in under 5 minutes. Focus on immediate business value and decision-making support.

Copy Prompt

✅ Prompt copied to clipboard!

// Search and filter functionality const searchInput = document.getElementById('searchInput'); const industryFilter = document.getElementById('industryFilter'); const moduleFilter = document.getElementById('moduleFilter'); const complexityFilter = document.getElementById('complexityFilter'); const promptGrid = document.getElementById('promptGrid'); const promptCount = document.getElementById('promptCount'); const copyNotification = document.getElementById('copyNotification'); function filterPrompts() { const searchTerm = searchInput.value.toLowerCase(); const industryValue = industryFilter.value; const moduleValue = moduleFilter.value; const complexityValue = complexityFilter.value; const cards = promptGrid.querySelectorAll('.prompt-card'); let visibleCount = 0; cards.forEach(card => { const title = card.querySelector('.card-title').textContent.toLowerCase(); const description = card.querySelector('.card-description').textContent.toLowerCase(); const industry = card.dataset.industry; const module = card.dataset.module; const complexity = card.dataset.complexity; const matchesSearch = searchTerm === '' || title.includes(searchTerm) || description.includes(searchTerm); const matchesIndustry = industryValue === '' || industry === industryValue; const matchesModule = moduleValue === '' || module === moduleValue; const matchesComplexity = complexityValue === '' || complexity === complexityValue; if (matchesSearch && matchesIndustry && matchesModule && matchesComplexity) { card.style.display = 'block'; visibleCount++; } else { card.style.display = 'none'; } }); promptCount.textContent = \`${visibleCount} prompts available\`; } // Copy prompt functionality function copyPrompt(button) { const promptText = button.closest('.prompt-card').querySelector('.prompt-text').textContent; navigator.clipboard.writeText(promptText).then(() => { // Show notification copyNotification.classList.add('show'); // Hide notification after 3 seconds setTimeout(() => { copyNotification.classList.remove('show'); }, 3000); // Update button temporarily const originalText = button.textContent; button.textContent = 'Copied!'; button.style.background = '#28a745'; setTimeout(() => { button.textContent = originalText; button.style.background = '#6B3FA0'; }, 2000); }).catch(err => { console.error('Failed to copy text: ', err); alert('Failed to copy prompt. Please select and copy manually.'); }); } // Event listeners searchInput.addEventListener('input', filterPrompts); industryFilter.addEventListener('change', filterPrompts); moduleFilter.addEventListener('change', filterPrompts); complexityFilter.addEventListener('change', filterPrompts); // Initialize filterPrompts(); // Keyboard shortcuts document.addEventListener('keydown', (e) => { if (e.ctrlKey && e.key === 'f') { e.preventDefault(); searchInput.focus(); } });