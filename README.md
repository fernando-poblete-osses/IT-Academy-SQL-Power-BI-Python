# Data Analytics Portfolio 
*IT Academy Barcelona Bootcamp Projects (Feb-Jul 2025)*

## Overview
This repository showcases my data analytics projects from the IT Academy Barcelona Bootcamp, demonstrating proficiency across SQL, Power BI, and Python. The portfolio highlights integrated data workflows from database querying to visualization and machine learning.

## Repository Structure
The portfolio is organized into five core technical domains:

| Folder | Assignment | Focus Area | Key Technologies |
|--------|------------|------------|------------------|
| [`SQL_Data_Analysis`](/SQL_Data_Analysis) | 4 | Database Analysis | MySQL, Window Functions |
| [`PowerBI_Data_Analysis`](/PowerBI_Data_Analysis) | 5 & 6 | Business Intelligence | Power Query, DAX |
| [`Python_Programming`](/Python_Programming) | 7 | Core Programming | Data Structures, Regex |
| [`Python_Data_Analysis`](/Python_Data_Analysis) | 8 | Advanced Analytics | Pandas, Seaborn, Plotly |
| [`ML_Fraud_Detection`](/ML_Fraud_Detection) | 10 | Machine Learning | CatBoost, SMOTE, Scikit-learn |

> **Integrated Projects**: Assignments 4, 5, 6, and 8 form a continuous data pipeline using a shared database

## Technical Skills Breakdown

### 🔍 SQL - Data Analysis (Assignment 4)
[See detailed README](/SQL_Data_Analysis)
- **Database Expertise**: 
  - Complex joins and aggregations
  - CTEs and window functions
  - Date manipulation and data modification
- **Key Operations**:
  - Query optimization
  - Subquery implementation
  - Advanced filtering techniques

### 📊 Power BI - Data Analysis (Assignments 5 & 6)
[See detailed README](/PowerBI_Data_Analysis)
- **BI Development**:
  - Star schema data modeling
  - ETL processes with Power Query
  - DAX measure creation
- **Visualization**:
  - Interactive dashboard design
  - Business KPI tracking
  - Drill-through reporting

### 🐍 Python - Programming (Assignment 7)
[See detailed README](/Python_Programming)
- **Core Programming**:
  - Data structure manipulation (Dictionaries/Lists)
  - String processing with regex
  - Input validation & error handling
- **System Design**:
  - Modular program architecture
  - File I/O operations
  - Context managers

### 📈 Python - Data Analysis (Assignment 8)
[See detailed README](/Python_Data_Analysis)
- **Full Analytics Workflow**:
  - MySQL → Python data pipeline
  - Pandas transformations (feature engineering)
  - DateTime operations
- **Advanced Visualization**:
  - Seaborn statistical plots
  - Plotly interactive charts
  - Matplotlib customization
- **Statistical Analysis**:
  - Correlation testing
  - Multi-dimensional analysis
  - Geospatial segmentation

### 🤖 Machine Learning - Fraud Detection (Assignment 10)
[See detailed README](/ML_Fraud_Detection)
- **ML Pipeline**:
  - Class imbalance handling (SMOTE)
  - Feature scaling & encoding
  - Model evaluation metrics
- **Algorithms**:
  - CatBoost (with class weighting)
  - MLP Neural Networks
  - Support Vector Machines
- **Evaluation**:
  - Precision-Recall curves
  - AUC-ROC metrics
  - Confusion matrix analysis

## Integrated Workflow Highlights
```mermaid
graph LR
    A[SQL Data Extraction] --> B[Power BI Dashboarding]
    A --> C[Python Analysis]
    C --> D[Machine Learning]
    B --> E[Business Insights]
    D --> E
