---
title: 홈
---

<style>
.hero-section {
  text-align: center;
  padding: 50px 20px;
  border-bottom: 3px solid #0c2577;
  margin-bottom: 50px;
}

.hero-section h2 {
  font-size: 0.9em;
  margin-bottom: 15px;
  font-weight: 400;
  color: #0c2577;
  letter-spacing: 1px;
}

.hero-section h1 {
  font-size: 2em;
  margin-bottom: 15px;
  font-weight: 600;
  color: #333;
}

.hero-section p {
  font-size: 1.1em;
  font-style: italic;
  color: #666;
}

.content-section {
  margin: 60px 0;
  text-align: center;
}

.content-section h2 {
  color: #0c2577;
  font-size: 1.8em;
  margin-bottom: 15px;
  font-weight: 600;
}

.content-section h1 {
  color: #0c2577;
  font-size: 2em;
  margin-bottom: 15px;
  font-weight: 600;
}

.content-section p {
  font-size: 1em;
  color: #666;
  margin-bottom: 30px;
}

.section-divider {
  margin: 50px 0;
  border-bottom: 1px solid #e9ecef;
}

.info-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 25px;
  margin: 40px 0;
}

.info-card {
  background: white;
  padding: 25px;
  border: 2px solid #e9ecef;
  border-radius: 4px;
  transition: all 0.2s ease;
}

.info-card:hover {
  border-color: #0c2577;
  box-shadow: 0 2px 8px rgba(12, 37, 119, 0.1);
}

.info-card h3 {
  margin-bottom: 15px;
  color: #0c2577;
}

.info-card p {
  color: #666;
  line-height: 1.6;
}
</style>

<div class="hero-section">
  <h2>｜체화 인공지능 연구소｜</h2>
  <h1>사람과 함께하는 체화 인공지능 기술 개발</h1>
  <p>Embodied Artificial Intelligence Research for Human-Robot Collaboration</p>
</div>

{% include section.html %}

<div class="content-section">
  <h2>닫힌 세계가 아닌 실제 세계에 적용가능한 인공지능을 향해</h2>
  <p>실세계에서 인간과 상호작용하며 끊임없이 배워나가는, 체화된 AI를 목표로 연구합니다.</p>
</div>

<div class="section-divider"></div>

{% include section.html %}

<div class="content-section">
  <h1>인공지능은 필수기반 국가전력기술</h1>
  <p>최근 인공지능은 모든 산업에 적용되고 있으므로, AI 기술경쟁력이 곧 기업과 국가 기술 경쟁력의 척도가 될 것입니다.</p>
  
  {% include figure.html image="images/home-ai-technology.jpg" %}
</div>

<div class="section-divider"></div>

{% include section.html %}

<div class="content-section">
  <h1>체화 인공지능으로 기술 고도화 필요</h1>
  <p>알고리즘 기반 기존 로봇 인공지능에서 <strong>체화 인공지능</strong>으로 진화를 통해, 전 세계적인 AI 경쟁에서 선도적인 역할을 주도할 수 있습니다.</p>
  
  {% include figure.html image="images/home-embodied-ai.jpg" %}
</div>

{% include section.html %}

<div class="info-grid">
  <div class="info-card">
    {%
      include button.html
      link="vision"
      text="비전 및 계획"
      icon="fa-solid fa-lightbulb"
      flip=false
      style="button"
    %}
    <p style="margin-top: 15px;">연구소의 비전과 발전 계획을 확인하세요</p>
  </div>
  
  <div class="info-card">
    {%
      include button.html
      link="team"
      text="구성원"
      icon="fa-solid fa-users"
      flip=false
      style="button"
    %}
    <p style="margin-top: 15px;">연구소의 연구진을 만나보세요</p>
  </div>
  
  <div class="info-card">
    {%
      include button.html
      link="research"
      text="연구 성과"
      icon="fa-solid fa-flask"
      flip=false
      style="button"
    %}
    <p style="margin-top: 15px;">최신 연구 성과를 확인하세요</p>
  </div>
</div>
