# Project Plan: SaaS Growth Engine FP&A Dashboard

This document outlines the workflow for building the **SaaS Growth Engine: Revenue Forecasting & Churn Optimization Dashboard**.  
The project is structured to showcase data-driven FP&A skills for SaaS companies, from raw data through forecasting and interactive dashboards.

---

## Workflow Breakdown

### 1. Project Setup & Environment
- [ ] Create GitHub repo (`saas-growth-engine-fpa`)
- [ ] Add README with project overview
- [ ] Setup Jupyter notebook (`notebooks/saas_fp_a_analysis.ipynb`)
- [ ] Install required libraries via `requirements.txt`

---

### 2. Data Acquisition & Preparation
- [ ] Download Kaggle dataset: SaaS Financial Market Dataset
- [ ] Load into notebook
- [ ] Inspect columns and data types
- [ ] Clean data:
  - Handle missing values
  - Remove duplicates
  - Standardize formats (dates, percentages, currency)
- [ ] Create derived metrics:
  - ARR = MRR × 12
  - LTV = ARR / Churn Rate
  - LTV:CAC ratio
  - Growth rate (YoY, MoM)
- [ ] Save cleaned dataset to `data/processed/`

---

### 3. Exploratory Data Analysis (EDA) & Benchmarking
- [ ] Visualize ARR growth distribution
- [ ] Analyze churn by company size
- [ ] Quartile analysis of LTV:CAC ratio
- [ ] Correlation studies:
  - Funding vs ARR
  - CAC vs churn
  - ARR growth vs employee count
- [ ] Define SaaS benchmarks:
  - Median churn, top-quartile churn
  - Median CAC, top-quartile LTV:CAC
- [ ] Summarize key insights

---

### 4. Forecasting & Scenario Analysis
- [ ] Aggregate dataset by median company metrics
- [ ] Forecast ARR with Prophet (2025–2027)
- [ ] Forecast churn with Prophet
- [ ] Build what-if scenarios:
  - Pricing increase (+10%) → ARR impact
  - Churn reduction (–2%) → LTV/CAC improvement
- [ ] Monte Carlo simulation for ARR under churn variability
- [ ] Create variance/sensitivity tables

---

### 5. Dashboard Development (Streamlit)
- [ ] Setup `app.py`
- [ ] Create layout:
  - Tab 1: Overview & benchmarks
  - Tab 2: ARR forecast
  - Tab 3: Scenario analysis
- [ ] Add interactive Plotly charts
- [ ] Add KPI cards (ARR, churn %, LTV:CAC)
- [ ] Deploy to Streamlit Cloud
- [ ] Add demo link to README

---

### 6. Documentation & Polish
- [ ] Finalize README with:
  - Overview
  - Dataset info
  - Key findings
  - Tech stack
  - How to run locally
  - Live demo link + screenshots
- [ ] Export Jupyter notebook to PDF
- [ ] Write one-page executive summary memo
- [ ] Upload final repo files:
  - Notebook
  - App.py
  - requirements.txt
  - Screenshots
- [ ] Highlight project on resume & LinkedIn

---

✅ *This document serves as the project roadmap. Progress can be tracked by checking off items as they are completed.*
