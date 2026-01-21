---
permalink: /
title: ""
excerpt: ""
author_profile: true
lang: en
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}





<span class='anchor' id='about-me'></span>
# 😊 About me

***Resume (in Chinese)***: [Resume](resume_in_chinese_20260120.pdf) (Updated on 20 Jan, 2026)

***Contact***: **lihaoxun23@mails.ucas.ac.cn (preferred)**, rickyhx@163.com

---
<style>
/* Slightly reduce spacing between top-level headings on the home page */
.page__content > h1 { margin-top: 1.7em !important; margin-bottom: 0.45em; }
.page__content > h1:first-of-type { margin-top: 0.45em !important; }
@media (max-width: 640px) { .page__content > h1 { margin-top: 1.4em !important; } }
/* Use Times New Roman for body content and slightly smaller size */
.page__content { font-family: "Times New Roman", Times, serif; font-size: 1.00em; }
.page__content p, .page__content li, .page__content div { font-family: "Times New Roman", Times, serif; }
/* Headings in Times New Roman and emphasized styling */
.page__content h1, .page__content h2, .page__content h3 { font-family: "Times New Roman", Times, serif; font-weight: 700; color: #222; text-rendering: optimizeLegibility; }
.page__content h1 { border-bottom: 2px solid #e5e5e5; padding-bottom: 4px; }
.page__content h2, .page__content h3 { border-left: 4px solid #2a72d4; padding-left: 10px; background: linear-gradient(to right, rgba(42,114,212,0.06), rgba(42,114,212,0)); border-radius: 4px; }

/* Collapsible section styles */
.section-toggle-btn {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: #fff;
  border: none;
  border-radius: 20px;
  padding: 6px 16px;
  font-family: "Times New Roman", Times, serif;
  font-size: 0.9em;
  font-weight: 600;
  cursor: pointer;
  margin: 8px 0 12px 0;
  box-shadow: 0 3px 10px rgba(102, 126, 234, 0.3);
  transition: all 0.3s ease;
}
.section-toggle-btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
}
.section-toggle-btn:active {
  transform: translateY(0);
}
.section-toggle-btn .toggle-icon {
  display: inline-block;
  transition: transform 0.3s ease;
  font-size: 0.85em;
}
.section-toggle-btn.expanded .toggle-icon {
  transform: rotate(180deg);
}
.collapsible-content {
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.5s ease-out, opacity 0.3s ease;
  opacity: 0;
}
.collapsible-content.expanded {
  max-height: 5000px;
  opacity: 1;
  transition: max-height 0.7s ease-in, opacity 0.3s ease;
}
/* Dark mode support for toggle button */
@media (prefers-color-scheme: dark) {
  .section-toggle-btn { background: linear-gradient(135deg, #5a67d8 0%, #6b46c1 100%); box-shadow: 0 3px 10px rgba(90, 103, 216, 0.4); }
}
html.dark .section-toggle-btn, body.dark .section-toggle-btn, html[data-theme="dark"] .section-toggle-btn { 
  background: linear-gradient(135deg, #5a67d8 0%, #6b46c1 100%) !important; 
  box-shadow: 0 3px 10px rgba(90, 103, 216, 0.4) !important; 
}
</style>

<!-- Dark mode is handled globally in layout/head; local button/styles removed -->


Hi! I am Haoxun Li (李浩勋), a final-year M.S. candidate in Artificial Intelligence at the [School of Intelligent Science and Technology](http://hias.ucas.ac.cn/znkxyjs/index.htm), [Hangzhou Institute for Advanced Study (HIAS)](http://hias.ucas.ac.cn/), [University of Chinese Academy of Sciences (UCAS)](https://www.ucas.edu.cn/). 

My research interests include emotional speech generation and recognition, as well as multimodal affective computing. During my studies, I have received multiple honors, including the UCAS Merit Student Award, the First-Class Academic Scholarship, and the National Scholarship. I am grateful to be advised by Prof. Taihao Li and Dr. Leyuan Qu for their high comprehensive support and guidance in my research. I also sincerely thank my labmates [Yu Liu](https://yultheconkor.github.io/) and Hanlei Shi—our close collaboration and frequent discussions have made research both productive and enjoyable.

I believe that while AI is rapidly growing into a powerful tool and assistant, it still cannot be compared with humans in a fundamental sense, largely because it lacks genuine emotional understanding and empathy. Affective computing will be crucial for making human-computer interaction more natural and trustworthy, and may become an important direction for the future of AI. Motivated by this, my current work focuses on speech as a primary modality: by leveraging richer paralinguistic cues, I aim to improve both emotion recognition and emotion generation, ultimately enabling more natural and emotionally aware human-computer interaction.

<span class='anchor' id='news'></span>
# 🔥 News
<style>
/* News section scroll window styles (scoped) */
.news .scroll-window { max-height: 640px; overflow-y: auto; padding: 8px 6px; border: 1px solid #eaeaea; border-radius: 12px; background: #fff; box-shadow: inset 0 1px 0 rgba(255,255,255,0.6), 0 6px 14px rgba(0,0,0,0.04); }
.news .scroll-window::-webkit-scrollbar { width: 8px; }
.news .scroll-window::-webkit-scrollbar-thumb { background: #ddd; border-radius: 4px; }
</style>

<div class="news" markdown="1">
<div class="scroll-window" markdown="1">
- *2026.01*  &nbsp;🎉🎉 Two papers accepted by ICASSP 2026 (one for [TTS](https://arxiv.org/abs/2510.05758) and one for [SER](https://arxiv.org/abs/2510.05749)).

</div>
</div>

<script>
(function() {
  function setNewsScrollWindowHeight() {
    var container = document.querySelector('.news .scroll-window');
    if (!container) return;
    var firstLi = container.querySelector('li');
    if (!firstLi) return; // fallback to CSS default max-height
    var liRect = firstLi.getBoundingClientRect();
    var liStyle = window.getComputedStyle(firstLi);
    var marginTop = parseFloat(liStyle.marginTop) || 0;
    var marginBottom = parseFloat(liStyle.marginBottom) || 0;
    var perItem = liRect.height + (marginTop + marginBottom);
    var target = perItem * 2; // show ~2 items
    container.style.maxHeight = target + 'px';
  }
  function onReady(fn) {
    if (document.readyState === 'loading') {
      document.addEventListener('DOMContentLoaded', fn, { once: true });
    } else { fn(); }
  }
  onReady(setNewsScrollWindowHeight);
  var resizeTimeout;
  window.addEventListener('resize', function() {
    clearTimeout(resizeTimeout);
    resizeTimeout = setTimeout(setNewsScrollWindowHeight, 150);
  });
})();
</script>

<span class='anchor' id='Publication-List'></span>
# 📝 Publications

<div id="publications-section" markdown="1">

## Papers and preprints
Please scroll down to view all publications.
\* denotes Co-first Author, † denotes Advisor.
<style>
/* Publications section styles (scoped) */
.publications { font-family: "Times New Roman", Times, serif; font-size: 0.96em; }
.publications .bibliography { list-style: none; margin: 0; padding: 0; }
.publications .bibliography li { margin: 10px 0; }
.publications .pub-row {
  display: flex;
  gap: 12px;
  align-items: center;
  background: #fff;
  border: 1px solid #eee;
  border-radius: 12px;
  padding: 14px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.06);
  max-width: 900px;
  margin-left: auto;
  margin-right: auto;
}
.publications .pub-row .abbr.pub-thumb {
  position: relative;
  flex: 0 0 320px;
  max-width: 320px;
  padding: 0 15px; /* keep original padding intent */
}
.publications .pub-row .abbr.pub-thumb img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 10px 16px rgba(0,0,0,0.12);
}
.publications .pub-row .abbr.pub-thumb .badge {
  position: absolute;
  top: -8px;
  left: -8px;
  background: #e74d3c;
  color: #fff;
  padding: 4px 8px;
  border-radius: 6px;
  font-weight: 700;
}
.publications .pub-content { flex: 1 1 auto; padding-left: 4px; }
.publications .title { font-size: 1.14rem; font-weight: 700; line-height: 1.35; }
.publications .author { font-size: 0.98rem; }
.publications .periodical { font-size: 0.96rem; }
.publications .honor { font-size: 0.96rem; color: #e74d3c; font-weight: 700; margin: 4px 0; }
.publications .honor p { margin: 0; }
.publications .honor a { color: inherit; text-decoration: underline; }
.publications .honor a:hover { color: inherit; text-decoration: none; }
.publications .intro { font-size: 0.90rem; color: #555; font-weight: 600; font-style: italic; margin: 4px 0; }
.publications .links a { font-size: 12px !important; }
.publications .links { margin-top: 10px; display: flex; gap: 10px; flex-wrap: wrap; }
.publications .pub-button {
  font-family: "Times New Roman", Times, serif;
  background: #fff;
  color: #333;
  border: 1px solid #ddd;
  border-radius: 0;
  padding: 8px 14px;
  font-size: 1rem;
  text-decoration: none;
  box-shadow: 0 4px 12px rgba(0,0,0,0.12);
  transition: transform .05s ease, box-shadow .2s ease, border-color .2s ease;
}
.publications .pub-button:hover {
  transform: translateY(-1px);
  box-shadow: 0 10px 18px rgba(0,0,0,0.16);
  border-color: #bbb;
  text-decoration: none;
}
.publications .title a { color: #2a72d4; text-decoration: none; }
.publications .title a:hover { text-decoration: underline; color: #1e5bb8; }
/* Scroll window to show only a few items initially */
.publications .scroll-window { max-height: 640px; overflow-y: auto; padding: 8px 6px; border: 1px solid #eaeaea; border-radius: 12px; background: #fff; box-shadow: inset 0 1px 0 rgba(255,255,255,0.6), 0 6px 14px rgba(0,0,0,0.04); }
.publications .scroll-window::-webkit-scrollbar { width: 8px; }
.publications .scroll-window::-webkit-scrollbar-thumb { background: #ddd; border-radius: 4px; }
@media (max-width: 640px) {
  .publications .pub-row { flex-direction: column; }
  .publications .pub-row .abbr.pub-thumb { max-width: 100%; flex-basis: auto; }
  .publications .scroll-window { max-height: 420px; }
}
</style>

<div class="publications" markdown="1">
<div class="scroll-window">
<ul class="bibliography">

{% for link in site.data.publications.main %}

<li>
<div class="pub-row">
  <div class="col-sm-3 abbr pub-thumb" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if link.image %} 
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width: 100%; height: auto;">
    {% endif %}
    {% if link.conference_short %} 
    <abbr class="badge">{{ link.conference_short }}</abbr>
    {% endif %}
  </div>
  <div class="col-sm-9 pub-content" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.paper | default: '/404.html' }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em>
      </div>
      {% if link.honor %}
      <div class="honor">{{ link.honor | markdownify }}</div>
      {% endif %}
      {% if link.intro %}
      <div class="intro">{{ link.intro }}</div>
      {% endif %}
    <div class="links">
      <a href="{{ link.paper | default: '/404.html' }}" class="pub-button paper" role="button" target="_blank">Paper</a>
      <a href="{{ link.code | default: '/404.html' }}" class="pub-button code" role="button" target="_blank">Code</a>
      <a href="{{ link.website | default: '/404.html' }}" class="pub-button website" role="button" target="_blank">Website</a>
      {% if link.github_folks %} 
      <a target="_blank" href ="https://github.com/{{ link.github_stars }}"><img alt="GitHub forks" align="right" src="https://img.shields.io/github/forks/{{ link.github_folks }}?style=social"></a>
      {% endif %}
      {% if link.github_stars %} 
      <a target="_blank" href ="https://github.com/{{ link.github_stars }}"><img alt="GitHub stars" align="right" src="https://img.shields.io/github/stars/{{ link.github_stars }}?style=social"></a>
      {% endif %}
    </div>
  </div>
</div>
</li>



{% endfor %}

</ul>
</div>
</div>

<script>
(function() {
  function setScrollWindowHeight() {
    var container = document.querySelector('.publications .scroll-window');
    if (!container) return;
    var firstLi = container.querySelector('.bibliography > li');
    var firstRow = container.querySelector('.pub-row');
    if (!firstRow || !firstLi) return;
    var rowRect = firstRow.getBoundingClientRect();
    var liStyle = window.getComputedStyle(firstLi);
    var marginTop = parseFloat(liStyle.marginTop) || 0;
    var marginBottom = parseFloat(liStyle.marginBottom) || 0;
    var perItem = rowRect.height + (marginTop + marginBottom);
  var target = perItem * 3.5; // show ~3.5 items
    container.style.maxHeight = target + 'px';
  }
  function onReady(fn) {
    if (document.readyState === 'loading') {
      document.addEventListener('DOMContentLoaded', fn, { once: true });
    } else { fn(); }
  }
  onReady(setScrollWindowHeight);
  var resizeTimeout;
  window.addEventListener('resize', function() {
    clearTimeout(resizeTimeout);
    resizeTimeout = setTimeout(setScrollWindowHeight, 150);
  });
})();
</script>

## Invention Patents
† denotes Advisor.

- **A Fine-Grained Emphasis-Controllable Emotional Speech Synthesis Method**

   Inventor: Taihao Li†, Leyuan Qu†, **<u>Haoxun Li</u>**, Jiaxi Hu, Hanlei Shi

- **A Speech Emotion Recognition Method Based on Supervised Contrastive Learning**

   Inventor: Taihao Li†, Leyuan Qu†, Jiaxi Hu, **<u>Haoxun Li</u>**, Yu Zhang

- **A Dynamic Facial Expression Recognition Method, Electronic Device, and Computer-Readable Storage Medium**

   Inventor: Taihao Li†, Leyuan Qu†, Yu Liu, Hanlei Shi, **<u>Haoxun Li</u>**

- **A Chord-Emotion-Based Motivic Development Algorithm for Multi-Voice Music Generation**

   Inventor: **<u>Haoxun Li</u>**, Wei Ma†

<!-- ## White Paper
As these works are presented in China, these names are directly translated from Chinese.

- **White Paper on Cross-Border Economic Large Language Model** -->

</div>

<span class='anchor' id='educations'></span>
# 📖 Educations

<button class="section-toggle-btn" onclick="toggleSection('educations-section', this)">
  <span class="toggle-icon">▼</span> Click to expand
</button>

<div id="educations-section" class="collapsible-content" markdown="1">

<style>
.edu-list { list-style: none; margin: 0; padding: 0; }
.edu-item { 
  background: #fff; border: 1px solid #eee; border-radius: 12px; 
  box-shadow: 0 4px 12px rgba(0,0,0,0.06); padding: 14px; 
  display: flex; gap: 16px; align-items: center; max-width: 900px; margin: 10px auto;
}
.edu-text { flex: 1 1 auto; font-family: "Times New Roman", Times, serif; }
.edu-title { font-weight: 700; margin: 0 0 6px; }
.edu-sub { color: #555; margin: 0 0 6px; }
.edu-time { color: #777; font-size: 0.95em; }
.edu-img { flex: 0 0 200px; max-width: 200px; }
.edu-img img { width: 100%; height: auto; border-radius: 8px; box-shadow: 0 6px 14px rgba(0,0,0,0.10); }
@media (max-width: 640px) { .edu-item { flex-direction: column; } .edu-img { max-width: 100%; flex-basis: auto; } }
</style>

<ul class="edu-list">
  <li class="edu-item">
    <div class="edu-text">
      <p class="edu-title">M.S. in Artificial Intelligence</p>
      <p class="edu-sub">University of Chinese Academy of Sciences, Hangzhou Institute for Advanced Study (HIAS, UCAS)</p>
      <ul style="margin: 6px 0 6px 18px; padding: 0; font-size: 0.96em; color: #555;">
        <li>Advisor: Prof. Taihao Li</li>
      </ul>
      <p class="edu-time">2023.09 -</p>
    </div>
    <div class="edu-img"><img src="images/ucas.png" alt="UCAS"></div>
  </li>
  <li class="edu-item">
    <div class="edu-text">
      <p class="edu-title">B.S. in Computer Science and Technology</p>
      <p class="edu-sub">Fan Gongxiu Honors College, Beijing University of Technology</p>
      <ul style="margin: 6px 0 6px 18px; padding: 0; font-size: 0.96em; color: #555;">
        <li>Advisor: Prof. Wei Ma</li>
      </ul>
      <p class="edu-time">2019.09 - 2023.07</p>
    </div>
    <div class="edu-img"><img src="images/bjut-logo-2048px.png" alt="BJUT"></div>
  </li>
</ul>

</div>

---
<!-- <span class='anchor' id='internships'></span>
# 💻 Internships and Work Experiences

<button class="section-toggle-btn" onclick="toggleSection('internships-section', this)">
  <span class="toggle-icon">▼</span> Click to expand
</button>

<div id="internships-section" class="collapsible-content" markdown="1">

<style>
.exp-list { list-style: none; margin: 0; padding: 0; }
.exp-item { 
  background: #fff; border: 1px solid #eee; border-radius: 12px; 
  box-shadow: 0 4px 12px rgba(0,0,0,0.06); padding: 14px; 
  display: flex; gap: 16px; align-items: center; max-width: 900px; margin: 10px auto;
}
.exp-text { flex: 1 1 auto; font-family: "Times New Roman", Times, serif; }
.exp-title { font-weight: 700; margin: 0 0 6px; }
.exp-sub { color: #555; margin: 0 0 6px; }
.exp-time { color: #777; font-size: 0.95em; }
.exp-img { flex: 0 0 200px; max-width: 200px; }
.exp-img img { width: 100%; height: auto; border-radius: 8px; box-shadow: 0 6px 14px rgba(0,0,0,0.10); background: #fff; }
@media (max-width: 640px) { .exp-item { flex-direction: column; } .exp-img { max-width: 100%; flex-basis: auto; } }
</style>

<style>
/* Experiences section scroll window styles (scoped) */
.experiences .scroll-window { max-height: 640px; overflow-y: auto; padding: 8px 6px; border: 1px solid #eaeaea; border-radius: 12px; background: transparent; box-shadow: inset 0 1px 0 rgba(255,255,255,0.6), 0 6px 14px rgba(0,0,0,0.04); }
.experiences .scroll-window::-webkit-scrollbar { width: 8px; }
.experiences .scroll-window::-webkit-scrollbar-thumb { background: #ddd; border-radius: 4px; }
</style>

<style>
/* Dark mode overrides for Internships section */
@media (prefers-color-scheme: dark) {
  .experiences .scroll-window { background: #111; border-color: #333; box-shadow: inset 0 1px 0 rgba(255,255,255,0.04), 0 6px 14px rgba(0,0,0,0.6); }
  .exp-item { background: #111; border-color: #333; box-shadow: 0 4px 12px rgba(0,0,0,0.5); }
}
</style>

<style>
/* Dark mode overrides (class/data-attribute toggles) for Internships section */
html.dark .experiences .scroll-window,
body.dark .experiences .scroll-window,
html[data-theme="dark"] .experiences .scroll-window,
:root[data-theme="dark"] .experiences .scroll-window,
[data-scheme="dark"] .experiences .scroll-window { background: #111 !important; border-color: #333 !important; box-shadow: inset 0 1px 0 rgba(255,255,255,0.04), 0 6px 14px rgba(0,0,0,0.6) !important; }

html.dark .exp-item,
body.dark .exp-item,
html[data-theme="dark"] .exp-item,
:root[data-theme="dark"] .exp-item,
[data-scheme="dark"] .exp-item { background: #111 !important; border-color: #333 !important; box-shadow: 0 4px 12px rgba(0,0,0,0.5) !important; }

html.dark .exp-img img,
body.dark .exp-img img,
html[data-theme="dark"] .exp-img img,
:root[data-theme="dark"] .exp-img img,
[data-scheme="dark"] .exp-img img { background: transparent !important; }
</style>

<div class="experiences">
<div class="scroll-window">
<ul class="exp-list">
  <li class="exp-item">
    <div class="exp-text">
      <p class="exp-title">Full-time Research Staff</p>
      <p class="exp-sub">Nanyang Technological University, Singapore</p>
      <ul style="margin: 6px 0 6px 18px; padding: 0; font-size: 0.96em; color: #555;">
        <li>Affiliation: College of Computing and Data Science (CCDS)</li>
        <li>Advisor: Prof. Bo An</li>
      </ul>
      <p class="exp-time">2025.09 - 2026.01</p>
    </div>
    <div class="exp-img"><img src="assets/institutions/ntu.png" alt="NTU"></div>
  </li>


  <li class="exp-item">
    <div class="exp-text">
      <p class="exp-title">Intern (Remote)</p>
      <p class="exp-sub">Hong Kong Generative AI Research & Development Center (HKGAI), HKUST</p>
      <ul style="margin: 6px 0 6px 18px; padding: 0; font-size: 0.96em; color: #555;">
        <li>Affiliation: HKGAI</li>
        <li>Director: Prof. Yike Guo</li>
        <li>Proposed a new product-inspired Agentic Function Calling paradigm (<a href="https://arxiv.org/abs/2601.01569v1">[[CaveAgent]]</a>).</li>
      </ul>
      <p class="exp-time">2025.05 - 2025.09</p>
    </div>
    <div class="exp-img"><img src="assets/institutions/hkgai.png" alt="HKGAI"></div>
  </li>


  <li class="exp-item">
    <div class="exp-text">
      <p class="exp-title">Intern Researcher</p>
      <p class="exp-sub">Agency for Science, Technology and Research (A*STAR), Singapore</p>
      <ul style="margin: 6px 0 6px 18px; padding: 0; font-size: 0.96em; color: #555;">
        <li>Affiliation: Centre for Frontier AI Research (CFAR), Institute of High Performance Computing (IHPC)</li>
        <li>Advisor: Prof. Ivor Tsang, Dr. Xingrui Yu</li>
      </ul>
      <p class="exp-time">2024.07 - 2025.09  (3 months full-time + 11 months part-time)</p>
    </div>
    <div class="exp-img"><img src="assets/institutions/astar.png" alt="A*STAR"></div>
  </li>


  <li class="exp-item">
    <div class="exp-text">
      <p class="exp-title">Research Assistant</p>
      <p class="exp-sub">The Chinese University of Hong Kong, Shenzhen</p>
      <ul style="margin: 6px 0 6px 18px; padding: 0; font-size: 0.96em; color: #555;">
        <li>Affiliation: School of Data Science</li>
        <li>Advisor: Prof. Jianfeng Mao</li>
      </ul>
      <p class="exp-time">2023.06 - 2024.06</p>
    </div>
    <div class="exp-img"><img src="assets/institutions/cuhksz.png" alt="CUHK(SZ)"></div>
  </li>

  <li class="exp-item">
    <div class="exp-text">
      <p class="exp-title">Machine Learning Algorithm Engineer Intern</p>
      <p class="exp-sub">HUIYINTONG, Shenzhen, China</p>
      <ul style="margin: 6px 0 6px 18px; padding: 0; font-size: 0.96em; color: #555;">
        <li>Mentor: Dr. Jun Song</li>
      </ul>
      <p class="exp-time">2023.07 - 2024.01</p>
    </div>

  </li>



 </ul>
</div>
</div>
<span class='anchor' id='person'></span>

<script>
(function() {
  function setExpScrollWindowHeight() {
    var container = document.querySelector('.experiences .scroll-window');
    if (!container) return;
    var firstLi = container.querySelector('.exp-list > li');
    if (!firstLi) return; // fallback to CSS default max-height
    var rowRect = firstLi.getBoundingClientRect();
    var liStyle = window.getComputedStyle(firstLi);
    var marginTop = parseFloat(liStyle.marginTop) || 0;
    var marginBottom = parseFloat(liStyle.marginBottom) || 0;
    var perItem = rowRect.height + (marginTop + marginBottom);
    var target = perItem * 3; // show ~3 items
    container.style.maxHeight = target + 'px';
  }
  function onReady(fn) {
    if (document.readyState === 'loading') {
      document.addEventListener('DOMContentLoaded', fn, { once: true });
    } else { fn(); }
  }
  onReady(setExpScrollWindowHeight);
  var resizeTimeout;
  window.addEventListener('resize', function() {
    clearTimeout(resizeTimeout);
    resizeTimeout = setTimeout(setExpScrollWindowHeight, 150);
  });
})();
</script>

</div> -->

<!-- <span class='anchor' id='services'></span>
# 🎈 Services

<button class="section-toggle-btn" onclick="toggleSection('services-section', this)">
  <span class="toggle-icon">▼</span> Click to expand
</button>

<div id="services-section" class="collapsible-content" markdown="1">

- Reviewer of AAAI, ICLR, ICML, NeurIPS

</div> -->

<span class='anchor' id='honors-and-awards'></span>
# 🎖 Honors, Awards and Scholarships

<button class="section-toggle-btn" onclick="toggleSection('honors-section', this)">
  <span class="toggle-icon">▼</span> Click to expand
</button>

<div id="honors-section" class="collapsible-content" markdown="1">

- **National Scholarship**

- **UCAS First-Class Academic Scholarship**

- **UCAS Merit Student Award**

- **BJUT Innovation & Entrepreneurship Award**

- **BJUT Outstanding Graduation Thesis Award**

</div>
  
<!-- <span class='anchor' id='press-media'></span>

# 💬 Press/Media

<button class="section-toggle-btn" onclick="toggleSection('press-section', this)">
  <span class="toggle-icon">▼</span> Click to expand
</button>

<div id="press-section" class="collapsible-content" markdown="1">

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">White Paper</div><img src='personal_page_sources/white_paper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


- The co-author of the first White Paper on Cross-Border Economic Large Language Model in Shenzhen, China.
[深圳卫视：深圳发布首个跨境经济大模型白皮书](https://www.sohu.com/a/786227332_121123831)

</div>
</div>

</div> -->

<span class='anchor' id='person'></span>
# Miscellaneous

<button class="section-toggle-btn" onclick="toggleSection('misc-section', this)">
  <span class="toggle-icon">▼</span> Click to expand
</button>

<div id="misc-section" class="collapsible-content" markdown="1">

I'm a music enthusiast. I started learning guitar in the 5th grade under Mr. Yongxi Yang. After reaching Level 10 in classical guitar, I became obsessed with fingerstyle guitar and taught myself more advanced techniques. My favorite player is the Brazilian fingerstyle guitarist Daniel Padim—I genuinely think every one of his pieces is pure magic, and they've kept me company through countless days and nights. During my master's program, I even chose to live in the lab so I could practice guitar every deep night.

<div style="display: flex; justify-content: space-between; gap: 10px; max-width: 500px; margin: 15px auto;">
  <img src='images/m1-1.jpg' alt="guitar" style="width: 60%; height: auto; object-fit: contain;">
  <img src='images/m1-2.jpg' alt="guitar" style="width: 40%; height: auto; object-fit: contain;">
</div>

In high school, I formed my first band, "半成品乐队", and we performed our songs at the coming-of-age ceremony of Beijing No. 101 High School. As an undergraduate, I met my three best friends—Xincheng Liu, Jieni Ma, and Yuchen Zhu—and we started a small band called "三人一猪". We wrote the college anthem and performed it at the [graduation ceremony](https://www.bilibili.com/video/BV1wa4y1c7Kg/?spm_id_from=333.1387.homepage.video_card.click&vd_source=aea926cd427c710577bcb1bcdaae25ee). During my master's program, I helped found an instrumental music club, formed HIAS's first band, and played at various events.

<div style="display: flex; justify-content: space-between; gap: 10px; max-width: 500px; margin: 15px auto;">
  <img src='images/m2-1.png' alt="band" style="width: 60%; height: auto; object-fit: contain;">
  <img src='images/m2-2.jpg' alt="band" style="width: 60%; height: auto; object-fit: contain;">
</div>

I also love chess games, especially Go (围棋). Ever since I learned Go in the 2nd grade, I once went through a phase where I studied it on my own for about 10 hours a day. In 3rd grade, I won the Haidian District "Chunqiu Cup" (Primary School Group). By 5th grade, I reached Amateur 5-dan (the highest amateur rank) and was awarded the title of National Level-2 Athlete.

<div style="display: flex; justify-content: center; max-width: 220px; margin: 15px auto;">
  <img src='images/m3-1.jpg' alt="go" style="width: 100%; height: auto; object-fit: contain;">
</div>

I enjoy logic games too—Werewolf, Blood on the Clocktower, Sudoku, and more. I started competitive math early in elementary school, and in 4th grade I won a Gold Award at the IMC (International Mathematics Competition) held in Singapore, which definitely sharpened my logical thinking. Friends I've played Werewolf with once nicknamed me "老流氓"—and I take it as a really high compliment. 🙂

I'm a big fan of ball sports, including (but not limited to) badminton, table tennis, soccer, tennis, and billiards. Before starting my master's program, I served multiple times as team captain for badminton, table tennis, and soccer teams. Since entering my master's program, I've won five medals across different campus sports competitions—and, jokingly speaking, I've done my part to make people take the Sports Power of the School of Intelligent Science and Technology very seriously.

<div style="display: flex; justify-content: center;">
  <img src='images/jiangpai.png' alt="sports medals" width="40%" style="display: inline-block;">
</div>

Finally, my two favorite games are Arknights and Identity V. Feel free to add me (my Arknights account is on the official server).

<div style="display: flex; justify-content: space-between; gap: 10px; max-width: 500px; margin: 15px auto;">
  <img src='images/mingrifangzhou.png' alt="Arknights" style="width: 70%; height: auto; object-fit: contain;">
  <img src='images/diwurenge.png' alt="Identity V" style="width: 55%; height: auto; object-fit: contain;">
</div>

</div>

<script>
function toggleSection(sectionId, btn) {
  var content = document.getElementById(sectionId);
  var isExpanded = content.classList.contains('expanded');
  
  if (isExpanded) {
    content.classList.remove('expanded');
    btn.classList.remove('expanded');
    btn.innerHTML = '<span class="toggle-icon">▼</span> Click to expand';
  } else {
    content.classList.add('expanded');
    btn.classList.add('expanded');
    btn.innerHTML = '<span class="toggle-icon">▼</span> Click to collapse';
  }
}
</script>



