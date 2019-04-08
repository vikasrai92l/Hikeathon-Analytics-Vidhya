# Hikeathon-Analytics-Vidhya

The Data Size was huge,so could not use full data. Worked with 10% of data by random sampling.
LightGBM is used.
Parameters are 
params = {
    'objective' :'binary',
    'learning_rate' : 0.1,
    'num_leaves' : 76,
    'feature_fraction': 0.64, 
    'bagging_fraction': 0.8, 
    'boosting_type' : 'gbdt',
    'metric': 'binary_logloss'
}

Accuracy obtained was 84.93%

Secured Rank is 80
