# 📊 DCF Valuation Model & Screening Tool

**An advanced Excel-based financial model for Discounted Cash Flow (DCF) valuation, complete with real-time screening, automated analysis, and professional-grade insights.**

---

## 🚀 Overview

This integrated **DCF valuation model** offers a powerful framework for evaluating companies using systematic cash flow projections, WACC calculations, and terminal value methodologies. Built with automation and flexibility in mind, it enables real-time screening across multiple companies and is designed for both individual analysts and institutional workflows.

---

## 🧩 Key Features

### 💼 Core Valuation Components

* **5-Year Financial Projections**: Forecasted income statement, balance sheet, and cash flows
* **WACC Calculation Engine**: Peer-based cost of capital estimation
* **Terminal Value Estimation**: Both perpetual growth and exit multiple methods
* **Sensitivity Analysis**: Dynamic stress testing across key variables

### ⚙️ Advanced Capabilities

* **Live Market Data Connectivity** *(manually updatable)*
* **Multi-Company Screening**: Run valuations across multiple firms simultaneously
* **ROIC & Reinvestment Modeling**: Analyze capital efficiency and growth drivers
* **Intrinsic vs Market Value**: Clear premium/discount comparisons

---

## 🗂️ Model Structure

```bash
DCF_Valuation_Model/
├── Main_Dashboard.xlsx
├── Company_Inputs/
│   ├── Financial_Data_Input.xlsx
│   ├── Assumptions_Sheet.xlsx
│   └── Market_Data_Feed.xlsx
├── Calculations/
│   ├── WACC_Calculator.xlsx
│   ├── FCF_Projections.xlsx
│   ├── Terminal_Value.xlsx
│   └── Sensitivity_Analysis.xlsx
├── Outputs/
│   ├── Valuation_Summary.xlsx
│   └── Comparative_Analysis.xlsx
└── Documentation/
    ├── Model_Guide.pdf
    └── Assumptions_Log.xlsx
```

---

## 🛠️ Getting Started

### 📋 Prerequisites

* Microsoft Excel 2016 or later
* Basic understanding of financial modeling
* Company annual reports or market data

### ⚙️ Installation & Setup

1. Download the complete model package
2. Enable Excel macros
3. Set up live feeds in `Market_Data_Feed.xlsx`
4. Customize variables in `Assumptions_Sheet.xlsx`

---

## 📈 How to Use

### 🔍 Basic Valuation Steps

1. **Input historical data** in `Financial_Data_Input.xlsx`
2. **Set assumptions** for growth, margins, cap structure
3. **Run valuation** via `Main_Dashboard.xlsx`
4. **Analyze results** in `Valuation_Summary.xlsx`

### 🧠 Advanced Tools

* **Screening Mode**: Simultaneous multi-firm analysis
* **Scenario Planning**: Adjust variables for risk cases
* **Peer Benchmarking**: Compare WACC & multiples industry-wide

---

## 📐 Technical Specifications

| Parameter         | Default  | Customizable   |
| ----------------- | -------- | -------------- |
| Projection Period | 5 Years  | Up to 10 Years |
| Terminal Growth   | 2–4%     | Yes            |
| WACC              | Dynamic  | Yes            |
| Sensitivity Range | ±200 bps | Yes            |

**Key Formulas:**

* FCF = EBIT(1-T) + Dep – CapEx – ΔNWC
* WACC = (E/V × Re) + (D/V × Rd × (1–T))
* TV = FCF × (1+g) / (WACC – g)

---

## 🧾 Sample Output

| Metric                | Value    | Market Comparison     |
| --------------------- | -------- | --------------------- |
| Intrinsic Value/Share | ₹1,010.2 | Market: ₹1,825        |
| Upside/Downside       | -44.6%   | Overvalued            |
| WACC                  | 15.65%   | Industry Avg: 14.2%   |
| Terminal Growth Rate  | 6.50%    | Conservative Estimate |
| ROIC                  | 47.22%   | High Efficiency       |

---

## 🔎 Model Validation

* ✅ **Back-Testing** on historical data
* ✅ **Peer Benchmarking** against analyst models
* ✅ **Stress Tested** for sensitivity
* ✅ **Real Use Cases** in valuation decisions

---

## ⚠️ Limitations

* Dependent on input accuracy
* High weight of terminal value in output
* Not intended for short-term trading
* Manual market updates (unless API linked)

---

## 📌 Planned Enhancements

* API integration for real-time data
* Monte Carlo simulation module
* Smart peer benchmarking with scraping
* AI-generated assumption suggestions

---

## 👨‍💼 Contact

**Nishchay Chaudhary**
*Financial Strategy Analyst*
📧 [nishchaychaudhary.dce@gmail.com](mailto:nishchaychaudhary.dce@gmail.com)
🔗 [LinkedIn Profile](https://www.linkedin.com/in/nishchay-chaudhary-20b520314/)

---

## 📜 Disclaimer

This model is for educational and analytical use. Investment decisions should be based on complete due diligence. Output accuracy depends on data quality and assumptions used.

---

> **Built with Excel | Designed for Analysts | Continuously Evolving**
