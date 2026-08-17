```yaml
---
title: "현대자동차 2026년 2분기 실적발표"
company: "현대자동차"
ticker: "005380"
ticker_us: "HYMTF"
english_name: "Hyundai Motor Company"
doc_type: "실적발표"
publish_date: "2026-07-23"
fiscal_year: 2026
fiscal_quarter: "Q2"
source: "IRGO"
pipeline_version: "v2.0.0"
converted_at: "2026-07-23T00:00:00Z"
audit_status: "미감사 (회계감사 진행 중)"
audit_note: "제시된 자료의 내용 중 일부는 회계감사 과정에서 변경될 수 있음"

key_figures:
  dart_revenue_annual:
    value: "1,862,544.7"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_operating_profit_annual:
    value: "114,678.5"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_net_income_annual:
    value: "103,647.8"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_total_assets:
    value: "3,688,448.5"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_total_liabilities:
    value: "2,411,966.1"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_total_equity:
    value: "1,276,482.4"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  # ====== 매출/수익 ======
  revenue_q2:
    value: "49"
    unit: "조원"
    period: "Q2 2026"
    basis: "연결"
    confidence: 0.95
    note: "역대 분기 최대 매출액 기록, 단위 변환 필요 (조원=trillion KRW)"

  operating_profit_q2_2026:
    value: "N/A"
    unit: "조원"
    period: "Q2 2026"
    basis: "연결"
    confidence: 0
    note: "Stage 4 교정: missing_fields - 원본 데이터 확인 필요"

  operating_profit_q2_2025:
    value: "N/A"
    unit: "조원"
    period: "Q2 2025"
    basis: "연결"
    confidence: 0
    note: "Stage 4 교정: missing_fields - 원본 데이터 확인 필요"

  net_income_q2_2026:
    value: "N/A"
    unit: "조원"
    period: "Q2 2026"
    basis: "연결"
    confidence: 0
    note: "Stage 4 교정: missing_fields - 원본 데이터 확인 필요"

  net_income_q2_2025:
    value: "N/A"
    unit: "조원"
    period: "Q2 2025"
    basis: "연결"
    confidence: 0
    note: "Stage 4 교정: missing_fields - 원본 데이터 확인 필요"

  operating_margin:
    value: "N/A"
    unit: "%"
    period: "Q2 2026"
    basis: "연결"
    confidence: 0
    note: "Stage 4 교정: missing_fields - 원본 데이터 확인 필요"

  net_margin:
    value: "N/A"
    unit: "%"
    period: "Q2 2026"
    basis: "연결"
    confidence: 0
    note: "Stage 4 교정: missing_fields - 원본 데이터 확인 필요"

  # ====== 글로벌 판매 현황 (Q2 2026 도매 기준) ======
  global_wholesale_q2_2026:
    value: "992"
    unit: "천대"
    period: "Q2 2026"
    confidence: 0.98
    note: "도매 판매량 (소매 기준이 아님)"

  global_wholesale_q2_2025:
    value: "1,066"
    unit: "천대"
    period: "Q2 2025"
    confidence: 0.98
    note: "도매 판매량 YoY 비교용"

  global_wholesale_growth:
    value: "-6.9"
    unit: "%"
    period: "Q2 2026 vs Q2 2025"
    basis: "연결"
    confidence: 0.98
    note: "도매 판매량 전년동기 대비 감소율"

  global_retail_q2_2026:
    value: "999"
    unit: "천대"
    period: "Q2 2026"
    confidence: 0.98
    note: "소매 판매량"

  global_retail_q2_2025:
    value: "1,043"
    unit: "천대"
    period: "Q2 2025"
    confidence: 0.98

  global_retail_growth:
    value: "-4.2"
    unit: "%"
    period: "Q2 2026 vs Q2 2025"
    confidence: 0.98
    note: "소매 판매량 전년동기 대비 감소율"

  # ====== 지역별 도매 판매 (Q2 2026) ======
  wholesale_by_region_q2_2026:
    usa:
      value: "265"
      unit: "천대"
      period: "Q2 2026"
      confidence: 0.98
      note: "북미 도매 판매 (도매 기준)"
    
    europe:
      value: "144"
      unit: "천대"
      period: "Q2 2026"
      confidence: 0.98
    
    korea:
      value: "158"
      unit: "천대"
      period: "Q2 2026"
      confidence: 0.98
      note: "국내 도매 판매"
    
    india:
      value: "139"
      unit: "천대"
      period: "Q2 2026"
      confidence: 0.98
      note: "인도 도매 판매"
    
    china:
      value: "19"
      unit: "천대"
      period: "Q2 2026"
      confidence: 0.98
      note: "중국 도매 판매"

  # ====== 지역별 도매 판매 (Q2 2025) ======
  wholesale_by_region_q2_2025:
    usa:
      value: "262"
      unit: "천대"
      period: "Q2 2025"
      confidence: 0.98
    
    europe:
      value: "161"
      unit: "천대"
      period: "Q2 2025"
      confidence: 0.98
    
    korea:
      value: "189"
      unit: "천대"
      period: "Q2 2025"
      confidence: 0.98
    
    india:
      value: "132"
      unit: "천대"
      period: "Q2 2025"
      confidence: 0.98
    
    china:
      value: "31"
      unit: "천대"
      period: "Q2 2025"
      confidence: 0.98

  # ====== 지역별 도매 판매 성장률 ======
  wholesale_growth_rate_by_region:
    usa:
      value: "+0.9"
      unit: "%"
      period: "Q2 2026 vs Q2 2025"
      confidence: 0.98
      note: "M/S 6%대 유지, 5개 분기 연속 유지"
    
    europe:
      value: "-10.9"
      unit: "%"
      period: "Q2 2026 vs Q2 2025"
      confidence: 0.98
      note: "경기 심화 및 지정학적 리스크로 감소, 하반기 투찬 예정"
    
    korea:
      value: "-16.4"
      unit: "%"
      period: "Q2 2026 vs Q2 2025"
      confidence: 0.98
    
    india:
      value: "+5.4"
      unit: "%"
      period: "Q2 2026 vs Q2 2025"
      confidence: 0.98
    
    china:
      value: "-36.9"
      unit: "%"
      period: "Q2 2026 vs Q2 2025"
      confidence: 0.98
      note: "중국 시장 경쟁 심화"

  # ====== HEV(하이브리드) 판매 비중 ======
  hev_penetration_rate_global:
    value: "18.9"
    unit: "%"
    period: "Q2 2026"
    basis: "도매 기준"
    confidence: 0.95
    note: "사상 최대 글로벌 HEV 판매 비중, 전체 판매 대수 대비"

  hev_penetration_rate_usa:
    value: "26.2"
    unit: "%"
    period: "Q2 2026"
    basis: "도매 기준"
    confidence: 0.95
    note: "미국 시장 HEV 판매 비중 (역점 최대)"

  # ====== 미국 xEV 판매 믹스 ======
  usa_xev_mix_q2_2026:
    ev:
      value: "4.0"
      unit: "%"
      period: "Q2 2026"
      confidence: 0.95
      note: "전기차 비중"
    
    hev:
      value: "26.2"
      unit: "%"
      period: "Q2 2026"
      confidence: 0.95
      note: "하이브리드 비중 (YoY +6.8%p)"
    
    phev:
      value: "0.4"
      unit: "%"
      period: "Q2 2026"
      confidence: 0.95
    
    fcev:
      value: "-"
      unit: "%"
      period: "Q2 2026"
      note: "수소연료전지차 - 데이터 없음"

  usa_xev_mix_q2_2025:
    ev:
      value: "10.2"
      unit: "%"
      period: "Q2 2025"
      confidence: 0.95
    
    hev:
      value: "19.4"
      unit: "%"
      period: "Q2 2025"
      confidence: 0.95
    
    phev:
      value: "0.4"
      unit: "%"
      period: "Q2 2025"
      confidence: 0.95
    
    fcev:
      value: "0.002"
      unit: "%"
      period: "Q2 2025"
      confidence: 0.95

  # ====== 미국 차급별 판매 ======
  usa_vehicle_mix_q2_2026:
    suv:
      value: "72.9"
      unit: "%"
      period: "Q2 2026"
      confidence: 0.95
      note: "SUV 판매 비중"
    
    pv:
      value: "27.1"
      unit: "%"
      period: "Q2 2026"
      confidence: 0.95
      note: "승용차(PV) 판매 비중, YoY +9.6% (중형 세단 등 실용적 차급 수요)"

  usa_vehicle_mix_q2_2025:
    suv:
      value: "75.1"
      unit: "%"
      period: "Q2 2025"
      confidence: 0.95
    
    pv:
      value: "24.9"
      unit: "%"
      period: "Q2 2025"
      confidence: 0.95

  # ====== 유럽 xEV 판매 믹스 ======
  europe_xev_mix_q2_2026:
    ev:
      value: "21.8"
      unit: "%"
      period: "Q2 2026"
      confidence: 0.95
    
    hev:
      value: "25.5"
      unit: "%"
      period: "Q2 2026"
      confidence: 0.95
      note: "HEV 판매 YoY +17.8%, QoQ -2.8%"
    
    phev:
      value: "4.7"
      unit: "%"
      period: "Q2 2026"
      confidence: 0.95
    
    fcev:
      value: "0.002"
      unit: "%"
      period: "Q2 2026"
      confidence: 0.95

  europe_xev_mix_q2_2025:
    ev:
      value: "18.6"
      unit: "%"
      period: "Q2 2025"
      confidence: 0.95
    
    hev:
      value: "19.3"
      unit: "%"
      period: "Q2 2025"
      confidence: 0.95
    
    phev:
      value: "6.8"
      unit: "%"
      period: "Q2 2025"
      confidence: 0.95
    
    fcev:
      value: "0.02"
      unit: "%"
      period: "Q2 2025"
      confidence: 0.95

  # ====== 유럽 차급별 판매 ======
  europe_vehicle_mix_q2_2026:
    suv:
      value: "74.2"
      unit: "%"
      period: "Q2 2026"
      confidence: 0.95
      note: "SUV 판매 비중, YoY +0.4%, QoQ +5.4% (차종 믹스 전략 성과)"
    
    pv:
      value: "25.1"
      unit: "%"
      period: "Q2 2026"
      confidence: 0.95
    
    cv:
      value: "0.7"
      unit: "%"
      period: "Q2 2026"
      confidence: 0.95
      note: "상용차(CV) 비중"

  europe_vehicle_mix_q2_2025:
    suv:
      value: "65.8"
      unit: "%"
      period: "Q2 2025"
      confidence: 0.95
    
    pv:
      value: "33.2"
      unit: "%"
      period: "Q2 2025"
      confidence: 0.95
    
    cv:
      value: "1.0"
      unit: "%"
      period: "Q2 2025"
      confidence: 0.95

  # ====== 시장별 신차 수요 ======
  industry_demand_q2_2026:
    usa:
      value: "4,238"
      unit: "천대"
      period: "Q2 2026"
      basis: "소매 기준"
      confidence: 0.95
    
    europe:
      value: "4,400"
      unit: "천대"
      period: "Q2 2026"
      basis: "소매 기준"
      confidence: 0.95
    
    korea:
      value: "440"
      unit: "천대"
      period: "Q2 2026"
      basis: "소매 기준"
      confidence: 0.95
    
    india:
      value: "1,291"
      unit: "천대"
      period: "Q2 2026"
      basis: "도매 기준"
      confidence: 0.95
      note: "인도 기준은 도매 (소매 아님)"
    
    china:
      value: "4,283"
      unit: "천대"
      period: "Q2 2026"
      basis: "도매 기준"
      confidence: 0.95
      note: "중국 기준은 도매, YoY -25.1%"

  industry_demand_q2_2025:
    usa:
      value: "4,217"
      unit: "천대"
      period: "Q2 2025"
      basis: "소매 기준"
      confidence: 0.95
    
    europe:
      value: "4,276"
      unit: "천대"
      period: "Q2 2025"
      basis: "소매 기준"
      confidence: 0.95
    
    korea:
      value: "440"
      unit: "천대"
      period: "Q2 2025"
      basis: "소매 기준"
      confidence: 0.95
    
    india:
      value: "1,029"
      unit: "천대"
      period: "Q2 2025"
      basis: "도매 기준"
      confidence: 0.95
    
    china:
      value: "5,730"
      unit: "천대"
      period: "Q2 2025"
      basis: "도매 기준"
      confidence: 0.95

  # ====== 시장별 신차 수요 성장률 ======
  industry_demand_growth_rate:
    usa:
      value: "+0.5"
      unit: "%"
      period: "Q2 2026 vs Q2 2025"
      note: "금리 인하 지연 영향으로 정체"
    
    europe:
      value: "+2.9"
      unit: "%"
      period: "Q2 2026 vs Q2 2025"
    
    korea:
      value: "-0.1"
      unit: "%"
      period: "Q2 2026 vs Q2 2025"
    
    india:
      value: "+25.6"
      unit: "%"
      period: "Q2 2026 vs Q2 2025"
      note: "인도 시장 높은 성장"
    
    china:
      value: "-25.1"
      unit: "%"
      period: "Q2 2026 vs Q2 2025"
      note: "중국 산업 수요 큰 폭 감소"

english_summary:
  title: "Hyundai Motor Company Q2 2026 Earnings Results"
  
  one_liner: "Revenue KRW 49.0 trillion (record high for a single quarter), global wholesale sales 992K units (YoY -6.9%), HEV penetration reached historic high of 18.9% globally and 26.2% in the US."
  
  highlights:
    - "Record quarterly revenue of KRW 49.0 trillion despite geopolitical uncertainties and industry demand headwinds, demonstrating strong pricing power and market positioning."
    - "Global HEV (hybrid electric vehicle) penetration reached historic highs: 18.9% globally and 26.2% in the US market, driven by favorable US fuel prices and government incentives for hybrid vehicles."
    - "US market share maintained at 6% level for 5 consecutive quarters (YoY wholesale +0.9%) despite industry demand growth of only +0.5%, reflecting strong competitiveness and HEV sales momentum."
    - "SUV sales mix in Europe strengthened to 74.2% (YoY +0.4%), with wholesale volume decline of -10.9% due to economic slowdown and geopolitical risks, though new model launches planned for H2 2026."
    - "China market wholesale sales declined 36.9% YoY to 19K units amid intensifying competition, while India market showed robust growth of +5.4% to 139K units, demonstrating market diversification."
  
  key_figures_en:
    revenue: "KRW 49.0 trillion (consolidated, record quarterly high)"
    global_wholesale_sales: "992K units (YoY -6.9%)"
    global_retail_sales: "999K units (YoY -4.2%)"
    hev_penetration_global: "18.9% (record high, wholesale basis)"
    hev_penetration_usa: "26.2% (record high for US market)"
    usa_wholesale_growth: "+0.9% YoY"
    usa_market_share: "6% level (maintained for 5 consecutive quarters)"
    europe_wholesale_decline: "-10.9% YoY"
    europe_suv_mix: "74.2% (YoY +0.4%)"
    china_wholesale_decline: "-36.9% YoY"
    india_wholesale_growth: "+5.4% YoY"
    usa_sedan_growth: "+9.6% (mid-size sedans gaining preference)"
  
  outlook: "Company expects H2 2026 to benefit from new model launches (including Ioniq3 in Europe), continued HEV sales momentum driven by fuel price environment, and market stabilization in China despite near-term headwinds from geopolitical uncertainties."

---
```

## 현대자동차 2026년 2분기 경영실적 발표

[이미지: Hyundai Avante 차량의 정면 및 측면 이미지]

**현대자동차 2026년 2분기 경영실적 발표**

2026년 7월 23일

---

## 유의사항

본 자료는 2026년 2분기 실적에 대한 외부강사인의 회계감사가 **미완료 상태**에서 투자자 여러분의 편의를 위하여 작성된 자료로서, 제시된 자료의 내용 중 일부는 회계감사 과정에서 변경될 수 있음을 양지하시기 바랍니다.

---

## 목차

| 섹션 | 페이지 |
|------|--------|
| 2분기 주요 메시지 | P. 3 |
| 판매 실적 | P. 4~9 |
| 손익 분석 | P. 10~13 |
| Appendix | P. 16~19 |

---

## 2분기 주요 메시지

### 세 가지 핵심 성과

#### 1. **M/S ↑**

**미국 시장 점유율 상승**
- 미국 산업우호 정책 물가, 당사 미국 HEV 판매 효과에 힘입어 **미국시장 M/S YoY +0.2%p 상승**
- **5개 분기 연속 6%대 유지** (강한 경쟁력 입증)

#### 2. **18.9% — 역대 최대 글로벌 HEV 판매 비중**

**전동화 전략 가속화**
- 글로벌 전체 판매 대수(도매 기준) 대비 **HEV 비중 18.9% 달성** (사상 최대)
- 미국 시장에서 **HEV 판매 비중 26.2% 기록** (역점 최고)
- 고유가 환경에서 HEV 수요 증가 추세 반영

#### 3. **49조원 — 역대 분기 최대 매출액**

**강력한 실적 창출**
- 지정학적 불확실성 확대로 인한 수요 감소 우려 불구, **역대 분기 최대 매출액 49조원(KRW 49.0 trillion) 기록**
- 프리미엄 포지셔닝 및 HEV 판매 성장이 주요 견인

---

## 판매 실적

### 글로벌 도·소매판매 현황

#### 주요 시장별 신업수요 및 도·소매 현황 (단위: 천대)

| 지역 | **Q2 2025 신업수요¹** | **Q2 2026 신업수요¹** | **변화율** | **Q2 2025 도매** | **Q2 2026 도매** | **도매 변화율** | **Q2 2025 소매** | **Q2 2026 소매** | **소매 변화율** |
|------|----------------------|----------------------|-----------|-----------------|-----------------|-----------------|-----------------|-----------------|-----------------|
| **USA** | 4,217 | 4,238 | +0.5% | 262 | 265 | +0.9% | ⚠️ | ⚠️ | ⚠️ |
| **유럽** | 4,276 | 4,400 | +2.9% | 161 | 144 | -10.9% | ⚠️ | ⚠️ | ⚠️ |
| **국내** | 440 | 440 | -0.1% | 189 | 158 | -16.4% | ⚠️ | ⚠️ | ⚠️ |
| **인도** | 1,029 | 1,291 | +25.6% | 132 | 139 | +5.4% | ⚠️ | ⚠️ | ⚠️ |
| **중국** | 5,730 | 4,283 | -25.1% | 31 | 19 | -36.9% | ⚠️ | ⚠️ | ⚠️ |
| **소계** | 15,692 | 14,652 | -6.6% | 775 | 725 | -6.5% | ⚠️ | ⚠️ | ⚠️ |
| **기타지역** | - | - | - | 291 | 267 | -8.2% | ⚠️ | ⚠️ | ⚠️ |
| **합계** | - | - | - | 1,066 | 992 | -6.9% | 1,043 | 999 | -4.2% |

> ⚠️ 원본 확인 필요: 소매 데이터는 원본 문서에서 절단되어 추가 확인 필요합니다.

¹ 신업수요 기준: 미국·유럽·국내는 소매(retail) 기준, 인도·중국은 도매(wholesale) 기준

---

## 지역별 판매 분석

### 1. **미국 시장 (USA)**

#### 도매 판매 현황
- **Q2 2026 도매**: 265천대 (Q2 2025: 262천대, **+0.9% YoY**)
- **시장점유율**: 6% 수준 **5개 분기 연속 유지** ✓

#### 전동화 판매 (xEV Mix)

| 차종 | Q2 2025 | Q2 2026 | 변화 |
|------|---------|---------|------|
| **전기차 (EV)** | 10.2% | 4.0% | -6.2%p |
| **하이브리드 (HEV)** | 19.4% | 26.2% | +6.8%p ⭐ |
| **플러그인하이브리드 (PHEV)** | 0.4% | 0.4% | 동등 |
| **수소연료전지 (FCEV)** | 0.002% | - | N/A |

> **핵심**: HEV 판매 비중 급증으로 전동화 전략 성공, 미국 시장에서 **사상 최고** 26.2% 달성

#### 차급별 판매 믹스 (Vehicle Mix)

| 차급 | Q2 2025 | Q2 2026 | 변화 |
|------|---------|---------|------|
| **SUV** | 75.1% | 72.9% | -2.2%p |
| **승용차 (PV)** | 24.9% | 27.1% | +2.2%p |

> **주목**: 중형 세단 등 실용적 승용차 수요 증가 추세 (**PV +9.6% YoY**)

---

### 2. **유럽 시장 (Europe)**

#### 도매 판매 현황
- **Q2 2026 도매**: 144천대 (Q2 2025: 161천대, **-10.9% YoY**)
- **원인**: 경기 심화 및 지정학적 리스크
- **전망**: 하반기 신모델 출시(Ioniq3 포함)로 회복 예상

#### 전동화 판매 (xEV Mix)

| 차종 | Q2 2025 | Q2 2026 | 변화 |
|------|---------|---------|------|
| **전기차 (EV)** | 18.6% | 21.8% | +3.2%p |
| **하이브리드 (HEV)** | 19.3% | 25.5% | +6.2%p |
| **플러그인하이브리드 (PHEV)** | 6.8% | 4.7% | -2.1%p |
| **수소연료전지 (FCEV)** | 0.02% | 0.002% | -0.018%p |

> **하이라이트**: HEV 판매 비중 **+17.8% YoY** 성장, 친환경 동력 전략 가속

#### 차급별 판매 믹스 (Vehicle Mix)

| 차급 | Q2 2025 | Q2 2026 | 변화 |
|------|---------|---------|------|
| **SUV** | 65.8% | 74.2% | +8.4%p |
| **승용차 (PV)** | 33.2% | 25.1% | -8.1%p |
| **상용차 (CV)** | 1.0% | 0.7% | -0.3%p |

> **전략 성과**: SUV 중심 차종 믹스 전환으로 **+0.4% YoY** 개선 (QoQ +5.4%)

---

### 3. **국내 시장 (Korea)**

#### 도매 판매 현황
- **Q2 2026 도매**: 158천대 (Q2 2025: 189천대, **-16.4% YoY**)


---

## DART 연결재무제표 (현대자동차, 2025년)
<!-- source: OpenDART API | ground_truth: true -->

| 계정 | 금액(억원) | 출처 |
|------|--------:|------|
| 매출액 | 1,862,544.7 | DART |
| 영업이익 | 114,678.5 | DART |
| 당기순이익 | 103,647.8 | DART |
| 자산총계 | 3,688,448.5 | DART |
| 부채총계 | 2,411,966.1 | DART |
| 자본총계 | 1,276,482.4 | DART |
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
