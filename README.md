# Spring_basic_study

#### ◈ 스프링 개념잡기

#### ◈ 스프링부트 기초 학습 _ hello
 1. 회원관리 예제 (MVC 패턴사용)
 2. H2 DB 사용
 3. 스프링 빈과 의존관계 학습
 4. 순수 JDBC, 스프링 JDBC Template, JPA, 스프링 데이터 JPA 학습
 
 -------------------------------------
 
 #### ◈ 스프링 부트 + MySQL + Spring Data JPA 활용하여 회원관리 예제 만들어보기 _ Member
 - 회원가입 기능
 - 로그인 기능
 - 회원목록, 조회, 정보수정, 삭제
 - 로그아웃 기능
 - ajax 이용하여 이메일 중복확인 기능
 
 -------------------------------------
 
 #### ◈ 스프링 부트 + MySQL + Spring Data JPA 활용하여 블로그 만들어보기 _log   
 
 1. Entity 테이블 생성
  - MySQL DB 생성
  - 각 테이블 연관관계의 주인 학습
 
 2. 메인화면 만들기(jsp 사용)
  - Bootstrap  사용
 
 3. 회원가입 기능
  - ajax 사용
  
 4. 로그인 기능
 
 
 ------------------------------------
 
  #### ◈ 개념 및 용어정리
 ※ 영속 컨텍스트 & 더티체킹
 
  ==> 더티체킹(Dirty Checking)
  
     · 상태 변경 검사이다. 

     · JPA에서는 트랜잭션이 끝나는 시점에 변화가 있는 모든 엔티티 객체를 데이터베이스 반영한다. 
        그렇기 때문에 값을 변경한 뒤, save 하지 않더라도 DB에 반영되는 것이다.

  ==> 더티체킹(Dirty Checking) 원리
  
     · 영속성 컨텍스트란 서버와 DB사이에 존재한다.
     
     · JPA는 엔티티를 영속성 컨텍스트에 보관할 때, 최초 상태를 복사해서 저장해둔다.(일종의 스냅샷)
     
     · 트랜잭션이 끝나고 flush할 때 스냅샷과 현재 엔티티를 비교해 변경된 엔티티를 찾아낸다.
     
     · JPA는 변경된 엔티티를 DB단에 반영하여 한번에 쿼리문을 날려준다.
    
  ※ Ajax 사용이유
  
     · 요청에 대한 응답을 html이 아닌 Data(Json)을 받기 위해 사용
     
     · 비동기 통신
 
 
