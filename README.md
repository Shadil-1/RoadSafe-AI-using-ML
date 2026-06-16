# RoadSafe AI 🚦

A Machine Learning project for predicting road traffic accident severity using historical accident data. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and performance evaluation.

## 📌 Project Overview

Road traffic accidents remain a major public safety concern worldwide. This project analyzes accident-related factors and builds machine learning models to predict accident severity based on driver, vehicle, road, and environmental conditions.

The goal is to identify important contributing factors and develop a predictive model that can assist in traffic safety analysis and decision-making.

---

## 📂 Dataset

Dataset: **RTA Dataset**

The dataset contains information related to:

- Driver demographics
- Driving experience
- Vehicle characteristics
- Road conditions
- Weather conditions
- Accident severity levels
- Traffic-related factors

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 🔍 Project Workflow

### 1. Data Collection
- Loaded Road Traffic Accident (RTA) dataset.

### 2. Data Cleaning
- Removed unnecessary columns.
- Handled missing values using mode imputation.
- Removed duplicates.
- Treated outliers using the IQR method.

### 3. Exploratory Data Analysis (EDA)
Visualizations include:

- Accident distribution by light conditions
- Weather conditions analysis
- Road surface condition vs accident severity
- Driver age group analysis
- Correlation heatmap

### 4. Feature Engineering
- Label Encoding for categorical variables.
- Standard Scaling for numerical features.

### 5. Model Building
Implemented:

- Logistic Regression
- Random Forest Classifier

### 6. Hyperparameter Tuning
- GridSearchCV
- RandomizedSearchCV

### 7. Model Evaluation
Evaluation metrics:

- Accuracy
- Precision
- Recall
- F1 Score

---

## 📊 Models Used

| Model | Purpose |
|---------|----------|
| Logistic Regression | Baseline classification |
| Random Forest | Main prediction model |

---

## 🎯 Results

The Random Forest model achieved better performance compared to Logistic Regression and was selected as the final model.

Performance metrics evaluated:

- Accuracy
- Precision
- Recall
- F1 Score

---

## 📈 Feature Importance

The project identifies the most influential features contributing to accident severity using Random Forest feature importance analysis.

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/RoadSafe-AI.git
```

### Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Run Notebook

```bash
jupyter notebook accidents.ipynb
```

---

## Project Structure

```text
RoadSafe-AI/
│
├── accidents.ipynb
├── RTA Dataset.csv
├── README.md
└── requirements.txt
```

---

## Future Improvements

- Deploy as a web application using Flask or Streamlit.
- Add real-time accident severity prediction.
- Explore advanced machine learning models.
- Improve model interpretability using SHAP values.

---

## Author

Developed as a Machine Learning project focused on traffic accident severity prediction and road safety analytics.
