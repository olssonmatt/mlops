# MLOps
 - An MLOps system for deploying ML models—initially for credit card fraud detection, with plans to add custom models later.
 - Credit card fraud detection model for the Kaggle dataset (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
 - A quick project aimed be a proof of concept as well as an effort to bolster the explainations models

## Description
 - In this dataset, there are a number of transactions and only a small number of them are fraudulent. This allows us to calculate the percent of fraudulent transactions. To direct this into a model, we consider the percent of fraudulent transactions to be the probability of any given transaction to be linked to fraud. Consider the logistic function, $f(x) = \frac{1}{1+ e^{m_1 x_1 + ... + m_n x_n + b}}$. In this formula, there are $x_n$ variables that influence the logsitc function. In this case, $f(x)$, takes the places of the probability of a fraudulent transaction, the $x$ variables relate to the columns provided in the data set, $m_n$ is some scaling factor(s), and $b$ is some intercept of the line. It is advantageous to fit to a logistic function because the range of the function operates between (0,1) much like probability.
 - 
