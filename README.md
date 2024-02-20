# Wholesale-Classification
**1 K-nearest neighbor classification**

1. Implement k-nn and test on the dataset. Calculate the classification error? (by comparing
the class labels obtained with the prediction and the original labels of test data)
2. Vary the value of k
3. Try to normalize the input dataset, is the performance better?
4. Apply PCA and SVD on the dataset, then what is the performance of k-nn on the new projected data?
5. Propose an approach to improve the performance of k-nn with the help of k-cross validation.

**2 Perceptron classifier**

  Plot linear classifiers for dataset (using PCA or SVD to reduce the number of dimensions to 2D)

  # Maternal Health Risk classification
**1 Decition Tree - DT**
1. Select a dataset with available label (for example Iris dataset)
2. Divide the original dataset into two subsets: one for training (80%) and one for testing (20%).
3. Build a DT for the training subset and test the built model for data from the testing subset.
Note: Try the “tree” package from sklearn in Python or the function fitctree() in Matlab.
4. Calculate the error of classification.

**2 Random Forests**
1. Select a high dimensional dataset with avaiable label.
2. Create K = 100 training set (using cross-validation or bagging technique), and build 1 testing
set.
3. Build a DT for each training set.
4. Classify data from the testing set using one DT and all DTs and calculate the error of classification.
