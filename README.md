# Mushroom_Naive_Bayes
Mushroom Classification using Naive Bayes Classifier
# Naive Bayes Classification
It is a classification technique based on Bayes' Theorem with an assumption of independence among predictors. In simple terms, a Naive Bayes classifier assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature.  
Bayes Theorem - P(Y/X)=(P(X/Y).P(Y))/P(X)
Y-Label
P(Y=C/X)= posterior probability
P(X/Y=C) = Likelihood= P(X1/Y=C).P(X2/Y=C)..............p(Xn/y=C)
P(Y=C) =Prior=SUM(all Y=C in training data)/Total examples in training data
P(X) =sigma i=0 to i=n((P(X/Y=i).P(Y=i))  ----> we can ignore this because it is going to be same for all cases
Calculate posterior probability for all labels 
posterior probability is directly proptional to likelihood.prior
predict the label for test data set take argmax(Posterior Probabilities)


# Prerequisites
1.Jupyter (or any other python platform)
2. install numpy, pandas and sklearn


# Attachements 
1. mushroom.csv file
2.code.ipynb file is code file in python showing above implementation
