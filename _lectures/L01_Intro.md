---
type: lecture
date: 2026-09-10T14:00:00
title: "Lecture 1: RL Framework"
tldr: "Introduction"
stat: lec
# for lectures stat: lec
description: We start with the multi-armed bandit problem, and see how optimally or randomly playing could change the collected reward. We look at a mix strategy, first explore the environment for some limited time and then exploit this exploration in the real-time. We see that we could get very close to the optimal reward if we play for a long enough time. We then formulate the RL setting for a general interactive problem. We get to know what the agent is, what the environment is, and how the interactions between them is formulated. We look into a few sample environment, namely Tic-Tac-Toe, Cart-Pole, and Trading examples. For each, we formulate the State, Action, and Reward. Finally, we introduce Gymnasium. 
videoID: rPPx3FjMETM
hide_from_announcments: false
---
**Lecture Notes:**
- [Chapter 1 - Section 1]({{ site.baseurl }}/assets/Notes/CH1/CH1_Sec1.pdf) 
- [Chapter 1 - Section 2]({{ site.baseurl }}/assets/Notes/CH1/CH1_Sec2.pdf) 

**Further Reads:**
* [Intro to RL](http://incompleteideas.net/book/the-book-2nd.html): Chapter 1 - Sections 1.1 and 1.2 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
* [k-armed Bandit](http://incompleteideas.net/book/the-book-2nd.html): Chapter 2 - Section 2.1 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
* [Robbins' Paper](https://www.ams.org/journals/bull/1952-58-05/S0002-9904-1952-09620-8/S0002-9904-1952-09620-8.pdf): Paper _Some aspects of the sequential design of experiments_ by _H. Robbins_ published in the _Bulletin of the American Mathematical Society_ in 1952 formulating multi-armed bandit as we know it nowadays
* [RL Setting](http://incompleteideas.net/book/the-book-2nd.html): Chapter 3 - Sections 3.1 to 3.3 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)