# 🏠 Boston Housing Price Prediction

This machine learning project predicts housing prices in Boston using a Linear Regression model. It explores relationships between various housing-related features (like crime rate, number of rooms, etc.) and the house price.

---

## 📌 Problem Statement

The goal is to build a regression model that can accurately predict house prices based on several attributes from the Boston housing dataset. This helps in real estate analysis and price estimation.

---

## 📊 Dataset

- **Source**: `boston.csv`  
- **Features**:
  - CRIM: Crime rate per capita
  - ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT
  - **Target**: Price (MEDV – Median value of owner-occupied homes)

---

## 🧠 Model Used

- **Algorithm**: Linear Regression  
- **Library**: scikit-learn (`sklearn.linear_model.LinearRegression`)
- **Preprocessing**: StandardScaler for feature normalization

---

## 📈 Model Evaluation

- **Train/Test Split**: 70% Training, 30% Testing  
- **Metrics Used**:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score

## 📉 Visualization

- Scatter Plot: CRIM (Crime Rate) vs. Price  
- Actual vs Predicted Values  
- Residual Plot using KDE (Seaborn)

---

## 🗃️ Files

- `boston.csv` – Dataset  
- `regmodel.pkl` – Trained Linear Regression Model  
- `scaling.pkl` – Trained Scaler for input normalization  

---

## 🚀 How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/Rajitha-5/Boston.git
    cd Boston
    ```

2. Make sure you have required packages:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

3. Run the Python script in your environment:
    ```bash
    python boston_model.py
    ```

---

## 📦 Future Improvements

- Use advanced models like Random Forest or XGBoost  
- Add Flask or Streamlit for deploying a web app  
- Perform feature engineering and hyperparameter tuning  

---

## 👩‍💻 Author

**Rajitha Bodireddy**  
📧 [rajithareddy182@gmail.com](mailto:rajithareddy182@gmail.com)

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

