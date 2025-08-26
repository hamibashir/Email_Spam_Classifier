# Email Spam Classifier

This repository contains an Email Spam Classifier that uses a classical machine learning approach to differentiate between "spam" and "ham" (non-spam) emails.

Key Features & Technologies:

Multinomial Naive Bayes Model: The classifier is based on the MultinomialNB algorithm from scikit-learn, a probabilistic classifier well-suited for text classification.

Bag-of-Words Vectorization: The CountVectorizer from scikit-learn is used to transform the raw email text into a numerical "Bag-of-Words" representation. This process counts the occurrences of words, which serves as input for the model.

Training Data: The model is trained on a dataset from a CSV file (emails.csv), which contains the email text and a corresponding spam label (1 for spam, 0 for ham).

Evaluation Metrics: The project uses classification_report, confusion_matrix, and accuracy_score from scikit-learn to evaluate the model's performance on a test set.

How to Use:

The notebook includes a function predictMessage that takes a message as input, vectorizes it using the trained CountVectorizer, and then uses the model to predict if it is spam or ham. The output will clearly state the classification.
