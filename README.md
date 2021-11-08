# javafx
fx

프로세스 : 회원가입, 로그인, 회원정보 수정
구현언어 : javaFx + SceneBuilder + Oracle

# 버전 및 환경
javaJDK , JavaFX SDK 15 버젼

SQL  테이블명 : smember
               필드 : USERID,USERPWD,UNAME,UNUMBER,UPHONE,UMAJOR,UADDRESS
               
--module-info.java 파일 내 추가내용--

	requires javafx.controls;
	requires javafx.fxml;
	requires java.sql;
	opens application;
--


# 프로그램 화면
(1)로그인

![캡처](https://user-images.githubusercontent.com/84943154/140712547-dc289f51-97fc-4c1b-8135-0506d8806e04.PNG)

(2) 회원가입

![캡처1](https://user-images.githubusercontent.com/84943154/140712733-e0a0c4f3-8752-4f3e-8233-2c0cff62f1bf.PNG)

(3)회원정보수정

![reg_e](https://user-images.githubusercontent.com/93318468/140670350-bdb0dfc6-eb30-48bd-9054-e2de7d2ddff9.jpg)

