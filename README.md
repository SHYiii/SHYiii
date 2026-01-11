## Tech Stack
<p align="left">
  <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/springboot-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/spring%20data%20jpa-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/maven-C71A36?style=for-the-badge&logo=apache%20maven&logoColor=white" />
  <img src="https://img.shields.io/badge/redis-%23DC382D.svg?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/mysql-%234479A1.svg?style=for-the-badge&logo=mysql&logoColor=white" />
</p>

---

## Experience

### NHN Academy Java Backend 개발자 과정 12기
**2025.07.28** ~ **2025.12.31**

---

## Projects

### MSA 기반 온라인 서점 'trillion-book.shop'

**2025.11.11 ~ 2025.12.31**

**담당 역할**: 장바구니(Cart) 서비스 설계 및 백엔드 인프라 최적화

#### Repository
- **[trillion Repository](https://github.com/nhnacademy-be12-trillion)**
- **[Cart Service Repository](https://github.com/nhnacademy-be12-trillion/order)**

#### 주요 개발 내용 (Key Development Features)

* **고성능 장바구니 서비스 아키텍처 설계** 
	-  Redis를 주 저장소로 활용하여 인메모리 기반의 빠른 장바구니 조회 및 갱신 성능 확보
	- 빈번한 장바구니 변경 사항을 캐시에 우선 반영하고, 일정 주기 또는 특정 시점에 DB에 동기화하여 데이터베이스 부하 최소화
* **MSA 환경의 데이터 정합성 및 통신 최적화** 
	- OpenFeign을 이용한 마이크로서비스 간 선언적 HTTP 통신 구현 및 도서/주문 서비스와의 유연한 데이터 연동
	- 장바구니 상품 정보 검증 시 N+1 문제 해결을 위한 배치 조회 로직 구현 및 페이징 처리 최적화
* **시스템 안정성 확보를 위한 테스트 및 모니터링** 
	- JUnit5를 활용한 단위 테스트 및 통합 테스트 작성으로 장바구니 비즈니스 로직의 신뢰성 검증
	- 로그 추적 및 디버깅을 통한 시스템 병목 구간 식별 및 개선 작업 수행 
