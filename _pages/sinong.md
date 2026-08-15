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
          <li>Sinong is China's first open-source agricultural LLM. It addresses challenges in heterogeneous data and spatiotemporal modeling through a "human–AI collaborative, knowledge-driven" approach, building a knowledge base of over 4 billion tokens. The model supports agricultural question answering, literature mining, and experimental design. Since its January 2026 release, Sinong has been downloaded over 2,300 times and adapted for specialized domains including pear, chrysanthemum, potato, and animal quarantine. Recognized as an exemplary "AI + Education" case in Jiangsu Province, it is driving intelligent transformation across agricultural research, production, and education.</li>
          <li>Website: <a href="https://nongzheng.njau.edu.cn/">https://nongzheng.njau.edu.cn/</a><br><a href="https://modelscope.cn/organization/NAULLM">https://modelscope.cn/organization/NAULLM</a></li>
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
          <li>AI Wenli is the world's first openly accessible LLM for the pear industry, trained on a 500M+ token domain corpus validated by over 150 experts and enriched with knowledge from more than 40 industry scientists.</li>
          <li>The platform integrates RAG, web search, Text2SQL, and DeepResearch to support domain-specific question answering, genomic database queries, and automated industry report generation.</li>
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
          <li>Green Shield is China’s first openly accessible LLM for plant protection, jointly developed by 30+ research and industry partners and trained on a 2.5B+ token domain corpus.</li>
          <li>Its three-stage Precision–Expertise–Compliance framework integrates RAG and retrieval-enhanced technologies for evidence-grounded QA and literature retrieval across research, education, agricultural production, and government decision-making.</li>
          <li>Website: <a href="https://psllm.njau.edu.cn/">https://psllm.njau.edu.cn/</a></li>
        </ul>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-image">
      <span class="publication-status">Model</span>
      <img src="{{ '/images/projects/soy-ai.png' | relative_url }}" alt="SoyAI">
    </div>
    <div class="publication-text">
      <h2><a href="https://soyai.njau.edu.cn/">SoyAI</a></h2>
      <div class="publication-highlight">
        <ul>
          <li>SoyAI is China’s first openly accessible LLM dedicated to the soybean industry, built on a 1.5B+ token domain corpus spanning breeding, cultivation, pest management, policy, and markets.</li>
          <li>It combines curated domain knowledge with authoritative web and academic sources, enabling reliable pest diagnosis, risk assessment, and actionable guidance for sustainable soybean production through a progressive three-stage QA workflow.</li>
          <li>Website: <a href="https://soyai.njau.edu.cn/">https://soyai.njau.edu.cn/</a></li>
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
      <h2>Multi-Agent Collaborative Potato Late Blight Protection Assistant</h2>
      <div class="publication-highlight">
        <ul>
          <li>An intelligent recognition system for potato late blight and related pest and disease scenarios is under development.</li>
        </ul>
      </div>
    </div>
  </div>
</div>

