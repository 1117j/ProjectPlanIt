# ProjectPlanIt
Spring Project - 여행 일정 등록 및 커뮤니티 공유 서비스 
<hr />

>여행 계획을 등록, 여행지간 경로검색, 회원커뮤니티에 후기 및 일정을 공유하는 서비스 플랫폼


<br>
<br>

### 기술 / 구조 

<hr />

- 웹 표준 

  `HTML5` `CSS3` `JavaScript` `jQuery` `Bootstrap` `W3C`

- DBMS  - `MySQL`

- Spring Framework, Mybatis

- API 

   `Rest API` `kakao API` `kakao 주소 API` `kakao map API` `summernote`

- RESTful API 구조

  서버와 클라이언트 통신을 위한 REST 인터페이스 구현

- WAS - `Tomcat8`

- AWS 배포 

  `EC2` `RDS`


<br>
<br>


### 주요 기능 및 담당 업무

<hr />

* 회원 기능
    - 로그인 Session 처리 
    - 가입 시 Email/닉네임 중복 여부 Ajax 처리
    - 패스워드 유효성 검사
    - Kakao REST API를 활용한 간편 로그인
    - KAKAO 회원 액세스 토큰/ 리프레시 토큰 발급 및 인증
* 메인 화면
    - 작성 플랜 및 커뮤니티 차트 플랜 출력
* 마이 페이지
    -마이 페이지에 작성 플랜, 작성글 출력
  
<br>
<br>

### 요청 게시판 & 후기 작성 설계 

<hr />

* DB - 전체 ERD

![PlanIt_ERD](https://user-images.githubusercontent.com/63032376/97860795-1f00e280-1d46-11eb-80f9-5d45ccedcc53.png)


* 회원가입 및 로그인 프로세스 

![member_process](https://user-images.githubusercontent.com/63032376/97861126-a2bacf00-1d46-11eb-8395-6bf8f69ae0e9.png)

<br>
<br>


### 구현 - 소스코드
* 회원관리 코드
    - [Controller](https://github.com/1117j/ProjectPlanIt/tree/main/PlanIt/src/main/java/com/aia/it/member/controller)
    
    - [Service](https://github.com/1117j/ProjectPlanIt/tree/main/PlanIt/src/main/java/com/aia/it/member/service)
    
    - [Dao](https://github.com/1117j/ProjectPlanIt/tree/main/PlanIt/src/main/java/com/aia/it/member/service)
    
    - [View](https://github.com/1117j/ProjectPlanIt/tree/main/PlanIt/src/main/webapp/WEB-INF/views/member)

<hr />



  









