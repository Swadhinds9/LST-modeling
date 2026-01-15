# Land Surface Temperature (LST) Modeling using Machine Learning

This project models monthly Land Surface Temperature (LST) using environmental, urban, and climatic variables from 2000–2023.

## Data
Variables include:
- Methane emission
- NDVI, NDBI
- Specific humidity
- Waste
- Wind speed
- LST (target)

## Methods
Models used:
- Linear Regression
- Ridge Regression
- Random Forest
- Gradient Boosting

Feature engineering:
- Urbanization index (NDBI − NDVI)
- NDBI²
- Waste / humidity

## Results
Best model: **Random Forest**

Performance:
- R² ≈ 0.72

Most important predictors:
1. Specific humidity
2. Wind speed
3. NDVI

## Files
- `LST_modeling.ipynb` – full analysis
- `LST.csv` – dataset
- `figures/` – output plots

