
# Swire Coca-Cola Capstone Project: Predictive Maintenance Optimization

# Summary of Business Problem and Project Objective
Swire Coca-Cola, one of the five largest Coca-Cola bottlers in the U.S., produces close to 192 million cases of beverages annually to serve markets across 13 states. However, the company faces significant financial and operational challenges due to frequent and unplanned machine downtimes in its six production plants. These downtimes result in only 94.4% of ordered cases being produced, causing an estimated $60 million in annual losses. The root cause lies in a reactive maintenance strategy that focuses on repairing machines after breakdowns, leading to prolonged periods of inactivity and substantial productivity loss.

# Objective
The primary objective of this project was to analyze maintenance data, build predictive models, and provide actionable recommendations to transition Swire Coca-Cola from a reactive to a proactive maintenance strategy. By leveraging data-driven insights and predictive analytics, the project aimed to:

Minimize unplanned downtime and associated costs.
Enhance machine reliability and operational efficiency.
Optimize maintenance schedules to reduce disruptions and increase production output.
Provide clear, actionable strategies for prioritizing critical maintenance areas.

# Our Group’s Solution
Our team employed the CRISP-DM (Cross Industry Standard Process for Data Mining) methodology to systematically address the problem. This framework guided the project through six structured phases:

Data Understanding:
Analyzed over 1.4 million work order records spanning multiple plants and equipment categories.
Conducted univariate, bivariate, and multivariate analyses to identify patterns, relationships, and critical factors driving downtimes.
Performed missing value and outlier analyses to improve data quality and reliability.
Feature Engineering:

Created new features such as breakdown frequency by equipment type, time between failures, and downtime trends to improve model accuracy.
Extracted meaningful insights from equipment descriptors, timestamps, and functional area hierarchies.
Modeling Techniques:

Explored various modeling techniques, including ARIMA for time-series analysis and Kaplan-Meier survival models for time-to-failure predictions.
Selected models were tailored to provide interpretable results and align with Swire Coca-Cola's business goals.
Results and Insights:

Identified critical equipment and locations with the highest breakdown risks.
Analyzed seasonal trends in downtime, helping prioritize maintenance schedules during peak failure periods.
Business Recommendations:

Proposed a proactive maintenance strategy focusing on high-risk equipment such as fillers and packers.
Recommended resource reallocation and inventory planning for critical spare parts to minimize production disruptions.

# My Contribution to the Project
As a core contributor to the project, I played a pivotal role in data analysis, visualization, and modeling investigations. Below is a detailed account of my work:

**1. Data Analysis and Visualization**
Conducted a thorough exploration of the dataset, uncovering key patterns and relationships among variables such as downtime frequency, maintenance types, and equipment categories.
Designed and developed high-impact visualizations to:
Highlight breakdown trends over time and across production locations.
Analyze downtime patterns for functional area nodes and equipment types.
Showcase feature importance, revealing critical factors influencing machine breakdowns.
Delivered visual insights that facilitated effective communication of findings, enabling stakeholders to identify high-priority maintenance areas.
**2. Modeling Techniques Investigation**
Conducted in-depth research on suitable modeling approaches for predictive maintenance, including:
Linear Regression: Used as a baseline for simple relationships.
Random Forest and XGBoost: Explored for their robustness in feature selection and non-linear relationships.
LightGBM: Investigated for its efficiency with large datasets.
Evaluated model performance and interpretability to recommend techniques that align with Swire Coca-Cola’s operational needs.
**3. Feature Importance and Insights**
Performed feature importance analysis using advanced methods like tree-based models to identify key predictors of downtime.
Investigated time between failures for equipment categories, pinpointing fillers and packers as the most failure-prone.
Analyzed seasonal and location-based trends to provide targeted maintenance recommendations.
**4. Interpretation and Documentation**
Interpreted data patterns and modeling outcomes to generate actionable insights, such as prioritizing maintenance for high-risk equipment.
Proofread the final report to ensure accuracy, clarity, and a coherent narrative for both technical and non-technical audiences.


# Business Value of the Solution
The proposed solution provided Swire Coca-Cola with actionable strategies to reduce downtime and improve operational efficiency. Key impacts include:

 -**Enhanced Predictive Capabilities:** 
 Insights into high-risk periods and equipment enable better planning and proactive interventions.
 
 -**Cost Savings:** 
 A 5.6% reduction in downtime translates to approximately $10.7 million additional cases annually, significantly boosting productivity.
 
 -**Operational Efficiency:** 
 Prioritized maintenance and resource allocation improve uptime, reduce delays, and enhance production stability.


# Difficulties Encountered
The team faced several challenges during the project:

 -**Data Quality Issues:** High percentages of missing data in critical variables (e.g., MAINTENANCE_PLAN had 89% missing values) complicated modeling efforts.
Inconsistent documentation practices led to gaps in equipment lifecycle data.

 -**Modeling Complexities:** Balancing model accuracy and interpretability to ensure actionable insights.
Limited computational resources for testing advanced models and hyperparameter tuning.

 -**Resource Constraints:** Time constraints posed challenges in conducting exhaustive analyses across multiple datasets and methodologies.
Despite these challenges, the team successfully navigated these hurdles through robust feature engineering, careful selection of modeling techniques, and a focus on delivering high-value insights.

# What I Learned in the Project
This project provided invaluable learning experiences, including:

-**Technical Proficiency:** Strengthened expertise in data visualization, feature engineering, and model evaluation techniques.
Gained hands-on experience with tree-based algorithms and their applications in predictive maintenance.

-**Problem-Solving and Collaboration:** Improved teamwork skills and the ability to communicate technical insights effectively.
Adapted to challenges like missing data and resource limitations by leveraging innovative strategies.

-**Business Context:** Developed a deeper understanding of how operational inefficiencies impact business performance.
Learned to align technical outputs with actionable business recommendations.
