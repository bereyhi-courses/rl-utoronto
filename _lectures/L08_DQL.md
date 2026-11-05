---
type: lecture
date: 2026-11-05T13:10:00
title: "Lecture 8: Deep SARSA and Deep Q-Learning"
tldr: "DQL"
stat: lec
# for lectures stat: lec
description: We now use the developed training loop to train a Q-network a control process. We look into both on-policy and off-policy cases, and conclude the vanilla form of the Deep Q-Learning algorithm. The fact that we are doing off-policy control in DQL enables us to boost the sample efficiency. We can use the same samples multiple times. This is what is known as experience replay and is a key component of DQL. 
videoID: HK54dBqpR3w
hide_from_announcments: false
---
- [Chapter 4 - Section 3]({{ site.baseurl }}/assets/Notes/CH4/CH4_Sec3.pdf) 


**Further Reads:**
* [Control with FA](https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf): Chapter 4 of [[CS]](https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf)
* [Deep Q-Learning](https://training.incf.org/sites/default/files/2023-05/Human-level%20control%20through%20deep%20reinforcement%20learning.pdf) Paper _Human-level control through deep reinforcement learning_ published in 2015 by _V. Mnih et al._ proposing the legendary idea of Deep Q-Learning
* [DQL Paper I](https://arxiv.org/abs/1312.5602) Paper _Playing Atari with Deep Reinforcement Learning_ published in 2013 by _V. Mnih et al._ describing DQL details
* [DQL Paper II](https://arxiv.org/abs/1509.06461) Paper _Deep Reinforcement Learning with Double Q-learning_ published in 2015 by _H. Haasselt et al._ proposing Double DQL
* [DQL Paper III](https://arxiv.org/abs/1511.06581) Paper _Dueling Network Architectures for Deep Reinforcement Learning_ published in 2016 by _Z. Wang et al._ proposing Dueling DQL
* [DQL Paper IV](https://arxiv.org/abs/1511.05952) Paper _Prioritized Experience Replay_ published in 2016 by _T. Schaul et al._ proposing a prioritizing experience replay scheme
* [Gorila](https://arxiv.org/abs/1507.04296) Paper _Massively Parallel Methods for Deep Reinforcement Learning_ published in 2015 by _A. Nair et al._ proposing Gorila