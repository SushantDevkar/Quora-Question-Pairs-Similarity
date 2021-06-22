# Quora-Question-Pairs-Similarity
1. Data set used is avilable on kaggle : https://www.kaggle.com/c/quora-question-pairs/data
2. Feature Engineering: Created 11 features like length of question 1, length of question2, number of comman words, etc. Created 15 advance feature from given 2 test questions.
3.Models:

Random model : - loss: 0.88

Logistic Regression:- loss: 0.52

SVM_with l1 regularization:-loss: 0.489

GBDT :loss- 0.357

We can improve the results with Word2vec model convert question in to directly vector using word2vec or BOW(sparce vectors).
