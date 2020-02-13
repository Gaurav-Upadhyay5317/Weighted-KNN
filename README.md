# Weighted-KNN

Weighted kNN is a modified version of k nearest neighbors. 
One of the many issues that affect the performance of the kNN algorithm is the choice of the hyperparameter k.
If k is too small, the algorithm would be more sensitive to outliers.
If k is too large, then the neighborhood may include too many points from other classes.
Another issue is the approach to combining the class labels. 
The simplest method is to take the majority vote, but this can be a problem if the nearest neighbors vary widely in their distance and
the closest neighbors more reliably indicate the class of the object.
