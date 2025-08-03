# portfolio_package 🚀

**portfolio_package** ist ein Python-Toolkit zur effizienten Verwaltung und tiefgehenden Analyse von Aktienportfolios mit Daten von Alpha Vantage.

---

## 🔧 Voraussetzungen

- **Python-Bibliotheken**:  
  `pandas`, `pandas_ta`, `os`, `time`, `matplotlib`, `seaborn`, `requests`, `json`

- **Alpha Vantage API-Key** (kostenlos):  
  Um Aktienkursdaten abzufragen, benötigst du einen API-Schlüssel von [Alpha Vantage](https://www.alphavantage.co/).  
  Hol dir deinen API-Key [hier](https://www.alphavantage.co/).

---

## 📒 Jupyter Notebooks

### 1. `pf-manager.ipynb`  
**Portfolio Manager**  
- Erstelle, bearbeite und verwalte deine Portfolio-Liste  
- Arbeite ausschließlich mit **Ticker-Symbolen** (z.B. `AAPL`, nicht Apple Inc.)  
- Bereitet die Datenbasis für die Analyse im zweiten Notebook vor  

---

### 2. `pf-insider.ipynb`  
**Portfolio Analyse & Insights**

| Funktion                | Beschreibung                                                                                  | Nutzen                                                                                  |
|------------------------|----------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| **Korrelationsmatrix**  | Visualisiert die Zusammenhänge zwischen deinen Portfolio-Tickern und den Märkten             | Portfolio-Risiko besser verstehen und optimieren                                       |
| **Smoothing ATR + Mean**| Glättet die Average True Range (ATR) und berechnet den Portfoliodurchschnitt                 | Volatilität der Aktien verstehen und Sharpe Ratio verbessern                           |
| **Performance Analyse** | Prozentuale Performance einzelner Ticker im Vergleich zum Portfolio-Durchschnitt             | Wachstumstreiber und Ausreißer erkennen, Portfolio optimieren                          |

---

## 🚀 Features & Ziele

- Einfache Portfolioverwaltung direkt im Jupyter Notebook  
- Umfassende Risiko- und Performance-Analysen  
- Grundlage für datengetriebene Investmententscheidungen  
- Ausbau mit weiteren Analysefunktionen geplant  

---

## 🛠 Installation & Setup

```bash
pip install pandas pandas_ta matplotlib seaborn requests
