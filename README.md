# KNN_Scratch
Python code for KNN implementation from scratch

Steps involved:
  Calculate d vector where d denotes the Euclidean distance between the training points and each test point.
  
  Arrange the calculated n Euclidean distances in increasing order.
  
  Let k be a +ve integer, take the first k distances from this sorted list.
  
  Find those k-points from training labels corresponding to these k-distances.
  
  Let ki denotes the number of points belonging to the ith class among k points i.e. k ≥ 0 where i = (1....n)
  
    ki, which has highest occurance assign the class i to the test point.
