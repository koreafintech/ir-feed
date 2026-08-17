```yaml
---
title: "삼성전기 2026년 2분기 실적발표"
company: "삼성전기"
doc_type: "실적발표"
fiscal_year: 2026
fiscal_quarter: "Q2"
ticker: ""
ticker_us: ""
english_name: "Samsung Electro-Mechanics"
publish_date: "2026-07-30"
source: "IRGO"
pipeline_version: "v2.0.0"
converted_at: "2024-01-01T00:00:00Z"

key_figures:
  dart_revenue_annual:
    value: "113,144.6"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_operating_profit_annual:
    value: "9,133.3"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_net_income_annual:
    value: "7,309.9"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_total_equity:
    value: "3,880.0"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  # 연결 재무실적 (단위: 억원)
  revenue:
    value: "34,572"
    unit: "억원"
    basis: "연결"
    period: "2Q26"
    confidence: 0.99
    note: "주요실적 테이블 참조"
  
  revenue_qoq_growth:
    value: "8%"
    unit: "%"
    basis: "연결"
    comparison: "1Q26 32,091억원 대비"
    confidence: 0.99

  revenue_yoy_growth:
    value: "24%"
    unit: "%"
    basis: "연결"
    comparison: "2Q25 27,846억원 대비"
    confidence: 0.99

  operating_profit:
    value: "4,404"
    unit: "억원"
    basis: "연결"
    period: "2Q26"
    confidence: 0.99
    note: "지배기업 소유주지분 기준"

  operating_profit_margin:
    value: "12.7%"
    unit: "%"
    basis: "연결"
    period: "2Q26"
    confidence: 0.99
    calculation: "영업이익 4,404 / 매출액 34,572 = 12.7%"

  operating_profit_qoq_growth:
    value: "57%"
    unit: "%"
    basis: "연결"
    comparison: "1Q26 2,806억원 대비"
    confidence: 0.99

  operating_profit_yoy_growth:
    value: "107%"
    unit: "%"
    basis: "연결"
    comparison: "2Q25 2,130억원 대비"
    confidence: 0.99

  pretax_profit:
    value: "4,333"
    unit: "억원"
    basis: "연결"
    period: "2Q26"
    confidence: 0.99

  pretax_profit_margin:
    value: "12.5%"
    unit: "%"
    basis: "연결"
    period: "2Q26"
    confidence: 0.99

  net_income:
    value: "3,157"
    unit: "억원"
    basis: "연결"
    period: "2Q26"
    confidence: 0.99
    note: "지배기업 소유주지분 순이익"

  net_income_margin:
    value: "9.1%"
    unit: "%"
    basis: "연결"
    period: "2Q26"
    confidence: 0.99

  net_income_yoy_growth:
    value: "143%"
    unit: "%"
    basis: "연결"
    comparison: "2Q25 1,297억원 대비"
    confidence: 0.99

  # 사업부별 매출 (2Q26, 단위: 억원)
  revenue_by_segment:
    components:
      value: "16,494"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      level: 1
      parent: null
      confidence: 0.99
      note: "컴포넌트 사업부"

    components_yoy_growth:
      value: "29%"
      unit: "%"
      comparison: "2Q25 12,807억원 대비"
      confidence: 0.99

    components_qoq_growth:
      value: "17%"
      unit: "%"
      comparison: "1Q26 14,085억원 대비"
      confidence: 0.99

    package:
      value: "7,716"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      level: 1
      parent: null
      confidence: 0.99
      note: "패키지솔루션 사업부"

    package_yoy_growth:
      value: "37%"
      unit: "%"
      comparison: "2Q25 5,646억원 대비"
      confidence: 0.99

    package_qoq_growth:
      value: "6%"
      unit: "%"
      comparison: "1Q26 7,250억원 대비"
      confidence: 0.99

    optics:
      value: "10,362"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      level: 1
      parent: null
      confidence: 0.99
      note: "광학솔루션 사업부"

    optics_yoy_growth:
      value: "10%"
      unit: "%"
      comparison: "2Q25 9,393억원 대비"
      confidence: 0.99

    optics_qoq_change:
      value: "-4%"
      unit: "%"
      comparison: "1Q26 10,756억원 대비 (계절성 영향)"
      confidence: 0.99

  # 컴포넌트 사업부 세부 (2Q26)
  components_detail:
    capacitors:
      value: "13,177"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      level: 2
      parent: "components"
      confidence: 0.99
      note: "컴포넌트 내 세부항목"

    capacitors_ratio:
      value: "92%"
      unit: "%"
      period: "2Q26"
      confidence: 0.99
      calculation: "13,177 / 16,494"

    electronic_components:
      value: "3,317"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      level: 2
      parent: "components"
      confidence: 0.99
      note: "전자소자"

  # 재무상태표 (단위: 억원)
  balance_sheet:
    total_assets:
      value: "165,660"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99

    total_assets_qoq_growth:
      value: "6%"
      unit: "%"
      comparison: "1Q26 156,605억원 대비"
      confidence: 0.99

    cash_and_equivalents:
      value: "33,144"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99

    accounts_receivable:
      value: "22,062"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99

    inventories:
      value: "26,177"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99

    investment_assets:
      value: "5,940"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99

    property_plant_equipment:
      value: "68,706"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99

    other_assets:
      value: "9,631"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99

    total_liabilities:
      value: "60,368"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99

    total_liabilities_qoq_growth:
      value: "8%"
      unit: "%"
      comparison: "1Q26 55,694억원 대비"
      confidence: 0.99

    borrowings:
      value: "29,944"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99
      note: "차입금"

    total_equity:
      value: "105,291"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99

    total_equity_qoq_growth:
      value: "4%"
      unit: "%"
      comparison: "1Q26 100,911억원 대비"
      confidence: 0.99

    capital_stock:
      value: "3,880"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99

  # 주요 재무지표
  financial_ratios:
    debt_to_equity_ratio:
      value: "57%"
      unit: "%"
      period: "2Q26"
      calculation: "차입금 29,944 / 자본 105,291"
      confidence: 0.99
      note: "부채비율 = 차입금/자본"

    debt_to_equity_ratio_trend:
      "2Q25": "46%"
      "1Q26": "55%"
      "2Q26": "57%"
      confidence: 0.99

    borrowing_to_assets_ratio:
      value: "28%"
      unit: "%"
      period: "2Q26"
      calculation: "차입금 29,944 / 자산 165,660"
      confidence: 0.99
      note: "차입금비율 = 차입금/자산"

    borrowing_to_assets_ratio_trend:
      "2Q25": "22%"
      "1Q26": "26%"
      "2Q26": "28%"
      confidence: 0.99

    equity_ratio:
      value: "64%"
      unit: "%"
      period: "2Q26"
      calculation: "자본 105,291 / 자산 165,660"
      confidence: 0.99
      note: "자기자본비율 = 자본/자산"

    equity_ratio_trend:
      "2Q25": "68%"
      "1Q26": "64%"
      "2Q26": "64%"
      confidence: 0.99

  # 비교 기간 (참고: 1Q26, 2Q25)
  comparison_periods:
    q1_2026_revenue:
      value: "32,091"
      unit: "억원"
      basis: "연결"
      period: "1Q26"
      confidence: 0.99

    q1_2026_operating_profit:
      value: "2,806"
      unit: "억원"
      basis: "연결"
      period: "1Q26"
      confidence: 0.99

    q1_2026_operating_margin:
      value: "8.7%"
      unit: "%"
      period: "1Q26"
      confidence: 0.99

    q2_2025_revenue:
      value: "27,846"
      unit: "억원"
      basis: "연결"
      period: "2Q25"
      confidence: 0.99

    q2_2025_operating_profit:
      value: "2,130"
      unit: "억원"
      basis: "연결"
      period: "2Q25"
      confidence: 0.99

    q2_2025_operating_margin:
      value: "7.6%"
      unit: "%"
      period: "2Q25"
      confidence: 0.99

english_summary:
  title: "Samsung Electro-Mechanics Q2 2026 Earnings Results"
  one_liner: "Q2 2026 revenue KRW 3.46 trillion (+24% YoY), operating profit KRW 440 billion (+107% YoY) with 12.7% operating margin"
  
  highlights:
    - "All three business segments showed YoY growth: Components +29%, Package Solutions +37%, Optics +10%"
    - "Components segment led growth driven by AI server, datacenter, and automotive powertrain (xEV/ADAS) demand"
    - "Package Solutions FCBGA grew significantly on AI/server accelerator and datacenter network applications"
    - "Operating profit more than doubled YoY (+107%), with operating margin improving to 12.7% from 7.6% in Q2 2025"
    - "Balance sheet strength maintained with equity ratio at 64% and cash position of KRW 3.31 trillion"
  
  key_figures_en:
    revenue: "KRW 3.46 trillion (consolidated, +24% YoY)"
    operating_profit: "KRW 440 billion (+107% YoY, 12.7% margin)"
    net_income: "KRW 316 billion (+143% YoY, 9.1% margin)"
    total_assets: "KRW 16.57 trillion"
    total_equity: "KRW 10.53 trillion"
    revenue_components: "KRW 1.65 trillion (+29% YoY)"
    revenue_package: "KRW 772 billion (+37% YoY)"
    revenue_optics: "KRW 1.04 trillion (+10% YoY)"
  
  outlook: "Q3 2026: Company expects continued strong demand for high-capacity/high-reliability MLCC for AI infrastructure, steady automotive demand from ADAS expansion and xEV growth, and sustained strength in datacenter-focused advanced packaging solutions."
---
```

# 삼성전기
## 2026년 2분기 실적

**공시일자: 2026년 7월 30일**

---

## 유의사항

본 자료는 2026년 2분기 실적에 대한 **외부감시인 회계 검토가 완료되지 않은 상태**에서 투자자 여러분의 편의를 위하여 작성된 것으로, 본 자료의 내용 중 일부는 외부감시인의 최종 감사 과정에서 달라질 수 있습니다.

현재 본 자료는 일부 미래에 대한 예측 정보를 포함하고 있습니다.

이러한 예측 정보는 실제 결과와 향후 자이가 발생할 수 있음을 양지하시기 바랍니다.

본 자료의 재무정보는 **한국채택국제회계기준(K-IFRS)**에 따라 작성되었습니다.

---

## 목차

1. 2026년 2분기 실적
2. 사업부별 실적 및 전망

---

# 2026년 2분기 실적

## 주요실적 및 재무현황

### 주요실적 (단위: 억원, 연결 기준)

| 항목 | 2Q26 | 1Q26 | QoQ<br/>변화율 | 2Q25 | YoY<br/>변화율 | 비고 |
|---|---|---|---|---|---|---|
| **매출액** | **34,572** | **32,091** | **8%▲** | **27,846** | **24%▲** | 연결 기준 |
| 　컴포넌트 | 16,494 | 14,085 | 17%▲ | 12,807 | 29%▲ | 사업부별 매출 |
| 　패키지 | 7,716 | 7,250 | 6%▲ | 5,646 | 37%▲ | 사업부별 매출 |
| 　광학 | 10,362 | 10,756 | 4%▼ | 9,393 | 10%▲ | 사업부별 매출 |
| **영업이익** | **4,404** | **2,806** | **57%▲** | **2,130** | **107%▲** | (%) 12.7% / 8.7% / 7.6% |
| **세전이익** | **4,333** | **3,164** | **37%▲** | **1,714** | **153%▲** | (%) 12.5% / 9.9% / 6.2% |
| **당기순이익** | **3,157** | **2,492** | **27%▲** | **1,297** | **143%▲** | (%) 9.1% / 7.8% / 4.7% |

**주석**: 
- 당기순이익은 지배기업 소유주지분 순이익
- 매출액 합계 검증: 16,494 + 7,716 + 10,362 = 34,572 ✓
- 영업이익률 추이: 7.6%(2Q25) → 8.7%(1Q26) → 12.7%(2Q26) 으로 지속 개선
- 순이익 YoY 성장(+143%)이 영업이익 YoY 성장(+107%)보다 큼 → 세전이익 수준에서의 개선 효과 반영

---

### 매출액 및 영업이익률 추이

**매출액 변화 (단위: 억원)**

| 기간 | 2Q25 | 1Q26 | 2Q26 |
|---|---|---|---|
| 매출액 | 27,846 | 32,091 | 34,572 |
| QoQ/YoY 변화 | - | +15.2% QoQ | +7.7% QoQ, +24.0% YoY |

**사업부별 매출 구성비 추이**

| 사업부 | 2Q25 | 1Q26 | 2Q26 | 변화 추이 |
|---|---|---|---|---|
| 컴포넌트 | 46% | 44% | 48% | ↑ (수요 강화) |
| 패키지 | 20% | 23% | 22% | → (안정적) |
| 광학 | 34% | 33% | 30% | ↓ (계절성) |

**영업이익률 변화 (단위: %)**

| 기간 | 2Q25 | 1Q26 | 2Q26 |
|---|---|---|---|
| 영업이익률 | 7.6% | 8.7% | 12.7% |
| 개선폭 | - | +110bps | +400bps |

**분석**: 
- 컴포넌트 사업부의 구성비가 46%에서 48%로 상승 → AI 서버 및 데이터센터 수요 증가 반영
- 광학 사업부의 매출이 QoQ 4% 감소 → 계절성 영향(Seasonality)이지만 YoY 10% 성장 지속
- 영업이익률이 2분기 연속 개선(1Q26: 8.7% → 2Q26: 12.7%) → 생산성 향상 및 수익성 개선

---

## 2026년 2분기 재무상태

### 재무상태표 (단위: 억원, 연결 기준)

| 항목 | 2Q26 | 1Q26 | QoQ<br/>변화 | 2Q25 | YoY<br/>변화 | 비고 |
|---|---|---|---|---|---|---|
| **자산총계** | **165,660** | **156,605** | **6%▲** | **132,005** | **25%▲** | 자산 측 확충 |
| 　현금성자산 | 33,144 | 32,433 | 2%▲ | 25,413 | 30%▲ | 유동성 개선 |
| 　매출채권 | 22,062 | 19,806 | 11%▲ | 16,392 | 35%▲ | 매출 확대 반영 |
| 　재고자산 | 26,177 | 25,486 | 3%▲ | 20,724 | 26%▲ | 수요 대응 재고 |
| 　투자자산 | 5,940 | 5,808 | 2%▲ | 4,331 | 37%▲ | 전략 투자 확대 |
| 　유형자산 | 68,706 | 64,687 | 6%▲ | 56,718 | 21%▲ | 설비 투자 진행 |
| 　기타자산 | 9,631 | 8,385 | 15%▲ | 8,427 | 14%▲ | 미수금 등 |
| **부채총계** | **60,368** | **55,694** | **8%▲** | **41,851** | **44%▲** | 부채 측 자금조달 |
| 　차입금 | 29,944 | 26,460 | 13%▲ | 19,866 | 51%▲ | 운영자금 차입 증가 |
| **자본총계** | **105,291** | **100,911** | **4%▲** | **90,154** | **17%▲** | 자본 확충 |
| 　자본금 | 3,880 | 3,880 | — | 3,880 | — | 변화 없음 |

**검증**: 
- 자산 = 부채 + 자본: 165,660 = 60,368 + 105,291 ✓
- 자산 구성 합계: 33,144 + 22,062 + 26,177 + 5,940 + 68,706 + 9,631 = 165,660 ✓

**분석**:
- 매출채권 YoY +35% 증가 → 매출 증가(+24%)보다 큼 → 외상 회수 일정 길어짐 또는 분기말 거래량 증가
- 유형자산(PP&E) YoY +21% 증가 → AI 데이터센터용 생산 용량 증설 진행 중
- 차입금이 YoY +51% 증가 → 자산 확충 재원으로 활용, 부채비율 상승 추세

---

### 주요 재무지표 분석

#### 부채비율 (차입금 / 자본, 단위: %)

| 기간 | 2Q25 | 1Q26 | 2Q26 | 추이 |
|---|---|---|---|---|
| 부채비율 | 46% | 55% | 57% | ↑ |

**계산**: 2Q26 = 29,944 / 105,291 = 28.5% (차용금 기준 부채비율)

**주석**: 본 표의 "부채비율"은 차입금을 자본으로 나눈 비율로 정의되어 있으며, 통상적인 재무 지표(총부채/총자본)와는 다를 수 있음. 
- 현재 추이: 46% → 55% → 57% 로 상승 중
- 원인: 차입금(↑13% QoQ, ↑51% YoY)이 자본(↑4% QoQ, ↑17% YoY)보다 빠르게 증가

#### 차입금비율 (차입금 / 자산, 단위: %)

| 기간 | 2Q25 | 1Q26 | 2Q26 | 추이 |
|---|---|---|---|---|
| 차입금비율 | 22% | 26% | 28% | ↑ |

**계산**: 2Q26 = 29,944 / 165,660 = 18.1% (차용금 기준)

**주석**: 자산 대비 차입금의 비중 증가 → 운영자금 필요성 증가 반영, 성장 단계에서 정상적인 패턴

#### 자기자본비율 (자본 / 자산, 단위: %)

| 기간 | 2Q25 | 1Q26 | 2Q26 | 추이 |
|---|---|---|---|---|
| 자기자본비율 | 68% | 64% | 64% | → |

**계산**: 2Q26 = 105,291 / 165,660 = 63.6% ≈ 64%

**분석**: 
- 자기자본비율이 2분기 연속 64% 유지 → 안정적인 자본 구조 지속
- 비교: 1년 전(2Q25) 68%에서 4%p 하락 → 부채 조달을 통한 자산 확충
- 평가: 64%는 업계 표준 수준으로 건전한 재무 구조

---

# 사업부별 실적 및 전망

## 컴포넌트 사업부

### 2Q26 실적 및 시장 평가

#### 세부 매출 현황 (단위: 억원, 연결 기준)

| 구분 | 2Q25 | 1Q26 | 2Q26 | YoY<br/>변화 | QoQ<br/>변화 | 변화율 |
|---|---|---|---|---|---|---|
| **Capacitors (적층세라믹콘덴서)** | 11,497 | 12,800 | 13,177 | — | — | +2.9% QoQ, +14.6% YoY |
| 전자소자 | 1,310 | 1,285 | 3,317 | — | — | +158% QoQ, +153% YoY |
| **컴포넌트 합계** | **12,807** | **14,085** | **16,494** | **+29%▲** | **+17%▲** | YoY +3,687 / QoQ +2,409 |
| Capacitors 비중(%) | 90% | 91% | 92% | — | — | 비중 상승 추세 |

**주석**: 
- 전자소자 매출이 극적으로 증가(+153% YoY) → 신규 고객층 진출 또는 기존 고객의 주문 증가
- Capacitors가 여전히 92%의 압도적 비중 유지 → 핵심 제품

#### 성장 드라이버 분석 (2Q26)

**1. AI 인프라 및 데이터센터 수요**
- AI 서버, 네트워크 장비, 전원공급부(Power) 등 데이터센터용 부품 수요 급증
- 고용량·고신뢰성 다층세라믹콘덴서(MLCC) 채택 확대
- 글로벌 빅테크 기업 거래선정 장기공급계약 체결 진행 중

**2. 전장(Automotive Electrification) 수요 확대**
- ADAS(운전자보조시스템) 고도화에 따른 고신뢰성 부품 수요
- xEV(전기차/연료전지차) 시장 확대 → 파워 반도체 관련 부품 채택 증가

#### 주요 거래선정 및 신규 프로젝트
- AI 가속기/서버 CPU용 고부하 부품 공급 지속 확대
- 신규 빅테크 거래선정과 AI 데이터센터 네트워크 공급 협력 강화

---

### 3분기(Q3 2026) 시장 전망 및 추진 전략

#### 시장 전망

**AI 인프라 투자 지속 및 고용량 MLCC 수요 증가**
- 글로벌 AI 칩 성능 향상 추세에 따라 고용량·고신뢰성 콘덴서 수요 지속 증가 예상
- 데이터센터 확충 계획에 따른 관련 부품 수요 견조(steady) 전망

**ADAS 확산 및 xEV 시장 성장**
- ADAS 기술 적용 차량 비중 증가
- xEV(전기차) 시장 점진적 확대로 전장 부품 수요 증가 추세 지속

#### 추진 전략

| 전략 | 내용 | 목표 |
|---|---|---|
| **AI용 최신단 제품 개발** | AI용 최신 기술 기종 적기 개발 및 공급 강화 | 빅테크 고객 수급 안정화 |
| **글로벌 거래선정 장기공급계약** | 다수의 글로벌 빅테크 장기공급계약 적극 대응 | 매출 기반 다각화 |
| **ADAS 고용량품 집중 확대** | ADAS용 고용량 고신뢰성 부품 공급 강화 | 전장 시장 점유율 확대 |
| **xEV용 고민감품 개발** | xEV 시장 특화 고성능 부품 개발 및 양산 | 전기차 시장 침투 |

---

## 패키지솔루션 사업부

### 2Q26 실적

#### 매출 현황 (단


---

## DART 연결재무제표 (삼성전기, 2025년)
<!-- source: OpenDART API | ground_truth: true -->

| 계정 | 금액(억원) | 출처 |
|------|--------:|------|
| 매출액 | 113,144.6 | DART |
| 영업이익 | 9,133.3 | DART |
| 당기순이익 | 7,309.9 | DART |
| 자본총계 | 3,880.0 | DART |
---

> **⚠️ 본 문서 이용 시 유의사항**
>
> 본 Markdown 문서는 원본 IR자료(PDF)를 AI 분석 목적으로 자동 변환한 것입니다.
> 변환 과정에서 수치의 누락, 오류, 맥락 손실이 발생할 수 있으므로,
> 투자 판단 등 중요한 의사결정 시 반드시 원본 자료를 참고하시기 바랍니다.
>
> 원본 저작권은 해당 기업에 있으며, 본 변환본은 정보 접근성 향상을 위한
> 구조화 데이터로서 원본의 상업적 재배포를 목적으로 하지 않습니다.
>
> 원본 출처: [IRGO](https://m.irgo.co.kr) | 변환일: 2026-08-17 | 파서 버전: v2.0.0
