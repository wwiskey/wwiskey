<div align="center">

# wwiskey

### Data Engineering · Data Applications

**데이터를 정리하고, 검색과 분석이 가능한 서비스로 연결합니다.**

Python · SQL · Django · React<br />
PostgreSQL · Redis · Microsoft Fabric · Power BI

[About](#about) · [Skills](#skills) · [Projects](#projects) · [ITC 시연 보기](https://github.com/wwiskey/ITC#서비스-화면)

</div>

---

## About

데이터 엔지니어링과 데이터 기반 웹 서비스 개발을 중심으로 경험을 쌓고 있습니다. 데이터를 저장하는 구조부터 API, 검색, 시각화까지 연결해 사용자가 필요한 정보를 탐색할 수 있는 서비스를 만드는 데 관심이 있습니다.

현재는 **Django·PostgreSQL과 React 기반 데이터 탐색 서비스**를 개발하며, 검색·캐싱·데이터 조회와 화면의 상호작용을 다루고 있습니다. ITC 팀 프로젝트에서는 **PM & Data Engineer**를 맡아 Microsoft Fabric 데이터 파이프라인과 Power BI 운영 분석을 구성했습니다.

## Skills

프로젝트에서 다뤄온 기술과 작업입니다.

| 분야 | 기술 | 다룬 작업 |
| :--- | :--- | :--- |
| Data & Backend | Python · SQL · Django · Django REST Framework · PostgreSQL | 데이터 모델, REST API, 필터·집계·페이지네이션 |
| Search & Performance | Redis · Meilisearch · PostgreSQL Index | 통합 검색·자동완성, 캐시, 인덱스와 조회 구조 |
| Frontend & Visualization | JavaScript · React · Vite · Chart.js · SVG | 데이터 탐색 UI, 연동 필터, 차트, 결과 내보내기 |
| Data Engineering & BI | Azure SQL · Microsoft Fabric · Dataflow · Lakehouse · Power BI | 수집·변환·적재, 분석용 테이블, 대시보드 |
| Delivery & Collaboration | Docker · Compose · Nginx · GitHub Actions · Git | 컨테이너 구성, CI/CD, PR 기반 작업·검증 |

## Projects

### 데이터 탐색·분석 포털

**진행 중 · 비공개 프로젝트**

여러 유형의 데이터를 통합 검색하고, 조건별로 탐색하며, 차트와 표로 분석 결과를 확인하는 웹 서비스입니다.

- **데이터 조회:** Django API와 PostgreSQL 모델·인덱스, Redis 캐시, Meilisearch 검색 연계
- **탐색 경험:** React 기반 검색·필터·정렬·페이지네이션, 차트와 표의 선택 상태 연동
- **시각화·출력:** Chart.js와 SVG 차트, 데이터·이미지 내보내기
- **개발·배포:** Docker 기반 구성과 GitHub Actions 검사·테스트·빌드·배포 흐름

### [ITC · Investment Training Crypto](https://github.com/wwiskey/ITC)

**2025.08–09 · 6인 팀 · PM & Data Engineer**

실시간 모의투자와 과거 시장 시나리오, 뉴스·백과사전·리포트를 연결한 암호화폐 투자 학습 플랫폼입니다.

| 담당 영역 | 주요 경험 |
| :--- | :--- |
| 데이터 파이프라인 | Azure SQL → Fabric Dataflow → Lakehouse → 분석용 Fact Table → Power BI |
| 운영 분석 | 고객 특성·선호 코인·주문 방식·거래량 분석, 1시간 단위 갱신 대시보드 |
| 제품·프로젝트 관리 | 로드맵·리스크 관리, 세 가지 시장 시나리오와 학습 콘텐츠 설계 |

웹 서비스·거래 엔진·인증·AI·인프라는 팀 공동 산출물입니다. 위 표는 제가 담당한 영역이며, 현재는 기존 외부 리소스가 삭제되어 **소스와 과거 시연을 보관한 프로젝트**입니다.

[프로젝트 소개](https://github.com/wwiskey/ITC/blob/main/README.md) · [시연 영상](https://github.com/wwiskey/ITC#서비스-화면) · [소스 코드](https://github.com/wwiskey/ITC/tree/main/src) · [재구축 가이드](https://github.com/wwiskey/ITC/blob/main/docs/RECOVERY_GUIDE.md)
