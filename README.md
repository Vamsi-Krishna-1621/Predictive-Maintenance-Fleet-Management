# Predictive Analytics for Vehicle Maintenance in Fleet Management

## Project Overview

This project applies Predictive Analytics and Machine Learning techniques to vehicle maintenance data to identify vehicles that are likely to require maintenance before breakdowns occur.

The project was developed as part of an MBA Business Analytics internship project and focuses on improving fleet reliability, reducing downtime, and supporting data-driven maintenance planning.

---

## Business Problem

Organizations that manage large vehicle fleets often face challenges due to unexpected vehicle breakdowns, resulting in:

- Increased maintenance costs
- Operational delays
- Reduced fleet availability
- Lower service efficiency
- Safety risks

Traditional maintenance approaches are often reactive or time-based and may not accurately reflect the actual condition of vehicles.

This project aims to use historical vehicle data and machine learning models to predict maintenance requirements and support proactive maintenance scheduling.

---

## Business Objectives

- Analyze vehicle maintenance data using data analytics techniques.
- Identify factors influencing vehicle maintenance requirements.
- Build predictive models to forecast maintenance needs.
- Support fleet managers with data-driven insights.
- Develop an interactive dashboard for monitoring fleet health.

---

# Project Workflow

## Step 1: Project Brief

Understanding the business problem, project objectives, expected outcomes, and solution approach.

**File:**

`01_project_brief.pdf`

---

## Step 2: Data Collection & Preparation

Collected and prepared vehicle maintenance data containing information such as:

- Vehicle Age
- Mileage
- Fuel Type
- Engine Size
- Tire Condition
- Brake Condition
- Battery Status
- Service History
- Maintenance History
- Reported Issues

**File:**

`02_vehicle_maintenance_data.csv`

---

## Step 3: Data Analysis & Machine Learning

Performed:

### Data Cleaning

- Missing value handling
- Duplicate removal
- Data preprocessing
- Label encoding

### Exploratory Data Analysis (EDA)

Analyzed:

- Vehicle Age vs Maintenance Requirement
- Mileage vs Maintenance Requirement
- Brake Condition Impact
- Battery Status Impact
- Maintenance History Patterns

### Machine Learning Models

Implemented:

1. Logistic Regression
2. Decision Tree
3. Random Forest

### Model Evaluation

Evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve

**File:**

`03_predictive_maintenance_analysis.ipynb`

---

## Step 4: Dashboard Development

Developed an interactive Power BI dashboard to visualize:

- Fleet Maintenance Distribution
- Vehicle Age Analysis
- Maintenance Trends
- Brake Condition Impact
- Reported Issues Analysis
- Fleet Health Monitoring

**File:**

`04_fleet_maintenance_dashboard.pbix`

---

## Step 5: Project Documentation

Prepared a detailed project report covering:

- Research Methodology
- Data Analysis
- Predictive Modelling
- Results & Discussion
- Dashboard Analysis
- Recommendations
- Future Scope

**File:**

`05_project_report.pdf`

---

# Tools & Technologies

### Programming

- Python
- SQL

### Data Analysis

- Pandas
- NumPy

### Visualization

- Power BI
- Matplotlib
- Seaborn

### Machine Learning

- Scikit-Learn

### Other Tools

- Excel
- Jupyter Notebook

---

# Key Insights

- Older vehicles are more likely to require maintenance.
- High mileage vehicles show increased maintenance requirements.
- Brake condition significantly impacts maintenance needs.
- Battery status influences vehicle reliability.
- Reported issues are strong indicators of maintenance requirements.
- Predictive analytics can reduce downtime and improve fleet planning.

---

# Machine Learning Models Used

| Model | Purpose |
|---------|---------|
| Logistic Regression | Baseline Classification Model |
| Decision Tree | Rule-Based Prediction |
| Random Forest | Ensemble Learning Prediction |

---

# Business Value

The implementation of predictive maintenance can help organizations:

- Reduce vehicle downtime
- Improve fleet reliability
- Lower maintenance costs
- Enhance operational efficiency
- Improve maintenance scheduling
- Support proactive decision-making

---

# Repository Structure

```
01_project_brief.pdf
02_vehicle_maintenance_data.csv
03_predictive_maintenance_analysis.ipynb
04_fleet_maintenance_dashboard.pbix
05_project_report.pdf
README.md
```

---

# Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Predictive Analytics
- Machine Learning
- Power BI Dashboard Development
- SQL Querying
- Business Analytics
- Reporting & Documentation

---

# Author

## Vamsi Krishna Meka

MBA – Business Analytics

P.B. Siddhartha College of Arts & Science

Vijayawada, Andhra Pradesh

### LinkedIn

www.linkedin.com/in/vamsi-krishna-meka

### GitHub

github.com/Vamsi-Krishna-1621

---

# Future Improvements

- Real-time vehicle sensor integration
- IoT-enabled predictive maintenance
- Advanced machine learning models
- Fleet maintenance alert system
- Cloud-based dashboard deployment
