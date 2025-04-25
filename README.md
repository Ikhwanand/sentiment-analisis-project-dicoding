# Indodax App Reviews Sentiment Analysis

## Project Overview

This project performs sentiment analysis on Indodax cryptocurrency exchange mobile app reviews from the Google Play Store. The goal is to understand user sentiments and feedback by classifying reviews as positive or negative.

## Key Features

- **Data Collection**: Scrapes reviews for the Indodax app using `google_play_scraper`
- **Text Preprocessing**: 
  - Cleans and normalizes Indonesian text
  - Handles slang words and informal language
  - Removes stopwords and performs text normalization
- **Sentiment Classification**: Uses machine learning techniques to classify review sentiments

## Project Structure

```
sentiment-analisis-project/
│
├── data/           # Collected review data
├── models/         # Trained sentiment classification models
└── notebooks/      # Jupyter notebooks with analysis and model development
    └── Sentiment_analysis_indodax.ipynb
```

## Requirements

- Python 3.8+
- Libraries:
  - google_play_scraper
  - Sastrawi (Indonesian text processing)
  - pandas
  - scikit-learn
  - numpy

## Installation

1. Clone the repository
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

Open the Jupyter notebook `notebooks/Sentiment_analysis_indodax.ipynb` to explore the analysis and sentiment classification process.

## Key Insights

- Analyzed over 60,000 Indodax app reviews
- Developed text preprocessing pipeline for Indonesian language
- Created sentiment classification model

