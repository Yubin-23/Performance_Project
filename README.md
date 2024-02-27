# PERFORMANCE TICKET
![PT](https://github.com/Yubin-23/Performance_Project/assets/137861704/3218a201-f519-455a-b827-21bcc7114422)

<br>

## 📁프로젝트 개요

> **프로젝트**: 공연 예매 사이트
>
> **기획 및 제작**: 권순성, 송지선, 왕유빈, 이희윤, 전원영
>
> **분류**: 팀 프로젝트
>
> **제작 기간**: 2023.08.16~2023.09.15

<br>

## 🧑‍🤝‍🧑팀원소개

> **팀원**: 권순성
>
> 상품 관리, 위시리스트, 결제 기능

> **팀원**: 송지선
>
> 회원가입, 로그인, Front Design

> **팀장**: 왕유빈
>
> 공연/공연시설 관리, 댓글 및 댓글 좋아요 기능, Front Design

> **팀원**: 이희윤
>
> 공연 예매 및 관리 

> **팀원**: 전원영
>
> 게시판 관리, Front Design

<br>

## 🛠️개발 환경 및 도구

<img src="https://img.shields.io/badge/FRAMEWORK-%23121011?style=for-the-badge"> ![spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white) <br/>

<img src="https://img.shields.io/badge/LIBRARY-%23121011?style=for-the-badge"> <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"> <br/>

<img src="https://img.shields.io/badge/IDE-%23121011?style=for-the-badge"> ![Spring Tool Suite 3](https://img.shields.io/badge/Spring%20Tool%20Suite%203-6DB33F?style=for-the-badge&logo=Spring&logoColor=white) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white) ![DBeaver](https://img.shields.io/badge/DBeaver-382923?style=for-the-badge&logo=dbeaver&logoColor=white)<br/>

<img src="https://img.shields.io/badge/DB-%23121011?style=for-the-badge"> ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white) <br/>

<img src="https://img.shields.io/badge/Language-%23121011?style=for-the-badge"> ![Java](https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white) <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <br/>

<img src="https://img.shields.io/badge/OS-%23121011?style=for-the-badge"> ![Windows](https://img.shields.io/badge/Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white) <br/>

<img src="https://img.shields.io/badge/Server-%23121011?style=for-the-badge"> ![Apache Tomcat](https://img.shields.io/badge/apache%20tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black) <br/>

<img src="https://img.shields.io/badge/Hosting-%23121011?style=for-the-badge"> ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white) <br/>

<img src="https://img.shields.io/badge/Other-%23121011?style=for-the-badge"> ![Docker](https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white) ![GitHub](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white) 

<br>

## 🖥️기능 구현
### 사용자
#### - 공연 목록

![공연목록](https://github.com/Yubin-23/Performance_Project/assets/137861704/9e56132a-a69b-47ed-b200-92069a032d2f)

- 뮤지컬과 연극으로 카테고리를 나눠서 뮤지컬별/연극별 공연 조회 가능
- Title(공연명) 또는 Cast(출연진)으로 검색 가능 
- 원하는 공연을 클릭 시 공연의 상세 페이지로 이동 

#### - 공연 상세

![공연상세](https://github.com/Yubin-23/Performance_Project/assets/137861704/66e845bc-3979-425b-860f-4c49db80552d)

- 공연의 상세 정보와 댓글을 확인할 수 있는 페이지 
- 예매하기 버튼을 누르면 예매창이 팝업으로 나타남

#### - 댓글

![댓글](https://github.com/Yubin-23/Performance_Project/assets/137861704/4d6f714c-ad52-4446-b5c4-6ec20d0073f2)


- 회원만 댓글 등록 가능 
- 로그인 안된 상태에서 등록 버튼을 누르면 로그인 페이지로 이동 
- 댓글의 수정, 삭제는 작성자만 가능  

#### - 댓글 좋아요 

![댓글좋아요](https://github.com/Yubin-23/Performance_Project/assets/137861704/200abe4b-f4c6-41c3-9235-6c0f8e5df7c7)

- 회원이 좋아요 아이콘을 클릭 시 좋아요 개수가 증가 
- 좋아요 아이콘을 한번더 누르면 좋아요 취소됨

------

### 관리자
#### - 공연 목록 

![관리자_공연목록](https://github.com/Yubin-23/Performance_Project/assets/137861704/956259b5-9114-47b1-9427-3d83c6d2afe6)

- 전체 공연 확인 가능
- Title(공연명) 또는 Cast(출연진)으로 검색 가능 
- 공연명 클릭 시 공연의 상세 페이지로 이동 

#### - 공연 상세 

![관리자_공연상세](https://github.com/Yubin-23/Performance_Project/assets/137861704/8f81caac-8499-446d-adce-4f9d23c16a9c)

- 공연의 상세 정보를 확인할 수 있는 페이지
- 삭제 버튼을 누르면 공연이 삭제됨 

#### - 공연시설 목록

![관리자_공연시설목록](https://github.com/Yubin-23/Performance_Project/assets/137861704/dbb7413f-5f38-4d19-8efd-576f88a4e245)

- 전체 공연시설 확인 가능
- Name(공연시설명) 또는 Address(주소)로 검색 가능
- 공연시설명 클릭 시 공연시설의 상세 페이지로 이동

#### - 공연시설 상세 

![관리자_공연시설상세](https://github.com/Yubin-23/Performance_Project/assets/137861704/009e339e-d3c2-411a-9698-d9c0cd7ff226)

- 공연시설의 상세 정보를 확인할 수 있는 페이지




