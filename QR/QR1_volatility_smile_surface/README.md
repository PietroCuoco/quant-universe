# QR1 — Volatility Smile and Surface Analysis

## Objective
Construct and analyze implied volatility smiles and surfaces from listed options:
- Extract implied volatilities from market option quotes.
- Fit an arbitrage-aware IV surface.
- Study smile/skew behaviour across maturities and underlyings.
- Relate smile features to underlying returns and realized volatility.

## Universe (initial)
- SPX index options
- TSLA, NVDA, JPM single-name options

## Structure
- `data/`: raw and cleaned option chain and underlying data.
- `notebooks/`:
  - `01_download_clean_data.ipynb`
  - `02_compute_iv.ipynb`
  - `03_surface_fitting.ipynb`
  - `04_smile_analysis.ipynb`
- `src/`: source code for BS pricing, IV solvers, surface fitting, and plotting.
- `report/`: LaTeX report and final figures.
