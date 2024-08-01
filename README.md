# Predicting Tesla Stock Prices Using Sentiment Analysis

[![YouTube Video](https://img.youtube.com/vi/GIHftI4H96E/0.jpg)](https://www.youtube.com/watch?v=GIHftI4H96E)

## Overview
This project aims to predict Tesla's stock prices by leveraging sentiment analysis from social media, specifically focusing on tweets mentioning Tesla and Elon Musk. By analyzing the sentiment of these tweets, alongside traditional financial indicators, we aim to create a robust predictive model for Tesla's stock prices.

## Motivation
The financial market is a complex ecosystem influenced by various factors, including public sentiment. This project investigates the impact of Elon Musk's tweets on Tesla's stock prices, providing valuable insights for investors.

## Data
- **Tweets Data:** Extracted from financial news Twitter accounts and Elon Musk's official account.
- **Stock Prices:** Historical stock price data for Tesla and its competitors from Yahoo Finance.
- **Wikipedia Page Views:** Weekly page views for Tesla's Wikipedia page.

## Methodology
- Data Cleaning: Removing duplicates, URLs, @mentions using Beautiful Soup.
- Sentiment Analysis: Using VADER (Valence Aware Dictionary and sEntiment Reasoner) to quantify tweet sentiments.
- Predictive Modeling: Employing Linear Regression, Decision Tree Regressor, Random Forest, and Gradient Boosting Trees.

## Results
- **Linear Regression:** Provided initial insights but showed high multicollinearity.
- **Random Forest and Gradient Boosting Trees:** Performed better with cross-validation and feature importance analysis.

## Conclusion
The sentiment from tweets, especially those by influential figures like Elon Musk, significantly impacts Tesla's stock prices. By integrating sentiment analysis with traditional financial indicators, our model provides a more comprehensive prediction tool.

## How to Run
1. Clone the repository.
2. Place the datasets in the `data/` folder.
3. Run the scripts in the `src/` folder.

## Technologies Used
**Programming Languages and Libraries:**
- **Python:** The primary programming language used for data analysis and modeling.
- **Pandas:** For data manipulation and analysis.
- **NumPy:** For numerical computing.
- **Scikit-learn:** For machine learning algorithms and model evaluation.
- **Statsmodels:** For statistical modeling and hypothesis testing.
- **VADER Sentiment Analysis:** For sentiment analysis of tweets.
- **Matplotlib and Seaborn:** For data visualization.

**Data Collection:**
- **Twitter API:** For collecting tweets related to Tesla and Elon Musk.
- **Beautiful Soup:** For web scraping and data cleaning.

**Data Sources:**
- **Yahoo Finance:** For historical stock price data of Tesla and its competitors.
- **Wikipedia API:** For weekly page view data of Tesla's Wikipedia page.

**Version Control:**
- **Git:** For version control and collaboration.
- **GitHub:** For repository hosting and project management.


## Contributors
- Sahil Mehta
- Daniel Garcia Mijares
- Claudia Cañete Yaque
- Majda Brahimi

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
