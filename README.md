# Regime-Based Forecasting of S&P 500 Returns

## Overview
This project builds a regime-aware machine learning framework for forecasting equity market dynamics and managing risk.  
It constructs a Market Volatility Index (MVI) from macro-financial indicators, detects regime shifts in market structure, and predicts regime-dependent returns.  
The framework integrates predictive modeling and model explainability to improve transparency and interpretability in financial forecasting.

## Methods
- Market Volatility Index construction via Principal Component Analysis (PCA)
- Regime shift detection using Bayesian Online Change Point Detection (BOCPD)
- Regime classification with Logistic Regression and XGBoost
- Feature attribution and model interpretation with SHAP
- Evaluation of regime-conditioned dynamic risk allocation strategies

## Results
- Clear segmentation of market regimes over time  
- Regime-aware models outperform static benchmarks in directional forecasting accuracy  
- SHAP analysis reveals dominant macro-financial drivers within each regime  
- Risk-adjusted returns improve under regime-conditioned allocation

## Repository Structure
