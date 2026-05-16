# impact-of-Inflation-on-Exchange-Rates-INR-USD-1980-2024-Data-Analytics-

An empirical data analytics project examining the macroeconomic relationship between inflation rates and currency exchange movements between India and the United States, using the foundational theory of **Purchasing Power Parity (PPP)**.

## 📌 Project Overview
This project evaluates how structural inflation differentials drive long-term currency depreciation and appreciation patterns. By compiling and cross-examining 44 years of economic data (1980–2024), the project calculates directional correlations and maps true market trajectories against theoretical economic baselines to reveal deviations caused by broader market conditions.

## 👥 Authors & Contributors
* **Virgil Kalluvely** - University of Europe for Applied Sciences, Potsdam
* **Tekulapally Vamshi Abhishake** - University of Europe for Applied Sciences, Potsdam
* **Shaik Mohammed Feroz** - University of Europe for Applied Sciences, Potsdam
* **Rajeev** - University of Europe for Applied Sciences, Potsdam
* **Deepu Kushwaha** - University of Europe for Applied Sciences, Potsdam

## 🎯 Core Objectives
1. **Trend Analysis:** Map and isolate individual historical trajectories for the INR/USD exchange rate alongside inflation metrics in both India and the US.
2. **Correlation Matrix:** Measure and quantify the linear strength and direction between shifting domestic prices and shifting currency values.
3. **Theory Validation:** Verify if the Purchasing Power Parity (PPP) theory consistently reflects reality by generating a synthetic expected exchange rate model based on inflation differentials.
4. **Deviation Analysis:** Identify and analyze historical anomalies where the actual currency valuation heavily decoupled from theoretical expectations.

## 🛠️ Tech Stack & Dependencies
* **Language:** Python 3.x
* **Environment:** Jupyter Notebook
* **Data Manipulation:** `pandas`, `numpy`
* **Interactive Visualizations:** `plotly` (`graph_objs`, `make_subplots`)

## 📊 Dataset Structure
The analytical workflow utilizes two historical CSV datasets:
* `Inflation_Rates_Transformed.csv`: Yearly baseline consumer price index/inflation adjustments across international entities.
* `USD_INR_Exchange_Rates_1980_2024.csv`: Historical value metrics tracking the value of one US Dollar priced in Indian Rupees.

## ⚙️ Analytical Workflow
1. **Data Preprocessing & Filtering:** Isolate regional metrics corresponding to India and the United States, pivot data fields into clear temporal series indexed by year, and perform inner merges to maintain database alignment.
2. **Descriptive & Exploratory Analysis:** Isolate mean variance boundaries, check distributions, and extract temporal patterns across four decades.
3. **Mathematical Compounding:** Model cumulative product structures to dynamically generate the theoretical PPP expected rate over time ($E_t$).
4. **Interactive Dashboard Plotting:** Render detailed time-series charts contrasting actual market performance against mathematical predictions.

## 💡 Key Insights
* **Inflation-Driven Depreciation:** A strong, distinct positive correlation confirms that higher relative domestic inflation inside India consistently corresponds to the long-term depreciation of the INR against the USD, aligning safely with basic economic principles.
* **Asymmetric Inflation Impact:** While India's inflation dynamics strongly anchor currency values, fluctuations in US inflation exhibited a noticeably weaker, lower correlation on isolated nominal exchange values over the calculated timeline.
* **Theoretical Decoupling (PPP Deviations):** Empirical calculations indicate the Indian Rupee has remained structurally undervalued relative to pure theoretical PPP predictions, mathematically confirming that secondary pressures—like trade balances, capital flows, and macro-monetary policies—exert significant influence.

## 🚀 Future Enhancements
* **Time-Lag Embeddings:** Implement lag variables to assess whether current price-level shifts dictate exchange movements downstream with distinct time delays.
* **Econometric Time-Series Forecasting:** Deploy advanced statistical models (such as Vector Autoregression (VAR) or Cointegration models) to capture dynamic, time-varying relationships.
* **Machine Learning Extension:** Incorporate ML frameworks (e.g., Random Forest Regressor or LSTM networks) to transition from retrospective analysis into active currency trend forecasting.

## 🙏 Acknowledgments
We express our gratitude to **Dr. Talha Ali Khan** for his data analytics guidance, domain insights, and encouragement throughout the drafting of this study.
