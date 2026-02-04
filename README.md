# End-to-End Excel Analytics Project: Business Analytics + Data Analytics Reporting Pack

Comprehensive Sales, Marketing, and P&L reporting pack built in Excel, supported by Business Analysis documentation and decision-support tools. The solution standardises fragmented Excel reporting into a single reporting pack with defined KPIs, governance rules, and validation/UAT structure.

 > **Portfolio-safe note:** Customer names are anonymised in shared materials.

---

## 📈 Business Value & Impact
- **Efficiency:** manual consolidation effort by enabling a refreshable reporting workflow (Power Query), improving consistency and shortening the monthly reporting cycle.
- **Margin Protection:** Implemented a Discount Scenario Tool that prevents 3% margin leakage, and saves comprehensive decision time.
- **Strategic Alignment:** Established a unified KPI Dictionary, eliminating "data silos" between Sales and Finance.
- **Decision Support:** Provided a Priority Matrix to align IT/Ops resources with high-impact business initiatives and projects.

---

## 🛠️ Technical Methodology (The "How")
To ensure the solution is robust and scalable, I followed a professional ETL (Extract, Transform, Load) approach:

1. **Data Analysis (Power Query):** Used for automated data cleaning, merging fragmented CSV/Excel exports, and enforcing data types to ensure data integrity. Performed advanced data shaping, including unpivoting, attribute standardization, and merging multi-year datasets to establish a "Single Source of Truth."
2. **Data Modeling:** Built a star-schema-inspired model within Excel to link Sales, Targets, and P&L data efficiently with Power Pivot and DAX. _[Data Model](Data%20Model.jpg)_
3. **Decision Logic:** Built dynamic "What-If" models for discount approvals and project prioritization. _[Scenario Planning Tool for (Discount Approval)](02_Data_Analytics/07_Scenario_planning_Tool_Discouunt_approval.pdf)_
4. **Tabular Report Design:** Eschewed "flashy" visuals in favor of Executive-Standard Tabular Reports. This approach prioritizes data density, precision, and auditability that is critical for Finance and C-Suite stakeholders.

---

## 📂 Project Governance & Artifacts (BA Pack)

### [Business_Analytics](./01_Business_Analytics/)
1. Mini-BRD: Defines scope, "As-Is" vs "To-Be" states, and functional requirements. _[As_Is vs To_Be](As-Is%20vs%20To-Be%20diagram.png)_, _[Mini_BRD](01_Business_Analytics/Mini_BRD_BA.pdf)_
2. Stakeholder RACI: Ensures clear accountability across Finance, Sales, and Marketing. _[Stakeholder_RACI](01_Business_Analytics/Stakeholders_RACI.pdf)_
3. KPI DictionaryThe "Single Source of Truth" for metrics like Gross Profit, Operating Margin, and Variance. _[KPI_Dictionary](01_Business_Analytics/KPI_Dictionary_and_Business_Rules_BA.pdf)_
4. UAT & Validation: A rigorous sign-off process ensuring data accuracy and reconciliation against source systems. _[UAT_Validation](01_Business_Analytics/Validation_UAT_Signoff.pdf)_

---

## 📊 Strategic Reporting Outputs

### [Data_Analytics](./02_Data_Analytics/)
1. **Sales & Marketing Performance:** Automated Target vs Actual tracking with regional drill-downs.
*   _[Net_sales_performance](02_Data_Analytics/01_Customer_performance_Analysis.pdf)_, _[Market Performance](02_Data_Analytics/02_Market%20performance%20vs%20Target.pdf)_
  
2. **P&L Reporting Pack:** Monthly, Quarterly, and Yearly views with inter-company transfer exclusions.
*  _[P&L by Fiscal Year](02_Data_Analytics/03_P&L%20by%20Year.pdf)_, _[P&L for Markets](02_Data_Analytics/04_P&L%20for%20Markets.pdf)_, _[GM% by Quarters](02_Data_Analytics/05_GM%%20by%20Quarters.pdf)_

3. **Ad-hoc Analysis:** Supported Business Manager with an on-demand analysis to evaluate key insight and identify performance drivers, enabling rapid management decision.
* _[ad_hoc Analysis](02_Data_Analytics/06_Ad_hoc_P&L_Analysis.pdf)_
  
4. **Discount Scenario Tool:** A governance-focused tool with built-in approval tiers (10% / 20% thresholds). So, Business Manager and Finance team experienced consumption of Time and effort to aprove discount rate for customers, and I created this tool. By adding key information about customer, it shows wheter approve or not.  
* _[Scenario planning tool for discount approval](02_Data_Analytics/07_Scenario_planning_Tool_Discouunt_approval.pdf)_

6. **Project Priority Matrix:** An objective scoring system for initiative feasibility vs. business impact. To prioritize the tasks and project here I created Project Priority Matrix that shows the relationship beteen feasibility and impact.
* [Project Priority Matrix](Decision_matrix.jpg)

---

7. **🛠️ Skills & Competencies**
*  Advanced Data Modeling
*  DAX (Data Analysis Expressions)
*  ETL Automation (Power Query)
*  Financial Analytics
*  Business Intelligence Reporting
*  Requirement Gathering

---

8. **Soft Skills**
* Strategic Sparring  Partner
* Stakeholder Management (Polder Model)
* Stakeholder Management (Polder Model)
* Designing user-centric reports with empathy in mind

---

## 📩 Contact & Professional Sparring
I am a Business Analyst who speaks both "Data" and "Business." If you are looking for a sparring partner to optimize your reporting processes, let's connect.
**[https://www.linkedin.com/in/harshil-patel-188b2274/]**






