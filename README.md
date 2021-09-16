

# DRIP Frontend

다양한 체험을 제공하는 [Frip](https://www.frip.com)을 모티브로 한 프로젝트

<img width="486" alt="DRIP_메인페이지" src="https://user-images.githubusercontent.com/67620484/125184605-288a0500-e25a-11eb-9d49-0c802de12536.png">
<br>

## 프로젝트 계획 및 기간

📆 2021.06.21 ~ 07.02

- 1st Sprint : 개발환경 초기세팅, 전체 레이아웃, 컴포넌트화
- 2nd Sprint : 컴포넌트 별 기능 구현, 프론트-백 통신, 코드 리팩토링, conflict 수정 작업

<br>

---

## 페이지별 기능 Demo 및 구현 기능 상세

### 0. 공통

- React 기반의 커머스 홈페이지 제작
- CRA를 사용한 초기 세팅
- 2명의 팀원들이 공통 `styled-component` 사용
- 공통부분인 Nav, Footer 컴포넌트 제작

### 1. 소셜 로그인, 로그아웃 페이지
![DRIP_로그인](https://user-images.githubusercontent.com/67620484/125184628-5707e000-e25a-11eb-9e35-19c65d68c998.gif)

- 카카오 로그인 API를 활용한 구성
- 카카오를 통해 Token을 받고 Backend와의 통신이 완료되면 Backend로부터 Token을 받아 Localstorage에 저장
- 카카오 로그아웃 API를 통해 로그아웃을 실행하고 성공하면 Localstorage에 저장 된 Token 삭제

### 2. 메인 페이지
![DRIP_메인](https://user-images.githubusercontent.com/67620484/125184638-730b8180-e25a-11eb-98b2-d7b9ca6fc59e.gif)

- 상단 React-Slick 라이브러리를 활용한 빅배너 캐러셀 구현
- Best, New 상품 카드 형식으로 리스트 노출
- 클릭 시 검색페이지로 이동하는 상단바 노출
- 상품 찜하기 버튼 구현

### 3. 메뉴(카테고리별 ) 페이지
![DRIP_하위카테고리](https://user-images.githubusercontent.com/67620484/125184737-3f7d2700-e25b-11eb-9cf0-73d3f152f6ec.gif)

- 상품 종류인 액티비티, 배움 상품 메뉴 리스트 구현
- 상품 종류별 서브카테고리 클릭 시 필터 적용된 상품 리스트 노출 구현
- 인기순, 평점순, 가격순 정렬 필터 구현


### 4. 주문 페이지
![DRIP_주문](https://user-images.githubusercontent.com/67620484/125184932-a64f1000-e25c-11eb-9f22-5e9d5cfc840a.gif)

- Daum Postcode API를 활용한 주소 검색 기능 구현
- 액티비티 참여 날짜, 인원 수 선택 기능 구현
- 참여하기 클릭 시 사용자 정보, 참여 옵션 데이터 저장

### 5. 상품 검색 페이지 
![DRIP_검색](https://user-images.githubusercontent.com/67620484/125184676-b4039600-e25a-11eb-9af9-cb0deedcca0e.gif)

- 검색창 활성화 시 인기 상품 fetch 받아 노출
- 인기 상품 클릭 시 해당 상품 상세 페이지 이동 기능 구현
- 검색 시 관련 상품 리스트 노출 및 관련 상품 없을 시 재검색 안내 페이지 노출 구현



## 🛠 사용한 기술
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/> <img src="https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white"/> <img src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E"/>
<br>

## 🛠 사용한 툴
<img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"/> <img alt="Trello" src="https://img.shields.io/badge/Trello-%23026AA7.svg?style=for-the-badge&logo=Trello&logoColor=white"/> <img alt="Git" src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white"/> <img alt="GitHub" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/>

<br>

## 👥 팀원

- 프론트 : [박준우](https://github.com/AutumnWithJay), [신미영](https://github.com/smy0102)
- 벡엔드 : [박준영](https://github.com/SkyStar-K), [송준](https://github.com/riassuc), [최승리](https://github.com/araaaaan)
  (드립 벡앤드팀 [깃허브](https://github.com/wecode-bootcamp-korea/21-2nd-Drip-backend))
  
  <br>

## Reference

이 프로젝트는 [프립](https://www.frip.co.kr) 사이트를 참조하여 학습목적으로 만들었습니다.
실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
