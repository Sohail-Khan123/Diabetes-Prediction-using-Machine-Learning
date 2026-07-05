# 🩺 Diabetes Prediction using Machine Learning

A machine learning project that predicts whether a patient is likely to have diabetes based on medical diagnostic measurements. This project includes data exploration, preprocessing, model training, evaluation, and hyperparameter tuning using Python and Scikit-learn.

---

## 📌 Project Overview

The objective of this project is to build a machine learning model capable of predicting diabetes using patient health data.

The notebook covers the complete machine learning workflow:

- Data exploration and analysis
- Data preprocessing
- Handling missing values
- Feature scaling
- Model training
- Model evaluation
- Hyperparameter tuning
- Performance comparison

---

## 📂 Project Structure

```
Diabetes-Prediction/
│
├── Diabetes Prediction.ipynb      # Main Jupyter Notebook
├── posa_shaktoi.csv               # Dataset
├── README.md                      # Project documentation
```

---

## 📊 Dataset

The dataset contains medical attributes commonly used for diabetes prediction.

Typical features include:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

**Target Variable**

- `0` → Non-Diabetic
- `1` → Diabetic

---

## 🔍 Exploratory Data Analysis (EDA)

The notebook performs several exploratory analysis tasks including:

- Class distribution analysis
- Correlation between features
- Detection of invalid zero values
- Displaying dataset statistics
- Dataset preview using `head()`

---

## 🛠 Data Preprocessing

The preprocessing pipeline includes:

- Replacing invalid values
- Median imputation for missing values
- Feature and target separation
- Train/Test split
- Feature standardization using `StandardScaler`

---

## 🤖 Machine Learning Models

The following models are implemented:

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

---

## ⚙ Hyperparameter Tuning

The project uses **GridSearchCV** to optimize:

### Random Forest

- Number of estimators
- Maximum depth
- Minimum samples split
- Minimum samples leaf

### Support Vector Machine

- Kernel
- C
- Gamma

---

## 📈 Evaluation Metrics

Each model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

---

## 🧰 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Diabetes-Prediction.git
```

Move into the project directory:

```bash
cd Diabetes-Prediction
```

Install dependencies:

```bash
pip install pandas numpy scikit-learn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Diabetes Prediction.ipynb
```

---

## ▶️ How to Run

1. Clone the repository.
2. Install the required Python libraries.
3. Place the dataset (`posa_shaktoi.csv`) in the project directory.
4. Open the notebook.
5. Run all cells sequentially.

---

## 📌 Project Workflow

```
Dataset
    │
    ▼
Data Exploration
    │
    ▼
Data Cleaning
    │
    ▼
Missing Value Imputation
    │
    ▼
Feature Scaling
    │
    ▼
Train/Test Split
    │
    ▼
Model Training
    │
    ▼
Model Evaluation
    │
    ▼
Hyperparameter Tuning
    │
    ▼
Performance Comparison
```

---

## 🎯 Learning Outcomes

This project demonstrates:

- Exploratory Data Analysis (EDA)
- Data preprocessing techniques
- Missing value handling
- Feature engineering basics
- Machine learning model development
- Model evaluation
- Hyperparameter optimization using GridSearchCV

---

## 🚀 Future Improvements

Possible enhancements include:

- Add XGBoost and LightGBM models
- Perform feature selection
- Build a Streamlit or Flask web application
- Deploy the model on Render or Hugging Face Spaces
- Add SHAP explainability
- Perform cross-validation comparison

---

## 👨‍💻 Author

**Sohail Khan**

Software Engineering Student

Interested in:

- Machine Learning
- Deep Learning
- Python Development
- Artificial Intelligence
- Data Science
- Web Development

---

## 📄 License

This project is intended for educational and learning purposes.