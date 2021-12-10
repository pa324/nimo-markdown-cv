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

## Project

### [**ESM+ 상품 일괄등록 API Phase1 개발**]

### 1. 소개
  
- 지마켓,옥션 통합상품관리 플랫폼인 ESM+에서 2.0 일반상품을 엑셀에 입력하여 대량으로 등록할 수 있는 API 개발 

### 2. 기술스택

- Java 11, Spring Boot 2.3.3, Apache Kafka,Apache poi, MSSQL, Vue.js, Typescript

   
### 3. 역할
 
- Apache POI를 활용해서 엑셀파일을 자바객체로 변환하는 모듈 개발
- 인터페이스를 활용해서 상품등록에 필요한 json모델로 변환하는 컨버팅 로직 개발
- 상품 대량등록시 멱등성 보장을 위해 처리현황별 상태 업데이트 로직 개발
- 컨버팅 로직 및 엑셀 파싱 모듈에 단위테스트코드 작성
- 일괄등록 비동기 현황조회를 위한 프론트엔드 컴포넌트들을 Vue.js와 Typescript를 사용해서 구현
  

<br>

### [**옥션 실시간 이미지 리사이징 전환**]

### 1. 소개
  
- 원본이미지만 NAS에 저장하고 나머지 이미지 사이즈들은 실시간 리사이징으로 전환하는 프로젝트

### 2. 기술스택

- Java 11, Spring Boot 2.3.3, Ehcache, hystrix

### 3. 역할

- iac-image애플리케이션에 로컬캐시 적용 및 코드의 안정성을 올리기위해 단위테스트코드 작성
  - 서킷브레이커 open/close관련 단위테스트코드 작성
- 원본이미지 제공용 iis서버 세팅
- iac-image애플리케이션 쿠버네티스 인프라 설정 작업

<br>

### [**상품 SD속성정보 일괄삭제 Admin 개발**]

### 1. 소개
  
- 분산환경의 2.0 상품 SD속성 매칭정보를 삭제하는 Admin개발

### 2. 기술스택

- .NET MVC

### 3. 역할

- esm+,gmarket,auction API로 분리된 분산환경에서 보상트랜잭션을 통해 애플리케이션 레벨에서 데이터 정합성 유지가 가능하도록 SD속성 일괄삭제기능 개발

<br>

### [**통합 재고 API 유지보수**]

### 1. 소개
  
- 2.0 상품의 통합재고 API를 유지보수하는 업무를 담당했습니다.

### 2. 기술스택

- Java 11, Spring Boot 2.3.3

### 3. 역할

- 물리서버에서 수집하던 통합재고 API의 모니터링 인프라를 클라우드 환경으로 이관
- 운영중인 서비스 쿠버네티스 신규 클러스터로 이관

<br>
<br>
<br>
<br>
<br>
<br>

## Education

### **ATDD과정** `2021.4 - 2021.5`

<br>

레거시 시스템을 유지보수하면서 테스트 코드가 없어서 리팩토링하기 힘들고 작은 수정에도 사이드이펙트가 많이 발생하는 경험을 했었습니다. 테스트 코드의 필요성을 느끼고 신규 프로젝트 및 신규개발건에는 테스트코드를 작성해서 코드의 안전성을 올리고 싶어서 NEXT STEP의 [ATDD](https://edu.nextstep.camp/c/R89PYi5H/s)과정을 이수했고 Production 코드에 테스트를 도입하기위해 노력하고있습니다.

- [atdd-subway-path](https://github.com/pa324/atdd-subway-path)
- [atdd-subway-favorite](https://github.com/pa324/atdd-subway-favorite)
- [atdd-subway-map](https://github.com/pa324/atdd-subway-map)




<!-- ### Footer

Last updated: May 2013 -->
