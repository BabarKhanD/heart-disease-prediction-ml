Heart Disease Prediction using Machine Learning

This project is part of the AI/ML Engineering Internship at DevelopersHub Corporation.

We use supervised learning to build a classification model that predicts the likelihood of a person having heart disease based on clinical and diagnostic features.

Task Objective
Predict heart disease risk using the UCI Heart Disease dataset
Apply preprocessing, visualization, model training, and evaluation
Interpret medical features and assess feature importance

Dataset
Source: [Heart Disease UCI Dataset on Kaggle](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
Features: Age, sex, chest pain type, cholesterol, max heart rate, exercise-induced angina, etc.
Target: Binary (0 = No heart disease, 1 = Heart disease present)

Methods Used
Data Preprocessing  | Renaming columns, replacing categorical values, one-hot encoding         
Visualization       | Heatmaps, histograms, boxplots, violin plots, regression analysis        
Model               | Random Forest Classifier (n=50 trees, max_depth=5)
Evaluation Metrics  | Accuracy, Confusion Matrix, Classification Report, ROC Curve & AUC Score

Libraries Used

- pandas, numpy
- matplotlib, seaborn
- scikit-learn

How to Run

1. Open the notebook: `heart_disease_prediction.ipynb`
2. Upload `heart.csv` to your Colab/Notebook session
3. Run all cells to see preprocessing, visualizations, and model output

Results
Training Accuracy: ~98%
Testing Accuracy: ~85%
AUC Score: ~0.90
- Model performs well and distinguishes heart disease presence effectively.

Final Insights

- Key risk indicators: chest pain type, cholesterol, max heart rate, ST depression
- Random Forest provides strong performance with minimal overfitting
- Can be used as a screening tool for early diagnosis

Credits

- Internship by DevelopersHub Corporation
- Dataset by UCI Machine Learning Repository
