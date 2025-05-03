---
title: "VRU-Centric Hazardous Scenario Detection via Monocular Spatiotemporal Feature Fusion"
collection: publications
permalink: /publication/VRUHI
date: 2025-05-01
venue: '(Submit) to the 28th IEEE International Conference on Intelligent Transportation Systems (ITSC 2025)'
---
<p style="font-size:small; line-height:1;">Ying Ni<sup style="font-size:smaller;">1,2</sup>, Siying Li<sup style="font-size:smaller;">1,2</sup>,  Jialin Fan<sup style="font-size:smaller;">1,2</sup><sup style="font-size:smaller;">1,2</sup></p>
<p style="font-size:small; line-height:1;"><sup style="font-size:smaller;">1</sup> Department of Transportation Engineering, Tongji University, Shanghai, China</p>
<p style="font-size:small; line-height:1;"><sup style="font-size:smaller;">2</sup> Key Laboratory of Road and Traffic Engineering, Ministry of Education, Shanghai, China</p>
![2](https://github.com/user-attachments/assets/65e6da6e-a02d-456b-b6f0-9c9ed586aba1)

The rapid deployment of autonomous vehicles necessitates robust hazard detection systems, yet existing methods struggle to detect subtle spatiotemporal cues in hazardous vehicle-vulnerable road user (VRU) interactions.
This paper addresses this critical gap through three key contributions. First, a multi-stream spatiotemporal network (VRU-HazardNet) is proposed to synergistically integrates 3D bounding box localization and optical flow dynamics via a transformer-based fusion architecture. The framework extracts geometric context from 3D object detection, encodes motion patterns through optical flow estimation, and employs temporal self-attention to model hazard precursors. Second, we introduce the VRU Hazardous Interaction (VRUHI) dataset—a benchmark tailored for vehicle-VRU interactive risk assessment, comprising 6,000 dashcam clips (2,000 hazardous, 4,000 safe) spanning diverse urban scenarios at 25 FPS. Third, extensive experiments demonstrate state-of-the-art performance. VRUHazardNet achieves 78.37% AUC and 41.03% F1-score on the VRUHI dataset, outperforming prior methods and validating its efficacy in capturing early hazardous signals. The dataset and model establish a foundation for safety-critical autonomous systems to detect VRU-related hazards proactively.
