# Gender-classification-challenge

This the gender classification challenge which was given by Siraj. To know more, you can watch his this video https://www.youtube.com/watch?v=T5pRlIbr6gg .


In this challenge we had to use 3 models to predict whether the given measurements belonged to male or female. In exception to decision tree classifier, I used the following models and this is the prediction given by them for the same data in Gender_Classification_challenge.ipynb.

| Models Used          | Predicted Result |
| -------------------- | ---------------- |
| Decision Tree        | Male             |
| Logistic Regression  | Female           |
| Gaussian Naive Bayes | Male             |
| K Nearest Neighbors  | Male             |

I used scilit-learn or sklearn and Python 3.6.

In the Gender Classifier.ipynb, I have defined test set as well and made predictions using the same model and I have measured their accuracy score, following are the results:

| Models Used          | Accuracy         |
| -------------------- | ---------------- |
| Decision Tree        | 100%             |
| Logistic Regression  | 100%             |
| Gaussian Naive Bayes | 100%             |
| K Nearest Neighbors  | 87.5%            |

The most shocking thing I found was in the first program, I am getting female for Logistic Regression, but in second it is giving 100% accuracy.
