---
title: "Transferring Causal Driving Patterns for Generalizable Traffic Simulation with Diffusion-Based Distillation"
collection: publications
permalink: /publication/CDPT
date: 2025-07-26
venue: 'AAAI 2026'
---
<p style="font-size:small; line-height:1;"> Yuhang Chen<sup style="font-size:smaller;">1,2</sup>, Jie Sun<sup style="font-size:smaller;">1,2</sup>, Jialin Fan<sup style="font-size:smaller;">1,2</sup>, and Jian Sun<sup style="font-size:smaller;">1,2</sup></p>
<p style="font-size:small; line-height:1;"><sup style="font-size:smaller;">1</sup> College of Transportation, Tongji University, Shanghai, China</p>
<p style="font-size:small; line-height:1;"><sup style="font-size:smaller;">2</sup> Key Laboratory of Road and Traffic Engineering, Ministry of Education, Shanghai, China</p>

Traffic simulation is essential for validating the safety and reliability of autonomous driving systems, yet data-driven simulation methods often struggle with distribution shifts, limiting their generalizability across diverse datasets (domains). To address this, we present Causal Driving Pattern Transfer (CDPT), a novel two-stage knowledge distillation framework built upon diffusion model to enhance cross-domain generalizability. In Phase I, we implement hybrid self-distillation within the source domain by integrating feature-, response-, and contrastive-level distillation, which enables the model to decompose complex driving behaviors into their core causal components, including scene-conditioned driven patterns, multi-agent interaction dynamics and casual saliency. In Phase II, we introduce a continual distillation strategy: few-shot samples from the target domain are used to initiate generation of diverse synthetic scenarios, allowing the student model to continually adapt to novel environments without retraining on large-scale data. Extensive experiments demonstrates that CDPT achieves strong generalization in both open-loop and closed-loop simulations, effectively generating realistic, interaction-aware behaviors that are critical for scalable and reliable autonomous driving testing.
