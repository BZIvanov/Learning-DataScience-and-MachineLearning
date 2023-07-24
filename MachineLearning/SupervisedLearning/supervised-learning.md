# Train and Test splits

The data used to train a model is typically divided into two main subsets: the training set and the test set.

1. Training Set
   - The training set is the portion of the data used to train the machine learning model. It is the data on which the model learns patterns, relationships, and generalizes from the input features to the target output
   - the model is exposed to the training set during the training process, and it adjusts its internal parameters (weights and biases) based on the input data and the corresponding target labels to minimize the prediction error
2. Test Set
   - the test set is a separate subset of data that is used to evaluate the performance of the trained machine learning model after it has been trained on the training set
   - the model has never seen the data in the test set during the training process, so it serves as an independent and unbiased evaluation of the model's performance on unseen data

## Data example

In the below table we have 5 total rows, 3 of which are train data and 2 will be test data. So we can say that 60% of our data is the train data and the rest 40% will be test data.

| Advertisement | Sales | _type_  |
| ------------- | ----- | ------- |
| 5             | 15    | _train_ |
| 3             | 9     | _train_ |
| 4             | 12    | _train_ |
| 11            | 33    | _test_  |
| 6             | 14    | _test_  |
