# Fixed Income ML & Strategy Demo

This repository contains a demonstration notebook for fixed income analysis and strategy.  
It showcases a simple top-down pipeline: data ingestion, macro + yield curve features, ML forecasting, strategy construction, and risk assessment.

---

## Contents

- **FI_ML_Challenge.ipynb**  
  Main Jupyter Notebook with code + outputs (charts & summary).
- **requirements.txt**  
  Dependencies needed to re-run the notebook.
- **README.md**  
  This description.

---

## Notebook Highlights

- Synthetic (or optional real) data loading
- PCA factors for yield curve (level, slope, curvature)
- Ridge regression forecast of next-month 2s10s slope
- DV01-neutral 2s10s trade construction
- Risk metrics: VaR, Expected Shortfall, Drawdown
- Client-style executive summary

---

## How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/FI_ML_Challenge.git
   cd FI_ML_Challenge
