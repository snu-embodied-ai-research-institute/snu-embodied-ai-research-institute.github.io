---
title: 구성원
nav:
  order: 8
---

<style>
.people-hero {
  text-align: center;
  padding: 50px 20px;
  border-bottom: 3px solid #0c2577;
  color: #333;
  margin-bottom: 50px;
  
}

.people-hero h1 {
  font-size: 1.8em;
  margin-bottom: 15px;
  font-weight: 600;
}

.people-hero p {
  font-size: 1em;
  
}

.section-divider {
  margin: 50px 0;
  border-bottom: 1px solid #e9ecef;
}

.director-section {
  max-width: 900px;
  margin: 60px auto;
  padding: 40px;
  background: white;
  
  border: 2px solid #e9ecef;
}

.director-section h2 {
  color: #0c2577;
  font-size: 1.8em;
  margin-bottom: 20px;
  text-align: center;
}

.director-info h3 {
  color: #333;
  font-size: 1.5em;
  margin: 20px 0 10px;
}

.director-info p {
  color: #666;
  line-height: 1.8;
  margin: 10px 0;
}

.faculty-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 30px;
  margin: 40px 0;
}

.faculty-card {
  background: white;
  padding: 30px;
  
  border: 2px solid #e9ecef;
}

.faculty-card h3 {
  color: #0c2577;
  font-size: 1.5em;
  margin-bottom: 10px;
}

.faculty-card h4 {
  color: #333;
  font-size: 1em;
  margin-bottom: 15px;
}

.faculty-card p {
  color: #666;
  line-height: 1.6;
  margin: 5px 0;
}

.researchers-section {
  margin: 50px 0;
}

.researchers-section h2 {
  color: #0c2577;
  font-size: 1.8em;
  margin-bottom: 30px;
  text-align: center;
}

.researcher-list {
  max-width: 800px;
  margin: 0 auto;
}

.researcher-item {
  background: white;
  padding: 20px;
  margin-bottom: 15px;
  border-radius: 8px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.researcher-item strong {
  color: #0c2577;
  font-size: 1.1em;
}

.researcher-item span {
  color: #666;
}
</style>

<div class="people-hero">
  <h1>구성원｜체화 인공지능 연구소의 연구진</h1>
</div>

{% include section.html %}

<div class="director-section">
  <h2>연구 책임자</h2>
  
  {% include figure.html image="images/bb3fcbd4f9af4d7027f908e1cd98ffc9.jpg" %}
  
  <div class="director-info">
    <h3>장 병 탁 교수</h3>
    <p><strong>서울대학교 AI 연구원(AIIS) 원장</strong></p>
    
    <h4>학력</h4>
    <p>• 1988｜서울대학교 컴퓨터공학과 학사 및 석사</p>
    <p>• 1992｜Universität Bonn (본 대학교), 컴퓨터과학 박사</p>
    
    <h4>경력</h4>
    <p>• 1997｜서울대학교 컴퓨터공학부, 뇌과학/인지과학/인공지능 협동과정 교수</p>
    <p>• (전)서울대학교 인지과학연구소장, 정보과학회 인공지능소사이어티 회장</p>
    
    <h4>연구 성과</h4>
    <p>• H-index: 54, 총인용지수: 15896 (Google Scholar Citation 2024.11 기준)</p>
    <p>• 한국공학한림원 회원(2021)</p>
    <p>• 비디오 튜링 테스트 개최(2021)</p>
    <p>• 국가연구개발사업 우수 성과 100선 선정(2018)</p>
    <p>• 홍조근정훈장 수훈 (2017)</p>
    <p>• 국가연구개발사업 우수 성과 50선 선정(2013)</p>
    <p>• 교육과학부 장관상 수상(2008)</p>
    <p>• 국가지정연구실(NRL) 우수과제 선정(2007)</p>
    <p>• Okawa 연구상 수상(2007)</p>
    
    <h4>연구분야</h4>
    <p>뇌인지기반 인공지능 및 기계학습, 멀티모달 학습 및 복합 지식정보 추출</p>
  </div>
</div>

<div class="section-divider"></div>

{% include section.html %}

<h2 style="text-align: center; color: #0c2577; font-size: 2em; margin-bottom: 50px;">교수진</h2>

{% include figure.html image="images/436e6c0e493d502be745db558eee118c.jpg" %}

{% include figure.html image="images/310895836b8f080fb0f6f38e6148bf89.jpg" %}

{% include figure.html image="images/eebe6444895e3366cf3befc295639e41.jpg" %}

{% include figure.html image="images/72c482265dce88b73b8eabca88928df3.jpg" %}

{% include figure.html image="images/5e063c608429cbd9356708ec3204207b.jpg" %}

<div class="section-divider"></div>

{% include section.html %}

<div class="researchers-section">
  <h2>핵심 연구 교수</h2>
  <div class="researcher-list">
    <div class="researcher-item">
      <div>
        <strong>이민수 박사</strong>
      </div>
      <div>
        <span>비디오 이해 능동학습, 실세계 응용을 위한 강화학습</span>
      </div>
    </div>
    
    <div class="researcher-item">
      <div>
        <strong>이준기 박사</strong>
      </div>
      <div>
        <span>설명 가능한 인공지능 및 강화학습, 인간-로봇 상호작용</span>
      </div>
    </div>
    
    <div class="researcher-item">
      <div>
        <strong>김인영 박사</strong>
      </div>
      <div>
        <span>대용량 데이터 패턴 분석 및 모델링을 위한 인공지능</span>
      </div>
    </div>
  </div>
</div>

<div class="section-divider"></div>

{% include section.html %}

<div class="researchers-section">
  <h2>핵심 연구원</h2>
  <div class="researcher-list">
    <div class="researcher-item">
      <div>
        <strong>정지오 박사</strong>
      </div>
      <div>
        <span>DAQ, 로보틱스 및 협업 멀티 에이전트 학습 기술</span>
      </div>
    </div>
    
    <div class="researcher-item">
      <div>
        <strong>이종현 박사</strong>
      </div>
      <div>
        <span>뇌파 데이터를 활용한 감정, 추상 개념, 발화 의도 이해</span>
      </div>
    </div>
  </div>
</div>

<div class="section-divider"></div>

{% include section.html %}

<div class="researchers-section">
  <h2>학생 연구원</h2>
  <p style="text-align: center; color: #999; font-size: 1.1em;">
    우수한 학생 연구원들이 체화 인공지능 연구에 참여하고 있습니다.
  </p>
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

