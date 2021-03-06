---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About Me
I am a [Prime Minister's Research Fellow](https://pmrf.in/) (May 2019 batch) in the Department of Electrical Communication Engineering, Indian Institute of Science, where I am being advised by [Prof. Himanshu Tyagi](https://ece.iisc.ac.in/~htyagi/). Before starting my PhD in 2019, I completed my M.Tech (Research) in the Department of Electrical Engineering, Indian Institute of Science, under the supervision of [Prof. Kunal N. Chaudhury](https://sites.google.com/site/kunalnchaudhury/).

**Email:** adityavs [at] iisc [dot] ac [dot] in


## Research
My research interests lie in statistics, information theory, and optimization. Currently, I am working on problems in distributed statistical inference under communication constraint.

Statistical inference problems ask us to make some inference about a probabilistic source, given access to $n$ samples from it. In the distributed setting, the samples are distributed across multiple agents (players), who send messages to a central referee (center). Based on these messages, the center must make some inference about the probabilistic source. What makes distributed inference challenging are the constraints on the communication-link between the players and the center. One such constraint is where a player can send only an $\ell$-bit message to the center, as depicted in the figure below.

<center><img src="/images/diststat.JPG" width="400" height="400"></center>

We are interested in characterizing the sample complexity of statistical inference in this setting: Given an inference problem, what is the *minimum number of players* required for the center to solve the problem? Moreover, we want to *design optimal protocols* that the players and the center can implement to accomplish the inference task at hand. Currently, we are looking at two specific distributed inference problems under communication constraint:

**Closeness testing:** Here, in addition to the players receiving samples from distribution $P$, the center receives samples from a distribution $Q$. Based on the $\ell$-bit messages from the players, the center must output, with probability of error at most $1/3$, whether $P=Q$, or whether $d_{TV}(P,Q) > \epsilon$, for a given $\epsilon > 0$. Here, $d_{TV}$ stands for the total variation distance between probability distributions.

**Nonparametric density estimation:** Here, the players observe samples from a distribution $P$, whose density is known to belong to a class of sufficiently smooth functions (e.g. functions that are twice differentiable, with bounded derivatives). Based on the $\ell$-bit messages from the players, the center must output an estimate of the density of $P$. Given that there are $n$ players, the problem is to characterize the minimax mean squared error between the estimate and the true (unknown) distribution $P$.


## Courses
I have credited the following courses during my PhD.
- Information Theory
- Detection and Estimation
- Online Learning and Prediction
- Stochastic Processes and Queuing Theory
- Topics in Stochastic Approximation
- Foundations of Data Science


## Teaching
- TA for [Information Theory (2020)](https://ece.iisc.ac.in/~htyagi/course-E2201-2020.html) 
- TA for [NPTEL course on Information Theory (2020)](https://nptel.ac.in/courses/108/108/108108168/#) 


## Publications
- **On Uniquely Registrable Networks** [[arXiv]](https://arxiv.org/abs/1906.09714)  
Aditya Vikram Singh, Kunal N. Chaudhury  
IEEE Transactions on Network Science and Engineering (2019)  
Oral presentation at [ICASSP 2019](https://ieeexplore.ieee.org/document/8682680)  

- **An Iterative Eigensolver for Rank-Constrained Semidefinite Programming**  
Rajat Sanyal, Aditya Vikram Singh, Kunal N. Chaudhury  
Oral presentation at [NCC 2019](https://ieeexplore.ieee.org/document/8732206)  

- **Convergence Analysis of Nonconvex ADMM for Rigid Registration** [[arxiv]](https://arxiv.org/abs/1907.07729)  
Aditya Vikram Singh, Kunal N. Chaudhury  


## Thesis  
**Theoretical and Algorithmic Aspects of Rigid Registration** [[pdf]](/files/thesis_mtech.pdf)  
M.Tech (Research), Indian Institute of Science, 2019
