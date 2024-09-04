## Natural Language Text Classification Models and Vectorization

This project compares estimators: Logistic Regression, Decision Tree, and Naive Bayes, and text vectorization strategies: tfidf, and count for a text classification problem.  
A pipeline is created is created with one of the estimators, with either tfidt or count vectorization technique.  GridSearchCV in scikitlearn is used to find the best hyper-parameters for the different estimators.  The model pipeline results are generated for each estimator and vectorization combination. 

### Machine Learning Models
#### Logistic Regression
Logistic Regression is a linear model used for binary classification tasks, predicting the probability that a given input belongs to a particular class.
#### Decision Tree Classifier
Decision Tree classifiers split the data into subsets based on the value of input features, creating a tree-like model of decisions. 
#### Naive Bayes
Naive Bayes classifiers are based on Bayes’ theorem, assuming independence between features.

### Text Vectorization

This is a crucial step in Natural Language Processing (NLP) that involves converting text data into numerical representations, which can then be processed by machine learning algorithms. This project examines and compares the 2 common vectorization techniques:

#### Bag of Words (BoW): 
Also known as Count Vectorization, converts text into numerical features by counting the occurrences of each word in a document. It creates a sparse matrix where each row represents a document and each column represents a word from the vocabulary. 

#### Term Frequency-Inverse Document Frequency (TF-IDF): 
This technique not only considers the frequency of words in a document but also their importance across the entire corpus. It reduces the weight of commonly occurring words and gives more importance to less frequent but more meaningful words. 
