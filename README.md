# Financial-Tweet-Preprocessing-NLP
Financial Tweet Preprocessing and NLP Analysis
## Project Overview
This repository demonstrates the core Natural Language Processing (NLP) techniques applied to real-world financial data. The primary objective is to transform raw, noisy tweet data from key financial influencers into a clean, structured format suitable for advanced tasks like Financial Sentiment Classification.

The notebook, financial_sentiment_nlp_analysis.ipynb, serves as a detailed, step-by-step guide and demonstration environment.

## 💾 Dataset Context
The analysis is performed on the StockerBot Export dataset sourced from Kaggle (dwallach/stockerbot-export).

Feature

* Data Type: Tweets related to publicly traded companies and cryptocurrencies.

* Source: Tweets monitored from a curated list of influential finance and news accounts (e.g., MarketWatch, WSJ, Jim Cramer).

* Purpose: Provides raw textual data to gauge public and influencer sentiment around financial markets.

## ✨ Core NLP Techniques Demonstrated
The project applies and explains five essential NLP preprocessing and enrichment techniques:

1. Normalization: Standardizing text by lowercasing, removing URLs, mentions, hashtags, and stock tickers ($AAPL), and eliminating standard stop words.

2. Stemming: A heuristic process using the Porter Stemmer to reduce words to their rough root form (e.g., investing → invest).

3. Lemmatization: A linguistic process using the WordNet Lemmatizer to reduce words to their valid dictionary base form, or lemma (e.g., better → good).

4. Text Enrichment (POS Tagging): Assigning a Part-of-Speech (POS) tag (Noun, Verb, Adjective) to each word to provide vital grammatical context.

5. Named Entity Recognition (NER): Using spaCy to identify and classify entities such as Organizations (ORG), People (PERSON), and Dates (DATE), effectively structuring the unstructured text.

## 🚀 Setup and Execution
To run this analysis, you must have the necessary Python libraries and a Kaggle API key configured, as the notebook fetches the data directly.

## Prerequisites
* Python Environment: Python 3.8+

## Running the Notebook
* Clone the Repository: git clone [https://github.com/CarolSamoei/Financial-Tweet-Preprocessing-NLP.git](https://github.com/CarolSamoei/Financial-Tweet-Preprocessing-NLP.git)
cd Financial-Tweet-Preprocessing-NLP

* Open in Google Colab:
The notebook is designed to run in Google Colab. Upload financial_sentiment_nlp_analysis.ipynb to your Google Drive and open it with Colab.

* Execute Cells:
Run the cells sequentially. You will be prompted to upload your kaggle.json file in Section 2.2 for data access. The subsequent sections will execute the NLP pipelines and display the results and explanations.

## ⚙️ Dependencies
The primary libraries used in this project are:

* pandas

* nltk

* spacy (en_core_web_sm model)

* re (for regular expressions)
