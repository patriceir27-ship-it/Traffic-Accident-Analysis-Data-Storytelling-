# 🚦 US Traffic Accident Analysis & Data Storytelling  
### Internship Project — **Prodigy Info Tech**


##  Project Overview

This repository contains a **full end-to-end data analytics and data storytelling project** developed as part of my **Data Analyst Internship at Prodigy Info Tech**.

The project focuses on analyzing **US Traffic Accident data** to uncover **where**, **when**, and **why** road accidents occur, with special emphasis on:

- Accident **severity**
- **Temporal patterns** (hour, weekday, season)
- **Weather conditions**
- **Road and infrastructure characteristics**
- **Geospatial hotspots**
- **Contributing factors** using statistics and interpretable machine learning

The entire workflow follows **industry-grade analytical standards**, from data understanding and cleaning to advanced exploratory analysis, geospatial hotspot detection, and explainable insights.


## Project Objectives

The main goals of this project are:

1. **Understand the structure and limitations** of a real-world large accident dataset  
2. **Clean and validate data** to ensure analytical reliability  
3. **Engineer meaningful features** from raw temporal, weather, and road data  
4. **Discover patterns** using Exploratory Data Analysis (EDA)  
5. **Identify accident hotspots** across the United States  
6. **Explain contributing factors** behind accident severity  
7. **Translate findings into actionable insights** through data storytelling  

>  This project is not about “just plotting graphs” — it is about **reasoning with data**.



## Dataset Description

- **Source**: US Accidents Dataset (Kaggle)
- **Sampling**: Applied for computational efficiency during EDA
- **Rows**: ~16,000+
- **Columns**: 46
- **Key Dimensions**:
  - Time (`Start_Time`, `End_Time`)
  - Location (`Start_Lat`, `Start_Lng`, `City`, `State`)
  - Severity (`1` to `4`)
  - Weather conditions
  - Road & infrastructure indicators


## Analytical Philosophy

This project follows a **professional analytics pipeline**:

> **Data → Information → Insight → Story → Decision**

Every step is **justified**, **documented**, and **interpretable**.



##  Step-by-Step Analytical Workflow

###  Data Understanding
- Dataset structure & schema inspection
- Variable classification (temporal, spatial, weather, road)
- Identification of analytical targets
- Early detection of limitations and biases


###  Data Cleaning & Quality Assurance
- Structural validation (rows, columns, data types)
- Missing value classification:
  - **Critical** (coordinates, time)
  - **Contextual** (weather)
  - **Optional** (end coordinates)
- Integrity checks:
  - Duplicate IDs
  - Invalid ranges
  - Time consistency
- Result: **Trustworthy, analysis-ready dataset**


### Feature Engineering
- **Time features**: hour, weekday, weekend, season, rush hours
- **Weather features**:
  - Grouped weather conditions
  - Risk indicators (low visibility, freezing temperature, high wind)
- **Road complexity features**:
  - Intersection complexity
  - Traffic control presence
  - Urban infrastructure proximity



###  Exploratory Data Analysis (EDA)
Key questions answered:
- How does **severity distribute**?
- When do accidents peak?
- How do **weather conditions** influence severity?
- Which road features correlate with higher risk?

 **Key Story**  
> *Accidents follow human activity rhythms, not randomness.*



### Geospatial Hotspot Analysis
- National-level accident density maps
- Severity-weighted hotspot detection
- State and city drill-down analysis
- Urban vs rural comparison (proxy)
- Hotspot profiling:
  - Peak hours
  - Dominant weather
  - Common road features
  - Average severity

**Outcome**: Clear identification of high-risk regions.


###  Contributing Factor Analysis
#### Statistical Association
- Chi-square tests (categorical vs severity)
- Kruskal / ANOVA (numeric vs severity)
- Effect sizes:
  - **Cramér’s V**
  - **Epsilon-squared**
  
#### Predictive Insight (Optional)
- Binary severity classification (Low vs High)
- Interpretable models:
  - Logistic Regression
  - Decision Tree
- Feature importance & SHAP explanations

 **Outcome**: Ranked list of factors that truly matter.


##  Key Insights (Summary)

- Accident severity increases significantly under **low visibility**
- **Rush hours** show strong concentration of incidents
- **Intersections and traffic signals** are major contributors
- Urban areas concentrate accidents, but **rural accidents tend to be more severe**
- Weather amplifies risk, but **road complexity determines impact**

---

## Tools & Technologies

- **Python**
- **Pandas, NumPy**
- **Matplotlib**
- **Scikit-learn**
- **SciPy**
- **SHAP (optional)**


## Internship Context

This project was completed as part of the **Data Analyst Internship at Prodigy Info Tech**.

It demonstrates:
- Strong analytical reasoning
- Clean, efficient coding practices
- Real-world data handling
- Professional storytelling with data
- Readiness for industry-level analytics tasks


## Acknowledgement

I would like to thank **Prodigy Info Tech** for providing this internship opportunity, which allowed me to apply theoretical knowledge to a practical, real-world data problem.


## Contact

**Author:** Patrice IRADUKUNDA  
**Role:** Data Analyst Intern — Prodigy Info Tech  

If you have feedback, suggestions, or collaboration ideas, feel free to reach out.


> *If you find this repository insightful, consider giving it a star!*  



