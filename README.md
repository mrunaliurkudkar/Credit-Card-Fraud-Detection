Credit-Card-Fraud-Detection 
    This repo analyze how various machine learning algorithms perform on balance and unbalance dataset by taking examples of credit card fraud detection.
INTRODUCTION
    According to the Fraud Benchmark Report by cyber source 83% American businesses are conducting manual reviews, and on an average basis, they review 29 % of orders manually. India is witnessing a drastic change to online transactions. It was ranked in top 5 countries with respect to credit card fraud and cases related to debit/credit card fraud have surged to 42% in 2017 according to the Hindustan Times. According to RBI data, the number of credit cards rose by a quarter upto 38 million in the last 12 months ending in May, while the number of debit cards jumped 17% to over 925 million in the same period.
OBJECTIVE
    The aim of this work is to study and analyze how machine learning algorithms like boosting and ensembling along with data balancing algorithms.
DATASET DESCRIPTION
    Due to security reasons, most of the features in the dataset are transformed using principal component analysis (PCA). V1, V2, V3,..., V28 are PCA applied features and rest features include ‘time’, ‘amount’ and ‘class’ are non-PCA applied features.
CONCLUSION
   The overall project discusses the problem of credit card fraud detection and how machine learning can be used to deal with it. During analysis ’V14’ is found to be the most dominating feature when smote and adasyn are used as data balancing algorithm, also both of them are oversampling method, ’V17’ is found to be the most dominating feature when no data balancing algorithm is used. Most variation was observed in case of allknn as data balancing algorithm.
