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

<figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/ba12ec9d-1cad-4642-ba08-1f0ec49c1f02" alt="Proposed" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">EGPO Pipline.</figcaption>
</figure>

Optimizing multi-agent behaviors with Equilibrium Value Estimation (EVE) to strengthen autonomous vehicle testing. (a) We construct a closedloop, agent-based reinforcement learning framework in which smart test agents are trained by interacting with the environment, while their diverse interaction behaviors are meta-learned through the EVE mechanism to support AV testing. (b) By tuning the EVE parameter, EGPO can controllably generate multi-modal driving behaviors that expose AVs to a broad spectrum of realistic and safety-critical scenarios. (c) Compared with log-replay methods that reproduce diverse but non-interactive trajectories, and rule-based controllers that yield interactive yet overly compliant and homogeneous behaviors, EGPO jointly achieves both interactivity and behavioral diversity in zero-shot testing.

<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/9fcd383a-f7be-4ffa-a465-8182afec1dbc" alt="Case#1" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">vanilla methods.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/514bac10-ad3a-4304-8b55-076e6e5a1c6d" alt="Case#2" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">EGPO.</figcaption>
  </figure>
</div>

<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/8ee19dba-9a34-41a0-89f9-f9ac450d4dea" alt="Case#1" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Case#1.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/982c70d4-d6f1-43be-a3e6-b5ef7f44a29b" alt="Case#2" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Case#2.</figcaption>
  </figure>
</div>

<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/d3735bd5-1d52-4a58-ab26-a89c955b2241" alt="Case#3" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Case#3.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/1cf05f38-d8c2-4961-a83a-8bbcd0bfbe40" alt="Case#4" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Case#4.</figcaption>
  </figure>
</div>

Long-term cases with self-play EGPO smart agents
![shsj3](https://github.com/user-attachments/assets/f4c6ff98-0b49-4707-a33b-633b4b52ea8b)

<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/8e3dfba4-b32f-4679-a89b-d2ec4577b17" alt="Case#5" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Case#5.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/513adbcd-4dd2-47f9-8529-9316e711788b" alt="Case#6" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Case#6.</figcaption>
  </figure>
</div>
