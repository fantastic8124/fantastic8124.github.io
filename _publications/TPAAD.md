---
title: "Towards Proactive-Aware Autonomous Driving:
A Reinforcement Learning Approach Utilizing Expert Priors during Unprotected Turns
"
collection: publications
permalink: /publication/TPAAD
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-02-09
venue: 'Journal 1'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Jialin Fan1,2, Ying Ni1,2, Donghu Zhao1,2, and Peng Hang1,2
1 Department of Transportation Engineering, Tongji University, Shanghai, China
2 Key Laboratory of Road and Traffic Engineering, Ministry of Education, Shanghai, China

![image](https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/6c3eb436-11e2-4ad9-921e-1abd945bd316)
Existing AVs struggle to comprehend and apply common HV social norms, especially the driving skills exhibited by adept human drivers in ambiguous right-of-way scenarios. In this study, we put forth a novel framework to leverage expert priors for proactive-aware decision-making in ambiguous right-of-way, merging data-driven reinforcement learning (RL) with parameterized modeling. The proposed method is intensively validated in different driving tasks with unprotected turning scenarios, the results demonstrate that the AV can accelerate the convergence of the interaction by consistent probing and decision updates. We present demos in the following sections.

 <div align="center"><strong>Interactive Performance in Unprotected-turning tasks</strong></div>
 ![image](https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/bdc207b3-1190-4fc0-a540-ce81c16d75c2)
We performed a qualitative and quantitative examination of the agent’s probing process in the context of a typical unprotected left-turn interaction. The initial state of the two vehicles was based on the ambiguous right-of-way scenario obtained in Section II.B.
<div style="display: flex; align-items: flex-start;">
  <figure>
    <img src="https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/2ce3fd6e-b07a-4b0c-8356-b6c44558d8df" alt="图片1描述" style="width: 95%;" margin-bottom: 0;/>
    <figcaption style="text-align: center;">Interactive Performance of The Proposed Strategy</figcaption>
  </figure>
  <figure>
    <img src="https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/80a908fa-e08a-4b0b-b85e-2a96c29544da" alt="图片2描述" style="width: 95%;" margin-bottom: 0;/>
    <figcaption style="text-align: center;">Interactive Performance of The Baseline Strategy (PPO)</figcaption>
  </figure>
</div>
![1](https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/63690999-9708-4239-885f-5205add9fda9)

 <div align="center"><strong>Interaction with HVs of Different Driving Styles</strong></div>
![image](https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/96be819b-d6a9-4a8a-acb2-4e2f840c1606)
It's worth noting that when faced with aggressive HVs, AV demonstrates a lower likelihood of choosing to probe and gaining right-of-way advantages. When facing relatively conservative interaction objects, AV has a higher probability of completing the turn ahead of time.
<div style="display: flex; align-items: flex-start;">
  <figure>
    <img src="https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/39b0a499-4a56-4c22-83b4-9b9bc07a2cc5" alt="图片1描述" style="width: 95%;" margin-bottom: 0;/>
    <figcaption style="text-align: center;">Interaction with Aggressive HVs</figcaption>
  </figure>
  <figure>
    <img src="https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/74a2e65a-d6cd-47d8-9402-e0e910e335e1" alt="图片2描述" style="width: 95%;" margin-bottom: 0;/>
    <figcaption style="text-align: center;">Interaction with Conservative HVs</figcaption>
  </figure>
</div>

 <div align="center"><strong>Interaction in Facing Different Ambiguities of Right-of-way</strong></div>
 ![image](https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/bdc207b3-1190-4fc0-a540-ce81c16d75c2)
  In facing different ambiguities of right-of-way, AV with the proposed method can take distinct actions, highlighting the importance of autonomous generation of this active driving behavior instead of reliance on manually coded policies. 
<div style="display: flex; align-items: flex-start;">
  <figure>
    <img src="https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/1ac839b1-b3d7-490b-ad5c-322dc76d2778" alt="图片1描述" style="width: 95%;" margin-bottom: 0;/>
    <figcaption style="text-align: center;">Interaction in Ambiguous Right-of-way.</figcaption>
  </figure>
  <figure>
    <img src="https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/763476e4-c004-4d2d-b9b5-67458e31db0d" alt="图片2描述" style="width: 95%;" margin-bottom: 0;/>
    <figcaption style="text-align: center;">Interaction in Clear Right-of-way.</figcaption>
  </figure>
</div>
[Download paper here](http://academicpages.github.io/files/paper1.pdf)
