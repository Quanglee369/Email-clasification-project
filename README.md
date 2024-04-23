# Email-clasification-project
In this project I will build a classification model that predict whether an email to be spam or non-spam. This is done by traning and testing the model with data of 83448 different emails.
Throughout the project I have done many steps which include:
- Preprocessing data:
  + Remove stop words, punctuation
  + Tokenizer the text data
  + Turn the tokenized data into padding sequence
- Choose the best model and tunning parameters:
  + Go through well know model for email classification such as (Random Forest, GRU, RNN)
Tunning parameters to come up with the most optimal result for that model

#Sources
1. 2007 TREC Public Spam Corpus
- Original link: https://plg.uwaterloo.ca/~gvcormac/treccorpus07/
- Preprocessed download link: https://www.kaggle.com/datasets/bayes2003/emails-for-spam-or-ham-classification-trec-2007
2. Enron-Spam Dataset
- Original link: https://www2.aueb.gr/users/ion/data/enron-spam/
- Preprocessed download link: https://github.com/MWiechmann/enron_spam_data/
- Code for combining and processing the two datasets: https://github.com/PuruSinghvi/Spam-Email-Classifier/blob/main/Combining%20Datasets.ipynb
