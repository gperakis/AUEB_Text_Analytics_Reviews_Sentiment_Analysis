# Sentiment Analysis on Customer Reviews

This repository holds the implementation of the 2nd (second) assignment for the Text Engineering and Analytics course, which is part of the M.Sc. in Data Science program of the Athens University of Economics and Business.


### Assignment Description:

1. Develop a text classifier for a kind of texts of your choice (e.g., e-mail messages, tweets,
customer reviews) and at least two classes (e.g., spam/ham, positive/negative/neutral).
2. You may use Boolean, TF, or TF-IDF features corresponding to words or n-grams, to which you
can also add other features (e.g., length of the text). You may apply any feature selection (or
dimensionality reduction) method you consider appropriate. You may also want to try using
centroids of pre-trained word embeddings (slide 36).
3. You can write your own code to produce feature vectors, perform feature selection (or dimensionality reduction)
and train the classifier (e.g., using SGD and the tricks of slides 59–60, in the case of logistic regression), or
you can use existing implementations and software libraries.
4. You should experiment with at least logistic regression, and optionally other learning algorithms 
(e.g., Naive Bayes, k-NN, SVM). Draw learning curves (slides 66, 69) with appropriate measures (e.g., accuracy, F1)
and precision-recall curves (slide 24). Include experimental results of appropriate baselines
(e.g., majority classifiers). Make sure that you use separate training and test data. Tune the
feature set and hyper-parameters (e.g., regularization weight λ) on a held-out part of the
training data or using a cross-validation (slide 26) on the training data. Document clearly in a
short report (max. 5 pages) how your system works (e.g., what algorithms it uses, examples of
input/output) and its experimental results (e.g., learning curves, precision-recall curves).
