# **Stock Market Predictions with Neural Network - Powered Social Media Sentiment Analysis**

## **Overview**
This project explores the integration of social media sentiment analysis with traditional stock market forecasting to improve prediction accuracy. Using deep learning techniques like LSTM (Long Short-Term Memory) and machine learning models, we assess how Twitter sentiment impacts stock price movements.

## **Problem Statement**
Traditional stock market forecasting methods rely heavily on historical price data and technical indicators, overlooking real-time market sentiment expressed on social media. This project bridges that gap by incorporating Twitter sentiment analysis into stock price prediction models.

## **Business Use Case**
This forecasting model is designed for investors, financial analysts, and institutions looking for data-driven insights. The system provides enhanced decision-making tools, leveraging sentiment data to better predict stock trends.

## **Data Sources**
- **Stock Data:** Yahoo Finance (Sample Data: Apple Inc. - AAPL)
- **Twitter Data:** Scraped tweets from Kaggle dataset (2021-2022)

## **Methodology**
1. **Data Collection & Cleaning**
   - Historical stock data (Open, Close, High, Low, Volume)
   - Twitter data preprocessing (Tokenization, Stopword removal, Sentiment Scoring via VADER)

2. **Feature Engineering**
   - Technical indicators (Moving Averages, Bollinger Bands, EMA)
   - Sentiment scores merged with stock price data

3. **Model Architecture**
   - **Baseline Models:** SVM, Naïve Bayes, Linear Regression
   - **Deep Learning:** 1D CNN + Bidirectional LSTM + Dense Layers
   - **Evaluation Metrics:** Mean Squared Error (MSE)

4. **Training & Evaluation**
   - Train-test split (80:20) with additional validation split (90:10)
   - Comparison of stock price prediction with and without sentiment analysis

## **Results & Key Findings**
- LSTM with sentiment analysis **outperforms** stock-only models.
- Sentiment analysis enhances market trend responsiveness, improving peak and trough predictions.

## **Future Enhancements**
- Real-time stock prediction using live Twitter feeds
- Enhanced sentiment scoring models (e.g., Transformers, BERT)
- Integration of financial news APIs for comprehensive market insights

## **Contributors**
- **Anuraag Gujje**  
- Prudhvi Teja Mamidi  
- Sai Koushik Thatipamula  
- Akshita Katta  
