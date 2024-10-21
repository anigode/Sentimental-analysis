### Sentiment Analysis Project
This project aims to analyze customer reviews to determine their sentiment—whether they are positive, negative, or neutral. The sentiment analysis is performed using Natural Language Processing (NLP) techniques, including the VADER and Roberta models, which are used to classify and score sentiments in textual data.
## Table of Contents
- Introduction
- Installation
- Usage
- Data
- Models
- Evaluation
- Libraries
## Introduction
The project focuses on analyzing product reviews from e-commerce platforms to identify customer sentiment. By leveraging machine learning models such as VADER (Valence Aware Dictionary and sEntiment Reasoner) and Roberta, the analysis extracts sentiment scores from textual reviews and helps businesses gain insights into customer opinions and product feedback.
## Installation
- Clone the repository.
- Install the required libraries.
- Ensure you have Python (preferably version 3.6 or above) installed.
## Usage
- Place your dataset (e.g., Reviews.csv) in the project directory.
- Run the sentiment analysis script (e.g., sentiment_analysis.py) to analyze the data.
- The output will include sentiment scores for each review, visualizations, and detailed reports of positive, negative, and neutral reviews.
## Data
The project uses a dataset of customer reviews, with key fields including:
  - Id: Unique identifier for each review
  - ProductId: Identifier for the reviewed product
  - UserId: Identifier for the customer
  - ProfileName: Customer's profile name
  - HelpfulnessNumerator: Number of helpful votes
  - HelpfulnessDenominator: Number of total votes
  - Score: Rating given by the customer (1–5)
  - Time: Timestamp of the review
  - Summary: Short summary of the review
  - Text: Full text of the review

Data Preprocessing
  - Tokenization of text
  - Part-of-speech tagging
  - Chunking for named entity recognition
- Text normalization and cleaning
## Models
The project implements two sentiment analysis models:
- VADER Model: A rule-based model for sentiment analysis specifically attuned to social media texts.
- Roberta Model: A transformer-based model trained for text classification, used for more nuanced sentiment detection.
## Key Outputs:
- Polarity Scores: Each text receives a sentiment score (positive, negative, neutral) from both VADER and Roberta models.
- Compound Scores: Aggregated sentiment score from VADER.
## Evaluation
The project evaluates sentiment predictions by comparing sentiment scores with actual product ratings. Visualizations, such as bar plots, are used to compare positive, neutral, and negative sentiment distributions across different review scores.
## Libraries
The project requires the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- nltk (Natural Language Toolkit)
- transformers (for Roberta)
