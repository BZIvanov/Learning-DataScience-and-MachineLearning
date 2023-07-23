# Scikit-Learn

Scikit-Learn is a library containing many machine learning algorithms.

### Using scikit-learn for _supervised_ machine learning process

Below is some pseudo code for how generally scikit-learn works:

```python
from sklearn.some_model_family import SomeModelAlgorithm

my_model = SomeModelAlgorithm(some_params)
my_model.fit(X_train, y_train) # we provide some training data for the model
my_predictions = my_model.predict(X_test)

# and then we import some model metrics
from sklearn.metrics import some_metric
my_performace = some_metric(y_test, predictions)
```
