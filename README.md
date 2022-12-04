# Bulletin-Borad Project
---
## 목차
1. [개발환경](#개발환경)
2. [기능](#기능)
3. [참고자료](#참고자료)
4. [업데이트](#업데이트)

---

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
