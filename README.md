# EU Freight Emissions Analysis

This project analyzes the relationship between road freight transport activity and CO₂ emissions across EU countries.

## Objective
To investigate whether freight activity directly explains emissions, or whether structural differences between countries play a significant role.

## Methods
- OLS Regression (log-log model)
- Decision Tree Regression (non-linear modeling)
- Residual Analysis (country-level deviations)

## Key Findings

- Linear regression shows very low explanatory power (low R²)
- Emissions follow a non-linear pattern rather than a simple linear relationship
- A critical threshold (~140,000 tonne-km) was identified, beyond which emissions increase more rapidly
- High-volume countries such as Germany and France produce lower-than-expected emissions
- Significant heterogeneity exists across EU countries

## Insight

Freight emissions are not determined only by transport volume, but by how efficiently logistics systems are structured and managed.

## Tools
- Python (Pandas, NumPy)
- Statsmodels (OLS)
- Scikit-learn (Decision Tree)
- Matplotlib / Seaborn

## Author
Dilek Gökalp
