**프로젝트 개요**

**velog:**  https://velog.io/@jongsunpark88/projectW2

<br>

**프로젝트를 마치며**

**velog:**  https://velog.io/@jongsunpark88/projectW2me

<br>

<br>

## 프로젝트 :  https://www.wanted.co.kr/ Clone Coding

- **원본 레파지토리:  https://github.com/wecode-bootcamp-korea/Wepick-frontend** 

  

- 코딩 6주차 WeCode 8기 수강생들의 2주 클론 프로젝트입니다.

- 프론트엔드 3명과 백엔드 2명이 팀을 이뤄 개발했습니다.

<br>

## 목표

- 학습한 React를 활용하여 실제 웹사이트처럼 구현하기.
- 새롭게 배운 **스타일 컴포넌트, Hook 그리고 Redux**를 활용하여 프로젝트를 만들기.

<br>

## 사용된 기술

- Front-End: **ReactJS**, **Styled Componenet**, **hook**, **Redux**
- Back-End: **Django**, **MySQL** ([Back-End Repository 주소]( https://github.com/wecode-bootcamp-korea/Wepick-backend ))
- Deployment: **AWS**

<br>

## 기능

**1.  회원가입 및 로그인 구현** 
- google소셜 로그인: 
  프론트에서 구글로 유저의 정보를 보내고 토큰을 받는다. 그 토큰을 다시  백엔드로 보내어 백엔드에서 발행하는 토큰으로 교환한다.  그 후 백엔드에서 발행한 토큰을 이용하여 회원정보를 확인한다.

- 일반 로그인은 3단계로 구성되어있다.  최초 이메일만 확인 후 회원, 비회원에 따라 로그인modal, 또는 회원가입modal로 유도한다.

  <br>

**2. 페이지 이동시에도 회원정보 유지 및 로그인 상태에 따른 페이지 변화**
- 최초 로그인 후 에는 페이지가 변해도 로그인 정보를 유지해야 하며 페이지에서는 로그인 유무에 따라서 페이지에도 제공하는 정보나 사용할 수 있는 UI등이 변한다.

  <br>

**3. main List페이지**
- 백엔드로부터 받은 데이터를 리스트형태로 보여지며 category에 변화에 따라 보여지는 정보가 바뀐다.

  <br>

**4. main detail**
- list 목록으로부터 detail로 이동하여 detail 정보를 제공한다.

  <br>

**5. 이력서 페이지**

- 이력서를 작성, 삭제, 해당 유저의 기존 데이터를 불러오기를 제공한다.

<br>

## 구현 화면

 https://www.youtube.com/watch?v=3sZc05pvuCY 

