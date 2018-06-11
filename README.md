# Machine-Learning-In-Data-Science-
## Project on Data Science using Python and Applying the Machine Learning Algorithms 

## Overview: 

The objective of this Project is to scrape a corpus of News articles from a set of web pages, pre-process the corpus, and evaluate the performance of automated classification of these articles in a supervised learning context. The project has been implemented as a single IPython Notebook. The code has been clearly documented, using comments and Markdown cells to explain my code and results.

## Part 1. Data Collection 
  
 The goal here is to collect a labelled news corpus. Tasks that has completed: 
  1. Identify the URLs and category labels for all news articles listed on the website:                  http://mlg.ucd.ie/modules/COMP41680/archive/index.html 
  2. Retrieve all web pages corresponding to these News article URLs From the web pages, extract
  the main body text containing the content of each news article. Save the body of each article as plain text. 
  3. Save the category labels for all News articles in a separate file. 
  
## Part 2. Text Classification 

The goal here is to analyse the corpus of documents from Part 1 in a text classification context. Tasks that has completed: 
1. From Part 1 load the files having the set of raw documents and its realative labels into Jupyter notebook. 
Ensuring that each document has a class label, based on the original category label that was identified. 
2. From the raw documents I have created a document-term matrix, before that I performed an appropriate text pre-processing techniques like Tokenization, Removing Stopwords, Bag-Of-Words Representation, Lemmatization and term weighting steps. 

## Part 3. Applying the Machine Learning Algorithm

1. Here I have builded three multi-class classification models using three different classifiers namely. 
a] K-Nearest-Neighbor(KNN) Classifier

b] Logistic Regression Classifier, and. 

c] Decision Tree Classifier.

2. I have compared the predictions of the these classification models using an appropriate evaluation strategy 
and discussed the evaluation results in the notebook. 
3. Displayed the Confusion Matrix and Classification Report which has precision, recall, f1-score, and support of the Classifier. 
