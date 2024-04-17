# Breast Cancer Classification

This repository contains a machine learning project that classifies breast cancer tumors as malignant or benign based on various features.

### Libraries Used

- Pandas: For data manipulation and analysis.
- NumPy: For numerical computations.
- Scikit-learn: For machine learning algorithms and model evaluation.
- Matplotlib and Seaborn: For data visualization.
- Pickle: For saving and loading trained models.
- Warnings: For handling warning messages during execution.

### Data Preprocessing

- Loaded the Breast Cancer Wisconsin dataset from scikit-learn.
- Explored the dataset's structure and summary statistics.
- Checked for missing values in the dataset.

### Model Training and Evaluation

Three machine learning algorithms were employed for classification:

1. **Logistic Regression**: Achieved an accuracy of 98.25%.
2. **Support Vector Machine (SVM)**: Achieved an accuracy of 96.49%.
3. **Random Forest**: Also achieved an accuracy of 96.49%.

Each model was trained, evaluated, and its performance visualized using a confusion matrix.

### Model Deployment

The Logistic Regression model was chosen for deployment due to its high accuracy. It was saved as `Breast_Cancer_Model.sav` using Pickle.
