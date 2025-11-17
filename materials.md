---
layout: page
title: Materials
permalink: /materials/
---

## Lecture Notes
The lecture notes are uploaded through the semester. For each chapter, the notes are provided section by section. 
### Chapter 0: Course Overview and Logistics
* [Handouts]({{site.baseurl}}/assets/Notes/CH0/CH0.pdf): All Sections included in a single file

### Chapter 1: RL Framework
* [Section 1]({{site.baseurl}}/assets/Notes/CH1/CH1_Sec1.pdf): Multi-armed Bandit
* [Section 2]({{site.baseurl}}/assets/Notes/CH1/CH1_Sec2.pdf): RL Problem: _Definitions and Basics_
* [Section 3]({{site.baseurl}}/assets/Notes/CH1/CH1_Sec3.pdf): Playing in RL Framework
* [Section 4]({{site.baseurl}}/assets/Notes/CH1/CH1_Sec4.pdf): Our First Game


### Chapter 2: Model-based RL
* [Section 1]({{site.baseurl}}/assets/Notes/CH2/CH2_Sec1.pdf): Markov Decision Process and Bellman Equation
* [Section 2]({{site.baseurl}}/assets/Notes/CH2/CH2_Sec2.pdf): Bellman Optimality
* [Section 3]({{site.baseurl}}/assets/Notes/CH2/CH2_Sec3.pdf): Policy and Value Iteration

### Chapter 3: Model-free Tabular RL
* [Section 1]({{site.baseurl}}/assets/Notes/CH3/CH3_Sec1.pdf): Evaluation via Monte-Carlo 
* [Section 2]({{site.baseurl}}/assets/Notes/CH3/CH3_Sec2.pdf): Temporal Difference 
* [Section 3]({{site.baseurl}}/assets/Notes/CH3/CH3_Sec3.pdf): Deep Bootstrapping and Credit Assignment
* [Section 4]({{site.baseurl}}/assets/Notes/CH3/CH3_Sec4.pdf): Online Control via Monte-Carlo
* [Section 5]({{site.baseurl}}/assets/Notes/CH3/CH3_Sec5.pdf): Online Control via TD - _SARSA and Q-Learning_

### Chapter 4: RL with Function Approximation
* [Section 1]({{site.baseurl}}/assets/Notes/CH4/CH4_Sec1.pdf): Tabular RL vs RL with Function Approximation
* [Section 2]({{site.baseurl}}/assets/Notes/CH4/CH4_Sec2.pdf): Prediction with Function Approximation  
* [Section 3]({{site.baseurl}}/assets/Notes/CH4/CH4_Sec3.pdf): Control with Function Approximation  
* [Section 4]({{site.baseurl}}/assets/Notes/CH4/CH4_Sec4.pdf): Deep Q-Learning

### Chapter 5: Policy Gradient Methods (PGMs)
* [Section 1]({{site.baseurl}}/assets/Notes/CH5/CH5_Sec1.pdf): Policy Network
* [Section 2]({{site.baseurl}}/assets/Notes/CH5/CH5_Sec2.pdf): Training Policy Net and PGM 
* [Section 3]({{site.baseurl}}/assets/Notes/CH5/CH5_Sec3.pdf): PGM with Trust Region  
* [Section 4]({{site.baseurl}}/assets/Notes/CH5/CH5_Sec4.pdf): Basic Form TRPO and PPO





## Tutorial Notebooks and Videos
The tutorial notebooks can be accessed below. 
* [Tutorial 1]({{site.baseurl}}/assets/Tutorials/Tutorial_1.ipynb): Overview on RL environment and Introduction to Gymnasium, by __Eason Qu__ [Video](https://play.library.utoronto.ca/watch/b1e2e52ab234989cb9da863f4c4fbadc)
* [Tutorial 2]({{site.baseurl}}/assets/Tutorials/Tutorial_2.ipynb): Policy and Value Iteration, by __Eason Qu__ [Video](https://play.library.utoronto.ca/watch/d4f9c09f5081542d3592b146e526cc71)
* [Tutorial 3](https://colab.research.google.com/drive/1lOzNXLveTXTaTx5fHNUsAHnrHJiixMv3?usp=sharing): Monte Carlo Learning, by __Eason Qu__ [Video](https://play.library.utoronto.ca/watch/44b2dea347ae3fb106590342ae394e80)
* [Tutorial 4](https://colab.research.google.com/drive/1gQIEhCgANZBN76hyNT67S2y5Iv5ODVNJ?usp=sharing): TD Learning, by __Eason Qu__ [Video](https://play.library.utoronto.ca/watch/40f7e689ccb600d0577e9d1181509798)
* [Tutorial 5](https://q.utoronto.ca/courses/414555/modules): Midterm Review by __Eason Qu__ [Video](https://play.library.utoronto.ca/watch/5b3045ec1edec245607084dc5361ca90)
* [Tutorial 6](https://q.utoronto.ca/courses/414555/modules): Tabular vs Deep RL by __Eason Qu__ [Video](https://play.library.utoronto.ca/watch/c9e1b925ee70d8179bfb43e69aba5494)
* [Tutorial 7](https://q.utoronto.ca/courses/414555/modules): PGM by __Eason Qu__ [Video](https://play.library.utoronto.ca/watch/54a5a535f36689be21243ffb1b0bc11b)

## Book

Most of the contents covered in the first two parts of course can be further read in

* [[SB] Sutton, R., and Barto, A. _Reinforcement Learning: An Introduction,_ 2nd Edition, MIT Press, 2018](http://incompleteideas.net/book/the-book-2nd.html)

The following old preprint is also a good summary of important RL algorithms

* [[CS] Csaba Szepesvari, _Algorithms for Reinforcement Learning_ (2009)](https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf)

Most materials in the third part, i.e., deep RL, are collected from research papers. The following textbook is also good resources for __practicing hands-on skills.__

* [Maxim Lapan. _Deep Reinforcement Learning Hands-On._ O'Reilly Media, Inc., 2020.](https://www.oreilly.com/library/view/deep-reinforcement-learning/9781838826994/)


## Reading List

This section will be completed gradually through the semester.


### Chapter 1: RL Framework
#### Introduction
* [Intro to RL](http://incompleteideas.net/book/the-book-2nd.html): Chapter 1 - Sections 1.1 and 1.2 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)

#### Multi-armed Bandit
* [k-armed Bandit](http://incompleteideas.net/book/the-book-2nd.html): Chapter 2 - Section 2.1 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
* [Robbins' Paper](https://www.ams.org/journals/bull/1952-58-05/S0002-9904-1952-09620-8/S0002-9904-1952-09620-8.pdf): Paper _Some aspects of the sequential design of experiments_ by _H. Robbins_ published in the _Bulletin of the American Mathematical Society_ in 1952 formulating multi-armed bandit as we know it nowadays

#### RL Problem Formulation
* [RL Setting](http://incompleteideas.net/book/the-book-2nd.html): Chapter 1 - Sections 1.3 and 1.5 [[SB]](http://incompleteideas.net/book/the-book-2nd.html)


#### Terminal State and Episode
* [RL Setting](http://incompleteideas.net/book/the-book-2nd.html): Chapter 3 - Section 3.4 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)

### Chapter 2: Model-based RL
#### MDPs 
* [Intro to RL](http://incompleteideas.net/book/the-book-2nd.html): Chapter 3 - Sections 3.1 and 3.5 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)

#### Bellman Equation and Optimal Policy
* [Bellman and Optimality](http://incompleteideas.net/book/the-book-2nd.html): Chapter 3 - Sections 3.6 and 3.7 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)


#### Policy Iteration 
* [Policy Evaluation](http://incompleteideas.net/book/the-book-2nd.html): Chapter 4 - Section 4.1 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
* [Policy Improvement and Iteration](http://incompleteideas.net/book/the-book-2nd.html): Chapter 4 - Sections 4.2 and 4.3 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)

#### Value Iteration 
* [Value Iteration](http://incompleteideas.net/book/the-book-2nd.html): Chapter 4 - Sections 4.4, 4.6 and 4.7 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)

### Chapter 2: Model-free RL
#### Monte Carlo Approach
* [Monte-Carlo](http://incompleteideas.net/book/the-book-2nd.html): Chapter 5 - Sections 5.1, 5.2 and 5.3 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)

#### Temporal Difference
* [TD-0](http://incompleteideas.net/book/the-book-2nd.html): Chapter 6 - Sections 6.1, 6.3 and 6.3 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)

#### Deep Temporal Difference
* [TD-n](http://incompleteideas.net/book/the-book-2nd.html): Chapter 7 - Sections 7.1 and 7.2 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)

#### Credit Assignment
* [TD-lambda](http://incompleteideas.net/book/the-book-2nd.html): Chapter 12 - Sections 12.1 to 12.3 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)

#### Eligibility Trace
* [Eligibility Tracing](http://incompleteideas.net/book/the-book-2nd.html): Chapter 12 - Sections 12.4 and 12.5 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
* [RL with Eligibility](https://link.springer.com/article/10.1023/A:1018012322525) Paper _Reinforcement Learning with Replacing Eligibility Traces_ published in 1996 by _S. Singh and R. Sutton_ proposing the idea of including eligibility tracing in RL

#### Monte-Carlo Control
* [MC Control](http://incompleteideas.net/book/the-book-2nd.html): Chapter 5 - Sections 5.3 and 5.4 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)

#### &epsilon;-Greedy Improvement
* [&epsilon;-Greedy](http://incompleteideas.net/book/the-book-2nd.html): Chapter 2 - Sections 2.5 and 2.6 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)

#### Temporal-Difference Control
* [TD Control](http://incompleteideas.net/book/the-book-2nd.html): Chapter 6 - Section 6.2 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)

#### Sarsa Algorithm
* [Online Q-Learning](https://www.researchgate.net/publication/2500611_On-Line_Q-Learning_Using_Connectionist_Systems) Article _On-Line Q-Learning Using Connectionist Systems_ published in 1994 by _G. Rummery and M. Niranjan_ proposing SARSA as an online version of Q-Learning
* [Sarsa](http://incompleteideas.net/book/the-book-2nd.html): Chapter 6 - Section 6.4 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
* [Sarsa](http://incompleteideas.net/book/the-book-2nd.html): Chapter 10 - Sections 10.2 and 10.5 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
* [Sarsa](http://incompleteideas.net/book/the-book-2nd.html): Chapter 12 - Section 12.7 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)

#### Importance Sampling and Off-policy Learning
* [Importance Sampling](http://incompleteideas.net/book/the-book-2nd.html): Chapter 5 - Section 5.5 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
* [Off Policy Learning](http://incompleteideas.net/book/the-book-2nd.html): Chapter 12 - Sections 12.9 and 12.11 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)

#### Q-Learning
* [Q-Learning Paper](https://link.springer.com/article/10.1007/bf00992698) Paper _Q-learning_ published in 1992 by _C Watkins and P. Dayan_proposing the off-policy learning as in Q-learning algorithm
* [Q-Learning](http://incompleteideas.net/book/the-book-2nd.html): Chapter 6 - Section 6.5 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
* [Q-Learning](http://incompleteideas.net/book/the-book-2nd.html): Chapter 12 - Section 12.10 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)

#### Q-Learning vs SARSA
*[Convergence](https://link.springer.com/article/10.1007/bf00992698) Paper _The O.D.E. Method for Convergence of Stochastic Approximation and Reinforcement Learning_ published in 2000 by _V. Borkar and S. Meyn_ studying convergence of Q-Learning and SARSA


### Chapter 4: RL with Function Approximation
#### Function Approximation for Value Estimation
* [Function Approximation for RL](http://incompleteideas.net/book/the-book-2nd.html): Chapter 9 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
* [Neuro-dynamic Programming](https://ieeexplore.ieee.org/abstract/document/478953) Paper _Neuro-dynamic programming: an overview_ published in 1995 by _D. Bertsekas and J. Tsitsiklis_ discussing function approximation for value learning

#### Prediction via Function Approximation
* [Prediction with FA](https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf): Chapter 3 of [[CS]](https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf)
* [TD with FA](https://proceedings.neurips.cc/paper_files/paper/1996/hash/e00406144c1e7e35240afed70f34166a-Abstract.html) Paper _Analysis of Temporal-Diffference Learning with Function Approximation_ published in 1996 by _J. Tsitsiklis and B. Roy_ analyzing Prediction with parameterized models
* [FA vs Tabular](https://dl.acm.org/doi/abs/10.1145/1273496.1273589) Paper _Analyzing feature generation for value-function approximation_ published in 2008 by _R. Parr et al._ discussing connections of RL with FA to tabular RL
* [RL with FA](http://leemon.com/papers/1995b.pdf) Paper _Residual Algorithms: Reinforcement Learning with Function Approximation_ published in 1995 by _L. BAird_ giving some critics to RL with FA

#### Control via Function Approximation
* [Control with FA](http://incompleteideas.net/book/the-book-2nd.html): Chapters 10 and 11 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
* [Control with FA](https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf): Chapter 4 of [[CS]](https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf)


#### Deep Q-Learning
* [Off-Policy with FA](https://proceedings.neurips.cc/paper_files/paper/2008/file/e0c641195b27425bb056ac56f8953d24-Paper.pdf) Paper _A Convergent O(n) Algorithm for Off-policy Temporal-difference Learning with Linear Function Approximation_ published in 2008 by _R. Sutton et al._ analyzing off-policy learning via linear models
* [DQL](https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf): Chapter 4 - Section 4.3 of [[CS]](https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf)
* [Deep Q-Learning](https://training.incf.org/sites/default/files/2023-05/Human-level%20control%20through%20deep%20reinforcement%20learning.pdf) Paper _Human-level control through deep reinforcement learning_ published in 2015 by _V. Mnih et al._ proposing the legendary idea of Deep Q-Learning
* [DQL Paper I](https://arxiv.org/abs/1312.5602) Paper _Playing Atari with Deep Reinforcement Learning_ published in 2013 by _V. Mnih et al._ describing DQL details
* [DQL Paper II](https://arxiv.org/abs/1509.06461) Paper _Deep Reinforcement Learning with Double Q-learning_ published in 2015 by _H. Haasselt et al._ proposing Double DQL
* [DQL Paper III](https://arxiv.org/abs/1511.06581) Paper _Dueling Network Architectures for Deep Reinforcement Learning_ published in 2016 by _Z. Wang et al._ proposing Dueling DQL
* [DQL Paper IV](https://arxiv.org/abs/1511.05952) Paper _Prioritized Experience Replay_ published in 2016 by _T. Schaul et al._ proposing a prioritizing experience replay scheme
* [DQL Paper V](https://arxiv.org/abs/1507.06527) Paper _Deep Recurrent Q-Learning for Partially Observable MDPs_ published in 2017 by _M. Hausknecht and P. Stone_ extending DQL to more realistic cases
* [Gorila](https://arxiv.org/abs/1507.04296) Paper _Massively Parallel Methods for Deep Reinforcement Learning_ published in 2015 by _A. Nair et al._ proposing Gorila
* [Why Policy Net](https://spinningup.openai.com/en/latest/algorithms/ddpg.html) Article _Deep Deterministic Policy Gradient_ at _OpenAI Spinning Up_

### Chapter 5: Policy Gradient Method
#### Basic PGM
* [REINFORCE](https://link.springer.com/article/10.1007/bf00992696) Paper _Simple statistical gradient-following algorithms for connectionist reinforcement learning_ published by _R. Williams_ in 1992 introducing REINFORCE algorithm

#### Policy Gradient Theorem
* [PGM Theorem](https://proceedings.neurips.cc/paper_files/paper/1999/hash/464d828b85b0bed98e80ade0a5c43b0f-Abstract.html) Paper _Policy Gradient Methods for Reinforcement Learning with Function Approximation_ published by _R. Sutton et al._ in 1999 developing the Policy Gradient Theorem

#### Vanilla and Baseline PGM
* [Baseline](https://people.eecs.berkeley.edu/~russell/papers/icml99-shaping.pdf) Paper _Policy invariance under reward transformations: Theory and application to reward shaping_ published by _A. Ng et al._ in 1999

#### Trust Region PGM
* [Nat PGM](https://papers.nips.cc/paper_files/paper/2001/hash/4b86abe48d358ecf194c56c69108433e-Abstract.html) Paper _A Natural Policy Gradient_ published by _S. Kakade_ in 2001 proposing a basic natural PGM
* [TRPO](https://proceedings.mlr.press/v37/schulman15.html) Paper _Trust Region Policy Optimization_ published by _J. Schulman et al._ in 2015 proposing TRPO
* [PPO](https://arxiv.org/abs/1707.06347) Paper _Proximal Policy Optimization Algorithms_ published by _J. Schulman et al._ in 2017 proposing PPO
