# News-Article-Analysis-Unraveling-Key-Terms-with-TFIDF-Metrics
An in-depth text processing project leveraging TFIDF metrics to analyze and categorize news articles, aiming to uncover significant terms and insights from raw textual data.

Objective: 
This project focuses on the representation of raw text documents in a machine-processable manner, utilizing the Term Frequency Inverse Document Frequency (TFIDF) method. The goal is to effectively preprocess the text data, compute TFIDF vectors, and uncover significant terms that characterize the topics of the documents.

Scope:
Extraction and representation of raw text documents from the provided dataset.
Preprocessing of the documents to generate unigrams.
Computation of TFIDF vectors for each document.
Identification of the top 3 most frequent words in each category.
Derivation of the top 3 highest average TFIDF words in each category.

Tools Used:
Python: For all data processing, text manipulation, and computation tasks.
CSV Files: To store and represent the dataset containing news articles and their respective categories.
JSON: For the final representation of frequency and score results.
Methods Used:

Data Loading: 
Import raw text data from the provided CSV files.
Text Preprocessing: Convert documents to lowercase, remove punctuation, tokenize documents, eliminate stop words, and extract character stems to generate unigrams.
TFIDF Computation: Calculate TFIDF scores for each term in every document, following the provided formulas.
Term Analysis: Determine the most frequent terms and highest average TFIDF words in each category.
Output Generation: Create a well-formatted JSON representation for both frequency and TFIDF scores.

Deliverables:
A Jupyter notebook (.ipynb) containing all the Python code.
A text file (matrix.txt) representing the TFIDF matrix for the documents.
Two JSON files (frequency.json and scores.json) representing the top terms by frequency and TFIDF scores, respectively.
