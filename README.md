# Multiclass-multilabel-classification-using-ML-Kaggle-competition-
Using Machine learning to predict programming tags for stack overflow data

### Description and Problem Statemtent

Stack Overflow is the largest, most trusted online community for developers to learn, share their programming knowledge, and build their careers.

Stack Overflow is something which every programmer use one way or another. Each month, over 50 million developers come to Stack Overflow to learn, share their knowledge, and build their careers. It features questions and answers on a wide range of topics in computer programming. The website serves as a platform for users to ask and answer questions, and, through membership and active participation, to vote questions and answers up or down and edit questions and answers in a fashion similar to a wiki or Digg. As of April 2014 Stack Overflow has over 4,000,000 registered users, and it exceeded 10,000,000 questions in late August 2015. Based on the type of tags assigned to questions, the top eight most discussed topics on the site are: Java, JavaScript, C#, PHP, Android, jQuery, Python and HTML.

#### Suggest the tags based on the content that was there in the question posted on Stackoverflow.
### Source: https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/

### Type of Machine Learning Problem 
It is a multi-label classification problem 
**Multi-label Classification:** Multilabel classification assigns to each sample a set of target labels. This can be thought as predicting properties of a data-point that are not mutually exclusive, such as topics that are relevant for a document. A question on Stackoverflow might be about any of C, Pointers, FileIO and/or memory-management at the same time or none of these. 
**Credit: http://scikit-learn.org/stable/modules/multiclass.html

### Techniques used: Feature vectorization with Tf-Idf and n-grams, Onevsall logistic regression, Micro-averaged F1-score as performance metric.

Programming languages: Python, SQL
Sofware tools and libraries: Pandas, Numpy, sqlite3, sqlalchemy, NLTK, Sci-kit learn, seaborn, matplotlib, wordcloud 
