  VA01 Custom Objects - Visual Guide \* { margin: 0; padding: 0; box-sizing: border-box; } body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: #333; line-height: 1.6; min-height: 100vh; } .container { max-width: 1200px; margin: 0 auto; padding: 20px; } .header { text-align: center; background: rgba(255, 255, 255, 0.95); border-radius: 20px; padding: 40px; margin-bottom: 30px; box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1); } .header h1 { font-size: 2.5em; color: #2c3e50; margin-bottom: 10px; font-weight: 700; } .header .subtitle { font-size: 1.2em; color: #7f8c8d; margin-bottom: 20px; } .transaction-badge { display: inline-block; background: linear-gradient(45deg, #3498db, #2980b9); color: white; padding: 10px 25px; border-radius: 25px; font-weight: bold; font-size: 1.1em; box-shadow: 0 5px 15px rgba(52, 152, 219, 0.3); } .stats-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin-bottom: 40px; } .stat-card { background: rgba(255, 255, 255, 0.95); border-radius: 15px; padding: 25px; text-align: center; box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1); transition: transform 0.3s ease; } .stat-card:hover { transform: translateY(-5px); } .stat-number { font-size: 2.5em; font-weight: bold; color: #e74c3c; margin-bottom: 10px; } .stat-label { font-size: 1.1em; color: #34495e; font-weight: 600; } .objects-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 25px; margin-bottom: 40px; } .object-category { background: rgba(255, 255, 255, 0.95); border-radius: 15px; padding: 25px; box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1); } .category-header { display: flex; align-items: center; margin-bottom: 20px; padding-bottom: 15px; border-bottom: 2px solid #ecf0f1; } .category-icon { font-size: 2em; margin-right: 15px; } .category-title { font-size: 1.4em; font-weight: bold; color: #2c3e50; } .object-list { list-style: none; } .object-item { background: #f8f9fa; margin-bottom: 12px; padding: 15px; border-radius: 10px; border-left: 4px solid #3498db; transition: all 0.3s ease; } .object-item:hover { background: #e3f2fd; border-left-color: #2196f3; } .object-name { font-weight: bold; color: #2c3e50; font-size: 1.1em; } .object-package { color: #7f8c8d; font-size: 0.9em; margin-top: 5px; } .object-description { color: #555; font-size: 0.95em; margin-top: 5px; } .enhancement-flow { background: rgba(255, 255, 255, 0.95); border-radius: 15px; padding: 30px; margin-bottom: 30px; box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1); } .flow-title { text-align: center; font-size: 1.8em; color: #2c3e50; margin-bottom: 30px; font-weight: bold; } .flow-diagram { display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 20px; } .flow-step { flex: 1; min-width: 200px; text-align: center; position: relative; } .flow-step:not(:last-child)::after { content: '→'; position: absolute; right: -30px; top: 50%; transform: translateY(-50%); font-size: 2em; color: #3498db; font-weight: bold; } .flow-box { background: linear-gradient(45deg, #74b9ff, #0984e3); color: white; padding: 20px; border-radius: 15px; box-shadow: 0 5px 15px rgba(116, 185, 255, 0.3); } .flow-step-title { font-weight: bold; font-size: 1.1em; margin-bottom: 8px; } .flow-step-desc { font-size: 0.9em; opacity: 0.9; } .recommendations { background: rgba(255, 255, 255, 0.95); border-radius: 15px; padding: 30px; box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1); } .recommendations h2 { color: #2c3e50; margin-bottom: 20px; font-size: 1.6em; text-align: center; } .rec-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; } .rec-item { background: #f8f9fa; padding: 20px; border-radius: 10px; border-left: 4px solid #e74c3c; } .rec-title { font-weight: bold; color: #2c3e50; margin-bottom: 10px; } .rec-desc { color: #555; font-size: 0.95em; } .footer { text-align: center; margin-top: 40px; padding: 20px; background: rgba(255, 255, 255, 0.1); border-radius: 15px; color: white; } @media (max-width: 768px) { .flow-step:not(:last-child)::after { content: '↓'; right: 50%; top: 100%; transform: translateX(50%); } .flow-diagram { flex-direction: column; } } .legend { background: rgba(255, 255, 255, 0.95); border-radius: 15px; padding: 25px; margin-bottom: 30px; box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1); } .legend h3 { color: #2c3e50; margin-bottom: 15px; text-align: center; } .legend-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; } .legend-item { display: flex; align-items: center; padding: 10px; background: #f8f9fa; border-radius: 8px; } .legend-color { width: 20px; height: 20px; border-radius: 50%; margin-right: 10px; } .color-enhancement { background: #3498db; } .color-badi { background: #e74c3c; } .color-exit { background: #f39c12; } .color-custom { background: #27ae60; }

# 🛒 VA01 Custom Objects

Visual Guide to Sales Order Creation Customizations

Transaction: VA01 - Create Sales Order

4

Enhancement Implementations

5

Available User Exits

2

Standard BAdIs

3

Main Packages

### 🎨 Object Type Legend

Enhancement Implementations

BAdI Definitions

User Exits

Custom Programs

🔧

Enhancement Implementations

*   ZBADI\_SLS\_HEAD\_CUS
    
    Package: ZPKG\_PROGRAMS\_09
    
    Sales order header customization
    
*   ZBADI\_SLS\_HEAD\_SCR\_CUS2
    
    Package: ZPKG\_PROGRAMS\_09
    
    Sales order header screen customization
    
*   ZCHECK\_NETPRICE\_HEADER
    
    Package: ZDEVELOPER25
    
    Net price validation at header level
    
*   ZEHPRC\_SALES\_ORDER
    
    Package: ZEHSM\_PRC
    
    Sales order pricing enhancement
    

🚪

Available User Exits

*   EXIT\_SAPMV45A\_001
    
    Customer enhancement for sales document header
    
*   EXIT\_SAPMV45A\_002
    
    Customer enhancement for sales document items
    
*   EXIT\_SAPMV45A\_003
    
    Customer enhancement for schedule lines
    
*   EXIT\_SAPMV45A\_004
    
    Customer enhancement for partners
    
*   EXIT\_SAPMV45A\_005
    
    Customer enhancement for texts
    

🔌

Standard BAdIs

*   BADI\_SD\_SCH\_GETWAGFZ
    
    Scheduling agreement delivery schedule
    
*   BADI\_SD\_V46H0001
    
    Sales document processing
    

📦

Package Distribution

*   ZPKG\_PROGRAMS\_09
    
    Main sales customization package (2 objects)
    
*   ZDEVELOPER25
    
    Validation and checking logic (1 object)
    
*   ZEHSM\_PRC
    
    Specialized pricing package (1 object)
    

🔄 VA01 Enhancement Flow

User Input

Sales order data entry in VA01

Header Validation

ZBADI\_SLS\_HEAD\_CUS triggers

Price Check

ZCHECK\_NETPRICE\_HEADER validates

Save Order

Standard SAP processing

## 🎯 Investigation Recommendations

$TMP Package Check

Search for temporary developments that might be in active use

Workflow Customizations

Check for sales order approval workflows and custom routing

Output Determination

Investigate custom forms, output types, and print programs

Pricing Procedures

Review condition type customizations and pricing logic

Copy Control

Check document flow customizations and copy routines

Field Modifications

Look for screen modifications and field validations

📊 Generated by C16 SAP Analysis Engine | System: ECC 7.40 | Client: 800

🔍 Analysis Date: April 14, 2026 | Objects Found: Active Custom Implementations