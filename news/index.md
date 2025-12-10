---
title: 소식
nav:
  order: 6
---

<style>
.news-hero {
  text-align: center;
  padding: 50px 20px;
  border-bottom: 3px solid #0c2577;
  margin-bottom: 50px;
}

.news-hero h1 {
  font-size: 2em;
  margin: 0;
  font-weight: 600;
  color: #333;
}

.news-section {
  margin: 60px 0;
  text-align: center;
}

.news-section h2 {
  color: #0c2577;
  font-size: 1.8em;
  margin-bottom: 30px;
  font-weight: 600;
}

.news-item {
  max-width: 800px;
  margin: 40px auto;
  padding: 30px;
  background: white;
  border: 2px solid #e9ecef;
  border-radius: 4px;
  text-align: left;
}

.news-item h3 {
  color: #0c2577;
  font-size: 1.5em;
  margin-bottom: 15px;
  font-weight: 600;
}

.news-item p {
  font-size: 1em;
  line-height: 1.7;
  color: #666;
  margin: 10px 0;
}

.section-divider {
  margin: 50px 0;
  border-bottom: 1px solid #e9ecef;
}
</style>

<div class="news-hero">
  <h1>소식｜체화 인공지능 연구소의 소식</h1>
</div>

{% include section.html %}

<div class="news-section">
  <h2>새 소식</h2>
  
  <div class="news-item">
    <h3>서울대학교 해동첨단공학관 완공</h3>
    
    {% include figure.html image="images/news-haedong-building.jpg" %}
    
    <p>서울대학교 해동첨단공학관이 4월 29일 완공되었다.</p>
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
