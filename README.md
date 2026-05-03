# Airlines Delay Prediction

A Machine Learning system designed to predict flight delays by fusing real-time flight data, meteorological conditions, and news sentiment analysis.

## Project Overview
This project aims to go beyond traditional scheduling data by incorporating:
- **Weather Impact:** Real-time data from OpenWeather API.
- **Social Context:** News sentiment analysis (NLP) to detect strikes or technical issues.
- **Advanced Modeling:** Using XGBoost/RandomForest and MLflow for tracking.

## Structure
- `/src`: Source code for ingestion, processing, and modeling.
- `/docs`: Project Charter and technical documentation.
- `/notebooks`: Exploratory Data Analysis (EDA).
- `/tests`: Unit tests for data validation.

## Setup
1. **Environment:** `.\venv\Scripts\activate`
2. **Dependencies:** `pip install -r requirements.txt`
3. **Configuration:** Create a `.env` file with your API keys.
