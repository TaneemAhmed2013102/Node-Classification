# Node-Classification
Node classification is a fundamental task in graph-based machine learning where the goal is to predict the labels of nodes using both their features and the structure of the graph. Three widely used benchmark datasets for this task are CiteSeer, Cora, and PubMed, which represent citation networks of scientific papers.

In these datasets, each node corresponds to a scientific paper, and an edge between two nodes represents a citation link. The features are typically derived from the content of the papers, such as word vectors or bag-of-words representations. Each paper (node) is also associated with a label indicating its topic or category, which is what the model aims to predict.

The Cora dataset consists of 2,708 nodes and 5,429 edges with papers classified into 7 distinct categories. CiteSeer includes 3,327 nodes and 4,732 edges across 6 classes. The PubMed dataset is larger, containing 19,717 nodes and 44,338 edges with 3 categories. These datasets are semi-supervised, meaning only a small portion of the node labels are known during training.
