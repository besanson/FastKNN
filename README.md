# FastKNN: A faster way to do K Nearest Neighbour

Please use `devtools` so you can install this package in R.

The command to do this is `devtools::install_github("besanson/FastKNN").

After this just do `library(FastKNN)` as with a normal R package.

Remember that this Package is under `GPL-3 License`.

`FastKNN` consist of several functions:

1. `k.nearest.neighbors`: gives the list of points (k neigbours) that are closest to the row i in descending order. Please see ?k.nearest.neighbors for further details.

2. `knn_test_function`: returns the labels for a test set using the KNN Clasification method.Please see ?knn_test_function for further details and an `**Example**`.

3. `knn_training_function`: returns the labels for a training set using the KNN Clasification method. Please see ?knn_training_function for further details.

4. `Distance_for_KNN_test`: returns the distance matrix between the test set and the training set. Please see ?Distance_for_KNN_test for further details.



