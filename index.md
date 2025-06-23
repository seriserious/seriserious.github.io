---
layout: home
title: Home
sidebar:
   enabled: true
---
<div style="position: relative;">
  <!-- 1) 이미지를 절대 위치로 띄워서 텍스트 흐름에 영향 주지 않음 -->
  <img src="/assets/images/me.jpg" alt="프로필"
       style="
         position: absolute;
         left: -20px;     /* 원하는 만큼 왼쪽으로 꺼내세요 */
         top: 0;
         width: 100px;
         height: 100px;
         object-fit: cover;
         border-radius: 50%;
       " />

  <!-- 2) 텍스트는 그대로 아래 블록에서 렌더링 -->
  <div style="margin-left: 0; /* float 같은 여백 없음 */">


안녕하세요, 소프트웨어를 전공 중인 학부생 박찬우입니다.  
데이터 분석, 특히 금융 데이터 분석에 관심이 있습니다.

이곳에서는 학부 과정에서 공부한 내용과  
금융 데이터를 활용한 분석 결과를 공유합니다.
