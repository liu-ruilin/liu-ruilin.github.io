---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>
# About me

Hi! I am Ruilin, a Ph.D. student at the College of Information Management, Nanjing Agricultural University. Additionally, I am an active researcher at both the Research Center for Humanities and Social Computing and the Large Language Model Research Center at NJAU. I am privileged to be co-advised by [Prof. Dongbo Wang](https://baike.baidu.com/item/%E7%8E%8B%E4%B8%9C%E6%B3%A2/65038669) and Prof. Shuiqing Huang. At our labs, I work closely with a group of talented colleagues, including [Zhixiao Zhao](https://scholar.google.com/citations?user=ae3BTEMAAAAJ&hl) and [Chang Liu](https://scholar.google.com/citations?user=qN9WYzEAAAAJ&hl). I also benefit immensely from the invaluable guidance and collaboration of [Jin Song](http://scholar.google.com/citations?user=hgv0npkAAAAJ&hl) and [Shiqi Chen](https://scholar.google.com/citations?user=4Tg7zOMAAAAJ&hl).

My research lies at the intersection of Cognitive Science and Computer Science, with a core focus on Large Language Model (LLM) Interpretability. Driven by a mission to make multilingual models more reliable and equitable, my work investigates how LLMs acquire, organize, transfer, and update knowledge under low-resource, cross-lingual, and historical language settings. I am also deeply interested in understanding and mitigating cross-lingual knowledge conflicts to build more trustworthy AI.


<span class="anchor" id="selected-publications"></span>
# Selected Publications

<style>
.publication-list {
  display: flex;
  flex-direction: column;
  margin-top: 8px;
}

.publication-card {
  display: flex;
  padding: 30px 0;
  border-bottom: 1px solid #eceff3;
}

.publication-card:last-child {
  border-bottom: 0;
}

.publication-image {
  flex: 0 0 40%;
}

.publication-image img {
  width: 100%;
  max-height: 210px;
  object-fit: cover;
  display: block;
}

.publication-card h3 {
  margin-top: 0;
  margin-bottom: 6px;
  font-size: 1em;
  line-height: 1.35;
  font-weight: 500;
}

.publication-card h3 a {
  color: #224b8d;
  text-decoration: none;
}

.publication-card h3 a:hover {
  text-decoration: underline;
}

.publication-text {
  flex: 1;
  padding-left: 30px;
}

.publication-authors {
  margin: 0 0 8px 0;
  color: #333;
  font-size: 0.95em;
}

.publication-highlight {
  margin: 0;
  color: #444;
  font-size: 0.95em;
  line-height: 1.5;
}

.publication-highlight ul {
  margin: 0;
  padding-left: 20px;
}

.publication-status {
  display: inline-block;
  margin: 6px 0 0 -6px;
  padding: 0 15px;
  background: #00369f;
  color: #fff;
  font-size: 12px;
  line-height: 18px;
}

@media (max-width: 640px) {
  .publication-card {
    flex-direction: column;
  }

  .publication-text {
    padding-left: 0;
    padding-top: 14px;
  }
}
</style>

<div class="publication-list">
  <div class="publication-card">
    <div class="publication-image">
      <span class="publication-status">ACL March ARR</span>
      <img src="{{ '/images/publications/ffn-organization-vlm.png' | relative_url }}" alt="From Separation to Entanglement">
    </div>
    <div class="publication-text">
      <h3><a href="{{ '/files/publications/ffn-organization-vlm.pdf' | relative_url }}">From Separation to Entanglement: Dissecting Feed-Forward Network Functional Organization in Vision–Language Models for Ancient Chinese Documents</a></h3>
      <p class="publication-authors"><strong>Ruilin Liu</strong>, Dongmei Zhu, Yuting Wei et al.</p>
      <div class="publication-highlight">
        <ul>
          <li>Introducing AC-TCGN to uncover task-relevant FFN neurons and cross-task entanglement in ancient Chinese document VLMs.</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-image">
      <span class="publication-status">Under review</span>
      <img src="{{ '/images/publications/guji-tai.png' | relative_url }}" alt="Guji-TAI">
    </div>
    <div class="publication-text">
      <h3>Guji-TAI: Task-Aware Interpretability for Large Language Models in Ancient Chinese Text Processing</h3>
      <p class="publication-authors"><strong>Ruilin Liu</strong>, Zhixiao Zhao, Dongbo Wang et al.</p>
      <div class="publication-highlight">
        <ul>
          <li>A task-aware interpretability framework unifying explanation targets across diverse ancient Chinese text processing tasks.</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-image">
      <span class="publication-status">Under review</span>
      <img src="{{ '/images/publications/gazetteer-qa.png' | relative_url }}" alt="Progressive Retrieval-Reasoning-Verification">
    </div>
    <div class="publication-text">
      <h3>Progressive Retrieval-Reasoning-Verification for Evidence-Grounded Question Answering in Chinese Local Gazetteers</h3>
      <p class="publication-authors"><strong>Ruilin Liu</strong>, Fan Yang, Dongbo Wang.</p>
      <div class="publication-highlight">
        <ul>
          <li>Introducing progressive retrieval–reasoning–verification for evidence-grounded and traceable question answering over Chinese local gazetteers.</li>
        </ul>
      </div>
    </div>
  </div>
</div>


<span class="anchor" id="projects"></span>
# Projects

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 22px;
  margin-top: 18px;
}

.project-card {
  display: block;
  border: 1px solid #e5e7eb;
  border-radius: 8px;
  overflow: hidden;
  background: #fff;
  color: inherit;
  text-decoration: none;
  transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
}

.project-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 22px rgba(15, 23, 42, 0.08);
  border-color: #cbd5e1;
  text-decoration: none;
}

.project-card img {
  width: 100%;
  height: 180px;
  object-fit: contain;
  display: block;
  background: #fff;
}

.project-card-body {
  padding: 16px 18px 18px;
}

.project-card h3 {
  margin: 0 0 8px;
  color: #224b8d;
  font-size: 1.08em;
}

.project-card p {
  margin: 0;
  color: #4b5563;
  font-size: 0.95em;
  line-height: 1.55;
}

@media (max-width: 720px) {
  .project-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="project-grid">
  <a class="project-card" href="{{ '/projects/sinong/' | relative_url }}">
    <img src="{{ '/images/projects/si-nong.png' | relative_url }}" alt="Si Nong">
    <div class="project-card-body">
      <h3>Si Nong</h3>
      <p>Si Nong is China's first open-source agricultural large language model, based on which we have developed a series of fine-grained LLMs and intelligent agents, such as AI Wenli and Green Shield.</p>
    </div>
  </a>

  <a class="project-card" href="https://xunziallm.njau.edu.cn/">
    <img src="{{ '/images/projects/xunzi.png' | relative_url }}" alt="Xunzi">
    <div class="project-card-body">
      <h3>Xunzi</h3>
      <p>Our project develops an open-source large language model ecosystem for ancient Chinese texts, enabling intelligent processing, research, and application of classical literature.</p>
    </div>
  </a>
</div>
