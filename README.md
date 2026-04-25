# 📈🤖 Stock Price Prediction using Machine Learning

## 🏢 Internship Details
This project was completed as part of my **AI/ML Engineering Internship Tasks** at **DevelopersHub Corporation**.  
🔗 https://linkedin.com/company/developershub-corporation/

---

## 📌 Project Overview
This project focuses on predicting the **next day’s stock closing price** using historical stock market data. By leveraging machine learning techniques, the model analyzes past trends and patterns to estimate future price movements.

---

## 🎯 Objective
To build a regression model that can predict stock prices based on features such as opening price, highest price, lowest price, and trading volume.

---

## 📊 Dataset
- **Source:** Yahoo Finance API (via `yfinance`)
- **Stock Used:** Apple (AAPL) / Tesla (TSLA)
- **Features:**
  - Open
  - High
  - Low
  - Close
  - Volume

---

## ⚙️ Tech Stack
- Python 🐍  
- Pandas & NumPy (Data Processing)  
- Matplotlib (Visualization) 📊  
- Scikit-learn (Machine Learning) 🤖  
- yfinance (Data Collection API)

---

## 🔄 Project Workflow

### 1️⃣ Data Collection
- Retrieved historical stock data using the yfinance API
- Loaded dataset into Pandas DataFrame

---

### 2️⃣ Data Exploration
- Analyzed dataset structure using `.info()` and `.describe()`
- Visualized stock closing price trends over time

---

### 3️⃣ Data Preprocessing
- Created target variable (next day’s closing price)
- Shifted data using `.shift(-1)`
- Removed null values

---

### 4️⃣ Feature Selection
- Selected relevant features:
  - Open
  - High
  - Low
  - Volume

---

### 5️⃣ Data Splitting
- Split dataset into training (80%) and testing (20%)
- Maintained time-series order (no shuffling)

---

### 6️⃣ Model Building
- Applied **Linear Regression**
- Trained model on historical stock data

---

### 7️⃣ Prediction
- Predicted next-day closing prices
- Compared predicted vs actual values

---

### 8️⃣ Model Evaluation
- Evaluated using:
  - 📉 Mean Absolute Error (MAE)
- Visualized:
  - 📈 Actual vs Predicted Price Graph

---

## 📈 Results & Insights
- The model successfully captures general price trends  
- Predictions follow the overall market direction  
- Some deviation exists due to market volatility (real-world behavior)  

---

## 📷 Visualizations

### 📊 Stock Price Trend
*(Add image in /images folder)*

### 📈 Actual vs Predicted Prices
*(Add image in /images folder)*

---

## 🚀 Future Improvements
- Use advanced models (Random Forest, LSTM, XGBoost)
- Add technical indicators (Moving Average, RSI)
- Hyperparameter tuning
- Deploy as a web app (Streamlit)

---

## 👨‍💻 Author
**Hasnain**  
Aspiring AI/ML Engineer 🚀

---

## 📸 Output Screenshot

<img width="1590" height="566" alt="image" src="https://github.com/user-attachments/assets/adea8353-6e1c-4aab-9c83-039c50f03164" />

<img width="748" height="814" alt="image" src="https://github.com/user-attachments/assets/c1053069-b617-45d2-bcaf-cf9a21bdcd6b" />

<img width="1198" height="787" alt="image" src="https://github.com/user-attachments/assets/72d7e269-c3d4-4b30-9d56-012820f62c0e" />

<img width="596" height="564" alt="image" src="https://github.com/user-attachments/assets/039db63d-bf9d-4126-bd0b-d55f3b684999" />

<img width="1229" height="799" alt="image" src="https://github.com/user-attachments/assets/af1902e3-db97-41fe-93c0-d530a13f9b2a" />

<img width="581" height="170" alt="image" src="https://github.com/user-attachments/assets/23255b2a-f6b4-4b92-847e-3de92d4688c2" />

## ⭐ Support
If you found this project useful, give it a ⭐ and connect with me!
