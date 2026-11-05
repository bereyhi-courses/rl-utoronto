---
type: lecture
date: 2026-10-22T13:10:00
title: "Lecture 7: Policy Evaluation with Function Approximation"
tldr: "Deep RL"
stat: lec
# for lectures stat: lec
description: In this lecture, we learn RL with function approximation. In this approach we estimate the values using a parameterized model, e.g., a NN. We look into the evaluation problem and develop training loops based on Monte Carlo and Temporal Difference to train a model for estimation of action-values of a policy. This leads to introduction of Value and Q-Networks. We show that by setting the state representation to one-hot and using a linear model, our training algorithms return to Tabular RL counterparts.  
videoID: T3d6w05SrT0
hide_from_announcments: false
---
- [Chapter 4 - Section 1]({{ site.baseurl }}/assets/Notes/CH4/CH4_Sec1.pdf) 
- [Chapter 4 - Section 2]({{ site.baseurl }}/assets/Notes/CH4/CH4_Sec2.pdf) 

**Further Reads:**
* [Prediction with FA](https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf): Chapter 3 of [[CS]](https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf)
* [Neuro-dynamic Programming](https://ieeexplore.ieee.org/abstract/document/478953) Paper _Neuro-dynamic programming: an overview_ published in 1995 by _D. Bertsekas and J. Tsitsiklis_ discussing function approximation for value learning
* [FA vs Tabular](https://dl.acm.org/doi/abs/10.1145/1273496.1273589) Paper _Analyzing feature generation for value-function approximation_ published in 2008 by _R. Parr et al._ discussing connections of RL with FA to tabular RL 
* [TD with FA](https://proceedings.neurips.cc/paper_files/paper/1996/hash/e00406144c1e7e35240afed70f34166a-Abstract.html) Paper _Analysis of Temporal-Diffference Learning with Function Approximation_ published in 1996 by _J. Tsitsiklis and B. Roy_ analyzing Prediction with parameterized models
* [RL with FA](http://leemon.com/papers/1995b.pdf) Paper _Residual Algorithms: Reinforcement Learning with Function Approximation_ published in 1995 by _L. BAird_ giving some critics to RL with FA