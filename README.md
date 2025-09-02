# csca-5622-final-project
CSCA-5622 Introduce to machine learning: Supervised Learning final project.

# Credit Card Default Prediction (Final ML Project)

This repository contains my final project for **Introduction to Machine Learning: Supervised Learning**.  
The goal is to predict whether a credit card client will default on their next month’s payment.

---

## 📊 Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)  
- **File:** `default of credit card clients.xls` (file is also available in this repository).  
- **Size:** 30,000 rows, 23 features.  
- **Target:** `default payment next month` (1 = default, 0 = non-default).

---

## 🧪 Project Structure
- `final_project.ipynb` — Jupyter notebook with:
  - Step 1: Data source & provenance
  - Step 2: Problem definition
  - Step 3: Exploratory Data Analysis (EDA)
  - Step 4: Modeling (LogReg, Random Forest, HistGradientBoosting)
  - Step 5: Deliverables
- `requirements.txt` — dependencies to recreate the environment.

---

## ⚙️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/jamespoju/csca-5622-final-project.git
   cd csca-5622-final-project
2. Create a virtual env. (i.e. Python 3.12/3.13):
   ```bash
   python -m venv venv
   source venv/bin/activate    # macOS/Linux
   venv\Scripts\activate       # Windows
   pip install -r requirements.txt
3. Launch Jupyter:
   ```bash
   jupyter notebook
4. Open csca-5622-final-project.ipynb and run all cells.

