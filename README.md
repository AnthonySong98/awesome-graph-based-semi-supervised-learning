# Awesome Graph-based Semi-supervised Learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
This repository contains graph-based semi-supervised learning (GSSL) papers mentioned in our GSSL survey.

We will update this paper list to include new GSSL papers periodically.

## Citation

Please cite our paper if you find it helpful.
```
@article{DBLP:journals/corr/abs-2102-13303,
  author    = {Zixing Song and
               Xiangli Yang and
               Zenglin Xu and
               Irwin King},
  title     = {Graph-based Semi-supervised Learning: {A} Comprehensive Review},
  journal   = {CoRR},
  volume    = {abs/2102.13303},
  year      = {2021}
}
```

## Content
1. [Survey](#Survey)
2. [Graph Construction Methods](#Graph-Construction-Methods)
    1. [Unsupervised Approaches](#Unsupervised-Approaches)
    1. [Supervised Approaches](#Supervised-Approaches)
3. [Label Inference Methods](#Label-Inference-Methods)
    1. [Graph Regularization Approaches](#Graph-Regularization-Approaches)
    1. [Graph Embedding Approaches](#Graph-Embedding-Approaches)
4. [Applications](#Applications)
    1. [Computer Vision](#Computer-Vision)
    1. [Natural Language Processing](#Natural-Language-Processing)
    1. [Social Networks](#Social-Networks)
    1. [Others](#Others)
5. [Theories](#Theories)
6. [Datasets](#Datasets)
7. [Tutorials](#Tutorials)

## [Survey](#content)

1. **Graph-based Semi-supervised Learning: A Comprehensive Review,** arXiv preprint, 2021.
*Song, Z., Yang, X., Xu, Z., & King, I.*
[paper](https://arxiv.org/abs/2102.13303)
[code](https://github.com/AnthonySong98/awesome-graph-based-semi-supervised-learning)

## [Graph Construction Methods](#content)

### Unsupervised approaches

1. **Topics in graph construction for semi-supervised learning,** technical report, 2009.
*P. P. Talukdar.*
[paper](https://repository.upenn.edu/cgi/viewcontent.cgi?article=1982&context=cis_reports)

1. **Using the mutual k-nearest neighbor graphs for semi-supervised classification on natural language data,** in CoNLL, 2011.
*P. P. Talukdar.*
[paper](https://dl.acm.org/doi/10.5555/2018936.2018954)

1. **Regular graph construction for semi-supervised learning,** in Jounral of physics, 2014.
*L. Berton and A. d. A. Lopes.*
[paper](https://iopscience.iop.org/article/10.1088/1742-6596/490/1/012022/pdf)

1. **Graph construction and b-matching for semi-supervised learning,** in ICML, 2009.
*T. Jebara, J. Wang, and S. Chang.*
[paper](https://icml.cc/Conferences/2009/papers/188.pdf)

1. **Label propagation through linear neighborhoods,** in ICML, 2006.
*F. Wang and C. Zhang.*
[paper](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.76.3431&rep=rep1&type=pdf)

1. **Sparsity induced similarity measure for label propagation,** in ICCV, 2009.
*H. Cheng, Z. Liu, and J. Yang.*
[paper](https://ieeexplore.ieee.org/document/5459267)

1. **Non-negative low rank and sparse graph for semi-supervised learning,** in CVPR, 2012.
*L. Zhuang, H. Gao, Z. Lin, Y. Ma, X. Zhang, and N. Yu.*
[paper](https://ieeexplore.ieee.org/document/6247944)

1. **Manifold-based similarity adaptation for label propagation,** in NIPS, 2013.
*M. Karasuyama and H. Mamitsuka.*
[paper](https://proceedings.neurips.cc/paper/2013/file/3a835d3215755c435ef4fe9965a3f2a0-Paper.pdf)

1. **Large graph construction for scalable semi-supervised learning,** in ICML, 2012.
*W. Liu, J. He, and S. Chang.*
[paper](https://dl.acm.org/doi/10.5555/3104322.3104409)

1. **Influence of graph construction on semi-supervised learning,** in ECML/PKDD, 2013.
*C. A. R. de Sousa, S. O. Rezende, and G. E. A. P. A. Batista.*
[paper](https://link.springer.com/chapter/10.1007/978-3-642-40994-3_11)

### Supervised Approaches

1. **Supervised neighborhood graph construction for semi-supervised classification,** in Pattern Recognition, 2012.
*M. H. Rohban and H. R. Rabiee.*
[paper](https://www.sciencedirect.com/science/article/pii/S0031320311003797)

1. **Graph construction based on labeled instances for semi-supervised learning,** in ICPR, 2014.
*L. Berton and A. d. A. Lopes.*
[paper](https://ieeexplore.ieee.org/document/6977141)

1. **Graph construction for semisupervised learning,** in IJCAI, 2015.
*L. Berton and A. de Andrade Lopes.*
[paper](https://www.ijcai.org/Proceedings/15/Papers/619.pdf)

1. **RGCLI: Robust Graph that Considers Labeled Instances for Semi-Supervised Learning,** in Neurocomputing, 2017.
*L. Berton, T. de Paulo Faleiros, A. Valejo, J. Valverde-Rebaza, and A. de Andrade Lopes.*
[paper](https://www.sciencedirect.com/science/article/pii/S0925231216314680)

1. **Label information guided graph construction for semi-supervised learning,** in TIP, 2017.
*L. Zhuang, Z. Zhou, S. Gao, J. Yin, Z. Lin, and Y. Ma.*
[paper](https://ieeexplore.ieee.org/document/7931596)

1. **Matrix completion for graph-based deep semi-supervised learning,** in AAAI, 2019.
*F. Taherkhani, H. Kazemi, and N. M. Nasrabadi.*
[paper](https://ojs.aaai.org//index.php/AAAI/article/view/4438)

1. **Interactive graph construction for graph-based semi-supervised learning,** in TVCG, 2021.
*C. Chen, Z. Wang, J. Wu, X. Wang, L. Guo, Y. Li, and S. Liu.*
[paper](https://ieeexplore.ieee.org/document/9444198)
[demo](http://datalinker.thuvis.org/)
[code](https://github.com/chencjgene/SSLVis)

1. **Particle competition and cooperation in networks for semi-supervised learning,** in TKDE, 2012.
*F. A. Breve, L. Zhao, M. G. Quiles, W. Pedrycz, and J. Liu.*
[paper](https://ieeexplore.ieee.org/document/5871621)

1. **Particle competition and cooperation in networks for semi-supervised learning with concept drift,** in IJCNN, 2012.
*F. A. Breve and L. Zhao.*
[paper](https://ieeexplore.ieee.org/document/6252617)

1. **Particle competition and cooperation for semi-supervised learning with label noise,** in Neurocomputing, 2015.
*F. A. Breve, L. Zhao, and M. G. Quiles.*
[paper](https://dl.acm.org/doi/abs/10.1016/j.neucom.2014.08.082)

1. **Joint sparse graph and flexible embedding for graph-based semi-supervised learning,** in Neural Networks, 2019.
*F. Dornaika and Y. E. Traboulsi.*
[paper](https://www.sciencedirect.com/science/article/pii/S0893608019300759)

1. **Autoencoder-based graph construction for semi-supervised learning,** in ECCV, 2020.
*M. Kang, K. Lee, Y. H. Lee, and C. Suh.*
[paper](http://csuh.kaist.ac.kr/Suh_ECCV_Kang.pdf)

## [Label Inference Methods](#content)

### Graph Regularization Approaches

1. **A regularization framework for learning from graph data,** in ICML, 2004.
*D. Zhou and B. Scholkopf.*
[paper](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.65.1015&rep=rep1&type=pdf)

1. **Learning on graph with laplacian regularization,** in NeurIPS, 2007.
*R. K. Ando and T. Zhang.*
[paper](https://papers.nips.cc/paper/2006/file/d87c68a56bc8eb803b44f25abb627786-Paper.pdf)

1. **Properly-weighted graph laplacian for semi-supervised learning,** in Applied Mathematics & Optimization, 2019.
*J. Calder and D. Slepcev.*
[paper](https://arxiv.org/abs/1810.04351)

1. **Consistency of semi-supervised learning algorithms on graphs: Probit and one-hot methods,** in JMLR, 2020.
*F. Hoffmann, B. Hosseini, Z. Ren, and A. M. Stuart.*
[paper](https://arxiv.org/abs/1906.07658)

1. **Learning from labeled and unlabeled data with label propagation,** Technical Report, 2002.
*X. Zhu and Z. Ghahramani.*
[paper](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.14.3864&rep=rep1&type=pdf)

1. **Semi-supervised learning using gaussian fields and harmonic functions,** in ICML, 2003.
*X. Zhu, Z. Ghahramani, and J. D. Lafferty.*
[paper](https://dl.acm.org/doi/10.5555/3041838.3041953)

1. **Learning with local and global consistency,** in NeurIPS, 2003.
*D. Zhou, O. Bousquet, T. N. Lal, J. Weston, and B. Scholkopf.*
[paper](https://papers.nips.cc/paper/2003/file/87682805257e619d49b8e0dfdc14affa-Paper.pdf)

1. **Analysis of p-laplacian regularization in semisupervised learning,** in SIMA, 2019.
*D. Slepcev and M. Thorpe.*
[paper](https://epubs.siam.org/doi/pdf/10.1137/17M115222X)

1. **Dynamic label propagation for semi-supervised multi-class multi-label classification,** in ICCV, 2013.
*B. Wang, Z. Tu, and J. K. Tsotsos.*
[paper](https://ieeexplore.ieee.org/document/6751162)

1. **Label propagation via teaching-to-learn and learning-to-teach,** in TNNLS, 2017.
*C. Gong, D. Tao, W. Liu, L. Liu, and J. Yang.*
[paper](https://ieeexplore.ieee.org/document/7447818)

1. **A general graph-based semisupervised learning with novel class discovery,** in Neural Comput. Appl, 2010.
*F. Nie, S. Xiang, Y. Liu, and C. Zhang.*
[paper](https://dl.acm.org/doi/10.1007/s00521-009-0305-8)

1. **Graph based constrained semisupervised learning framework via label propagation over adaptive neighborhood,** in TKDE, 2015.
*Z. Zhang, M. Zhao, and T. W. S. Chow.*
[paper](https://ieeexplore.ieee.org/document/6682892)

1. **Semisupervised dimensionality reduction and classification through virtual label regression,** in IEEE Trans SMC, 2011.
*F. Nie, D. Xu, X. Li, and S. Xiang.*
[paper](https://ieeexplore.ieee.org/document/5645697)

1. **Can the virtual labels obtained by traditional LP approaches be well encoded in wlr?** in TNNLS, 2016.
*Q. Ye, J. Yang, T. Yin, and Z. Zhang.*
[paper](https://ieeexplore.ieee.org/document/7336553)

1. **Adaptive neighborhood propagation by joint l2, 1-norm regularized sparse coding for representation and classification,** in ICDM, 2016.
*L. Jia, Z. Zhang, L. Wang, W. Jiang, and M. Zhao.*
[paper](https://www.computer.org/csdl/proceedings-article/icdm/2016/07837844/12OmNCdk2I7)

1. **Robust adaptive embedded label propagation with weight learning for inductive classification,** in TNNLS, 2018.
*Z. Zhang, F. Li, L. Jia, J. Qin, L. Zhang, and S. Yan.*
[paper](https://ieeexplore.ieee.org/document/8000333)

1. **Robust triple-matrix-recovery-based auto-weighted label propagation for classification,** in TNNLS, 2020.
*H. Zhang, Z. Zhang, M. Zhao, Q. Ye, M. Zhang, and M. Wang.*
[paper](https://ieeexplore.ieee.org/document/8966607)

1. **Label propagation through linear neighborhoods,** in ICML, 2006.
*F. Wang and C. Zhang.*
[paper](https://dl.acm.org/doi/pdf/10.1145/1143844.1143968)

1. **Label propagation through linear neighborhoods,** in TKDE, 2008.
*F. Wang and C. Zhang.*
[paper](https://www.computer.org/csdl/journal/tk/2008/01/ttk2008010055/13rRUx0PqpN)

1. **Linear neighborhood propagation and its applications,** in TPAMI, 2009.
*J. Wang, F. Wang, C. Zhang, H. C. Shen, and L. Quan.*
[paper](https://ieeexplore.ieee.org/document/4620115)

1. **Learning from labeled and unlabeled data on a directed graph,** in ICML, 2005.
*D. Zhou, J. Huang, and B. Scholkopf.*
[paper](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.294.7765&rep=rep1&type=pdf)

1. **Tikhonov regularization and semi-supervised learning on large graphs,** in ICASSP, 2004.
*M. Belkin, I. Matveeva, and P. Niyogi.*
[paper](https://ieeexplore.ieee.org/document/1326716)

1. **Regularization and semisupervised learning on large graphs,** in COLT, 2004.
*M. Belkin, I. Matveeva, and P. Niyogi.*
[paper](https://link.springer.com/chapter/10.1007/978-3-540-27819-1_43)

1. **Manifold regularization:A geometric framework for learning from labeled and unlabeled examples,** in JMLR, 2006.
*M. Belkin, P. Niyogi, and V. Sindhwani.*
[paper](https://www.jmlr.org/papers/v7/belkin06a.html)

1. **Beyond the point cloud: from transductive to semi-supervised learning,** in ICML, 2005.
*V. Sindhwani, P. Niyogi, and M. Belkin.*
[paper](https://dl.acm.org/doi/10.1145/1102351.1102455)

1. **Large-scale graph-based semi-supervised learning via tree laplacian solver,** in AAAI, 2016.
*Y. Zhang, X. Zhang, X. Yuan, and C. Liu.*
[paper](https://dl.acm.org/doi/10.5555/3016100.3016226)

1. **Large graph construction for scalable semi-supervised learning,** in ICML, 2012.
*W. Liu, J. He, and S. Chang.*
[paper](https://dl.acm.org/doi/10.5555/3104322.3104409)

1. **Scalable semi-supervised learning by efficient anchor graph regularization,** in TKDE, 2016.
*M. Wang, W. Fu, S. Hao, D. Tao, and X. Wu.*
[paper](https://ieeexplore.ieee.org/document/7420705)

1. **Learning on big graph: Label inference and regularization with anchor hierarchy,** in TKDE, 2017.
*M. Wang, W. Fu, S. Hao, H. Liu, and X. Wu.*
[paper](https://ieeexplore.ieee.org/document/7820177)

1. **Deformed graph laplacian for semisupervised learning,** in TNNLS, 2015.
*C. Gong, T. Liu, D. Tao, K. Fu, E. Tu, and J. Yang.*
[paper](https://ieeexplore.ieee.org/document/7010929)

1. **Poisson learning: Graph based semi-supervised learning at very low label rates,** in ICML, 2020.
*J. Calder, B. Cook, M. Thorpe, and D. Slepcev.*
[paper](http://proceedings.mlr.press/v119/calder20a/calder20a.pdf)
[code](https://github.com/jwcalder/GraphLearning)

### Graph Embedding Approaches