# ⚡ Electricity Bill Prediction using Multiple Linear Regression

A Machine Learning project that predicts a household's monthly electricity bill using **Multiple Linear Regression**. The model is trained on multiple features such as electricity consumption, family size, AC usage, appliance count, and house area to estimate the expected bill.

---

## 📌 Project Overview

This project demonstrates the complete machine learning workflow:

- Data Loading
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Selection
- Train-Test Split
- Model Training using Multiple Linear Regression
- Model Evaluation
- Runtime Prediction using User Input

---

## 📂 Dataset

The dataset contains **1,000 synthetic records** with the following features:

| Feature | Description |
|---------|-------------|
| Units_Consumed | Monthly electricity consumption (kWh) |
| Family_Members | Number of family members |
| AC_Hours_Per_Day | Average daily AC usage (hours) |
| Appliance_Count | Number of electrical appliances |
| House_Area_sqft | House area in square feet |
| Electricity_Bill | Monthly electricity bill (Target Variable) |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- OpenPyXL
- ipywidgets

---

## 📈 Machine Learning Model

**Algorithm Used:**
- Multiple Linear Regression

The model predicts the monthly electricity bill based on multiple independent variables.

---

## 📊 Model Evaluation

The model is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📷 Visualizations

The project includes:

- Scatter Plot
- Correlation Heatmap
- Actual vs Predicted Values
- Regression Analysis

---

## 📁 Project Structure

```
Electricity-Bill-Prediction/
│
├── electricity_bill_multiple_linear_1000.xlsx
├── Multiple_Linear_Regression.ipynb
├── requirements.txt
├── README.md
└── images/
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YourUsername/Electricity-Bill-Prediction-LinearRegression.git
```

Move into the project folder:

```bash
cd Electricity-Bill-Prediction-LinearRegression
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

1. Open the project in **VS Code**.
2. Open the Jupyter Notebook.
3. Run all notebook cells from top to bottom.
4. Enter custom values using the runtime input section (or widgets, if included).
5. View the predicted electricity bill.

---

## 🚀 Future Improvements

- Add a Streamlit web application
- Use real-world electricity consumption data
- Compare Multiple Linear Regression with other regression algorithms
- Hyperparameter tuning and feature engineering

---

## 👩‍💻 Author

**Monika Dewangan**

- GitHub: https://github.com/MonikaDewangan
- LinkedIn: www.linkedin.com/in/monikadewangan

---

⭐ If you found this project useful, feel free to star the repository!

