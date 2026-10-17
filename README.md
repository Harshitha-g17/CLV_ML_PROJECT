# 💰 Customer Lifetime Value (CLV) Prediction

## 🧠 Project Overview

Customer Lifetime Value (CLV) Prediction is a machine learning project that estimates the potential value of customers based on their purchasing behavior. It helps businesses identify high-value customers, improve customer retention, and optimize marketing strategies.

The project uses Python, machine learning libraries, and Streamlit to provide an interactive interface for customer value estimation and business recommendations.

## 🎯 Objectives

- Predict customer lifetime value using transaction data.
- Analyze customer purchasing behavior.
- Segment customers based on their estimated value.
- Support targeted marketing and customer retention.
- Provide an interactive prediction dashboard.

## 📊 Dataset

The project uses the **Online Retail Dataset** from the UCI Machine Learning Repository.

Dataset: https://archive.ics.uci.edu/dataset/352/online+retail

Important features include:
- `InvoiceNo` – Invoice number
- `Quantity` – Number of items purchased
- `UnitPrice` – Price per item
- `InvoiceDate` – Transaction date
- `CustomerID` – Customer identifier
- `Country` – Customer's country

## ⚙️ Project Workflow

1. **Data Collection:** Load historical retail transaction data.
2. **Data Preprocessing:** Handle missing values, invalid transactions, and inconsistent data.
3. **Exploratory Data Analysis:** Analyze customer spending and purchasing patterns.
4. **Feature Engineering:** Extract useful customer and transaction features.
5. **Model Development:** Prepare and evaluate machine learning models for CLV estimation.
6. **Web Application:** Use Streamlit to display customer value estimates and recommendations.

## 🛠️ Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn
- CatBoost and XGBoost
- Matplotlib and Seaborn
- Streamlit
- Git and GitHub

## 🖥️ Application Features

- Enter customer and transaction details.
- View an estimated customer lifetime value.
- Categorize customers into value segments.
- Display customer-specific business recommendations.
- Interact with predictions through a web interface.

## 📁 Project Structure

```text
CLV_ML_PROJECT/
├── artifacts/          # Model and preprocessing artifacts
├── notebook/           # Analysis and experimentation
├── src/                # Source code
├── templates/          # Application templates
├── logs/                # Log files
├── app.py               # Streamlit application
├── requirements.txt     # Project dependencies
├── setup.py             # Package configuration
└── README.md             # Project documentation
```

## 🚀 Installation and Execution

**1. Clone the repository**

```bash
git clone https://github.com/Harshitha-g17/CLV_ML_PROJECT.git
cd CLV_ML_PROJECT
```

**2. Install dependencies**

```bash
pip install -r requirements.txt
```

**3. Run the application**

```bash
streamlit run app.py
```

Open the local URL displayed in the terminal to access the application.

## 💼 Applications

- Customer segmentation
- Targeted marketing campaigns
- Customer retention strategies
- Marketing budget optimization
- Data-driven business decisions

## 📌 Conclusion

This project demonstrates how machine learning and data analysis can help businesses estimate customer value, understand purchasing behavior, and make better marketing and customer retention decisions.
