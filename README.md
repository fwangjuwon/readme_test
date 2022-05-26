# 🐶냥도 놀러가고 싶댕 - 강원도 반려동물 여행 플랫폼 프로젝트

###  **Spring Boot를 활용한 반려동물 동반 여행 플랫폼 만들기**

- **팀 프로젝트 기간 : 2022.03.21~2022.04.23**
<a href="https://ibb.co/dP0xL1D"><img src="https://i.ibb.co/7nJLR8K/Screenshot-84.png" alt="Screenshot-84" border="0" /></a>
- **리팩토링 기간: 2022.05.10 ~ 2022.05.22**

- **팀 프로젝트 인원 : 구아현, 이선호, 정성현, 조해윤, 황주원 총 5명**
    
    - 🧑🏻‍💻 프론트엔드 : 정성현, 황주원
    - 🧑🏻‍💻 백엔드 : 구아현, 이선호
    - 👩🏻‍💻 총괄 : 조해윤
    
- **리팩토링 인원: 구아현, 정셩현, 황주원 총 3명**
    - 🧑🏻‍💻 구아현: 사용자(user) 부분 코드 리팩토링 및 추가 기능 구현
    - 🧑🏻‍💻 황주원: 게시판(board) 부분 코드 리팩토링 및 추가 기능 구현
    - 👩🏻‍💻 정성현: 전체 코드 리팩토링 및 추가 기능 구현
    
---

# 🐱기획 의도

📌 댕냥이와 같이 여행 할 수 있는 장소를 서로 공유하여 <br />
함께 반려동물 동반 여행 지도를 만들어 가는 여행 플랫폼! <br /> <br />

냥도놀러가고싶댕은 강원도 여행을 좋아하고 <br />
반려동물을 💖사랑하는 모두에게💖 열려 있습니다. <br />


# 🐱화면 설계 및 기능 구성

- 로고, 화면 설계, 기능 구성

🔗 [https://drive.google.com/drive/folders/1a44wdBKWE6OrUSmXG6B3PWgNdIsPQH7S]


# 🐱ERD
<a href="https://ibb.co/XSGXX1J"><img src="https://i.ibb.co/dGHBBFK/Screenshot-82.png" alt="Screenshot-82" border="0"></a>


# 🐱기능 소개

<a href="https://ibb.co/48g7Y6F"><img src="https://i.ibb.co/D9gt8x1/Screenshot-83.png" alt="Screenshot-83" border="0"></a>

# 🐱****프로젝트 개발 환경****
<a href="https://ibb.co/wLqgGH1"><img src="https://i.ibb.co/7zDCMcF/icon-common.png" alt="icon-common" border="0" /></a>

- **개발 언어**: Java 11, HTML 5, CSS, JavaScript
- **DataBase**: MariaDB 10.6
- **API**
    
    강원도 반려동물 동반관광 Open API([http://pettravel.kr/petapi](http://pettravel.kr/petapi)) 
    
    네이버 지도 API([https://developers.naver.com/main/](https://developers.naver.com/main/))
    
    Google Font API([https://fonts.google.com/](https://fonts.google.com/))
    
- **Library**
- **Front**
    - Bootstrap 5.1.3
    - jQuery 3.5.1
    - Summernote
    - Mustache
    - FontAwesome 5.15.2
- **Back**
    - Spring Web
    - Spring Boot Devtools
    - Lombok
    - MariaDB Driver
    - Spring Data JPA
    - Validation
- **개발 환경** : VS Code, SpringBoot 2.5.12, Gradle, Lombok, JPA
- **협업 툴** : GitHub, Trello, Discord, Kakaotalk, GoogleDrive, Slack


  
# 🐱****페이지별 상세 기능****

## 🙋‍♀️ ****관광정보 관련 기능****
- 관광정보와 네이버 지도API 연계 기능 
- 카테고리 별 관광정보 리스트 제공 
- 관광정보 상세보기 기능 
- 관광정보 좋아요, 즐겨찾기 기능 

| 관광정보와 네이버 지도API 연계 기능 | 카테고리 별 관광정보 리스트 제공 |
|------|------|
|![이미지1](https://ibb.co/nzw2BRn)|![이미지2](https://ifh.cc/g/v8C230.jpg)|
| 관광정보 상세보기 기능 | 관광정보 좋아요, 즐겨찾기 기능  |
|![이미지1](https://ifh.cc/g/qkLAwL.jpg)|![이미지2](https://ibb.co/5rVFj8x)|

## 🙋‍♀️ ****유저 관련 기능****
- 회원가입 시 유저 네임 중복 체크 기능
- 로그인 시 쿠키에 username 기억 기능
- 로그아웃 기능
- 회원정보 수정 기능
- 회원 탈퇴 기능
- 아이디/비밀번호 찾기 : 입력받은 이메일과 핸드폰번호로 회원 정보 찾는 기능

| 회원가입 시 유저 네임 중복 체크 기능 | 로그인 시 쿠키에 username 기억 기능 |
|------|------|
|![이미지1](https://ifh.cc/g/qkLAwL.jpg)|![이미지2](https://ibb.co/zxqhdS7)|
| 로그아웃 기능 | 회원정보 수정기능 |
|![이미지1](https://ifh.cc/g/qkLAwL.jpg)|<a href="https://ibb.co/1MnQYZC"><img src="https://i.ibb.co/2S6h0qz/update-user.gif" alt="update-user" border="0" /></a>|
| 회원탈퇴 기능 | 아이디/비밀번호 찾기 |
|![이미지1](https://ibb.co/CbQZkLB)|![이미지2](https://ifh.cc/g/v8C230.jpg)|


## 🙋‍♀️ ****게시글 관련 기능****
- 글 쓰기, 글 목록, 글 상세보기, 글 수정하기, 글 삭제하기, 글 좋아요
- 이미지 업로드 및 썸네일 등록
- 댓글 쓰기, 댓글 삭제하기 기능 제공

| 글 쓰기 | 글 목록 |
|------|------|
|![이미지1](https://ifh.cc/g/qkLAwL.jpg)|![이미지2](https://ifh.cc/g/v8C230.jpg)|
| 글 상세보기 | 글 수정 |
|![이미지1](https://ifh.cc/g/qkLAwL.jpg)|![이미지2](https://ibb.co/nRshyrR)|
| 글 삭제하기 | 글 좋아요 |
|![이미지1](https://ifh.cc/g/qkLAwL.jpg)|![이미지2](https://ifh.cc/g/v8C230.jpg)|
| 이미지 업로드(썸네일) | 댓글 기능 |
|![이미지1](https://ifh.cc/g/qkLAwL.jpg)|![이미지2](https://ibb.co/9bJ5Xfj)|


## 🙋‍♀️ ****게시글 관련 기능****
- 관리자가입코드를 만들어 관리자가입코드 입력 시 관리자로 회원가입 가능
- 회원 게시글 삭제 및 회원 댓글 삭제 기능
- 전체 데이터 받기 기능

| 관리자 회원가입 | 회원 게시글 삭제 |
|------|------|
|![이미지1](https://ifh.cc/g/qkLAwL.jpg)|![이미지2](https://i.imgur.com/A6gpri3.gif)|
| 회원 댓글 삭제 | 전체 데이터 받기 |
|![이미지1](https://ibb.co/jbvqLCn)|![이미지2](https://ifh.cc/g/v8C230.jpg)|



# 🐱구현 결과

🔗 [시연 영상 링크](https://youtu.be/xCVd9cn0hUE)



# 🐱****프로젝트 후기****

- 좋았던 점
    - 시간이 부족하여 계획했던 기능을 다 구현하지 못했지만 최선을 다하는 모습들을 보며 끝까지 포기하지 않고 마무리할 수 있었다.
    - 프론트도 함께 맡아 구현하니 새로운 개념들을 알아가며 더 배울 수 있었고, 프론트와 백의 소통이 중요하다는 것을 깨달았다.
    - 배웠던 기술을 프로젝트에 응용하여 팀원들과 함께 개발하면서 개념을 완벽하게 익힐 수 있었던 시간이었다.
    - 다양한 오류를 접하면서 원인을 찾고, 해결하면서 다시 한 번 공부하고 이해하는 계기가 되었다.
    - 수업 때 배우지 않은 기능을 찾아보고, 구현하며 더 많이 배울 수 있었다.
- 보완할 점
    - 프로젝트를 같이 모의하기에 앞서 팀원 개인의 실력과 수준을 정확하게 알고 역할 분담하는 것이 중요하다고 느꼈다.
    - 세부적인 기능 설정을 구현하면서 정하였고, 일정을 세세하게 관리하지 않아 후반에는 시간이 촉박했다. 이번 프로젝트를 통해 프로젝트 일정 관리와 기획 및 설계 단계에서 명확한 설계가 필요하다는 것을 느꼈다.
    - 중복되는 코드가 많아 코드가 깔끔하지 않았다.
    - 자신이 만드는 코드에 주석을 통해 간략한 정보나 기능을 명시하지 않아  전체적인 코드를 파악 힘들어 수정에 어려움이 있었다.
    - 협업툴(github)에 대한 이해도와 사용법에 대한 지식이 부족하여 버전관리 하기 힘들었다.
    - 의사소통 미흡으로 각자 진행/변동 사항 파악이 제대로 이루어지지 않아 전체적인 일정에 차질이 발생했다. 주기적인 회의가 필요한 것 같다.
  