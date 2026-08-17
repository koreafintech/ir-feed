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
converted_at: "2024-12-19T00:00:00Z"

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
  # 주요 실적 - 2Q26 (연결기준)
  revenue:
    value: "34,572"
    unit: "억원"
    basis: "연결"
    period: "Q2 2026"
    confidence: 0.99
    note: "전년 동기(2Q25) 27,846억원 대비 24% 증가, 전분기(1Q26) 32,091억원 대비 8% 증가"
  
  operating_profit:
    value: "4,404"
    unit: "억원"
    basis: "연결"
    period: "Q2 2026"
    confidence: 0.99
    operating_margin: "12.7%"
    note: "전년 동기 2,130억원(7.6%) 대비 107% 증가, 전분기 2,806억원(8.7%) 대비 57% 증가"

  operating_margin:
    value: "12.7%"
    period: "Q2 2026"
    confidence: 0.99
    note: "전년 동기 7.6%, 전분기 8.7% 대비 증가"

  pre_tax_income:
    value: "4,333"
    unit: "억원"
    basis: "연결"
    period: "Q2 2026"
    confidence: 0.99
    pre_tax_margin: "12.5%"
    note: "전년 동기 1,714억원(6.2%) 대비 153% 증가, 전분기 3,164억원(9.9%) 대비 37% 증가"

  net_income:
    value: "3,157"
    unit: "억원"
    basis: "연결 (지배기업 소유주지분)"
    period: "Q2 2026"
    confidence: 0.99
    net_margin: "9.1%"
    note: "전년 동기 1,297억원(4.7%) 대비 143% 증가, 전분기 2,492억원(7.8%) 대비 27% 증가"

  # 사업부별 매출 - 2Q26
  revenue_by_segment:
    component:
      value: "16,494"
      unit: "억원"
      basis: "연결"
      period: "Q2 2026"
      level: 1
      parent: null
      confidence: 0.99
      yoy_growth: "29%"
      qoq_growth: "17%"
      note: "컴포넌트 사업부 - 산업/전장용 중심으로 매출 증가, AI 서버/네트워크/파워 등 데이터센터용 고성장"
    
    component_capacitors:
      value: "16,494"
      unit: "억원"
      basis: "연결"
      period: "Q2 2026"
      level: 2
      parent: "component"
      confidence: 0.99
      note: "컴포넌트 사업부 내 Capacitors 매출 (점유율 92%)"

    package:
      value: "7,716"
      unit: "억원"
      basis: "연결"
      period: "Q2 2026"
      level: 1
      parent: null
      confidence: 0.99
      yoy_growth: "37%"
      qoq_growth: "6%"
      note: "패키지솔루션 사업부 - FCBGA는 AI/서버용 및 전장용 기판 중심, BGA는 모바일/메모리용"

    optical:
      value: "10,362"
      unit: "억원"
      basis: "연결"
      period: "Q2 2026"
      level: 1
      parent: null
      confidence: 0.99
      yoy_growth: "10%"
      qoq_growth: "-4%"
      note: "광학솔루션 사업부 - Seasonality 영향으로 전분기 대비 소폭 감소, 국내 거래처 신규 플래그십용 차별화품 공급 확대"

  # 사업부별 영업이익 기여도 - 2Q26
  operating_profit_by_segment_contribution:
    component_ratio: "48%"
    package_ratio: "22%"
    optical_ratio: "30%"
    period: "Q2 2026"
    confidence: 0.95
    note: "영업이익 구성 비율 - 2Q25 대비 컴포넌트 비중 증가(46% → 48%)"

  # 재무상태표 (2Q26 연결기준, 억원)
  balance_sheet:
    total_assets:
      value: "165,660"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99
      qoq_growth: "6%"
      yoy_growth: "25.5%"
      note: "2Q25 132,005억원 대비 증가"

    cash_and_equivalents:
      value: "33,144"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99
      qoq_growth: "2%"
      note: "현금성자산"

    accounts_receivable:
      value: "22,062"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99
      qoq_growth: "11%"
      note: "매출채권"

    inventory:
      value: "26,177"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99
      qoq_growth: "3%"
      note: "재고자산"

    investment_assets:
      value: "5,940"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99
      qoq_growth: "2%"
      note: "투자자산"

    ppe:
      value: "68,706"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99
      qoq_growth: "6%"
      note: "유형자산 (Property, Plant & Equipment)"

    other_assets:
      value: "9,631"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99
      qoq_growth: "15%"
      note: "기타자산"

    total_liabilities:
      value: "60,368"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99
      qoq_growth: "8%"
      note: "부채총계"

    borrowings:
      value: "29,944"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99
      qoq_growth: "13%"
      note: "충차입금 (금융차입금)"

    total_equity:
      value: "105,291"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99
      qoq_growth: "4%"
      note: "자본총계"

    share_capital:
      value: "3,880"
      unit: "억원"
      basis: "연결"
      period: "2Q26"
      confidence: 0.99
      note: "자본금"

  # 주요 재무 지표 (2Q26)
  financial_ratios:
    debt_to_equity_ratio:
      value: "57%"
      period: "2Q26"
      confidence: 0.99
      formula: "금융차입금 / 자본"
      note: "2Q25 46% → 1Q26 55% → 2Q26 57% (증가추세)"

    borrowing_to_assets_ratio:
      value: "28%"
      period: "2Q26"
      confidence: 0.99
      formula: "금융차입금 / 자산"
      note: "2Q25 22% → 1Q26 26% → 2Q26 28% (증가추세)"

    equity_ratio:
      value: "64%"
      period: "2Q26"
      confidence: 0.99
      formula: "자본 / 자산"
      note: "2Q25 68% → 1Q26 64% → 2Q26 64% (안정적 유지)"

  # 분기별 매출 추이
  quarterly_revenue_trend:
    q2_2025:
      value: "27,846"
      unit: "억원"
      period: "Q2 2025"
    q1_2026:
      value: "32,091"
      unit: "억원"
      period: "Q1 2026"
      qoq_vs_q2_2025: "+33%"
    q2_2026:
      value: "34,572"
      unit: "억원"
      period: "Q2 2026"
      qoq_vs_q1_2026: "+30%"
      yoy_vs_q2_2025: "+24%"

english_summary:
  title: "Samsung Electro-Mechanics Q2 2026 Earnings Results"
  one_liner: "Revenue KRW 345.7B (+24% YoY), Operating profit KRW 44.0B (+107% YoY) with improving margin to 12.7%"
  highlights:
    - "Component business achieved 29% YoY growth driven by AI server/datacenter demand (MLCC for high capacity, high reliability applications)"
    - "Package Solution business posted 37% YoY growth with strong FCBGA substrate demand for AI accelerators and automotive ADAS applications"
    - "Operating margin expanded to 12.7% from 7.6% YoY, benefiting from favorable product mix and operational efficiency"
    - "Net income increased 143% YoY to KRW 31.6B as pre-tax income surged 153% despite higher financial costs"
  key_figures_en:
    revenue: "KRW 345.7B (consolidated, +24% YoY, +8% QoQ)"
    operating_profit: "KRW 44.0B (+107% YoY), margin 12.7% vs 7.6% YoY"
    operating_profit_qoq: "KRW 44.0B (+57% QoQ from KRW 28.1B in Q1)"
    net_income: "KRW 31.6B (+143% YoY), margin 9.1% vs 4.7% YoY"
    pre_tax_income: "KRW 43.3B (+153% YoY), margin 12.5%"
    total_assets: "KRW 1,656.6B (+25.5% YoY)"
    total_equity: "KRW 1,052.9B, equity ratio 64%"
  segment_performance_en:
    component: "KRW 164.9B (+29% YoY, +17% QoQ) - AI datacenter and automotive applications drive growth"
    package_solution: "KRW 77.2B (+37% YoY, +6% QoQ) - High-margin FCBGA substrates for AI accelerators and automotive platforms"
    optical_solution: "KRW 103.6B (+10% YoY, -4% QoQ) - Seasonal decline offset by new flagship camera module supply and automotive sensing applications"
  outlook: "Management expects sustained AI infrastructure investment to support high-capacity MLCC demand and automotive ADAS/xEV market expansion to continue driving growth in Component and Package Solution businesses; Optical Solution to benefit from new camera module launches and emerging autonomous vehicle applications."

---
```

# 삼성전기
## 2026년 2분기 실적

**공시일**: 2026년 7월 30일

---

## 유의사항

본 자료는 2026년 2분기 실적에 대한 외부감시인의 회계 검토가 완료되지 않은 상태에서 투자자 여러분의 편의를 위하여 작성된 것으로, 본 자료의 내용 중 일부는 외부감시인의 최종 감사 과정에서 달라질 수 있습니다.

현재 본 자료는 일부 미래에 대한 예측 정보를 포함하고 있습니다. 이러한 예측 정보는 실제 결과와 왕후 차이가 발생할 수 있음을 양지하시기 바랍니다.

본 자료의 재무정보는 한국채택국제회계기준(K-IFRS)에 따라 작성되었습니다.

---

## 목차

1. 2026년 2분기 주요 실적
2. 2026년 2분기 재무현황
3. 사업부별 실적 및 전망

---

## 2026년 2분기 실적

### 주요실적 및 수익성

#### 주요실적 (연결기준, 억원)

| 항목 | 2Q26 | 1Q26 | QoQ 변화 | 2Q25 | YoY 변화 |
|---|---|---|---|---|---|
| **매출액** | **34,572** | **32,091** | **▲ 8%** | **27,846** | **▲ 24%** |
| ├ 컴포넌트 | 16,494 | 14,085 | ▲ 17% | 12,807 | ▲ 29% |
| ├ 패키지 | 7,716 | 7,250 | ▲ 6% | 5,646 | ▲ 37% |
| └ 광학 | 10,362 | 10,756 | ▼ 4% | 9,393 | ▲ 10% |
| **영업이익** | **4,404** | **2,806** | **▲ 57%** | **2,130** | **▲ 107%** |
| **영업이익률** | **12.7%** | **8.7%** | — | **7.6%** | **+510bp** |
| **세전이익** | **4,333** | **3,164** | **▲ 37%** | **1,714** | **▲ 153%** |
| **세전이익률** | **12.5%** | **9.9%** | — | **6.2%** | **+630bp** |
| **당기순이익** | **3,157** | **2,492** | **▲ 27%** | **1,297** | **▲ 143%** |
| **순이익률** | **9.1%** | **7.8%** | — | **4.7%** | **+440bp** |

**주석**: 당기순이익은 지배기업 소유주지분 순이익 기준 / 모든 금액은 연결기준 재무제표

**분석**:
- **매출 성장**: Q2 2026 매출 3,457억 원은 전년 동기(Q2 2025) 2,784억 원 대비 24% 성장, 전분기(Q1 2026) 3,209억 원 대비 8% 성장
- **수익성 개선**: 영업이익률이 전년 동기 7.6%에서 12.7%로 510bp 상승하며, 영업이익은 107% 폭증(2,130억 → 4,404억 원)
- **사업부별 성장률**: 컴포넌트 29% YoY, 패키지 37% YoY, 광학 10% YoY로 모두 긍정적 성장 기록

#### 매출액 및 영업이익률 추이

**그래프 분석 (연결기준, 억원)**:

- **Q2 2025**: 매출 27,846억 원, 영업이익률 7.6%
  - 사업부 구성: 컴포넌트 46%, 패키지 20%, 광학 34%
  
- **Q1 2026**: 매출 32,091억 원 (+33% vs Q2 2025), 영업이익률 8.7%
  - 사업부 구성: 컴포넌트 44%, 패키지 23%, 광학 33%
  
- **Q2 2026**: 매출 34,572억 원 (+30% vs Q1 2026, +24% vs Q2 2025), 영업이익률 12.7%
  - 사업부 구성: 컴포넌트 48%, 패키지 22%, 광학 30%
  - **핵심 변화**: 컴포넌트 사업부 비중 증가로 전체 이익률 개선

---

## 2026년 2분기 재무현황

### 연결 재무상태표 (억원)

| 항목 | 2Q26 | 1Q26 | QoQ 변화 | 2Q25 | YoY 변화 |
|---|---|---|---|---|---|
| **자산총계** | **165,660** | **156,605** | **▲ 6%** | **132,005** | **▲ 25.5%** |
| ├ 현금성자산 | 33,144 | 32,433 | ▲ 2% | 25,413 | ▲ 30.3% |
| ├ 매출채권 | 22,062 | 19,806 | ▲ 11% | 16,392 | ▲ 34.7% |
| ├ 재고자산 | 26,177 | 25,486 | ▲ 3% | 20,724 | ▲ 26.3% |
| ├ 투자자산 | 5,940 | 5,808 | ▲ 2% | 4,331 | ▲ 37.1% |
| ├ 유형자산(PP&E) | 68,706 | 64,687 | ▲ 6% | 56,718 | ▲ 21.1% |
| └ 기타자산 | 9,631 | 8,385 | ▲ 15% | 8,427 | ▲ 14.3% |
| **부채총계** | **60,368** | **55,694** | **▲ 8%** | **41,851** | **▲ 44.2%** |
| └ 금융차입금 | 29,944 | 26,460 | ▲ 13% | 19,866 | ▲ 50.7% |
| **자본총계** | **105,291** | **100,911** | **▲ 4%** | **90,154** | **▲ 16.8%** |
| └ 자본금 | 3,880 | 3,880 | — | 3,880 | — |

**자산 구성 분석 (2Q26)**:
- 유형자산(PP&E): 165,660억 원 중 41.5% 차지 → 생산 능력 확충 진행 중
- 현금성자산: 33,144억 원 (20.0%)
- 재고자산: 26,177억 원 (15.8%) → 매출 성장에 따른 정상적 증가
- 매출채권: 22,062억 원 (13.3%) → QoQ 11% 증가로 매출 회수 진행 중

**부채 및 자본 분석**:
- 금융차입금이 전년 동기 19,866억 원에서 29,944억 원으로 50.7% 증가 → 유형자산 투자 자금 조달
- 자본금 변화 없음 (3,880억 원 고정)

---

### 주요 재무 지표

#### 부채비율 (금융차입금 / 자본)

| 항목 | 2Q25 | 1Q26 | 2Q26 |
|---|---|---|---|
| **부채비율** | **46%** | **55%** | **57%** |

**추이 분석**: 46% → 55% → 57% (증가 추세)
- 금융차입금 증가로 인한 자연스러운 레버리지 상승
- 여전히 건전한 수준 유지 (부채비율 < 100%)

#### 금융차입금비율 (금융차입금 / 자산)

| 항목 | 2Q25 | 1Q26 | 2Q26 |
|---|---|---|---|
| **금융차입금비율** | **22%** | **26%** | **28%** |

**추이 분석**: 22% → 26% → 28% (증가 추세)
- 총자산 165,660억 원 중 금융차입금 29,944억 원이 차지하는 비율
- 자산 수익성 개선으로 인한 적극적 자본 조달 반영

#### 자기자산비율 (자본 / 자산)

| 항목 | 2Q25 | 1Q26 | 2Q26 |
|---|---|---|---|
| **자기자산비율** | **68%** | **64%** | **64%** |

**추이 분석**: 68% → 64% → 64% (안정적 유지)
- 자본비율 64% 수준은 건전한 재무 상태 유지
- 부채비율 증가에도 불구하고 자본력 건전성 확보

**종합평가**: 
- 자산의 64%가 자본으로 구성되어 재무 안정성 양호
- 금융차입금 증가는 AI/자동차 관련 생산능력 확충 투자에 따른 계획된 재원 조달

---

## 사업부별 실적 및 전망

### 1. 컴포넌트 사업부

#### 2Q26 매출 현황 (연결기준, 억원)

| 제품군 | 2Q25 | 1Q26 | 2Q26 | 성장률 |
|---|---|---|---|---|
| **Capacitors (MLCC 등)** | 12,807 | 14,085 | 16,494 | YoY +29%, QoQ +17% |
| 기타 전자소자 | — | — | — | — |
| **사업부 합계** | **12,807** | **14,085** | **16,494** | **YoY +29%, QoQ +17%** |
| **점유율** | **90%** | **91%** | **92%** | — |

**주석**: Capacitors(콘덴서/MLCC)가 컴포넌트 사업부 매출의 92%를 차지 (2Q26 기준)

#### 2Q26 실적 분석

**성장 동력**:
1. **AI/데이터센터 수요 급증**
   - AI 서버, 네트워크, 파워 관련 제품의 매출 고성장 기록
   - MLCC(Multi-Layer Ceramic Capacitor)의 고용량·고신뢰성 제품 수요 강세

2. **자동차 전장용 수요 확대**
   - ADAS(Advanced Driver Assistance Systems) 고도화에 따른 수요 증가
   - xEV(전기차, 수소차 등) 시장 성장으로 전장용 제품 다변화

**수익성 개선**:
- 컴포넌트 사업부가 전체 영업이익의 **48%** 차지 (2Q25: 46% → 2Q26: 48%)
- 고마진 제품군(AI용 MLCC, 전장용 제품) 판매 비중 증가

#### 3분기 시장 전망 및 추진 전략

**시장 기대 요인**:
1. AI 인프라 투자 지속
   - 글로벌 빅테크(Google, Meta, Amazon, Microsoft 등)의 AI 데이터센터 투자 가속화
   - AI 반도체 성능 향상에 따른 고용량·고신뢰성 MLCC 수요 지속 증가

2. 자동차 전장화 추진
   - ADAS 기능 확산 및 xEV 시장 지속 성장

**회사 전략**:
- **AI용 최선단 기종 개발**: 데이터센터용 고신뢰성 MLCC의 적기 개발 및 공급 강화
- **장기 공급계약 대응**: 다수의 글로벌 빅테크 거래처와 장기공급계약 적극 대응
- **전장용 제품 확대**: ADAS용 고용량품 및 xEV용 고신뢰성 제품 진정 확대

---

### 2. 패키지솔루션 사업부

#### 2Q26 매출 현황 (연결기준, 억원)

| 항목 | 2Q25 | 1Q26 | 2Q26 | 성장률 |
|---|---|---|---|---|
| **사업부 합계** | **5,646** | **7,250** | **7,716** | **YoY +37%, QoQ +6%** |

**성장 분석**:
- YoY 37% 고성장: AI/서버 기판 수요의 강세
- QoQ 6% 성장: 분기 대비 안정적 성장 지속

#### 2Q26 실적 분석

**매출 구성 및 성장 동인**:

1. **FCBGA(Flip Chip Ball Grid Array) 기판**
   - AI/서버용 고단가 기판 중심 성장
   - 주요 빅테크 회사의 AI 가속기/서버 CPU용 기판 공급 지속 확대
   - 신규 거래처에 AI 데이터센터 네트워크용 신제품 공급 개시
   - ADAS/자율주행 관련 전장용 기판 공급 증가

2. **BGA(Ball Grid Array) 기판**
   - 모바일 AP(Application Processor)용, 메모리용 공급 확대

**수익성 기여**:
- 패키지 사업부가 전체 영업이익의 **22%** 차지 (2Q25: 20% → 2Q26: 22%)
- FCBGA 고마진 제품 비중 증가로 수익성 개선

#### 3분기 시장 전망 및 추진 전략

**시장 전망**:
- 데이터센터용 고부가 FCBGA 기판의 수요 강세 지속 예상
- 글로벌 빅테크의 AI 가속기/서버 CPU용 신제품 양산으로 매출 확대 기대

**회사 전략**:
- **국내 생산능력(Capa) 증설**: 고객 수요에 적극 대응하기 위한 국내 설비 투자 추진
- **구각가(고부가가치) 기판 공급 확대**: AI 고성능 기판, 자동차 전장용 기판 등 차별화 제품 공급 강화
- **기술 개발**: 차세대 FCBGA 기술 확보 및 양산화

---

### 3. 광학솔루션 사업부

#### 2Q26 매출 현황 (연결기준, 억원)

| 항목 | 2Q25 | 1Q26 | 2Q26 | 성장률 |
|---|---|---|---|---|
| **사업부 합계** | **9,393** | **10,756** | **10,362** | **YoY +10%, QoQ -4%** |

**성장 분석**:
- YoY 10% 성장: 전년 동기 대비 긍정적 성장 유지
- QoQ -4% 감소: Seasonality(계절성) 영향으로 전분기 대비 소폭 하락

#### 2Q26 실적 분석

**스마트폰 카메라(모바일) 부문**:

1. **주요 제품**
   - 2인화-풀드층(Dual-layer folded) 신규 양산 개시
   - 고해상도 LS Slim OIS(Optical Image Stabilization) 등 고성능 카메라 공급 확대
   
2. **시장 성과**
   - 국내 거래처의 신규 플래그십(


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
