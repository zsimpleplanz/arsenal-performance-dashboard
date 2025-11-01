# Arsenal Football Performance Dashboard
[![Arsenal-Dashboard-0.jpg](https://i.postimg.cc/htJj5GHV/Arsenal-Dashboard-0.jpg)](https://postimg.cc/RWB43vC0)

Analyze Arsenal's Premier League performance across seasons with Python + Streamlit.


## Features
- Data ingestion from football-data.co.uk (multiple seasons)
- EDA: points by season, goals for/against trends
- Baseline Logistic Regression to predict win vs not-win
- Interactive Streamlit dashboard with KPIs and charts


## Quickstart
```bash
# 1) Setup
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
# source .venv/bin/activate


pip install -r requirements.txt


# 2) Get data
python src/data_ingest.py


# 3) (Optional) Train model
python src/train.py


# 4) Run dashboard
streamlit run src/app.py
