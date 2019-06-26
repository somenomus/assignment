Here, I will use an unsupervised learning algorithm, Autoencoder and apply anomaly detection technique to 
identify possible fruad transactions using a Credit Card Fraud Detection 
dataset(https://www.kaggle.com/hunk3749/credit-card/data).

Download it directly at - https://drive.google.com/file/d/1Tw_391BkVU_AkTEXPo6Z1md-kuvYHCBy/view?usp=sharing

About this Dataset:
The datasets contains transactions made by credit cards in September 2013 by european cardholders. 
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 
transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all 
transactions.

Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not
been transformed with PCA are 'Time' and 'Amount'. And, another one 'Class'. Value 1>fraud, Value 0>normal.

Problem Description:
Here, I will use Autoencoder as an unsupervised feature-learning algorithn that learns and generalizes 
the common patterns in the data. The key point is during the training, the Root Mean Square Error (RMSE)
will be much higher for the transactions that have unusual patterns. For accuracy, will set a threshold.
(Ex. 0.1)
