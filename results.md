## Model Performance without bootstrapping

### Table 1: Performance Metrics for Various Classification Methods


| Classification Method | Accuracy | F1-score | Precision | Recall | AUC |
|-----------------------|----------|----------|-----------|--------|-----|
| Logistic Regression   | 89.8%    | 0.898    | 0.899     | 0.901  | 0.901 |
| SVM                   | 89.9%    | 0.899    | 0.900     | 0.902  | 0.902 |
| Naive Bayes           | 85.1%    | 0.851    | 0.851     | 0.853  | 0.853 |
| Random Forest         | 89.2%    | 0.892    | 0.891     | 0.893  | 0.893 |
| KNN                   | 82.9%    | 0.828    | 0.846     | 0.837  | 0.837 |


### Table 2: Performance Metrics for Neural Network Methods

| NN Method | Accuracy | F1-score | Precision | Recall | AUC |
|-----------|----------|----------|-----------|--------|-----|
| MLP       | 88.2%    | 0.881    | 0.881     | 0.883  | 0.882 |
| NN        | 72.3%    | 0.733    | 0.734     | 0.735  | 0.735 |
| LSTM      | 71.2%    | 0.711    | 0.720     | 0.721  | 0.721 |


## Model Performance with bootstrapping

### Table 3: Performance Metrics for ML Classification Methods

| Classification Method | Accuracy | F1-score | Precision | Recall | AUC |
|-----------------------|----------|----------|-----------|--------|-----|
| Logistic Regression   | 92.5%    | 0.924    | 0.924     | 0.926  | 0.926 |
| SVM                   | 94.0%    | 0.940    | 0.939     | 0.942  | 0.942 |
| Naive Bayes           | 86.1%    | 0.861    | 0.860     | 0.862  | 0.862 |
| Random Forest         | 96.8%    | 0.968    | 0.968     | 0.968  | 0.968 |
| KNN                   | 93.7%    | 0.937    | 0.937     | 0.939  | 0.939 |


### Table 4: Performance Metrics for Neural Network Methods

| NN Method        | Accuracy | F1-score | Precision | Recall | AUC   |
|------------------|----------|----------|-----------|--------|-------|
| MLP              | 95.70%   | 0.957    | 0.956     | 0.958  | 0.958 |
| Feed forward NN  | 74.12%   | 0.741    | 0.741     | 0.741  | 0.741 |
| LSTM             | 73.3%    | 0.729    | 0.732     | 0.728  | 0.728 |
