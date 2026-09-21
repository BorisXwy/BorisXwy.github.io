---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
:root { --ink:#172033; --muted:#607087; --accent:#1967d2; --soft:#f5f8fc; }
.hero { padding: 2rem 2.2rem 1.8rem; border-radius: 18px; background: linear-gradient(135deg,#f3f7ff 0%,#f9fbff 55%,#eef7f5 100%); border:1px solid #e4ebf5; margin-bottom:2rem; }
.hero h1 { margin:0 0 .6rem; color:var(--ink); font-size:2.1rem; letter-spacing:-.02em; }
.hero .tagline { color:var(--accent); font-size:1.1rem; font-weight:600; margin:.2rem 0 1rem; }
.hero p { max-width: 760px; color:var(--muted); font-size:1.03rem; line-height:1.75; }
.pills { display:flex; flex-wrap:wrap; gap:.55rem; margin-top:1.2rem; }
.pill { background:#fff; color:#31506f; border:1px solid #dce6f2; padding:.34rem .7rem; border-radius:999px; font-size:.86rem; }
.section-kicker { color:var(--accent); text-transform:uppercase; letter-spacing:.12em; font-size:.75rem; font-weight:700; margin-bottom:.3rem; }
.pub-grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(285px,1fr)); gap:1rem; margin:1rem 0 2rem; }
.pub-card { padding:1.1rem 1.15rem; border:1px solid #e5eaf1; border-radius:12px; background:#fff; box-shadow:0 3px 12px rgba(40,60,90,.05); }
.pub-card h3 { font-size:1rem; line-height:1.4; margin:.2rem 0 .5rem; }
.pub-card p { color:var(--muted); font-size:.9rem; line-height:1.55; margin:.3rem 0; }
.pub-meta { color:var(--accent)!important; font-size:.8rem!important; font-weight:700; }
.pub-card a { color:var(--accent); font-weight:600; }
.timeline { border-left:2px solid #dce6f2; padding-left:1.2rem; margin:1rem 0 2rem; }
.timeline p { margin:.8rem 0; color:var(--muted); }
.timeline strong { color:var(--ink); }
.cta { background:var(--soft); border-radius:12px; padding:1rem 1.2rem; margin-top:1.8rem; }
@media (max-width:650px) { .hero { padding:1.3rem; } .hero h1 { font-size:1.65rem; } }
</style>

<div class="hero">
  <div class="section-kicker">Embodied intelligence · Robotics · Learning agents</div>
  <h1>Wenyuan Xie <span style="font-weight:400;color:#607087">谢文远</span></h1>
  <div class="tagline">Building agents that can perceive, reason, and act in the physical world.</div>
  <p>I am a third-year master's student at <a href="https://www.sjtu.edu.cn/">Shanghai Jiao Tong University</a>'s <strong>Paris Elite Institute of Engineering</strong>, preparing applications for 2027 Fall. My research studies vision-language-action models, embodied navigation, robot manipulation, and post-training methods that make intelligent agents more reliable.</p>
  <p>I completed both my bachelor's and master's studies at the Paris Elite Institute of Engineering, and I enjoy badminton, fitness, and thoughtful conversations about robots and learning.</p>
  <div class="pills"><span class="pill">VLA &amp; VLN</span><span class="pill">Robot manipulation</span><span class="pill">Reinforcement learning</span><span class="pill">3D perception</span><span class="pill">Agentic post-training</span></div>
</div>

<div class="section-kicker">Selected work</div>
<h2 id="publications">Publications &amp; projects</h2>
<p>My research connects structured geometric representations with learning-based agents, so they can adapt from experience and execute long-horizon tasks robustly.</p>
<div class="pub-grid">
  <article class="pub-card"><p class="pub-meta">RSS 2026 · First author</p><h3>MVP-Nav: Multi-layer Value Map Planner Navigator</h3><p>A multi-layer value-map planner that combines VGGT, Grounded-SAM and vision-language models for robust 3D navigation.</p><p><a href="https://arxiv.org/">Paper</a> · <a href="https://github.com/">Code</a></p></article>
  <article class="pub-card"><p class="pub-meta">ICRA 2027 · Under review · Co-first author</p><h3>Navi-Agent: Unlocalized Monocular Navigation Agent</h3><p>A coordinate-free visual anchor graph for place recognition, progress verification, and recovery in continuous environments.</p><p><a href="https://arxiv.org/abs/2609.20388">Paper</a></p></article>
  <article class="pub-card"><p class="pub-meta">ECCV 2026</p><h3>RelAfford6D: Relational 6D Affordance Graphs</h3><p>Language-grounded relational affordances become kinematic constraints and closed-loop SE(3) trajectories for articulated-object manipulation.</p><p><a href="https://arxiv.org/">Paper</a></p></article>
  <article class="pub-card"><p class="pub-meta">CVPR 2026</p><h3>Dejavu: Towards Experience Feedback Learning</h3><p>An experience feedback network augments a frozen VLA policy with retrieved trajectories, enabling post-deployment learning without rewriting the base model.</p><p><a href="https://arxiv.org/">Paper</a></p></article>
  <article class="pub-card"><p class="pub-meta">ICML 2026</p><h3>Recovering Hidden Reward in Diffusion-Based Policies</h3><p>Learning reward signals hidden inside diffusion-policy behavior to improve reliable action generation.</p><p><a href="https://arxiv.org/">Paper</a></p></article>
  <article class="pub-card"><p class="pub-meta">EMNLP 2026 · Co-author</p><h3>TRUST: Uncertainty-Aligned Tool-Calling Decisions</h3><p>Reinforcement learning with uncertainty-aware rewards for more reliable decisions in multi-turn agent tool use.</p><p><a href="https://arxiv.org/abs/2606.06976">Paper</a> · <a href="https://github.com/yjzscode/TRUST">Code</a></p></article>
</div>

<div class="section-kicker">Experience</div>
<h2 id="experience">Education &amp; experience</h2>
<div class="timeline">
  <p><strong>2024.09 - present</strong> - Master's student (third year), Paris Elite Institute of Engineering, Shanghai Jiao Tong University - preparing 2027 Fall applications</p>
  <p><strong>2020.09 - 2024.06</strong> - Bachelor's student, Paris Elite Institute of Engineering, Shanghai Jiao Tong University</p>
  <p><strong>Before 2020</strong> - Hangzhou Xuejun High School</p>
  <p><strong>2026.03 - 2026.07</strong> - Research intern, Shanghai Artificial Intelligence Laboratory - reinforcement learning and whole-body control for humanoid robots</p>
  <p><strong>2024.06 - 2024.09</strong> - Research intern, Alibaba - visual navigation with ViNT and NoMaD</p>
</div>

<div class="section-kicker">A few more things</div>
<h2 id="honors">Honors &amp; skills</h2>
<p>Outstanding Undergraduate Thesis (Top 1%) · Outstanding Student of SJTU · Chun-Tsung Scholar · Zhiyuan Honor Scholarship</p>
<p><strong>Tools:</strong> Python, PyTorch, JAX, C++, Java, MATLAB · <strong>Topics:</strong> VLA, VLN, agents, world models, reinforcement learning</p>
<div class="cta"><strong>Let's connect.</strong> I am open to research collaborations and robotics opportunities. Reach me at <a href="mailto:wenyuan.xie2002@gmail.com">wenyuan.xie2002@gmail.com</a> or <a href="/files/Wenyuan_Xie_CV.pdf">download my CV</a>.</div>


