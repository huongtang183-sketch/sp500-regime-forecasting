# Regime-Based Forecasting of S&P 500 Returns

## Overview
This project builds a regime-aware machine learning framework for forecasting equity market dynamics and managing risk.  
It constructs a Market Volatility Index (MVI) from macro-financial indicators, detects regime shifts in market structure, and predicts regime-dependent returns.  
The framework integrates predictive modeling and model explainability to improve transparency and interpretability in financial forecasting.

## Methods
- Market Volatility Index construction via :contentReference[oaicite:1]{index=1} (PCA)
- Regime shift detection using :contentReference[oaicite:2]{index=2} (BOCPD)
- Regime classification with :contentReference[oaicite:3]{index=3} and :contentReference[oaicite:4]{index=4}
- Feature attribution and model interpretation with :contentReference[oaicite:5]{index=5}
- Evaluation of regime-conditioned dynamic risk allocation strategies

## Results
- Clear segmentation of market regimes over time  
- Regime-aware models outperform static benchmarks in directional forecasting accuracy  
- SHAP analysis reveals dominant macro-financial drivers within each regime  
- Risk-adjusted returns improve under regime-conditioned allocation

## How to Run
1. Clone this repository  
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn xgboost shap matplotlib
