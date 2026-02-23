---
title: "Skills"
layout: single
permalink: /skills/
author_profile: true
---

<style>
.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
  margin-top: 10px;
}
.skill-card {
  border: 1px solid #e0e0e0;
  border-radius: 10px;
  padding: 20px 22px;
  background: #fff;
  box-shadow: 0 2px 8px rgba(0,0,0,0.06);
  border-top: 4px solid #4a90d9;
  transition: box-shadow 0.2s ease;
}
.skill-card:hover {
  box-shadow: 0 4px 16px rgba(0,0,0,0.12);
}
.skill-card .card-title {
  font-size: 0.95em;
  font-weight: 700;
  color: #1a1a1a;
  margin: 0 0 12px 0;
}
.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 7px;
}
.skill-tag {
  display: inline-block;
  background: #f0f6ff;
  color: #004085;
  border: 1px solid #b8daff;
  border-radius: 20px;
  padding: 3px 11px;
  font-size: 0.78em;
  font-weight: 500;
}
.skill-card.security   { border-top-color: #c0392b; }
.skill-card.security .skill-tag   { background: #fff0f0; color: #7b1111; border-color: #f5c6c6; }

.skill-card.vapt       { border-top-color: #922b21; }
.skill-card.vapt .skill-tag       { background: #fdedec; color: #6e1010; border-color: #f1948a; }

.skill-card.crypto     { border-top-color: #6c3483; }
.skill-card.crypto .skill-tag     { background: #f5eef8; color: #4a235a; border-color: #d7bde2; }

.skill-card.cloud      { border-top-color: #FF9900; }
.skill-card.cloud .skill-tag      { background: #fff8f0; color: #7a4500; border-color: #ffd9a8; }

.skill-card.ml         { border-top-color: #8e44ad; }
.skill-card.ml .skill-tag         { background: #f9f0ff; color: #5a2d82; border-color: #d4a8f0; }

.skill-card.llm        { border-top-color: #1a5276; }
.skill-card.llm .skill-tag        { background: #eaf2ff; color: #1a3a5c; border-color: #aed6f1; }

.skill-card.simulation { border-top-color: #16a085; }
.skill-card.simulation .skill-tag { background: #f0fffd; color: #0d5c4a; border-color: #a8e6dc; }

.skill-card.programming { border-top-color: #2c3e50; }
.skill-card.programming .skill-tag { background: #f4f5f6; color: #2c3e50; border-color: #c8cdd2; }

.skill-card.writing    { border-top-color: #b7950b; }
.skill-card.writing .skill-tag    { background: #fefbd8; color: #7d6608; border-color: #f9e79f; }

.skill-card.database   { border-top-color: #27ae60; }
.skill-card.database .skill-tag   { background: #f0fff4; color: #155724; border-color: #c3e6cb; }

.skill-card.tools      { border-top-color: #2980b9; }
.skill-card.tools .skill-tag      { background: #f0f6ff; color: #004085; border-color: #b8daff; }
</style>


<div class="skills-grid">

  <!-- Cybersecurity -->
  <div class="skill-card security">
    <p class="card-title">🔐 Cybersecurity</p>
    <div class="skill-tags">
      <span class="skill-tag">Network Security</span>
      <span class="skill-tag">CPS Security</span>
      <span class="skill-tag">Cloud Security</span>
      <span class="skill-tag">AI Security</span>
      <span class="skill-tag">IAM</span>
      <span class="skill-tag">SOC Operations</span>
      <span class="skill-tag">Incident Response</span>
      <span class="skill-tag">SIEM Tools</span>
      <span class="skill-tag">Intrusion Detection (IDS)</span>
      <span class="skill-tag">Threat Intelligence</span>
    </div>
  </div>

  <!-- VA & PT Tools (CEH Certified) -->
  <div class="skill-card vapt">
    <p class="card-title">🛡️ Vulnerability Assessment & Penetration Testing</p>
    <div class="skill-tags">
      <span class="skill-tag">Metasploit</span>
      <span class="skill-tag">Nmap</span>
      <span class="skill-tag">Burp Suite</span>
      <span class="skill-tag">Wireshark</span>
      <span class="skill-tag">Nessus</span>
      <span class="skill-tag">OpenVAS</span>
      <span class="skill-tag">Nikto</span>
      <span class="skill-tag">Hydra</span>
      <span class="skill-tag">John the Ripper</span>
      <span class="skill-tag">Aircrack-ng</span>
      <span class="skill-tag">OWASP ZAP</span>
      <span class="skill-tag">K6 Load Testing</span>
    </div>
  </div>

  <!-- Cryptography & Privacy -->
  <div class="skill-card crypto">
    <p class="card-title">🔑 Cryptography & Privacy</p>
    <div class="skill-tags">
      <span class="skill-tag">AES / RSA / PKI</span>
      <span class="skill-tag">Homomorphic Encryption</span>
      <span class="skill-tag">Searchable Encryption</span>
      <span class="skill-tag">Identity-Based Encryption (IBE)</span>
      <span class="skill-tag">Zero-Knowledge Proofs</span>
      <span class="skill-tag">Differential Privacy</span>
      <span class="skill-tag">Privacy-Preserving Storage</span>
      <span class="skill-tag">Scyther (Protocol Verification)</span>
    </div>
  </div>

  <!-- Cloud & DevOps -->
  <div class="skill-card cloud">
    <p class="card-title">☁️ Cloud & DevOps</p>
    <div class="skill-tags">
      <span class="skill-tag">Oracle Cloud (OCI)</span>
      <span class="skill-tag">AWS</span>
      <span class="skill-tag">Azure</span>
      <span class="skill-tag">Terraform</span>
      <span class="skill-tag">Docker</span>
      <span class="skill-tag">Kubernetes</span>
      <span class="skill-tag">CI/CD Pipelines</span>
      <span class="skill-tag">Infrastructure as Code (IaC)</span>
    </div>
  </div>

  <!-- Machine Learning & AI -->
  <div class="skill-card ml">
    <p class="card-title">🧠 Machine Learning & AI</p>
    <div class="skill-tags">
      <span class="skill-tag">Scikit-learn</span>
      <span class="skill-tag">Random Forest</span>
      <span class="skill-tag">XGBoost</span>
      <span class="skill-tag">SVM</span>
      <span class="skill-tag">Clustering</span>
      <span class="skill-tag">Anomaly Detection</span>
      <span class="skill-tag">Federated Learning</span>
      <span class="skill-tag">Adversarial ML</span>
      <span class="skill-tag">Deep Learning</span>
      <span class="skill-tag">TensorFlow / PyTorch</span>
      <span class="skill-tag">MATLAB</span>
      <span class="skill-tag">Pandas / NumPy</span>
      <span class="skill-tag">Matplotlib / Seaborn</span>
    </div>
  </div>

  <!-- LLM & Generative AI -->
  <div class="skill-card llm">
    <p class="card-title">🤖 LLM & Generative AI</p>
    <div class="skill-tags">
      <span class="skill-tag">Large Language Models (LLMs)</span>
      <span class="skill-tag">Retrieval-Augmented Generation (RAG)</span>
      <span class="skill-tag">Prompt Engineering</span>
      <span class="skill-tag">Fine-Tuning (LoRA / PEFT)</span>
      <span class="skill-tag">LLM Security & Red Teaming</span>
      <span class="skill-tag">Defensive Architectures for LLMs</span>
      <span class="skill-tag">Vector Databases</span>
      <span class="skill-tag">Hugging Face Transformers</span>
    </div>
  </div>

  <!-- Simulation Tools -->
  <div class="skill-card simulation">
    <p class="card-title">🧪 Simulation & Verification Tools</p>
    <div class="skill-tags">
      <span class="skill-tag">NS-3</span>
      <span class="skill-tag">GridPACK</span>
      <span class="skill-tag">HELICS</span>
      <span class="skill-tag">Node-RED</span>
      <span class="skill-tag">Smart Grid Simulation</span>
      <span class="skill-tag">Scyther</span>
      <span class="skill-tag">MATLAB / Simulink</span>
      <span class="skill-tag">Time Sync Models</span>
    </div>
  </div>

  <!-- Programming -->
  <div class="skill-card programming">
    <p class="card-title">🖥️ Programming & Scripting</p>
    <div class="skill-tags">
      <span class="skill-tag">Python</span>
      <span class="skill-tag">C</span>
      <span class="skill-tag">C++</span>
      <span class="skill-tag">Java</span>
      <span class="skill-tag">JavaScript</span>
      <span class="skill-tag">Bash / Shell</span>
      <span class="skill-tag">HTML / CSS</span>
      <span class="skill-tag">Markdown</span>
    </div>
  </div>

  <!-- Academic Writing -->
  <div class="skill-card writing">
    <p class="card-title">✍️ Academic & Technical Writing</p>
    <div class="skill-tags">
      <span class="skill-tag">LaTeX</span>
      <span class="skill-tag">Overleaf</span>
      <span class="skill-tag">TeXstudio</span>
      <span class="skill-tag">Research Paper Writing</span>
      <span class="skill-tag">Technical Documentation</span>
      <span class="skill-tag">Zotero & Mendeley</span>
    </div>
  </div>

  <!-- Database & Web -->
  <div class="skill-card database">
    <p class="card-title">🗃️ Database & Web</p>
    <div class="skill-tags">
      <span class="skill-tag">MySQL</span>
      <span class="skill-tag">Oracle DB</span>
      <span class="skill-tag">PostgreSQL</span>
      <span class="skill-tag">RESTful APIs</span>
      <span class="skill-tag">WebSockets</span>
    </div>
  </div>

  <!-- Tools & Platforms -->
  <div class="skill-card tools">
    <p class="card-title">📂 Tools & Platforms</p>
    <div class="skill-tags">
      <span class="skill-tag">Git / GitHub / GitLab</span>
      <span class="skill-tag">Linux (Ubuntu / Oracle Linux)</span>
      <span class="skill-tag">VS Code</span>
      <span class="skill-tag">Jupyter Notebook</span>
      <span class="skill-tag">Google Colab</span>
      <span class="skill-tag">Wireshark</span>
      <span class="skill-tag">VirtualBox / VMware</span>
    </div>
  </div>

</div>