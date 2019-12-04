- (2017 NeurIPS) [Inductive Representation Learning on Large Graphs](https://papers.nips.cc/paper/6703-inductive-representation-learning-on-large-graphs.pdf)

  GraphSAGE: Sampling (a fixed number of) neighbors at each hop

- (2018 KDD) [Large-Scale Learnable Graph Convolutional Networks](https://arxiv.org/pdf/1808.03965.pdf)

  Take k largest features (separately in each feature dimension) from a node's neighbor, and sample a subgraph for training
  
- (2018 ICML) [Learning Steady-States of Iterative Algorithms over Graphs](http://proceedings.mlr.press/v80/dai18a/dai18a.pdf)

- (2018 ICML) [Stochastic Training of Graph Convolutional Networks with Variance Reduction](http://proceedings.mlr.press/v80/chen18p/chen18p.pdf)

  Sampling a small number of neighbors at each hop, but reuse the hidden states of non-sampled nodes to reduce variance. Can greatly reduce the number of samples needed.

- (2018 ICLR) [FastGCN: Fast Learning with Graph Convolutional Networks via Importance Sampling](https://arxiv.org/pdf/1801.10247.pdf)

- (2018 Arxiv) [Towards Efficient Large-Scale Graph Neural Network Computing](https://arxiv.org/pdf/1810.08403.pdf)

- (2019 ICLR workshop) [Advancing GraphSAGE with A Data-Driven Node Sampling](https://arxiv.org/pdf/1904.12935.pdf)

- (2019 KDD) [Cluster-GCN: An Efficient Algorithm for Training Deep and Large Graph Convolutional Networks](https://arxiv.org/pdf/1905.07953.pdf)
