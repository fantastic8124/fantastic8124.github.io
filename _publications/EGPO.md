<img width="279" height="62" alt="image" src="https://github.com/user-attachments/assets/33be9222-39a9-4e58-ba55-a43bb7bd33d6" />---
title: "Optimizing Multi-agent Behavior for Interactive Autonomous Driving with Equilibrium Value Estimation"
collection: publications
permalink: /publication/EGPO
date: 2025-07-25
venue: '(submit) Transportation Research Part C: Emerging Technologies'
---
<p style="font-size:small; line-height:1;">Jialin Fan<sup style="font-size:smaller;">1,2</sup>, Ying Ni<sup style="font-size:smaller;">1,2</sup>, Yujia Zhao<sup style="font-size:smaller;">1,2</sup>, Jie Sun<sup style="font-size:smaller;">1,2</sup>, and Jian Sun<sup style="font-size:smaller;">1,2</sup></p>
<p style="font-size:small; line-height:1;"><sup style="font-size:smaller;">1</sup> Department of Transportation Engineering, Tongji University, Shanghai, China</p>
<p style="font-size:small; line-height:1;"><sup style="font-size:smaller;">2</sup> Key Laboratory of Road and Traffic Engineering, Ministry of Education, Shanghai, China</p>

<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/a703189a-f076-42c3-b769-a8013c709151" alt="Proposed" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 1: 1521cutin85.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/20f3b7cb-461f-4800-90aa-9b8fef354c1d" alt="Baseline" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 2: 1455lanechanging46.</figcaption>
  </figure>
</div>


The safe deployment of autonomous vehicles (AVs) into real-world traffic requires robust interaction with human drivers exhibiting heterogeneous behavioral tendencies, spanning from rational cooperation to adversarial aggression. Existing methods often lack the capacity to systematically model such behavioral diversity, limiting their applicability for rigorous evaluation of AV. 
To address this challenge, we propose a multi-agent reinforcement learning (MARL) framework that generates diverse interactive traffic through Estimation-Guided Policy Optimization (EGPO). Central to EGPO is the Equilibrium Value Estimation (EVE), a learnable hyperparameter that weights the outputs of the rational value function and the adversarial value function, reconstructing the policy's estimation of the expected reward. Notably, EVE is globally updated using meta-learning during policy learning. Furthermore, an EVE-guided policy network is used to feature multi-head architectures that efficiently process high-dimensional multi-agent observations while dynamically prioritizing context-specific features aligned with the learned EVEs.
Extensive experiments conducted in both urban and highway scenarios demonstrate that EGPO produces traffic environments with enhanced behavioral controllability and diversity. Furthermore, EGPO excels in the closed-loop AV testing on OnSite benchmark, outperforming SOTA methods based on deep learning and rule-based methods in terms of both realism and testing efficiency. Overall, EGPO offers a scalable and robust solution for simulating realistic interactions among diverse driving tendencies, facilitating the development of AV systems capable of handling complex real-world corner cases.


<div align="center"><strong>Closed-Loop Test with EGPO on OnSite benchmark</strong></div>

<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/a703189a-f076-42c3-b769-a8013c709151" alt="Proposed" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 1: 1521cutin85.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/20f3b7cb-461f-4800-90aa-9b8fef354c1d" alt="Baseline" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 2: 1455lanechanging46.</figcaption>
  </figure>
</div>

<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/f227075d-fe9c-4188-827c-49ab8c1b1294" alt="Proposed" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 3: 0_36_straight_straight_39.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/0129f799-7850-4728-9246-422d1a9618c5" alt="Baseline" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 4: 13_117_straight_in_adjacent_left_119.</figcaption>
  </figure>
</div>

<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/413a8751-6e29-4725-8be0-fae7c380d94d" alt="Proposed" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 5: _0_76_merge_82.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/8d962cc1-0ff8-4e5d-b26d-bdcef0226fc6" alt="Baseline" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 6: 0_879_merge_895.</figcaption>
  </figure>
</div>
