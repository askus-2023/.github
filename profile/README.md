# :cookie: Cookle

## :books: 목차

- [:cookie: Cookle](#cookie-Cookle)
  - [:books: 목차](#books-목차)
    - [:tada: 소개](#tada-소개)
    - [:rocket: 프로젝트](#rocket-프로젝트)
    - [:clipboard: 문서](#clipboard-문서)

### :tada: 소개

안녕하세요! 저희는 백엔드 2명, 프론트엔드 2명으로 구성된 개발모임 Cookle입니다.

### :rocket: 프로젝트

<table>
    <tr>
        <th> 이름 </th>
        <th> 일자 </th>
        <th> 종류 </th>
        <th> 버전 </th>
        <th> 기술 </th>
        <th> 참여자 </th>
    </tr>
    <tr>
        <td> <a href=""> Cookle </a> </td>
        <td width="170px"> 2023. 03. 10 - </br>2023. 05. 15 </td>
        <td> Web </td>
        <td> 1.0 </td>
        <td>
        <img src="https://img.shields.io/badge/Java-444444?style=for-the-badge&logo=Java&logoColor=yellow">
        <img src="https://img.shields.io/badge/Spring Boot-444444?style=for-the-badge&logo=Spring Boot&logoColor=#6DB33F">
        <img src="https://img.shields.io/badge/Spring Data Jpa-444444?style=for-the-badge&logo=Spring&logoColor=#6DB33F">
        <img src="https://img.shields.io/badge/Spring Security-444444?style=for-the-badge&logo=Spring Security&logoColor=#6DB33F">
        <img src="https://img.shields.io/badge/querydsl-444444?style=for-the-badge&logo=querydsl&logoColor=#6DB33F">
        <img src="https://img.shields.io/badge/MySQL-444444?style=for-the-badge&logo=MySQL&logoColor=##4479A1">
        <img src="https://img.shields.io/badge/Amazon S3-444444?style=for-the-badge&logo=Amazon S3&logoColor=#569A31">
        <img src="https://img.shields.io/badge/Amazon EC2-444444?style=for-the-badge&logo=Amazon EC2&logoColor=#FF9900">
        <img src="https://img.shields.io/badge/Amazon CodeDeploy-444444?style=for-the-badge&logo=Amazon CodeDeploy&logoColor=##2088FF">
        <img src="https://img.shields.io/badge/GitHub Actions-444444?style=for-the-badge&logo=GitHub Actions&logoColor=##2088FF">
        <img src="https://img.shields.io/badge/Redis-444444?style=for-the-badge&logo=redis&logoColor=##2088FF">
        <img src="https://img.shields.io/badge/openai-444444?style=for-the-badge&logo=openai&logoColor=#412991">
        <br />
        <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB">
        <img src="https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white">
        <img src="https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white">
        <img src="https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white">
        </td>
        <td width="150px">
            <a href="https://github.com/1Bronze"> 백엔드 김한동 </a> </br>
            <a href="https://github.com/hgene0929"> 백엔드 이현진 </a> </br>
            <a href="https://github.com/dlsdo1101"> 프론트엔드 김인애 </a> </br>
            <a href="https://github.com/t-junne"> 프론트엔드 우태준 </a> </br>
        </td>
    </tr>     
</table>

### :clipboard: 문서

자세한 문서(회의록, API 설계서, ERD 설계서, 와이어프레임)는 [여기](https://hgene.notion.site/cookle-dc4b81479b0e4012a58c8ae8158e878c)를 참고해주세요.<br>
이외에도 백엔드 관련 정리는 [여기](https://github.com/askus-2023/cookle_backend#readme), API 문서는 [여기](http://13.124.76.165:8080/swagger-ui/index.html#/)를 참고해주세요.

### 🙂 서비스

실제 서비스는 http://www.cookle.site/main 를 클릭하여 사용해보실 수 있습니다.

### 📹 시연영상

#### 1. 회원 기능<br>
- 회원가입을 한 후, 로그인을 통해 cookle 서비스를 이용할 수 있습니다.
- 프로필 수정 및 비밀번호 수정이 가능합니다.
- 내 프로필 페이지에서 자신의 프로필 내용을 확인할 수 있습니다.<br><br>

#### 2. 게시글 기능<br>
- 챗봇이 추천해준 레시피를 토대로 요리해 터득한 자신만의 레시피를 공유하는 게시글을 작성, 수정, 삭제할 수 있습니다.
- cookle 서비스의 게시글을 조회할 수 있습니다.
- 검색어를 통해 게시글을 조회할 수 있습니다.
- 게시글의 메뉴 카테고리(한식, 중식, 일식, 양식, 기타)에 따라 조회할 수 있습니다.
- 상세조회를 통해 게시글의 상세조회 페이지에 접근할 수 있습니다.
- 전체 게시물은 최신순, 좋아요순으로 정렬할 수 있습니다.<br><br>
![게시글1](https://github.com/askus-2023/.github/assets/90823532/8e35fb73-06c8-4d39-b862-5428404bedd2)
![게시글2](https://github.com/askus-2023/.github/assets/90823532/ef01ea33-134e-4562-b75d-7df5d3ad9815)

<br>
#### 3. 기타 기능<br>
- 다른 사람의 게시글에 댓글을 달고, 좋아요를 누를 수 있습니다(수정,삭제 기능 포함).
- 자신이 좋아요를 누른 게시글을 모아 볼 수 있습니다.
- 자신이 작성한 게시글을 모아 볼 수 있습니다.<br><br>
![기타기능1](https://github.com/askus-2023/.github/assets/90823532/2cb4ef3f-7f58-4337-bfe0-dcf534ff4f12)
![기타기능2](https://github.com/askus-2023/.github/assets/90823532/a88092bc-ff59-493d-9d20-2e1150d77b5e)

<br>
#### 4. 챗봇 기능<br>
- gpt-3.5 모델 기반의 openai api를 연동하여 레시피를 물어보고 답변을 받을 수 있는 챗봇 서비스를 이용하실 수 있습니다.<br><br>
![챗봇기능](htt![11](https://github.com/askus-2023/.github/assets/90823532/6e60d61a-2cca-4629-9ab1-e9f3a94b8df4)
