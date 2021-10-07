# Riiid-Answer-Correctness-Prediction
Track knowledge states of 1M+ students in the wild
>This is the competition of the AAAI-2021 workshop on AI Education! Prize-winning teams presented their models at the AAAI-2021 Workshop on AI Education - Imagining Post-COVID Education with AI - on February 9, 2021.

In this competition, our challenge is to create algorithms for "Knowledge Tracing," the modeling of student knowledge over time. The goal is to accurately predict how students will perform on future interactions. You will pair your machine learning skills using Riiid’s EdNet data.

You can find all useful information, rules and dataset at https://www.kaggle.com/c/riiid-test-answer-prediction/overview.

To solve this problem, I tried 7 different algorithms, each with different performance. My final ranking was **1031/3395**, which is about **31%** of all.

The best performance (score) of each algorithm with the dataset provided by Riiid is shown below:
+ LGBM bagging2 + SAKT = **0.781**
+ SAKT model inference = **0.774**
+ Feature Engineering prediction = **0.762**
+ LGBM single model ensembling = **0.760**
+ making ensemble of CATBoost and LGBM = **0.756**
+ LGBM voting with tags (1000) = **0.682**
+ XGBoost = **0.509**

btw, this is the first solo competition I've participated.
