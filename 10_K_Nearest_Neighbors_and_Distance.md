# K-Nearest Neighbors (KNN)
KNN is a "lazy learner" because it doesn't learn a discriminative function; it simply stores the training dataset.
## 1. How it Works
To predict the label of a new point:
1. Calculate the distance between the new point and all points in the training set.
2. Pick the K closest points (neighbors).
3. The most common label among those K neighbors is the prediction.

## 2. Distance Metrics

1. Euclidean Distance: The "straight-line" distance: $\sqrt{\sum (x_i - y_i)^2}$
2. Manhattan Distance: The "city block" distance: $\sum |x_i - y_i|$Note: Feature Scaling is mandatory for KNN because the algorithm relies entirely