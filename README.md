# k-means-clustering-from-scratch
this k-means classifier is made wholly on python and numpy, while using matplotlib to plot the graphs.

the code is in the "k-means-clustering" file. it contains two method of classifying the points, in the first method, i've taken the cetnroids from the dataset itself. the function for clustering returns the variation for each iteration, the clusters for the run with the least variation is saved as the final cluster. which basically means that it doesn't work by "fixing" the centroids choosen, but by taking random ones and keeping the best ones. the second method initially generates a centroid in the range of the dataset and clusters points according to them, then in each iteration, the new centroids of each cluster are found by taking the mean of all the points in that cluster. basically, each iteration brings the centroids to a "stable" mean position. I've also up[dated the code so as to print the variation in second method also to compare the best variance achieved by method 1 and 2.

i've labelled each part of the code so it'll be easy to read if you just skim through it.

see you around next time :)
