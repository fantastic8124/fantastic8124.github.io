---
title: "Optimizing Multi-agent Behavior for Interactive Autonomous Driving with Equilibrium Value Estimation"
collection: publications
permalink: /publication/EGPO
date: 2025-07-25
venue: '(submit) Transportation Research Part C: Emerging Technologies'
---
<p style="font-size:small; line-height:1;">Jialin Fan<sup style="font-size:smaller;">1,2</sup>, Ying Ni<sup style="font-size:smaller;">1,2</sup>, Yujia Zhao<sup style="font-size:smaller;">1,2</sup>, Jie Sun<sup style="font-size:smaller;">1,2</sup>, and Jian Sun<sup style="font-size:smaller;">1,2</sup></p>
<p style="font-size:small; line-height:1;"><sup style="font-size:smaller;">1</sup> Department of Transportation Engineering, Tongji University, Shanghai, China</p>
<p style="font-size:small; line-height:1;"><sup style="font-size:smaller;">2</sup> Key Laboratory of Road and Traffic Engineering, Ministry of Education, Shanghai, China</p>

The safe deployment of autonomous vehicles (AVs) into real-world traffic requires robust interaction with human drivers exhibiting heterogeneous behavioral tendencies, spanning from rational cooperation to adversarial aggression. Existing methods often lack the capacity to systematically model such behavioral diversity, limiting their applicability for rigorous evaluation of AV. 
To address this challenge, we propose a multi-agent reinforcement learning (MARL) framework that generates diverse interactive traffic through Estimation-Guided Policy Optimization (EGPO). Central to EGPO is the Equilibrium Value Estimation (EVE), a learnable hyperparameter that weights the outputs of the rational value function and the adversarial value function, reconstructing the policy's estimation of the expected reward. Notably, EVE is globally updated using meta-learning during policy learning. Furthermore, an EVE-guided policy network is used to feature multi-head architectures that efficiently process high-dimensional multi-agent observations while dynamically prioritizing context-specific features aligned with the learned EVEs.
Extensive experiments conducted in both urban and highway scenarios demonstrate that EGPO produces traffic environments with enhanced behavioral controllability and diversity. Furthermore, EGPO excels in the closed-loop AV testing on OnSite benchmark, outperforming SOTA methods based on deep learning and rule-based in terms of both realism and testing efficiency. Overall, EGPO offers a scalable and robust solution for simulating realistic interactions among diverse driving tendencies, facilitating the development of AV systems capable of handling complex real-world corner cases.

<img width="531" height="354" alt="image" src="https://github.com/user-attachments/assets/a703189a-f076-42c3-b769-a8013c709151" />
