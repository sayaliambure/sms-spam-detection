# sms-spam-detection

This is a end-to-end sms classification preject

Here, we classify if the input sms is Spam or Not Spam. This same processes can be applied to classify email as well.

Dataset uesd: SMS Spam Collection Dataset (kaggle)

Various pre training things are done, like:
* data cleaning
* EDA
* text preprocessing.

Important libraries used- nltk (natural language toolkit), streamlit

Model is trained using Naive Bayes. 
Performance of model is checked on these models:
* Gaussian Naive Bayes
* Multinomial Naive Bayes
* Bernoulli Naive Bayes

Among these, Multinomial Naive Bayes gives better performance
