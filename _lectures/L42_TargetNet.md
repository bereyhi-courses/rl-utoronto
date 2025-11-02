---
type: lecture
date: 2025-10-24T17:30:00
title: "Lecture 42: Target Network"
tldr: "Action-Value Learning"
stat: lec
# for lectures stat: lec
description: DQL in vanilla form has a second problem which is the fact that the labels computed by TD change by network update. This can deteriorate the convergence significantly. To address this issue, we could train via a nested loop in which we copy the value net into a Target Network and keep it fixed for multiple iterations. This helps significantly with convergence.
videoID: 47zX0rw5xu4 
hide_from_announcments: false
---
- [Chapter 4 - Section 4]({{ site.baseurl }}/assets/Notes/CH4/CH4_Sec4.pdf) 

**Further Reads:**
* [DQL Paper I](https://arxiv.org/abs/1312.5602) Paper _Playing Atari with Deep Reinforcement Learning_ published in 2013 by _V. Mnih et al._ describing DQL details