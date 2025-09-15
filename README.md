
# Telco Customer Churn Prediction

This repository contains code and experiments for predicting customer churn using different machine learning approaches.  
The project compares **Linear Regression, Logistic Regression, and GAM-like models (GLM with Splines)** on a telco dataset.

---

## 📂 Project Structure

#### Telco_Churn_Assignment.ipynb # Jupyter notebook with data prep, modeling, and evaluation
#### requirements.txt # Python dependencies to recreate the environment
#### data/ # This is where I placed the dataset that I downloaded from Kaggle: https://www.kaggle.com/datasets/blastchar/telco-customer-churn


---

## 🚀 Getting Started

### 1. Clone the repository, Create a Virtual Environment, and Launch the jupyter notebook
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>


python -m venv .venv
source .venv/bin/activate     # On Windows: .venv\Scripts\activate

pip install -r requirements.txt

jupyter notebook
