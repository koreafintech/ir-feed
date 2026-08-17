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
converted_at: "2024-12-19T00:00:00Z"

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
  revenue:
    value: "49"
    unit: "조원"
    basis: "연결"
    period: "Q2 2026"
    confidence: 0.95
    note: "역대 분기 최대 매출액 기록"
  
  global_wholesale:
    value: "992"
    unit: "천대"
    basis: "도매"
    period: "Q2 2026"
    confidence: 0.98
    note: "전분기 대비 -6.9% (Q2 2025: 1,066천대)"
  
  global_retail:
    value: "999"
    unit: "천대"
    basis: "소매"
    period: "Q2 2026"
    confidence: 0.98
    note: "전분기 대비 -4.2% (Q2 2025: 1,043천대)"
  
  global_market_demand:
    value: "20,746"
    unit: "천대"
    basis: "신차 수요"
    period: "Q2 2026"
    confidence: 0.95
    note: "전분기 대비 -3.8% (Q2 2025: 21,576천대)"

  usa_wholesale:
    value: "265"
    unit: "천대"
    period: "Q2 2026"
    confidence: 0.98
    note: "도매 기준, 전분기 대비 +0.9% (Q2 2025: 262천대); M/S 6%대 유지"
  
  usa_market_share:
    value: "6.0"
    unit: "%"
    period: "Q2 2026"
    confidence: 0.85
    note: "5개 분기 연속 6%대 유지"
  
  usa_hev_sales_ratio:
    value: "26.2"
    unit: "%"
    basis: "도매 기준"
    period: "Q2 2026"
    confidence: 0.98
    note: "미국 시장 역대 HEV 판매 비중 최대치"
  
  global_hev_sales_ratio:
    value: "18.9"
    unit: "%"
    basis: "도매 기준"
    period: "Q2 2026"
    confidence: 0.98
    note: "글로벌 사상 최대 HEV 판매 비중"

  # 지역별 도매 판매
  usa_wholesale_detail:
    wholesale:
      value: "265"
      unit: "천대"
      period: "Q2 2026"
      yoy_change: "+0.9%"
    suv_ratio:
      value: "72.9"
      unit: "%"
      period: "Q2 2026"
      yoy_change: "-2.2p (from 75.1%)"
    pv_ratio:
      value: "27.1"
      unit: "%"
      period: "Q2 2026"
      yoy_change: "+2.2p (from 24.9%)"
    suv_count:
      value: "193"
      unit: "천대"
      period: "Q2 2026"
      confidence: 0.85
      note: "⚠️ 원본 확인 필요 | Stage 4 교정: 계산값(265 × 72.9% = 193.185) 검증 완료. 테이블 기재값(196 → 193천대)과 상이하므로 명확화 필요"

  usa_xev_breakdown:
    ev:
      value: "4.0"
      unit: "%"
      period: "Q2 2026"
      yoy_change: "-6.2p"
    hev:
      value: "26.2"
      unit: "%"
      period: "Q2 2026"
      yoy_change: "+6.8p"
    phev:
      value: "0.4"
      unit: "%"
      period: "Q2 2026"
      yoy_change: "flat"
    fcev:
      value: "N/A"
      unit: "%"
      period: "Q2 2026"
      confidence: 0
      yoy_change: "중단"

  europe_wholesale_detail:
    wholesale:
      value: "144"
      unit: "천대"
      period: "Q2 2026"
      yoy_change: "-10.9%"
    suv_ratio:
      value: "74.2"
      unit: "%"
      period: "Q2 2026"
      yoy_change: "+8.4p"
    pv_ratio:
      value: "25.1"
      unit: "%"
      period: "Q2 2026"
      yoy_change: "-8.1p"
    cv_ratio:
      value: "0.7"
      unit: "%"
      period: "Q2 2026"
      yoy_change: "-0.3p"

  europe_xev_breakdown:
    ev:
      value: "21.8"
      unit: "%"
      period: "Q2 2026"
      yoy_change: "+3.2p"
    hev:
      value: "25.5"
      unit: "%"
      period: "Q2 2026"
      yoy_change: "+6.2p"
    phev:
      value: "4.7"
      unit: "%"
      period: "Q2 2026"
      yoy_change: "-2.1p"
    fcev:
      value: "0.002"
      unit: "%"
      period: "Q2 2026"
      yoy_change: "-0.018p"

  domestic_wholesale:
    value: "158"
    unit: "천대"
    period: "Q2 2026"
    yoy_change: "-16.4%"
    confidence: 0.98
    note: "도매 기준 (Q2 2025: 189천대)"

  india_wholesale:
    value: "139"
    unit: "천대"
    period: "Q2 2026"
    yoy_change: "+5.4%"
    confidence: 0.98
    note: "도매 기준, 신차 수요 +25.6% (Q2 2025: 132천대)"

  china_wholesale:
    value: "19"
    unit: "천대"
    period: "Q2 2026"
    yoy_change: "-36.9%"
    confidence: 0.98
    note: "도매 기준, 신차 수요 -25.1% (Q2 2025: 31천대)"

  # 글로벌 다른 지역
  americas_ex_usa:
    value: "91"
    unit: "천대"
    period: "Q2 2026"
    region: "중남미"
    yoy_change: "+8.1% (도매) / +12.5% (소매)"
    confidence: 0.85

  apac_ex_india_china:
    value: "43"
    unit: "천대"
    period: "Q2 2026"
    region: "아태 (인도, 중국 제외)"
    yoy_change: "-12.5% (도매) / -11.2% (소매)"
    confidence: 0.85

  africa_mea:
    value: "61"
    unit: "천대"
    period: "Q2 2026"
    region: "아프리카 & 중동"
    yoy_change: "-23.8% (도매) / -17.3% (소매)"
    confidence: 0.85

english_summary:
  title: "Hyundai Motor Company Q2 2026 Earnings Results"
  one_liner: "Record Q2 revenue of KRW 49 trillion achieved, driven by robust HEV sales globally; global wholesale sales of 992K units (-6.9% YoY), maintaining U.S. market share at 6% for 5 consecutive quarters"
  highlights:
    - "Achieved record quarterly revenue of KRW 49 trillion despite macroeconomic uncertainties and demand headwinds"
    - "Global HEV sales ratio reached historic high of 18.9% (wholesale basis), with U.S. market HEV penetration at 26.2%, highest ever"
    - "Maintained 6% market share in the U.S. for five consecutive quarters despite flat industry demand (+0.5% YoY); U.S. wholesale sales grew +0.9% YoY to 265K units"
    - "Europe wholesale sales declined 10.9% YoY to 144K units due to economic slowdown and geopolitical risks; strategic product mix shift achieved 74.2% SUV ratio"
    - "Europe xEV sales expanded: HEV penetration reached 25.5% (+6.2p), and EV reached 21.8% (+3.2p), as battery electric and hybrid products gained traction"
    - "India market showed strong growth: wholesale sales +5.4% YoY to 139K units, supported by 25.6% YoY increase in market demand"
    - "China market faced headwinds: wholesale sales declined 36.9% YoY to 19K units amidst -25.1% YoY market demand contraction"
  key_figures_en:
    revenue: "KRW 49.0 trillion (consolidated, record Q2)"
    global_wholesale: "992K units (-6.9% YoY)"
    global_retail: "999K units (-4.2% YoY)"
    usa_market_share: "6.0% (5 consecutive quarters maintained)"
    global_hev_ratio: "18.9% (wholesale, highest ever)"
    usa_hev_ratio: "26.2% (wholesale, highest ever in U.S. market)"
  outlook: "Company expects to maintain market momentum through second half of 2026 with new model launches (Ioniq 3 in Europe, and other products) while capitalizing on growing HEV demand globally."
---
```

---

# 현대자동차 2026년 2분기 경영실적 발표

[이미지: 흰색 현대자동차 AVANTE 모델]

현대자동차 2026년 2분기 경영실적 발표

2026년 7월 23일

---

## 유의사항

본 자료는 2026년 2분기 실적에 대한 외부감사가 완료되지 않은 상태에서 투자자 여러분들의 편의를 위하여 작성된 자료로서, 제시된 자료의 내용 중 일부는 회계감사 과정에서 변경될 수 있음을 양지하시기 바랍니다.

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

### M/S ↑
**미국 시장 점유율 6%대 유지 (5개 분기 연속)**

미국 산업 수요 정체 불구, 당사 미국 HEV 판매 호조에 힘입어 5개 분기 연속 6%대 시장점유율 차증

### 18.9% — 글로벌 사상 최대 HEV 판매 비중 달성

- 글로벌 전체 판매 대수(도매 기준) 대비 HEV 비중 **18.9%** 달성  
- 미국 시장 HEV 판매 비중 **26.2%** 기록 (역대 최고)

### 49조원 — 역대 분기 최대 매출액 기록

지정학적 불황 확대로 인한 수요 감소 우려 불구, **역대 분기 최대 매출액** 기록 (연결 기준 KRW 49.0T)

---

## 글로벌 도·소매 판매 현황

### 전체 글로벌 통계

| 지표 | Q2 2025 | Q2 2026 | 변화율 | 단위 |
|------|---------|---------|--------|------|
| **신차 시장 수요** | 21,576 | 20,746 | -3.8% | 천대 |
| **도매 판매** | 1,066 | 992 | -6.9% | 천대 |
| **소매 판매** | 1,043 | 999 | -4.2% | 천대 |

**주석**: 
- 중국 제외 도매: Q2 2025 1,035천대 → Q2 2026 972천대 (-6.1%)
- 중국 제외 소매: Q2 2025 1,012천대 → Q2 2026 978천대 (-3.4%)

---

### 지역별 도·소매 판매 현황 (단위: 천대)

#### 미국

| 구분 | Q2 2025 신차수요 | Q2 2026 신차수요 | 변화율 | Q2 2025 도매 | Q2 2026 도매 | 변화율 | Q2 2025 소매 | Q2 2026 소매 | 변화율 |
|------|---------|---------|--------|--------|--------|--------|--------|--------|--------|
| **미국** | 4,217 | 4,238 | +0.5% | 262 | 265 | **+0.9%** | 256 | 266 | **+4.1%** |

**분석**: 미국 산업 수요가 정체(+0.5%)하는 가운데도 현대차의 도매 판매는 +0.9%, 소매 판매는 +4.1% 성장. 소매 대비 도매 증가율이 낮은 이유는 판매 채널 믹스 차이로 추정.

#### 유럽

| 구분 | Q2 2025 신차수요 | Q2 2026 신차수요 | 변화율 | Q2 2025 도매 | Q2 2026 도매 | 변화율 | Q2 2025 소매 | Q2 2026 소매 | 변화율 |
|------|---------|---------|--------|--------|--------|--------|--------|--------|--------|
| **유럽** | 4,276 | 4,400 | +2.9% | 161 | 144 | **-10.9%** | 159 | 147 | **-7.2%** |

**분석**: 유럽 산업 수요는 +2.9%로 증가했으나, 현대차 도매는 -10.9% 감소. 이는 경제 심화, 지정학적 리스크, 하반기 신차 출시 준비(아이오닉3 등)로 인한 전략적 판매 조절로 해석됨.

#### 국내

| 구분 | Q2 2025 신차수요 | Q2 2026 신차수요 | 변화율 | Q2 2025 도매 | Q2 2026 도매 | 변화율 | Q2 2025 소매 | Q2 2026 소매 | 변화율 |
|------|---------|---------|--------|--------|--------|--------|--------|--------|--------|
| **국내** | 440 | 440 | -0.1% | 189 | 158 | **-16.4%** | 189 | 158 | **-16.4%** |

**분석**: 국내 시장 수요는 정체 수준(-0.1%)인데 현대차 판매는 -16.4% 감소. 도매와 소매가 동일하며, 이는 국내 시장 경쟁 심화 또는 수출 우선 정책으로 추정.

#### 인도

| 구분 | Q2 2025 신차수요¹ | Q2 2026 신차수요¹ | 변화율 | Q2 2025 도매 | Q2 2026 도매 | 변화율 | Q2 2025 소매 | Q2 2026 소매 | 변화율 |
|------|---------|---------|--------|--------|--------|--------|--------|--------|--------|
| **인도** | 1,029 | 1,291 | **+25.6%** | 132 | 139 | **+5.4%** | 131 | 140 | **+7.4%** |

**주석**: ¹인도 도매 기준. 인도전 대형 상용차 미포함.

**분석**: 인도 시장 수요가 강성장(+25.6%)하는 가운데 현대차도 도매 +5.4%, 소매 +7.4%로 성장. 수요 증가 속도에 비해 판매 성장이 완만한 이유는 현지 시장의 경쟁 심화 또는 공급 제약으로 추정.

#### 중국

| 구분 | Q2 2025 신차수요² | Q2 2026 신차수요² | 변화율 | Q2 2025 도매 | Q2 2026 도매 | 변화율 | Q2 2025 소매 | Q2 2026 소매 | 변화율 |
|------|---------|---------|--------|--------|--------|--------|--------|--------|--------|
| **중국** | 5,730 | 4,283 | **-25.1%** | 31 | 19 | **-36.9%** | 31 | 21 | **-32.6%** |

**주석**: ²중국 도매 기준. 상용차, 제네비스 포함.

**분석**: 중국 시장이 급격한 수요 감소(-25.1%)를 겪는 가운데 현대차의 낙폭이 더욱 심함(도매 -36.9%, 소매 -32.6%). 이는 중국 시장에서의 경쟁력 약화 또는 현지 경쟁사(BYD 등)의 강화를 시사.

#### 기타 지역

| 지역 | 도매 (Q2 2025 → Q2 2026) | 소매 (Q2 2025 → Q2 2026) | 변화율 (도매) | 변화율 (소매) |
|------|---------|---------|--------|--------|
| **중남미** | 85 → 91 | - | +8.1% | +12.5%³ |
| **아태 (인도, 중국 제외)** | 50 → 43 | - | -12.5% | -11.2%³ |
| **아프리카 & 중동** | 84 → 61 | - | -23.8% | -17.3%³ |
| **기타⁴** | 72 → 74 | - | -5.9% | -3.9%³ |

**주석**:  
³소매 변화율 미기입 (원본 테이블 오류)  
⁴러시아, 기타 권역 포함

---

## 미국 시장 상세 분석

### 차금별 판매 (단위: 천대, 도매 기준)

| 차금 | Q2 2025 대수 | Q2 2025 비중 | Q2 2026 대수 | Q2 2026 비중 | 변화율 |
|------|---------|--------|---------|--------|--------|
| **SUV** | 196 | 75.1% | 193 | 72.9% | **-1.5%** |
| **PV (승용차)** | 66 | 24.9% | 72 | 27.1% | **+9.1%** |
| **전체** | 262 | - | 265 | - | **+0.9%** |

**분석 및 Stage 4 교정**: 
- ⚠️ 원본 확인 필요: SUV 절대값 계산(265 × 72.9% = 193.185 ≈ 193천대) 검증 완료이나, 테이블 기재값('196 → 193천대 (-3천대)')과 상이. 원본 데이터에서 SUV 비중 72.9%가 정확한지 재확인 필요
- PV(승용차) 판매는 66 → 72천대로 +6천대(+9.1%) 증가, 비중도 24.9% → 27.1%로 상승
- 이는 중형 세단 수요 증가(예: AVANTE, ELANTRA)를 반영

### xEV(전동화차량) 판매 현황 (도매 기준, %)

| 파워트레인 | Q2 2025 | Q2 2026 | 변화 (p) |
|----------|---------|---------|--------|
| **EV** | 10.2% | 4.0% | -6.2p |
| **HEV** | 19.4% | 26.2% | **+6.8p** |
| **PHEV** | 0.4% | 0.4% | flat |
| **FCEV** | 0.002% | N/A | 중단 |
| **xEV 합계 (절대값)** | 79천대 | 81천대 | +2천대 |

**분석**:
- HEV(하이브리드) 판매 비중이 19.4% → 26.2%로 **+6.8p 상승** → 미국 역대 최고 기록
  - 절대값: 약 51천대 → 69천대 (+18천대, +35.3%)
- EV 판매 비중이 10.2% → 4.0%로 **-6.2p 하락** → 하이브리드로의 수요 전환 시사
  - 절대값: 약 27천대 → 11천대 (-16천대, -59.3%)
- **고유가(휘발유 가격 상승) 환경에서 HEV가 소비자 선호도 상승**

### 미국 시장 요약

✓ **산업 수요 정체 불구 점유율 유지**: 미국 산업 신차 수요 +0.5% 정체 상황에서 현대차 도매 +0.9%, 소매 +4.1% 성장 → **5개 분기 연속 6%대 시장점유율 유지**

✓ **HEV 성장이 핵심 동력**: 고유가로 인한 연비 중심 소비 선호도 상승에 따라 HEV 판매가 19.4% → 26.2%로 대폭 증가 → **미국 시장 역대 최고 HEV 판매 비중 달성**

✓ **세단(PV) 수요 회복**: 경제 정체 환경에서 SUV보다 실용적이고 연비 우수한 중형 세단(AVANTE, ELANTRA 등)으로의 수요 집중 → 세단 판매 비중 +9.6%

---

## 유럽 시장 상세 분석

### 차금별 판매 (단위: 천대, 도매 기준)

| 차금 | Q2 2025 대수 | Q2 2025 비중 | Q2 2026 대수 | Q2 2026 비중 | 변화율 |
|------|---------|--------|---------|--------|--------|
| **SUV** | 106 | 65.8% | 107 | 74.2% | **+0.9%** |
| **PV (승용차)** | 54 | 33.2% | 36 | 25.1% | **-33.3%** |
| **CV (상용차)** | 2 | 1.0% | 1 | 0.7% | **-50.0%** |
| **전체** | 161 | - | 144 | - | **-10.9%** |

**분석**:
- 전체 도매는 161 → 144천대로 -17천대(-10.9%) 감소
- **SUV는 선전**: 106 → 107천대로 +1천대(+0.9%) 증가, 비중도 65.8% → 74.2%로 상승
  - SUV 비중 상승분(+8.4p)이 PV와 CV의 비중 하락분(-8.1p, -0.3p)을 초과 → 전략적 SUV 포지셔닝 성공
- **PV는 급락**: 54 → 36천대로 -18천대(-33.3%) 급감, 비중 33.2% → 25.1%
  - 이는 유럽의 경제 심화로 세단 수요 감소 + 하반기 신차 출시 준비로 해석
- **CV(상용차)**: 2 → 1천대로 -50% 감소

### xEV(전동화차량) 판매 현황 (도매 기준, %)

| 파워트레인 | Q2 2025 | Q2 2026 | 변화 (p) |
|----------|---------|---------|--------|
| **EV** | 18.6% | 21.8% | **+3.2p** |
| **HEV** | 19.3% | 25.5% | **+6.2p** |
| **PHEV** | 6.8% | 4.7% | -2.1p |
| **FCEV** | 0.02% | 0.002% | -0.018p |
| **xEV 합계 (절대값)** | 71천대 | 72천대 | +1천대 |

**분석 및 Stage 4 교정**:
- ⚠️ 원본 확인 필요: 문서 손상 가능성. PHEV 섹션이 중단되어 원본 데이터 완전성 확인 필요
- **EV 성장**: 18.6% → 21.8%로 **+3.2p 상승** → 유럽의 EV 보조금 정책 효과
- **HEV 강세**: 19.3% → 25.5%로 **+6.2p 상승** → 유럽 최고의 전동화 성장률
- **PHEV 약세**: 6.8% → 4.7%로 -2.1p 하락 → EV와 HEV로의 양극화
- **절대값 분석**: 전체 도매 감소(-10.9%) 속에서도 xEV 수량은 71 → 72천대로 미미하게 증가(+1천대) → xEV 비중 상승 주요 성장 동력

### 유럽 시장 요약

✓ **전략적 포트폴리오 전환 성공**: 전체 판매 감소(-10.9%) 속에서 SUV 비중을 65.8% → 74.2%로 상향 조정 → 고마진 상품 집중

✓ **xEV 판매 호조**: 산업 부진 속에서 EV(+3.2p), HEV(+6.2p)의 동시 성장 → 유럽 친환경 정책에 부응한 포지셔닝 성공

✓ **하반기 신차 준비**: 현재 세단 판매 부진은 아이오닉3 등 신차 출시 전 재고 조정으로 해석 → 하반기 회복 기대

---

## 주요 시장별 성과 및 과제

### 성과 요약

| 항목 | 평가 | 근거 |
|------|------|------|
| **글로벌 HEV 성장** | 🟢 우수 | 18.9% 달성 (사상 최고) |
| **미국 시장점유율** | 🟢 우수 | 6%대 5개 분기 연속 유지 |
| **수익


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
