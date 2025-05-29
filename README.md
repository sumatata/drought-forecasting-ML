# Forecasting Drought Severity in U.S. Counties Using ML on Historical Weather Data (2011–2020)

##  Project Overview
This project applies machine learning to forecast drought severity levels in U.S. counties using historical weather data. Using weather features such as temperature, precipitation, wind speed, and humidity, the model predicts drought categories based on the U.S. Drought Monitor’s classification (D0–D4).

##  Data Sources
- **Meteorological Data**: NASA POWER Climate Data (2011–2020)
- **Drought Labels**: U.S. Drought Monitor
- **Granularity**: Weekly data by U.S. county (FIPS)

##  Methodology
- Merged drought and weather data by FIPS and week
- Feature engineering on key weather variables
- Class balancing using SMOTE
- Model training with XGBoost and comparison to baselines
- Evaluation via ROC AUC, accuracy, recall, and F1-score

## Key Results
- **Best Model**: SMOTE + XGBoost Classifier
- **ROC AUC**: 0.8187
- **Accuracy**: 80%
- **Recall (severe drought)**: 0.66
- Significantly improved detection of severe drought conditions

##  Author
**Suma Tata**  
MS in Data Science, University of Delaware  
