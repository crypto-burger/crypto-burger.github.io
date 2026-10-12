---
title: "미니 프로젝트 선정: 유통량 모니터링 대시보드 & STO 조각투자 시뮬레이터"
date: 2026-10-12
author: "phillipKim96"
categories: [미니 프로젝트]
---

사업 3명 + 개발 1명으로 구성된 팀입니다. 완전 초기 단계인 만큼 커리어에 도움이 될 만한 쉬운 프로젝트부터 시작하기로 하고, 후보 4개 중 2개를 골랐습니다. (스테이블코인 결제 데모 등 다른 후보도 검토했지만, 팀 역량과 일정을 고려해 최종적으로 아래 2개로 판단했습니다.)

## 핵심 요약

### 1. 토큰 유통량/언락 모니터링 미니 대시보드

세션에서 다룬 락업·인플레이션·유통량 개념을 데이터 제품으로 만들어보는 프로젝트입니다.

- **사업팀(3명)**: 추적할 코인 3~5개 선정 기준 수립 → 공개 API/공시 자료에서 유통 계획 데이터 수집·정리 → 매주 "유통량 변화 인사이트" 짧은 글 작성
- **개발자(1명)**: CoinGecko/Etherscan 등 무료 API로 유통량·언락 일정을 가져와 표·그래프로 보여주는 정적 대시보드 제작
- **결과물**: 대시보드 웹페이지 + 주간 인사이트 글 1~2편
- **예상 소요**: 1~2주
- **참고 자료**:
  - [CoinGecko API 문서 - Circulating Supply Chart](https://docs.coingecko.com/reference/coins-id-circulating-supply-chart)
  - [Etherscan API 문서 - Token Supply](https://docs.etherscan.io/openapi/api-reference/endpoint/tokensupply.json)
  - [Tokenomist(구 Token Unlocks) - 언락 캘린더 대시보드 사례](https://tokenomist.ai/learn/glossary-term/unlock-calendar)

### 2. STO(토큰증권) 조각투자 시장 분석 + 미니 지분 시뮬레이터

2026년 1월 전자증권법·자본시장법 개정안이 국회를 통과하면서 시의성이 높아진 주제입니다. 실제 증권을 다루지는 않고, 교육용 시뮬레이터로 범위를 좁혔습니다.

- **사업팀(3명)**: 국내 STO/조각투자 플랫폼 현황 비교표 작성(카사·펀블 등 폐업 현황 포함) → 2027년 시행 예정 제도 요약 → 가상 자산을 조각투자하는 케이스 스터디 1건 작성(예: 사무실 한 층을 100주로 나누는 경우)
- **개발자(1명)**: 자산 1개를 N개의 지분 토큰으로 나누고 각자 보유 비율을 보여주는 테스트넷 기반 웹 시뮬레이터 제작
- **결과물**: 시장 분석 리포트 + 지분 시뮬레이터 데모
- **예상 소요**: 1~2주
- **참고 자료**:
  - [금융위원회, "토큰증권 발행·유통 규율체계 정비방안" (2023.02)](https://www.smallake.kr/wp-content/uploads/2023/02/230203토큰-증권-발행-유통-규율체계-정비방안.pdf)
  - [블록미디어, "STO 개정안, 국회 소위 통과" (2025.12)](https://www.blockmedia.co.kr/archives/1012991)
  - [비즈한국, 카사코리아 서비스 종료 기사 (2026.07)](https://bizhankook.com/articles/kasa-service-termination.html)
