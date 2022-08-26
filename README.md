# Bulletin-Borad Project
---
## 목차
1. [계기](#프로젝트-동기)
2. [개발환경](#개발환경)
3. [기능](#기능)
4. [참고자료](#참고자료)
5. [업데이트](#업데이트)

---
### 프로젝트 동기
>> 전역할 때 쯤 되니 장래에 대해 걱정되기 시작했다. 요새 컴퓨터 관련 과가 유망있다 하여, 일단 입학하고 보자 하는 심정으로 들어왔던 거 같다. 입학하고 난 뒤에 그저 학과 공부만 잘 따라가면 모든게 해결될 줄 알았다. 학과 공부를 열심히 하여 학점은 그럭저럭 나왔다. 그러나 시간이 흐르면서 마음 한편에 불안함이 계속 자리 잡았다. 다른 사람이 만든 기능들을 보면서 내가 여지껏 배운 것으로 이걸 할 수 있을까 하는 의문이 계속 들었다. 그렇게 불안함을 안고 지내던 중 S/W 프로젝트 과목을 수강하기 위해 교수님과 면담을 했다. back-end 개발자를 희망한다고 말씀드렸는데, 여러 조언을 해주시면서 하신 말씀이 '게시판이 기본이다'였다. 그러기에 면담을 하고 온 오늘 바로 깃허브 계정을 만들어 이 프로젝트를 시작해보려 한다.

### 개발환경
##### Langauge
- Java(JDK 1.8)
##### IDE
- Eclipse
##### Server
- Apache Tomcat(apache-tomcat-8.5.65)
##### DB
- MySQL

### 기능
- 자바 클래스
1. 자바빈즈
    - 사용자 - [User.java](https://github.com/Parktkddyd/bulletin-board/tree/main/BBS/src/main/java/user/User.java)
    - 게시판 - [Bbs.java](https://github.com/Parktkddyd/bulletin-board/tree/main/BBS/src/main/java/bbs/Bbs.java)
2. 데이터 접근 객체
    - 사용자 - [UserDAO.java](https://github.com/Parktkddyd/bulletin-board/tree/main/BBS/src/main/java/user/UserDAO.java)
    - 게시판 - [BbsDAO.java](https://github.com/Parktkddyd/bulletin-board/tree/main/BBS/src/main/java/bbs/BbsDAO.java)
- 메인화면 & 회원관리
    - 홈페이지 메인
        - [main.jsp](https://github.com/Parktkddyd/bulletin-board/tree/main/BBS/src/main/webapp/main.jsp)
    - 로그인
        - [login.jsp](https://github.com/Parktkddyd/bulletin-board/tree/main/BBS/src/main/webapp/login.jsp)
        - [loginAction.jsp](https://github.com/Parktkddyd/bulletin-board/tree/main/BBS/src/main/webapp/loginAction.jsp)
    - 회원가입
        - [join.jsp](https://github.com/Parktkddyd/bulletin-board/tree/main/BBS/src/main/webapp/join.jsp)
        - [joinAction.jsp](https://github.com/Parktkddyd/bulletin-board/tree/main/BBS/src/main/webapp/joinAction.jsp)
- 게시판 기능
    - 게시판 메인
        - [bbs.jsp](https://github.com/Parktkddyd/bulletin-board/tree/main/BBS/src/main/webapp/bbs.jsp)
    - 목록
        - [view.jsp](https://github.com/Parktkddyd/bulletin-board/tree/main/BBS/src/main/webapp/view.jsp)
    - 쓰기
        - [write.jsp](https://github.com/Parktkddyd/bulletin-board/tree/main/BBS/src/main/webapp/write.jsp)
        - [writeAction.jsp](https://github.com/Parktkddyd/bulletin-board/tree/main/BBS/src/main/webapp/writeAction.jsp)
    - 수정
        - [update.jsp](https://github.com/Parktkddyd/bulletin-board/tree/main/BBS/src/main/webapp/update.jsp)
        - [updateAction.jsp](https://github.com/Parktkddyd/bulletin-board/tree/main/BBS/src/main/webapp/updateAction.jsp)
    - 삭제
        - [deleteAction.jsp](https://github.com/Parktkddyd/bulletin-board/tree/main/BBS/src/main/webapp/deleteAction.jsp)
### 참고자료
[Youtube](https://www.youtube.com/watch?time_continue=110&v=wEIBDHfoMBg&feature=emb_title)
  **동빈나** 님의 JSP게시판 만들기 강좌

### 업데이트
> - 20220819
>     - 개발환경 구축
> - 20220820
>     - 로그인 화면 구현
> - 20220822
>     - 로그인 기능 구현
>     - 회원가입 화면 구현
>     - 회원가입 기능 구현
> - 20220823
>     - 회원 세션 관리 기능 추가
>     - 메인 페이지 디자인
>     - 게시판 페이지 디자인
>     - 게시판 데이터베이스 구축
>     - 게시판 글쓰기 기능 구현
> - 20220824
>     - 게시판 글 목록, 글 보기 기능 구현 
>     - 게시판 글 수정, 삭제 기능 구현
