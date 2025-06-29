---
layout: page
title: "Tutorial"
permalink: /Tutorial.html
---

<link type="text/css" rel="stylesheet" href="assets/css/style.css" />

## Decision Making in Open Agent Systems (AAMAS'2025 Tutorial)

**Morning of May 19th, 2025**

---

### Description

Many real-world applications of multiagent systems (MAS) are open agent systems (OASYS) where the sets of agents, tasks, and capabilities can dynamically change over time. Often, these changes are unpredictable and unknown in advance by the decision making agents utilizing their capabilities to accomplish tasks.

In contrast, most methods for autonomous decision making (whether planning, reinforcement learning, or game theory) assume that the set of agents, tasks, and capabilities are static throughout the lifetime of the system. Mismatches between the assumptions of the agents’ reasoning and models of the environment vs. the underlying dynamics of the environment can risk critical failure of agents deployed to real-world applications.

In this tutorial, we will:
1. Introduce OASYS as a challenging complexity of decision making in multiagent systems, illustrating different sources of openness in several real-world applications of MAS.
2. Summarize state-of-the-art solutions for decision making in OASYS within both the multiagent planning and multiagent reinforcement learning paradigms.
3. Highlight several promising avenues of future research that would enhance the ability of agents to reason within OASYS.

---

### Learning Outcomes

Participants will enhance their understanding of:
- The challenges of multiagent decision-making in open agent systems caused by the sets of agents, tasks, and/or agent capabilities changing over time in dynamic and unpredictable ways.
- State-of-the-art planning and reinforcement learning solutions for autonomous reasoning in open agent systems, including a comparison of their relative strengths and weaknesses.
- Active areas of current and future research for improving reasoning in such challenging multiagent environments.

---

### Target Audience

We expect two target audiences for this tutorial:

1. Researchers studying multiagent decision making (e.g., planning, reinforcement learning, and game theory practitioners) interested in exploring additional challenging environment complexities created by real-world applications.
2. AAMAS attendees who work in applied multiagent systems involving OASYS and are seeking decision-making solutions for such problems.

We hope to provide useful background information for both audiences and encourage collaboration across research and application domains.

---

### Tutorial Outline

- **Topic 1: Introduction to Open Agent Systems**
  - Types and Sources of Openness  
  - Challenges Caused by Openness  
  - Example Applications  

- **Topic 2: Multiagent Reasoning in OASYS**
  - Origins of OASYS  
  - Background: (Multiagent) Markov Decision Processes  
  - Planning and Reinforcement Learning Solutions  

- **Topic 3: Emerging and Future Research in OASYS**
  - Addressing Scalability to Many-Agent Systems  
  - Focusing on Task and Type Openness  
  - Human-Agent Interactions  

- **Topic 4: Community Discussion and MOASEI Competition**

---

### Presenters

- [Adam Eck](https://cs.oberlin.edu/~aeck), Oberlin College  
- [Prashant Doshi](https://thinc.cs.uga.edu/), University of Georgia  
- [Leen-Kiat Soh](http://cse.unl.edu/~lksoh/), University of Nebraska  

---

### Tutorial Slides

Our slides are [available here (current version 1.0, posted 05/18/2025)](OASYSTutorial_AAMAS2025.pptx)

---

### Contact

For any queries or further information, please reach out to:

**Email:** [aeck@oberlin.edu](mailto:aeck@oberlin.edu)

---

### Acknowledgements

This research was supported by a collaborative NSF Grant:
- [#IIS-2312657](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2312657&HistoricalAwards=false) (to P.D.)  
- [#IIS-2312658](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2312658&HistoricalAwards=false) (to L.K.S.)  
- [#IIS-2312659](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2312659&HistoricalAwards=false) (to A.E.)

This work also used the Holland Computing Center of the University of Nebraska and received support from the UNL Office of Research and Economic Development and the Nebraska Research Initiative.

We thank the following students for contributing to the development of OASYS:

Muthukumaran Chandrasekaran, Maulik Shah, Anirudh Kakarlapudi, Keyang He, Gayathri Anil, Bala Duggirala, Ceferino Patino, Alireza Saleh Abadi, Tyler Billings, Daniel Firebanks-Quevedo, Quinn Barker-Plummer, Tumas Rackaitis, Gaurab Pokharel, Ran Liu, Tianxing Zhu, Zejian Huang, Dung Do, Kenean Yemane Kejela, Quan Nguyen, Ryn Lazorchak, Menard Simoya, and M. Daud Zarif.
