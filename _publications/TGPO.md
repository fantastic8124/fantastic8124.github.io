---
title: "Learning to Model Diverse Interactive Traffic with Driving Tendency-Guided Policy Optimization"
collection: publications
permalink: /publication/TGPO
date: 2025-02-01
venue: 'IEEE INTELLIGENT VEHICLES SYMPOSIUM (IV)'
---
<p style="font-size:small; line-height:1;">Jialin Fan<sup style="font-size:smaller;">1,2</sup>, Ying Ni<sup style="font-size:smaller;">1,2</sup>, Yuhao Yang<sup style="font-size:smaller;">1,2</sup>,  Wentao Zheng<sup style="font-size:smaller;">1,2</sup>,  Jie Sun<sup style="font-size:smaller;">1,2</sup>, and Jian Sun<sup style="font-size:smaller;">1,2</sup></p>
<p style="font-size:small; line-height:1;"><sup style="font-size:smaller;">1</sup> Department of Transportation Engineering, Tongji University, Shanghai, China</p>
<p style="font-size:small; line-height:1;"><sup style="font-size:smaller;">2</sup> Key Laboratory of Road and Traffic Engineering, Ministry of Education, Shanghai, China</p>

![2](https://github.com/user-attachments/assets/65e6da6e-a02d-456b-b6f0-9c9ed586aba1)
The safe deployment of autonomous vehicles (AVs) into real-world traffic requires robust interaction with human drivers exhibiting heterogeneous behavioral tendencies, spanning from rational cooperation to adversarial aggression. Existing simulation frameworks often lack the capacity to systematically model such behavioral diversity, limiting their applicability for rigorous AV evaluation. To address this challenge, we propose a multi-agent reinforcement learning framework that generates dynamically controllable traffic through Tendency-Guided Policy Optimization (TGPO). Central to TGPO is the Adversary-Rationality-Tendency (ART), a continuous hyperparameter that enables fine-grained control over the spectrum of driving behaviors by fusing separately learned adversarial and rational value functions. Furthermore, we design an ART-guided policy network incorporating multi-head mechanisms to resolve high-dimensional multi-agent observations, adaptively prioritizing context features aligned with assigned driving tendencies. Extensive experiments across urban and highway scenarios demonstrate that TGPO generates traffic flows with enhanced behavioral controllability and diversity. The proposed method provides a scalable solution for simulating realistic driver interactions, thereby facilitating the development of AV systems capable of handling complex real-world corner cases.

 <div align="center"><strong>Case Studies with TGPO</strong></div>
 ![image](https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/bdc207b3-1190-4fc0-a540-ce81c16d75c2)
To validate the capability of TGPO in generating diverse and controllable driving behaviors, we construct three representative interactive scenarios involving an autonomous vehicle (AV), which was governed by a vanilla PPO agent trained by single-agent RL [24]; And four surrounding vehicles (SVs) governed by TGPO agents. Each scenario defines fixed start and goal positions for all vehicles, requiring agents to dynamically negotiate trajectories without predefined rules. Two SVs are designed to interact directly with the AV, while the remaining two serve as control groups to verify baseline driving task completion.
<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/ac634ed4-0645-4807-addf-c91d58966c4b" alt="Proposed" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 1: Roundabout Negotiation #1.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/18f91f1e-5ef0-46ad-9948-553f5984480a" alt="Baseline" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 1: Roundabout Negotiation #2.</figcaption>
  </figure>
</div>
<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/7e62f44b-2460-4b14-8c95-28cf9a652cf6" alt="Proposed" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 2: T-Junction Conflict #1.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/bd4e9d9f-05a2-44bd-ab58-3f4b7fd06c91" alt="Baseline" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 2: T-Junction Conflict #2.</figcaption>
  </figure>
</div>
<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/998f2cb6-2fec-47ea-8194-fb02307d1558" alt="Proposed" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 3: Unprotected Turn #1.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/9f992da7-1518-4f12-b056-458717b2d71d" alt="Baseline" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 3: Unprotected Turn #2.</figcaption>
  </figure>
</div>
