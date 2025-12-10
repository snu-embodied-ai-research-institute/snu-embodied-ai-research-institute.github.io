---
title: 시설 및 장비
nav:
  order: 9
---

<style>
.facilities-hero {
  text-align: center;
  padding: 50px 20px;
  border-bottom: 3px solid #0c2577;
  margin-bottom: 50px;
}

.facilities-hero h1 {
  font-size: 2em;
  margin-bottom: 15px;
  font-weight: 600;
  color: #333;
}

.facilities-hero p {
  font-size: 1em;
  color: #666;
}

.facilities-section {
  margin: 60px 0;
}

.facilities-section h2 {
  color: #0c2577;
  font-size: 1.8em;
  margin-bottom: 20px;
  text-align: center;
  font-weight: 600;
}

.facilities-section p {
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

.building-info {
  max-width: 800px;
  margin: 40px auto;
  padding: 30px;
  background: white;
  border: 2px solid #e9ecef;
  border-radius: 4px;
}

.building-info h3 {
  color: #0c2577;
  font-size: 1.4em;
  margin-bottom: 15px;
  font-weight: 600;
}

.building-info p {
  color: #666;
  line-height: 1.7;
  margin: 10px 0;
  text-align: left;
}

.equipment-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
  margin: 40px 0;
}

.equipment-card {
  background: #f8f9fa;
  padding: 30px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  text-align: center;
}

.equipment-card h3 {
  color: #0c2577;
  font-size: 1.3em;
  margin-bottom: 15px;
}

.equipment-card p {
  color: #666;
  line-height: 1.6;
}
</style>

<div class="facilities-hero">
  <h1>시설 및 장비｜체화 인공지능 연구소의 자원</h1>
</div>

{% include section.html %}

<div class="facilities-section">
  <h2>연구 시설</h2>
  
  <div class="building-info">
    <h3>서울대학교 해동첨단공학관</h3>
    <p><strong>주소</strong>｜서울 관악구 관악로 1 서울대학교, 303동</p>
    <p><strong>완공</strong>｜2024.04</p>
    <p><strong>규모</strong>｜3000여 평의 연구공간 확보</p>
    <br/>
    <p>
      최첨단 연구 인프라를 갖춘 해동첨단공학관에서 
      체화 인공지능 연구를 수행하고 있습니다.
    </p>
  </div>
</div>

<div class="section-divider"></div>

{% include section.html %}

<div class="facilities-section">
  <h2>연구 장비 보유 현황</h2>
  
  <div style="margin: 40px 0;">
    {% include figure.html image="images/38b266e69ef77c3e1f888f464a17e147.jpg" caption="**Servers & GPUs** | 계산용 서버 다수, 연구용 GPU 300여개" %}
  </div>
  
  <div style="margin: 40px 0;">
    {% include figure.html image="images/edd4a2b6bd0e7acf8c17c34c66d21554.jpg" caption="**TurtleBot3 Burger (4EA)** | 경로 Planning 검증용 소형 모바일 로봇" %}
  </div>
  
  <div style="margin: 40px 0;">
    {% include figure.html image="images/560b088c954beae9090e20e2c899baa6.jpg" caption="**Fetch OEM Base (1EA)** | 경로 Planning 검증용 대형 모바일 로봇" %}
  </div>
  
  <div style="margin: 40px 0;">
    {% include figure.html image="images/17861ddf769a6129956e6112c1501e5a.jpg" caption="**MiR 로봇 (1EA)** | 최적 주행경로 검증용 모바일 로봇" %}
  </div>
  
  <div style="margin: 40px 0;">
    {% include figure.html image="images/0bde25eab2466c14f5512c5b71ef9b05.jpg" caption="**UR5 (3EA)** | 조작 수행용 로봇 팔, 최대 하중 5kg" %}
  </div>
  
  <div style="margin: 40px 0;">
    {% include figure.html image="images/e6661376085df187faadcfbdd037e764.jpg" caption="**Kinova Gen2 (2EA)** | 시나리오 수행용 로봇 팔, 최대 하중 5kg" %}
  </div>
  
  <div style="margin: 40px 0;">
    {% include figure.html image="images/1c6c17bd04a23cb6e3c5609d123d4033.jpg" caption="**Sawyer (1EA)** | 시나리오 수행용 로봇 팔, 최대 하중 4kg" %}
  </div>
  
  <div style="margin: 40px 0;">
    {% include figure.html image="images/592e1bd758c26bc3374c9b9bb32c417e.jpg" caption="**Allegro Hand (1EA)** | 적응적 파지 수행용 로봇 손" %}
  </div>
  
  <div style="margin: 40px 0;">
    {% include figure.html image="images/f6ad3d079226e0158d674eb2e8e3ce2c.jpg" caption="**Kinova Gen3 lite (1EA)** | 시나리오 수행용 로봇 팔, 최대 하중 5kg" %}
  </div>
  
  <div style="margin: 40px 0;">
    {% include figure.html image="images/1bba76898c4a5016720bc73ff3318663.jpg" caption="**Softbank Pepper (4EA)** | 인간과의 소통에 특화된 휴머노이드 로봇" %}
  </div>
  
  <div style="margin: 40px 0;">
    {% include figure.html image="images/13a120882c75ef7f202c7ca03a54ee43.jpg" caption="**토카비 (1EA)** | 자체 개발 휴머노이드 아바타 / 이족 보행 로봇" %}
  </div>
  
  <div style="margin: 40px 0;">
    {% include figure.html image="images/edeef586d6281ba28e83af4bac6501fc.jpg" caption="**모바일 매니퓰레이터 (1EA)** | Franka 와 Husky를 결합한 모바일 조작 로봇" %}
  </div>
  
  <div style="margin: 40px 0;">
    {% include figure.html image="images/toyota-hsr.jpg" caption="**Toyota HSR (1EA)** | 물체 운반 및 의사소통용 모바일 조작 로봇" %}
  </div>
  
  <div style="margin: 40px 0;">
    {% include figure.html image="images/1ed90f42771e9cf9e5d22c4422f6dd53.jpg" caption="**Mobile ALOHA (1EA)** | Teleoperation 실험용 모바일 조작 로봇" %}
  </div>
</div>

{% include section.html %}

<div style="text-align: center; margin-top: 60px;">
  <p style="color: #666; font-size: 1.1em; line-height: 1.8; max-width: 600px; margin: 0 auto 30px;">
    최첨단 시설과 장비를 기반으로 
    세계 수준의 체화 인공지능 연구를 수행하고 있습니다.
  </p>
  
  {%
    include button.html
    link="/"
    text="홈으로 돌아가기"
    icon="fa-solid fa-home"
    style="button"
  %}
</div>

