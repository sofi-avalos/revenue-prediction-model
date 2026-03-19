# Revenue Prediction with Machine Learning

## 📌 Overview

This project is an end-to-end machine learning pipeline designed to predict company revenue based on business investment features such as marketing spend, R&D investment, administrative costs, number of employees, and region.

The model uses data preprocessing, feature engineering, and a linear regression algorithm to generate predictions. It also includes an interactive console for real-time user input and evaluation metrics to assess model performance.

---

## ⚙️ Features

- Data preprocessing with:
  - Missing value imputation
  - Feature scaling
  - One-hot encoding for categorical variables
- Machine Learning model:
  - Linear Regression
- Model evaluation using:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- Interactive prediction system via console input
- Clean and modular code structure

---

## 🧠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn

---

## 📊 Model Performance

The model was evaluated on a test dataset and achieved the following results:

- MAE: 6648.40  
- RMSE: 8363.06  
- R²: 0.93  

These metrics indicate that the model explains a large portion of the variance in the data and performs well in predicting revenue.

---

## ▶️ How to Run the Project

1. Clone the repository or download the files

2. Make sure you have the required libraries installed:

```bash
pip install pandas numpy scikit-learn

Run the script:

python main.py

Enter the required inputs when prompted:
- Marketing Spend
- R&D Spend
- Administration Costs
- Number of Employees
- Region

📁 Project Structure
.
├── main.py
├── 788438_data.csv
└── README.md

👩‍💻 Author

Developed by Sofía Avalos

📌 Note

This project was developed as part of a machine learning learning process and demonstrates the application of regression models and data preprocessing techniques in a real-world scenario.
