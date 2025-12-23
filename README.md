# Predictive Analysis of Operational QSR
Project Title:
Predictive Analysis of Operational Performance and Customer Satisfaction in a Quick Service Restaurant

Link notion page:
[(English version)](https://www.notion.so/ekapujiwara/Predictive-Analysis-of-Operational-QSR-2cdc5d1ee80d80fd947cc16c4815a479?source=copy_link)
[(versi Bahasa Indonesia)](https://www.notion.so/ekapujiwara/Predictive-Analysis-of-Operational-QSR-2cec5d1ee80d816d931ac4d8564bdf55?source=copy_link)

Dashboard Preview:
![page1](https://github.com/Pujiwara/Pictures/blob/main/Predictive%20Analysis%20of%20Operational%20QSR_page-0001.jpg)
![page2](https://github.com/Pujiwara/Pictures/blob/main/Predictive%20Analysis%20of%20Operational%20QSR_page-0002.jpg)
![page3](https://github.com/Pujiwara/Pictures/blob/main/Predictive%20Analysis%20of%20Operational%20QSR_page-0003.jpg)
![page4](https://github.com/Pujiwara/Pictures/blob/main/Predictive%20Analysis%20of%20Operational%20QSR_page-0004.jpg)
![page5](https://github.com/Pujiwara/Pictures/blob/main/Predictive%20Analysis%20of%20Operational%20QSR_page-0005.jpg)

Description:
This case study analyzes operational performance and customer satisfaction in a Quick Service Restaurant (QSR) using a data-driven approach. The objective of this project is to identify key operational drivers of customer satisfaction, evaluate the reliability of predictive models, and assess the potential business impact of operational improvements through scenario simulation.
Using a combination of SQL for data preparation, Python for exploratory analysis and predictive modeling, and Power BI for interactive visualization, this study transforms raw operational data into actionable insights. The analysis covers exploratory data analysis, feature engineering, regression-based prediction, model validation, and what-if scenario simulation to support informed operational decision-making.

Dataset:
https://www.kaggle.com/datasets/john8909/qsr-operational-dataset

# Analytical Approach
### Methods
This analysis follows a structured, end-to-end analytics workflow designed to move from exploration to decision support:
- **Exploratory Data Analysis (EDA)** to identify patterns in demand, service duration, wait time, staffing, and customer satisfaction
- **Operational feature engineering**, including time-based features, capacity ratios, and satisfaction segmentation
- **Predictive modeling** using linear regression to estimate customer satisfaction based on operational drivers
- **Model validation and error analysis** to assess accuracy, stability, and potential bias
- **What-if scenario simulation** to evaluate the business impact of operational changes and support decision-making

### Dashboard Structure
1. **Executive Overview**
    High-level KPIs, overall model performance, and trend comparison between actual and predicted customer satisfaction
2. **Model Performance & Diagnostics**
    Evaluation of model accuracy, prediction errors, and reliability through scatter plots and error distributions
3. **Operational & Correlation Analysis**
    Exploration of relationships between operational variables such as wait time, staff efficiency, item rating, and customer satisfaction
4. **What-If Scenario Simulation**
    Interactive simulation to assess how changes in key operational drivers affect customer satisfaction outcomes
5. **Operational Insights & Recommendations**
    Summary of key findings translated into actionable business recommendations

### Tools
- **PostgreSQL** — data loading, cleaning, validation, and feature preparation
- **Python** — exploratory analysis, correlation analysis, regression modeling, and model diagnostics
- **Power BI** — interactive dashboards, KPI monitoring, model visualization, and scenario simulation

# Key Insight
- **Product quality and staff performance are the primary drivers of customer satisfaction**
    The analysis shows that item rating and staff efficiency have the strongest positive influence on customer satisfaction. Improvements in these areas deliver significantly higher satisfaction gains compared to operational speed metrics.
- **Reducing wait time alone yields limited satisfaction improvement**
    While wait time has a negative relationship with customer satisfaction, its overall impact is relatively smaller. This suggests that customers are more tolerant of moderate delays when service quality and product experience remain strong.
- **The predictive model demonstrates strong reliability for operational monitoring**
    With a high alignment between actual and predicted satisfaction scores and a low average prediction error, the model is suitable for tracking customer satisfaction trends and supporting day-to-day operational decisions.
- **Customer satisfaction levels are already relatively stable under current operations**
    Scenario simulations indicate that moderate operational adjustments do not generate significant satisfaction deltas, implying that the restaurant’s baseline performance is already optimized to a certain extent.
- **Operational improvements should prioritize quality over speed**
    Simulation results confirm that investments in product improvement and staff capability development are more impactful than focusing solely on faster service processes.

# Business Recommendations
### **Prioritize Product Quality Improvement**
**Rationale:**
Item rating is the strongest driver of customer satisfaction based on the predictive model and driver sensitivity analysis.
**Action Plan:**
- Conduct regular menu quality reviews based on customer feedback and item ratings
- Identify underperforming menu items and refine recipes, ingredients, or presentation
- Focus innovation efforts on high-impact menu items rather than broad menu expansion
**Expected Impact:**
Sustained improvement in customer satisfaction with relatively high return on investment.
### **Enhance Staff Efficiency Through Training and Scheduling Optimization**
**Rationale:**
Staff efficiency has a significant positive impact on customer satisfaction, second only to product quality.
**Action Plan:**
- Implement targeted staff training programs focused on service consistency and responsiveness
- Optimize staff scheduling during peak hours to maintain service quality
- Use efficiency metrics as part of routine performance monitoring
**Expected Impact:**
Improved service experience without significantly increasing operational costs.
### **Manage Wait Time as a Supporting Factor, Not the Primary Focus**
**Rationale:**
While wait time negatively affects satisfaction, its influence is weaker compared to quality-related factors.
**Action Plan:**
- Set acceptable wait-time thresholds rather than aggressively minimizing service time
- Use wait-time reduction strategies selectively during peak congestion periods
- Balance speed improvements with service quality to avoid negative trade-offs
**Expected Impact:**
Operational efficiency gains without compromising customer experience.
### **Leverage Predictive Monitoring for Early Detection**
**Rationale:**
The predictive model demonstrates sufficient accuracy for operational monitoring and early warning purposes.
**Action Plan:**
- Integrate predicted satisfaction metrics into daily or weekly performance dashboards
- Monitor deviations between actual and predicted satisfaction as early signals of operational issues
- Use trend-based alerts rather than individual outlier orders
**Expected Impact:**
Proactive issue detection and faster operational response.
### **Use Scenario Simulation to Support Data-Driven Decision Making**
**Rationale:**
What-if simulations help quantify the potential impact of operational changes before implementation.
**Action Plan:**
- Use scenario simulation during operational planning and budgeting discussions
- Evaluate trade-offs between quality improvements and operational speed initiatives
- Prioritize initiatives that show the highest simulated satisfaction uplift
**Expected Impact:**
More informed decisions with reduced risk of ineffective operational changes
