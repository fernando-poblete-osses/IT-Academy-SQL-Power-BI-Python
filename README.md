# Data Analytics Portfolio 
*IT Academy Barcelona Bootcamp Projects (Feb-Jul 2025)*

## Overview
This repository showcases data analytics projects from the IT Academy Barcelona Bootcamp, demonstrating proficiency in SQL, Power BI, and Python. The portfolio highlights integrated workflows from database querying to visualization and machine learning.

## Repository Structure
The portfolio is organized into five technical domains with exact folder names:

| Folder | Assignment | Focus Area | Key Technologies |
|--------|------------|------------|------------------|
| **[1. SQL - Data Analysis](/1.%20SQL%20-%20Data%20Analysis)** | 4 | Database Analysis | MySQL, Window Functions |
| **[2. Power BI - Data Analysis](/2.%20Power%20BI%20-%20Data%20Analysis)** | 5 & 6 | Business Intelligence | Power Query, DAX |
| **[3. Python - Programming Training](/3.%20Python%20-%20Programming%20Training)** | 7 | Core Programming | Data Structures, Regex |
| **[4. Python - Data Analysis](/4.%20Python%20-%20Data%20Analysis)** | 8 | Advanced Analytics | Pandas, Seaborn, Plotly |
| **[5. Python - Machine Learning](/5.%20Python%20-%20Machine%20Learning)** | 10 | Machine Learning | CatBoost, SMOTE, Scikit-learn |

> **Integrated Projects**: Assignments 4, 5, 6, and 8 form a continuous data pipeline using a shared database

## Technical Skills Breakdown

### 🔍 1. SQL - Data Analysis (Assignment 4)
[See detailed README >](/1.%20SQL%20-%20Data%20Analysis)
- **Database Expertise**: 
  - Complex joins and aggregations
  - CTEs and window functions
  - Date manipulation and schema design

### 📊 2. Power BI - Data Analysis (Assignments 5 & 6)
[See detailed README >](/2.%20Power%20BI%20-%20Data%20Analysis)
- **BI Development**:
  - Star schema implementation
  - ETL processes with Power Query
  - DAX measure creation
- **Visual Storytelling**:
  - Interactive dashboard design
  - Business KPI tracking

### 🐍 3. Python - Programming (Assignment 7)
[See detailed README >](/3.%20Python%20-%20Programming%20Training)
- **Core Programming**:
  - Dictionary/list operations
  - Regex text processing
  - Input validation & error handling
- **System Design**:
  - Modular architecture
  - File I/O operations

### 📈 4. Python - Data Analysis (Assignment 8)
[See detailed README >](/4.%20Python%20-%20Data%20Analysis)
- **Analytics Workflow**:
  - MySQL → Python pipeline
  - Pandas transformations
  - DateTime feature engineering
- **Advanced Visualization**:
  - Seaborn statistical plots
  - Plotly interactive charts
  - Correlation analysis

### 🤖 5. Python - Machine Learning (Assignment 10)
[See detailed README >](/5.%20Python%20-%20Machine%20Learning)
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
    A[1. SQL Extraction] --> B[2. Power BI Dashboard]
    A --> C[4. Python Analysis]
    C --> D[5. Machine Learning]
    B --> E[Business Insights]
    D --> E
