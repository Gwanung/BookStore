# 도서 관리 프로젝트

## 📚 개발 의도 
교보문고, 알라딘과 같은 자체적인 도서관리 시스템 구현 

## 개발 블로그 및 배포
- [블로그 바로가기](https://wgu2105.tistory.com/)
- [배포 링크](http://15.164.199.51:8080/BookStore/mainHome)

## 개발 버전 
- Java - 11.0.15
- Oracle - 11g Express Edition
- Spring - 5.2.7 

##  사용 기술 및 환경  
<!-- <img src="https://img.shields.io/badge/표시할이름-색상?style=for-the-badge&logo=기술스택아이콘&logoColor=white"> -->

<div align=center> 
  <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=OpenJDK&logoColor=white"/>
  <img src="https://img.shields.io/badge/JSP-007396?style=flat&logo=OpenJDK&logoColor=white"/>
  <br>
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
  <br>
  <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
  <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"> 
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> 
  <br> 
  <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white">
  <img src="https://img.shields.io/badge/Git Kraken-179287?style=for-the-badge&logo=GitKraken&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">
  <img src="https://img.shields.io/badge/AWS EC2-FF9900?style=for-the-badge&logo=amazonecs&logoColor=white">
</div>

## 🔧 개발 기간
 2022.11.15 ~ 2022.12.07

## 👥 개발 인원 
- 원관웅 : 회원가입 및 로그인, 도서리스트, 카테고리, 도서검색, 장바구니, 마이페이지 구현
- 전상민 : 게시판, 게시판 댓글, 도서리뷰 및 평점, 게시판 검색 구현
- 황민우 : 주문 및 구매 구현

## 맡은 업무 주요 기능

회원가입 
- 보안을 위한 Security 암호화 적용
- 아이디 중복체크 및 유효성 검사 
- 주소 api를 통한 배송지 정보 등록

로그인 
- 아이디, 비밀번호 일치여부 확인
- 회원가입 링크 연결

마이페이지 
- 회원정보 확인 및 수정
- 회원정보 탈퇴

메인화면
- 제목 및 저자 검색 
- 카테고리 분류
- 전체 도서 페이징 처리
- 할인율 및 평점 높은 순 리스트 
- 도서 개수 차감 및 품절 처리 

도서 상세페이지
- 장바구니 등록

장바구니 
- 수량 조절 시 도서 개수 초과확인
- 체크박스를 통한 원하는 도서만 구매

## 이미지

메인화면
- 도서 개수를 부여하여 도서를 구매했을 시 개수 차감이 되게 적용하였습니다. 이때 도서 개수가 0개가 되면 해당 도서는 품절처리 됩니다. (구매 및 장바구니 담기 불가)
<img src="https://github.com/Gwanung/web-programming/assets/100282696/98b02fde-d8ec-4c71-ac3a-db3828b66481">

- 도서 메인화면에 할인이 높은 순과 낮은 순을 리스트로 표현하여 사용자가 보다 쉽게 자신이 원하는 도서를 선택할 수 있도록 하였습니다.
<img src="https://github.com/Gwanung/web-programming/assets/100282696/d4801c34-f994-47ce-94cb-d06952eb117a">

- 저자와 제목에 해당하는 내용을 검색 하면 해당 내용에 맞는 도서가 리스트로 출력되고 도서를 클릭하면 상세페이지로 이동합니다.
<img src="https://github.com/Gwanung/web-programming/assets/100282696/467dc611-ef57-41e3-814b-764482600e1d">

- 


## ERD

<img src="https://github.com/Gwanung/web-programming/assets/100282696/ea34f0f1-54fb-493d-bfc3-4272a0fab517">