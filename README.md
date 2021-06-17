# POS Tagging
## Please find the attached .ipynb file.
## We import the files and libraries for our POS Tags Prediction

## sklearn_crfsuite was utilized to make models.

## 2 Types of Models are analysed.
## Model 1 doesn't account for the prefix/suffix in the features
## Model 2 accounts for prefix/suffix in the features

## Performance metrix for both the models are produced in the end.

## Model 1 gives a f1 score of .866
## Model 2 gives a f1 score of .901 making is better than Model 1

## Other performance measures such as precision and recall were also used to analyse the models.

## l2sgd (SGD with L2 Regularization) is used while training both the models. The regularization constant is taken as 0.1