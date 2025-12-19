### 🤖 5. Python - Machine Learning (Assignment 10)

See detailed README >

**Fraud Detection System:**

**Data Preprocessing & Feature Engineering:**
- Categorical encoding using OneHotEncoder (for MLP/SVC pipelines)
- Feature scaling with RobustScaler (for numerical features like transaction amount)
- Train-test splitting with stratification to maintain class distribution
- Feature engineering to create relevant predictors

**Algorithm Implementation:**
- **CatBoost**: CatBoostClassifier with native categorical feature handling
- **Neural Networks**: MLPClassifier for complex pattern recognition
- **Support Vector Machines**: SVC for classification with optimal hyperplanes

**Model Evaluation & Metrics:**
- Precision, Recall, F1-Score analysis (comprehensive classification reports)
- AUC-ROC & AUC-PR evaluation: roc_auc_score and average_precision_score
- Confusion Matrix visualization using seaborn.heatmap
- Precision-Recall Curves for detailed performance assessment

**Handling Class Imbalance:**
- **SMOTE**: Synthetic Minority Over-sampling Technique for oversampling the minority class
- **Class weighting**: Implementation in CatBoost to adjust for imbalanced distributions

**ML Pipeline & Workflow:**
- End-to-end pipelines using Pipeline + ColumnTransformer for preprocessing
- Custom evaluation functions for consistent metrics tracking and storage
- Comparative model analysis with AUC-PR plots for algorithm selection

**Key Technical Stack:**
- Core libraries: scikit-learn, pandas, numpy, matplotlib, seaborn
- Specialized: catboost, imbalanced-learn (for SMOTE implementation)

*Note: This standalone machine learning project focuses on credit card fraud detection, representing an independent application of advanced predictive modeling techniques.*
