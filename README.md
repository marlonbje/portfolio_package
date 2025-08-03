# portfolio_package 🚀

**portfolio_package** is a Python toolkit for efficient portfolio management and in-depth stock analysis using data from Alpha Vantage.

---

## 🔧 Requirements

- **Python Libraries:**  
  `pandas`, `pandas_ta`, `os`, `time`, `matplotlib`, `seaborn`, `requests`, `json`

- **Alpha Vantage API Key** (free):  
  To fetch stock data, you need an API key from [Alpha Vantage](https://www.alphavantage.co/).  
  Get your API key [here](https://www.alphavantage.co/).

---

## 📒 Jupyter Notebooks

### 1. `pf-manager.ipynb`  
**Portfolio Manager**  
- Create, edit, and manage your portfolio list  
- Use **ticker symbols** only (e.g., `AAPL`, not "Apple Inc.")  
- Prepares the data foundation for further analysis in the second notebook  

---

### 2. `pf-insider.ipynb`  
**Portfolio Analysis & Insights**

| Feature                  | Description                                                                              | Benefits                                                      |
|--------------------------|------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| **Correlation Matrix**   | Visualizes correlations between your portfolio tickers and general market indices        | Better understand and optimize portfolio risk                 |
| **Smoothing ATR + Mean** | Smooths the Average True Range (ATR) and calculates portfolio average                     | Understand volatility and improve Sharpe ratio                |
| **Performance Analysis** | Analyzes percentage performance of individual tickers vs. portfolio mean                  | Identify growth drivers and outliers, optimize portfolio      |

---

## 🚀 Features & Goals

- Easy portfolio management within Jupyter Notebooks  
- Comprehensive risk and performance analysis  
- Data-driven investment decision support  
- More analysis functions planned for future releases  

---

## 🛠 Installation & Setup

Run this to install dependencies:
- Insert your API key in the notebooks  
- Create your portfolio using ticker symbols and start analyzing  

---

## 📚 Resources

- [Alpha Vantage API](https://www.alphavantage.co/)  
- Python libraries: `pandas`, `matplotlib`, `seaborn`, etc.

---

## 🙋‍♂️ Feedback & Contributions

Got ideas, suggestions, or feature requests?  
Your feedback is highly appreciated!

---

**Happy investing!**  
_The portfolio_package Team_
