---
layout: page
title: OASYS
---

<link type="text/css" rel="stylesheet" href="assets/css/style.css" />

<img src="assets/images/NSF_Official_logo_Med_Res_600ppi.png" style="width:25%; float:right; margin:5px;"/>  This project is a multi-institution collaboration led by [Prashant Doshi](https://thinc.cs.uga.edu) of the University of Georgia, [Leen-Kiat Soh](http://cse.unl.edu/~lksoh/) of the University of Nebraska-Lincoln, and [Adam Eck](https://cs.oberlin.edu/~aeck) of Oberlin College.  Our work has been supported by two collaborative grants from the National Science Foundation: NSF [IIS-1910037](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1910037&HistoricalAwards=false), [IIS-1910156](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1910156&HistoricalAwards=false), [IIS-1909513](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1909513&HistoricalAwards=false) and NSF [IIS-2312657](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2312657&HistoricalAwards=false), [IIS-2312658](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2312658&HistoricalAwards=false), [IIS-2312659](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2312659&HistoricalAwards=false).

<br/>
<hr/>
<br/>

## Project Description

In many real-world applications of AI, the set of actors and tasks are not constant, but instead change over time.  Robots tasked with suppressing wildfires eventually run out of limited suppressant resources and need to temporarily disengage from the collaborative work in order to recharge, or they might become damaged and leave the environment permanently.  In a large business organization, objectives and goals change with the market, requiring workers to adapt to perform different sets of tasks across time.  We call these multiagent systems **open agent systems**, and the *openness* of the sets of agents and tasks  necessitates new capabilities and modeling for decision making compared to planning and learning in *closed* environments.

In this research, we address the challenges to multiagent decision making caused by three types of openness: 

1. **agent openness**, where the set of agents acting in the world change over time.  This could include agents temporarily disengaging from the environment before returning (e.g., autonomous ride-sharing cars recharging when low on energy), new groups of agents joining over time (e.g., new attackers appearing globally in a cybersecurity defense application), or existing agents leaving permanently (e.g., firefighting robots becoming damaged and needing to leave the operations to recover valuable hardware).

2. **task openness**, where the set of tasks that agents aim to accomplish change over time.  This could include new tasks appearing that are novel compared to existing tasks (e.g., transporting ride-sharing passengers for unique events) or popular existing tasks disappearing forever.  It could also entail a gradual shift in the requirements of tasks over time so that tasks gradually become different from their initial context.

3. **type openness**, where the types (i.e., capabilities) of agents change over time.  This could include agents learning new skills and gaining new responsibilities (e.g., promotions of office workers) or robots losing abilities over time (e.g., modeling damage to robots engaged in the field).

The following video provides a short overview of the problems, challenges, and solutions related to OASYS:

<div>
  <iframe style="display: block; margin: auto;" width="560" height="315" src="https://www.youtube.com/embed/vQOK3YNeTDE?si=4NO0ZqwAb893tTxI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
  <br/>
</div>

<br/>
<hr/>
<br/>

## Publications 

A summary of the research area of OASYS can be found in:

* Eck, A., Soh, L.-K., & Doshi, P. 2023. Decision Making in Open Multiagent Systems. AI Magazine. 44(4), 508-523. [[link]](https://onlinelibrary.wiley.com/doi/10.1002/aaai.12131)

More details about our research on OASYS can be found in:

* Aditya Shinde, Prashant Doshi. 2025. "Inferring Hidden Behavioral Signatures of Cyber Adversaries Using Inverse Reinforcement Learning", Proceedings of the 2025 Prestigious Applications of Intelligent Systems (PAIS)/ECAI [[link]](http://thinc.cs.uga.edu/files/p2763.pdf)

* Tyson Jordan, Pranav Pandey, Prashant Doshi, Ramviyas Parasuraman, Adam Goodie. 2025. "Analyzing Human Perceptions of a MEDEVAC Robot in a Simulated Evacuation Scenario", Proceedings of the 2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) [[link]](https://arxiv.org/abs/2410.19072)

* Pranav Pandey, Ramviyas Parasuraman, Prashant Doshi. 2025. "Integrating Perceptions: A Human-Centered Physical Safety Model for Human-Robot Interaction", Proceedings of the 2025 IEEE Robot-Human Interaction (RO-MAN)  [[link]](https://arxiv.org/abs/2507.06700)

* Yanyu Liu, Yinghui Pan, Yifeng Zeng, Biyang Ma, Prashant Doshi. 2025. "Active Legibility in Multiagent Reinforcement Learning", in Artificial Intelligence Journal (AIJ), Elsevier [[link]](https://www.sciencedirect.com/science/article/pii/S0004370225000761?via%3Dihub)

* Gayathri Anil, Prashant Doshi, Daniel Redder, Adam Eck, Leen-Kiat Soh. 2025. "MOHITO: Multi-Agent Reinforcement Learning using Hypergraphs for Task-Open Systems", Proceedings of the 2025 Conference on Uncertainty in AI (UAI)[[link]](http://thinc.cs.uga.edu/files/adresUAI25_cameraready.pdf)

* Prasanth Sengadu Suresh, Prashant Doshi, Bikramjit Banerjee. 2025. "Adaptive Human-Robot Collaboration using Type-Based IRL", Proceedings of the 2025 Conference on Uncertainty in AI (UAI) [[link]](http://thinc.cs.uga.edu/files/sdbUAI25.pdf)

* Bhavana Nare, Anusha Challa, John Bradley Frericks, Prashant Doshi, Kyle Johnsen. 2025. "A Novel Computational Framework of Robot Trust for Human-Robot Teams", Proceedings of the 2025 IEEE International Conference on Robotics and Automation (ICRA) [[link]](http://thinc.cs.uga.edu/files/nfdcjICRA25.pdf)

* Yikang Gui, Prashant Doshi. 2025. "Inversely Learning Transferable Rewards via Abstracted States". arXiv:2501.01669 [[link]](https://arxiv.org/abs/2501.01669)

* He, K., Doshi, P., & Banerjee, B. 2024. Robust Individualistic Learning in Many-Agent Systems. Proceedings of the 25th International Conference on Principles and Practice of Multi-Agent Systems (PRIMA'2024) [[link]](http://thinc.cs.uga.edu/files/hdbPRIMA24.pdf)

* Suresh, P.S., Romeres, D., Doshi, D., & Jain, S. 2024. Open Human-Robot Collaboration Systems (OHRCS): A Research Perspective. Proceedings of the 2024 IEEE Conference on Cognition and Machine Intelligence (CogMI'2024), Blue Sky/Vision Track. [[link]](http://thinc.cs.uga.edu/files/srdjCogMI24.pdf)

* Suresh, P.S., Jain, S., Doshi, P., & Romeres, D. 2024. Open Human-Robot Collaborations using Decentralized Inverse Reinforcement Learning. Proceedings of the 2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS'2024). [[link]](http://thinc.cs.uga.edu/files/sjprIROS24.pdf)

* Kakarlapudi, A., Anil, G., Eck, A., Doshi, P., & Soh, L.-K. 2022. Decision-Theoretic Planning with Communication in Open Multiagent Systems. Proceedings of the 2022 Conference on Uncertainty in Artificial Intelligence (UAI'22), Eindhoven, Netherlands, August 1-5, 2022 [[link]](https://proceedings.mlr.press/v180/kakarlapudi22a/kakarlapudi22a.pdf) [[Open Review with Appendices]](https://openreview.net/forum?id=H5LUOwUoql5) [[Code]](https://github.com/OberlinAI/CommunicativeOASYS)

* Eck, A., Shah, M., Doshi, P., & Soh, L.-K. 2020. Scalable Decision-Theoretic Planning in Open and Typed Multiagent Systems. Proceedings of the Thirty-fourth AAAI Conference on Artificial Intelligence (AAAI’2020), New York City, NY, February 8-12, 2020. [[link]](https://aaai.org/ojs/index.php/AAAI/article/view/6200) [[Preprint with Appendices]](https://arxiv.org/abs/1911.08642) [[Code]](https://github.com/OberlinAI/ScalableOASYS)

* Chandrasekaran, M., Eck, A., Doshi, P., & Soh, L.-K. 2016. Individual Planning in Open and Typed Agent Systems. Proceedings of the 2016 Conference on Uncertainty in Artificial Intelligence (UAI'16), New York City, NY, June 25-29, 2016. [[link]](http://www.auai.org/uai2016/proceedings/papers/286.pdf)

