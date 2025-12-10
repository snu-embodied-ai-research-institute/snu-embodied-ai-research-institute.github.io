---
title: 성과
nav:
  order: 7
---

<style>
.accomplish-hero {
  text-align: center;
  padding: 50px 20px;
  border-bottom: 3px solid #0c2577;
  margin-bottom: 50px;
}

.accomplish-hero h1 {
  font-size: 2em;
  margin-bottom: 15px;
  font-weight: 600;
  color: #333;
}

.accomplish-hero p {
  font-size: 1em;
  color: #666;
}

.accomplish-section {
  margin: 60px 0;
}

.accomplish-section h2 {
  color: #0c2577;
  font-size: 1.8em;
  margin-bottom: 20px;
  text-align: center;
  font-weight: 600;
}

.accomplish-section p {
  font-size: 1em;
  line-height: 1.7;
  color: #666;
  text-align: center;
  max-width: 800px;
  margin: 0 auto 30px;
}

.section-divider {
  margin: 50px 0;
  border-bottom: 1px solid #e9ecef;
}

.accomplish-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 25px;
  margin: 40px 0;
}

.accomplish-card {
  background: white;
  padding: 25px;
  border: 2px solid #e9ecef;
  border-radius: 4px;
  text-align: center;
  transition: all 0.2s ease;
}

.accomplish-card:hover {
  border-color: #0c2577;
  box-shadow: 0 2px 8px rgba(12, 37, 119, 0.1);
}

.accomplish-card h3 {
  margin-bottom: 15px;
  color: #0c2577;
  font-size: 1.3em;
  font-weight: 600;
}

.accomplish-card p {
  color: #666;
  line-height: 1.6;
}
</style>

<div class="accomplish-hero">
  <h1>성과｜체화 인공지능 연구소의 업적</h1>
</div>

{% include section.html %}

<div class="accomplish-section">
  <h2>연구소 운영실적</h2>
  
  {% include figure.html image="images/df253cd104d7359da0b299750d3f499b.jpg" %}
</div>

<div class="section-divider"></div>

{% include section.html %}

<div class="accomplish-section">
  <h2>특성화·전문화 추진 실적</h2>
  
  {% include figure.html image="images/a30309c6ed7d6059feabaa43ee6038db.jpg" %}
</div>

<div class="section-divider"></div>

{% include section.html %}

<div class="accomplish-section">
  <h2>인공지능 연구 실적</h2>
  
  {% include figure.html image="images/dcd12323e022cbdcb219d88d305d6abf.jpg" %}
</div>

<div class="section-divider"></div>

{% include section.html %}

<div class="accomplish-section">
  <h2>인공지능 산학 실적</h2>
  
  {% include figure.html image="images/6b0c088188b8e3261affa6d0f5eb2281.jpg" %}
</div>

<div class="section-divider"></div>

{% include section.html %}

<div class="accomplish-section">
  <h2>연구 공유 실적</h2>
  
  {% include figure.html image="images/298e3d6847ae3007589a2137d903fcdb.jpg" %}
</div>

<div class="section-divider"></div>

{% include section.html %}

<div class="accomplish-section">
  <h2>인재 양성 실적</h2>
  
  {% include figure.html image="images/b90f7b9f99b689c52e5dd57fa1f4d010.jpg" %}
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

