---
layout: post
title: "Google Analytics 기능 추가하기" 
date: 2022-11-26 20:34:09 +0900
categories: jekyll update
comments: true
---

## 1. Google Analytics 계정 생성하기

![image](https://user-images.githubusercontent.com/104906731/204795077-6463d84e-0ad2-4234-9b31-9af18817cce1.png)
- 측정 시작 버튼을 누릅니다.

![image](https://user-images.githubusercontent.com/104906731/204795310-63d1abf4-d7a4-47d2-a0db-c5e8b1a0ceac.png)
- 계정 설정을 하고 다음 버튼을 누릅니다.

![image](https://user-images.githubusercontent.com/104906731/204795751-045e7cb7-cb36-440e-8cee-2765825a54d0.png)
- 속성 설정을 하고 다음 버튼을 누릅니다. 

![image](https://user-images.githubusercontent.com/104906731/204795956-134b4e6d-59ae-4b8d-a2d3-aed285f84efb.png)
- 비지니스 정보를 입력하고 만들기 버튼을 누릅니다.

## 2. Git Blog와 Google Analytics 연동하기

![image](https://user-images.githubusercontent.com/104906731/204796674-e8e19b04-aead-4bc4-9b23-ddca224c443d.png)
- 등록을 완료한 다음 관리로 이동하고 데이터 스트림으로 이동한 뒤 플랫폼 선택 창에서 웹을 선택합니다.

![image](https://user-images.githubusercontent.com/104906731/204797154-91ff8dcd-e34e-4c97-8690-35a5df77afc4.png)
- 웹사이트 URL에 Git Blog의 주소(kossseonghyeok.github.io)를 입력하고 스트림의 이름을 입력한 뒤 스트림을 만듭니다.

![_](https://user-images.githubusercontent.com/104906731/204798157-eff268dc-e527-449e-beec-9a006c5c5eb1.png)
- 만든 뒤 태그 안내 보기로 들어갑니다.

![__](https://user-images.githubusercontent.com/104906731/204798665-cddd676d-1a53-4833-845b-44845a43ff31.png)
- 직접 설치를 클릭한 뒤 Google 태그를 복사합니다.

![___](https://user-images.githubusercontent.com/104906731/204799458-a2b31775-cbb3-46ea-82c2-0cade269f5c0.png)
- _layouts 폴더 내의 default.html의 <body> 위에 다음과 같이 붙여넣어줍니다.

![image](https://user-images.githubusercontent.com/104906731/204799819-329c6efd-5a55-4e04-baea-83d511f59395.png)
- 그리고 Git에 add, commit, push를 한 뒤 사이트에 접속하고나서 Google Analytics에 접속하면 다음과 같이 정상적으로 Git BLOG와 Google Analytics가 연동되었음을 알 수 있습니다.

