# Relative-Valuation
This project applies machine learning techniques to estimate relative valuation multiples using financial data from [WRDS](https://wrds.wharton.upenn.edu/), specifically the Compustat database. Drawing inspiration from Geertsema, Paul, and Helen Lu's paper ["Relative Valuation with Machine Learning"](https://onlinelibrary.wiley.com/doi/full/10.1111/1475-679X.12435) (*Journal of Accounting Research*, 2023), we implemented machine learning models to predict valuation multiples based on firm-specific financial variables.

1. variable_const_v1: Variable source is Compustat, merged with CRSP using CUSIP by first converting GVKEY to CUSIP
2. variable_const_v2: variables source: Variable source is the merged CRSP/Compustat dataset
3. variable_const_v3: variables source: Variable source is the WRDS ratio suite

file link: https://drive.google.com/drive/folders/1tMVt5nltb1W6Y-k4QRldX-D9yQP1OC5P?usp=sharing