---
title: "Optimizing Multi-agent Behavior for Interactive Autonomous Driving with Equilibrium Value Estimation"
collection: publications
permalink: /publication/EGPO
date: 2026-01-21
venue: '(submit) IEEE Transactions on Intelligent Transportation Systems'
---
<p style="font-size:small; line-height:1;">Jialin Fan<sup style="font-size:smaller;">1,2</sup>, Ying Ni<sup style="font-size:smaller;">1,2</sup>, Yujia Zhao<sup style="font-size:smaller;">1,2</sup>, Jie Sun<sup style="font-size:smaller;">1,2</sup>, and Jian Sun<sup style="font-size:smaller;">1,2</sup></p>
<p style="font-size:small; line-height:1;"><sup style="font-size:smaller;">1</sup> College of Transportation, Tongji University, Shanghai, China</p>
<p style="font-size:small; line-height:1;"><sup style="font-size:smaller;">2</sup> Key Laboratory of Road and Traffic Engineering, Ministry of Education, Shanghai, China</p>
![image](https://github.com/user-attachments/assets/4086b256-5205-49b0-a771-8711a5761f8c)

<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/43c9533e-a7b5-4a8c-a507-a4e5c389b6aa" alt="Proposed" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Vaniila MARL.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/5150ae21-3d21-4319-87c0-bea164e76763" alt="Baseline" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">EGPO.</figcaption>
  </figure>
</div>

The safe deployment of autonomous vehicles (AVs) into real-world traffic requires robust interaction with human drivers exhibiting heterogeneous behavioral tendencies, spanning from rational cooperation to adversarial aggression. Existing methods often lack the capacity to systematically model such behavioral diversity, limiting their applicability for rigorous evaluation of AV. 
To address this challenge, we propose a multi-agent reinforcement learning (MARL) framework that generates diverse interactive traffic through Estimation-Guided Policy Optimization (EGPO). Central to EGPO is the Equilibrium Value Estimation (EVE), a learnable hyperparameter that weights the outputs of the rational value function and the adversarial value function, reconstructing the policy's estimation of the expected reward. Notably, EVE is globally updated using meta-learning during policy learning. Furthermore, an EVE-guided policy network is used to feature multi-head architectures that efficiently process high-dimensional multi-agent observations while dynamically prioritizing context-specific features aligned with the learned EVEs.
Extensive experiments conducted in both urban and highway scenarios demonstrate that EGPO produces traffic environments with enhanced behavioral controllability and diversity. Furthermore, EGPO excels in the closed-loop AV testing on OnSite benchmark, outperforming SOTA methods based on deep learning and rule-based methods in terms of both realism and testing efficiency. Overall, EGPO offers a scalable and robust solution for simulating realistic interactions among diverse driving tendencies, facilitating the development of AV systems capable of handling complex real-world corner cases.

<div align="center"><strong>Closed-Loop Test with EGPO on OnSite benchmark</strong></div>

<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/ed216edf-0b2d-4ba4-962c-45c656c25c54" alt="Proposed" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 1: 1521cutin85.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/54beab72-a039-4bbf-9bd8-4f536678f537" alt="Baseline" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 2: 1455lanechanging46.</figcaption>
  </figure>
</div>

<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/b479b66b-e9d5-4c63-bf3e-37a27a98acbb" alt="Proposed" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 3: 0_36_straight_straight_39.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/0d0d404b-b727-4b45-8ed9-92c4da6c62d7" alt="Baseline" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 4: 13_117_straight_in_adjacent_left_119.</figcaption>
  </figure>
</div>

<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/351da1d2-7c72-4cec-9f27-f391196de487" alt="Proposed" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 5: _0_76_merge_82.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/56b319d7-cf67-4d9c-905b-f9c0bcceb742" alt="Baseline" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Scenario 6: 0_879_merge_895.</figcaption>
  </figure>
</div>
