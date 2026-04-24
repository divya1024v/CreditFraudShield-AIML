# 💳 Credit Card Fraud Detection

---

## 📖 About The Project

This project focuses on detecting fraudulent credit card transactions using machine learning techniques.  
It analyzes transaction-level data to classify whether a transaction is genuine or fraudulent, helping reduce financial losses and improve fraud prevention systems.

The dataset used is highly imbalanced, making fraud detection a challenging problem that requires careful preprocessing, sampling, and model evaluation.

---

## 🎯 Key Features

- Fraud detection using machine learning models  
- Handles highly imbalanced dataset  
- Includes complete ML pipeline (EDA → training → evaluation)  
- Applies sampling techniques to improve model performance  
- Uses appropriate evaluation metrics for fraud detection  
- Designed for real-world financial risk scenarios  

---

## 🏗️ System Workflow

```bash
Raw Data → EDA → Preprocessing → Sampling → Model Training → Evaluation → Fraud Prediction
```

---

## ⚙️ Tech Stack

### Machine Learning & Data Processing

- Python  
- Pandas  
- NumPy  
- Scikit-learn  

### Data Analysis & Visualization

- Matplotlib  
- Seaborn  

---

## 📂 Project Structure

```bash
credit-card-fraud-detection/
│
├── data/                 # Dataset files
├── notebooks/            # EDA and experimentation
├── src/
│   ├── preprocessing.py  # Data preprocessing
│   ├── train.py          # Model training
│   ├── evaluate.py       # Model evaluation
│   └── utils.py          # Helper functions
│
├── models/               # Saved models
├── requirements.txt
└── README.md
```

---

## 📊 Dataset Details

- Total Transactions: 284,807  
- Fraudulent Transactions: 492  
- Fraud Ratio: ~0.172%  

### Dataset Characteristics

- Highly imbalanced dataset  
- Features transformed using PCA (V1–V28)  
- Includes:
  - `Time`: Time elapsed  
  - `Amount`: Transaction amount  
  - `Class`: Target (0 = normal, 1 = fraud)  

---

## 🧠 Machine Learning Pipeline

### Data Understanding

- Load and inspect dataset  
- Identify feature types and distribution  

### Exploratory Data Analysis (EDA)

- Univariate and bivariate analysis  
- Distribution checks  
- Outlier detection  

### Data Preprocessing

- Handle missing values (if any)  
- Normalize/scale features  
- Prepare data for modeling  

### Handling Imbalanced Data

- Apply sampling techniques such as:
  - Undersampling  
  - Oversampling  

### Train/Test Split

- Split dataset into training and testing sets  
- Use cross-validation for better evaluation  

### Model Training

- Train classification models such as:
  - Logistic Regression  
  - Decision Trees  
  - Random Forest  

### Model Evaluation

- Evaluate using metrics suitable for imbalanced data:
  - Precision  
  - Recall  
  - F1-score  
  - ROC-AUC  

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x  
- pip  

---

## Installation

```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt
```

---

## ▶️ Usage

### Run Data Preprocessing

```bash
python src/preprocessing.py
```

### Train Model

```bash
python src/train.py
```

### Evaluate Model

```bash
python src/evaluate.py
```

---

## 📈 Results

- Successfully handled highly imbalanced dataset  
- Improved fraud detection using sampling techniques  
- Focused on maximizing recall for fraud cases  
- Reduced false negatives (missed frauds)  

---

## 🔮 Future Improvements

- Use advanced models like XGBoost  
- Apply deep learning techniques  
- Real-time fraud detection system  
- Deploy as API or web application  
- Add anomaly detection techniques  

---

## 📚 Learnings

- Handling imbalanced datasets  
- Fraud-focused evaluation metrics  
- End-to-end ML pipeline development  
- Data preprocessing and feature engineering  
- Model selection and performance tuning  

---

## ⭐ Acknowledgements

- Kaggle Credit Card Fraud Dataset  
- Scikit-learn documentation  
- Data science community  
