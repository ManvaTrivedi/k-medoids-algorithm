# k-medoids-algorithm
Implementation of this program gives clustering solution using k-medoids algorithm

The program will take two inputs: a data file containing multiple continuous features and a value for k. Then, it calculates the dissimilarity matrix and then applies the k-medoids algorithm.

The clustering process continues until cluster assignments do not change or maximum 100 iterations have been completed and calculates average silhouette width for the final clustering solution.
The program adds a new column containing cluster ids (1, 2, 3, …, k) to the original input file and save it to clusters_k.csv, where k is the number of clusters.
Finally, the program shows average silhouette width in the console.
