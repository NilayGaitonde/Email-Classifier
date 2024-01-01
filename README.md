# Email Classifier

Email is an efficient and widely used communication method between professionals. However, unsolicited bulk emails, known as spam, clutter inboxes and cause lost productivity. This project builds a classifier to identify and filter spam emails. 

## Problem and Key Features

Spam email filtering is a common machine learning task. Classification is challenging due to the high dimension feature space of text data and large volume of documents. This project implements a robust voting ensemble classifier and topic modeling to categorize emails.

Key features:

- Data preprocessing including tokenization, stopword removal
- Hyperparameter tuning using RandomizedSearchCV 
- VotingClassifier ensemble of Naive Bayes, SVM, Neural Net models
- Latent Dirichlet Allocation (LDA) topic modeling to categorize non-spam
- Evaluation metrics such as confusion matrix and classification report

## Usage 

The implementation is an easy to run Jupyter notebook:

1. Download notebook and encoded email dataset
2. Ensure key libraries (NumPy, SciKit-Learn) are installed 
3. Run notebook cells end-to-end to preprocess, train, and evaluate model


## Performance

The current model achieves **97% accuracy** on the test set. This could likely be improved further by tuning model hyperparameters and the number of topics for LDA.

## Credits
This project was made with [Niharika Bhende](), [Riddhi Dumre](https://github.com/RiddhiDumre/RiddhiDumre) and [Vishesh Giyanani](https://github.com/Vishesh-Giyanani)
