🧠 Logistic Regression - Binary Classification Project
This project implements a binary classification model using Logistic Regression to classify whether a tumor is benign or malignant, based on the Breast Cancer Wisconsin dataset.

📌 Objective
Build a logistic regression model to perform binary classification.
Evaluate performance using metrics like confusion matrix, precision, recall, F1-score, and ROC-AUC.
Understand and visualize the sigmoid function.
Explore threshold tuning to adjust decision boundaries.

🛠️ Tools & Libraries
Python
scikit-learn
pandas
numpy
matplotlib
seaborn

📂 Dataset
Name: Breast Cancer Wisconsin Dataset
Source: `sklearn.datasets.load_breast_cancer()`
Features: 30 numeric features (e.g., radius, texture, perimeter)
Target: 
`0` = malignant  
`1` = benign
    
🚀 Steps Performed
1. Import Libraries  
2. Load Dataset from scikit-learn
3. Preprocess:
   - Train/test split
   - Feature standardization using `StandardScaler`
4. Train Logistic Regression Model
5. Evaluate Model:
   - Confusion matrix
   - Classification report
   - Precision, Recall, F1-score
   - ROC-AUC score and ROC curve plot
6. Tune Classification Threshold
7. Visualize Sigmoid Function

📚 References
Scikit-learn Breast Cancer Dataset
Logistic Regression - Wikipedia
