# Quantitative Trading & Algorithmic Strategies

Repozytorium zawiera autorskie skrypty, wskaźniki oraz kompletne systemy transakcyjne dedykowane dla rynków kontraktów terminowych (indeksy USA oraz kryptowaluty). Projekt stanowi portfolio moich kompetencji w zakresie handlu ilościowego (Quantitative Trading), analizy danych oraz automatyzacji procesów decyzyjnych.

Projekt łączy podejście statystyczne z implementacją algorytmów egzekucyjnych na platformach TradingView, MetaTrader 5 oraz giełdach zdecentralizowanych.

---

## 🛠️ Architektura Projektu

Kod został podzielony strukturalnie według wykorzystywanych technologii i środowisk:

### 🐍 Python (`/python`)
Moduły odpowiedzialne za backend, analizę danych rynkowych oraz integrację z zewnętrznymi architekturami.
* **Analiza Ilościowa:** Implementacja modeli matematycznych i statystycznych (analiza zmienności, regresje lokalne) przy użyciu bibliotek ekonometrycznych.

### 🌲 Pine Script (`/pine-script`)
Prototypowanie, analiza wizualna oraz środowisko testowe na platformie TradingView.
* **Wskaźniki Statystyczne (v5):** Narzędzia filtrujące szum rynkowy na podstawie zaawansowanych wyliczeń matematycznych.
* **Systemy Backtestingowe:** Strategie intraday zaimplementowane w celu weryfikacji hipotez rynkowych na danych historycznych.

### 📊 MQL5 (`/mql5`)
Warstwa egzekucyjna i produkcyjna dla platformy MetaTrader 5.
* **Expert Advisors (EAs):** W pełni autonomiczne roboty handlowe realizujące założenia systemów matematycznych.
* **Moduły Zarządzania Ryzykiem:** Biblioteki odpowiedzialne za dynamiczne kalkulowanie wielkości pozycji, kontrolę obsunięć (drawdown) oraz trailing stopy.

---

## 💻 Stack Technologiczny

* **Języki programowania:** Python, Pine Script (v5), MQL5
* **Analiza danych & Ekonometria:** Pandas, NumPy, Statsmodels, SciPy
* **Komunikacja:** REST API, WebSockets, Git

---

## 📈 Metodologia i Podejście Rynkowe

Głównym założeniem projektów jest eliminacja czynnika uznaniowego na rzecz przewagi statystycznej i rygorystycznej kontroli ryzyka. Każda strategia przed wdrożeniem przechodzi proces backtestingu uwzględniający koszty transakcyjne, poślizgi cenowe (slippage) oraz płynność arkusza zleceń. Kluczowymi metrykami efektywności kodu są dla mnie Profit Factor, Sharpe Ratio oraz maksymalny Drawdown, a nie wyłącznie nominalna stopa zwrotu.

---

*Disclaimer: Materiały zawarte w tym repozytorium mają charakter wyłącznie badawczo-edukacyjny i nie stanowią rekomendacji inwestycyjnych.*
