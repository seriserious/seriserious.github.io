---
layout: home
title: Home
sidebar:
   enabled: true
---
<!-- Flex 컨테이너: 가로 정렬 -->
<div style="display: flex; align-items: flex-start; margin-bottom: 1rem;">

  <!-- 1) 이미지 영역: 좌측으로 약간 음수 마진 -->
  <img src="/assets/images/me.jpg" alt="프로필"
       style="
         width: 100px;
         height: 100px;
         object-fit: cover;
         border-radius: 50%;
         margin-left: -50px;  /* 숫자를 키우면 더 왼쪽으로! */
         margin-right: 1rem;  /* 텍스트와 간격 */
       " />

  <!-- 2) 텍스트 영역: flex-grow 로 남은 공간 차지 -->
  <div style="flex: 1;">
    안녕하세요, 소프트웨어를 전공 중인 학부생 박찬우입니다.  
    데이터 분석, 특히 금융 데이터 분석에 관심이 많습니다.

    이곳에서는 학부 과정에서 공부한 내용과  
    금융 데이터를 활용한 분석 결과를 공유합니다.
  </div>
</div>


<!-- 안녕하세요, 소프트웨어를 전공 중인 학부생 박찬우입니다.  
데이터 분석, 특히 금융 데이터 분석에 관심이 있습니다.

이곳에서는 학부 과정에서 공부한 내용과  
금융 데이터를 활용한 분석 결과를 공유합니다. -->
