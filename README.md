# 개요
간단 쇼핑몰 커머스 프로젝트

기술 : Spring, Jpa, Mysql, Docker, AWS, Redis

목표 : 셀러 구매자 사이 중개하는 커머스 서버 구축


## 회원

### 고객
  - [ ] 이메일로 인증번호 인증을 통한 회원 가입
  - [ ] 로그인 토큰 발행
  - [ ] 토큰을 통한 제어 확인 (JWT, Filter 사용해 간략히)
  - [ ] 예치금 관리

### 셀러
  - [ ] 회원가입


## 주문 서버

### 셀러
  - [ ] 상품 등록 ( CRUD )

### 구매자
  - [ ] 장바구니를 위한 Redis 연동
  - [ ] 상품 검색 & 상세 페이지
  - [ ] 장바구니에 물건 추가
  - [ ] 장바구니 확인
  - [ ] 주문하기
  - [ ] 주문내역 이메일 발송
