# Linear Regression With Pytorch

This is my first time using Pytorch.  I'm following the Udemy class Pytorch: Deep Learning and AI.  Using the knowledge from that class, I've taken a dataset from kaggle (https://www.kaggle.com/mdrazakhan/linear-regression-dataset), and run a Linear Regression on 2 of the variables.  Obviously, this dataset offers opportunities for much more complicated analyses, but I'm taking this one step at a time.  I'll later try adding in more variables.  I might try also doing a logistic regression at some point.

I first tried using MSE, which gave increasing losses each epoch.  Then I switch to L1, which measures MAE instead of MSE, and came up with usable results.  I noticed that it took 9 epochs to get to the point where error stopped decreasing.  I charted the loss, and came up with a weight and bias.
