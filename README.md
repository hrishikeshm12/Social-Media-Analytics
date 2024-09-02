# Social-Media-Analytics

Description:

The main purpose of this project is to predict the total social media usage of a particular
individual based on the time spent on social media on various platforms such as WhatsApp,
Instagram and Facebook. We aim to predict which platform is being used the most by an
individual based on time spent on weekends versus time spent on weekdays. Using Instagram
followers and the number of posts, the algorithm will predict whether the user has a high or low
interaction activity status.

Dataset used:

The data set was collected from the Kaggle website. The dataset was named as - Social Media
Usage Analysis. The dataset contains 26 variables (columns) and 1628 records (rows). The
datatypes in the dataset were of object data type initially, which we preprocessed to fit into the
models and to get a better accuracy performance of the models used.


**Performance of Optimized Models Over Baseline in terms of RMSE and R2 Score**

| No. | Model             | Baseline Models |       | Optimized Models |       | Improvement          |
|-----|-------------------|-----------------|-------|------------------|-------|----------------------|
|     |                   | RMSE Score      | R2 Score | RMSE Score       | R2 Score |                      |
| 1   | Linear Regression | 1241.29         | 0.5598 | 1004.66          | 0.7025 | (25.49% ↑)           |
| 2   | Poly. Regression  | 1180.45         | 0.5772 | 1092.13          | 0.6410 | (11.05% ↑)           |
| 3   | Random Forest     | 1015.76         | 0.6959 | 982.32           | 0.7156 | (02.83% ↑)           |
| 4   | Decision Tree     | 1079.00         | 0.6568 | 1005.60          | 0.7020 | (06.88% ↑)           |
| 5   | XGBoost           | 982.97          | 0.7152 | 967.07           | 0.7243 | (01.27% ↑)           |
| 6   | LightGBM          | 1036.92         | 0.6834 | 974.17           | 0.7203 | (05.40% ↑)           |
| 7   | CatBoost          | 968.62          | 0.7234 | 956.94           | 0.7298 | (00.88% ↑)           |
| 8   | AdaBoost          | 1154.73         | 0.6074 | 1028.48          | 0.6882 | (13.30% ↑)           |
| 9   | Lasso Regression  | 1005.11         | 0.7023 | 1005.60          | 0.7020 | (00.04% ↓)           |
| 10  | Ridge Regression  | 1005.10         | 0.7023 | 1005.83          | 0.7018 | (00.07% ↓)           |
| 11  | KNN               | 1112.68         | 0.6351 | 1073.97          | 0.6607 | (04.03% ↑)           |
| 12  | SVM               | 1030.06         | 0.6873 | 1041.61          | 0.6807 | (00.96% ↓)           |

