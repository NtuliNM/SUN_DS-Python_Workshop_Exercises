# SUN Data Science with Python Workshop — Exercises

Exercises (notebooks) completed during the **"Introduction to Data Science Using Python"** workshop - A free 5-day online bootcamp run by the [School for Data Science and Computational Thinking](https://www.dataschool.sun.ac.za) at Stellenbosch University on 07–11 September 2026.

The workshop built up from basic Python programming to introductory machine learning, covering:

- Fundamental Python programming concepts
- Data manipulation and analysis with `pandas`
- Data visualization with `matplotlib` and `seaborn`
- Sampling, chance, and statistical inference
- Confidence intervals, correlation, and causality
- Basic machine learning (regression, classification, decision trees) with `scikit-learn`

## Repository structure

```
Day 1 Scripts/    Data types, tables, groups & pivots, visualization
Day 2 Scripts/    Flowcharts, conditionals & iteration, functions, chance
Day 3 Scripts/    Sampling, comparing distributions, A/B testing
Day 4 Scripts/    Causality, confidence intervals, correlation
Day 5 Scripts/    Regression, classification, decision trees
Datasets/         CSV files used across the notebooks
```

Each `Day N Scripts` folder has its own README describing that day's sessions. Some days also contain a `Templates/` subfolder — these are the blank starter notebooks handed out before each session, alongside the versions worked through live.

## Getting started

The notebooks were built and run in Google Colab and load data with relative paths, e.g. `pd.read_csv('olympics2024.csv')`. To run a notebook locally:

1. Clone this repo.
2. Copy the CSV files it needs (see that day's README, or `Datasets/README.md`) into the same folder as the notebook, or update the `read_csv`/`read_excel` paths to point at `../Datasets/`.
3. Install the dependencies below and open the notebook in Jupyter.

**Dependencies:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `scikit-learn`, `plotly`

```bash
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn plotly
```

> Note: the Day 5 Decision Trees notebook (not yet uploaded) references `loan_data_sample.csv`, which wasn't part of the shared dataset pack — see `Datasets/README.md`.

## Acknowledgements

This bootcamp was run free of charge by the School for Data Science and Computational Thinking at Stellenbosch University and presented by:

- Prof. Kanshukan Rajaratnam (Director, School for Data Science and Computational Thinking)
- Dr. Sunday Oladejo
- Dr. Marike Visser
- Rumbidzai Mutangadura (PhD Candidate)

Session templates and datasets were provided by the School as course material; the notebooks in this repo reflect my own work through the exercises during the live sessions, shared here as a personal learning record.
