# Batch-RL-Paper-Lists
Paper Collection for Batch RL with brief introductions.

Batch RL can be seen as an interesting specifc area in imitation learning yet it learn purely from demonstrations (batch data) and do not need to interact with the environment.

It is also knwon as offline RL.

# Overview

TBA

## Tutorial

- <[Offline Reinforcement Learning: Tutorial, Review, and Perspectives on Open Problems](https://arxiv.org/abs/2005.01643)> by Sergey Levine, Aviral Kumar, George Tucker, Justin Fu, 2020.
- <[Exponentially Weighted Imitation Learning for Batched Historical Data](https://link.springer.com/chapter/10.1007/978-3-642-27645-3_2)> by Sascha Lange, Thomas Gabel, Martin Riedmiller, 2012.

## Early Work

- [LSPI] <[Least-squares policy iteration](http://www.jmlr.org/papers/v4/lagoudakis03a.html)> by Michail G. Lagoudakis, Ronald Parr, 2003.
- [FQI] <[Tree-based batch mode reinforcement learning](https://www.jmlr.org/papers/volume6/ernst05a/ernst05a.pdf)> by Damien Ernst, Pierre Geurts, Louis Wehenkel, 2005.
- [NQI] <[Neural fitted Q iteration–first experiences with a data efficient neural reinforcement learning method](https://link.springer.com/chapter/10.1007/11564096_32)> by Martin Riedmiller, 2005.

## Try to imitate without interacting with environments

* <[Exponentially Weighted Imitation Learning for Batched Historical Data](https://papers.nips.cc/paper/7866-exponentially-weighted-imitation-learning-for-batched-historical-data.pdf)> by Qing Wang, Jiechao Xiong, Lei Han, Peng Sun, Han Liu and Tong Zhang, NIPS 2018.

## General Batch RL

### Model-free

* [DQfD] <[Deep Q-learning from Demonstrations](https://arxiv.org/abs/1704.03732)> by Todd Hester, Matej Vecerik, Olivier Pietquin, Marc Lanctot, Tom Schaul, Bilal Piot, Dan Horgan, John Quan, Andrew Sendonaris, Gabriel Dulac-Arnold, Ian Osband, John Agapiou, Joel Z. Leibo, Audrunas Gruslys, 2017.

* [NAC] <[Reinforcement Learning from Imperfect Demonstrations](https://arxiv.org/abs/1802.05313)> by Yang Gao, Huazhe Xu, Ji Lin, Fisher Yu, Sergey Levine, Trevor Darrell, ICML 2018.

* [BEAR] <[Stabilizing Off-Policy Q-Learning via Bootstrapping Error Reduction](https://arxiv.org/1906.00949)> by Aviral Kumar, Justin Fu, George Tucker and Sergey Levine, NIPS 2019.

* [DualDICE] <[Dualdice: Behavior-agnostic estimation of discounted stationary distribution corrections](http://papers.nips.cc/paper/8503-dualdice-behavior-agnostic-estimation-of-discounted-stationary-distribution-corrections)> by Ofir Nachum, Yinlam Chow, Bo Dai, Lihong Li, ICML 2019.

* [SPIBB] <[Safe policy improvement with baseline bootstrapping](http://proceedings.mlr.press/v97/laroche19a/laroche19a.pdf)> by Romain Laroche, Paul Trichelair, Remi Tachet des Combes, ICML 2019.

* <[Batch Policy Learning under Constraints](https://arxiv.org/abs/1903.08738)> by Hoang M. Le, Cameron Voloshin, Yisong Yue, ICML 2019.

* [BCQ] <[Off-Policy Deep Reinforcement Learning without Exploration](https://arxiv.org/abs/1812.02900)> by Scott Fujimoto, David Meger and Doina Precup, ICML 2019.

* <[Truly Batch Apprenticeship Learning with Deep Successor Features](https://arxiv.org/abs/1903.10077)>, Donghun Lee, Srivatsan Srinivasan and Finale Doshi-Velez, IJCAI 2019.

* [BCQ-Discrete] <[Benchmarking Batch Deep Reinforcement Learning Algorithms](https://arxiv.org/abs/1910.01708)> by Fujimoto, Edoardo Conti, Mohammad Ghavamzadeh, Joelle Pineau, 2019.

* <[On Value Discrepancy of Imitation Learning](https://arxiv.org/abs/1911.07027)> by Tian Xu, Ziniu Li, Yang Yu, 2019.

* [AWR] <[Advantage-Weighted Regression: Simple and Scalable Off-Policy Reinforcement Learning](https://arxiv.org/abs/1910.00177)> by Xue Bin Peng,  Aviral Kumar,  Grace Zhang and Sergey Levine, 2019.

* [BRAC] <[Behavior Regularized Offline Reinforcement Learning](https://arxiv.org/abs/1911.11361)> by Yifan Wu, George Tucker, Ofir Nachum, 2019.

* [AlgaeDICE] <[AlgaeDICE: Policy Gradient from Arbitrary Experience](https://arxiv.org/abs/1912.02074)> by Ofir Nachum, Bo Dai, Ilya Kostrikov, Yinlam Chow, Lihong Li, Dale Schuurmans, 2019.

* [2IWIL] <[Imitation Learning from Imperfect Demonstration](https://arxiv.org/abs/1901.09387)> by Yueh-Hua Wu, Nontawat Charoenphakdee, Han Bao, Voot Tangkaratt, Masashi Sugiyama, 2019.

* [ABM] <[Keep Doing What Worked: Behavioral Modelling Priors for Offline Reinforcement Learning](https://arxiv.org/abs/2002.08396)> by Siegel et al., ICLR 2020.

* [GenDICE] <[GenDICE: Generalized Offline Estimation of Stationary Values](https://openreview.net/forum?id=HkxlcnVFwB)> by Ruiyi Zhang, Bo Dai, Lihong Li, Dale Schuurmans, ICLR 2020.

* [GradientDICE] <[GradientDICE: Rethinking Generalized Offline Estimation of Stationary Values](https://arxiv.org/abs/2001.11113)> by Shangtong Zhang, Bo Liu, Shimon Whiteson, ICML 2020.

* [REM] <[An Optimistic Perspective on Offline Reinforcement Learning](https://arxiv.org/abs/1907.04543)> by Rishabh Agarwal, Dale Schuurmans and Mohammad Norouzi, ICML 2020.

* [BOPAH] <[Batch Reinforcement Learning with Hyperparameter Gradients](http://proceedings.mlr.press/v119/lee20d/lee20d.pdf)> by Byung-Jun Lee, Jongmin Lee, Peter Vrancx, Dongho Kim, Kee-Eung Kim, ICML 2020.

* [OFENet] <[Can Increasing Input Dimensionality Improve Deep Reinforcement Learning?](https://arxiv.org/abs/2003.01629)> by Kei Ota, Tomoaki Oiki, Devesh K. Jha, Toshisada Mariyama, Daniel Nikovski, ICML 2020.

* [PFQI] <[Control Frequency Adaptation via Action Persistence in Batch Reinforcement Learning](https://arxiv.org/abs/2002.06836)> by Alberto Maria Metelli, Flavio Mazzolini, Lorenzo Bisi, Luca Sabbioni, Marcello Restelli, ICML 2020.

* [PESC-TD(0)] <[Reducing Sampling Error in Batch Temporal Difference Learning](http://proceedings.mlr.press/v119/pavse20a/pavse20a.pdf)> by Brahma S. Pavse, Ishan Durugkar, Josiah P. Hanna, Peter Stone, ICML 2020.

* <[Provably Good Batch Reinforcement Learning Without Great Exploration](https://arxiv.org/abs/2007.08202)> by Yao Liu, Adith Swaminathan, Alekh Agarwal and Emma Brunskill, NIPS 2020.

* [ESRL] <[Expert-Supervised Reinforcement Learning for Offline Policy Learning and Evaluation](https://arxiv.org/abs/2006.13189)> by Aaron Sonabend-W, Junwei Lu, Leo A. Celi, Tianxi Cai, Peter Szolovits, NIPS 2020.

* [MBML] <[Multi-Task Batch Reinforcement Learning with Metric Learning](https://arxiv.org/abs/1909.11373)> by Jiachen Li et al., NIPS 2020.

* [BAIL] <[BAIL: Best-Action Imitation Learning for Batch Deep Reinforcement Learning](https://arxiv.org/abs/1910.12179)> by Xinyue Chen, Zijian Zhou, Zheng Wang, Che Wang, Yanqiu Wu, Keith Ross, NIPS 2020.

* [EDM] <[Strictly Batch Imitation Learning by Energy-based Distribution Matching](https://arxiv.org/abs/2006.14154)> by Daniel Jarrett, Ioana Bica and Mihaela van der Schaar, NIPS 2020.

* [AWAC] <[Accelerating Online Reinforcement Learning with Offline Datasets](https://arxiv.org/abs/2006.09359)> by Ashvin Nair, Murtaza Dalal, Abhishek Gupta, Sergey Levine, 2020.

* [CQL] <[Conservative Q-Learning for Offline Reinforcement Learning](https://arxiv.org/abs/2006.04779)> by Aviral Kumar, Aurick Zhou, George Tucker, Sergey Levine, 2020.

* [BREMEN] <[Deployment-Efficient Reinforcement Learning via Model-Based Offline Optimization](https://arxiv.org/abs/2006.03647)> by Tatsuya Matsushima, Hiroki Furuta, Yutaka Matsuo, Ofir Nachum, Shixiang Shane Gu, 2020.

* [UWAC] <[Uncertainty Weighted Offline Reinforcement Learning](https://openreview.net/forum?id=7hMenh--8g)> by Yue Wu, Shuangfei Zhai, Nitish Srivastava, Joshua M. Susskind, Jian Zhang, Ruslan Salakhutdinov, Hanlin Goh, 2020.

* [CRR] <[Critic Regularized Regression](https://arxiv.org/abs/2006.15134)> by Ziyu Wang, Alexander Novikov, Konrad Zolna, Jost Tobias Springenberg, Scott Reed, Bobak Shahriari, Noah Siegel, Josh Merel, Caglar Gulcehre, Nicolas Heess, Nando de Freitas, NIPS 2020.

* [DAC-MDP] <[DeepAveragers: Offline Reinforcement Learning By Solving Derived Non-Parametric MDPs](https://openreview.net/forum?id=eMP1j9efXtX)> by Aayam Shrestha, Stefan Lee, Prasad Tadepalli, Alan Fern, ICLR 2021.

* [OPAL] <[OPAL: Offline Primitive Discovery for Accelerating Offline Reinforcement Learning](https://openreview.net/forum?id=V69LGwJ0lIN)> by Anurag Ajay, Aviral Kumar, Pulkit Agrawal, Sergey Levine, Ofir Nachum, ICLR 2021.

* [O-RAAC] <[Risk-Averse Offline Reinforcement Learning](https://openreview.net/forum?id=TBIzh9b5eaz)> by Nuria Armengol Urpi, Sebastian Curi, Andreas Krause, ICLR 2021.

* <[What are the Statistical Limits of Offline RL with Linear Function Approximation?](https://openreview.net/forum?id=30EvkP2aQLD)> by Ruosong Wang, Dean P. Foster, Shan M. Kakade, ICLR 2021.

### Model-based

* [MOReL] <[MOReL : Model-Based Offline Reinforcement Learning](https://arxiv.org/abs/2005.05951)> by Rahul Kidambi, Aravind Rajeswaran, Praneeth Netrapalli and Thorsten Joachims, NIPS 2020.

* [MOPO] <[MOPO: Model-based Offline Policy Optimization](https://arxiv.org/abs/2005.13239)> by Tianhe Yu et al., NIPS 2020.

* [MOOSE] <[Overcoming Model Bias for Robust Offline Deep Reinforcement Learning](https://arxiv.org/abs/2008.05533)> by Phillip Swazinna, Steffen Udluft, Thomas Runkler, 2020.

* <[Model-Based Offline Planning](https://arxiv.org/abs/2008.05556)> by Arthur Argenson, Gabriel Dulac-Arnold, ICLR 2021.

* <[Autoregressive Dynamics Models for Offline Policy Evaluation and Optimization](https://openreview.net/forum?id=kmqjgSNXby)> by Michael R Zhang, Thomas Paine, Ofir Nachum, Cosmin Paduraru, George Tucker, ziyu wang, Mohammad Norouzi, ICLR 2021.

* [COMBO] <[COMBO: Conservative Offline Model-Based Policy Optimization](https://arxiv.org/abs/2102.08363)> by Tianhe Yu, Aviral Kumar, Rafael Rafailov, Aravind Rajeswaran, Sergey Levine, Chelsea Finn, 2021.

### Benchmark

* [D4rl] <[D4rl: Datasets for deep data-driven reinforcement learning](https://arxiv.org/abs/2004.07219)> by Justin Fu, Aviral Kumar, Ofir Nachum, George Tucker, Sergey Levine, 2020.

* <[Rl unplugged: Benchmarks for offline reinforcement learning](https://arxiv.org/abs/2006.13888)> by Caglar Gulcehre, et al., 2020.

* [NeoRL] <[NeoRL: A Near Real-World Benchmark for Offline Reinforcement Learning](https://arxiv.org/abs/2102.00714)> by Rongjun Qin, Songyi Gao, Xingyuan Zhang, Zhen Xu, Shengkai Huang, Zewen Li, Weinan Zhang, Yang Yu, 2021.

## Applied Batch RL

- <[Scaling data-driven robotics with reward sketching and batch reinforcement learning](https://ui.adsabs.harvard.edu/abs/2019arXiv190912200C/abstract)> by Ajay Mandlekar, et al., 2019.
- <[Way Off-Policy Batch Deep Reinforcement Learning of Implicit Human Preferences in Dialog](https://arxiv.org/abs/1907.00456)> by Natasha Jaques et al., 2019.
- <[Iris: Implicit reinforcement without interaction at scale for learning control from offline robot manipulation data](https://ieeexplore.ieee.org/abstract/document/9196935/)> by Ajay Mandlekar, et al., 2020.






