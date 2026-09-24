---
type: lecture
date: 2026-09-24T13:10:00
title: "Lecture 03: Policy and Value Iteration"
tldr: "Model-based RL - Part II"
stat: lec
# for lectures stat: lec
description: We derive the Bellman Optimality equation. This equation enables us to compute the optimal value function without needing to know the optimal policy. This further let us derive the optimal policy for an environment with known MDP. We then use dynamic programming to find the solution to the Bellman equation. We can do this in two different ways. (i) We could start with a policy, evaluate it with DP and then improve the policy iteratively. This will lead to policy iteration algorithm. (ii) Alternatively, we can iterate to find the optimal values and then specify the optimal policy out of it. This is value iteration. We look at both algorithms and also merge them into the unified generalized policy iteration scheme. 
videoID: CbyhKJesiqU
hide_from_announcments: false
---
**Lecture Notes:**
- [Chapter 2 - Section 2]({{ site.baseurl }}/assets/Notes/CH2/CH2_Sec2.pdf) 
- [Chapter 2 - Section 3]({{ site.baseurl }}/assets/Notes/CH2/CH2_Sec3.pdf) 

**Further Reads:**
* [VI and PI](http://incompleteideas.net/book/the-book-2nd.html): Chapters 3 and 4 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
