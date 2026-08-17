```yaml
---
title: "SK하이닉스 2026년 2분기 실적발표"
company: "SK하이닉스"
ticker: "000660"
ticker_us: "SK Hynix Inc."
english_name: "SK Hynix Inc."
doc_type: "실적발표"
publish_date: "2026-07-29"
fiscal_year: 2026
fiscal_quarter: "Q2"
source: "IRGO"
pipeline_version: "v2.0.0"
converted_at: "2025-01-01T00:00:00Z"

key_figures:
  dart_revenue_annual:
    value: "971,466.8"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_operating_profit_annual:
    value: "472,063.2"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_net_income_annual:
    value: "429,479.0"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_total_assets:
    value: "1,761,076.6"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_total_liabilities:
    value: "554,409.1"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_total_equity:
    value: "1,206,667.5"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  # === 매출 부문 ===
  revenue_q2_2026:
    value: "79.32"
    unit: "조원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
    note: "역대 최대 분기 매출"
  
  revenue_q2_2026_trillion:
    value: "7,932"
    unit: "십억원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
    note: "79.32조원 = 7,932십억원 (본문 통계표 기준)"
  
  revenue_q1_2026:
    value: "52.58"
    unit: "조원"
    basis: "연결"
    period: "2026 Q1"
    confidence: 0.99
    note: "분기 실적"
  
  revenue_growth_qoq:
    value: "+51%"
    basis: "연결"
    period: "2026 Q2 vs Q1"
    confidence: 0.99
    note: "79.32조원 ÷ 52.58조원"
  
  revenue_growth_yoy:
    value: "+257%"
    basis: "연결"
    period: "2026 Q2 vs 2025 Q2"
    confidence: 0.8
    note: "전년동기비 증가율 | ⚠️ Stage 4 교정: 전년동기 매출이 본문에 명시되지 않아 검증 불가. 역산 시 Q2'25 매출은 약 21.8조원 수준이어야 함 (79.32 ÷ 3.57 ≈ 22.2조원)"
  
  revenue_q2_2025_implied:
    value: "N/A"
    unit: "조원"
    basis: "연결"
    period: "2025 Q2"
    confidence: 0
    note: "Stage 4 교정: YoY 검증용 명시 필요 - 본문에 미제시"

  # === 매출 구성 (DRAM/NAND) ===
  dram_asp_growth_qoq:
    value: "약 +30%"
    period: "2026 Q2 vs Q1"
    confidence: 0.85
    note: "DRAM ASP(평균판매가격) 분기대비 증가"
  
  dram_bg_growth_qoq:
    value: "한자릿수% 중반"
    period: "2026 Q2 vs Q1"
    confidence: 0.80
    note: "DRAM B/G(비트 성장률) 분기대비 증가"
  
  nand_asp_growth_qoq:
    value: "약 +50% 중반"
    period: "2026 Q2 vs Q1"
    confidence: 0.85
    note: "NAND ASP 분기대비 증가"
  
  nand_bg_growth_qoq:
    value: "+10% 중반"
    period: "2026 Q2 vs Q1"
    confidence: 0.85
    note: "NAND B/G 분기대비 증가; Solidigm 인정 실적 기준"

  # === 영업이익 부문 ===
  operating_profit_q2_2026:
    value: "60.54"
    unit: "조원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
    note: "5개 분기(2025 Q2~2026 Q2) 연속 사상 최대 분기 영업이익 경신"
  
  operating_profit_q2_2026_billion:
    value: "60,543"
    unit: "십억원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
    note: "60.54조원 = 60,543십억원 (본문 통계표 기준)"
  
  operating_profit_growth_qoq:
    value: "+61%"
    basis: "연결"
    period: "2026 Q2 vs Q1"
    confidence: 0.75
    note: "분기대비 영업이익 증가 | ⚠️ Stage 4 교정: Q1 영업이익이 본문/YAML에 명시되지 않아 검증 불가. 역산 시 Q1'26 영업이익은 약 37.5조원 수준이어야 함 (60.54 ÷ 1.61)"
  
  operating_profit_q1_2026_implied:
    value: "N/A"
    unit: "조원"
    basis: "연결"
    period: "2026 Q1"
    confidence: 0
    note: "Stage 4 교정: QoQ 검증용 명시 필요 - 본문에 미제시"

  operating_profit_growth_yoy:
    value: "+557%"
    basis: "연결"
    period: "2026 Q2 vs 2025 Q2"
    confidence: 0.7
    note: "전년동기비 영업이익 증가 | ⚠️ Stage 4 교정: Q2'25 영업이익이 본문에 명시되지 않아 검증 불가. 역산 시 Q2'25 영업이익은 약 10.8조원 수준이어야 함 (60.54 ÷ 5.57)"
  
  operating_profit_q2_2025_implied:
    value: "N/A"
    unit: "조원"
    basis: "연결"
    period: "2025 Q2"
    confidence: 0
    note: "Stage 4 교정: YoY 검증용 명시 필요 - 본문에 미제시"
  
  operating_margin:
    value: "76%"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
    note: "영업이익률 = 60.54조 ÷ 79.32조; 분기 기준 최고 기록"

  # === 손익 구성요소 (십억원 기준) ===
  revenue_consolidated_billion:
    value: "79,319"
    unit: "십억원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
    note: "매출액"
  
  cost_of_revenue:
    value: "65,991"
    unit: "십억원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
    note: "매출원가"
  
  gross_profit:
    value: "13,327"
    unit: "십억원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
    note: "매출이익 = 79,319 - 65,991"
  
  sga_expenses:
    value: "5,449"
    unit: "십억원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
    note: "판관비(판매관리비)"
  
  operating_profit_from_components:
    value: "60,543"
    unit: "십억원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.7
    note: "영업이익 | ⚠️ Stage 4 교정: 산술 검증 오류 발견. 매출이익(13,327) - 판관비(5,449) = 7,878(십억원)이나, 영업이익 60,543으로 표기됨. 본문에서 '재계산 필요'로 주석되었으나 명시적 조정항목 부재. 추정 조정항목: 약 52,665십억원 (기타영업이익 또는 특수항목 포함으로 추정되나 원본 명확화 필요)"

  # === EBITDA ===
  da_depreciation:
    value: "4,020"
    unit: "십억원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
    note: "D&A = 감가상각비 및 무형자산상각비"
  
  ebitda:
    value: "64.56"
    unit: "조원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.95
    note: "EBITDA = 영업이익 + D&A = 60.54 + 4.02"
  
  ebitda_billion:
    value: "64,563"
    unit: "십억원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.95
    note: "64.56조원 = 64,563십억원"
  
  ebitda_growth_qoq:
    value: "+56%"
    basis: "연결"
    period: "2026 Q2 vs Q1"
    confidence: 0.75
    note: "분기대비 EBITDA 증가 | ⚠️ Stage 4 교정: Q1 EBITDA가 본문에 명시되지 않아 검증 불가. 역산 시 Q1'26 EBITDA는 약 41.4조원 수준이어야 함 (64.56 ÷ 1.56)"
  
  ebitda_q1_2026_implied:
    value: "N/A"
    unit: "조원"
    basis: "연결"
    period: "2026 Q1"
    confidence: 0
    note: "Stage 4 교정: QoQ 검증용 명시 필요 - 본문에 미제시"
  
  ebitda_growth_yoy:
    value: "+411%"
    basis: "연결"
    period: "2026 Q2 vs 2025 Q2"
    confidence: 0.95
    note: "전년동기비 EBITDA 증가"
  
  ebitda_q2_2025_implied:
    value: "N/A"
    unit: "조원"
    basis: "연결"
    period: "2025 Q2"
    confidence: 0
    note: "Stage 4 교정: YoY 검증용 명시 필요 - 본문에 미제시"
  
  ebitda_margin:
    value: "81%"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.95
    note: "EBITDA 마진율"

  # === 순이익 부문 ===
  operating_income_external:
    value: "62.17"
    unit: "조원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.65
    note: "영업외순익 | ⚠️ Stage 4 교정: 62.17조원에 대한 내역이 모호함. 영업외순익과 투자자산 이익(63.27조원)의 관계가 불명확하며, 외환관련이익(1.15조원)과의 연계 방식 명확화 필요"
  
  foreign_exchange_gain:
    value: "1.15"
    unit: "조원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
    note: "외환관련이익 (환율 상승 효과)"
  
  investment_asset_income:
    value: "63.27"
    unit: "조원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.85
    note: "투자자산 관련 순이익 (기타 영업외순익에 포함)"
  
  other_operating_income:
    value: "60.89"
    unit: "조원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.85
    note: "기타 영업외순익 (투자자산 관련 순이익 63.27조 포함)"
  
  income_before_tax:
    value: "122.708"
    unit: "조원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
    note: "법인세차감전순이익"
  
  income_before_tax_billion:
    value: "122,708"
    unit: "십억원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
  
  tax_expense:
    value: "28.786"
    unit: "조원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
    note: "법인세 비용"
  
  tax_expense_billion:
    value: "28,786"
    unit: "십억원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
  
  net_income:
    value: "93.92"
    unit: "조원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
    note: "당기순이익 = 122.708 - 28.786"
  
  net_income_billion:
    value: "93,923"
    unit: "십억원"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
    note: "93.92조원 = 93,923십억원"
  
  net_margin:
    value: "118%"
    basis: "연결"
    period: "2026 Q2"
    confidence: 0.99
    note: "당기순이익률 = 93.92 ÷ 79.32"

  # === 재무상태 ===
  cash_q2_2025:
    value: "16.96"
    unit: "조원"
    basis: "연결"
    period: "2025 Q2말"
    confidence: 0.99
    note: "현금 = 현금 및 현금장치 + 단기금융상품"
  
  cash_q1_2026:
    value: "54.33"
    unit: "조원"
    basis: "연결"
    period: "2026 Q1말"
    confidence: 0.99
  
  cash_q2_2026:
    value: "87.96"
    unit: "조원"
    basis: "연결"
    period: "2026 Q2말"
    confidence: 0.99
    note: "현금 급증 (분기 영업이익 및 투자자산 이익 반영)"
  
  debt_q2_2025:
    value: "21.84"
    unit: "조원"
    basis: "연결"
    period: "2025 Q2말"
    confidence: 0.99
    note: "차입금 = 단기차입금 + 유동성장기채무 + 사채 + 장기차입금"
  
  debt_q1_2026:
    value: "19.32"
    unit: "조원"
    basis: "연결"
    period: "2026 Q1말"
    confidence: 0.99
  
  debt_q2_2026:
    value: "18.59"
    unit: "조원"
    basis: "연결"
    period: "2026 Q2말"
    confidence: 0.99
  
  debt_ratio_q2_2025:
    value: "25%"
    basis: "연결"
    period: "2025 Q2말"
    confidence: 0.99
    note: "차입금비율"
  
  debt_ratio_q1_2026:
    value: "18%"
    basis: "연결"
    period: "2026 Q1말"
    confidence: 0.99
  
  debt_ratio_q2_2026:
    value: "7%"
    basis: "연결"
    period: "2026 Q2말"
    confidence: 0.99
    note: "차입금비율 급락 (현금 증가 + 차입금 감소)"
  
  net_debt_ratio_q2_2025:
    value: "6%"
    basis: "연결"
    period: "2025 Q2말"
    confidence: 0.99
    note: "순차입금비율"
  
  net_debt_ratio_q1_2026:
    value: "-4%"
    basis: "연결"
    period: "2026 Q1말"
    confidence: 0.99
    note: "순차입금비율 음수 (순현금 상태)"
  
  net_debt_ratio_q2_2026:
    value: "-11%"
    basis: "연결"
    period: "2026 Q2말"
    confidence: 0.99
    note: "순차입금비율 음수 (강한 순현금 상태)"

english_summary:
  title: "SK Hynix Q2 2026 Earnings Results"
  one_liner: "Record quarterly revenue of KRW 79.3 trillion (+51% QoQ, +257% YoY); operating profit of KRW 60.5 trillion (+61% QoQ, +557% YoY) with 76% operating margin."
  highlights:
    - "Record quarterly revenue of KRW 79.3 trillion, up 51% QoQ and 257% YoY, driven by DRAM and NAND price increases across the board"
    - "Operating profit reached KRW 60.5 trillion, marking five consecutive quarters of record quarterly operating profits; operating margin expanded to 76%, the highest on a quarterly basis"
    - "Strong EBITDA of KRW 64.6 trillion with 81% margin, up 56% QoQ and 411% YoY"
    - "Net income surged to KRW 93.9 trillion (net margin: 118%), benefiting from operating profit growth and investment asset-related gains of KRW 63.3 trillion"
    - "Fortress balance sheet: cash position strengthened to KRW 88.0 trillion (+61% QoQ), debt ratio improved to 7%, and net debt ratio turned negative at -11%"
  key_figures_en:
    revenue: "KRW 79.3 trillion (consolidated, +51% QoQ, +257% YoY)"
    operating_profit: "KRW 60.5 trillion (+61% QoQ, +557% YoY; operating margin 76%)"
    ebitda: "KRW 64.6 trillion (EBITDA margin 81%)"
    net_income: "KRW 93.9 trillion (net margin 118%)"
    cash_position: "KRW 88.0 trillion (Q2 2026 end)"
    debt_ratio: "7% (vs. 25% in Q2 2025)"
    net_debt_ratio: "-11% (net cash position)"
  outlook: "Company maintains momentum from DRAM and NAND market recovery with strong pricing environment and cost improvements; balance sheet strengthened significantly with declining leverage ratios."
---
```

# SK Hynix 2026년 2분기 실적발표

2026.07.29 | Investor Relations

---

## 공시 및 주의 사항

본 자료는 정보 제공만을 위하여 당사에 의해 작성된 것으로서, 본 자료에 기재된 정보에 대해서는 법도의 도림적인 확인 과정을 거치지 않았습니다. 본 자료에 포함된 정보의 공정성, 정확성 또는 완결성과 관련해서는 어떠한 진술 및 보장도 제공되지 않으며, 이를 신뢰하여서도 안 됩니다. 당사 및 임직원은 본 자료와 관련하여, 또는 그 내용을 이용함으로 인하여 발생하는 어떠한 손해에 대해서도 민·형사상 및 행정상의 책임을 일절 부담하지 않습니다.

본 자료는 외부감시인의 감시가 완료되지 않은 상태에서 투자자 여러분의 편의를 위하여 작성된 자료이며, 내용 중 일부는 외부 감시인의 감시 과정에서 달라질 수 있습니다.

이 자료에 포함된 회사의 재무성과에 대한 모든 정보는 **한국채택국제회계기준(K-IFRS)에 따라 연결 기준**으로 작성되었습니다.

또한, 본 자료는 미래에 대한 예상, 전망, 계획, 기대 등의 '예측정보'를 포함하고 있으며 이러한 '예측정보'는 그 성격의 불확실성으로 인해 회사의 실제 미래실적과 중대한 차이가 있을 수 있음을 양지하시기 바랍니다.

본 자료는 자본시장과 금융투자업에 관한 법률상 증권의 취득 또는 매수에 대한 청약의 권유를 구성하지 않으며, 본 자료의 어떠한 부분도 어떠한 계약, 약정 또는 투자결정의 근거가 되거나 그와 관련하여 신뢰 되어서는 안 됩니다.

---

# 재무실적

## 매출 분석 — 역대 최대 분기 매출 달성

### 2026 Q2 매출: **79.32조원 (K-IFRS 연결)**

| 지표 | 수치 | 기준 |
|------|------|------|
| **Q2 2026 매출** | **79.32조원** | 연결 |
| 분기대비 증가율 | +51% | Q1 2026 vs Q2 2026 |
| 전년동기비 증가율 | +257% | Q2 2025 vs Q2 2026 |

**Stage 4 교정:** 전년동기 매출액(Q2 2025)이 본문에 명시되지 않아 +257% 검증이 불가능합니다. 역산 시 Q2'25 매출은 약 21.8조원 수준이어야 합니다(79.32 ÷ 3.57). ⚠️ 원본 자료에서 Q2'25 실제 매출액 명시 필요

### 2026 Q1 매출: **52.58조원 (K-IFRS 연결)**

#### 제품별 성장 동인

**DRAM:**
- 비트 성장(B/G): 한자릿수% 중반 ↑ QoQ
- 평균판매가격(ASP): 약 30% ↑ QoQ

**NAND:**
- 비트 성장(B/G): 10% 중반 ↑ QoQ  
- 평균판매가격(ASP): 50% 중반 ↑ QoQ
- *Solidigm 인정 실적 기준

---

## 이익 분석 — 영업이익

### 5개 분기 연속 사상 최대 분기 영업이익 경신  
**2025 Q2 → 2026 Q2 (5개 분기)**

### 2026 Q2 영업이익: **60.54조원 (K-IFRS 연결)**

| 항목 | 금액 (십억원) | 비율 |
|------|---------------|----|
| **매출액** | **79,319** | **100.0%** |
| 매출원가 | 65,991 | 83.2% |
| **매출이익** | **13,327** | **16.8%** |
| 판관비(SG&A) | 5,449 | 6.9% |
| **영업이익** | **60,543** | **76.3%** |

**Stage 4 교정:** 산술 검증 결과 불일치 발견:
- 매출이익(13,327) - 판관비(5,449) = 7,878(십억원)
- 그러나 영업이익 = 60,543(십억원)
- **미계정 조정항목: 약 52,665십억원** 추정

본문에서 "재계산 필요"로 표기되었으나 명시적 조정항목이 제시되지 않았습니다. 기타영업이익, 특수항목, 또는 원가 배분 관련 내용이 추가 설명되어야 합니다. ⚠️ 원본 자료에서 영업이익 구성요소 상세 설명 필요

#### 영업이익 성장
- **분기대비(QoQ):** +61%  
  **Stage 4 교정:** Q1 2026 영업이익이 명시되지 않아 검증 불가. 역산 시 Q1'26 영업이익 약 37.5조원 수준 필요(60.54 ÷ 1.61). ⚠️ 원본 자료에서 Q1 영업이익 명시 필요

- **전년동기비(YoY):** +557%  
  **Stage 4 교정:** Q2 2025 영업이익이 명시되지 않아 검증 불가. 역산 시 Q2'25 영업이익 약 10.8조원 수준 필요(60.54 ÷ 5.57). ⚠️ 원본 자료에서 Q2'25 영업이익 명시 필요

#### 수익성 개선 동인
- DRAM·NAND 전반에 걸친 **가격 상승** ✓ (비용 대비 높은 마진)
- **원가 개선** ✓ (원가율 83.2% → 효율성 증대)
- **분기 기준 최고 영업이익률 달성: 76.3%** ✓

---

## 감가상각비 및 EBITDA

### 감가상각비 및 무형자산상각비 (D&A): **4.02조원 (K-IFRS 연결)**

| 항목 | 금액 (십억원) |
|------|---------------|
| 영업이익 | 60,543 |
| D&A (감가상각비 + 무형자산상각비) | 4,020 |
| **EBITDA** | **64,563** |

### 2026 Q2 EBITDA: **64.56조원**

#### EBITDA 성장 및 마진
- **분기대비(QoQ):** +56%  
  **Stage 4 교정:** Q1 2026 EBITDA가 명시되지 않아 검증 불가. 역산 시 Q1'26 EBITDA 약 41.4조원 수준 필요(64.56 ÷ 1.56). ⚠️ 원본 자료에서 Q1 EBITDA 명시 필요

- **전년동기비(YoY):** +411%  
  **Stage 4 교정:** Q2 2025 EBITDA가 명시되지 않아 검증 불가. 원본 자료에서 Q2'25 EBITDA 명시 필요

- **EBITDA 마진율:** 81.4%

---

## 이익 분석 — 순이익

### 영업외순익 및 특수 항목

| 항목 | 금액 | 설명 |
|------|------|------|
| **외환관련이익** | 1.15조원 | 환율 상승에 따른 환차익 |
| **투자자산 관련 순이익** | 63.27조원 | 주요 영업외 수익 항목 |
|


---

## DART 연결재무제표 (SK하이닉스, 2025년)
<!-- source: OpenDART API | ground_truth: true -->

| 계정 | 금액(억원) | 출처 |
|------|--------:|------|
| 매출액 | 971,466.8 | DART |
| 영업이익 | 472,063.2 | DART |
| 당기순이익 | 429,479.0 | DART |
| 자산총계 | 1,761,076.6 | DART |
| 부채총계 | 554,409.1 | DART |
| 자본총계 | 1,206,667.5 | DART |
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
