## Implementations of Uncertainty Quantification Methods for Neural Networks
This repository collects available implementations for uncertainty quantification and calibration methods in neural networks. The list mainly links to resources which are provided by the authors of the corresponding approaches or to other collections of implementations. 

| Method Type | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Approch&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| Paper(s) | Authors official Repository | Framework | Link to Repository 
| --- | --- | --- | --- | --- | --- |
Calibration | Temperature Scaling | C. Guo, G. Pleiss, Y. Sun, K. Q. Weinberger, <i>"On calibration of modern neural networks"</i>, International Conference on Machine Learning (2017). [[paper](https://dl.acm.org/doi/pdf/10.5555/3305381.3305518)] | yes | PyTorch | https://github.com/gpleiss/temperature_scaling
Single Deterministic Neural Network | Misclassification and Out-of-Distribution detection based on the softmax output. | D. Hendrycks and K. Gimpel. <i>"A baseline for detecting misclassified and out-of-distribution examples in neural networks."</i> arXiv preprint arXiv:1610.02136 (2016). [[paper](https://arxiv.org/abs/1610.02136)] | yes | TensorFlow | https://github.com/hendrycks/error-detection
Single Deterministic Neural Network & Calibration| Implementation of Odin and Temperature Scalling for out-of-distribution detection. |S. Liang, Y. Li and R. Srikant, <i>"Enhancing The Reliability of Out-of-distribution Image Detection in Neural Networks"</i>, International Conference on Learning Representations (2018). [[paper](https://openreview.net/pdf?id=H1VGkIxRZ)] | yes | PyTorch | https://github.com/facebookresearch/odin
| Single Deterministic Neural Network | Outlier exposure - Learn heuristic for out-of-distribution detection from out-of-distribution examples. | Hendrycks, Dan, Mantas Mazeika, and Thomas Dietterich. <i>"Deep anomaly detection with outlier exposure."</i> arXiv preprint arXiv:1812.04606 (2018). [[paper](https://arxiv.org/abs/1812.04606)]| yes | PyTorch | https://github.com/hendrycks/outlier-exposure
| Single Deterministic Neural Network | Deep Mahalanobis Detector for Out-of-Dsitribution detection| <i>K. Lee, K. Lee, H. Lee, J. Shin, “A Simple Unified Framework for Detecting Out-of-Distribution Samples and Adversarial Attacks”</i>, NeurIPS 2018. [[paper](https://papers.nips.cc/paper/2018/file/abdeb6f575ac5c6676b747bca8d09cc2-Paper.pdf)] | yes | PyTorch | https://github.com/pokaxpoka/deep_Mahalanobis_detector
| Single Deterministic Neural Network | Evidential Neural Networks for Classification tasks | M. Sensoy, L. Kaplan, and M. Kandemir, <i>“Evidential deep learning to quantify classification uncertainty” </i>,  NeurIPS 2018. [[paper](https://papers.nips.cc/paper/2018/file/a981f2b708044d6fb4a71a1463242520-Paper.pdf)] | partially | Tensorflow & PyTorch | https://github.com/dougbrion/pytorch-classification-uncertainty <br /><br /> https://muratsensoy.github.io/uncertainty.html
| Single Deterministic Neural Network | Dirichlet Prior Networks | A. Malinin and M. Gales, <i>“Predictive uncertainty estimation via prior networks”</i> NeurIPS 2018. [[paper](https://papers.nips.cc/paper/2018/file/3ea2db50e62ceefceaf70a9d9a56a6f4-Paper.pdf)]  <br /><br /> A. Malinin and M. Gales, <i>“Reverse kl-divergence training of prior networks: Improved uncertainty and adversarial robustness” </ i>, NeurIPS 2019. [[paper](https://papers.nips.cc/paper/2019/file/7dd2ae7db7d18ee7c9425e38df1af5e2-Paper.pdf)] | yes | PyTorch | https://github.com/KaosEngineer/PriorNetworks
| Bayesian Neural Network | Bayes By Backprop (BBB) | C. Blundell, J. Cornebise, K. Kavukcuoglu & D. Wierstra <i>"Weight Uncertainty in Neural Network"</i>, ICML 2015. [[paper](http://proceedings.mlr.press/v37/blundell15.pdf)] | no | PyTorch | https://github.com/nitarshan/bayes-by-backprop <br /> <br />https://github.com/ThirstyScholar/bayes-by-backprop
| Bayesian Neural Network | Example implementation of Multiplicative Normalizing Flows |  C. Louizos and M. Welling,  <i>"Multiplicative Normalizing Flows for Variational Bayesian Neural Networks"</i>, ICML 2017. [[paper](http://proceedings.mlr.press/v70/louizos17a/louizos17a.pdf)]  | no | TensorFlow & PyTorch | https://github.com/AMLab-Amsterdam/MNF_VBNN <br /><br /> https://github.com/janosh/torch-mnf
| Bayesian Neural Network | Monte Carlo Dropout | Gal, Yarin, and Zoubin Ghahramani. <i>"Dropout as a bayesian approximation: Representing model uncertainty in deep learning."</i> ICML 2016. [[paper](http://www.cs.ox.ac.uk/people/yarin.gal/website/publications.html#Gal2015Dropout)]| yes | TensorFlow | https://github.com/yaringal/DropoutUncertaintyExps
| Bayesian Neural Network | VOGN Optimizer and presentation of Bayesian principles in neural networks. | M. Khan, D. Nielsen, V. Tangkaratt, W. Lin, Y. Gal and A. Y. Srivastava, <i>"Fast and Scalable Bayesian Deep Learning by Weight-Perturbation in Adam"</i>, ICML 2018. [[paper](http://proceedings.mlr.press/v80/khan18a.html)] | yes | PyTorch | https://github.com/team-approx-bayes/dl-with-bayes
| Bayesian Neural Network | Provides facilities to easily train your PyTorch neural network models using variational inference. | - | no | PyTorch | https://github.com/ctallec/pyvarinf
Bayesian Neural Network | Stochastic Weight Averaging-Gaussian (SWAG) | W. J. Maddox, et al. <i>"A simple baseline for bayesian uncertainty in deep learning."</i> NeurIPS 2019: 13153-13164. [[paper](https://proceedings.neurips.cc/paper/2019/file/118921efba23fc329e6560b27861f0c2-Paper.pdf)]| yes | PyTorch  |  https://github.com/wjmaddox/swa_gaussian |
| Bayesian Neural Network | Deterministic Variational Inference | A. Wu, S. Nowozin, E. Meeds, R. E. Turner, J. M. Hernandez-Lobato, A. L. Gaunt, <i>Deterministic Variational Inference for Robust Bayesian Neural Networks</i>, ICLR 2019. [[paper](https://openreview.net/pdf?id=B1l08oAct7)] | partially  | TensorFlow & PyTorch | https://github.com/Microsoft/deterministic-variational-inference <br /><br /> https://github.com/markovalexander/DVI
| Bayesian Neural Network | Laplace Approximation with four different approximations of the curvature | Estimating Model Uncertainty of Neural Networks in Sparse Information Form J. Lee, M. Humt, J. Feng, R. Triebel, ICLR 2020. [[paper](https://proceedings.icml.cc/static/paper_files/icml/2020/2525-Paper.pdf)] <br /><br /> Bayesian Optimization Meets Laplace Approximation for Robotic Introspection M. Humt, J. Lee, R. Triebel, IROS 2020 Workshop. [[paper](https://elib.dlr.de/137021/1/ICRA2020LTAWS_paper_2.pdf)]<br /><br />  <i>"Learning Multiplicative Interactions with Bayesian Neural Networks for Visual-Inertial Odometry"<i />, K. Shinde, J. Lee, M. Humt, A. Sezgin, R. Triebel, ICLR 2020 Workshop. [[paper](https://elib.dlr.de/135547/1/Learning%20Multiplicative%20Interactions%20with%20Bayesian%20Neural%20Networks%20for%20Visual-Inertial%20Odometry.pdf)] | yes | PyTorch | https://github.com/DLR-RM/curvature
| Ensembles | Deep Ensembles | B. Lakshminarayanan, A. Pritzel, and C. Blundell, <i> “Simple and scalable predictive uncertainty estimation using deep ensembles” </i> NeurIPS 2017. [[paper](https://papers.nips.cc/paper/2017/file/9ef2ed4b7fd2c810847ffa5fa85bce38-Paper.pdf)]| no | TensorFlow | https://github.com/vvanirudh/deep-ensembles-uncertainty <br /> <br /> https://github.com/axelbrando/Mixture-Density-Networks-for-distribution-and-uncertainty-estimation <br /> <br /> https://github.com/Kyushik/Predictive-Uncertainty-Estimation-using-Deep-Ensemble
| Collection | Collection containing <ul><li>Deep Ensembles <li>Stochastic Weight-Averaging Gaussian <li>Kronecker-Factored Laplace Approximation</ul> | A. Ashukha, A. Lyzhov, D. Molchanov and D. Vetrov, <i>"Pitfalls of In-Domain Uncertainty Estimation and Ensembling in Deep Learning"</i>, ICLR 2020 | yes | PyTorch | https://github.com/bayesgroup/pytorch-ensembles
| Collection | Collection containing <ul><li>Deep Ensembles <li>Bayes by Backprop <li>Monte Carlo Dropout <li>Temperature scaling</ul> | - | no | PyTorch | https://github.com/cpark321/uncertainty-deep-learning
| Collection | Collection containing <ul><li>Bayes by Backprop <li>Monte Carlo Dropout <li>Stochastic gradient Langevin dynamics <li>Kronecker-Factored Laplace Approximation <li>Stochastic Gradient Hamiltonian Monte Carlo</ul> | - | no | PyTorch | https://github.com/JavierAntoran/Bayesian-Neural-Networks
