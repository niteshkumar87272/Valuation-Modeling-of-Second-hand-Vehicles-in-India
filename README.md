# 🚗 Valuation Modeling of Second-hand Vehicles in India


This project focuses on building a **machine learning-based valuation model** for used cars in India. The goal is to accurately estimate the market price of second-hand vehicles based on features like brand, year, fuel type, transmission, kilometers driven, and more.

---

## 🎯 Objectives

- Identify key factors affecting used car prices in India  
- Preprocess and analyze real-world vehicle datasets  
- Build and evaluate ML models to predict resale value  
- Provide insights into pricing trends in the Indian used car market

---

## 📊 Dataset Description

The dataset includes listings of second-hand cars in India with the following attributes:

| Feature           | Description                          |
|-------------------|--------------------------------------|
| Name              | Car brand and model                  |
| Year              | Year of manufacture                  |
| Selling_Price     | Target variable (resale price)       |
| Present_Price     | Current ex-showroom price            |
| Kms_Driven        | Kilometers driven                    |
| Fuel_Type         | Petrol / Diesel / CNG                |
| Seller_Type       | Dealer / Individual                  |
| Transmission      | Manual / Automatic                   |
| Owner             | Number of previous owners            |

---

## 🛠️ Tech Stack & Tools

- 🐍 Python 3.x  
- 📦 Pandas, NumPy – for data manipulation  
- 📊 Matplotlib, Seaborn – for data visualization  
- 🤖 Scikit-learn – for model building and evaluation  
- 🧪 Jupyter Notebook / Google Colab – for experimentation

---

## 🚀 Workflow

### 🔹 Step 1: Data Preprocessing
- Handle missing values and outliers  
- Encode categorical features (Label Encoding / One-hot Encoding)  
- Feature engineering (e.g., calculating car age)

### 🔹 Step 2: Exploratory Data Analysis (EDA)
- Visualize price trends by brand, fuel type, etc.  
- Analyze correlations with the selling price

### 🔹 Step 3: Model Building
Tested multiple regression models:
- Linear Regression  
- Ridge & Lasso Regression  
- Decision Tree Regressor  
- Random Forest Regressor

### 🔹 Step 4: Evaluation

| Model                | R² Score | MAE    |
|----------------------|----------|--------|
| Linear Regression    | 0.84     | 0.97 L |
| Decision Tree        | 0.89     | 0.73 L |
| Random Forest        | 0.92     | 0.64 L |

---

## 📈 Key Insights

- Diesel cars generally have higher resale value than petrol cars  
- Resale value drops significantly after 5 years of usage  
- Dealer-listed vehicles are priced higher than individual listings  
- Automatic transmission cars retain better value over time

---

## 🔮 Future Scope

- Use deep learning for better generalization  
- Deploy as a web app using Flask or Streamlit  
- Add more datasets from various Indian regions  
- Incorporate car condition, service history, or accident reports

---

## 👨‍💻 Author

**Nitesh Kumar**  
_B.Tech CSE (Data Science), 4th Semester_  
📍 Bihar, India  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/nitesh-kumar-507a0928b/)

---

## 📜 License

This project is open-source and free to use for educational and research purposes.
