# Fraud Detection System | Short Description
This project detects fraudulent financial transactions using machine learning. It includes data loading, preprocessing, exploratory data analysis (EDA), feature scaling, model training, and evaluation to classify transactions as fraud or legitimate.

---

## Project Structure
```
fraud-detection-system/
|-- fraud_detection.ipynb
|-- dataset/
|   |-- Fraud.csv
```
---

## Requirements
Python 3.8+  
Jupyter Notebook / JupyterLab  

Libraries required:  
numpy, pandas, matplotlib, seaborn, scikit-learn, jupyter

---

## How to Run (Complete Guide)

1. Clone the repository
``` 
git clone https://github.com/Manish9198/fraud-detection-system.git  
cd fraud-detection-system  
```
3. Create and activate virtual environment (optional but recommended)  
```
python -m venv venv  
source venv/bin/activate        (Linux / Mac)  
venv\Scripts\activate           (Windows)  
```
4. Install dependencies
```
pip install numpy pandas matplotlib seaborn scikit-learn jupyter  
```
6. Dataset setup  
Place the dataset file inside the dataset folder.  
The file name must be exactly: dataset/Fraud.csv  

7. Run the notebook
```
jupyter notebook  
```
Open fraud_detection.ipynb and run all cells from top to bottom.

---

## What This Project Does
Loads transaction data, checks missing values, performs EDA, scales numerical features using StandardScaler, trains a machine learning model, and evaluates fraud detection performance.

---

## Output
Fraud vs legitimate transaction analysis, visualizations, and model evaluation metrics.

---

## GitHub Push Commands
git add .  
git commit -m "Initial Fraud Detection project"  
git push  

---

## Author
Manish Sutar
