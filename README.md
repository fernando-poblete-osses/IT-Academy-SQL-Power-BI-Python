# Data Analytics Portfolio 
*IT Academy Barcelona Bootcamp Projects (Feb-Jul 2025)*

## Overview
This repository showcases data analytics projects from the IT Academy Barcelona Bootcamp, demonstrating proficiency in SQL, Power BI, and Python. The portfolio highlights integrated workflows from database querying to visualization and machine learning.

## Repository Structure
The portfolio is organized into five technical domains:

| Folder | Assignment | Focus Area | Key Technologies |
|--------|------------|------------|------------------|
| **[SQL - Data Analysis](/SQL%20-%20Data%20Analysis)** | 4 | Database Analysis | MySQL, Window Functions |
| **[Power BI - Data Analysis](/Power%20BI%20-%20Data%20Analysis)** | 5 & 6 | Business Intelligence | Power Query, DAX |
| **[Python - Programming Training](/Python%20-%20Programming%20Training)** | 7 | Core Programming | Data Structures, Regex |
| **[Python - Data Analysis](/Python%20-%20Data%20Analysis)** | 8 | Advanced Analytics | Pandas, Seaborn, Plotly |
| **[Python - Machine Learning](/Python%20-%20Machine%20Learning)** | 10 | Machine Learning | CatBoost, SMOTE, Scikit-learn |

> **Integrated Projects**: Assignments 4, 5, 6, and 8 form a continuous data pipeline using a shared database

## Technical Skills Breakdown

### 🔍 SQL - Data Analysis (Assignment 4)
[See detailed README >](/SQL%20-%20Data%20Analysis)
- **Database Expertise**: 
  - Complex joins and aggregations
  - CTEs and window functions
  - Date manipulation and schema design

### 📊 Power BI - Data Analysis (Assignments 5 & 6)
[See detailed README >](/Power%20BI%20-%20Data%20Analysis)
- **BI Development**:
  - Star schema implementation
  - ETL processes with Power Query
  - DAX measure creation
- **Visual Storytelling**:
  - Interactive dashboard design
  - Business KPI tracking

### 🐍 Python - Programming (Assignment 7)
[See detailed README >](/Python%20-%20Programming%20Training)
- **Core Programming**:
  - Dictionary/list operations
  - Regex text processing
  - Input validation & error handling
- **System Design**:
  - Modular architecture
  - File I/O operations

### 📈 Python - Data Analysis (Assignment 8)
[See detailed README >](/Python%20-%20Data%20Analysis)
- **Analytics Workflow**:
  - MySQL → Python pipeline
  - Pandas transformations
  - DateTime feature engineering
- **Advanced Visualization**:
  - Seaborn statistical plots
  - Plotly interactive charts
  - Correlation analysis

### 🤖 Machine Learning (Assignment 10)
[See detailed README >](/Python%20-%20Machine%20Learning)
- **Fraud Detection System**:
  - Class imbalance handling (SMOTE)
  - Feature scaling & encoding
  - Model evaluation metrics
- **Algorithms**:
  - CatBoost classifier
  - Neural Networks (MLP)
  - Support Vector Machines

## Project Pipeline Flow
```mermaid
graph LR
    A[SQL Extraction] --> B[Power BI Dashboard]
    A --> C[Python Analysis]
    C --> D[Machine Learning]
    B --> E[Business Insights]
    D --> E
