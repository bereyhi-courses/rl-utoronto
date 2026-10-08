---
type: lecture
date: 2026-10-01T13:10:00
title: "Lecture 4: Generalized Policy Iteration via Monte-Carlo and Temporal Difference"
tldr: "Model-Free RL - Part I"
stat: lec
# for lectures stat: lec
description: We start with model-free approaches for RL. We see that using Monte-Carlo estimate, we can estimate the values needed in a Generalized Policy Iteration algorithm. We hence develop a model-free GPI loop, where we use Monte-Carlo to estimate all required values directly from sample trajectories. We then use Bellman equation to estimate the values using bootstraping. This approach is called Temporal Difference (TD). We develop a GPI loop using TD, as well. 
videoID: 23EA5dmaQoE
hide_from_announcments: false
---
**Lecture Notes:**
- [Chapter 3 - Section 1]({{ site.baseurl }}/assets/Notes/CH3/CH3_Sec1.pdf) 
- [Chapter 3 - Section 2]({{ site.baseurl }}/assets/Notes/CH3/CH3_Sec2.pdf) 

**Further Reads:**
* [Monte-Carlo](http://incompleteideas.net/book/the-book-2nd.html): Chapter 5 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
* [TD-0](http://incompleteideas.net/book/the-book-2nd.html): Chapter 6 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)