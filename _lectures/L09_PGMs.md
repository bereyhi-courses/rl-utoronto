---
type: lecture
date: 2026-11-12T13:15:00
title: "Lecture 09: Policy Gradient Theorem and PGMs"
tldr: "PGMs"
stat: lec
# for lectures stat: lec
description: We learn policy gradient theorem. This enables us to train a policy net to learn the optimal policy. Policy gradient theorem shows that we can use the gradient of state's log likelihood to train a policy net. Using the theorem, we can develop efficient algorithm for training of a policy network via SGD. This leads to the class of policy gradient methods (PGMs). We see that vanilla PGMs are sensitive to reward shift. We hence extend it to baseline PGMs and introduce the Advantage PGM algorithm. 
videoID: Vj1ID9dA9S8
hide_from_announcments: false
---
- [Chapter 5 - Section 1]({{ site.baseurl }}/assets/Notes/CH5/CH5_Sec1.pdf) 
- [Chapter 5 - Section 2]({{ site.baseurl }}/assets/Notes/CH5/CH5_Sec2.pdf) 

**Further Reads:**
* [REINFORCE](https://link.springer.com/article/10.1007/bf00992696) Paper _Simple statistical gradient-following algorithms for connectionist reinforcement learning_ published by _R. Williams_ in 1992 introducing REINFORCE algorithm
* [PGM Theorem](https://proceedings.neurips.cc/paper_files/paper/1999/hash/464d828b85b0bed98e80ade0a5c43b0f-Abstract.html) Paper _Policy Gradient Methods for Reinforcement Learning with Function Approximation_ published by _R. Sutton et al._ in 1999 developing the Policy Gradient Theorem
* [Baseline](https://people.eecs.berkeley.edu/~russell/papers/icml99-shaping.pdf) Paper _Policy invariance under reward transformations: Theory and application to reward shaping_ published by _A. Ng et al._ in 1999