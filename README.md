# 📊 Hindustan Unilever Limited — Equity Research & Financial Modelling

> A comprehensive, end-to-end financial analysis of Hindustan Unilever Limited (HUL), 
> covering historical financial modelling, intrinsic valuation, relative valuation, 
> Football-field Analysis and Python-automated WACC computation using live market data.

---

## 🔍 Project Overview

This project presents a full-scale equity research analysis of Hindustan Unilever 
Limited — India's largest Fast-Moving Consumer Goods (FMCG) company. The analysis 
spans nine years of historical financial data (FY2017–FY2025) and culminates in a 
multi-method valuation framework encompassing a Discounted Cash Flow model, 
Comparable Company Analysis, Sensitivity Analysis, and a Football Field valuation chart.

The project was built entirely from scratch, integrating Excel-based 
financial modelling with Python automation and live market data — reflecting a 
real-world analyst workflow.

---

## 💡 Why HUL?

HUL operates across three well-defined FMCG segments — Home Care, Beauty & Personal 
Care, and Foods & Refreshment — making it an ideal candidate for segment-level 
analysis. As India's most recognised consumer staples company, HUL offers rich 
data availability, strong comparability with domestic and global peers, and a 
valuation story that is both analytically nuanced and interview-relevant.

---

## 🗂️ Project Components

| Component | Description |
|---|---|
| 📋 3 Statement Financial Model | Linked Income Statement, Balance Sheet, and Cash Flow Statement covering FY2017–FY2025 |
| 📈 ROIC & Reinvestment Analysis | Return on Invested Capital and reinvestment rate framework used to anchor DCF assumptions |
| ⚖️ WACC | Weighted Average Cost of Capital derived from first principles using bottom-up beta methodology |
| 💰 DCF Model | 5-year FCFF projection with terminal value, equity bridge, and implied share price |
| 🎯 Sensitivity Analysis | Two-variable sensitivity table — WACC vs Terminal Growth Rate |
| 🏢 Comparable Company Analysis | EV/EBITDA, EV/Revenue, and P/E multiples across six domestic peers |
| 🏈 Football Field Analysis | Python-generated horizontal bar chart summarising valuation ranges across all methods |
| 🤖 WACC Automation Script | Python script that pulls live price data, calculates beta via regression, and computes WACC end-to-end |
| 📄 Model Documentation | Technical methodology note explaining assumptions, data sources, and analytical decisions |

---

## 🛠️ Tools & Skills

- 📗 **Excel** — Financial modelling, DCF, sensitivity analysis, comparable company analysis
- 🐍 **Python** — Pandas, NumPy, Matplotlib, yfinance
- 🧠 **Financial Concepts** — DCF, WACC, Beta (Blume adjustment, unlevering/relevering), Financial-statement Analysis,
ROIC, Terminal Value, EV/EBITDA, Football Field Analysis

---

## 📌 Key Findings

- 💹 **DCF Implied Price: ₹673** vs Current Market Price of ₹2,309 — a **3.43x premium**
- ✅ **EV/EBITDA** suggests HUL is marginally **undervalued** relative to domestic peers 
  at 34.5x vs peer median of 35.1x
- ⚠️ **EV/Revenue** suggests HUL carries a **revenue premium** at 8.5x vs peer median 
  of 7.7x, reflecting its superior margin profile
- 🔎 The valuation gap between DCF and market price reflects HUL's structurally low 
  reinvestment rate (median 6.99%), decelerating revenue growth (2% in FY2024–25), 
  and an intrinsic growth rate of just 1.45% — suggesting the market is pricing in 
  a growth recovery that operational data does not yet support
- 📉 **WACC: 12.28%** derived using bottom-up beta of 0.912, ERP of 5.90% via geometric 
  mean methodology, and AAA credit rating based cost of debt

---

## 🖼️ Screenshots

### 💸 Discounted Cash Flow Statement (DCF)
### 💸 DCF Model — Projections
<img width="1128" height="778" alt="image" src="https://github.com/user-attachments/assets/498bcc9e-9884-467f-bbef-a7a1b5aea6f7" />

### 💸 DCF Model — Valuation Output
<img width="460" height="642" alt="image" src="https://github.com/user-attachments/assets/e16edc0f-251e-4866-a5d1-370ea7dbad4d" />

### 🎯 Sensitivity Analysis
<img width="1116" height="699" alt="image" src="https://github.com/user-attachments/assets/86e133b2-ae5c-496b-9869-71b7726ab734" />

### 🏢 Comparable Company Analysis
<img width="1639" height="739" alt="image" src="https://github.com/user-attachments/assets/dbe9dcb4-a75c-48ef-ab4b-9da778ea701a" />

### 🏈 Football Field Valuation Analysis
<img width="1856" height="923" alt="image" src="https://github.com/user-attachments/assets/1b1b0bdc-e2eb-430e-adcb-8388a66fb7a6" />


---

## 📁 Files in this Repository

| File | Description | Link |
|---|---|---|
| `Hind__Unilever.xlsx` | Complete financial model | [View on Google Drive](https://docs.google.com/spreadsheets/d/1d5Z_3lZDXx5eR-Gue-VheOlVb2TmFlFW/edit?usp=sharing&ouid=100911399564110374078&rtpof=true&sd=true) |
| `WACC_Automation.ipynb` | Python notebook — automated WACC calculation | [View in Google Colaboratory](https://colab.research.google.com/drive/1HcBVc29tIlDNgufFTVV6Yv0D1r59E99E?usp=sharing) |
| `hul_football_field.png` | Football field valuation chart | [View in Google Colaboratory](https://colab.research.google.com/drive/1JtAVWe2wI1BaG61j1MkL4zrp9H6xn1f4?usp=sharing) |
| `HUL_Model_Documentation.pdf` | Technical documentation | [HUL_Financial_Model_Documentation](https://drive.google.com/file/d/1sznhsWiBveWjLZssmoIkhWPyJeAozSpH/view?usp=sharing) |

---

## ▶️ How to Run the Python Script

1. Open `WACC_Automation.ipynb` in Google Colab or Jupyter Notebook
2. Install dependencies — `pip install yfinance pandas numpy`
3. Run each cell sequentially
4. Enter the prompted inputs — risk free rate, market returns, cost of debt, 
   tax rate, company tickers, market cap, debt figures, and date range
5. The script will fetch live price data, compute beta, and output the final WACC

---

## 👤 Author

**Nasim Ul Jilani Memon**
🏅CFA L1 Aspirint |
📉 NISM Series XV — Research Analyst | NISM Series VIII — Equity Derivatives  
🐍 Python | 📗 Excel | 🗄️ SQL | 📊 Power BI  
✍️ Finance Writer on Substack

[🔗 LinkedIn](https://www.linkedin.com/in/nasim-ul-jilani-memon-907417318/) | [✍️ Substack](https://substack.com/@1nfallible)# HUL-Financial-Analysis
End-to-end equity research and financial modelling project on Hindustan Unilever Limited — DCF, Comps, WACC automation in Python, and Football Field Analysis
