---
permalink: /projects/sinong/
layout: standalone
title: "Si Nong"
excerpt: ""
---

# Si Nong

Si Nong is an open-source agricultural large language model ecosystem developed around domain-specific foundation models and intelligent agents for agricultural knowledge services, research assistance, and plant protection applications.

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
  height: 210px;
  object-fit: contain;
  display: block;
  background: #fff;
}

.publication-text {
  flex: 1;
  padding-left: 30px;
}

.publication-card h2 {
  margin-top: 0;
  margin-bottom: 8px;
  font-size: 1em;
  line-height: 1.35;
}

.publication-card h2 a {
  color: #224b8d;
  text-decoration: none;
}

.publication-card h2 a:hover {
  text-decoration: underline;
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
  font-size: 0.82em;
  font-weight: 600;
  line-height: 1.65;
}

.publication-placeholder {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 170px;
  background: #f4f6f8;
  color: #6b7280;
  font-weight: 600;
}

@media (max-width: 720px) {
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
      <span class="publication-status">Model</span>
      <img src="{{ '/images/projects/si-nong.png' | relative_url }}" alt="Si Nong">
    </div>
    <div class="publication-text">
      <h2><a href="https://modelscope.cn/organization/NAULLM">Si Nong</a></h2>
      <div class="publication-highlight">
        <ul>
          <li>Si Nong is China's first open-source vertical LLM for the general agricultural sector, developed by Nanjing Agricultural University and released in 8B and 32B versions. It is trained on large-scale agricultural data and enhanced through synthetic data construction, instruction fine-tuning, reinforcement learning, and multi-agent RAG to support intelligent agricultural knowledge services.</li>
          <li>Website: <a href="https://modelscope.cn/organization/NAULLM">https://modelscope.cn/organization/NAULLM</a></li>
        </ul>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-image">
      <span class="publication-status">Platform</span>
      <img src="{{ '/images/projects/ai-wenli.png' | relative_url }}" alt="AI Wenli">
    </div>
    <div class="publication-text">
      <h2><a href="https://www.aiwenli.com/">AI Wenli</a></h2>
      <div class="publication-highlight">
        <ul>
          <li>AI Wenli is an intelligent platform for the pear industry, offering three core functions: knowledge question answering, research assistance, and industry report generation. Its QA module integrates RAG and web search, the research assistant supports Text2SQL-based pear genomic database queries, and the report module uses DeepSearch-style web search to generate structured pear industry reports.</li>
          <li>Website: <a href="https://www.aiwenli.com/">https://www.aiwenli.com/</a></li>
        </ul>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-image">
      <span class="publication-status">Platform</span>
      <img src="{{ '/images/projects/green-shield.png' | relative_url }}" alt="Green Shield">
    </div>
    <div class="publication-text">
      <h2><a href="https://psllm.njau.edu.cn/">Green Shield</a></h2>
      <div class="publication-highlight">
        <ul>
          <li>Green Shield is an intelligent plant protection platform offering knowledge question answering and literature retrieval for agricultural pest and disease management. It integrates RAG, web search, and other retrieval-enhanced technologies to provide accurate, evidence-supported answers and research references.</li>
          <li>Website: <a href="https://psllm.njau.edu.cn/">https://psllm.njau.edu.cn/</a></li>
        </ul>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-image">
      <span class="publication-status">Coming soon</span>
      <div class="publication-placeholder">Coming soon</div>
    </div>
    <div class="publication-text">
      <h2>Soybean Large Language Model</h2>
      <div class="publication-highlight">
        <ul>
          <li>A domain-specific large language model for soybean research and agricultural knowledge services is under development.</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-image">
      <span class="publication-status">Coming soon</span>
      <div class="publication-placeholder">Coming soon</div>
    </div>
    <div class="publication-text">
      <h2>Potato Late Blight Protection Agent</h2>
      <div class="publication-highlight">
        <ul>
          <li>An intelligent recognition system for potato late blight and related pest and disease scenarios is under development.</li>
        </ul>
      </div>
    </div>
  </div>
</div>
