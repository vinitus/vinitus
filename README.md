### 안녕하세요! 👋, JS에 진심인 개발자 강신욱입니다.

<!--
**vinitus/vinitus** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
## About Me

### 자기소개

👨‍💻 머신러닝 개론 강의를 수강하며, 생각을 구현하는 것이 재밌어서 개발에 푹 빠지게 되었습니다.

🔎 화려하게 써보는 것 보다는, 어느정도 깊게 공부하려고 노력합니다.

📈 실패에서 더 나아가려고 노력합니다.

🤔 질문받는 것을 좋아합니다. 팀원이 질문하면 같이 공부하고 같이 해결하려고 노력합니다.

### Email&Blog

📧 **Email | tlsdnrng@gmail.com**

📒 **Blog | [https://github.com/vinitus](https://github.com/vinitus)**

## Skills

### Frontend

<img src="https://img.shields.io/badge/JAVASCRIPT-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white"> <img src="https://img.shields.io/badge/REACT-61DAFB?style=for-the-badge&logo=react&logoColor=white"> <img src="https://img.shields.io/badge/VUE.JS-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white"> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white">

### Backend

<img src="https://img.shields.io/badge/DJANGO-092E20?style=for-the-badge&logo=django&logoColor=white">

### etc

<img src="https://img.shields.io/badge/JIRA-0052CC?style=for-the-badge&logo=jirasoftware&logoColor=white"> <img src="https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white">


## 1️⃣ Project 1


### [ 팀프로젝트 ] 추천 서비스 프로젝트 - pnut

삼성 청년 SW아카데미 | 2023.02 ~ 2023.04

설문조사 기반으로 하여 부족한 영양소를 찾고 이 영양소가 많은 음식을 추천하는 서비스입니다.

![image](https://user-images.githubusercontent.com/97886013/232408236-ff8d2228-30d0-4c2a-8db9-e6cb7e65910a.png)

[ 사용 기술 및 도구 ]

React, react-redux, react-router, eslint, prettier, yarn, vite, JIRA

[ 기여 ]

- react를 활용한 PC 웹사이트 SPA 개발
- 복잡한 상태들을 어떻게 관리해야할까
    - 게시글 작성 페이지에서 고생했던 기억이 있습니다.
    - 컴포넌트를 나누게 되는 기준들을 다시한번 생각해볼 수 있는 계기가 되었습니다.
- eslint+prettier를 설정하여 포맷터 설정 및 package.json을 활용하여 명령어를 하나로 줄이기
- dispatch의 작동방식에 대한 이해
    - dispatch는 비동기 처리를 지원하며, 인자로 들어간 결과값으로 then 체이닝이 가능함을 알게 되었습니다.

[상세보기](https://www.notion.so/pnut-dc5f6d78f62a44ce9e68b6cb255db9aa)

## 2️⃣ Project 2


### [ 팀프로젝트 ] IOT 프로젝트 - RIF (Recycle Is Fun)

삼성 청년 SW아카데미 | 2023.01 ~ 2023.02

YOLO 모델을 활용하여 쓰레기를 분리하고 분류 정확도에 따라 리워드와 기록이 남게 됩니다. 이를 웹에서 확인하는 프로젝트입니다.

![image](https://user-images.githubusercontent.com/97886013/232408862-f1e659f9-c75a-411c-be4a-a7eefb62c556.png)

[ 사용 기술 및 도구 ]

React, react-redux, react-router, prettier, cra, JIRA

[ 기여 ]

- react를 활용한 모바일 웹 SPA 개발
- api 요청 로직 개선
    - 원래 await을 통해서 axios 요청이 끝나고 다음 요청을 동기적으로 실행하였습니다.
    - 하지만, 이벤트 루프를 생각해보니 이렇게 할 이유가 전혀 없었고 이를 해결하여 0.9초에서 0.5초로 시간을 줄일 수 있었습니다.
- JWT 토큰을 활용한 로그인 관련 로직
    - 로그인에도 생각보다 많은 공이 들어간다는 것을 알게 되었습니다.
    - Axios Interceptor를 활용하고, 에러 코드를 컨트롤하며 토큰을 재발급하였습니다.

[상세보기](https://www.notion.so/RIF-d96d70a9c24e4297b8bd593bac4eb279)

## 3️⃣ Project 3


### [ 팀프로젝트 ] 영화 추천 서비스 - WhatToWatch

삼성 청년 SW아카데미 | 2022.11 ~ 2022.11

영화 데이터를 기반으로, 코사인 유사도 알고리즘을 활용하여 영화를 추천해주는 서비스를 개발했습니다.

![image](https://user-images.githubusercontent.com/97886013/232409034-77d7d5ef-b5b8-44ec-b29b-a4d27bfe357f.png)


[ 사용 기술 및 도구 ]

Vue, Vuex, vue-router

[ 기여 ]

- DB 설계 및 유저 관련 BE API 개발하였습니다.
- UX를 위한 기능 구현, vue를 활용한 SPA 개발하였습니다.
- BE와 FE를 경험해보며, 각자의 입장에 대해서 생각할 수 있는 인사이트를 갖게 되었습니다.

[상세보기](https://www.notion.so/WhatToWatch-d5be35df4b85405c92ade7521dfb43e7)

## 교육 내역

- 2022.07 ~ 현     재    삼성 청년 SW 아카데미 8기 교육 수료 중

## 경력

- 😥
