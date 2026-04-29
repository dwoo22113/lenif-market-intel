# 🪑 LENIF 의자 시장 인텔리전스

> 매일 08:00 KST 자동 발행되는 단일 HTML 리포트 — GitHub Pages 호스팅.

## 진입점

- 최신 리포트: **[index.html](./index.html)**
- 아카이브 (일별 history): [archive/](./archive/)

## 갱신 주기

매일 08:00 KST. LENIF 자동화 시스템에서 다음 단계로 빌드 후 push:
1. 네이버 데이터랩 · 검색광고 RelKwdStat · 검색 API 수집
2. 자사 광고 KPI (네이버 검색광고 conversion_detail) 통합
3. 듀얼 ROAS (총 + 구매완료) 산출 + 추세 분석
4. HTML 생성 + git push → GitHub Pages 배포

## 표시 규칙

🔢 **ROAS 듀얼 표시 절대 규칙**
모든 ROAS 는 **총 ROAS** (구매+장바구니, LENIF 추적 시점 = 모든 전환 합) 와
**구매완료 ROAS** (실 매출 = `conversion_type='purchase'`) 두 개를 모두 표시.
LENIF 옵티마이저 target 350% 는 **구매완료 기준**.

## 자동 갱신 안내

페이지를 새로고침하면 항상 최신 데이터. 보통 매일 08:00~08:05 KST 사이 갱신.
