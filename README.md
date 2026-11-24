# DTS201-GroupJ: Nigerian Food Price Prediction & Analysis

## Project Summary
This repository presents our end-to-end **DTS201 (Group J)** data science project analyzing and forecasting monthly staple food prices in Nigeria to help households anticipate food costs and plan budgets. Using a strict chronological train/test split (`Year <= 2025` for training and `Year == 2026` for out-of-sample testing) to prevent time-series data leakage, we built a per-item calendar-month seasonal baseline model and evaluated its accuracy across 14 staple food items using **Mean Absolute Error (MAE)** and **Root Mean Squared Error (RMSE)**.

### Group Members (Group J)
* Chifumnaya Omefe
* Oshiokeme Williams
* Chetachi Madiebo
* Stanley Chukwuemeka

*(Note: Matriculation numbers are intentionally excluded from this public repository and slides.)*

---

## Repository Contents
* `data/` — Raw and cleaned food price datasets (including `cleaned_foodprice_2024_2026.csv`, covering 238 monthly records across 14 staple items).
* `notebooks/` — Jupyter notebooks for data cleaning, regex state/price extraction, exploratory data analysis (`eda_seasonality`), seasonal baseline modeling, and out-of-sample evaluation.
* `docs/` — Supporting project documentation, notes, and model updates.
* `outputs/` — Generated evaluation metrics, forecast tables, and analysis outputs.
* `requirements.txt` — Python libraries required to reproduce the analysis and modeling notebooks.
* `README.md` — Project overview, setup instructions, and repository guide.

---

## How to Run the Code

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd DTS201-GroupJ
   ```

2. **Create and activate a virtual environment (recommended):**
   ```bash
   python -m venv .venv
   source .venv/bin/activate      # On Windows: .venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter and run the notebooks in order:**
   ```bash
   jupyter notebook
   ```
   Open the notebooks in `notebooks/` to inspect/run data preparation, exploratory analysis, seasonal forecasting, and 2026 evaluation (`MAE` and `RMSE`).# DTS201-GroupJ
Data Science Project for Group J-Chifumnaya, Oshioke, Chetachi, Stanley
