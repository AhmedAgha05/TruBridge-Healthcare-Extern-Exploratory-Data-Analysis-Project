# TruBridge-Healthcare-Extern-Exploratory-Data-Analysis-Project
# TruBridge Healthcare — Exploratory Data Analysis

## 📊 Project Overview

This project was completed as part of a **TruBridge Healthcare Data Analytics Externship**. The goal was to explore county-level healthcare data and identify relationships between **health insurance access, housing insecurity, and diabetes prevalence** across the United States.

The analysis focuses on **3,143 U.S. counties**, using data from the CDC's **Behavioral Risk Factor Surveillance System (BRFSS)**. The original dataset contained more than 229,000 records, which were filtered and aggregated to create one observation per county.

## 🎯 Research Question

> How are lack of health insurance access and housing insecurity associated with diabetes prevalence across U.S. counties?

### Variables

* **Dependent Variable:** Diabetes prevalence rate
* **Predictor Variables:**

  * Lack of health insurance rate
  * Housing insecurity rate
* **Unit of Analysis:** U.S. county

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **Google Colab**
* **Exploratory Data Analysis (EDA)**
* **Data Visualization**
* **Statistical Analysis**
* **Linear Regression**
* **Power BI**
* **Generative AI tools**

## 🔎 Analysis Process

### 1. Data Preparation

The original healthcare dataset contained 229,000+ records. The data was filtered to the variables relevant to the research question and transformed so that each county appeared once, resulting in **3,143 county-level observations**.

### 2. Exploratory Data Analysis

The analysis examined patterns between:

* Lack of insurance and diabetes prevalence
* Housing insecurity and diabetes prevalence
* The combined relationship of both predictors with diabetes prevalence

Scatter plots and regression analysis were used to identify relationships and compare the relative effects of the two predictors.

### 3. Statistical Analysis

A linear regression model was used to evaluate how lack of insurance and housing insecurity were associated with diabetes prevalence while accounting for both predictors in the same model.

## 📈 Key Findings

### Lack of Insurance & Diabetes

The analysis found a **positive county-level relationship** between lack of insurance and diabetes prevalence. In general, counties with higher rates of adults lacking health insurance also tended to have higher diabetes prevalence.

### Housing Insecurity

Housing insecurity showed a stronger relationship with diabetes prevalence than lack of insurance in the regression analysis. The analysis estimated that its effect was **more than twice that of lack of insurance**.

### Combined Model

Together, lack of insurance and housing insecurity explained approximately **74% of the variation in county-level diabetes prevalence**, leaving approximately 26% unexplained.

## ⚠️ Limitations

This analysis identifies **associations, not causation**.

The remaining unexplained variation suggests that other factors may also be related to diabetes prevalence. Potential factors not included in this analysis include:

* Income
* Food insecurity
* Food access
* Other socioeconomic conditions

Additionally, the data is based on the CDC's BRFSS, which uses telephone survey data.

Because the analysis is conducted at the **county level**, the findings should not be interpreted as demonstrating that an individual person's insurance status or housing situation causes diabetes.

## 💡 Healthcare Implications

The analysis suggests that healthcare teams could consider the overlap between **insurance access and housing insecurity** when examining county-level diabetes patterns.

Potential areas for further investigation include:

* Coordinating insurance enrollment and housing assistance resources
* Identifying counties experiencing multiple socioeconomic challenges
* Investigating the role of income and food insecurity
* Exploring additional healthcare access variables

These are areas for further investigation rather than conclusions of causation.


## 📊 Project Deliverables

* Exploratory data analysis
* County-level data preparation
* Data visualizations
* Linear regression analysis
* Healthcare findings brief
* Power BI dashboard
* Practitioner-focused summary

## 📚 Data Source

**CDC Behavioral Risk Factor Surveillance System (BRFSS)**

The project uses county-level measures derived from the CDC BRFSS and focuses on relationships between healthcare access, housing insecurity, and diabetes prevalence.

---

### 👤 About the Project

**TruBridge Healthcare Data Analytics Externship**

This project provided experience applying data analytics techniques to a healthcare-focused problem, including data preparation, exploratory analysis, visualization, regression analysis, and communicating findings to a practitioner-oriented audience.
