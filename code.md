---
layout: page
title: Code
---

<link type="text/css" rel="stylesheet" href="assets/css/style.css" />

Code for our Wildfire Suppression OASYS application and prior published solutions can be found at the two following GitHub repositories:

* [CommunicativeOASYS](https://github.com/OberlinAI/CommunicativeOASYS)

This repository contains a Cython implementation of Wildfire Suppression, as well as our open-agent Communicative I-POMDP decision process model and corresponding fully online CI-POMCP planning algorithm.  This code is based on our UAI'2022 publication: ["Decision-Theoretic Planning with Communication in Open Multiagent Systems"](https://proceedings.mlr.press/v180/kakarlapudi22a/kakarlapudi22a.pdf)

* [ScalableOASYS](https://github.com/OberlinAI/ScalableOASYS) 

This repository contains a Java implementation of Wildfire Suppression, as well as our approach for solution for scalable reasoning under agent openness that selectively models only a subset of neighbors, then extropolates their behaviors to the collective whole, and reasons using our I-POMCP online MCTS planning algorithm for the open-agent I-POMDP-Lite decision process.  This code is based on our AAAI'2020 publication: ["Scalable Decision-Theoretic Planning in Open and Typed Multiagent Systems"](https://aaai.org/ojs/index.php/AAAI/article/view/6200)
