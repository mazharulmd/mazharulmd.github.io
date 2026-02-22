---
title: "Education"
layout: single
permalink: /education/
author_profile: true
---

<style>
.edu-card {
  border: 1px solid #e0e0e0;
  border-radius: 10px;
  padding: 24px 28px;
  margin-bottom: 24px;
  background: #fff;
  box-shadow: 0 2px 8px rgba(0,0,0,0.06);
  border-left: 5px solid #4a90d9;
  transition: box-shadow 0.2s ease;
}
.edu-card:hover {
  box-shadow: 0 4px 16px rgba(0,0,0,0.12);
}
.edu-card.school {
  border-left-color: #28a745;
}
.edu-card .degree {
  font-size: 1.05em;
  font-weight: 700;
  color: #1a1a1a;
  margin: 0 0 4px 0;
}
.edu-card .university {
  font-size: 0.95em;
  font-weight: 600;
  color: #4a90d9;
  margin: 0 0 8px 0;
}
.edu-card.school .university {
  color: #28a745;
}
.edu-card .meta {
  font-size: 0.85em;
  color: #666;
  margin: 0 0 10px 0;
}
.edu-card .meta span {
  margin-right: 16px;
}
.edu-cgpa {
  display: inline-block;
  background: #d4edda;
  color: #155724;
  border: 1px solid #c3e6cb;
  border-radius: 20px;
  padding: 2px 12px;
  font-size: 0.82em;
  font-weight: 600;
  margin-bottom: 0;
}
.edu-thesis {
  background: #f0f6ff;
  border-left: 3px solid #4a90d9;
  border-radius: 4px;
  padding: 10px 14px;
  margin-top: 14px;
  font-size: 0.88em;
}
.edu-thesis .thesis-label {
  font-weight: 700;
  color: #333;
  margin-bottom: 3px;
}
.edu-thesis .thesis-desc {
  margin-top: 6px;
  color: #555;
  line-height: 1.5;
}
.edu-thesis .supervisor {
  margin-top: 6px;
  color: #555;
}
</style>


<!-- MSc -->
<div class="edu-card">
  <p class="degree">🎓 Master of Science in Computer Science and Engineering (MSc)</p>
  <p class="university">North South University</p>
  <p class="meta">
    <span>📍 Dhaka, Bangladesh</span>
    <span>📆 Graduated: Summer 2020</span>
  </p>
  <span class="edu-cgpa">CGPA: 3.97 / 4.00 &nbsp;·&nbsp; ≈ 99 / 100 &nbsp;·&nbsp; First-Class Standing</span>
  <div class="edu-thesis">
    <div class="thesis-label">📄 Thesis:</div>
    <div>
      <a href="/publication/masters-thesis-encrypted-cloud-storage" target="_blank" style="font-style:italic;">
        "A Practical Framework for Storing and Searching Encrypted Data on Cloud Storage"
      </a>
    </div>
    <div class="thesis-desc">
      Designed and implemented <strong>CryptoSearch</strong>, a secure and searchable encryption
      framework for cloud storage using symmetric cryptography with Identity-Based Encryption (IBE).
      The system enables efficient single and multi-keyword search over encrypted data while preserving
      user privacy, minimizing key-management overhead, and ensuring plaintext is never exposed to the
      storage provider. Also developed a web application as an overlay system on a cloud storage domain,
      demonstrating low response time and scalability.
    </div>
    <div class="supervisor">
      <strong>Supervisor:</strong>
      <a href="https://ece.northsouth.edu/people/rajesh-palit/" target="_blank">Dr. Rajesh Palit</a>
    </div>
  </div>
</div>


<!-- BSc -->
<div class="edu-card">
  <p class="degree">🎓 Bachelor of Science in Computer Science and Engineering (BSc)</p>
  <p class="university">North South University</p>
  <p class="meta">
    <span>📍 Dhaka, Bangladesh</span>
    <span>📆 Graduated: Summer 2018</span>
  </p>
  <span class="edu-cgpa">CGPA: 3.24 / 4.00 &nbsp;·&nbsp; ≈ 81 / 100</span>
</div>


<!-- HSC -->
<div class="edu-card school">
  <p class="degree">📘 Higher Secondary Certificate (HSC) — Science</p>
  <p class="university">Ansar VDP School & College</p>
  <p class="meta">
    <span>📍 Gazipur, Bangladesh</span>
    <span>📆 Year: 2013</span>
  </p>
  <span class="edu-cgpa">GPA: 5.00 / 5.00 &nbsp;·&nbsp; Perfect Score</span>
</div>


<!-- SSC -->
<div class="edu-card school">
  <p class="degree">📗 Secondary School Certificate (SSC) — Science</p>
  <p class="university">Ansar VDP High School</p>
  <p class="meta">
    <span>📍 Gazipur, Bangladesh</span>
    <span>📆 Year: 2011</span>
  </p>
  <span class="edu-cgpa">GPA: 5.00 / 5.00 &nbsp;·&nbsp; Perfect Score</span>
</div>