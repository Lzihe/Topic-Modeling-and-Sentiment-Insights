# Semantic N-Gram Topic Modeling and Sentiment Insights of Airline Reviews across Different Flight Classes

## Project Overview

This dissertation focuses on analyzing customer feedback in the airline industry using data mining techniques such as topic modeling and sentiment analysis. The primary goal is to explore the hidden customer requirements and sentiments across economy, business, and first-class cabins to identify key drivers of customer satisfaction.

## Key Features

- **Data Source**: The dataset includes 22,735 airline reviews collected from the airlinequality.com website. Reviews cover customer experiences across economy, business, and first-class cabins.
- **Topic Modeling Algorithms**: Three different topic modeling techniques were evaluated:
  1. Latent Dirichlet Allocation (LDA)
  2. Latent Semantic Analysis (LSA)
  3. Non-Negative Matrix Factorization (NMF)  
  Based on coherence scores, NMF with 10 topics was selected as the optimal model.
  
- **Sentiment Analysis**: The VADER tool was used to assess the emotional polarity of identified topics, helping quantify positive, negative, or neutral sentiments within customer reviews.

## Methodology

1. **Data Preprocessing**: The text data was preprocessed to remove stop words, punctuation, and short words. Lemmatization was applied to standardize words.
2. **Feature Engineering**: N-Grams and Bag of Words (BoW) methods were used to extract meaningful phrases and word combinations.
3. **Topic Modeling**: The NMF model was selected based on its high coherence score (0.4997), and topics were identified for each cabin class.
4. **Sentiment Analysis**: The VADER sentiment analyzer was applied to determine the emotional tendencies of passengers towards specific service aspects.

## Results

- **Economy Class**: Passengers prioritized flight punctuality, seat comfort, and cost-efficiency.
- **Business Class**: Customers focused on service quality in relation to ticket price, with an emphasis on seat comfort and food quality.
- **First Class**: Passengers emphasized premium service experiences, including luxury amenities and exclusive services.
  
Sentiment analysis revealed significant negative sentiment towards flight cancellations and delays, while food and beverage services garnered positive feedback across all classes.

## Practical Applications

- **Airline Service Improvement**: This framework offers valuable insights into customer satisfaction and areas for service enhancement, including:
  - Addressing flight scheduling and delays.
  - Improving seat comfort and catering services.
  - Offering flexible ticketing and refund options.
  
- **Strategic Recommendations**: The results can guide airlines in refining their services and aligning them with customer expectations to boost satisfaction and loyalty.

## Files Included

- **Dissertation Document**: Contains the detailed methodology, results, and analysis of the topic modeling and sentiment analysis on airline reviews.
- **SPARQL Queries**: Example queries for further exploration of the dataset.

## How to Run

1. Load the dataset into a suitable text analysis tool.
2. Preprocess the text data (tokenization, noise removal, etc.).
3. Apply the N-Gram and BoW methods for feature extraction.
4. Use the NMF model to perform topic modeling.
5. Conduct sentiment analysis using VADER or any other lexicon-based sentiment analyzer.
