# Python - Machine Learning - Assignment 10

Data Preprocessing
- Categorical encoding: OneHotEncoder (for MLP/SVC pipelines)
- Feature scaling: RobustScaler (for numerical features like amount)
- Train-test splitting: train_test_split with stratify.
- Feature Engineering
  
Key Algorithms
- CatBoost: CatBoostClassifier (with native categorical handling)
- Neural Networks: MLPClassifier
- Support Vector Machines: SVC

Model Evaluation
- Metrics: Precision, Recall, F1-Score (classification_report)
- AUC-ROC & AUC-PR: roc_auc_score, average_precision_score
- Confusion Matrix: confusion_matrix + seaborn.heatmap visualization
- Precision-Recall Curves: precision_recall_curve

Handling Imbalanced Data
- SMOTE: For oversampling minority class (handling categorical features)
- Class weighting: class_weights in CatBoost

Pipelines & Workflow
- Pipeline + ColumnTransformer for preprocessing
- Custom evaluation functions for metrics/storage
- Comparative model analysis with AUC-PR plots

Key Libraries
- Core: scikit-learn, pandas, numpy, matplotlib, seaborn
- Specialized: catboost, imbalanced-learn (SMOTE)
