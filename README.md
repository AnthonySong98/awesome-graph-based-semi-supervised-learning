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
    1. [Biomedical Science](#Biomedical-Science)
    1. [Others](#Others)
5. [Theory](#Theory)
6. [Datasets](#Datasets)
7. [Tutorials](#Tutorials)
8. [Books](#Books)

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

1. **Regular graph construction for semi-supervised learning,** in Journal of physics, 2014.
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

1. **Graphebm: Energy-based graph construction for semi-supervised learning,** in ICDM, 2020.
*Z. Chen, H. Cao, and K. C. Chang.*
[paper](https://ieeexplore.ieee.org/document/9338415)

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

1. **Semi-supervised learning by mixed label propagation,** in AAAI, 2007.
*Tong, W. and Jin, R.*
[paper](https://www.aaai.org/Papers/AAAI/2007/AAAI07-103.pdf)

1. **Tikhonov regularization and semi-supervised learning on large graphs,** in ICASSP, 2004.
*M. Belkin, I. Matveeva, and P. Niyogi.*
[paper](https://ieeexplore.ieee.org/document/1326716)

1. **Manifold regularization:A geometric framework for learning from labeled and unlabeled examples,** in JMLR, 2006.
*M. Belkin, P. Niyogi, and V. Sindhwani.*
[paper](https://www.jmlr.org/papers/v7/belkin06a.html)

1. **Beyond the point cloud: from transductive to semi-supervised learning,** in ICML, 2005.
*V. Sindhwani, P. Niyogi, and M. Belkin.*
[paper](https://dl.acm.org/doi/10.1145/1102351.1102455)

1. **Hyperparameter and kernel learning for graph based semi-supervised classification,** in NeurIPS, 2005.
*Kapoor, A., Ahn, H., Qi, Y. and Picard, R.*
[paper](https://proceedings.neurips.cc/paper/2005/file/c429429bf1f2af051f2021dc92a8ebea-Paper.pdf)

1. **Harmonic mixtures: combining mixture models and graph-based methods for inductive and scalable semi-supervised learning,** in ICML, 2005.
*Zhu, X. and Lafferty, J.*
[paper](https://dl.acm.org/doi/abs/10.1145/1102351.1102484)

1. **Graph based semi-supervised learning with sharper edges,** in ECML, 2005.
*Shin, H.H., Hill, N.J. and Rätsch, G.*
[paper](https://link.springer.com/chapter/10.1007/11871842_39)

1. **Graph-based semi-supervised learning as a generative model,** in IJCAI, 2007.
*He, J., Carbonell, J.G. and Liu, Y.*
[paper](https://www.aaai.org/Papers/IJCAI/2007/IJCAI07-401.pdf)

1. **Active model selection for graph-based semi-supervised learning,** in ICASSP, 2008.
*Zhao, B., Wang, F., Zhang, C. and Song, Y.*
[paper](https://ieeexplore.ieee.org/abstract/document/4518001)

1. **Prototype vector machine for large scale semi-supervised learning,** in ICML, 2009.
*Zhang, K., Kwok, J.T. and Parvin, B.*
[paper](https://dl.acm.org/doi/abs/10.1145/1553374.1553531)

1. **Generalized optimization framework for graph-based semi-supervised learning,** in SDM, 2012.
*Avrachenkov, K., Mishenin, A., Gonçalves, P. and Sokol, M.*
[paper](https://epubs.siam.org/doi/abs/10.1137/1.9781611972825.83)

1. **An iterative fusion approach to graph-based semi-supervised learning from multiple views,** in PAKDD, 2014.
*Wang, Y., Pei, J., Lin, X., Zhang, Q. and Zhang, W.*
[paper](https://link.springer.com/chapter/10.1007/978-3-319-06605-9_14)

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

1. **Learning flexible graph-based semi-supervised embedding,** in IEEE transactions on cybernetics, 2015.
*Dornaika, F. and El Traboulsi, Y.*
[paper](https://ieeexplore.ieee.org/abstract/document/7050298)

1. **Efficient label propagation,** in ICML, 2014.
*Y. Fujiwara and G. Irie.*
[paper](http://proceedings.mlr.press/v32/fujiwara14.pdf)

1. **Scalable graph-based semi-supervised learning through sparse bayesian model,** in TKDE, 2017.
*Jiang, B., Chen, H., Yuan, B., & Yao, X.*
[paper](https://ieeexplore.ieee.org/document/8027086)

1. **Graph-based semi-supervised learning for relational networks,** in SDM, 2017.
*Peel, L.*
[paper](https://epubs.siam.org/doi/abs/10.1137/1.9781611974973.49)

1. **Interpretable graph-based semi-supervised learning via flows,** in AAAI, 2018.
*Rustamov, R.M. and Klosowski, J.T.*
[paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPaper/16396)

1. **Lightweight label propagation for large-scale network data,** in IJCAI, 2018.
*D. Liang and Y. Li.*
[paper](https://www.ijcai.org/proceedings/2018/0475.pdf)

1. **Label propagation for deep semi-supervised learning,** in CVPR, 2019.
*A. Iscen, G. Tolias, Y. Avrithis, and O. Chum.*
[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Iscen_Label_Propagation_for_Deep_Semi-Supervised_Learning_CVPR_2019_paper.pdf)
[code](https://github.com/ahmetius/LP-DeepSSL)

1. **Consistency of semi-supervised learning algorithms on graphs: Probit and one-hot methods,** in JMLR, 2020.
*F. Hoffmann, B. Hosseini, Z. Ren, and A. M. Stuart.*
[paper](https://arxiv.org/abs/1906.07658)

1. **Uncertainty aware graph gaussian process for semi-supervised learning,** in AAAI, 2020.
*Liu, Z.Y., Li, S.Y., Chen, S., Hu, Y. and Huang, S.J.*
[paper](https://ojs.aaai.org/index.php/AAAI/article/view/5934)

1. **Understanding the Success of Graph-based Semi-Supervised Learning using Partially Labelled Stochastic Block Model,** in IJCAI, 2020.
*Saha, A., Sheshadri, S., Datta, S., Ganguly, N., Makhija, D. and Patel, P.*
[paper](https://www.ijcai.org/Proceedings/2020/0187.pdf)

1. **Poisson learning: Graph based semi-supervised learning at very low label rates,** in ICML, 2020.
*J. Calder, B. Cook, M. Thorpe, and D. Slepcev.*
[paper](http://proceedings.mlr.press/v119/calder20a/calder20a.pdf)
[code](https://github.com/jwcalder/GraphLearning)

1. **A simple graph-based semi-supervised learning approach for imbalanced classification,** in Pattern Recognition, 2021.
*Deng, J. and Yu, J.G.*
[paper](https://www.sciencedirect.com/science/article/pii/S0031320321002132)

1. **Lightweight label propagation for large-scale network data,** in TKDE, 2021.
*Y. Li and D. Liang.*
[paper](https://ieeexplore.ieee.org/abstract/document/8883067)

1. **Rethinking graph regularization for graph neural networks,** in AAAI, 2021.
*H. Yang, K. Ma, and J. Cheng.*
[paper](https://arxiv.org/abs/2009.02027)
[code](https://github.com/yang-han/P-reg)

### Graph Embedding Approaches

1. **Nonlinear dimensionality reduction by locally linear embedding,** in Science, 2000.
*S. T. Roweis and L. K. Saul.*
[paper](https://science.sciencemag.org/content/290/5500/2323)

1. **Laplacian eigenmaps and spectral techniques for embedding and clustering,** in NeurIPS, 2002.
*M. Belkin and P. Niyogi.*
[paper](https://papers.nips.cc/paper/2001/file/f106b7f99d2cb30c3db1c3cc0fde9ccb-Paper.pdf)

1. **Grarep: Learning graph representations with global structural information,** in CIKM, 2015.
*S. Cao, W. Lu, and Q. Xu.*
[paper](https://dl.acm.org/doi/10.1145/2806416.2806512)
[code](https://github.com/benedekrozemberczki/GraRep)

1. **Asymmetric transitivity preserving graph embedding,** in KDD, 2016.
*M. Ou, P. Cui, J. Pei, Z. Zhang, and W. Zhu.*
[paper](https://dl.acm.org/doi/10.1145/2939672.2939751)
[code](https://github.com/ZW-ZHANG/HOPE)

1. **Deepwalk: Online learning of social representations,** in KDD, 2014.
*B. Perozzi, R. Al-Rfou, and S. Skiena.*
[paper](https://dl.acm.org/doi/10.1145/2623330.2623732)
[code](https://github.com/phanein/deepwalk)

1. **Revisiting semi-supervised learning with graph embeddings,** in ICML, 2016.
*Z. Yang, W. Cohen, and R. Salakhudinov*
[paper](https://dl.acm.org/doi/10.5555/3045390.3045396)
[code](https://github.com/kimiyoung/planetoid)

1. **node2vec: Scalable feature learning for networks,** in KDD, 2016.
*A. Grover and J. Leskovec.*
[paper](https://dl.acm.org/doi/10.1145/2939672.2939754)
[code](https://github.com/aditya-grover/node2vec)

1. **Line: Large-scale information network embedding,** in WWW, 2015.
*J. Tang, M. Qu, M. Wang, M. Zhang, J. Yan, and Q. Mei.*
[paper](https://dl.acm.org/doi/10.1145/2736277.2741093)
[code](https://github.com/tangjianpku/LINE)

1. **HARP: hierarchical representation learning for networks,** in AAAI, 2018.
*H. Chen, B. Perozzi, Y. Hu, and S. Skiena.*
[paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16273/15922)
[code](https://github.com/GTmac/HARP)

1. **Network embedding as matrix factorization: Unifying deepwalk, line, pte, and node2vec,** in WSDM, 2018.
*J. Qiu, Y. Dong, H. Ma, J. Li, K. Wang, and J. Tang.*
[paper](https://dl.acm.org/doi/10.1145/3159652.3159706)
[code](https://github.com/xptree/NetMF)

1. **Structural deep network embedding,** in KDD, 2016.
*D. Wang, P. Cui, and W. Zhu.*
[paper](https://dl.acm.org/doi/10.1145/2939672.2939753)
[code](https://github.com/suanrong/SDNE)

1. **Deep neural networks for learning graph representations,** in AAAI, 2016.
*S. Cao, W. Lu, and Q. Xu.*
[paper](https://dl.acm.org/doi/10.5555/3015812.3015982)
[code](https://github.com/apoorvavinod/DNGR)

1. **Learning graph representations with recurrent neural network autoencoders,**, in KDD, 2018.
*A. Taheri, K. Gimpel, and T. Berger-Wolf.*
[paper](https://www.kdd.org/kdd2018/files/deep-learning-day/DLDay18_paper_27.pdf)

1. **Deep recursive network embedding with regular equivalence,** in KDD, 2018.
*K. Tu, P. Cui, X. Wang, P. S. Yu, and W. Zhu.*
[paper](https://dl.acm.org/doi/10.1145/3219819.3220068)
[code](https://github.com/tadpole/DRNE)

1. **Variational graph auto-encoders,** arXiv preprint, 2016.
*T. N. Kipf and M. Welling.*
[paper](https://arxiv.org/pdf/1611.07308.pdf%5D)
[code](https://github.com/tkipf/gae)

1. **Learning graph embedding with adversarial training methods,** in IEEE Transactions on Cybernetics, 2019.
*S. Pan, R. Hu, S.-f. Fung, G. Long, J. Jiang, and C. Zhang.*
[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8822591)

1. **Semi-supervised classification with graph convolutional networks,** in ICLR, 2017.
*T. N. Kipf and M. Welling.*
[paper](https://openreview.net/pdf?id=SJU4ayYgl)
[code](https://github.com/tkipf/gcn)

1. **Graph convolutional networks using heat kernel for semi-supervised learning,** in IJCAI, 2019.
*Xu, B., Shen, H., Cao, Q., Cen, K., & Cheng, X.*
[paper](https://arxiv.org/abs/2007.16002)

1. **Deeper insights into graph convolutional networks for semi-supervised learning,** in AAAI, 2018.
*Li, Q., Han, Z., & Wu, X. M.*
[paper](https://arxiv.org/abs/1801.07606)
[code](https://github.com/liqimai/gcn/tree/AAAI-18/)

1. **Dual graph convolutional networks for graph-based semi-supervised classification,** in WWW, 2018.
*Zhuang, C. and Ma, Q.*
[paper](https://dl.acm.org/doi/abs/10.1145/3178876.3186116)
[code](https://github.com/ZhuangCY/DGCN)

1. **Label efficient semi-supervised learning via graph filtering,** in CVPR, 2019.
*Li, Q., Wu, X. M., Liu, H., Zhang, X., & Guan, Z.*
[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Label_Efficient_Semi-Supervised_Learning_via_Graph_Filtering_CVPR_2019_paper.pdf)
[code](https://github.com/liqimai/Efficient-SSL)

1. **Simplifying graph convolutional networks,** in ICML, 2019.
*F. Wu, A. H. S. Jr., T. Zhang, C. Fifty, T. Yu, and K. Q. Weinberger.*
[paper](http://proceedings.mlr.press/v97/wu19e/wu19e.pdf)
[code](https://github.com/Tiiiger/SGC)

1. **Deep sets,** in NeurIPS, 2017.
*M. Zaheer, S. Kottur, S. Ravanbakhsh, B. Poczos, R. R. Salakhutdinov, and A. J. Smola.*
[paper](https://papers.nips.cc/paper/2017/file/f22e4747da1aa27e363d86d40ff442fe-Paper.pdf)
[code](https://github.com/manzilzaheer/DeepSets)

1. **Janossy pooling: Learning deep permutation-invariant functions for variablesize inputs,** in ICLR, 2019.
*R. L. Murphy, B. Srinivasan, V. A. Rao, and B. Ribeiro.*
[paper](https://openreview.net/pdf?id=BJluy2RcFm)
[code](https://github.com/PurdueMINDS/JanossyPooling)

1. **Graph attention networks,** in ICLR, 2018.
*P. Velickovic, G. Cucurull, A. Casanova, A. Romero, P. Lio, and Y. Bengio.*
[paper](https://arxiv.org/pdf/1710.10903.pdf)
[code](https://github.com/PetarV-/GAT)

1. **Inductive representation learning on large graphs,** in NeurIPS, 2017.
*W. Hamilton, Z. Ying, and J. Leskovec.*
[paper](https://dl.acm.org/doi/10.5555/3294771.3294869)
[code](https://github.com/williamleif/GraphSAGE)

1. **Column networks for collective classification,** in AAAI, 2017.
*T. Pham, T. Tran, D. Q. Phung, and S. Venkatesh.*
[paper](https://dl.acm.org/doi/10.5555/3298483.3298597)
[code](https://github.com/trangptm/Column_networks)

1. **Gated graph sequence neural networks,** in ICLR, 2016.
*Y. Li, D. Tarlow, M. Brockschmidt, and R. S. Zemel.*
[paper](https://arxiv.org/pdf/1511.05493.pdf)
[code](https://github.com/yujiali/ggnn)

1. **Learning a SAT solver from single-bit supervision,** in ICLR, 2019.
*D. Selsam, M. Lamm, B. Bunz, P. Liang, L. de Moura, and D. L. Dill.*
[paper](https://arxiv.org/pdf/1802.03685.pdf)
[code](https://github.com/dselsam/neurosat)

1. **Representation learning on graphs with jumping knowledge networks,** in ICML, 2018.
*K. Xu, C. Li, Y. Tian, T. Sonobe, K. Kawarabayashi, and S. Jegelka.*
[paper](https://arxiv.org/pdf/1806.03536.pdf)
[code](https://pytorch-geometric.readthedocs.io/en/latest/_modules/torch_geometric/nn/models/jumping_knowledge.html#JumpingKnowledge)

1. **Infograph: Unsupervised and semi-supervised graph-level representation learning via mutual information maximization,** in ICLR, 2020.
*F. Sun, J. Hoffmann, V. Verma, and J. Tang.*
[paper](https://openreview.net/forum?id=r1lfF2NYvH)
[code](https://github.com/fanyun-sun/InfoGraph)

1. **A flexible generative framework for graph-based semi-supervised learning,** in NeurIPS, 2019.
*J. Ma, W. Tang, J. Zhu, and Q. Mei.*
[paper](https://arxiv.org/abs/1905.10769)
[code](https://github.com/jiaqima/G3NN)

1. **Non parametric graph learning for bayesian graph neural networks,** in UAI, 2020.
*S. Pal, S. Malekmohammadi, F. Regol, Y. Zhang, Y. Xu, and M. Coates.*
[paper](http://proceedings.mlr.press/v124/pal20a.html)

1. **Graph-based semisupervised learning with non-ignorable non-response,** in NeurIPS, 2019.
*F. Zhou, T. Li, H. Zhou, H. Zhu, and Y. Jieping.*
[paper](https://proceedings.neurips.cc/paper/2019/file/42547f5a44d87da3bc40ee5d09624606-Paper.pdf)
[code](https://github.com/BIG-S2/keras-gnm)

1. **Graph agreement models for semisupervised learning,** in NeurIPS, 2019.
*O. Stretcu, K. Viswanathan, D. Movshovitz-Attias, E. Platanios, S. Ravi, and A. Tomkins.*
[paper](https://papers.nips.cc/paper/2019/file/4772c1b987f1f6d8c9d4ef0f3b764f7a-Paper.pdf)
[code](https://github.com/tensorflow/neural-structured-learning/tree/master/research/gam)

1. **Large data and zero noise limits of graph-based semi-supervised learning algorithms,** in Applied and Computational Harmonic Analysis, 2020.
*M. M. Dunlop, D. Slepcev, A. M. Stuart, and M. Thorpe.*
[paper](https://arxiv.org/abs/1805.09450)

1. **A unified framework for data poisoning attack to graph-based semi-supervised learning,** in NeurIPS, 2019.
*X. Liu, S. Si, J. Zhu, Y. Li, and C. Hsieh.*
[paper](https://arxiv.org/abs/1910.14147)

1. **Graph Convolution Networks with manifold regularization for semi-supervised learning,** in Neural Networks, 2020.
*Kejani, M.T., Dornaika, F. and Talebi, H.*
[paper](https://www.sciencedirect.com/science/article/pii/S0893608020301362?via%3Dihub)

1. **Label-Consistency based Graph Neural Networks for Semi-supervised Node Classification,** in SIGIR, 2020.
*Xu, B., Huang, J., Hou, L., Shen, H., Gao, J. and Cheng, X.*
[paper](https://dl.acm.org/doi/abs/10.1145/3397271.3401308)

1. **Confidence-based graph convolutional networks for semi-supervised learning,** in AISTATS, 2020.
*Vashishth, S., Yadav, P., Bhandari, M. and Talukdar, P.*
[paper](http://proceedings.mlr.press/v89/vashishth19a.html)

1. **Shoestring: Graph-based semi-supervised classification with severely limited labeled data,** in CVPR, 2020.
*Lin, W., Gao, Z., & Li, B.*
[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Lin_Shoestring_Graph-Based_Semi-Supervised_Classification_With_Severely_Limited_Labeled_Data_CVPR_2020_paper.pdf)
[code](https://github.com/iQua/CVPR2020-Shoestring)

1. **Uncertainty aware semisupervised learning on graph data,** in NeurIPS, 2020.
*X. Zhao, F. Chen, S. Hu, and J. Cho.*
[paper](https://proceedings.neurips.cc//paper/2020/file/968c9b4f09cbb7d7925f38aea3484111-Paper.pdf)
[code](https://github.com/zxj32/uncertainty-GNN)

1. **Contrastive and generative graph convolutional networks for graph-based semi-supervised learning.** in AAAI, 2021.
*Wan, S., Pan, S., Yang, J., & Gong, C.*
[paper](https://www.aaai.org/AAAI21Papers/AAAI-1965.WanS.pdf)

1. **Combining label propagation and simple models out-performs graph neural networks,** in ICLR, 2021.
*Q. Huang, H. He, A. Singh, S. Lim, and A. R. Benson.*
[paper](https://arxiv.org/abs/2010.13993)
[code](https://github.com/CUAI/CorrectAndSmooth)

## [Applications](#content)

### Computer Vision

1. **A graph based subspace semi-supervised learning framework for dimensionality reduction,** in ECCV, 2008.
*Yang, W., Zhang, S. and Liang, W.*
[paper](https://link.springer.com/chapter/10.1007/978-3-540-88688-4_49)

1. **Integrated graph-based semi-supervised multiple/single instance learning framework for image annotation,** in MM, 2008.
*Tang, J., Li, H., Qi, G.J. and Chua, T.S.*
[paper](https://dl.acm.org/doi/abs/10.1145/1459359.1459446)

1. **Video face recognition with graph-based semi-supervised learning,** in ICME, 2009.
*Kokiopoulou, E. and Frossard, P.*
[paper](https://ieeexplore.ieee.org/abstract/document/5202809)

1. **Nonnegative sparse coding for discriminative semi-supervised learning,** in CVPR, 2011.
*He, R., Zheng, W.S., Hu, B.G. and Kong, X.W.*
[paper](https://ieeexplore.ieee.org/abstract/document/5995487)

1. **A novel graph-based fisher kernel method for semi-supervised learning,** in ICPR, 2014.
*Rozza, A., Manzo, M. and Petrosino, A.*
[paper](https://ieeexplore.ieee.org/abstract/document/6977362)

1. **Probabilistic class structure regularized sparse representation graph for semi-supervised hyperspectral image classification,** in Pattern Recognition, 2017.
*Y. Shao, N. Sang, C. Gao, and L. Ma.*
[paper](https://dl.acm.org/doi/abs/10.1016/j.patcog.2016.09.011)

1. **Deep supervised hashing with anchor graph,** in ICCV, 2019.
*Y. Chen, Z. Lai, Y. Ding, K. Lin, and W. K. Wong.*
[paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Chen_Deep_Supervised_Hashing_With_Anchor_Graph_ICCV_2019_paper.pdf)

1. **Semisupervised and active learning through Manifold Reciprocal kNN Graph for image retrieval,** in Neurocomputing, 2019.
*D. C. G. Pedronette, Y. Weng, A. Baldassin, and C. Hou.*
[paper](https://www.sciencedirect.com/science/article/pii/S0925231219302309)

1. **Classification-aware semisupervised domain adaptation,** in CVPR, 2020.
*G. He, X. Liu, F. Fan, and J. You.*
[paper](https://ieeexplore.ieee.org/abstract/document/9150657)

### Natural Language Processing

1. **Relation extraction using label propagation based semi-supervised learning,** in COLING, 2006.
*Chen, J., Ji, D., Tan, C.L. and Niu, Z.Y.*
[paper](https://aclanthology.org/P06-1017.pdf)

1. **Seeing stars when there aren’t many stars: Graph-based semi-supervised learning for sentiment categorization,** in NAACL, 2006.
*Goldberg, A.B. and Zhu, X.*
[paper](https://aclanthology.org/W06-3808.pdf)

1. **Efficient graph-based semi-supervised learning of structured tagging models,** in EMNLP, 2010.
*A. Subramanya, S. Petrov, and F. C. N. Pereira.*
[paper](https://dl.acm.org/doi/10.5555/1870658.1870675)

1. **Graphbased semi-supervised conditional random fields for spoken language understanding using unaligned data,** in ALTA, 2014.
*M. Aliannejadi, M. Kiaeeha, S. Khadivi, and S. S. Ghidary.*
[paper](https://arxiv.org/abs/1701.08533)

1. **A general optimization framework for smoothing language models on graph structures,** in SIGIR, 2008.
*Q. Mei, D. Zhang, and C. Zhai.*
[paper](https://dl.acm.org/doi/10.1145/1390334.1390438)

1. **A graph-based semi-supervised learning for question-answering,** in ACL/IJNLP, 2009.
*Celikyilmaz, A., Thint, M. and Huang, Z.*
[paper](https://aclanthology.org/P09-1081.pdf)

1. **A graph-based semi-supervised learning for question semantic labeling,** in NAACL, 2010.
*Celikyilmaz, A. and Hakkani-Tur, D.*
[paper](https://aclanthology.org/W10-1204.pdf)

1. **Graph-based semi-supervised learning of translation models from monolingual data,** in ACL, 2014.
*Saluja, A., Hassan, H., Toutanova, K. and Quirk, C.*
[paper](https://aclanthology.org/P14-1064.pdf)

1. **Query-focused multi-document summarization: Combining a topic model with graph-based semi-supervised learning,** in COLING, 2014.
*Li, Y. and Li, S.*
[paper](https://aclanthology.org/C14-1113.pdf)

1. **Heterogeneous graph attention networks for semi-supervised short text classification,** in EMNLP/IJNLP, 2019.
*L. Hu, T. Yang, C. Shi, H. Ji, and X. Li.*
[paper](https://aclanthology.org/D19-1488/)

1. **Graph-based semi-supervised learning for natural language understanding,** in EMNLP, 2019.
*Z. Qiu, E. Cho, X. Ma, and W. M. Campbell.*
[paper](https://aclanthology.org/D19-5318/)

### Social Networks

1. **Semi-supervised graph-based genre classification for web pages,** in EMNLP, 2014.
*Asheghi, N.R., Markert, K. and Sharoff, S.*
[paper](https://aclanthology.org/W14-3706.pdf)

1. **Graph based semi-supervised learning with convolution neural networks to classify crisis related tweets,** in ICWSM, 2018.
*F. Alam, S. R. Joty, and M. Imran.*
[paper](https://arxiv.org/abs/1805.06289)

1. **Bridging collaborative filtering and semi-supervised learning: A neural approach for POI recommendation,** in KDD, 2017.
*C. Yang, L. Bai, C. Zhang, Q. Yuan, and J. Han.*
[paper](https://dl.acm.org/doi/10.1145/3097983.3098094)
[code](https://github.com/AnranWang/PACE)

1. **On the supermodularity of active graph-based semi-supervised learning with stieltjes matrix regularization,** in ICASSP, 2018.
*Chen, P.Y. and Wei, D.*
[paper](https://ieeexplore.ieee.org/abstract/document/8462232)

### Biomedical Science

1. **Graph-based semi-supervised gene mention tagging,** in Proceedings of the 15th Workshop on Biomedical Natural Language Processing, 2016.
*Sheikhshab, G., Starks, E., Karsan, A., Sarkar, A. and Birol, I.*
[paper](https://aclanthology.org/W16-2904.pdf)

1. **Semi-supervised prediction of human miRNA-disease association based on graph regularization framework in heterogeneous networks,** in Neurocomputing, 2018.
*J. Luo, P. Ding, C. Liang, and X. Chen.*
[paper](https://www.sciencedirect.com/science/article/pii/S0925231218302674)

1. **Semi-supervised learning and graph cuts for consensus based medical image segmentation,** in Pattern Recognition, 2017.
*D. Mahapatra.*
[paper](https://dl.acm.org/doi/abs/10.1016/j.patcog.2016.09.030)

1. **Graph-based semisupervised one class support vector machine for detecting abnormal lung sounds,** in Applied Mathematics and Computation, 2020.
*R. Lang, R. Lu, C. Zhao, H. Qin, and G. Liu.*
[paper](https://www.sciencedirect.com/science/article/pii/S0096300319304667)

### Others

1. **Graph-based semi-supervised learning for phone and segment classification,** in INTERSPEECH, 2013.
*Liu, Y. and Kirchhoff, K.*
[paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.475.4495&rep=rep1&type=pdf)

1. **Graph-based semi-supervised learning for fault detection and classification in solar photovoltaic arrays,** in IEEE Transactions on Power Electronics, 2014.
*Zhao, Y., Ball, R., Mosesian, J., de Palma, J.F. and Lehman, B.*
[paper](https://ieeexplore.ieee.org/abstract/document/6933939)

1. **Two step graph-based semi-supervised learning for online auction fraud detection,** in ECML/PKDD, 2015.
*Bangcharoensap, P., Kobayashi, H., Shimizu, N., Yamauchi, S. and Murata, T.*
[paper](https://link.springer.com/chapter/10.1007/978-3-319-23461-8_11)

1. **The counterintuitive mechanism of graph-based semi-supervised learning in the big data regime,** in ICASSP, 2017.
*Mai, X. and Couillet, R.*
[paper](https://ieeexplore.ieee.org/abstract/document/7952671)

1. **Label propagation based semi-supervised learning for software defect prediction,** in ASE, 2017.
*Zhang, Z. W., Jing, X. Y., & Wang, T. J.*
[paper](https://link.springer.com/article/10.1007/s10515-016-0194-x)

1. **Improved graph-based semi-supervised learning for fingerprint-based indoor localization,** in GLOBECOM, 2018.
*Wang, D., Wang, T., Zhao, F. and Zhang, X.*
[paper](https://ieeexplore.ieee.org/abstract/document/8647621)

1. **Graph-based semi-Supervised & active learning for edge flows,** in KDD, 2019.
*Jia, J., Schaub, M. T., Segarra, S., & Benson, A. R.*
[paper](https://dl.acm.org/doi/10.1145/3292500.3330872)
[code](https://github.com/000Justin000/ssl_edge)

## [Theory](#content)

1. **Regularization and semisupervised learning on large graphs,** in COLT, 2004.
*M. Belkin, I. Matveeva, and P. Niyogi.*
[paper](https://link.springer.com/chapter/10.1007/978-3-540-27819-1_43)

1. **Graph-based semi-supervised learning and spectral kernel design,** in IEEE Transactions on Information Theory, 2008.
*Johnson, R. and Zhang, T.*
[paper](https://ieeexplore.ieee.org/abstract/document/4418483)

1. **Semi-supervised learning for graph to signal mapping: A graph signal wiener filter interpretation,** in ICASSP, 2014.
*Girault, B., Gonçalves, P., Fleury, E. and Mor, A.S.*
[paper](https://ieeexplore.ieee.org/abstract/document/6853770)

1. **On consistency of graph-based semi-supervised learning,** in ICDCS, 2019.
*Du, C., Zhao, Y. and Wang, F.*
[paper](https://ieeexplore.ieee.org/document/8884958)

1. **A sampling theory perspective of graph-based semi-supervised learning,** in IEEE Transactions on Information Theory, 2019.
*Anis, A., El Gamal, A., Avestimehr, A. S., & Ortega, A.*
[paper](https://ieeexplore.ieee.org/abstract/document/8525137)

## [Datasets](#content)

1. **Community structure in social and biological networks,** in PNAS, 2002.
*Girvan, M. and Newman, M.E.*
[paper](https://www.pnas.org/content/99/12/7821)

1. **Collective classification in network data,** in AI magazine, 2008.
*Sen, P., Namata, G., Bilgic, M., Getoor, L., Galligher, B. and Eliassi-Rad, T.*
[paper](https://ojs.aaai.org//index.php/aimagazine/article/view/2157)

1. **Relational learning via latent social dimensions,** in KDD, 2009.
*Tang, L. and Liu, H.*
[paper](https://dl.acm.org/doi/abs/10.1145/1557019.1557109)

1. **Don't Walk, Skip! Online learning of multi-scale network embeddings,** in ASONAM, 2017.
*Perozzi, B., Kulkarni, V., Chen, H. and Skiena, S.*
[paper](https://dl.acm.org/doi/abs/10.1145/3110025.3110086)

1. **Pitfalls of graph neural network evaluation,** arXiv preprint, 2018.
*Shchur, O., Mumme, M., Bojchevski, A. and Günnemann, S.*
[paper](https://arxiv.org/abs/1811.05868)

1. **A unified weakly supervised framework for community detection and semantic matching,** in PAKDD, 2018.
*Wang, W., Liu, X., Jiao, P., Chen, X. and Jin, D.*
[paper](https://link.springer.com/chapter/10.1007/978-3-319-93040-4_18)

1. **SNAP Datasets: Stanford large network dataset collection,** webpage collection, 2014.
*Leskovec, J. and Krevl, A.*
[link](http://snap.stanford.edu/data/)

## [Tutorials](#content)

1. **Graph-based semi-supervised learning algorithms for NLP,** in ACL, 2012.
*Subramanya, A. and Talukdar, P.*
[link](https://aclanthology.org/P12-4006/)

## [Books](#content)

1. **Graph-Based Semi-Supervised Learning,** in Synthesis Lectures on Artificial Intelligence and Machine Learning, 2014.
*Subramanya, A. and Talukdar, P.P.*
[link](https://www.morganclaypool.com/doi/abs/10.2200/S00590ED1V01Y201408AIM029)

2. **Semi-supervised learning,**, in Adaptive Computation and Machine Learning, 2009.
*Chapelle, O., Scholkopf, B. and Zien, A.*
[link](http://www.acad.bg/ebook/ml/MITPress-%20SemiSupervised%20Learning.pdf)

3. **Introduction to semi-supervised learning,** in Synthesis lectures on artificial intelligence and machine learning, 2009.
*Zhu, X. and Goldberg, A.B.*
[link](https://www.morganclaypool.com/doi/abs/10.2200/S00196ED1V01Y200906AIM006)