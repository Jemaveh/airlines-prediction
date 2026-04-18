# Project Charter - DST Airlines

## 1. Discovery (The Why)
Flight delays represent a massive cost for the aviation industry and a major pain point for passengers. Existing models often fail to capture external "soft" factors like strikes or technical incidents mentioned in news reports.

## 2. Solution (The What)
The goal is to develop a data pipeline that integrates real-time flight schedules, weather reports, and news sentiment analysis. Using NLP (BERT), we will quantify news impact to refine delay predictions.

## 3. Business Value (The Value)
- **Predictive Accuracy:** Merging environmental and social data for better forecasting.
- **Explainability:** Providing context for delays (e.g., "predicted delay due to weather + airport staff strike").
- **Innovation:** Using RAG (Retrieval Augmented Generation) to query technical news context.