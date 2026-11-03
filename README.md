<p align="center">
  <img src="assets/profile-hero-v2.png" alt="wwiskey — Data Engineering & Applications. Pipelines / Search / Interfaces." width="100%" />
</p>

<div align="center">

### 데이터 처리부터 서비스 구현과 배포까지.

데이터를 가공해 API와 검색·분석 화면으로 제공하고,<br />
컨테이너 실행 환경과 자동 배포 흐름을 함께 구성합니다.

</div>

<br />

<table>
  <tr>
    <td width="50%" valign="top">
      <p><picture><source media="(prefers-color-scheme: dark)" srcset="assets/labels/systems-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/labels/systems-light.svg" /><img src="assets/labels/systems-light.svg" alt="DATA SYSTEMS" width="360" height="68" /></picture></p>
      <h3>분석할 수 있는 데이터 구조</h3>
      <p>수집·변환·적재에서 분석용 테이블과 운영 대시보드까지, 데이터가 활용되는 흐름을 연결합니다.</p>
      <p><code>SQL</code> <code>Fabric</code> <code>Lakehouse</code> <code>Power BI</code></p>
    </td>
    <td width="50%" valign="top">
      <p><picture><source media="(prefers-color-scheme: dark)" srcset="assets/labels/applications-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/labels/applications-light.svg" /><img src="assets/labels/applications-light.svg" alt="DATA APPLICATIONS" width="360" height="68" /></picture></p>
      <h3>탐색할 수 있는 데이터 서비스</h3>
      <p>API·검색·캐시와 인터랙티브 화면을 연결해 데이터를 찾고, 비교하고, 해석하는 경험을 구성합니다.</p>
      <p><code>Django</code> <code>PostgreSQL</code> <code>React</code> <code>Redis</code></p>
    </td>
  </tr>
</table>

## Selected Work

### <img src="assets/icons/portal.svg" width="28" height="28" alt="" /> 데이터 탐색·분석 포털

<sub>IN PROGRESS · PRIVATE PROJECT</sub>

여러 유형의 데이터를 검색·필터링하고, 차트와 표로 비교할 수 있는 데이터 탐색·분석 포털을 개발하고 있습니다.

<br />

### <img src="assets/icons/itc.svg" width="28" height="28" alt="" /> [ITC · Investment Training Crypto](https://github.com/wwiskey/ITC)

<sub>2025.08–09 · TEAM PROJECT · PM / DATA ENGINEER · ARCHIVED</sub>

코인 투자 시뮬레이션으로 매매를 연습하고 경제를 공부하는 학습 서비스입니다.

[프로젝트 소개 ↗](https://github.com/wwiskey/ITC/blob/main/README.md) · [실행 시연 ↗](https://github.com/wwiskey/ITC#서비스-화면) · [소스 코드 ↗](https://github.com/wwiskey/ITC/tree/main/src)

<sub>현재는 외부 리소스가 삭제되어 소스와 과거 시연을 보관하고 있습니다.</sub>

## Capabilities

| 경험 | 적용한 방식 |
| :--- | :--- |
| **데이터 파이프라인** | Azure SQL 데이터를 Fabric Dataflow로 Lakehouse에 적재·변환하고, Power BI 운영 분석 대시보드 구성 |
| **API·DB** | Django·DRF로 검색·목록·상세 API 구현, PostgreSQL 복합·trigram 인덱스와 집계 쿼리 적용 |
| **검색·캐시** | Meilisearch 색인으로 통합 검색을 제공하고, Redis로 조회·집계 결과 캐싱 |
| **데이터 시각화** | React에서 검색·필터·차트·표를 연동하고, Chart.js·SVG 시각화와 결과 내보내기 구현 |
| **서비스 인프라** | Docker·Compose로 앱·검색·캐시 실행 환경 구성, Nginx·Gunicorn으로 HTTPS·정적 파일·API 제공 |
| **배포 자동화** | GitHub Actions로 의존성 점검·테스트·빌드를 연결하고, `main` 커밋 기준 배포·응답 확인 흐름 구성 |
