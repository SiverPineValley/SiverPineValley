<div align=center>

[![hits](https://myhits.vercel.app/api/hit/https%3A%2F%2Fgithub.com%2FSiverPineValley%2FSiverPineValley?color=blue&label=hits&size=small)](https://myhits.vercel.app)

</div>

## 📌 Contact & Links

| 항목 | 링크 / 정보 |
| :--- | :--- |
| **GitHub** | [![Static Badge](https://img.shields.io/badge/GitHub-%23181717?logo=GitHub)](https://github.com/SiverPineValley) |
| **Blog** | [![Static Badge](https://img.shields.io/badge/TechBlog-%23663399?logo=Gatsby)](https://siverpinevalley.github.io/) |
| **Email** | [![Static Badge](https://img.shields.io/badge/Email-%2303C75A?logo=Naver)](mailto:whddls9632@naver.com) |
| **LinkedIn** | [![Static Badge](https://img.shields.io/badge/LinkedIn-%230A66C2?logo=LinkedIn)](https://www.linkedin.com/feed/?trk=guest_homepage-basic_nav-header-signin) |

---

## 🧭 Engineering Values (가치관)

> **"모든 일은 일어날 수 있다" — 유연한 사고와 높은 수용성으로 끊임없이 최선의 답을 찾아갑니다.**

- **유연한 사고와 높은 수용성**: 대규모 분산 환경에서는 예기치 못한 트래픽 급증과 장애 변수가 언제든 발생할 수 있습니다. 기존 설계나 과거의 성공 경험에 매몰되지 않고, 상황과 데이터의 변화에 맞춰 언제든 생각을 수정하고 최적의 대안을 적극적으로 받아들입니다.
- **비판적 탐구**: 기존의 관행이나 시스템 구조를 맹목적으로 따르지 않고, 문제의 근본 원인(Root Cause)을 끝까지 파고듭니다. 쿼리 병목, 메모리 누수, 아키텍처 한계에 직면했을 때 데이터와 프로파일링 도구를 기반으로 객관적인 가설을 세우고 집요하게 검증합니다.
- **다원주의적 접근**: 하나의 기술 스택이나 정답만을 고집하지 않고, 기술·비즈니스·보안 등 다각도의 맥락과 팀원들의 다양한 시각을 포용합니다. 개발 생산성과 보안(DevSecOps), 성능과 안정성 등 상충하는 가치 속에서 다원주의적 시각을 바탕으로 가장 조화롭고 최적화된 균형점을 도출합니다.

---

## 💼 Career

### 현대오토에버
**OTA플랫폼개발팀 / BE엔지니어** `[개발, 책임]`  
*2020.01 ~ 현재 (총 6년 9개월, 재직 중 / 기준: 2026년 9월 30일)*

**담당업무**
- OTA 관제 시스템 개발 및 운영
- OTA 서비스 플랫폼 개발 및 운영

---

#### 1. OTA 서비스 플랫폼 개발 프로젝트
- **기간**: 2025.04 ~ 2025.11 [8개월]
- **기술 스택**: `Java`, `Spring Boot`, `Kubernetes`, `Apache Kafka`, `Redis`, `PostgreSQL`, `GitLab`, `Jenkins`, `ArgoCD`, `Grafana`, `Prometheus`, `Loki`, `Jaeger`

##### 🎯 주요 성과 지표 (Key Results)
| 구분 | 개선 전 | 개선 후 | 주요 성과 및 기여 내용 |
| :--- | :--- | :--- | :--- |
| **아키텍처 분리** | 모놀리식 관제 서버 종속 | **독립 플랫폼 디커플링** | 외부 데이터 제공 I/F를 완전 추출·분리하여 결합도 해소 및 독립 배포 주기 확보 |
| **인프라 보안 및 라우팅** | Nginx Ingress Controller | **Traefik 전환** | Ingress 보안 취약점 이슈 대응 및 클라우드 네이티브 환경에 맞춘 동적 트래픽 라우팅 보안 강화 |
| **관측 가능성 (APM)** | 단순 로그 중심 모니터링 | **Full-Stack Observability** | Prometheus, Grafana, Loki, Jaeger 기반 풀스택 APM 구축 및 알람 연동으로 장애 탐지(MTTR) 단축 |
| **품질 및 안정성** | 단위 테스트 부재 구간 존재 | **테스트 커버리지 확대** | 결함 분석 기반 버그 개선 및 유닛/통합 테스트 커버리지 확대로 서비스 무장애 배포 달성 |

##### 📋 주요 업무 및 상세 내용
- **OTA 서비스 플랫폼 신규 개발**
  - 기존 관제 서버 중 외부 데이터 제공 인터페이스만 추출하여 독자적인 OTA 서비스 플랫폼 설계 및 개발
  - Java, Spring Boot, Kubernetes 환경에서 대고객 트래픽을 안정적으로 적재·조회할 수 있는 고가용 REST API 서비스 구축
  - Grafana, Prometheus, Loki, Jaeger를 연계하여 메트릭, 분산 추적(APM), 분산 로그 모니터링 체계 구축 및 실시간 알람 설정
- **프로젝트 사후 개선 및 운영 안정화**
  - 사후 결함 원인 분석 및 버그 수정, 유닛/통합 테스트 커버리지 확충을 통한 코드 신뢰성 강화
  - Kubernetes 및 인프라 컴포넌트 버전 업그레이드 수행
  - 보안 취약점 이슈 대응을 위해 Nginx Ingress Controller를 Traefik으로 전환하여 인프라 보안성 강화 및 트래픽 라우팅 운영 안정성 확보

---

#### 2. 제어기 OTA 관제 시스템 개발 프로젝트 및 고도화
- **기간**: 2021.04 ~ 현재 [5년 6개월, 재직 중 / 기준: 2026년 9월 30일]
- **기술 스택**: `Go`, `Apache Kafka`, `Redis`, `PostgreSQL`, `MongoDB`, `GitLab`, `Jenkins`, `gRPC`, `Elasticsearch`, `Kibana`

##### 🎯 주요 성과 지표 (Key Results)
| 구분 | 개선 전 | 개선 후 | 주요 성과 및 기여 내용 |
| :--- | :--- | :--- | :--- |
| **메시지 병렬 처리량 (CMPS)** | 1,200 CMPS | **14,400 CMPS** | **동일 리소스 내 처리 성능 12배 (1,100%↑) 개선**<br>(Kafka-서버 간 gRPC 서버 Streaming 기반 메시징 허브 개발) |
| **관제 통계 쿼리 응답 속도** | 40 ~ 60초 | **1초 이내** | **평균 응답 속도 최대 96% 단축**<br>(PostgreSQL 인덱스 튜닝 및 핫(Hot) 테이블 분리 설계) |
| **테스트 신뢰성 및 검증** | 부분 테스트 환경 | **커버리지 90% 이상 달성** | **Testcontainers 기반 테스트 모듈 개발**을 통해 유닛·통합 테스트를 작성하고, 비즈니스 로직 검증과 테스트 커버리지 90% 동시 확보 |
| **메모리 누수 및 안정성** | 런타임 메모리 누수 발생 | **누수 원천 차단 및 최적화** | **Golang pprof 프로파일링**을 통한 힙/고루틴 메모리 누수 지점 규명 및 구조 리팩토링 |
| **인프라 연속성 (Migration)** | 클라우드 자원 제한 직면 | **무중단 데이터 마이그레이션 100%** | 온프레미스 인프라 이관 시 무중단 데이터 마이그레이션 완수 (서비스 가용성 유지) |
| **DevSecOps 파이프라인** | 단순 빌드/배포 스크립트 | **품질/보안 내재화 파이프라인** | GitLab CI에 테스트, SonarQube, Black Duck 취약점 검사 자동화 통합 |

##### 📋 주요 업무 및 상세 내용
- **제어기 OTA 관제 시스템 개발 (2021.04 ~ 2021.11)**
  - Golang 및 Apache Kafka 기반의 실시간 제어기 OTA 관제 / 모니터링 웹 시스템 설계 및 개발
  - 대용량 모니터링 데이터 처리를 위한 데이터베이스 테이블 설계 및 웹 / 외부 시스템 연동 API 구현
  - 대규모 모니터링 집계 데이터 저장을 위한 데이터 구조 및 쿼리 최적화
  - GitLab CI + Jenkins를 활용한 자동 빌드/배포 파이프라인 구축
- **제어기 OTA 2세대 개발 및 고도화 (2021.12 ~ 현재)**
  - **아키텍처 및 통신 프로토콜 재설계**: 집계 성능 한계를 개선하기 위해 테이블 구조를 전면 재설계하고, 신규 OTA 기능을 반영한 통신 프로토콜 설계 및 1세대 규격 하위 호환 구조 구현
  - **gRPC 스트리밍 기반 메시징 허브 개발**: Kafka와 서버 사이에 gRPC 서버 Streaming 기반 메시징 허브를 구축하여 파티션 튜닝과 함께 메시지 병렬 처리 효율을 비약적으로 개선 (**CMPS 12배 향상: 1,200 → 14,400 CMPS**)
  - **DB 성능 최적화**: PostgreSQL 관제 통계 쿼리 조회를 분석하여 인덱스 튜닝 및 Hot 테이블 설계를 적용, **평균 응답 시간을 40~60초에서 2초 이내로 단축**
  - **메모리 프로파일링 및 구조 개선**: Golang pprof 도구를 활용해 런타임 메모리 누수 원인을 추적하고 아키텍처를 개선하여 시스템 안정성 확보
  - **Testcontainers 기반 테스트 모듈 개발 및 품질 검증**: testify 및 Testcontainers를 도입하여 격리된 실제 환경 기반의 테스트 모듈을 직접 개발. 이를 바탕으로 유닛 및 통합 테스트를 체계적으로 작성하여 비즈니스 로직에 대한 신뢰도 높은 검증과 더불어 **모듈별 테스트 커버리지 90% 이상**을 동시 달성
  - **DevSecOps 파이프라인 고도화**: GitLab CI를 고도화하여 빌드, 테스트, SonarQube(정적 코드 분석), Black Duck(오픈소스 취약점 분석)을 단일 파이프라인으로 통합 운영
  - **관측 가능성(Observability) 및 인프라 이관**: Elasticsearch 및 Kibana를 도입해 분산 로그와 관제 데이터를 수집·시각화하고, 클라우드 자원 제한 환경에서 온프레미스 인프라로의 무중단 데이터 마이그레이션 성공

---

#### 3. ccSP (커넥티드 카 서비스 플랫폼) 운영 및 개발
- **기간**: 2020.03 ~ 2021.03 [1년 1개월]
- **기술 스택**: `Go`, `Node.js`, `Apache Kafka`, `Redis`, `PostgreSQL`, `MongoDB`, `tyk APIGW`, `GitLab`, `Jenkins`

##### 🎯 주요 성과 지표 (Key Results)
| 구분 | 주요 성과 및 기여 내용 |
| :--- | :--- |
| **인증 안정성 개선** | OAuth 2.0 기반 사용자 가입/로그인/인가 프로세스 운영, 브라우저 및 앱 버전별 인증 버그 개선으로 인증 실패율 최소화 |
| **파트너사 확장 아키텍처** | 차량-홈 네트워크/통신사 간 연동 규격을 모듈화하고 tyk APIGW 기반 인증 연동 아키텍처를 구축해 신규 파트너사 연동 기간 단축 |

##### 📋 주요 업무 및 상세 내용
- **CCS 통합 계정 시스템**
  - Golang 기반 OAuth 2.0 인증 프로토콜을 적용한 대규모 사용자 계정/인가 서버 개발 및 안정적 운영
  - 사용자 앱·웹 및 브라우저 버전에 따른 프론트엔드 연동 이슈 분석 및 인증 흐름 최적화
  - 대고객 계정 정보 관리를 위한 백오피스 관리자 페이지 개발
- **차량 IoT 시스템**
  - 차량 - 홈 네트워크 / 통신사 장비 간 통신 API 서버 개발 및 운영
  - 신규 파트너사 확장을 위한 파트너사별 커스텀 인증 연동 아키텍처 구현
  - 차량 - 서버 간 맞춤형 통신 프로토콜 설계 및 REST API 개발 (Node.js/TypeScript, PostgreSQL, tyk APIGW)

---

### 웨이티즈
**BE엔지니어 (인턴)** `[개발, 인턴]`  
*2017.06 ~ 2017.08 [3개월]*

- **업무 내용**: V2X 프로토콜 개발 회사 개발 보조
- **프로젝트**: 전문 파싱 스크립트 개발
- **기술 스택**: `Python`, `MongoDB`
- **주요 업무 및 성과**:
  - 회사에서 수집 중인 V2X 및 LiDAR Raw 데이터 패킷을 분석하여 필요한 데이터를 추출하는 파싱 스크립트 프로그램 개발
  - Raw 데이터 파싱 및 MongoDB 자동 적재 데이터 파이프라인 스크립트 구현

---

## 🛠 Tools & Skills

| 분야 | 보유 기술 및 역량 |
| :--- | :--- |
| **Language** | **Go** `(중)`, Java `(하)`, JavaScript / TypeScript `(하)`, Python `(하)` |
| **Framework & Libraries** | **Echo Framework** `(중)`, Spring Boot / Spring Framework `(하)`, Node.js `(하)`, gRPC |
| **Infra / DB / Cloud** | **PostgreSQL** `(중)`, MongoDB `(하)`, Kubernetes `(하)`, Redis `(하)`, Traefik, Nginx `(하)`, AWS `(하)` |
| **CI / CD & Test** | GitLab CI, Jenkins, ArgoCD, SonarQube, Black Duck, Testcontainers |
| **Monitoring** | Elasticsearch, Kibana, Grafana, Loki, Prometheus, Jaeger |
| **Tools & IDEs** | Jira, Confluence, GoLand, IntelliJ, DataGrip, VS Code, GitLab Copilot, Claude |
| **Interests** | Cloud Native (Kubernetes, AWS), gRPC, DevSecOps, AI & LLM |

---

## 📜 Certificate

| 자격증 명칭 | 발급 기관 | 취득 / 유효 기간 | 자격 번호 |
| :--- | :--- | :--- | :--- |
| **Certified Kubernetes Administrator (CKA)** | The Linux Foundation | 2024.06.16 ~ 2026.06.11 | `LF-ulvzwb6ty0` |
| **Certified Kubernetes Application Developer (CKAD)** | The Linux Foundation | 2024.10.14 ~ 2026.10.14 | `LF-qzjqs3j8g2` |
| **AWS Certified Solutions Architect – Associate** | Amazon Web Services (AWS) | 2025.09.11 ~ 2027.09.11 | `5a45b4ac88564a8998797ced8acc251a` |
| **정보처리기사** | 한국산업인력공단 | 2019.08.16 | `19202240537Y` |

---

## 🏆 Experience

### 2019 단국대학교 소확행 해커톤
- **기관 / 행사**: 단국대학교 / 소확행
- **기간**: 2019.05.31 ~ 2019.06.01
- **프로젝트**: 중고 명품 대여 플랫폼
- **기술 스택**: `Vue.js`, `Node.js`, `MySQL`, `AWS S3`
- **상세 링크**: [온오프믹스 행사 페이지](https://onoffmix.com/event/178740?srsltid=AfmBOopLIVBPFD1HKF7CaTVhqYgJaLPC5lUDRu6us8Z6tuN9KBiqUZRP)

---

## 🎓 Education

| 학교 | 전공 / 구분 | 재학 기간 |
| :--- | :--- | :--- |
| **아주대학교** | 소프트웨어학과 (학사) | 2014.03 ~ 2020.01 |
| **수지고등학교** | - | 2011.03 ~ 2014.02 |
