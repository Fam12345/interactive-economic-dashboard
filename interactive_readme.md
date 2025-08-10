# interactive economic dashboard

A modern Streamlit dashboard for exploring and forecasting key macroeconomic indicators across countries.  This project blends rigorous data science—time‑series cleaning, feature engineering, and forecasting—with robust ML engineering, packaging the analytics into a modular, interactive web application.

## data science

- Aggregated historical GDP and other economic indicators from public sources (World Bank, IMF) and cleaned for consistency across countries and years.
- Engineered features such as year‑over‑year growth, moving averages, and economic ratios.
- Implemented baseline forecasting models (ARIMA, Prophet) for GDP projections and evaluated accuracy with cross‑validation.

## ml engineering

- Built a Streamlit interface that allows users to select countries and indicators, visualize trends, and compare forecasts interactively.
- Modularized data ingestion, processing, and visualization in `streamlit_app.py` for maintainability.
- Included a `requirements.txt` for reproducible environments and a placeholder GitHub Actions workflow for continuous deployment (optional).

## repository structure

| path | description |
| --- | --- |
| `streamlit_app.py` | Main Streamlit application code handling data loading, forecasting, and interactive plots |
| `requirements.txt` | Python dependencies |
| `data/` | Contains the raw datasets used by the dashboard |
| `.github/` | CI/CD workflow templates (optional) |
| `README.md` | Project overview (this document) |

## running the app locally

```bash
git clone https://github.com/Fam12345/interactive-economic-dashboard.git
cd interactive-economic-dashboard
pip install -r requirements.txt
streamlit run streamlit_app.py
```

Open the provided local URL in your browser and explore the interactive visualizations and forecasts.
