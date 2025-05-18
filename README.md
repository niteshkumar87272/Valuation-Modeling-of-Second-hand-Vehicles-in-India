# 🚗 Valuation Modeling of Second-hand Vehicles in India

This project focuses on building a **machine learning-based valuation model** for used cars in India. The goal is to accurately estimate the market price of second-hand vehicles based on various features like brand, year, fuel type, transmission, kilometers driven, and more.

---

## 🎯 Objectives

- Understand key factors influencing used car prices in India  
- Clean, preprocess, and analyze real-world vehicle datasets  
- Build predictive models to estimate resale value of used cars  
- Evaluate model performance using metrics like R² score and MAE  
- Provide insights into pricing trends for Indian second-hand vehicle market

---

## 📊 Dataset Description

The dataset includes historical listings of used cars in India with the following attributes:

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

- 📌 **Python 3.x**
- 📌 **Pandas, NumPy** – Data manipulation  
- 📌 **Matplotlib, Seaborn** – Data visualization  
- 📌 **Scikit-learn** – Model building and evaluation  
- 📌 **Jupyter Notebook / Google Colab** – Experimentation

---

## 🚀 Workflow

### 🔹 Step 1: Data Preprocessing

- Handled missing values and outliers  
- Converted categorical features using label/one-hot encoding  
- Feature engineering (e.g., car age from manufacturing year)

### 🔹 Step 2: Exploratory Data Analysis (EDA)

- Visualized price trends across car brands and fuel types  
- Analyzed correlation between price and other features

### 🔹 Step 3: Model Building

- Tried multiple regression models:
  - Linear Regression
  - Ridge and Lasso Regression
  - Decision Tree Regressor
  - Random Forest Regressor

### 🔹 Step 4: Evaluation

| Model                | R² Score | MAE    |
|----------------------|----------|--------|
| Linear Regression    | 0.84     | 0.97 L |
| Random Forest        | 0.92     | 0.64 L |
| Decision Tree        | 0.89     | 0.73 L |

---

## 📈 Key Insights

- Diesel cars have higher resale value than petrol cars (on average)  
- Price drops significantly after the 5th year of ownership  
- Dealer-sold cars are often priced higher than individual-sold ones  
- Automatic cars hold value better in the long term

---

## 💡 Future Scope

- Integrate deep learning models for better generalization  
- Deploy the model using Flask or Streamlit for real-time pricing  
- Add more regional datasets to capture city-wise pricing patterns  
- Incorporate car condition or service history as input features  

---

## 📁 Project Structure

