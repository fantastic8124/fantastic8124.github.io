---
title: "Towards Proactive-Aware Autonomous Driving:
A Reinforcement Learning Approach Utilizing Expert Priors during Unprotected Turns
"
collection: publications
permalink: /publication/TPAAD
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-02-09
---
<p style="font-size:small; line-height:1;">Jialin Fan<sup style="font-size:smaller;">1,2</sup>, Ying Ni<sup style="font-size:smaller;">1,2</sup>, Donghu Zhao<sup style="font-size:smaller;">1,2</sup>, and Peng Hang<sup style="font-size:smaller;">1,2</sup></p>
<p style="font-size:small; line-height:1;"><sup style="font-size:smaller;">1</sup> Department of Transportation Engineering, Tongji University, Shanghai, China</p>
<p style="font-size:small; line-height:1;"><sup style="font-size:smaller;">2</sup> Key Laboratory of Road and Traffic Engineering, Ministry of Education, Shanghai, China</p>
![image](https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/6c3eb436-11e2-4ad9-921e-1abd945bd316)
Existing AVs struggle to comprehend and apply common HV social norms, especially the driving skills exhibited by adept human drivers in ambiguous right-of-way scenarios. In this study, we put forth a novel framework to leverage expert priors for proactive-aware decision-making in ambiguous right-of-way, merging data-driven reinforcement learning (RL) with parameterized modeling. The proposed method is intensively validated in different driving tasks with unprotected turning scenarios, the results demonstrate that the AV can accelerate the convergence of the interaction by consistent probing and decision updates. We present demos in the following sections.

 <div align="center"><strong>Interactive Performance in Unprotected-turning tasks</strong></div>
 ![image](https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/bdc207b3-1190-4fc0-a540-ce81c16d75c2)
We performed a qualitative and quantitative examination of the agent’s probing process in the context of a typical unprotected left-turn interaction. The initial state of the two vehicles was based on the ambiguous right-of-way scenario obtained in Section II.B.
<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/d1320d37-74e9-423c-928d-0337ba16a333" alt="Proposed" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Interactive Performance of The Proposed Strategy</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/941d594d-09ca-4f6d-8fb6-52092f9c816e" alt="Baseline" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Interactive Performance of The Baseline Strategy (PPO)</figcaption>
  </figure>
</div>

 <div align="center"><strong>Interaction with HVs of Different Driving Styles</strong></div>
![image](https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/96be819b-d6a9-4a8a-acb2-4e2f840c1606)
It's worth noting that when faced with aggressive HVs, AV demonstrates a lower likelihood of choosing to probe and gaining right-of-way advantages. When facing relatively conservative interaction objects, AV has a higher probability of completing the turn ahead of time.
<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/84387826-7239-4316-a4a3-0ab303aebe3e" alt="Aggressive HVs" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Interaction with Aggressive HVs</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/c94d97f0-8497-4dcf-8d7a-a181e06e673f" alt="Conservative HVs" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Interaction with Conservative HVs</figcaption>
  </figure>
</div>

 <div align="center"><strong>Interaction in Facing Different Ambiguities of Right-of-way</strong></div>
 ![image](https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/bdc207b3-1190-4fc0-a540-ce81c16d75c2)
  In facing different ambiguities of right-of-way, AV with the proposed method can take distinct actions, highlighting the importance of autonomous generation of this active driving behavior instead of reliance on manually coded policies. 
<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/e8731323-7f9c-49de-9afb-034fc8b63391" alt="Ambiguous Right-of-way" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Interaction in Ambiguous Right-of-way.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/e32e9280-43fb-49f3-9cd3-0dbde4ff9194" alt="Clear Right-of-way" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Interaction in Clear Right-of-way.</figcaption>
  </figure>
</div>

 <div align="center"><strong>Interaction Performance in Generalization Scenarios (inD dataset)</strong></div>
 ![image](https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/bdc207b3-1190-4fc0-a540-ce81c16d75c2)
  Our method exhibits robust stability across diverse scenarios, showcasing the application of our method in varied and challenging environments. 
<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/3064398b-79ab-48bf-9fc6-b6be5cb116d1" alt="inD #2" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;"> Interaction Performance in Generalization Scenarios: Scene #2 in inD dataset.</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/32556a44-7d5b-4685-98b2-0f2968bb9a60" alt="inD #4" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Interaction Performance in Generalization Scenarios: Scene #4 in inD dataset.</figcaption>
  </figure>
</div>

 <div align="center"><strong>human-in-loop experiments</strong></div>
 ![image](https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/bdc207b3-1190-4fc0-a540-ce81c16d75c2)
  With our strategy, AV can interact reasonably with human-driven through vehicles, demonstrating proper safety and anthropomorphism. 
<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/d0e3c2e2-5e76-48ee-bc48-900a07d4c199" alt="HIL test" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;"> The AV controlled by the proposed strategy from the view of human-driver (obtains the right of way).</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/user-attachments/assets/9863cf65-d376-4bfb-bf12-f53c91cc8899" alt="HIL test" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;"> The AV controlled by the proposed strategy from the view of human-driver (lost the right of way).</figcaption>
  </figure>
</div>

