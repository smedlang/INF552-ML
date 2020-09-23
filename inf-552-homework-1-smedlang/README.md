# Savita Medlang
## INF 552 Summer 2020
#### Homework 1

This assignment analyzes the algorithm KNN by using the Vertebral Column Data Set from:
https://archive.ics.uci.edu/ml/datasets/Vertebral+Column. I looked at different distance metrics, different size training datasets, and different values for K. 


Notes:

  - To choose between k-values with equal error, I found the F-1 score for each and chose the k-value with the highest F-1 score.
  - **(f)** The lowest train error rate is 0.0 when K=1 because the one nearest neighbor will be the exact point that is being tested.
  - I used libraries sklearn, seaborn, matplotlib, pandas, scipy, and numpy to complete this assignment. 
