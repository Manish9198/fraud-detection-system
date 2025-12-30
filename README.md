# Fraud Detection System

## Short Description
This project detects fraudulent financial transactions using machine learning. It performs data loading, preprocessing, exploratory data analysis (EDA), feature scaling, model training, and evaluation to classify transactions as fraud or legitimate.

---

## Project Structure
.
├── fraud_detection.ipynb
└── dataset/
    └── Fraud.csv

---

## Requirements
- Python 3.8+
- Jupyter Notebook / JupyterLab

### Python Libraries
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

---

## How to Run (Step-by-Step)

### 1. Clone the Repository
```bash
git clone https://github.com/Manish9198/fraud-detection-system.git
cd fraud-detection-system
```
### 2.Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate        # Linux / Mac
venv\Scripts\activate           # Windows
```

### 3.Install Dependencies
pip install numpy pandas matplotlib seaborn scikit-learn jupyter

### 4.Dataset Setup
Place the dataset file inside the dataset/ folder
File name must be exactly:
dataset/Fraud.csv

### 5.Run the Notebook
jupyter notebook

Open fraud_detection.ipynb
Run cells from top to bottom
