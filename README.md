# Ways to handle missing Data --Imputer
-----------------------------------------------------------------------------------------------------------------
KNN Imputer and Iterative Imputer
-----------------------------------------------------------------------------------------------------------------

* Simple imputer : It takes **only one feature** into account and fill the missing values with `mean()`,`mode()`or `median()`.
* Multivariate Approch: It takes **multiple features** into account and do the prediction.
 1. **Iterative Imputer**: Iterator imputer create a model and fit on data and predict the missing value.it usees which ever model you say to fit the the model.
 2. **KNN Imputer**: knn imputer use it neighbors data i.e `n_neighbor=3` and get a avarage value and fill the missing value.
  
