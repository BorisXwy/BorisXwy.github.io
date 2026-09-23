---
permalink: /zh/
title: ""
excerpt: ""
author_profile: true
lang: zh
---

<style>
:root { --ink:#172033; --muted:#607087; --accent:#1967d2; --soft:#f5f8fc; }
.lang-switch { text-align:right; margin:0 0 1rem; font-size:.9rem; }
.lang-switch a { color:var(--accent); font-weight:600; text-decoration:none; }
.hero { padding:2rem 2.2rem 1.8rem; border-radius:18px; background:linear-gradient(135deg,#f3f7ff 0%,#f9fbff 55%,#eef7f5 100%); border:1px solid #e4ebf5; margin-bottom:2rem; }
.hero h1 { margin:0 0 .6rem; color:var(--ink); font-size:2.1rem; }
.hero .tagline { color:var(--accent); font-size:1.1rem; font-weight:600; margin:.2rem 0 1rem; }
.hero p { max-width:760px; color:var(--muted); font-size:1.03rem; line-height:1.75; }
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

<div class="lang-switch"><a href="/">EN</a> <span>|</span> <a href="/zh/">中文</a></div>

<div class="hero">
  <div class="section-kicker">具身智能 · 机器人 · 学习型智能体</div>
  <h1>谢文远 <span style="font-weight:400;color:#607087">Wenyuan Xie</span></h1>
  <div class="tagline">让智能体感知、推理，并在真实世界中行动。</div>
  <p>我目前是上海交通大学巴黎卓越工程师学院硕士三年级学生，正在准备 2027 Fall 申请。我的研究关注视觉-语言-动作模型、具身导航、机器人操作，以及提升智能体可靠性的后训练方法。</p>
  <p>我的本科和硕士阶段均就读于上海交通大学巴黎卓越工程师学院。研究之外，我喜欢羽毛球、健身，也乐于交流机器人与机器学习。</p>
  <div class="pills"><span class="pill">VLA 与 VLN</span><span class="pill">机器人操作</span><span class="pill">强化学习</span><span class="pill">三维感知</span><span class="pill">智能体后训练</span></div>
</div>

<div class="section-kicker">代表工作</div>
<h2 id="publications">论文与项目</h2>
<p>我的研究将结构化几何表示与学习型智能体结合，使系统能够从经验中适应，并更加稳健地完成长时序任务。</p>
<div class="pub-grid">
  <article class="pub-card"><p class="pub-meta">RSS 2026 · 第一作者</p><h3>MVP-Nav: Multi-layer Value Map Planner Navigator</h3><p>结合 VGGT、Grounded-SAM 与视觉语言模型的多层价值地图规划器，用于稳健的三维导航。</p><p><a href="https://arxiv.org/abs/2606.31919">论文</a></p></article>
  <article class="pub-card"><p class="pub-meta">ICRA 2027 · 审稿中 · 共同一作</p><h3>Navi-Agent: Unlocalized Monocular Navigation Agent</h3><p>基于视觉锚点图的无坐标单目导航智能体，用于地点确认、进度验证与路径恢复。</p><p><a href="https://arxiv.org/abs/2609.20388">论文</a></p></article>
  <article class="pub-card"><p class="pub-meta">ECCV 2026</p><h3>RelAfford6D: Relational 6D Affordance Graphs</h3><p>将语言指令转化为关系式 6D 可供性图，并以运动学约束生成闭环操作轨迹。</p><p><a href="https://arxiv.org/abs/2606.27036">论文</a></p></article>
  <article class="pub-card"><p class="pub-meta">CVPR 2026</p><h3>Dejavu: Towards Experience Feedback Learning</h3><p>通过经验反馈网络和执行记忆增强冻结的 VLA 策略，实现部署后的持续适应。</p><p><a href="https://arxiv.org/abs/2510.10181">论文</a> | <a href="https://dejavu2025.github.io/">项目主页</a></p></article>
  <article class="pub-card"><p class="pub-meta">ICML 2026</p><h3>Recovering Hidden Reward in Diffusion-Based Policies</h3><p>从扩散策略的行为中恢复隐藏奖励，为可靠的动作生成提供学习信号。</p><p><a href="https://arxiv.org/abs/2605.00623">论文</a></p></article>
  <article class="pub-card"><p class="pub-meta">EMNLP 2026 · 合作者</p><h3>TRUST: Uncertainty-Aligned Tool-Calling Decisions</h3><p>通过不确定性感知的奖励设计，提升多轮智能体工具调用决策的可靠性。</p><p><a href="https://arxiv.org/abs/2606.06976">论文</a> · <a href="https://github.com/yjzscode/TRUST">代码</a></p></article>
</div>

<div class="section-kicker">教育经历</div>
<h2 id="education">教育经历</h2>
<div class="timeline">
  <p><strong>2024.09 - 至今</strong> - 上海交通大学巴黎卓越工程师学院，硕士三年级，准备 2027 Fall 申请</p>
  <p><strong>2020.09 - 2024.06</strong> - 上海交通大学巴黎卓越工程师学院，本科</p>
  <p><strong>2020 年以前</strong> - 杭州学军中学</p>
</div>

<div class="section-kicker">实习经历</div>
<h2 id="internships">实习经历</h2>
<div class="timeline">
  <p><strong>2026.03 - 2026.07</strong> - 上海人工智能实验室，研究实习生：强化学习与人形机器人全身控制</p>
  <p><strong>2024.06 - 2024.09</strong> - 阿里云，算法实习生：基于 ViNT 与 NoMaD 的视觉导航</p>
</div>

<div class="section-kicker">技能</div>
<h2 id="skills">技能</h2>
<p><strong>工具：</strong>Python、PyTorch、JAX、C++、Java、MATLAB · <strong>方向：</strong>VLA、VLN、智能体、世界模型、强化学习</p>
<div class="cta"><strong>欢迎交流。</strong> 如有研究合作或机器人方向机会，欢迎通过 <a href="mailto:wenyuan.xie2002@gmail.com">wenyuan.xie2002@gmail.com</a> 联系我，或<a href="/files/Wenyuan_Xie_CV.pdf">下载我的 CV</a>。</div>
