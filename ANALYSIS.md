# Detailed Analysis and Findings

## Motivation
The financial market is influenced by a multitude of factors, from economic indicators to geopolitical events. Investors need predictive tools that can incorporate these various influences. This project focuses on the impact of public sentiment, particularly the influence of Elon Musk's tweets, on Tesla's stock prices.

## Data Collection
We sourced our data from multiple platforms:
- **Tweets:** Extracted from financial news Twitter accounts and Elon Musk's official account.
- **Stock Prices:** Historical data from Yahoo Finance for Tesla and its competitors.
- **Wikipedia Page Views:** Weekly views of Tesla's Wikipedia page to gauge public interest.

### Data Cleaning
Using the Beautiful Soup library, we cleaned the tweets by removing duplicates, URLs, and @mentions. We ensured the data from all features aligned with the dates of Tesla's stock prices.

### Sentiment Analysis
We utilized the VADER sentiment analysis tool to assign sentiment scores to each tweet, categorizing them into positive, negative, or neutral sentiments. This allowed us to gauge the overall sentiment trends regarding Tesla.

### Predictive Modeling
#### Regression Models
We used several models to predict Tesla's stock prices:
- **Linear Regression:** Initially used all features but refined the model to eliminate multicollinearity.
- **Decision Tree Regressor and Random Forest:** Implemented with cross-validation to enhance prediction accuracy.
- **Gradient Boosting Trees:** Provided the best performance with feature importance analysis.

#### Classification Models
To predict whether the stock price would go up or down, we used:
- **Baseline Model:** Predicted stock increase for any observation.
- **CART and Random Forest Classifiers:** Implemented with cross-validation.
- **Gradient Boosting Classifier:** Showed improved prediction accuracy.

### Results
The models demonstrated that tweets' sentiments significantly impact Tesla's stock prices. Specifically, tweets from influential accounts like Elon Musk's showed a strong correlation with stock price movements.

### Conclusion and Future Work
The integration of sentiment analysis into stock price prediction models offers a comprehensive tool for investors. Future work could involve more granular sentiment analysis from individual Twitter accounts to refine the predictive accuracy.

### Impact
Our project underscores the importance of considering public sentiment in financial modeling. By expanding the scope of analysis, investors can gain deeper insights into the factors driving stock price movements.

## Repository
The data and code for this project can be found in the [GitHub repository](https://github.com/majda-br/Stock-trend-prediction).

## Contributors
- Sahil Mehta
- Daniel Garcia Mijares
- Claudia Cañete Yaque
- Majda Brahimi
