# Spam-SMS-Detection
A machine learning program to classify text message as Spam or Ham.
Dataset link: https://www.kaggle.com/uciml/sms-spam-collection-dataset
## About the dataset(Kaggle)
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.
## About the project
A python program to detect sms spam using Machine Learning technique called Natural language processing. The progam uses Scikit-Learn library and Natural Language Toolkit (NLTK). Other libraries used includes Pandas, Matplotlib, Numpy.
### Implemented Naive bayes, SVM, Logistic regression and K-Nearest Neighbor model.

### SVM has highest AUC of ROC curve, area= 0.9368 while logistic regression model has AUC=0.9357. From AUC both SVM and logistic regression model performed equally well

### For our spam detector, we want to maximize precision of Spam and maximize recall of Ham

### Logistic Regression model has higher value in both precision of Spam and recall of Ham

### Logistic Regression model has higher accuracy (accuracy score=0.9806576402321083)

### Therefore I would choose Logistic Regression model over all the above models
