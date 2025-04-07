# Shanghai Stock Forecasting Web App

## 📌 Overview
This Shanghai Stock Forecasting Web App allows users to analyze historical stock data of the top 25 Shanghai companies, perform ARIMA-based time series forecasting, and compare predicted prices with actual stock prices using Yahoo Finance (finance).

The app is built using **Streamlit**, **Pandas**, **Plotly**, and **Statsmodels**, making it interactive and visually appealing.

## 🚀 Features
✅ **Stock Price Analysis**: Visualize historical stock prices for Shanghai-listed companies.
✅ **ARIMA-Based Forecasting**: Forecast future stock prices using the **ARIMA model**.
✅ **ADF Stationarity Test**: Check data stationarity before applying it to the forecast.
✅ **Interactive Forecast Selection**: Select forecast duration (5 to 90 days).
✅ **Compare Forecast vs. Actual Prices**: Fetch real stock data and compare it with predicted values.
✅ **Residual Analysis**: Analyze the difference between forecasted and actual prices.

## 📦 Tech Stack
- **Python** 🐍
- **Streamlit** 🎈 (Web UI)
- **Pandas** 📝 (Data Processing)
- **Plotly** 📊 (Data Visualization)
- **Statsmodels** 📈 (ARIMA Forecasting)
- **Yahoo Finance (yfinance)** 💹 (Stock Data Retrieval)

## 📥 Installation
To set up and run the app, follow these steps:

### 1️⃣ Clone the Repository
```sh
 git clone https://github.com/your-username/stock-forecasting-app.git
 cd stock-forecasting-app
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)
```sh
 python -m venv venv
 source venv/bin/activate  # On macOS/Linux
 venv\Scripts\activate  # On Windows
```

### 3️⃣ Install Dependencies
```sh
 pip install -r requirements.txt
```

### 4️⃣ Run the Streamlit App
```sh
 streamlit run app.py
```

📊 Usage
1.Select a company from the sidebar dropdown.
2. View historical stock price trends**.
3. Perform **ARIMA-based forecasting**.
4. Compare **forecasted vs. actual prices**.
5. Analyze **residual errors**.

📂 Project Structure
```
├── app.py                 # Main Streamlit app
├── Shanghai.csv           # Stock dataset
├── requirements.txt       # Dependencies
├── README.md              # Project documentation

```

🛠 To-Do / Future Enhancements
- Optimize ARIMA parameters automatically.
- Allow multiple stock selection for side-by-side analysis.
- Integrate Deep Learning models** (LSTM, Prophet) for better predictions.
- Deploy the app on Streamlit Sharing or AWS.

🤝 Contributing
Contributions are welcome! Feel free to fork the repo, create a branch, and submit a pull request.

 📝 License
This project is licensed under the **MIT License.

---
💡 Author: Nayan Thakre,Soham Parsodkar
📧 Contact: nayanthakre379@gmail.com,connectsohamparsodkar@gmail.com 
🌍 GitHub: [ntNayan23](https://github.com/ntNayan23)
[SohamParsodkar19](https://github.com/SohamParsodkar19)

