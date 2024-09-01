# Amazon Reviews Sentiment Analysis
## Overview

This project performs sentiment analysis on Amazon reviews using both the Vader Sentiment Analysis model and the Roberta (a Transformer-based model) for a comprehensive understanding of customer sentiments. The analysis is conducted on a dataset of 500 Amazon reviews, and the results are visualized and compared to provide insights into customer opinions.

## Sentiment Analysis
Vader Sentiment Analysis

Vader (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool specifically attuned to sentiments expressed in social media. Vader provides four sentiment scores:

Negative (vader_neg): Proportion of negative sentiment.
Neutral (vader_neu): Proportion of neutral sentiment.
Positive (vader_pos): Proportion of positive sentiment.
Compound (vader_compound): Aggregated score that sums up all the sentiment scores. It ranges from -1 (most negative) to +1 (most positive).

Roberta Sentiment Analysis
Roberta is a Transformer-based model designed for natural language processing tasks, including sentiment analysis.

Roberta Sentiment Insights:

Positive Sentiment (roberta_pos): 80.12% of the reviews are classified as positive.
Negative Sentiment (roberta_neg): 12.85% of the reviews are classified as negative.
Neutral Sentiment (roberta_neu): 7.03% of the reviews are classified as neutral.

Analysis Results
Star Ratings Distribution:

5-Star Reviews: 337 (67.67%)
4-Star Reviews: 70 (14.06%)
3-Star Reviews: 37 (7.43%)
1-Star Reviews: 36 (7.23%)
2-Star Reviews: 18 (3.61%)

Sentiment Analysis Insights:

The Roberta model indicates a high percentage of positive sentiment, correlating with the high number of 5-star reviews.
The Vader model shows a dominant neutral sentiment with very few positive reviews, suggesting it may be less sensitive to sentiment variations in this dataset.

