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
<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <figure style="margin: 0 10px;">
    <img src="https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/c94d97f0-8497-4dcf-8d7a-a181e06e673f" alt="图片1描述" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Interactive Performance of The Proposed Strategy</figcaption>
  </figure>
  <figure style="margin: 0 10px;">
    <img src="https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/a9fac432-eac1-4ed1-8b91-2fccc6ec6b8c" alt="图片2描述" style="width: 95%; margin-bottom: 0;" />
    <figcaption style="text-align: center; margin-top: 5px;">Interactive Performance of The Baseline Strategy (PPO)</figcaption>
  </figure>
</div>
![4](https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/c94d97f0-8497-4dcf-8d7a-a181e06e673f)

 <div align="center"><strong>Interaction with HVs of Different Driving Styles</strong></div>
![image](https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/96be819b-d6a9-4a8a-acb2-4e2f840c1606)
It's worth noting that when faced with aggressive HVs, AV demonstrates a lower likelihood of choosing to probe and gaining right-of-way advantages. When facing relatively conservative interaction objects, AV has a higher probability of completing the turn ahead of time.
<div style="display: flex; align-items: flex-start;">
  <figure>
    <img src="https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/6b0f1c08-dd3e-460c-8f9d-448d42f13b4d" alt="图片1描述" style="width: 95%;" margin-bottom: 0;/>
    <figcaption style="text-align: center;">Interaction with Aggressive HVs</figcaption>
  </figure>
  <figure>
    <img src="https://github.com/fantastic8124/fantastic8124.github.io/assets/63543931/84dde73c-781f-493a-a28e-62c47b9ff692" alt="图片2描述" style="width: 95%;" margin-bottom: 0;/>
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
