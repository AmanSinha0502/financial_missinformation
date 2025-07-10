# 🧠 Financial Misinformation Detector & 📈 Stock Market Predictor

This Streamlit-powered web app helps users **detect financial misinformation** using GPT-4 and **predict stock closing prices** using machine learning models (LSTM and XGBoost). It's designed to empower users with AI-driven insights in the financial world.

---

## 🚀 Features

### 1. 🔍 Financial News Verifier
- Uses **OpenAI's GPT-4** to assess whether a piece of financial news is **accurate or misleading**
- Returns GPT-4's reasoning and supporting evidence

### 2. 📉 Stock Price Predictor
- Accepts a stock ticker (e.g., AAPL, TSLA, GOOGL)
- Retrieves historical data using **Yahoo Finance**
- Predicts the next closing price using:
  - Long Short-Term Memory (**LSTM**) neural networks
  - **XGBoost** regression model

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend / ML**: Python, TensorFlow, Keras, XGBoost, Scikit-learn
- **API**: OpenAI GPT-4 (`openai.ChatCompletion`)
- **Data**: Yahoo Finance (`yfinance`)

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/financial_missinformation.git
cd financial_missinformation
```
### 2. Create and activate a virtual environment (optional but recommended)

#### Windows
```
python -m venv venv
venv\Scripts\activate
```
#### macOS/Linux
```
python3 -m venv venv
source venv/bin/activate
```
### 3. Install dependencies
```
pip install -r requirements.txt
```
## 🔐 Set OpenAI API Key
Create a .env file in the root directory with the following content:

```
OPENAI_API_KEY=your_openai_api_key_here
```

## ▶️ Run the App
```
streamlit run app.py
```

Visit the app in your browser at:

http://localhost:8501


## 📁 Project Structure
```
financial_missinformation/
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
├── .env                # API key (not committed to GitHub)
└── README.md           # Project documentation
```

## ⚠️ Disclaimer
The stock price predictions are experimental and not financial advice.

GPT-4 responses are probabilistic and may not always reflect factual accuracy.

Always do your own research before acting on financial insights.

📄 License
This project is licensed under the MIT License – feel free to use, modify, and distribute with attribution.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to open an issue or submit a pull request.

## 📬 Contact
Created by Aman Sinha
📍 India
🎓 B.Tech CSE Student | 🚀 Full-stack Developer
📧 kumaramansinha97088@gmail.com

## If you found this project useful, don’t forget to ⭐ star the repo!
