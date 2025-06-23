---
layout: home
title: Home
sidebar:
  enabled: true

show_recent_posts: false

---

<div style="
    display: grid;
    grid-template-columns: auto 150px 1fr;
    align-items: start;
    gap: 0;
    margin-bottom: 1rem;
  ">
  <!-- 1) 프로필 이미지 (첫번째 컬럼) -->
  <img src="/assets/images/me.jpg" alt="프로필"
       style="
         width: 100px;
         height: 100px;
         object-fit: cover;
         border-radius: 50%;
       " />

  <!-- 2) 빈 컬럼 (150px 고정 여백) -->
  <div></div>

  <!-- 3) 본문 텍스트 (세번째 컬럼) -->
  <div>
    안녕하세요, 소프트웨어를 전공 중인 학부생 박찬우입니다.<br><br>
    데이터 분석, 특히 금융 데이터 분석에 관심이 많습니다.<br><br>
    이곳에서는 학부 과정에서 공부한 내용과<br>
    금융 데이터를 활용한 분석 결과를 공유합니다.
  </div>
</div>

<!-- Recent Posts 섹션 헤더 -->
## Recent Posts

<!-- 네비게이션 링크 바 -->
<nav style="margin: 1.5rem 0; font-weight: bold;">
  <a href="{{ "/" | relative_url }}">홈</a> |
  <a href="{{ "/about/" | relative_url }}">소개</a> |
  <a href="{{ "/projects/" | relative_url }}">프로젝트</a> |
  <a href="{{ "/trading-log/" | relative_url }}">매매일지</a>
</nav>


<!-- 실제 포스트 리스트는 theme이 자동으로 렌더링합니다 -->
