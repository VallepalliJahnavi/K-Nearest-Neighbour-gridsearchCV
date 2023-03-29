# K-Nearest-Neighbour-gridsearchCV
The K-Nearest Neighbors (KNN) GridSearchCV algorithm is a popular method used in machine learning for classification and regression problems. This algorithm can help to find the optimal parameters for the KNN model by performing a grid search over a range of values for the hyperparameters, such as the number of neighbors (K) to use, and the distance metric to measure the similarity between data points.

The GridSearchCV algorithm is a brute-force approach to parameter tuning, where the algorithm exhaustively searches over all possible combinations of hyperparameters to find the best performing model. This is done by constructing a grid of hyperparameters and evaluating each combination using a specified evaluation metric, such as accuracy or mean squared error. The hyperparameters that give the best performing model are then selected as the optimal parameters for the KNN model.

The formula for KNN classification can be defined as follows:

Given a training set of data points X = {x1, x2, …, xn} with corresponding labels Y = {y1, y2, …, yn}, where xi ∈ R^d and yi ∈ {1, 2, …, k} for k classes, and a test data point z ∈ R^d, the KNN algorithm assigns the class label to z based on the k nearest neighbors in X, where k is a positive integer. The class label assigned to z is determined by a majority vote of the k nearest neighbors, using a distance metric to measure the similarity between data points. One popular distance metric is the Euclidean distance, which is defined as:

D(x, y) = √(Σ(xi - yi)^2)

where xi and yi are the i-th features of x and y respectively.
