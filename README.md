# k-means-clustering-from-scratch
this k-means classifier is made wholly on python and numpy, while using matplotlib to plot the graphs.

the code is in the "k-means-classification" file. it contains two method of classifying the points, in the first method, i've taken the cetnroids from the dataset itself. the function for classification returns the variation for each iteration, the classification for the run with the least variation is saved as the final classification. which basically means that it doesn't work by "fixing" the centroids choosen, but by taking random ones and keeping the best ones. the second method initially generates a centroid in the range of the dataset and classifies points according to them, then in each iteration, the new centroids of each class are found by taking the mean of all the points in that class. basically, each iteration brings the centroids to a "stable" mean position.

i've labelled each part of the code so it'll be easy to read if you just skim through it.

see you around next time :)
