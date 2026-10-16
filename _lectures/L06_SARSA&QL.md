---
type: lecture
date: 2026-10-16T13:10:00
title: "Lecture 6: SARSA Algorithms and Q-Learning"
tldr: "SARSA"
stat: lec
# for lectures stat: lec
description: We build a control loop using TD estimation. This enables us to learn the optimal policy while we are playing with it. The final algorithm is called State-Action Reward State-Action or simply SARSA. SARSA is the most used form of on-policy RL. We then discuss off-policy RL, and its specific form Q-learning. Here, we play epsilon-greedy, but we learn the value of the greedy policy. This leads to a simple control loop, often called the Q-Learning Algorithm. We discuss the requirements for both algorithms to converge. This is consistent with the notion of GLIE algorithms.
videoID: DHEmnL7DFwc
hide_from_announcments: false
---
- [Chapter 3 - Section 4]({{ site.baseurl }}/assets/Notes/CH3/CH3_Sec4.pdf)
- [Chapter 3 - Section 5]({{ site.baseurl }}/assets/Notes/CH3/CH3_Sec5.pdf) 

**Further Reads:**
* [Online Q-Learning](https://www.researchgate.net/publication/2500611_On-Line_Q-Learning_Using_Connectionist_Systems) Article _On-Line Q-Learning Using Connectionist Systems_ published in 1994 by _G. Rummery and M. Niranjan_ proposing SARSA as an online version of Q-Learning
* [Sarsa](http://incompleteideas.net/book/the-book-2nd.html): Chapters 6, 10, and 12 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
* [Q-Learning](http://incompleteideas.net/book/the-book-2nd.html): Chapters 6 and 12 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
* [Q-Learning Paper](https://link.springer.com/article/10.1007/bf00992698) Paper _Q-learning_ published in 1992 by _C Watkins and P. Dayan_proposing the off-policy learning as in Q-learning algorithm
*[Convergence](https://link.springer.com/article/10.1007/bf00992698) Paper _The O.D.E. Method for Convergence of Stochastic Approximation and Reinforcement Learning_ published in 2000 by _V. Borkar and S. Meyn_ studying convergence of Q-Learning and SARSA
