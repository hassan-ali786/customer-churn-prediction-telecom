# Customer Churn Prediction

A Machine Learning project that predicts customer churn for a telecom company using classification techniques.  
The goal is to identify customers likely to leave the service and help the company take preventive actions.

---

## Project Overview

This project analyzes telecom customer data to predict churn:

- Explore and preprocess customer data  
- Encode categorical variables  
- Visualize churn patterns against key features  
- Train a classification model for churn prediction  
- Evaluate model performance  

---

## Dataset Information

**Dataset:** Telecom Customer Churn Dataset  

**Features:**  

- Tenure  
- Monthly Charges  
- Contract Type  
- Internet Service  
- Payment Method  

**Target:** Customer Churn (Yes/No)  

---

## Key Analysis Performed

- Encoding categorical variables for machine learning  
- Visualization of churn vs tenure  
- Statistical comparison between churned and retained customers  

---

## Model Used

- **Logistic Regression** – simple, interpretable, and effective for binary classification  

---

## Results

- High churn observed among customers with lower tenure  
- Monthly charges significantly influence churn probability  
- Logistic Regression provides reliable predictions for telecom churn  

---

## Project Structure

```bash
customer-churn-prediction/
├── data/
│   └── telecom_churn.csv
├── notebooks/
│   └── Customer_Churn_Prediction.ipynb
├── requirements.txt
├── README.md
```

---

## Tools & Technology Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)  
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)  
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)  
![Matplotlib](https://img.shields.io/badge/Matplotlib-007D9C?style=flat&logo=matplotlib&logoColor=white)  
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)  
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)  
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)  

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/Hassan-Ali786/customer-churn-prediction.git
cd customer-churn-prediction
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook notebooks/Customer_Churn_Prediction.ipynb
```

4. Run all cells to reproduce analysis and model predictions.

---

## Future Improvements

- Experiment with other classification algorithms (Random Forest, XGBoost)  
- Include more customer features (support tickets, usage data)  
- Deploy as a web app for interactive churn prediction  
- Visualize feature importance and churn probability  

---

## Author

Hassan Ali  
Aspiring Data Scientist and Machine Learning Engineer  

GitHub: https://github.com/hassan-ali786  

---

## Notes

⭐ Feel free to fork this repository and explore further improvements!
