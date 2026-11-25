# SaaS Growth Engine

A planned analysis of SaaS company finances: benchmark churn, forecast recurring revenue and test what-if scenarios, with a Streamlit dashboard on top.

> **Status: planned, not built.** The repo holds the structure and the project plan. The notebook, the app and the report are placeholders, and the dataset is not included.

## The plan

1. **Clean the data** and compute annual recurring revenue (ARR), lifetime value (LTV), LTV to acquisition cost, and growth rates.
2. **Benchmark** churn by company size, ARR growth, and LTV to acquisition cost by quartile.
3. **Forecast** ARR and churn with Prophet, and test pricing, churn and acquisition cost scenarios, including Monte Carlo simulation.
4. **Build the dashboard** in Streamlit, with scenario sliders.

The full checklist is in [docs/project_plan.md](docs/project_plan.md).

## Data

[SaaS Financial Market Dataset](https://www.kaggle.com/datasets/tanishqpratap/saas-financial-market-dataset) on Kaggle, covering 500 companies. Download it and put it in `data/raw/`.

## Set up

Needs Python 3.

```bash
git clone https://github.com/Wammiri/saas-growth-engine-fpa.git
cd saas-growth-engine-fpa
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

There is nothing to run yet. Once the app exists it will start with `streamlit run app.py`.

## Project structure

```text
app.py          the Streamlit app (placeholder)
notebooks/      the analysis notebook (placeholder)
data/raw/       the dataset goes here
data/processed/ cleaned data
docs/           the project plan
reports/        the summary report (placeholder)
```

## Author

[Isaac Olorode](https://isaac.aperio.finance)
