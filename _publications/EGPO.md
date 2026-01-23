---
title: "Optimizing Multi-agent Behavior for Interactive Autonomous Driving with Equilibrium Value Estimation"
collection: publications
permalink: /publication/EGPO
date: 2026-01-21
venue: '(Under Review) IEEE Transactions on Intelligent Transportation Systems'
---

<div style="text-align: center; margin-bottom: 20px;">
    <div style="font-size: 1.2em; font-weight: bold; margin-bottom: 8px;">
        Jialin Fan<sup>1,2</sup>, Ying Ni<sup>1,2</sup>, Yujia Zhao<sup>1,2</sup>, Jie Sun<sup>1,2</sup>, and Jian Sun<sup>1,2</sup>
    </div>
    <div style="font-size: 0.9em; color: #555; line-height: 1.4;">
        <sup>1</sup> College of Transportation, Tongji University, Shanghai, China<br>
        <sup>2</sup> Key Laboratory of Road and Traffic Engineering, Ministry of Education, Shanghai, China
    </div>
    
    <div style="margin-top: 15px;">
        <a href="#" style="display: inline-block; padding: 5px 10px; margin: 0 5px; border: 1px solid #333; border-radius: 4px; text-decoration: none; color: #333; font-size: 0.9em;">📄 Paper (PDF)</a>
        <a href="#" style="display: inline-block; padding: 5px 10px; margin: 0 5px; border: 1px solid #333; border-radius: 4px; text-decoration: none; color: #333; font-size: 0.9em;">💻 Code (GitHub, coming soon)</a>
        <a href="#" style="display: inline-block; padding: 5px 10px; margin: 0 5px; border: 1px solid #333; border-radius: 4px; text-decoration: none; color: #333; font-size: 0.9em;">🎥 Video</a>
    </div>
</div>

<hr>

<h2 style="text-align: center;">Abstract</h2>
<div style="text-align: justify; margin-bottom: 30px;">
    Optimizing multi-agent behaviors with <strong>Equilibrium Value Estimation (EVE)</strong> to strengthen autonomous vehicle testing.
    <br><br>
    (a) We construct a closed-loop, agent-based reinforcement learning framework in which smart test agents are trained by interacting with the environment, while their diverse interaction behaviors are meta-learned through the EVE mechanism to support AV testing. 
    (b) By tuning the EVE parameter, EGPO can controllably generate multi-modal driving behaviors that expose AVs to a broad spectrum of realistic and safety-critical scenarios. 
    (c) Compared with log-replay methods that reproduce diverse but non-interactive trajectories, and rule-based controllers that yield interactive yet overly compliant and homogeneous behaviors, EGPO jointly achieves both interactivity and behavioral diversity in zero-shot testing.
</div>

<div style="text-align: center; margin-bottom: 40px;">
    <img src="https://github.com/user-attachments/assets/ba12ec9d-1cad-4642-ba08-1f0ec49c1f02" alt="EGPO Framework" style="width: 100%; max-width: 800px; box-shadow: 0 4px 8px 0 rgba(0,0,0,0.1); border-radius: 5px;" />
    <div style="margin-top: 10px; font-style: italic; color: #666; font-size: 0.9em;">
        <strong>Figure 1. The EGPO Pipeline.</strong> Our framework enables controllable generation of multi-modal driving behaviors.
    </div>
</div>

<hr>

<h2 style="text-align: center;">Qualitative Results</h2>

<h3 style="text-align: center; font-size: 1.1em; margin-top: 20px;">1. Comparison: Vanilla vs. EGPO</h3>
<p style="text-align: center; font-size: 0.9em; color: #666; margin-bottom: 10px;">EGPO demonstrates more aggressive and interactive behaviors compared to vanilla methods.</p>

<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin-bottom: 30px;">
    <div style="flex: 1; min-width: 300px; text-align: center;">
        <img src="https://github.com/user-attachments/assets/9fcd383a-f7be-4ffa-a465-8182afec1dbc" style="width: 100%; border-radius: 4px;" alt="Vanilla">
        <div style="margin-top: 5px;">Vanilla Methods</div>
    </div>
    <div style="flex: 1; min-width: 300px; text-align: center;">
        <img src="https://github.com/user-attachments/assets/514bac10-ad3a-4304-8b55-076e6e5a1c6d" style="width: 100%; border-radius: 4px;" alt="EGPO">
        <div style="margin-top: 5px;"><strong>EGPO (Ours)</strong></div>
    </div>
</div>

<h3 style="text-align: center; font-size: 1.1em; margin-top: 20px;">2. Diverse Scenarios Generation</h3>
<p style="text-align: center; font-size: 0.9em; color: #666; margin-bottom: 10px;">Demonstrating capability in various safety-critical scenarios.</p>

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px; margin-bottom: 30px;">
    <div style="text-align: center;">
        <img src="https://github.com/user-attachments/assets/8ee19dba-9a34-41a0-89f9-f9ac450d4dea" style="width: 100%; border-radius: 4px;">
        <div style="font-size: 0.85em; margin-top: 4px;">Case #1</div>
    </div>
    <div style="text-align: center;">
        <img src="https://github.com/user-attachments/assets/982c70d4-d6f1-43be-a3e6-b5ef7f44a29b" style="width: 100%; border-radius: 4px;">
        <div style="font-size: 0.85em; margin-top: 4px;">Case #2</div>
    </div>
    <div style="text-align: center;">
        <img src="https://github.com/user-attachments/assets/d3735bd5-1d52-4a58-ab26-a89c955b2241" style="width: 100%; border-radius: 4px;">
        <div style="font-size: 0.85em; margin-top: 4px;">Case #3</div>
    </div>
    <div style="text-align: center;">
        <img src="https://github.com/user-attachments/assets/1cf05f38-d8c2-4961-a83a-8bbcd0bfbe40" style="width: 100%; border-radius: 4px;">
        <div style="font-size: 0.85em; margin-top: 4px;">Case #4</div>
    </div>
</div>

<h3 style="text-align: center; font-size: 1.1em; margin-top: 20px;">3. Long-term Self-play</h3>
<p style="text-align: center; font-size: 0.9em; color: #666; margin-bottom: 10px;">Robustness testing in continuous long-term simulation.</p>

<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin-bottom: 20px;">
    <div style="flex: 1; min-width: 300px; text-align: center;">
        <img src="https://github.com/user-attachments/assets/f4c6ff98-0b49-4707-a33b-633b4b52ea8b" style="width: 100%; border-radius: 4px;">
        <div style="margin-top: 5px;">Case #5</div>
    </div>
    <div style="flex: 1; min-width: 300px; text-align: center;">
        <img src="https://github.com/user-attachments/assets/513adbcd-4dd2-47f9-8529-9316e711788b" style="width: 100%; border-radius: 4px;">
        <div style="margin-top: 5px;">Case #6</div>
    </div>
</div>

<hr>

<h3 style="margin-top: 30px;">Citation</h3>
If you find this work useful for your research, please cite:
```bibtex
@article{fan2026optimizing,
  title={Optimizing Multi-agent Behavior for Interactive Autonomous Driving with Equilibrium Value Estimation},
  author={Fan, Jialin and Ni, Ying and Zhao, Yujia and Sun, Jie and Sun, Jian},
  journal={IEEE Transactions on Intelligent Transportation Systems},
  year={2026}
}
