# Skin_Disorder_Prediction
This Machine Learning project focuses on predicting and diagnosing skin disorders (dermatological conditions) using clinical and histopathological patient data. The goal is to build an automated classification model that accurately categorizes skin conditions into one of 6 specific categories based on patient symptoms and test features.
Objective

Build a machine learning model to predict one of six skin disorder categories from clinical and histopathological patient attributes, to support early and accurate diagnosis.

Dataset

366 patient records with 34 predictive attributes (clinical symptoms + histopathological findings).

Workflow
Handled missing values in the Age column using median imputation
Performed EDA — class distribution (mild class imbalance across 6 disease classes), age distribution, feature correlations
Used stratified train-test split to handle class imbalance
Trained and compared five classification algorithms:
Logistic Regression
Decision Tree
Random Forest
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Evaluated using Accuracy, Classification Report, and Confusion Matrix
Results
Model	Accuracy
Logistic Regression	97.3%
Random Forest	95.9%
Decision Tree	93.2%
KNN	87.8%
SVM	71.6%
Suggestions for Clinical Use
Clinical symptoms (erythema, scaling, itching) should be carefully evaluated during initial diagnosis
Family history should be treated as an important diagnostic factor
Histopathological features flagged as important by the model deserve closer microscopic examination
The model can act as a decision-support tool for early disease identification, improving treatment outcomes
Tech Stack
Language: Python
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, joblib
Techniques: EDA, Feature Scaling, One-Hot Encoding, Train-Test Split, Regression, Classification, Clustering (K-Means, Hierarchical, DBSCAN), PCA, Feature Importance
Environment: Jupyter Notebook / Google Colab
Repository Structure
├── AutoPricePrediction.ipynb        # Car price regression
├── fifaprediction.ipynb             # FIFA player clustering
├── Heart_Disease_project.ipynb      # Heart disease classification
├── dermatology.ipynb                # Skin disorder classification
└── README.md
How to Run
Clone this repository
Install the required libraries:
   pip install pandas numpy matplotlib seaborn scikit-learn joblib
Open any notebook in Jupyter Notebook / JupyterLab / Google Colab
Run the cells in order (each notebook is self-contained, but datasets must be placed in the same directory or uploaded when prompted)
