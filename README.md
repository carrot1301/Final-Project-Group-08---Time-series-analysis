# 🏠 Housing Loan Outstanding Balance Forecasting

### Group 08 - Final Year Project | UEF
**Author:** Doan Nguyen Tri (Data Analyst)

## 📖 Project Overview
This project focuses on analyzing and forecasting the **Outstanding Balance of Housing Loans** for a commercial bank. Accurate forecasting of loan balances is critical for:
* **Liquidity Management:** Ensuring the bank has sufficient capital to meet obligations.
* **Risk Mitigation:** Identifying trends in credit growth and potential saturation.
* **Strategic Planning:** Setting targets for future credit growth.

## 📂 Repository Contents

| File Name | Description |
| :--- | :--- |
| **`Group08_FinalReport_SourceCode.ipynb`** | 📈 **R Notebook:** The Jupyter Notebook (running R Kernel on Google Colab) containing data cleaning, decomposition, and forecasting models. |
| **`Group08_FinalReport.pdf`** | 📄 **Full Report:** The complete thesis documenting the theoretical framework, model selection process, and detailed error analysis. |
| **`Group08_FinalReport_Presentation.pdf`** | 📊 **Slides:** Executive summary presentation highlighting key findings and business recommendations. |

## 🛠 Methodology & Tools
* **Environment:** Google Colab (R Kernel) / Jupyter Notebook
* **Language:** **R**
* **Key Libraries:**
    * `tidyverse` (Data Manipulation & Visualization)
    * `forecast` (ARIMA, ETS, Holt-Winters models)
    * `tseries` (Stationarity Tests / ADF)
    * `ggplot2` (Advanced Plotting)
    * `zoo` / `xts` (Time series objects handling)

## 📊 Modeling Approach
1.  **Data Preprocessing:** Handling missing values and converting data to Time Series objects (`ts`).
2.  **EDA & Decomposition:** Analyzing Trend, Seasonality, and Random components using STL decomposition.
3.  **Stationarity Test:** Conducting Augmented Dickey-Fuller (ADF) tests.
4.  **Forecasting Models:**
    * ARIMA / SARIMA (Auto-Regressive Integrated Moving Average)
    * Exponential Smoothing (Holt-Winters)
5.  **Evaluation:** Comparing models based on RMSE (Root Mean Squared Error) and MAPE.

## 👤 About the Author
**Doan Nguyen Tri**
* **University:** Ho Chi Minh City University of Economics and Finance (UEF)
* **Major:** Data Science (Financial Data Analysis)
* **Certifications:**
    * Google Data Analytics Professional Certificate
    * Google Business Intelligence Professional Certificate
* **Contact:** doantri12343@gmail.com

---
*Disclaimer: This project is for educational and research purposes as part of the academic curriculum at UEF.*
