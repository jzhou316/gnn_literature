#### Graph Pooling, Sparsify/Coarsen Graphs, Hierarchical Graph Representations

1. [Hierarchical Graph Representation Learning with Differentiable Pooling](https://arxiv.org/pdf/1806.08804.pdf) (NIPS 2018)
   
   DiffPool
   
   official github [repo](https://github.com/RexYing/diffpool), and also in PyG and DGL

2. [An End-to-End Deep Learning Architecture for Graph Classification](https://www.cse.wustl.edu/~muhan/papers/AAAI_2018_DGCNN.pdf) (AAAI 2018)

   SortPool, DGCNN
   
   official github [repo](https://github.com/muhanzhang/DGCNN)

3. [Towards Sparse Hierarchical Graph Classifiers](http://petar-v.com/spcls_nips18_camera.pdf) (NIPS workshop 2018)
   
4. [Self-Attention Graph Pooling](https://arxiv.org/pdf/1904.08082.pdf) (ICML 2019)

   SAGPool
  
5. [Graph U-Nets](https://arxiv.org/pdf/1905.05178.pdf) (ICML 2019)

   gPool
   
   relevant github [repo](https://github.com/bknyaz/graph_nn), [here](https://github.com/HongyangGao/gunet) and [here](https://github.com/rusty1s/pytorch_geometric/issues/37)
   
   **Another two similar papers by the same author:**
   
   [Large-Scale Learnable Graph Convolutional Networks](https://arxiv.org/pdf/1808.03965.pdf) (KDD 2018)
   
   LGCL
   
   [Graph Representation Learning via Hard and Channel-Wise Attention Networks](https://arxiv.org/pdf/1907.04652.pdf) (KDD 2019)
   
   hGAO

   All of the above papers calculate a score for each node, and select top k nodes by sorting the scores.

6. [Towards Interpretable Molecular Graph Representation Learning](https://openreview.net/pdf?id=HyljY04YDB) (ICLR submitted 2019)(Rejected)
   
   LaPool ([code](https://anonymous.4open.science/r/941cb9ee-302f-4c81-bbf9-abcff1e98894/))

7. [Are Powerful Graph Neural Nets Necessary? A Dissection on Graph Classification](https://openreview.net/pdf?id=BJxQxeBYwH) (ICLR submitted 2019)
   
   GFN
   
   official github [repo](https://github.com/chentingpc/gfn)
   
8. [StructPool: Structured Graph Pooling via Conditional Random Fields](https://openreview.net/pdf?id=BJxg_hVtwH) (ICLR submitted 2019)

   StructPool

9. [Unsupervised Learning of Graph Hierarchical Abstractions with Differentiable Coarsening and Optimal Transport](https://openreview.net/pdf?id=Bkf4XgrKvS) (ICLR submitted 2019) (Rejected)

   OTCoarsening
   
   official github [repo](https://github.com/anonymousOPT/OTCoarsening)
   
10. [Edge Contraction Pooling for Graph Neural Networks](https://arxiv.org/pdf/1905.10990.pdf)

    [Towards Graph Pooling by Edge Contraction](https://graphreason.github.io/papers/17.pdf) (ICLR 2019 Workshop)
    
    EdgePool
