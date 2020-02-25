#  Topic Modeling LDA Using Spark for Machine Learning 




## Introduction 

In this project, we are using spark to do machine learning. Our dataset is  `Amazon Product Review Dataset` and analyze reviews using natural language processing (NLP).Here we are using  algorithm "Topic Modeling " is a type of statistical modeling for discovering the abstract “topics” that occur in a collection of documents. Latent Dirichlet Allocation (LDA) is an example of topic model and is used to classify text in a document to a particular topic. It builds a topic per document model and words per topic model, modeled as Dirichlet distributions.


## About Data 

We used Amazon raw review dataset that was 34gb in zipped format and 120gb otherwise. We did EDA, DataProcessing along with Count vectorizer(files in Topic modeling folder) on that data but after that as data is too big and we were performing analysis on personal computer it stopped working when we tried to fit model. We thought to proceed with department's Datascience lab but we only have access on Tuesdays. Therefore we choose Amazon Magazine_Subscription data to proceed with.
`Amazon's Magazine Subscription dataset's online link is here http://deepyeti.ucsd.edu/jianmo/amazon/index.html.

## Topic Modeling:

For our project, we have to implement NLP on the dataset, in order to do that,we followed the following machine learning steps:

1. Exploratory Data Analysis (EDA)
2. Data Processing 
3. Machine Learning(Implementing Algorithms,Topic Modelling LDA)
4. Validation
5. Testing your Model

### 1. EDA 

In this part, We did the following steps:

1. Prepared graphical representation of `overall`
2. We found the most common words along with their frequency and graphical representation.
3. Got the count of all words in reviewText variable.
4. Counted the total number of characters in the whole dataset


### 2. Data Processing

Data Processing is the most important part of the project is to apply text processing to the dataset. 

For this purpose we performed following steps:

1. Removed punctations.
2. Lowercased words
3. Removed stopwords
4. Did Lemmatization
5. Stemming
6. Tokenization
7. Removed short words (len(word) > 3)

### 3. Machine Learning

For 





