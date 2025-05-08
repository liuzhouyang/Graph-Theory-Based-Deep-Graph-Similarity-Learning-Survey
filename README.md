<h2 align="center"> <a href="https://openreview.net/forum?id=fHf4jbIfex">[TMLR 2025] Graph Theory-Based Deep Graph Similarity Learning: A Unified Survey of Pipeline, Techniques, and Challenges <div align=center> </a></h2>
<h5 align="center"> If you like our project, please give us a star ⭐ on GitHub.</h5>

This repo lists key papers on recent advancements in graph theory-based deep graph similarity learning, with a focus on approaches approximating subgraph isomorphism, maximum common subgraph, and graph edit distance.
> **Paper**: [Graph Theory-Based Deep Graph Similarity Learning: A Unified Survey of Pipeline, Techniques, and Challenges](https://openreview.net/forum?id=fHf4jbIfex)

> **Authors**: Zhouyang Liu, Ning Liu<sup>†</sup>, Yixin Chen, Ziqing Wen, Jiezhong He, Dongsheng Li<sup>†</sup>

> National University of Defense Technology

> *<sup>†</sup> Corresponding Authors*


If you find our survey useful for your research, please cite the following paper:
```
@article{
liu2025graph,
title={Graph Theory-Based Deep Graph Similarity Learning: A Unified Survey of Pipeline, Techniques, and Challenges},
author={Zhouyang LIU and Ning Liu and Yixin Chen and Ziqing Wen and Jiezhong He and Dongsheng Li},
journal={Transactions on Machine Learning Research},
issn={2835-8856},
year={2025},
url={https://openreview.net/forum?id=fHf4jbIfex},
note={Survey Certification}
}
```


## Paper List

1. <u>SimGNN</u>: **"SimGNN: A Neural Network Approach to Fast Graph Similarity Computation"**. *Yunsheng Bai et al.* WSDM '19. [[Paper](https://dl.acm.org/doi/abs/10.1145/3289600.3290967)] [[Original Code](https://github.com/yunshengb/SimGNN)] [[PyTorch Re-implementation](https://github.com/benedekrozemberczki/SimGNN)]
2. <u>GMN-emb & GMN-match</u>: **"Graph Matching Networks for Learning the Similarity of Graph Structured Objects"**. *Yujia Li et al.* ICML '19. [[Paper](https://proceedings.mlr.press/v97/li19d.html)] [[Original Code](https://github.com/google-deepmind/deepmind-research/tree/master/graph_matching_networks)] [[PyTorch Re-implementation](https://github.com/Lin-Yijie/Graph-Matching-Networks/tree/main/GMN)]
3. <u>NeuroMatch</u>: **"SimGNN: A Neural Network Approach to Fast Graph Similarity Computation"**. *Rex (Zhitao)Ying et al.* arXiv. [[Paper](https://arxiv.org/abs/2007.03092v2)] [[Original Code](https://github.com/snap-stanford/neural-subgraph-learning-GNN)] [[Project Page](https://snap.stanford.edu/subgraph-matching/)]
4. <u>GraphSim</u>: **"Learning-based Efficient Graph Similarity Computation via Multi-Scale Convolutional Set Matching"**. *Yunsheng Bai et al.* AAAI '20. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/5720)] [[Original Code](https://github.com/yunshengb/GraphSim)]
5. <u>Noah</u>: **"Noah: Neural-optimized A* Search Algorithm for Graph Edit Distance Computation"**. *Lei Yang and Lei Zou.* ICDE '21. [[Paper](https://ieeexplore.ieee.org/document/9458863)] [[Original Code](https://github.com/pkumod/Noah-GED)]
6. <u>GOTSim</u>: **"Interpretable Graph Similarity Computation via Differentiable Optimal Alignment of Node Embeddings"**. *Khoa D. Doan. et al.* SIGIR '21. [[Paper](https://dl.acm.org/doi/10.1145/3404835.3462960)] [[Original Code](https://github.com/khoadoan/GraphOTSim)]
7. <u>TaGSim</u>: **"TaGSim: type-aware graph similarity learning and computation"**. *Jiyang Bai and Peixiang Zhao.* VLDB '21. [[Paper](https://dl.acm.org/doi/10.14778/3489496.3489513)] [[Original Code](https://github.com/jiyangbai/TaGSim)]
8. <u>GENN-A*</u>: **"Combinatorial Learning of Graph Edit Distance via Dynamic Embedding"**. *Runzhong Wang et al.* CVPR '21. [[Paper](https://ieeexplore.ieee.org/document/9578389)] [[Original Code](https://github.com/Thinklab-SJTU/GENN-Astar)]
9. <u>GLSearch</u>: **"GLSearch: Maximum Common Subgraph Detection via Learning to Search"**. *Yunsheng Bai et al.* ICML '21. [[Paper](https://proceedings.mlr.press/v139/bai21e.html)] [[Original Code](https://github.com/DerekQXu/GLSearch)]
10. <u>H2MN</u>: **"H2MN: Graph Similarity Learning with Hierarchical Hypergraph Matching Networks"**. *Zhen Zhang et al.* KDD '21. [[Paper](https://dl.acm.org/doi/10.1145/3447548.3467328)] [[Original Code](https://github.com/cszhangzhen/H2MN)]
11. <u>EGSC</u>: **"Slow Learning and Fast Inference: Efficient Graph Similarity Computation via Knowledge Distillation"**. *Can Qin et al.* NeurIPS '21. [[Paper](https://openreview.net/forum?id=Q4SdMvWMxb)] [[Original Code](https://github.com/canqin001/Efficient_Graph_Similarity_Computation)]
12. <u>IsoNet</u>: **"Interpretable Neural Subgraph Matching for Graph Retrieval"**. *Indradyumna Roy et al.* AAAI '22. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/20784)] [[Original Code](https://github.com/Indradyumna/ISONET)]
13. <u>RL-QVO</u>: **"Reinforcement Learning Based Query Vertex Ordering Model for Subgraph Matching"**. *Hanchen Wang et al.* ICDE '22. [[Paper](https://ieeexplore.ieee.org/document/9835186)]
14. <u>Eric</u>: **"Efficient Graph Similarity Computation with Alignment Regularization"**. *Wei Zhuo and Guang Tan.* NeurIPS '22. [[Paper](https://openreview.net/forum?id=lblv6NGI7un)] [[Original Code](https://github.com/JhuoW/ERIC)]
15. <u>MCSNet</u>: **"Maximum Common Subgraph Guided Graph Retrieval: Late and Early Interaction Networks"**. *Indradyumna Roy et al.* NeurIPS '22. [[Paper](https://openreview.net/forum?id=COAcbu3_k4U)] [[Original Code](https://github.com/Indradyumna/MCSNET)]
16. <u>Prune4Sed</u>: **"Towards Accurate Subgraph Similarity Computation via Neural Graph Pruning"**. *Linfeng Liu et al.* TMLR. [[Paper](https://openreview.net/forum?id=CfzIsWWBlo)] [[Original Code](https://github.com/tufts-ml/Prune4SED)]
17. <u>FAST</u>: **"FAST: A Scalable Subgraph Matching Framework over Large Graphs"**. *Linfeng Liu et al.* IEEE HPEC '22. [[Paper](https://ieeexplore.ieee.org/document/9926298)] [[Original Code](https://github.com/yixinchen200S/FAST)]
18. <u>GREED</u>: **"GREED: A Neural Framework for Learning Graph Distance Functions"**. *Rishabh Ranjan et al.* NeurIPS '22. [[Paper](https://openreview.net/forum?id=3LBxVcnsEkV)] [[Original Code](https://github.com/idea-iitd/greed)]
19. <u>D2Match</u>: **"D2Match: Leveraging Deep Learning and Degeneracy for Subgraph Matching"**. *Xuanzhou Liu et al.* ICML '23. [[Paper](https://proceedings.mlr.press/v202/liu23ba.html)] [[Original Code](https://github.com/XuanzhouLiu/D2Match-ICML23)]
20. <u>GEDGNN</u>: **"Computing Graph Edit Distance via Neural Graph Matching"**. *Chengzhi Piao et al.* VLDB '23. [[Paper](https://dl.acm.org/doi/10.14778/3594512.3594514)] [[Original Code](https://github.com/ChengzhiPiao/GEDGNN)]
21. <u>MATA*</u>: **"MATA*: Combining Learnable Node Matching with A* Algorithm for Approximate Graph Edit Distance Computation"**. *Junfeng Liu et al.* CIKM '23. [[Paper](https://dl.acm.org/doi/10.1145/3583780.3614959)] [[Original Code](https://github.com/jfkey/mata)]
22. <u>GED-CDA</u>: **"Graph-Graph Context Dependency Attention for Graph Edit Distance"**. *Ruiqi Jia et al.* ICASSP '23. [[Paper](https://ieeexplore.ieee.org/abstract/document/10094975)]
23. <u>AEDNet</u>: **"AEDNet: Adaptive Edge-Deleting Network For Subgraph Matching"**. *Zixun Lan et al.* PR. [[Paper](https://www.sciencedirect.com/science/article/pii/S0031320322005131)] [[Original Code](https://github.com/zixun-lan/AEDNet-Adaptive-Edge-Deleting-Network-For-Subgraph-Matching)]
