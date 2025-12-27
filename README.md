1. INTRODUCTION: 

We used a machine learning method called K-Nearest Neighbors (KNN) to classify different types of Iris flowers. KNN is a simple but powerful way to categorize data points by looking at what their closest neighbors in the dataset are. 

 

2. OBJECTIVES/AIM 

To see how well KNN can identify Iris flower species using the famous Iris dataset, while testing different amounts of training data and different settings for *k* (the number of neighbors checked). 

3. DATASET 
We used the Iris dataset, which has 150 flower samples. Each flower has four measurements: 

Sepal length 
Sepal width 
Petal length 
Petal width 
and belongs to one of three species: setosa, versicolor, or virginica. There were 50 flowers from each type, and no missing data. 

 

4. PREPROCESSING STEPS 
No missing values to deal with. 
We scaled all measurements to a 0–1 range so no single feature would dominate the results. 
We split the data into training and testing sets multiple ways: 50/50, 60/40, 70/30, and 80/20. 
How KNN Was Built 
We coded KNN from scratch using Python and NumPy. 
Used Euclidean distance to find nearest neighbors. 
Tried different values for *k*: 1, 3, 5, 7, 9, 11, 13, 15. 

 

5. CONCLUSION 

KNN worked really well for classifying Iris flowers, especially when we scaled the data and picked the right training split and *k* value. The model was very accurate and reliable for this dataset. 
