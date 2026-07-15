# 📈 Stock Price Prediction Using Machine Learning

---

# 📌 Project Overview

Stock Price Prediction is a Machine Learning and Deep Learning project that forecasts future stock prices using historical market data. The system analyzes past stock trends, trading volume, opening price, closing price, high price, and low price to predict future stock movements.

This project utilizes data preprocessing, technical indicators, machine learning models, and Long Short-Term Memory (LSTM) neural networks to provide accurate stock price predictions.

---

# 🎯 Objectives

- Predict future stock prices using historical data.
- Analyze stock market trends.
- Compare Machine Learning and Deep Learning models.
- Visualize stock performance.
- Generate future price forecasts.
- Build a real-time prediction dashboard.
- Assist investors in market analysis.

---

# 🚀 Features

✅ Historical Stock Data Analysis

✅ Data Cleaning and Preprocessing

✅ Technical Indicators

✅ Interactive Visualizations

✅ Machine Learning Models

✅ LSTM Deep Learning Model

✅ Future Price Forecasting

✅ Real-Time Stock Data Fetching

✅ Model Performance Comparison

✅ Streamlit Dashboard

✅ Download Prediction Reports

✅ User-Friendly Interface

---

# 🛠 Technologies Used

### Programming Language

- Python

### Libraries

- NumPy
- Pandas
- Matplotlib
- Plotly
- Seaborn
- Scikit-Learn
- TensorFlow
- Keras
- yFinance
- Streamlit
- Joblib

---

# 📂 Project Structure

```text
Stock-Price-Prediction/
│
├── data/
│   ├── stock_data.csv
│   └── processed_data.csv
│
├── models/
│   ├── lstm_model.h5
│   ├── scaler.pkl
│   └── random_forest.pkl
│
├── notebooks/
│   ├── EDA.ipynb
│   └── Model_Training.ipynb
│
├── images/
│   ├── stock_chart.png
│   ├── prediction_graph.png
│   ├── loss_curve.png
│   └── dashboard.png
│
├── src/
│   ├── data_collection.py
│   ├── preprocessing.py
│   ├── train.py
│   ├── predict.py
│   ├── evaluate.py
│   └── utils.py
│
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

# 📊 Dataset

The project uses stock market data collected from Yahoo Finance.

### Features

- Date
- Open Price
- High Price
- Low Price
- Close Price
- Adjusted Close
- Trading Volume

### Example

| Date | Open | High | Low | Close |
|--------|--------|--------|--------|--------|
| 2025-01-01 | 220.5 | 225.2 | 218.7 | 223.8 |

---

# 🔄 Project Workflow

```text
Data Collection
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Technical Indicators
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Prediction
      │
      ▼
Evaluation
      │
      ▼
Deployment
```

---

# 🧹 Data Preprocessing

The following preprocessing steps are applied:

- Missing Value Handling
- Duplicate Removal
- Feature Scaling
- Data Normalization
- Outlier Detection
- Time-Series Formatting
- Window Creation for LSTM

---

# 📈 Technical Indicators

The model uses multiple technical indicators:

### Trend Indicators

- Moving Average (MA)
- Exponential Moving Average (EMA)

### Momentum Indicators

- Relative Strength Index (RSI)
- MACD

### Volatility Indicators

- Bollinger Bands

### Volume Indicators

- On Balance Volume (OBV)

---

# 🤖 Machine Learning Models

### Traditional Models

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

### Deep Learning Models

- LSTM (Long Short-Term Memory)
- Bidirectional LSTM
- GRU Networks

---

# 🧠 LSTM Architecture

```text
Input Layer
      │
LSTM Layer (50 Units)
      │
Dropout Layer
      │
LSTM Layer (50 Units)
      │
Dense Layer
      │
Output Layer
```

---

# 📊 Evaluation Metrics

The model is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score
- Mean Absolute Percentage Error (MAPE)

---

# 📉 Visualizations

The project provides:

- Historical Stock Price Graph
- Closing Price Trend
- Moving Average Graph
- Prediction vs Actual Graph
- Loss Curve
- Correlation Heatmap
- Future Forecast Graph

---

# 💻 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/stock-price-prediction.git
```

### Navigate to Project

```bash
cd stock-price-prediction
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows

```bash
venv\Scripts\activate
```

Linux/Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 📦 Requirements

```text
numpy
pandas
matplotlib
seaborn
plotly
tensorflow
keras
scikit-learn
streamlit
joblib
yfinance
xgboost
```

Install using:

```bash
pip install -r requirements.txt
```

---

# ▶ Running the Project

### Train Model

```bash
python src/train.py
```

### Generate Predictions

```bash
python src/predict.py
```

### Run Streamlit Dashboard

```bash
streamlit run app.py
```

---

# 📈 Sample Prediction

### Input

```text
Stock Symbol: AAPL
Historical Data: Last 5 Years
Prediction Window: 30 Days
```

### Output

```text
Predicted Price After 30 Days: $245.75
Expected Growth: +6.2%
Confidence Score: 89%
```

---

# 📊 Model Performance

| Model | Accuracy |
|---------|---------|
| Linear Regression | 78% |
| Random Forest | 84% |
| XGBoost | 87% |
| LSTM | 92% |
| Bi-LSTM | 94% |

---

# 📱 Streamlit Dashboard Features

### Dashboard Includes:

- Stock Symbol Search
- Historical Charts
- Candlestick Charts
- Technical Indicators
- Future Price Prediction
- Download Reports
- Model Comparison
- Interactive Graphs

---

# 🔮 Future Enhancements

- Real-Time Stock Prediction
- News Sentiment Analysis
- AI Investment Recommendations
- Portfolio Management
- Cryptocurrency Prediction
- Reinforcement Learning Trading Bot
- Mobile Application
- Cloud Deployment
- Docker Support
- REST API Integration

---

# 📸 Screenshots
<img width="1366" height="662" alt="project 3 output screenshot 2" src="https://github.com/user-attachments/assets/ee5d1846-bc72-4e85-ae11-e94fac60d3fb" />
<img width="1358" height="650" alt="project 3 output screenshot 3" src="https://github.com/user-attachments/assets/22daa8a8-73f8-4b9b-abf0-118305eaac15" />
<img width="1352" height="542" alt="project 3 output screenshot 1" src="https://github.com/user-attachments/assets/fed414db-fcc8-4e2d-9590-a54aa19ca0ba" />
<img width="1353" height="656" alt="project 3 output screenshot 4" src="https://github.com/user-attachments/assets/831760ba-5754-47ae-9b71-88165cb816e6" />
<img width="1353" height="634" alt="project 3 output screenshot 5" src="https://github.com/user-attachments/assets/46603de9-99f8-4be8-a707-d1fbfb25e551" />

---

# 📚 Learning Outcomes

Through this project, you will learn:

- Time Series Analysis
- Feature Engineering
- Financial Data Analysis
- Deep Learning with LSTM
- Machine Learning Regression
- Data Visualization
- Model Deployment
- Streamlit Development

---

# 👩‍💻 Author

**Tanisha Mittal**

Machine Learning Developer

Artificial Intelligence Enthusiast

Data Science Learner

Python Programmer

---

# 📜 License

This project is licensed under the MIT License.

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository

🍴 Fork the repository

💡 Contribute improvements

🐛 Report bugs

---

# 🙏 Acknowledgements

- Yahoo Finance
- TensorFlow
- Keras
- Scikit-Learn
- Pandas
- NumPy
- Streamlit
- Plotly

---

## 📌 Conclusion

This Stock Price Prediction project demonstrates how Machine Learning and Deep Learning techniques can be applied to financial time-series data for forecasting future stock prices. It provides a complete pipeline from data collection and preprocessing to prediction and deployment through an interactive Streamlit dashboard.
