---
title: 비전
nav:
  order: 2
---

<style>
.vision-hero {
  text-align: center;
  padding: 50px 20px;
  border-bottom: 3px solid #0c2577;
  margin-bottom: 50px;
}

.vision-hero h2 {
  font-size: 0.9em;
  margin-bottom: 20px;
  font-weight: 400;
  color: #0c2577;
  letter-spacing: 1px;
}

.vision-hero h1 {
  font-size: 1.9em;
  margin: 0;
  font-weight: 600;
  line-height: 1.6;
  color: #333;
}

.vision-content {
  margin: 50px 0;
  text-align: center;
}

.vision-content h2 {
  color: #0c2577;
  font-size: 1.8em;
  margin-bottom: 20px;
  font-weight: 600;
}

.vision-content p {
  font-size: 1em;
  line-height: 1.7;
  color: #666;
  margin-bottom: 30px;
  max-width: 700px;
  margin-left: auto;
  margin-right: auto;
}

.section-divider {
  margin: 60px 0;
  border-bottom: 2px solid #eee;
}

.subsection-links {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
  margin: 40px 0;
}

.subsection-card {
  background: white;
  padding: 30px;
  border: 2px solid #e9ecef;
  border-radius: 4px;
  text-align: center;
  transition: all 0.2s ease;
}

.subsection-card:hover {
  border-color: #0c2577;
  box-shadow: 0 2px 8px rgba(12, 37, 119, 0.1);
}

.subsection-card h3 {
  margin-bottom: 12px;
  color: #0c2577;
  font-size: 1.3em;
  font-weight: 600;
}

.subsection-card p {
  color: #666;
  line-height: 1.6;
  margin-bottom: 20px;
  font-size: 0.95em;
}
</style>

<div class="vision-hero">
  <h2>비전 | 체화 인공지능 연구소의 미래</h2>
</div>

{% include section.html %}

<div class="vision-content">
  <h2>체화 인공지능 연구소의 비전</h2>
  
  {% include figure.html image="images/vision-main.jpg" %}
  
  <p style="margin-top: 40px;">
    서울대학교 체화 인공지능 연구소는 실세계에서 인간과 상호작용하며 끊임없이 배워나가는 
    체화된 인공지능 기술을 개발하여, 인류의 삶의 질을 향상시키는 것을 목표로 합니다.
  </p>
  
  <p>
    우리는 닫힌 세계가 아닌 실제 세계에 적용 가능한 인공지능을 연구하며,
    학제간 연계를 통해 세계적 수준의 원천기술을 개발하고자 합니다.
  </p>
</div>

<div class="section-divider"></div>

{% include section.html %}

<h2 style="text-align: center; margin-bottom: 40px; color: #741b47;">세부 계획</h2>

<div class="subsection-links">
  <div class="subsection-card">
    <h3>운영 및 연구 계획</h3>
    <p>연구소의 운영 방향과 주요 연구 계획을 확인하세요</p>
    {%
      include button.html
      link="researchplans"
      text="자세히 보기"
      icon="fa-solid fa-arrow-right"
      style="button"
    %}
  </div>
  
  <div class="subsection-card">
    <h3>연구소 발전 계획</h3>
    <p>연구소의 중장기 발전 로드맵을 살펴보세요</p>
    {%
      include button.html
      link="labplans"
      text="자세히 보기"
      icon="fa-solid fa-arrow-right"
      style="button"
    %}
  </div>
  
  <div class="subsection-card">
    <h3>과제 추진 전략</h3>
    <p>주요 연구 과제와 추진 전략을 알아보세요</p>
    {%
      include button.html
      link="projectplans"
      text="자세히 보기"
      icon="fa-solid fa-arrow-right"
      style="button"
    %}
  </div>
</div>

{% include section.html %}

<div style="text-align: center; margin-top: 60px;">
  {%
    include button.html
    link="/"
    text="홈으로 돌아가기"
    icon="fa-solid fa-home"
    style="button"
  %}
</div>

