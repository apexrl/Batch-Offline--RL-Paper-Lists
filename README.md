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

## Imitation without interacting with environments

* <[Exponentially Weighted Imitation Learning for Batched Historical Data](https://papers.nips.cc/paper/7866-exponentially-weighted-imitation-learning-for-batched-historical-data.pdf)> by Qing Wang, Jiechao Xiong, Lei Han, Peng Sun, Han Liu and Tong Zhang, NeurIPS 2018.
* [EDM] <[Strictly Batch Imitation Learning by Energy-based Distribution Matching](https://arxiv.org/abs/2006.14154)> by Daniel Jarrett, Ioana Bica and Mihaela van der Schaar, NeurIPS 2020.
* [MILO] <[Mitigating Covariate Shift in Imitation Learning via Offline Data With Partial Coverage](https://papers.nips.cc/paper/2021/hash/07d5938693cc3903b261e1a3844590ed-Abstract.html)> by Jonathan Chang, Masatoshi Uehara, Dhruv Sreenivas, Rahul Kidambi, Wen Sun, NeurIPS 2021.

## General Batch RL

### Model-free

* [DQfD] <[Deep Q-learning from Demonstrations](https://arxiv.org/abs/1704.03732)> by Todd Hester, Matej Vecerik, Olivier Pietquin, Marc Lanctot, Tom Schaul, Bilal Piot, Dan Horgan, John Quan, Andrew Sendonaris, Gabriel Dulac-Arnold, Ian Osband, John Agapiou, Joel Z. Leibo, Audrunas Gruslys, 2017.
* [NAC] <[Reinforcement Learning from Imperfect Demonstrations](https://arxiv.org/abs/1802.05313)> by Yang Gao, Huazhe Xu, Ji Lin, Fisher Yu, Sergey Levine, Trevor Darrell, ICML 2018.
* [BEAR] <[Stabilizing Off-Policy Q-Learning via Bootstrapping Error Reduction](https://arxiv.org/1906.00949)> by Aviral Kumar, Justin Fu, George Tucker and Sergey Levine, NeurIPS 2019.
* [DualDICE] <[Dualdice: Behavior-agnostic estimation of discounted stationary distribution corrections](http://papers.nips.cc/paper/8503-dualdice-behavior-agnostic-estimation-of-discounted-stationary-distribution-corrections)> by Ofir Nachum, Yinlam Chow, Bo Dai, Lihong Li, ICML 2019.
* [SPIBB] <[Safe policy improvement with baseline bootstrapping](http://proceedings.mlr.press/v97/laroche19a/laroche19a.pdf)> by Romain Laroche, Paul Trichelair, Remi Tachet des Combes, ICML 2019.
* <[Batch Policy Learning under Constraints](https://arxiv.org/abs/1903.08738)> by Hoang M. Le, Cameron Voloshin, Yisong Yue, ICML 2019.
* [BCQ] <[Off-Policy Deep Reinforcement Learning without Exploration](https://arxiv.org/abs/1812.02900)> by Scott Fujimoto, David Meger and Doina Precup, ICML 2019.
* [2IWIL] <[Imitation Learning from Imperfect Demonstration](https://arxiv.org/abs/1901.09387)> by Yueh-Hua Wu, Nontawat Charoenphakdee, Han Bao, Voot Tangkaratt, Masashi Sugiyama, ICML 2019.
* <[Truly Batch Apprenticeship Learning with Deep Successor Features](https://arxiv.org/abs/1903.10077)>, Donghun Lee, Srivatsan Srinivasan and Finale Doshi-Velez, IJCAI 2019.
* [BCQ-Discrete] <[Benchmarking Batch Deep Reinforcement Learning Algorithms](https://arxiv.org/abs/1910.01708)> by Fujimoto, Edoardo Conti, Mohammad Ghavamzadeh, Joelle Pineau, 2019.
* [AWR] <[Advantage-Weighted Regression: Simple and Scalable Off-Policy Reinforcement Learning](https://arxiv.org/abs/1910.00177)> by Xue Bin Peng,  Aviral Kumar,  Grace Zhang and Sergey Levine, 2019.
* [BRAC] <[Behavior Regularized Offline Reinforcement Learning](https://arxiv.org/abs/1911.11361)> by Yifan Wu, George Tucker, Ofir Nachum, 2019.
* [AlgaeDICE] <[AlgaeDICE: Policy Gradient from Arbitrary Experience](https://arxiv.org/abs/1912.02074)> by Ofir Nachum, Bo Dai, Ilya Kostrikov, Yinlam Chow, Lihong Li, Dale Schuurmans, 2019.
* [ABM] <[Keep Doing What Worked: Behavioral Modelling Priors for Offline Reinforcement Learning](https://arxiv.org/abs/2002.08396)> by Siegel et al., ICLR 2020.
* [GenDICE] <[GenDICE: Generalized Offline Estimation of Stationary Values](https://openreview.net/forum?id=HkxlcnVFwB)> by Ruiyi Zhang, Bo Dai, Lihong Li, Dale Schuurmans, ICLR 2020.
* [GradientDICE] <[GradientDICE: Rethinking Generalized Offline Estimation of Stationary Values](https://arxiv.org/abs/2001.11113)> by Shangtong Zhang, Bo Liu, Shimon Whiteson, ICML 2020.
* [REM] <[An Optimistic Perspective on Offline Reinforcement Learning](https://arxiv.org/abs/1907.04543)> by Rishabh Agarwal, Dale Schuurmans and Mohammad Norouzi, ICML 2020.
* [BOPAH] <[Batch Reinforcement Learning with Hyperparameter Gradients](http://proceedings.mlr.press/v119/lee20d/lee20d.pdf)> by Byung-Jun Lee, Jongmin Lee, Peter Vrancx, Dongho Kim, Kee-Eung Kim, ICML 2020.
* [OFENet] <[Can Increasing Input Dimensionality Improve Deep Reinforcement Learning?](https://arxiv.org/abs/2003.01629)> by Kei Ota, Tomoaki Oiki, Devesh K. Jha, Toshisada Mariyama, Daniel Nikovski, ICML 2020.
* [PFQI] <[Control Frequency Adaptation via Action Persistence in Batch Reinforcement Learning](https://arxiv.org/abs/2002.06836)> by Alberto Maria Metelli, Flavio Mazzolini, Lorenzo Bisi, Luca Sabbioni, Marcello Restelli, ICML 2020.
* [PESC-TD(0)] <[Reducing Sampling Error in Batch Temporal Difference Learning](http://proceedings.mlr.press/v119/pavse20a/pavse20a.pdf)> by Brahma S. Pavse, Ishan Durugkar, Josiah P. Hanna, Peter Stone, ICML 2020.
* <[Provably Good Batch Reinforcement Learning Without Great Exploration](https://arxiv.org/abs/2007.08202)> by Yao Liu, Adith Swaminathan, Alekh Agarwal and Emma Brunskill, NeurIPS 2020.
* [ESRL] <[Expert-Supervised Reinforcement Learning for Offline Policy Learning and Evaluation](https://arxiv.org/abs/2006.13189)> by Aaron Sonabend-W, Junwei Lu, Leo A. Celi, Tianxi Cai, Peter Szolovits, NeurIPS 2020.
* [MBML] <[Multi-Task Batch Reinforcement Learning with Metric Learning](https://arxiv.org/abs/1909.11373)> by Jiachen Li et al., NeurIPS 2020.
* [BAIL] <[BAIL: Best-Action Imitation Learning for Batch Deep Reinforcement Learning](https://arxiv.org/abs/1910.12179)> by Xinyue Chen, Zijian Zhou, Zheng Wang, Che Wang, Yanqiu Wu, Keith Ross, NeurIPS 2020.
* [AWAC] <[Accelerating Online Reinforcement Learning with Offline Datasets](https://arxiv.org/abs/2006.09359)> by Ashvin Nair, Murtaza Dalal, Abhishek Gupta, Sergey Levine, 2020.
* [CQL] <[Conservative Q-Learning for Offline Reinforcement Learning](https://arxiv.org/abs/2006.04779)> by Aviral Kumar, Aurick Zhou, George Tucker, Sergey Levine, NeurIPS 2020.
* [UWAC] <[Uncertainty Weighted Offline Reinforcement Learning](https://openreview.net/forum?id=7hMenh--8g)> by Yue Wu, Shuangfei Zhai, Nitish Srivastava, Joshua M. Susskind, Jian Zhang, Ruslan Salakhutdinov, Hanlin Goh, 2020.
* [CRR] <[Critic Regularized Regression](https://arxiv.org/abs/2006.15134)> by Ziyu Wang, Alexander Novikov, Konrad Zolna, Jost Tobias Springenberg, Scott Reed, Bobak Shahriari, Noah Siegel, Josh Merel, Caglar Gulcehre, Nicolas Heess, Nando de Freitas, NeurIPS 2020.
* [DAC-MDP] <[DeepAveragers: Offline Reinforcement Learning By Solving Derived Non-Parametric MDPs](https://openreview.net/forum?id=eMP1j9efXtX)> by Aayam Shrestha, Stefan Lee, Prasad Tadepalli, Alan Fern, ICLR 2021.
* [OPAL] <[OPAL: Offline Primitive Discovery for Accelerating Offline Reinforcement Learning](https://openreview.net/forum?id=V69LGwJ0lIN)> by Anurag Ajay, Aviral Kumar, Pulkit Agrawal, Sergey Levine, Ofir Nachum, ICLR 2021.
* [O-RAAC] <[Risk-Averse Offline Reinforcement Learning](https://openreview.net/forum?id=TBIzh9b5eaz)> by Nuria Armengol Urpi, Sebastian Curi, Andreas Krause, ICLR 2021.
* [BREMEN] <[Deployment-Efficient Reinforcement Learning via Model-Based Offline Optimization](https://arxiv.org/abs/2006.03647)> by Tatsuya Matsushima, Hiroki Furuta, Yutaka Matsuo, Ofir Nachum, Shixiang Shane Gu, ICLR 2021.
* [PEBL] <[PEBL: Pessimistic Ensembles for Offline Deep Reinforcement Learning](http://rbr.cs.umass.edu/r2aw/papers/R2AW_paper_6.pdf)> by RJordi Smit, Canmanie T. Ponnambalam, Matthijs T. J. Spaan, Frans A. Oliehoek, IJCAI R2AW 2021.
* [R-BVE] <[Regularized Behavior Value Estimation](https://arxiv.org/pdf/2103.09575.pdf)> by Caglar Gulcehre, Sergio Gómez Colmenarejo, Ziyu Wang, Jakub Sygnowski, Thomas Paine, Konrad Zołna,Yutian Chen, Matthew Hoffman, Razvan Pascanu, Nando de Freitas, 2021.
* [COIL] <[Curriculum Offline Imitation Learning](https://arxiv.org/abs/2111.02056)> by Minghuan Liu, Hanye Zhao, Zhengyu Yang, Jian Shen, Weinan Zhang, Li Zhao, Tie-Yan Liu, NeurIPS 2021.
* [EDAC] <[Uncertainty-Based Offline Reinforcement Learning with Diversified Q-Ensemble](https://proceedings.neurips.cc/paper/2021/hash/3d3d286a8d153a4a58156d0e02d8570c-Abstract.html)> by Gaon An, Seungyong Moon, Jang-Hyun Kim, Hyun Oh Song, NeurIPS 2021.
* [TD3-BC] <[A Minimalist Approach to Offline Reinforcement Learning](https://proceedings.neurips.cc/paper/2021/hash/a8166da05c5a094f7dc03724b41886e5-Abstract.html)> by Scott Fujimoto, Shixiang (Shane) Gu, NeurIPS 2021.

### Model-based

* [MOReL] <[MOReL : Model-Based Offline Reinforcement Learning](https://arxiv.org/abs/2005.05951)> by Rahul Kidambi, Aravind Rajeswaran, Praneeth Netrapalli and Thorsten Joachims, NeurIPS 2020.
* [MOPO] <[MOPO: Model-based Offline Policy Optimization](https://arxiv.org/abs/2005.13239)> by Tianhe Yu et al., NeurIPS 2020.
* [MOOSE] <[Overcoming Model Bias for Robust Offline Deep Reinforcement Learning](https://arxiv.org/abs/2008.05533)> by Phillip Swazinna, Steffen Udluft, Thomas Runkler, EAAI 2021.
* [MBOP] <[Model-Based Offline Planning](https://openreview.net/forum?id=OMNB1G5xzd4)> by Arthur Argenson, Gabriel Dulac-Arnold, ICLR 2021.
* <[Autoregressive Dynamics Models for Offline Policy Evaluation and Optimization](https://openreview.net/forum?id=kmqjgSNXby)> by Michael R Zhang, Thomas Paine, Ofir Nachum, Cosmin Paduraru, George Tucker, Ziyu Wang, Mohammad Norouzi, ICLR 2021.
* [COMBO] <[COMBO: Conservative Offline Model-Based Policy Optimization](https://proceedings.neurips.cc/paper/2021/hash/f29a179746902e331572c483c45e5086-Abstract.html)> by Tianhe Yu, Aviral Kumar, Rafael Rafailov, Aravind Rajeswaran, Sergey Levine, Chelsea Finn, NeurIPS 2021.
* [MAPLE] <[Offline Model-based Adaptable Policy Learning](https://papers.nips.cc/paper/2021/hash/470e7a4f017a5476afb7eeb3f8b96f9b-Abstract.html)> by Xiong-Hui Chen, Yang Yu, Qingyang Li, Fan-Ming Luo, Zhiwei Qin, Wenjie Shang, Jieping Ye, NeurIPS 2021.
* <[Weighted model estimation for offline model-based reinforcement learning](https://papers.nips.cc/paper/2021/hash/949694a5059302e7283073b502f094d7-Abstract.html)> by Toru Hishinuma, Kei Senda, NeurIPS 2021.

### Transformer

- [DT] <[Decision Transformer: Reinforcement Learning via Sequence Modeling](https://proceedings.neurips.cc/paper/2021/hash/7f489f642a0ddb10272b5c31057f0663-Abstract.html)> by Lili Chen,   Kevin Lu, Aravind Rajeswaran, Kimin Lee, Aditya Grover, Michael Laskin, Pieter Abbeel, Aravind Srinivas, Igor Mordatch, NeurIPS 2021.
- [TT] <[Offline Reinforcement Learning as One Big Sequence Modeling Problem](https://proceedings.neurips.cc/paper/2021/hash/099fe6b0b444c23836c4a5d07346082b-Abstract.html)> by Michael Janner, Qiyang Li, Sergey Levine, NeurIPS 2021.

## Meta/Multi-task

- [MBML] <[Multi-task Batch Reinforcement Learning with Metric Learning](https://proceedings.neurips.cc/paper/2020/hash/4496bf24afe7fab6f046bf4923da8de6-Abstract.html)> by Jiachen Li, Quan Vuong, Shuang Liu, Minghua Liu, Kamil Ciosek, Henrik Christensen, Hao Su, NeurIPS 2020.
- [SMAC] <[Offline Meta-Reinforcement Learning with Online Self-Supervision](https://arxiv.org/abs/2107.03974)> by Vitchyr H. Pong, Ashvin Nair, Laura Smith, Catherine Huang, Sergey Levine, 2021.
- [MACAW] <[Offline Meta-Reinforcement Learning with Advantage Weighting](https://arxiv.org/abs/2008.06043)> by Eric Mitchell, Rafael Rafailov, Xue Bin Peng, Sergey Levine, Chelsea Finn, ICML 2021.
- [FOCAL] <[FOCAL: Efficient Fully-Offline Meta-Reinforcement Learning via Distance Metric Learning and Behavior Regularization](https://openreview.net/forum?id=8cpHIfgY4Dj)> by Lanqing Li, Rui Yang, Dijun Luo, ICLR 2021.
- [CDS] <[Conservative Data Sharing for Multi-Task Offline Reinforcement Learning](https://papers.nips.cc/paper/2021/hash/5fd2c06f558321eff612bbbe455f6fbd-Abstract.html)> by Tianhe Yu, Aviral Kumar, Yevgen Chebotar, Karol Hausman, Sergey Levine, Chelsea Finn, NeurIPS 2021.
- [BOReL] <[Offline Meta Reinforcement Learning – Identifiability Challenges and Effective Data Collection Strategies](https://papers.nips.cc/paper/2021/hash/248024541dbda1d3fd75fe49d1a4df4d-Abstract.html)> by Ron Dorfman, Idan Shenfeld, Aviv Tamar, NeurIPS 2021.

## Data Augmentation

- [DrQ] <[Image Augmentation Is All You Need: Regularizing Deep Reinforcement Learning from Pixels](https://openreview.net/forum?id=GY6-6sTvGaf)> by Denis Yarats, Ilya Kostrikov, Rob Fergus, ICLR 2021.
- [DrQ-v2] <[Mastering Visual Continuous Control: Improved Data-Augmented Reinforcement Learning](https://arxiv.org/abs/2107.09645)> by Denis Yarats, Rob Fergus, Alessandro Lazaric, Lerrel Pinto, 2021.
- [RAD] <[Reinforcement Learning with Augmented Data](https://proceedings.neurips.cc/paper/2020/hash/e615c82aba461681ade82da2da38004a-Abstract.html)> by Misha Laskin, Kimin Lee, Adam Stooke, Lerrel Pinto, Pieter Abbeel, Aravind Srinivas, NeurIPS 2021.
- [S4RL] <[S4RL: Surprisingly Simple Self-Supervision for Offline Reinforcement Learning in Robotics](https://openreview.net/forum?id=8xC5NNej-l_)> by Samarth Sinha, Ajay Mandlekar, Animesh Garg, CoRL 2021.

## Benchmark

* [D4RL] <[D4RL: Datasets for Deep Data-Driven Reinforcement Learning](https://arxiv.org/abs/2004.07219)> by Justin Fu, Aviral Kumar, Ofir Nachum, George Tucker, Sergey Levine, 2020.

* <[Rl Unplugged: Benchmarks for Offline Reinforcement Learning](https://arxiv.org/abs/2006.13888)> by Caglar Gulcehre, et al., 2020.

* [NeoRL] <[NeoRL: A Near Real-World Benchmark for Offline Reinforcement Learning](https://arxiv.org/abs/2102.00714)> by Rongjun Qin, Songyi Gao, Xingyuan Zhang, Zhen Xu, Shengkai Huang, Zewen Li, Weinan Zhang, Yang Yu, 2021.

## Applied Batch RL

* <[Scaling data-driven robotics with reward sketching and batch reinforcement learning](https://ui.adsabs.harvard.edu/abs/2019arXiv190912200C/abstract)> by Ajay Mandlekar, et al., 2019.

* <[Way Off-Policy Batch Deep Reinforcement Learning of Implicit Human Preferences in Dialog](https://arxiv.org/abs/1907.00456)> by Natasha Jaques et al., 2019.

* <[Iris: Implicit reinforcement without interaction at scale for learning control from offline robot manipulation data](https://ieeexplore.ieee.org/abstract/document/9196935/)> by Ajay Mandlekar, et al., 2020.

## Representation Learning

* <[Representation Matters: Offline Pretraining for Sequential Decision Making](https://arxiv.org/abs/2102.05815)> by Mengjiao Yang, Ofir Nachum, ICML 2021.

## Thoery Batch RL

* <[The importance of pessimism in fixed-dataset policy optimization](https://arxiv.org/abs/2009.06799)> by Jacob Buckman, Carles Gelada, Marc G. Bellemare, ICLR 2020.
* <[Is Pessimism Provably Efficient for Offline RL?](https://arxiv.org/abs/2012.15085)> by Ying Jin, Zhuoran Yang, Zhaoran Wang, ICLR 2021.
* <[Bridging Offline Reinforcement Learning and Imitation Learning: A Tale of Pessimism](https://proceedings.neurips.cc/paper/2021/hash/60ce36723c17bbac504f2ef4c8a46995-Abstract.html)> by Paria Rashidinejad, Banghua Zhu, Cong Ma, Jiantao Jiao, Stuart Russell, NeurIPS 2021.
* <[What are the Statistical Limits of Offline RL with Linear Function Approximation?](https://openreview.net/forum?id=30EvkP2aQLD)> by Ruosong Wang, Dean Foster, Sham M. Kakade, ICLR 2021.
* <[Offline Constrained Multi-Objective Reinforcement Learning via Pessimistic Dual Value Iteration](https://papers.nips.cc/paper/2021/hash/d5c8e1ab6fc0bfeb5f29aafa999cdb29-Abstract.html)> by Runzhe Wu, Yufeng Zhang, Zhuoran Yang, Zhaoran Wang, NeurIPS 2021.
