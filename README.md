Customer Churn Prediction using Machine Learning & Power BI

This project predicts telecom customer churn using a machine learning model built in Google Colab and visualizes the insights using Power BI dashboards. The goal is to help businesses identify customers who are likely to leave and take preventive actions.

🔍 Overview

- Predict whether a customer will churn based on behavioral and service usage data.
- Includes a trained ML model and visual dashboard for easier decision-making.
- Built using Python, Scikit-Learn, and Power BI.

📁 Folder Structure

Customer-churn-project/
├── Notebooks/
  └── Churn_Prediction.ipynb # Model development in Colab
├── Dashboard/
  └── Customer Churn Dashboard.pbix # Power BI visualization file
├── README.md
├── dataset_info.txt

📊 Dataset Summary

- Dataset includes customer demographic, billing, and service usage details.
- Target variable: *Churn* (Yes = customer left, No = customer stayed)
- Dataset is not included in this repo due to size constraints. Please refer to dataset_info.txt for more details.

⚙ Tech Stack Used

- *Programming Language:* Python
- *ML Libraries:* Pandas, NumPy, Scikit-Learn
- *Visualization Tool:* Power BI
- *Platform:* Google Colab

🚀 How to Run the Project

1. Clone or download this repository.
2. Open the Churn_Prediction.ipynb notebook in Google Colab or Jupyter Notebook.
3. Upload the dataset (CSV format; see dataset_info.txt).
4. Run all notebook cells to train and evaluate the churn prediction model.
5. Open the Customer Churn Dashboard.pbix file in Power BI to view the churn analysis dashboard.

📈 Dashboard Includes

- Overall churn rate visualization
- Churn by contract type
- Churn distribution by demographics
- Prediction summary visualization

🔮 Future Enhancements

- Deploying model via Flask or Streamlit
- Automated churn report generation
- Adding deep learning models or hyperparameter tuning

⚠ Important Note


*Dataset and trained ML model are not included in this repository due to size limits.*
