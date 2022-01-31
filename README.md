# Hierarchical-Clustering
1) Run HierarchicalClustering.java
2) Enter the desired file name - "cho.txt" or "iyer.txt". 
3) Output is displayed.

Flow of algorithm
----------------------------
1) Initially, all the points are in one cluster.
2) Calculate the number of distinct clusters from ground truth value, and call it say ‘V’
3) Let the total number of items be ‘N’.
4) Create a new cluster map.
5) Repeat the following steps, N- V times
6) Choose the minimum value from the distance matrix. Let the minimum value be in row ‘i’ and column’j’.
7) Check any other values in the cluster map have same value as ‘i’. If so update all those values including ‘i’ and put in the new cluster
8) Do the same thing for column ‘j’ as well. 
9) This means that all the values in new cluster which have same values as ‘i’ or ‘j’, together with ‘i’ as well as ‘j’ goes to the same cluster.
10) After we have done the above steps for N-V times, the resultant new cluster will contains only that many clusters.
11) The values assigned to new cluster is the final values
