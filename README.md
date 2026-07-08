# 🧠 Personality Type Classification using Machine Learning

This project demonstrates how to build a machine learning model that predicts a person's **personality type** based on a set of input characteristics. The notebook follows a complete machine learning workflow, including data exploration, preprocessing, handling class imbalance, model training, and evaluation using **Logistic Regression**.

---

## 📌 Features

- Exploratory Data Analysis (EDA)
- Data visualization with Seaborn
- Label encoding for categorical data
- Feature standardization
- Class imbalance handling using `SMOTE`
- Train/Test split
- Logistic Regression classifier
- Model evaluation using multiple classification metrics

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- imbalanced-learn (SMOTE)
- Jupyter Notebook

---

## 📚 Libraries

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
```
---

## 📊 Dataset

The project uses a **synthetic personality dataset** containing various personal attributes used to classify an individual's personality type.

The dataset includes multiple input features and a target variable:

- Personality Type (Target Variable)

Categorical labels are converted into numerical values using **LabelEncoder** before model training.

---

## ⚙️ Machine Learning Workflow

The notebook performs the following steps:

- Load the dataset
- Explore and visualize the data
- Encode categorical labels
- Split the dataset into training and testing sets
- Standardize features using `StandardScaler`
- Balance the training data using **SMOTE**
- Train a **Logistic Regression** model
- Generate predictions
- Evaluate model performance

---

## 📈 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Precision Score
- Recall Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report
- ROC Curve

These metrics provide a comprehensive assessment of the classifier's performance.

---

## 🚀 Getting Started

### Install dependencies

```bash
pip install -r requirements.txt
```

Or install them manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
main.ipynb
```

Run the notebook cells sequentially to reproduce the complete machine learning workflow.

---

## 🎯 Learning Objectives

This project demonstrates how to:

- Perform exploratory data analysis
- Encode categorical variables
- Standardize numerical features
- Handle imbalanced datasets using SMOTE
- Train a Logistic Regression classifier
- Evaluate classification models using multiple performance metrics
- Interpret ROC curves and confusion matrices

---

## 🔮 Future Improvements

- Compare additional classification algorithms (Random Forest, SVM, XGBoost)
- Perform hyperparameter tuning with GridSearchCV
- Apply cross-validation
- Analyze feature importance
- Deploy the model as a web application using Streamlit or Flask
