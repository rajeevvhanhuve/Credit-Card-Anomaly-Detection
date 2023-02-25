# Credit-Card-Anomaly-Detection
**Introduction:**
Credit card fraud is becoming very common nowadays. Detecting these types of fraud is a challenging task as it requires detecting fraudulent transactions out of millions of daily transactions. Due to the enormous amount of data, it is nearly impossible for human specialists to identify meaningful patterns from transaction data. However, employing machine learning models these types of fraud can be detected.

**Problem statement:**
The goal of this project is to detect anomalous transactions in a dataset of financial transactions. An anomalous transaction is one that deviates significantly from the typical behavior of other transactions in the dataset. We aim to develop a machine learning model that can accurately identify anomalous transactions.

**Dataset:**<BR>
The dataset used in this project is the Credit Card Fraud Detection [dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle, which contains transactions made by credit cards in September 2013 by European cardholders. The dataset has 284,807 transactions, out of which 492 are fraudulent. The dataset is highly imbalanced, with the fraudulent transactions accounting for only 0.17% of the total transactions.

**Observation:**
- Isolation Forest detected 73 errors versus Local Outlier Factor detecting 97 errors vs. SVM detecting 8516 errors.
- Isolation Forest has a 99.74% more accurate than LOF of 99.65% and SVM of 70.09.
- When comparing error precision & recall for 3 models , the Isolation Forest performed much better than the LOF as we can see that the detection of fraud cases is around 27 % versus LOF detection rate of just 2 % and SVM of 0%.
- So overall Isolation Forest Method performed much better in determining the fraud cases which is around 30%.
