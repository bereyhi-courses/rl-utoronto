---
type: lecture
date: 2026-10-08T13:10:00
title: "Lecture 5: Deep Bootstraping and epsilon-Greedy Improvement"
tldr: "Model-Free RL - Part II"
stat: lec
# for lectures stat: lec
description: We study deep bootstraping. This enables us to extend the TD idea to TD-n. We then use this idea to find a sample efficient estimator of values, i.e., TD-lambda. The idea is though not online. We address this issue by doing Eligibility Tracing back in time. This leads to an online and efficient evaluation scheme. We then use these ideas to perform online control. We see that greedy improvement can lead to poor control, due to lack of exploration. To address this issue, we design the epsilon-greedy improvement, which let us explore and exploit at the same time.
videoID: U9zIG_nmaxM
hide_from_announcments: false
---
**Lecture Notes:**
- [Chapter 3 - Section 3]({{ site.baseurl }}/assets/Notes/CH3/CH3_Sec3.pdf) 
- [Chapter 3 - Section 4]({{ site.baseurl }}/assets/Notes/CH3/CH3_Sec4.pdf) 

**Further Reads:**
* [TD-n](http://incompleteideas.net/book/the-book-2nd.html): Chapter 7 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html) 
* [TD-lambda and Eligibility Tracing](http://incompleteideas.net/book/the-book-2nd.html): Chapter 12 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
* [MC Control](http://incompleteideas.net/book/the-book-2nd.html): Chapter 5 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)
* [&epsilon;-Greedy](http://incompleteideas.net/book/the-book-2nd.html): Chapter 2 of [[SB]](http://incompleteideas.net/book/the-book-2nd.html)