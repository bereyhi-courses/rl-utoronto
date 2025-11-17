---
type: lecture
date: 2025-11-11T17:15:00
title: "Lecture 49: PGM as Sequential Surrogate Optimization"
tldr: "Trust Region PGM I"
stat: lec
# for lectures stat: lec
description: Vanilla and baseline PGM still suffer from instability. We see in this lecture that we can interpret PGM update as sequential surrogate function optimization. This reveals us that the key challenge is unrestricted update in each iteration. This motivates us to study trust-region PGM approaches.
videoID: QaZGcrcfnmY  
hide_from_announcments: false
---
- [Chapter 5 - Section 3]({{ site.baseurl }}/assets/Notes/CH5/CH5_Sec3.pdf) 

**Further Reads:**
* [Nat PGM](https://papers.nips.cc/paper_files/paper/2001/hash/4b86abe48d358ecf194c56c69108433e-Abstract.html) Paper _A Natural Policy Gradient_ published by _S. Kakade_ in 2001 proposing a basic natural PGM
* [TRPO](https://proceedings.mlr.press/v37/schulman15.html) Paper _Trust Region Policy Optimization_ published by _J. Schulman et al._ in 2015 proposing TRPO