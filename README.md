# Graph Neural Networks (GNNs)

In this notebook we investigate two GCN flavors - for directed and undirected graphs.
First, we look into the popular undirected graph example of Zachary's karate club network, and then look into an analytical implementation of the GCNConv, a flavor spiked to suit directed graphs and train it with the WikiCS dataset.

Model architectures/parameterizations inspired by the following articles:
- T. Kipf and M. Welling, “Semi-Supervised Classification with Graph Convolutional Networks”, 2016, arXiv: 1609.02907
- M. Schlichtkrull, "Modeling Relational Data with Graph Convolutional Networks", 2017, arXiv: 1703.06103
- P. Mernyei and C. Cangea, "Wiki-CS: A Wikipedia-Based Benchmark for Graph Neural Networks", 2022, arXiv: 2007.02901

![SegmentLocal](emdir.gif "gif")
