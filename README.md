# Fraud-Detection-ML
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset used is highly imbalanced, so special attention was given to preprocessing steps such as resampling, feature selection, and scaling to improve model performance.

Key steps in this project include:

Data Cleaning & Preprocessing: Removed highly correlated features, scaled the 'Amount' column, and converted time-based features.

Handling Imbalanced Data: Applied resampling techniques to balance the dataset for better model training.

Feature Engineering: Dropped low-variance and highly correlated features to reduce multicollinearity and improve model interpretability.

Model Training: Utilized Logistic Regression due to its effectiveness in binary classification problems and evaluated using metrics like accuracy, precision, recall, F1-score, and the confusion matrix.

Performance: Achieved approximately 96% accuracy, 97% precision, and 95% recall, making the model robust for identifying fraudulent transactions.

Model Saving: Saved the trained model as a .pkl file for future deployment or inference.

Dataset : https://drive.google.com/file/d/16HtwvSSmImW12qgWzc-B48eWxMCzHPzl/view?usp=sharing
