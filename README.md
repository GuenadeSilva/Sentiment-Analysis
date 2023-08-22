# McDonald's Reviews Sentiment Analysis

This project focuses on performing sentiment analysis on the reviews of McDonald's employees obtained from Indeed, a popular job search platform. The aim is to compare the sentiment of reviews before and during the COVID-19 pandemic to gain insights into the impact of the pandemic on employee perceptions and experiences.

## Project Overview

The goal of this project is to analyze text data from employee reviews on Indeed for McDonald's and assess the sentiment expressed in those reviews. By comparing the sentiment before and during the COVID-19 pandemic, we aim to identify any shifts or changes in employee sentiment towards the company.

## Data Collection

The data for this project was obtained by scraping employee reviews from Indeed using web scraping techniques. We collected a significant number of reviews from two different time periods: before the COVID-19 pandemic and during the pandemic. Each review includes text content and a rating scale associated with sentiment.

### Options

**[Website:](Scrapper/website_collect.ipynb)** The data was pulled from the website directly and saved it into a CSV file

**[HTML:](Scrapper/html_collect.ipynb)** Since HTML is constantly also included a version that pulls from HTML saved from the website at the time

## Data Preprocessing

Before performing sentiment analysis, the collected text data went through a series of preprocessing steps:

**Cleaning:** Removal of unnecessary characters, punctuation, and special symbols from the text data.
**Tokenization:** Splitting the text into individual words or tokens.
**Stopword Removal:** Eliminating common words (e.g., "and," "the," "is") that do not carry much sentiment information.
**Normalization:** Converting words to their base or root form (e.g., "running" to "run") using stemming or lemmatization techniques.

## Sentiment Analysis

Sentiment analysis is performed on the preprocessed text data using various techniques, such as:

**Lexicon-based Approach:** Assigning sentiment scores to words based on pre-defined sentiment dictionaries and calculating the overall sentiment of a review.
**Machine Learning Models:** Building classification models (e.g., Naive Bayes, Support Vector Machines) to predict sentiment based on the training data.
The sentiment analysis results are used to compare the sentiment distribution and sentiment polarity between the reviews before and during the COVID-19 pandemic.

## Results and Analysis

The results of the sentiment analysis are presented and analyzed to identify any notable changes in employee sentiment towards McDonald's before and during the pandemic. Visualizations such as bar charts or line graphs may be utilized to illustrate the sentiment distributions and highlight any significant differences.
