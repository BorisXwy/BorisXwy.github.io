---
permalink: /
title: ""
excerpt: ""
author_profile: true
---



<style>
:root { --ink:#172033; --muted:#607087; --accent:#1967d2; --soft:#f5f8fc; }
.lang-switch { text-align:right; margin:0 0 1rem; font-size:.9rem; }
.lang-switch button { border:0; background:transparent; color:var(--accent); font-weight:600; padding:0; cursor:pointer; font:inherit; }
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
<div class="lang-switch" role="navigation" aria-label="Language"><button type="button" onclick="setLang('en', event)" aria-label="English">EN</button><span>|</span><button type="button" onclick="setLang('zh', event)" aria-label="Chinese">&#20013;&#25991;</button></div>
<script>
function setLang(lang, event) {
  if (event) { event.preventDefault(); event.stopPropagation(); }
  document.getElementById('lang-en').hidden = lang !== 'en';
  document.getElementById('lang-zh').hidden = lang !== 'zh';
  document.documentElement.lang = lang === 'zh' ? 'zh' : 'en';
  try { localStorage.setItem('homepage-lang', lang); } catch (e) {}
}
(function () {
  var lang = 'en';
  try { lang = localStorage.getItem('homepage-lang') || 'en'; } catch (e) {}
  setLang(lang === 'zh' ? 'zh' : 'en');
})();
</script>

<div id="lang-en" class="lang-panel"><div class="hero">
  <div class="section-kicker">Embodied intelligence · Robotics · Learning agents</div>
  <h1>Wenyuan Xie <span style="font-weight:400;color:#607087">谢文远</span></h1>
  <div class="tagline">Building agents that can perceive, reason, and act in the physical world.</div>
  <p>I am a third-year master's student at <a href="https://www.sjtu.edu.cn/">Shanghai Jiao Tong University</a>'s <strong>Paris Elite Institute of Engineering</strong>, preparing applications for 2027 Fall. My research studies vision-language-action models, embodied navigation, robot manipulation, and post-training methods that make intelligent agents more reliable.</p>
  <p>I completed both my bachelor's and master's studies at the Paris Elite Institute of Engineering, and I enjoy fitness and thoughtful conversations about robots and learning.</p>
  <div class="pills"><span class="pill">Embodied Policies and Agent Systems</span><span class="pill">World Models and Vision Foundation Models</span><span class="pill">Reinforcement Learning Algorithms and Systems</span></div>
</div>

<div class="section-kicker">Selected work</div>
<h2 id="publications">Publications &amp; projects</h2>
<p>My research connects structured geometric representations with learning-based agents, so they can adapt from experience and execute long-horizon tasks robustly.</p>
<div class="pub-grid">
  <article class="pub-card"><p class="pub-meta">RSS 2026 · First author</p><h3>MVP-Nav: Multi-layer Value Map Planner Navigator</h3><p>A multi-layer value-map planner that combines VGGT, Grounded-SAM and vision-language models for robust 3D navigation.</p><p><a href="https://arxiv.org/abs/2606.31919">Paper</a></p></article>
  <article class="pub-card"><p class="pub-meta">Under review · First author</p><h3>Navi-Agent: Unlocalized Monocular Navigation Agent</h3><p>A coordinate-free visual anchor graph for place recognition, progress verification, and recovery in continuous environments.</p><p><a href="https://arxiv.org/abs/2609.20388">Paper</a></p></article>
  <article class="pub-card"><p class="pub-meta">ECCV 2026</p><h3>RelAfford6D: Relational 6D Affordance Graphs</h3><p>Language-grounded relational affordances become kinematic constraints and closed-loop SE(3) trajectories for articulated-object manipulation.</p><p><a href="https://arxiv.org/abs/2606.27036">Paper</a></p></article>
  <article class="pub-card"><p class="pub-meta">CVPR 2026</p><h3>Dejavu: Towards Experience Feedback Learning</h3><p>An experience feedback network augments a frozen VLA policy with retrieved trajectories, enabling post-deployment learning without rewriting the base model.</p><p><a href="https://arxiv.org/abs/2510.10181">Paper</a> | <a href="https://dejavu2025.github.io/">Project</a></p></article>
  <article class="pub-card"><p class="pub-meta">ICML 2026</p><h3>Recovering Hidden Reward in Diffusion-Based Policies</h3><p>Learning reward signals hidden inside diffusion-policy behavior to improve reliable action generation.</p><p><a href="https://arxiv.org/abs/2605.00623">Paper</a></p></article>
  <article class="pub-card"><p class="pub-meta">EMNLP 2026 · Co-author</p><h3>TRUST: Uncertainty-Aligned Tool-Calling Decisions</h3><p>Reinforcement learning with uncertainty-aware rewards for more reliable decisions in multi-turn agent tool use.</p><p><a href="https://arxiv.org/abs/2606.06976">Paper</a> · <a href="https://github.com/yjzscode/TRUST">Code</a></p></article>
</div>

<div class="section-kicker">Education</div>
<h2 id="education">Education</h2>
<div class="timeline">
  <p><strong>2024.09 - present</strong> - Master's student (third year), Paris Elite Institute of Engineering, Shanghai Jiao Tong University - preparing 2027 Fall applications</p>
  <p><strong>2020.09 - 2024.06</strong> - Bachelor's student, Paris Elite Institute of Engineering, Shanghai Jiao Tong University</p>
  <p><strong>Before 2020</strong> - Hangzhou Xuejun High School</p>
</div>

<div class="section-kicker">Internships</div>
<h2 id="internships">Internships</h2>
<div class="timeline">
  <p><strong>2026.03 - 2026.07</strong> - Research intern, Agibot Robotics - reinforcement learning post-training for long-horizon phone packaging and whole-body control for wheeled-legged robots</p>
  <p><strong>2024.06 - 2024.09</strong> - Research intern, Alibaba - product carbon-footprint certification for the Hangzhou Asian Games mascot plush toy, the Games’ first zero-carbon licensed product; used life-cycle assessment and Alibaba Cloud Energy Expert for carbon accounting, offsetting and digital certification, and also supported the China Academy of Art low-carbon platform</p>
</div>

<div class="section-kicker">A few more things</div>
<h2 id="skills">Skills</h2>
<p><strong>Tools:</strong> Python, PyTorch, JAX, C++, Java, MATLAB · <strong>Topics:</strong> VLA, VLN, agents, world models, reinforcement learning</p>
<div class="cta"><strong>Let's connect.</strong> I am open to research collaborations and robotics opportunities. Reach me at <a href="mailto:wenyuan.xie2002@gmail.com">wenyuan.xie2002@gmail.com</a> or <a href="/files/Wenyuan_Xie_Academic_CV_EN.pdf">download my CV</a> / <a href="/files/Wenyuan_Xie_Resume_EN.pdf">resume</a>.</div>
</div>
<div id="lang-zh" class="lang-panel" hidden><div class="hero">
  <div class="section-kicker">具身智能 · 机器人 · 智能体学习</div>
  <h1>谢文远 <span style="font-weight:400;color:#607087">Wenyuan Xie</span></h1>
  <div class="tagline">让智能体感知、推理并在真实世界中行动。</div>
  <p>我目前是上海交通大学巴黎卓越工程师学院电子信息硕士三年级学生，准备申请 2027 Fall。研究方向包括视觉语言动作模型、具身导航、机器人操作、世界模型和智能体后训练。</p>
  <div class="pills"><span class="pill">具身策略与智能体系统</span><span class="pill">世界模型与视觉基础模型</span><span class="pill">强化学习算法与系统</span></div>
</div>
<div class="section-kicker">代表工作</div><h2 id="publications-zh">论文与项目</h2>
<p>研究聚焦将视觉表征、物理几何和学习型智能体结合，使系统能够从经验中适应并完成长程任务。</p>
<div class="pub-grid">
  <article class="pub-card"><p class="pub-meta">RSS 2026 · 一作</p><h3>MVP-Nav: Multi-layer Value Map Planner Navigator</h3><p>结合 VGGT、Grounded-SAM 与 Multi-layer Value Map，解决纯视觉导航中语义目标与物理约束的结合问题。</p><p><a href="https://arxiv.org/abs/2606.31919">论文</a></p></article>
  <article class="pub-card"><p class="pub-meta">在投 · 一作</p><h3>Navi-Agent: Unlocalized Monocular Navigation Agent</h3><p>通过 Visual Anchor Graph 解决无定位条件下导航系统的移动与位置认知问题。</p><p><a href="https://arxiv.org/abs/2609.20388">论文</a></p></article>
  <article class="pub-card"><p class="pub-meta">ECCV 2026 · 三作</p><h3>RelAfford6D: Relational 6D Affordance Graphs</h3><p>利用关系式 6D 可供性图和约束轨迹生成实现关节物体操作。</p><p><a href="https://arxiv.org/abs/2606.27036">论文</a></p></article>
</div>
<div class="section-kicker">教育经历</div><h2>教育经历</h2><div class="timeline">
<p><strong>2024.09 - 至今</strong> - 上海交通大学巴黎卓越工程师学院，电子信息硕士</p>
<p><strong>2020.09 - 2024.06</strong> - 上海交通大学巴黎卓越工程师学院，法语专业，辅修信息工程（IE）</p></div>
<div class="section-kicker">实习经历</div><h2>实习经历</h2><div class="timeline">
<p><strong>2026.03 - 2026.07</strong> - 智元机器人：手机包装任务强化学习后训练与轮足机器人全身控制</p>
<p><strong>2024.06 - 2024.09</strong> - 阿里云：杭州亚运会首款零碳特许商品吉祥物的产品碳足迹认证，完成生命周期碳核算、碳中和与数字化认证，并辅助中国美术学院低碳平台</p></div>
<div class="section-kicker">技能</div><h2>技能</h2><p><strong>编程：</strong>Python、PyTorch、JAX、C++、Java、MATLAB · <strong>方向：</strong>VLA、VLN、智能体、世界模型、真机 RL</p>
<div class="cta"><strong>欢迎交流。</strong> 如有研究合作或机器人方向机会，欢迎通过 <a href="mailto:wenyuan.xie2002@gmail.com">wenyuan.xie2002@gmail.com</a> 联系我，或<a href="/files/Wenyuan_Xie_Academic_CV_CN.pdf">下载我的 CV</a> / <a href="/files/Wenyuan_Xie_Resume_CN.pdf">中文简历</a>。</div>
</div>
