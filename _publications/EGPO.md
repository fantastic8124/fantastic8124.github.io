---
title: "Optimizing Multi-agent Behavior for Interactive Autonomous Driving with Equilibrium Value Estimation"
collection: publications
permalink: /publication/EGPO
date: 2026-01-21
venue: '(Under Review) IEEE Transactions on Intelligent Transportation Systems'
---

<link href="https://fonts.googleapis.com/css?family=Google+Sans|Noto+Sans|Castoro" rel="stylesheet">

<style>
  /* 全局容器约束 */
  .page-content {
    max-width: 1000px !important; /* 让页面更宽，适合展示大图 */
    margin: 0 auto;
    font-family: 'Google Sans', sans-serif;
  }
  
  /* 标题与作者样式 */
  h1.title {
    font-size: 2.5rem;
    line-height: 1.2;
    text-align: center;
    font-weight: 700;
    margin-bottom: 20px;
  }
  .author-block {
    text-align: center;
    font-size: 1.15rem;
    margin-bottom: 5px;
  }
  .author-link {
    color: #4285f4; /* 谷歌蓝/浅蓝色 */
    text-decoration: none; /* 默认无下划线 */
    font-weight: 500;
    transition: color 0.3s;
  }
  .author-link:hover {
    color: #1a0dab; /* 悬停时稍微变深 */
    text-decoration: underline;
  }
  .affiliation-block {
    text-align: center;
    font-size: 0.95rem;
    color: #555;
    margin-bottom: 20px;
  }
  
  /* 按钮组样式 */
  .link-block-container {
    display: flex;
    justify-content: center;
    gap: 15px;
    margin-bottom: 30px;
    flex-wrap: wrap;
  }
  .external-link-button {
    background-color: #363636;
    color: #ffffff !important;
    border-radius: 30px;
    padding: 10px 20px;
    text-decoration: none !important;
    font-weight: 500;
    font-size: 1rem;
    display: inline-flex;
    align-items: center;
    transition: background-color 0.3s;
  }
  .external-link-button:hover {
    background-color: #555;
  }
  .icon {
    margin-right: 8px;
    width: 16px;
    height: 16px;
    fill: currentColor;
  }

  /* 摘要样式 */
  .abstract-container {
    background-color: #f5f5f5; /* 淡淡的灰色背景，突出摘要 */
    padding: 30px;
    border-radius: 10px;
    margin-bottom: 40px;
    text-align: justify;
  }
  
  /* 图片通用样式 */
  img.teaser-img {
    width: 100%;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    margin-bottom: 10px;
  }
  
  /* 章节标题 */
  h2.section-title {
    text-align: center;
    font-size: 2rem;
    margin-top: 50px;
    margin-bottom: 30px;
    border-bottom: none; /* 去掉默认的下划线 */
  }

  /* Grid 布局用于对比图 */
  .results-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    margin-bottom: 30px;
  }
  .grid-item {
    text-align: center;
    background: white;
    padding: 10px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
  }
  .grid-caption {
    margin-top: 8px;
    font-weight: 600;
    color: #444;
  }
</style>

<div class="page-content">

  <div class="author-block">
    <span>Jialin Fan<sup>1,2</sup></span>, 
    <span>Ying Ni<sup>1,2</sup></span>, 
    <span>Yujia Zhao<sup>1,2</sup></span>, 
    <span>Jie Sun<sup>1,2</sup></span>, 
    <span>Jian Sun<sup>1,2</sup></span>
  </div>

  <div class="affiliation-block">
    <sup>1</sup> College of Transportation, Tongji University, Shanghai, China<br>
    <sup>2</sup> Key Laboratory of Road and Traffic Engineering, Ministry of Education, Shanghai, China
  </div>

  <div class="link-block-container">
    <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5367491" class="external-link-button">
      <svg class="icon" viewBox="0 0 24 24"><path d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm2 9h-4v-1h4v1zm0-3v1h-4v-1h4zm-2 13l-6-6h4v-3h4v3h4l-6 6z"/></svg>
      Paper
    </a>
    <a href="#" class="external-link-button">
      <svg class="icon" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg>
      Code(Coming Soon)
    </a>
    <a href="https://www.onsite.com.cn/#/dist/home" class="external-link-button">
      <svg class="icon" viewBox="0 0 24 24"><path d="M19.615 3.184c-3.604-.246-11.631-.245-15.23 0-3.897.266-4.356 2.62-4.385 8.816.029 6.185.484 8.549 4.385 8.816 3.6.245 11.626.246 15.23 0 3.897-.266 4.356-2.62 4.385-8.816-.029-6.185-.484-8.549-4.385-8.816zm-10.615 12.816v-8l8 3.993-8 4.007z"/></svg>
      OnSite
    </a>
  </div>

  <div style="text-align: center; margin-bottom: 40px;">
    <img src="https://github.com/user-attachments/assets/ba12ec9d-1cad-4642-ba08-1f0ec49c1f02" class="teaser-img" alt="EGPO Pipeline">
    <div style="color: #4a4a4a; font-size: 0.9em; margin-top: 10px;">
      <strong>Figure 1. The EGPO Pipeline.</strong> Our framework enables controllable generation of multi-modal driving behaviors through Equilibrium Value Estimation.
    </div>
  </div>

  <div class="abstract-container">
    <h2 style="text-align: center; margin-top: 0; font-size: 1.5rem;">Abstract</h2>
    <p>
      Optimizing multi-agent behaviors with <strong>Equilibrium Value Estimation (EVE)</strong> to strengthen autonomous vehicle testing. We construct a closed-loop, agent-based reinforcement learning framework in which smart test agents are trained by interacting with the environment, while their diverse interaction behaviors are meta-learned through the EVE mechanism to support AV testing. 
    </p>
    <p>
      By tuning the EVE parameter, EGPO can controllably generate multi-modal driving behaviors that expose AVs to a broad spectrum of realistic and safety-critical scenarios. Compared with log-replay methods that reproduce diverse but non-interactive trajectories, and rule-based controllers that yield interactive yet overly compliant and homogeneous behaviors, EGPO jointly achieves both interactivity and behavioral diversity in zero-shot testing.
    </p>
  </div>

  <h2 class="section-title">Qualitative Results</h2>
  
  <p style="text-align: center; font-size: 1.1em; margin-bottom: 30px; color: #555;">
    EGPO demonstrates superior interactivity and diversity compared to baselines.
  </p>

  <h3 style="text-align: center; margin-bottom: 20px;">Comparison with Baselines</h3>
  <div class="results-grid">
    <div class="grid-item">
      <img src="https://github.com/user-attachments/assets/9fcd383a-f7be-4ffa-a465-8182afec1dbc" style="width: 100%; border-radius: 5px;">
      <div class="grid-caption">Vanilla Methods</div>
    </div>
    <div class="grid-item">
      <img src="https://github.com/user-attachments/assets/514bac10-ad3a-4304-8b55-076e6e5a1c6d" style="width: 100%; border-radius: 5px;">
      <div class="grid-caption">EGPO (Ours)</div>
    </div>
  </div>

  <h3 style="text-align: center; margin-top: 50px; margin-bottom: 20px;">Diverse Interaction Scenarios</h3>
  <div class="results-grid">
    <div class="grid-item">
      <img src="https://github.com/user-attachments/assets/8ee19dba-9a34-41a0-89f9-f9ac450d4dea" style="width: 100%; border-radius: 5px;">
      <div class="grid-caption">Case #1</div>
    </div>
    <div class="grid-item">
      <img src="https://github.com/user-attachments/assets/982c70d4-d6f1-43be-a3e6-b5ef7f44a29b" style="width: 100%; border-radius: 5px;">
      <div class="grid-caption">Case #2</div>
    </div>
    <div class="grid-item">
      <img src="https://github.com/user-attachments/assets/d3735bd5-1d52-4a58-ab26-a89c955b2241" style="width: 100%; border-radius: 5px;">
      <div class="grid-caption">Case #3</div>
    </div>
    <div class="grid-item">
      <img src="https://github.com/user-attachments/assets/1cf05f38-d8c2-4961-a83a-8bbcd0bfbe40" style="width: 100%; border-radius: 5px;">
      <div class="grid-caption">Case #4</div>
    </div>
  </div>

  <h3 style="text-align: center; margin-top: 50px; margin-bottom: 20px;">Scalling Self-play</h3>
  <div class="results-grid">
    <div class="grid-item">
      <img src="https://github.com/user-attachments/assets/f4c6ff98-0b49-4707-a33b-633b4b52ea8b" style="width: 100%; border-radius: 5px;">
      <div class="grid-caption">Case #5： Urban road interchange</div>
    </div>
    <div class="grid-item">
      <img src="https://github.com/user-attachments/assets/513adbcd-4dd2-47f9-8529-9316e711788b" style="width: 100%; border-radius: 5px;">
      <div class="grid-caption">Case #6: Urban expressway</div>
    </div>
  </div>

  <h2 class="section-title">Citation</h2>
  <div style="background: #f5f5f5; padding: 20px; border-radius: 10px; overflow-x: auto;">
<pre style="margin: 0; font-size: 0.85em;"><code>@article{fan2026optimizing,
  title={Optimizing Multi-agent Behavior for Interactive Autonomous Driving with Equilibrium Value Estimation},
  author={Fan, Jialin and Ni, Ying and Zhao, Yujia and Sun, Jie and Sun, Jian},
  journal={IEEE Transactions on Intelligent Transportation Systems},
  year={2026}
}</code></pre>
  </div>

</div>
