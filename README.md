# Batch-RL-Paper-Lists
Paper Collection for Batch RL with brief introductions.

Batch RL can be seen as an interesting specifc area in imitation learning yet it learn purely from demonstrations (batch data) and do not need to interact with the environment.

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

* <[Benchmarking Batch Deep Reinforcement Learning Algorithms](https://arxiv.org/abs/1910.01708)> by Fujimoto, Edoardo Conti, Mohammad Ghavamzadeh, Joelle Pineau, 2019.

* <[Truly Batch Apprenticeship Learning with Deep Successor Features](https://arxiv.org/pdf/1903.10077)>, Donghun Lee, Srivatsan Srinivasan and Finale Doshi-Velez, 2019.

* [BCQ]<[Off-Policy Deep Reinforcement Learning without Exploration](https://arxiv.org/abs/1812.02900)> by Scott Fujimoto, David Meger and Doina Precup, 2019.

* [BEAR] <[Stabilizing Off-Policy Q-Learning via Bootstrapping Error Reduction](https://arxiv.org/1906.00949)> by Aviral Kumar, Justin Fu, George Tucker and Sergey Levine, NIPS 2019.

* <[Way Off-Policy Batch Deep Reinforcement Learning of Implicit Human Preferences in Dialog](https://arxiv.org/abs/1907.00456)> by Natasha Jaques et al. 2019.

* [AWR] <[Advantage-Weighted Regression: Simple and Scalable Off-Policy Reinforcement Learning](https://arxiv.org/1910.00177)> by Xue Bin Peng,  Aviral Kumar,  Grace Zhang and Sergey Levine,  2019.

* [AWAC] <[Accelerating Online Reinforcement Learning with Offline Datasets](https://arxiv.org/abs/2006.09359)> by Ashvin Nair, Murtaza Dalal, Abhishek Gupta, Sergey Levine, 2020.

* [ABM] <[Keep Doing What Worked: Behavioral Modelling Priors for Offline Reinforcement Learning](https://arxiv.org/2002.08396)> by Siegel et al. IClR 2020.

* <[Behavior Regularized Offline Reinforcement Learning](https://arxiv.org/abs/1911.11361)> by Yifan Wu, George Tucker, Ofir Nachum,  2019.

* [AlgaeDICE] <[AlgaeDICE: Policy Gradient from Arbitrary Experience](https://arxiv.org/abs/1912.02074)> by Ofir Nachum et al. 2019.

* [DualDICE] <[Dualdice: Behavior-agnostic estimation of discounted stationary distribution corrections](http://papers.nips.cc/paper/8503-dualdice-behavior-agnostic-estimation-of-discounted-stationary-distribution-corrections)> by Ofir Nachum, Yinlam Chow, Bo Dai, Lihong Li, ICML 2019.

* [GradientDICE] <[GradientDICE: Rethinking Generalized Offline Estimation of Stationary Values](https://arxiv.org/abs/2001.11113)> by Shangtong Zhang, Bo Liu, Shimon Whiteson, 2020.

* [REM] <[An Optimistic Perspective on Offline Reinforcement Learning](https://arxiv.org/abs/1907.04543)> by Rishabh Agarwal, Dale Schuurmans and Mohammad Norouzi, ICML 2020.

* <[Provably Good Batch Reinforcement Learning Without Great Exploration](https://arxiv.org/2007.08202)> by Yao Liu, Adith Swaminathan, Alekh Agarwal and Emma Brunskill, NIPS 2020.

* <[Expert-Supervised Reinforcement Learning for Offline Policy Learning and Evaluation](https://arxiv.org/abs/2006.13189)> by W, Aaron Sonabend et al. NIPS 2020.

* <[Multi-Task Batch Reinforcement Learning with Metric Learning](https://arxiv.org/abs/1909.11373)> by Jiachen Li et al. NIPS 2020.

* <[BAIL: Best-Action Imitation Learning for Batch Deep Reinforcement Learning](https://arxiv.org/abs/1910.12179)> by Xinyue Chen et al. NIPS 2020.

* <[Strictly Batch Imitation Learning by Energy-based Distribution Matching](https://arxiv.org/abs/2006.14154)> by Daniel Jarrett, Ioana Bica and Mihaela van der Schaar. NIPS 2020.

* [BOPAH] <[Batch Reinforcement Learning with Hyperparameter Gradients](https://icml.cc/Conferences/2020/ScheduleMultitrack?event=6388)> by Byung-Jun Lee, Jongmin Lee, Peter Vrancx, Dongho Kim, Kee-Eung Kim, ICML 2020.

* <[Conservative Q-Learning for Offline Reinforcement Learning](https://arxiv.org/abs/2006.04779)> by Aviral Kumar, Aurick Zhou, George Tucker, Sergey Levine, 2020.

* <[Batch Policy Learning under Constraints](https://arxiv.org/abs/1903.08738)> by Hoang M. Le, Cameron Voloshin, Yisong Yue, ICML 2019.

* [SPIBB] <[Safe policy improvement with baseline bootstrapping](http://proceedings.mlr.press/v97/laroche19a/laroche19a.pdf)> by Romain Laroche, Paul Trichelair, Remi Tachet des Combes, ICML 2019.

* <[On Value Discrepancy of Imitation Learning](https://arxiv.org/abs/1911.07027)> by Tian Xu, Ziniu Li, Yang Yu, 2019.

    ### Model-based

* [MOReL] <[MOReL : Model-Based Offline Reinforcement Learning](https://arxiv.org/abs/2005.05951)> by Rahul Kidambi, Aravind Rajeswaran, Praneeth Netrapalli and Thorsten Joachims, NIPS 2020.

* [MOPO] <[MOPO: Model-based Offline Policy Optimization](https://arxiv.org/abs/2005.13239)> by Tianhe Yu et al. NIPS 2020.

* [MOOSE] <[Overcoming Model Bias for Robust Offline Deep Reinforcement Learning](https://arxiv.org/abs/2008.05533)> by Phillip Swazinna, Steffen Udluft, Thomas Runkler, arXiv 2020.

* <[Model-Based Offline Planning](https://arxiv.org/abs/2008.05556)> by Arthur Argenson, Gabriel Dulac-Arnold, 2020.

    ### Benchmark

* [D4rl] <[D4rl: Datasets for deep data-driven reinforcement learning](https://arxiv.org/abs/2004.07219)> by Justin Fu, Aviral Kumar, Ofir Nachum, George Tucker, Sergey Levine, 2020.

* <[Rl unplugged: Benchmarks for offline reinforcement learning](https://arxiv.org/abs/2006.13888)> by Caglar Gulcehre, et al, 2020.

## Applied Batch RL

- <[Scaling data-driven robotics with reward sketching and batch reinforcement learning](https://ui.adsabs.harvard.edu/abs/2019arXiv190912200C/abstract)> by Ajay Mandlekar, et al., 2019.

- <[Iris: Implicit reinforcement without interaction at scale for learning control from offline robot manipulation data](https://ieeexplore.ieee.org/abstract/document/9196935/)> by Ajay Mandlekar, et al., 2020.






