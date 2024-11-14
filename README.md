# :books: 도서 관리 프로그램
인프런 김영한 강사님의 'jpa 활용1'강의를 수강하며 만든 도서 관리 프로그램

## :pencil2: Stacks

### Environment

<img src="https://img.shields.io/badge/intellij idea-000000?style=for-the-badge&logo=intellijidea&logoColor=white">


### Development

<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white"> <img src="https://img.shields.io/badge/thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white"> <img src="https://img.shields.io/badge/MYSQL-4479A1?style=for-the-badge&logo=MYSQL&logoColor=white">

## :pushpin: 기능 목록

+ 회원 기능
  + 회원 등록
  + 회원 조회
    
+ 상품 기능
  + 상품 등록
  + 상품 수정
  + 상품 조회
    
+ 주문 기능
  + 상품 주문
  + 주문 내역 조회
  + 주문 취소

+ 기타 요구사항
  + 상품은 재고 관리가 필요하다.
  + 상품의 종류에는 도서가 있다.
  + 상품을 카테고리로 구분할 수 있다.
  + 상품 주문시 배송 정보를 입력할 수 있다.

## :heavy_plus_sign: 현재 변경 완료
+ DATABASE : H2 Database -> MYSQL

## :bulb: 추가 변경 사항
+ 상품 종류에 음반, 영화 추가

## :mag_right: 화면 구성

### 1. Home 화면 : 제일 첫번째로 보이는 화면
<p align="center">
<img width="60%" src="https://github.com/user-attachments/assets/5f946003-6919-4a63-988a-011fb90fd076" />
</p>

### 2. 회원 기능
+ 회원 가입 : 회원 정보 입력
<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/e357f0b8-7e73-4769-a819-e8a1decb3c2f" />
</p>

+ 회원 목록 : 가입한 전체 회원 목록
<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/08fc8ec0-d34c-4cf6-bccc-5051ee5a6b7b" />
</p>

### 3. 상품 기능
+ 상품 등록 : 도서 정보 입력
<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/cdeab6a8-078b-4882-92e9-187ca77213a2" />
</p>

+ 상품 조회 : 등록한 전체 도서 목록 조회
<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/a5b5196d-1812-4ec6-98f1-2af97f9527f0" />
</p>

+ 상품 수정 : 상품 정보 수정
<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/278a841c-2241-4173-a0ad-a407fba2535c" />
</p>

+ 상품 수정 후 조회 : 가격과 수량이 변한 것을 확인
<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/deab00e9-d861-4565-be52-85eeb89b908d" />
</p>

### 4. 주문 기능
+ 상품 주문 : 주문 정보(회원이름, 상품명, 주문수량) 입력
<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/902a415c-73e0-41d8-b48b-73d8a394165c" />
</p>

+ 주문 내역 
<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/03e6453c-198f-4ede-b5af-ae16dc196b55" />
</p>

+ 주문 취소 : 취소 버튼 눌러서 활성화
<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/330631db-17e3-4d2a-8723-7a7dab277903" />
</p>

+ 취소 목록 : 주문 취소 상태인 전체 상품 목록 조회
<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/075931d7-3166-4abf-878e-56721c532da8" />
</p>

+ 주문 목록 : 주문 상태인 전체 상품 목록 조회
<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/3076ffcd-3cff-4a21-bed4-4f66c2a0e429" />
</p>

+ 이름으로 조회 : 회원 이름으로 주문 목록 조회
<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/07688838-c501-4ec3-a5b2-837a37187897" />
</p>

+ 주문 후 상품 목록 : 주문 후 남아 있는 도서 수량 변화
<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/21ee6dfd-fffc-4b37-8a7b-b565fc9aa72f" />
</p>
