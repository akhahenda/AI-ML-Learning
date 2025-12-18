# Ship Emissions ML (AIS Points, 1 Month)

## Objective
Build ML models to predict:
1) HOURLY_EMISSIONS and/or
2) TOTAL_EMISSIONS

from vessel + operational features (e.g., SOG, RPM, engine load, TEU band, age, DWT).

## Data
AIS point-level dataset for container ships (1 month), columns include:
- date, mmsi, length, TEU_BAND, SUBTYPE, AGE, dwt, sog, rpm, engine_load
- hourly_emissions, segtime (occupancy time in hours), total_emissions

## Plan
1. Exploratory Data Analysis (EDA)
2. Baseline model
3. Feature engineering + model improvements
4. Evaluation + interpretation
5. (Optional) simple deployment (Streamlit)

## How to run
Will be added after environment setup.