This project provides machine learning code and data for forecasting national-level emissions of halogenated polycyclic aromatic hydrocarbons (XPAHs) using an XGBoost regression model, coupled with Monte Carlo simulation for uncertainty estimation. The operating environment is Windows 11 with Python 3.9 and JupyterLab 4.0.11. Required packages include pandas, numpy, matplotlib, and scikit-learn, all of which can be installed via pip. The software can be conveniently set up through Anaconda Navigator, downloadable via Microsoft Edge, and typically installs within 10 minutes on a standard computer. A full demonstration is provided in this GitHub repository.

Dataset overview:
Data_S1: Modeling dataset covering 95 countries and 23 predictive variables

Data_S2: Forecast dataset containing data from 89 countries to be predicted

Data_S3: Output from Monte Carlo simulations showing prediction uncertainty

Code contents:
Final XGBoost model with uncertainty estimation

Comparative models using LightGBM, Random Forest, and Support Vector Regression (SVR)

This repository allows users to reproduce the XPAH emission forecasts presented in the manuscript, including all relevant data processing, model training, evaluation, and visualization steps.
