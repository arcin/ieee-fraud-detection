# ieee-fraud-detection
An example of logistic regression being used to detect fraud

## Dataset
The kaggle dataset can be found [here](https://www.kaggle.com/c/ieee-fraud-detection/data).

**A couple of challenges with the dataset**
1. The dataset uses PCA to hide sensitive information, making it difficult to understand what features have the best correlation with fraud.
2. There are a lot of missing values. Over Half of the hundreds of thousands of rows have missing data.
3. There is a large class imbalance. around 4 percent of the data is fraud.

### Some approaches used in this solution
1. One-hot encoding  categorical variables.
2. Filtering columns that have over 17% missing values.
3. Plotting distribution of null values to get an intuition of what columns may be important.
