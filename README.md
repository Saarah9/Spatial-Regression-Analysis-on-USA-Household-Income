# Spatial-Regression-Analysis-on-USA-Household-Income
This project performs spatial regression analysis and visualization on median household income data across the United States. It uses Python libraries such as `geopandas`, `pysal`, `esda`, and `scikit-learn` to explore spatial relationships and perform statistical modeling.
## Features
- Moran's I computation for spatial autocorrelation.
- Spatial autoregressive (SAR) model estimation using `pysal`.
- Ridge regression for regularized modeling.
- Geospatial visualization of predicted values.

## Data Requirements
- **Shapefile**: USA state boundaries (`shapefile/` directory).
- **Household Income Data**: Median household income in Excel format (`Median household income.xlsx`).

## Dependencies
Install the required Python packages:
```bash
pip install pandas numpy geopandas matplotlib pysal scikit-learn
