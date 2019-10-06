# Theory-of-neural-networks

## Approximation


### Expressibility

- G. F. Montufar, R. Pascanu, K. Cho, and Y. Bengio. [On the number of linear regions of deep neural networks](https://arxiv.org/abs/1402.1869)

- M. Raghu, B. Poole, J. Kleinberg, S. Ganguli, and J. S. Dickstein. [On the expressive power of deep neural networks](https://arxiv.org/abs/1606.05336)

- R. Arora, A. Basu, P. Mianjy, and A. Mukherjee. [Understanding deep neural networks with rectified linear units](https://arxiv.org/abs/1611.01491)

- T. Serra, C. Tjandraatmadja, and S. Ramalingam. [Bounding and counting linear regions of deep neural networks](https://arxiv.org/abs/1711.02114)
  - Estimates of the maximum number of linear regions.
 
- B. Hanin and M. Sellke. [Approximating continuous functions by relu nets of minimal width](https://arxiv.org/abs/1710.11278)
  - Universial approximation from the view of width.



### Interpolation

- C. Yun, S. Sra, and J. Ali. [Small relu networks are powerful memorizers: a tight analysis of memorization capacity](https://arxiv.org/abs/1810.07770)
  - Bounds on the interpolation capacity.
 
- M. Hardt and T. Ma. [Identity matters in deep learning](https://arxiv.org/abs/1611.04231)
  - Interpolation results for ResNet.



### Approximate functions with certain regularity

- D. Yarotsky. [Error bounds for approximations with deep relu networks](https://arxiv.org/abs/1610.01145)
  - Upper bound by approximating polynomials, lower bound by estimating VC-dimension.

- D. Yarotsky. [Optimal approximation of continuous functions by very deep relu networks](https://arxiv.org/abs/1802.03620)
  - Upper bound using 'bit extraction'.

- D. Yarotsky and A. Zhevnerchuk. [The phase diagram of approximation rates for deep neural networks](https://arxiv.org/abs/1906.09477)
  - Generalize the last result to higher order of regularity.

- I. Gühring, G. Kutyniok and P. Petersen. [Error bounds for approximations with deep ReLU neural networks in Ws,p norms](https://arxiv.org/abs/1902.07896)
  - Bounds on Sobolev norm.

- H. Bölcskei, P. Grohs, G. Kutyniok and P. Petersen. [Optimal approximation with sparsely connected deep neural networks](https://arxiv.org/abs/1705.01714)
  - Bounds based on min-max rate distortion theory.

- I. Daubechies, R. DeVore, S. Foucart, B. Hanin, and G. Petrova. [Nonlinear approximation and (deep) relu networks](https://arxiv.org/abs/1905.02199)

- Z. Shen, H. Yang, and S. Zhang. [Deep network approximation characterized by number of neurons](https://arxiv.org/abs/1906.05497)




### Benefits of depth, separation of neural networks

- M. Telgarsky. [Benefits of depth in neural networks](https://arxiv.org/abs/1602.04485)

- R. Eldan and O. Shamir. [The power of depth for feedforward neural networks](https://arxiv.org/abs/1512.03965)

- I. Safran and O. Shamir. [Depth-width tradeoffs in approximating natural functions with neural networks](https://arxiv.org/abs/1610.09887)

- R. Arora, A. Basu, P. Mianjy, and A. Mukherjee. [Understanding deep neural networks with rectified linear units](https://arxiv.org/abs/1611.01491)

- Z. Lu, H. Pu, F. Wang, Z. Hu and L. Wang [The expressive power of neural networks: A view from the width](https://arxiv.org/abs/1709.02540)
  - Separation results from the view of width.

- T. Poggio, H. Mhaskar, L. Rosasco, B. Miranda and Q. Liao. [Why and when can deep-but not shallow-networks avoid the curse of dimensionality: a review](https://link.springer.com/article/10.1007/s11633-017-1054-2)
  - Approximate functions with hierarchical structure.




### Results before deep learning

- A. Pinkus. [Approximation theory of the MLP model in neural networks](http://www2.math.technion.ac.il/~pinkus/papers/acta.pdf)
  - A good summary.
 
- A. R. Barron. [Universal Approximation bounds for superpositions of a sigmoidal function](https://ieeexplore.ieee.org/document/256500)
  - Bound obtained by probability method, independent of dimension.
  
- Y. Makovoz. [Random approximants and neural networks](https://www.sciencedirect.com/science/article/pii/S0021904596900313)
  - Bound obtained by probability method.
  
- R. A. DeVore, R. Howard, and C. Micchelli. [Optimal nonlinear approximation](https://link.springer.com/article/10.1007/BF01171759)
  - Famous nonlinear width, not directly related to neural networks.
  
- V. Maiorov and J. Ratsaby. [On the degree of approximation by manifolds of finite pseudo-dimension](https://link.springer.com/article/10.1007/s003659900108)
  - Nonlinear width based on pseudo-dimension, interesting and insightful, but not well-known.












## Generalization


### Experiments

- C. Zhang, S. Bengio, M. Hardt, B. Recht and O. Vinyals. [Understanding deep learning requires rethinking generalization](https://arxiv.org/abs/1611.03530)

- M. Belkin, S. Ma and S. Mandal. [To understand deep learning we need to understand kernel learning](https://arxiv.org/abs/1802.01396)

- M. Belkin, D. Hsu, S. Ma and S. Mandal. [Reconciling modern machine learning practice and the bias-variance trade-off](https://arxiv.org/abs/1812.11118)




### Probably Approximately Correct (PAC)

- P. Liang. [CS229T/STAT231: Statistical Learning Theory](https://github.com/percyliang/cs229t/blob/master/lectures/notes.pdf)
  - An introduction.

- P. L. Bartlett, N. Harvey, C. Liaw, and A. Mehrabian. [Nearly-tight VC-dimension and pseudodimension bounds for piecewise linear neural networks](https://arxiv.org/abs/1703.02930)
  - Estimates of VC-dimension.

- P. L. Bartlett and S. Mendelson. [Rademacher and gaussian complexities: Risk bounds and structural results](http://www.jmlr.org/papers/volume3/bartlett02a/bartlett02a.pdf)

- O. Bousquet and A. Elisseeff. [Stability and generalization](http://www.jmlr.org/papers/volume2/bousquet02a/bousquet02a.pdf)

- M. Hardt, B. Recht, and Y. Singer. [Train faster, generalize better: Stability of stochastic gradient descent](https://arxiv.org/abs/1509.01240)

- H. Xu and S. Mannor. [Robustness and generalization](https://arxiv.org/abs/1005.2243)

- D. McAllester and T. Akinbiyi [PAC-Bayesian Theory](https://link.springer.com/chapter/10.1007/978-3-642-41136-6_10)
  - An introduction of PAC-Bayesian.










## Optimation











