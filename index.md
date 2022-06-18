---
layout: cv
title: 
email:
  url: pa324@naver.com
  text: pa324@naver.com
homepage:
  url: https://syundev.tistory.com/
  text: https://syundev.tistory.com/
---

# 박상윤

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->

{% include cv-contact.html %}

## Work experience

### **eBay Korea** `2020.6 ~`

<br>
<br>

## Project

### [**ESM+ 상품 엑셀일괄등록 API 개발**]

### 1. 소개
- 지마켓,옥션 통합상품관리 플랫폼인 ESM+에서 2.0 일반상품을 엑셀에 입력하여 대량으로 등록할 수 있는 API 개발
- Apache POI를 활용해서 엑셀파일을 자바객체로 변환하는 모듈 개발
- 인터페이스를 활용해서 일반배송상품/스마일배송상품 등록에 필요한 json모델로 변환하는 컨버팅 로직 개발
- 상품 대량등록시 멱등성 보장을 위해 처리현황별 상태 업데이트 로직 개발
- 컨버팅 로직 및 엑셀 파싱 모듈에 단위테스트코드 작성
- 일괄등록 현황조회를 위한 프론트엔드 컴포넌트들을 Vue.js와 Typescript를 사용해서 구현

### 2. 기술스택

- Java 11, Spring Boot 2.3.3, Apache Kafka,Apache poi, MSSQL, Vue.js, Typescript


<br>
<br>

### [**상품 통합 재고 API 개선**]


### 1. 소개
  
- 통합재고 API를 사용하는 주문서 API에서 출고재고를 복구시킬시 같은 주문에 대한 중복복구, 출고재고차감을 정상적으로 처리하지 않았지만 출고재고를 복구함으로 인해 일부 상품의 재고정합성 문제 발생
- 출고재고 차감/복구를 시도할시 로그를 남기는 테이블이 있었는데 로그 테이블을 이용해서 같은 주문에 대한 중복복구, 출고재고차감을 성공하지 못했지만 복구하려는 시도를 처리하지 못하도록 개선


### 2. 기술스택

- Java 11, Spring Boot 2.3.3

<br>
<br>

### [**esm+ vue.js전환**]

### 1. 소개
- esm+의 판배상품별 일괄공지, 2.0상품등록 상품상세설명 등록/수정 컴포넌트 .NET Razor 서버사이드렌더링코드를 Vue.js로 전환

### 2. 기술스택

- Vue.js, TypeScript


<br>
<br>



<!-- ### Footer

Last updated: May 2013 -->
