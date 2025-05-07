---
title: "Toward Generalizable Traffic Simulation via Hybrid Knowledge Distillation in Diffusion Model"
collection: publications
permalink: /publication/HySD
date: 2025-05-01
venue: '(Submit) to the 28th IEEE International Conference on Intelligent Transportation Systems (ITSC 2025)'
---
<p style="font-size:small; line-height:1;">Yuhao Yang<sup style="font-size:smaller;">1,2</sup>, Jie Sun<sup style="font-size:smaller;">1,2</sup>, Jialin Fan<sup style="font-size:smaller;">1,2</sup>, and Jian Sun<sup style="font-size:smaller;">1,2</sup></p>
<p style="font-size:small; line-height:1;"><sup style="font-size:smaller;">1</sup> Department of Transportation Engineering, Tongji University, Shanghai, China</p>
<p style="font-size:small; line-height:1;"><sup style="font-size:smaller;">2</sup> Key Laboratory of Road and Traffic Engineering, Ministry of Education, Shanghai, China</p>

![image](https://github.com/user-attachments/assets/9a67b615-159c-452f-a56e-a44b9ebf8cdb)

Virtual simulation testing is crucial for validating the safety and reliability of autonomous driving systems, addressing the limitations of extensive real-world testing. Although data-driven methods, such as imitation learning and diffusion models, have advanced trajectory prediction and traffic simulation, their sensitivity to distribution shifts limits generalizability in realistic closed-loop traffic simulation across diverse datasets.
We propose a novel hybrid knowledge self-distillation framework based on diffusion model (HySD), integrating feature selfdistillation (FSD), response self-distillation (RSD), and relation self-distillation (RlSD) to enhance model robustness and generative diversity in multi-agent traffic simulation. The results show that our approach achieves superior performance on the Waymo open motion dataset in both trajectory generation and closedloop simulation tasks. The HySD method significantly reduces trajectory prediction errors (minADE: 0.977, minFDE: 2.791) and excels in closed-loop simulation for automated vehicle testing with more realistic and rule-compliant behaviors. Furthermore, the HySD model demonstrates exceptional zero-shot transferability in closed-loop simulation on the INTERACTION dataset, maintaining robust performance in diverse traffic scenarios.
These results highlight the potential of KD-optimized diffusion models to synthesize realistic traffic behaviors, offering a scalable solution for robust autonomous driving simulation across varying environments.
