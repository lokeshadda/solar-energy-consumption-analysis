# Solar Energy Consumption Analysis using Machine Learning

## Project Overview

This project focuses on analyzing solar energy consumption patterns using Machine Learning techniques. The objective of this project is to preprocess the dataset, perform exploratory data analysis, train multiple machine learning models, and evaluate their performance using various classification metrics.

The project demonstrates a complete end-to-end machine learning workflow including:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Handling imbalanced data using SMOTE
- Hyperparameter tuning using GridSearchCV
- Model evaluation and comparison

---

## Business Problem

Understanding energy consumption behavior and sustainability-related factors is important for improving renewable energy adoption and optimization. This project uses machine learning models to analyze solar energy consumption data and identify predictive patterns from the dataset.

---

## Dataset Information

The dataset used in this project contains solar footprint and energy consumption-related attributes.

### Dataset File
- `solar_footprints.csv`

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- MLflow

---

## Machine Learning Models Used

The following models were implemented and evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Classifier (SVC)
- Multi-Layer Perceptron (MLP)
- Random Forest Classifier

---

## Project Workflow

### 1. Data Loading
- Imported and explored the dataset
- Checked data types and structure

### 2. Data Cleaning & Preprocessing
- Handled missing values
- Feature scaling using `StandardScaler`
- Train-test split preparation

### 3. Handling Imbalanced Data
- Applied SMOTE (Synthetic Minority Oversampling Technique)

### 4. Exploratory Data Analysis (EDA)
- Correlation analysis
- Feature relationship analysis
- Statistical summaries

### 5. Model Training
- Implemented multiple machine learning algorithms
- Used GridSearchCV for hyperparameter tuning

### 6. Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## Correlation Heatmap

The correlation heatmap below highlights relationships between important variables in the dataset and helps identify useful patterns for feature analysis and model building.

![Correlation Heatmap](images/correlation_heatmap.png)

---

## Project Structure

```text
solar-energy-consumption-analysis/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   └── solar_footprints.csv
│
├── notebooks/
│   └── solar_footprint_analysis.ipynb
│
└── images/
    └── correlation_heatmap.png
```

---

## Installation & Setup

### Clone Repository

```bash
git clone https://github.com/your-username/solar-energy-consumption-analysis.git
```

### Navigate to Project Folder

```bash
cd solar-energy-consumption-analysis
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

---

## Future Improvements

- Deploy models using Streamlit or Flask
- Add advanced feature engineering techniques
- Perform deeper model comparison and optimization
- Integrate real-time renewable energy datasets
- Build interactive dashboards for visualization

---

## Author

Lokesh Adda

- Data Analyst
- Data Quality & Governance Enthusiast
- Machine Learning & Analytics Learner

---

## License

This project is for educational and portfolio purposes.