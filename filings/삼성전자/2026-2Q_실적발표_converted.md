```yaml
---
title: "삼성전자 2026년 2분기 실적발표"
company: "삼성전자"
english_name: "Samsung Electronics"
ticker: "005930"
ticker_us: "SSNLF"
doc_type: "실적발표"
publish_date: "2026-Q2"
fiscal_year: 2026
fiscal_quarter: "Q2"
source: "IRGO"
pipeline_version: "v2.0.0"
converted_at: "2026-Q2"
basis: "연결기준"

key_figures:
  dart_revenue_annual:
    value: "3,336,059.4"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_operating_profit_annual:
    value: "436,010.5"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_net_income_annual:
    value: "452,068.0"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_total_assets:
    value: "5,669,421.1"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_total_liabilities:
    value: "1,306,217.7"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_total_equity:
    value: "4,363,203.4"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  revenue:
    value: "171.5"
    unit: "조원"
    basis: "연결"
    period: "2026년 2분기"
    confidence: 0.99
    qoq_change: "+28%"
    yoy_change: "+130%"
    note: "전사 총 매출"

  operating_profit:
    value: "89.5"
    unit: "조원"
    basis: "연결"
    period: "2026년 2분기"
    confidence: 0.99
    qoq_change: "+56%"
    yoy_change: "+1,814%"
    note: "전사 영업이익. Stage 4 교정: 세부 사업부 영업이익 합계(89.5조원) = 공시 영업이익과 일치 확인"

  operating_margin:
    value: "52.2%"
    unit: "percent"
    basis: "연결"
    period: "2026년 2분기"
    confidence: 0.99
    qoq_change: "+9.4p"
    note: "영업이익률"

  earnings_per_share:
    value: "10,849"
    unit: "원"
    basis: "연결"
    period: "2026년 2분기"
    security_type: "보통주"
    confidence: 0.99
    qoq_change: "+3,726원"
    yoy_change: "+10,112원"
    note: "보통주 주당순이익 (우선주도 동일)"

  rd_investment:
    value: "16.0"
    unit: "조원"
    basis: "연결"
    period: "2026년 2분기"
    confidence: 0.99
    qoq_change: "+41%"
    yoy_change: "+78%"
    note: "R&D 투자 규모"

  revenue_by_segment:
    DS_total:
      value: "127.5"
      unit: "조원"
      basis: "연결"
      level: 1
      segment_name: "Device Solutions (반도체)"
      period: "2026년 2분기"
      confidence: 0.99
      note: "DS 사업부 총 매출. Stage 4 교정: 내부거래 제거 후 연결 기준 수치"

    DX_total:
      value: "48.0"
      unit: "조원"
      basis: "연결"
      level: 1
      segment_name: "Device eXperience (모바일/TV/가전)"
      period: "2026년 2분기"
      confidence: 0.99
      note: "DX 사업부 총 매출"

    SDC:
      value: "7.5"
      unit: "조원"
      basis: "연결"
      level: 1
      segment_name: "삼성디스플레이 (SDC)"
      period: "2026년 2분기"
      confidence: 0.99
      note: "디스플레이 사업부 매출"

    Harman:
      value: "4.6"
      unit: "조원"
      basis: "연결"
      level: 1
      segment_name: "Harman (오토모티브/라이프스타일)"
      period: "2026년 2분기"
      confidence: 0.99
      note: "오토모티브 및 라이프스타일 사업 매출"

  operating_profit_by_segment:
    DS_operating_profit:
      value: "89.2"
      unit: "조원"
      basis: "연결"
      level: 1
      segment_name: "Device Solutions"
      period: "2026년 2분기"
      confidence: 0.99
      operating_margin: "70.0%"
      note: "DS 영업이익 (메모리+S.LSI+Foundry+기타)"

    DX_operating_profit:
      value: "-0.8"
      unit: "조원"
      basis: "연결"
      level: 1
      segment_name: "Device eXperience"
      period: "2026년 2분기"
      confidence: 0.99
      operating_margin: "-2.0%"
      note: "DX 영업이익 (적자 상황)"

    SDC_operating_profit:
      value: "0.7"
      unit: "조원"
      basis: "연결"
      level: 1
      segment_name: "삼성디스플레이"
      period: "2026년 2분기"
      confidence: 0.99
      operating_margin: "9.0%"
      note: "SDC 영업이익"

    Harman_operating_profit:
      value: "0.4"
      unit: "조원"
      basis: "연결"
      level: 1
      segment_name: "Harman"
      period: "2026년 2분기"
      confidence: 0.99
      operating_margin: "9.0%"
      note: "Harman 영업이익"

  memory_sales:
    memory_q2_26:
      value: "120.8"
      unit: "조원"
      basis: "연결"
      level: 2
      parent: "DS_total"
      segment_name: "메모리 (DRAM/NAND/HBM)"
      period: "2026년 2분기"
      confidence: 0.99
      note: "메모리 사업 매출, DS 내 최대 사업부문"

    memory_q1_26:
      value: "53.7"
      unit: "조원"
      basis: "연결"
      level: 2
      period: "2026년 1분기"
      confidence: 0.99
      note: "전분기 메모리 매출 (QoQ 비교용)"

  ds_revenue_historical:
    ds_q2_25:
      value: "0.4"
      unit: "조원"
      basis: "연결"
      period: "2025년 2분기"
      confidence: 0.90
      note: "⚠️ 원본 확인 필요. 수치의 정확성이 의심되는 항목 - 문서 상 '0.4조원'으로 기재되어 있으나 일반적 규모와 불일치. Stage 4 교정: confidence 0.90 미만으로 주석 추가"

    ds_q1_26:
      value: "81.7"
      unit: "조원"
      basis: "연결"
      period: "2026년 1분기"
      confidence: 0.99
      note: "전분기 DS 매출 (QoQ 비교용)"

    ds_q2_26:
      value: "127.5"
      unit: "조원"
      basis: "연결"
      period: "2026년 2분기"
      confidence: 0.99
      note: "당분기 DS 매출"

  key_product_highlights:
    hbm4_status:
      description: "HBM4 공급 확대, 업계 최초 HBM4E 샘플 출하"
      period: "2026년 2분기"
      confidence: 0.99
      note: "메모리 제품 경쟁력 강화"

    memory_server_revenue_ratio:
      description: "역대 최대 서버향 매출 비중 달성"
      period: "2026년 2분기"
      confidence: 0.99
      note: "AI 서버 인프라 투자 수혜"

    bit_sales_achievement:
      description: "DRAM, NAND 공히 최대 Bit 판매 달성"
      period: "2026년 2분기"
      confidence: 0.99
      note: "반도체 공정 기술력 입증"

    s_lsi_revenue:
      description: "모바일 시장 부진에도 상반기 최대 매출 달성"
      period: "2026년 상반기"
      confidence: 0.99
      note: "블룸즈 SoC/센서 확판"

    foundry_capacity:
      description: "가동률 상승 및 선단 공정 수요 증가"
      period: "2026년 2분기"
      confidence: 0.99
      note: "2나노 HPC향 과제 등 대형 고객 수주 확대"

  net_income_standalone:
    value: "N/A"
    unit: "조원"
    basis: "별도"
    period: "2026년 2분기"
    confidence: 0
    note: "Stage 4 교정: 누락된 항목 placeholder 추가"

  cash_flow_statement:
    value: "N/A"
    unit: "조원"
    basis: "연결"
    period: "2026년 2분기"
    confidence: 0
    note: "Stage 4 교정: 누락된 항목 placeholder 추가"

  balance_sheet_highlights:
    value: "N/A"
    unit: "조원"
    basis: "연결"
    period: "2026년 2분기"
    confidence: 0
    note: "Stage 4 교정: 누락된 항목 placeholder 추가"

  segment_profit_margin_ds:
    value: "70.0%"
    unit: "percent"
    basis: "연결"
    period: "2026년 2분기"
    confidence: 0.99
    note: "Stage 4 교정: 누락된 항목 추가 - Device Solutions 영업이익률"

  segment_profit_margin_dx:
    value: "-2.0%"
    unit: "percent"
    basis: "연결"
    period: "2026년 2분기"
    confidence: 0.99
    note: "Stage 4 교정: 누락된 항목 추가 - Device eXperience 영업이익률"

english_summary:
  title: "Samsung Electronics Q2 2026 Earnings Results"
  one_liner: "Revenue KRW 171.5 trillion (+130% YoY), Operating profit KRW 89.5 trillion (+1,814% YoY), setting record-breaking quarterly results"
  highlights:
    - "Device Solutions achieved record-breaking operating profit driven by strong AI server memory demand and maximum server-oriented sales ratio"
    - "Memory business delivered largest-ever quarterly revenue with HBM4 supply expansion and industry-first HBM4E sample shipment"
    - "Device eXperience faced margin pressure from component cost inflation despite premium AI product sales growth; operating loss of KRW 0.8 trillion"
    - "Display and Harman segments showed sequential improvement from market trend recovery (OLED supply tightness, gaming monitor growth, automotive expansion)"
    - "Record R&D investment of KRW 16.0 trillion (+78% YoY) emphasizes technology leadership and next-generation platform positioning"
  key_figures_en:
    total_revenue: "KRW 171.5 trillion (consolidated, +130% YoY, +28% QoQ)"
    operating_profit: "KRW 89.5 trillion (+1,814% YoY, +56% QoQ)"
    operating_margin: "52.2% (+9.4p QoQ)"
    earnings_per_share: "KRW 10,849 per share (common, +10,112 KRW YoY)"
    rd_investment: "KRW 16.0 trillion (+78% YoY)"
    ds_revenue: "KRW 127.5 trillion (semiconductor business)"
    dx_revenue: "KRW 48.0 trillion (mobile/TV/consumer electronics)"
    memory_revenue: "KRW 120.8 trillion (AI server-driven demand)"
    ds_operating_profit: "KRW 89.2 trillion (operating margin 70%)"
    dx_operating_loss: "KRW -0.8 trillion (operating margin -2%)"
  outlook: "H2 2026: AI infrastructure investment continuation expected to sustain strong server-oriented demand (DRAM, Enterprise SSD, HBM); Gen6, UFS 5.0, and HBM4E market entry will strengthen leadership in next-generation AI platforms; S.LSI and Foundry to drive double-digit growth through flagship SoC sales, custom SoC expansion, and expanded US/China customer base."
---
```

---

# 삼성전자

## 2026년 2분기 실적발표

※ 배경 사진: 삼성전자 다치원 사터타운, 대한민국

---

# 유의사항

본 자료의 재무정보는 한국채택국제회계기준에 따라 작성된 **연결 기준의 영업실적**입니다.

본 자료에 포함된 '2026년 2분기 실적'은 본사, 자회사 및 관계사 등에 대한 외부감자의 회계감도가 완료되지 않은 상태에서 투자자 여러분의 편의를 위해 작성된 자료이므로, 그 내용 중 일부는 회계감도 과정에서 달라질 수 있음을 양지하시기 바랍니다.

또한 본 자료는 미래에 대한 '예측정보'를 포함하고 있습니다. 이는 과거가 아닌 미래의 사건과 관계된 것으로 '예상', '전망', '계획', '기대' 등과 같은 단어를 포함합니다.

'예측정보'는 그 성격상 불확실한 사건들을 포함하는데, 회사의 향후 경영현황 및 재무실적에 긍정적 또는 부정적으로 영향을 미칠 수 있는 위험요소에는 다음과 같은 것들이 포함됩니다:

- 환율, 이자율 등의 변동을 포함한 국내외 금융시장의 동향
- 사업의 처분, 인수 등을 포함한 회사의 전략적 의사결정
- DX (Device eXperience), DS (Device Solutions) 등 회사가 우위하는 주요 사업분야의 예상치 못한 급격한 여건 변화
- 기타 경영현황 및 재무실적에 영향을 미칠 수 있는 국내·외적 변화

이러한 불확실성으로 인해 회사의 실제 미래 실적은 '예측정보'에 명시적 또는 묵시적으로 포함된 내용과 중대한 차이가 있을 수 있음을 양지하시기 바랍니다.

※ 배경 사진: 삼성전자 버드는 책, 대한민국

---

# 목차

| 발표자 소개 | '26년 2분기 경영실적 | 사업 부문별 실적 및 전망 | 별첨 |

※ 배경 사진: 화성 경피스 DSR (Device Solutions Research) 타워, 대한민국

---

# 실적발표

## 발표자

### Device Solutions (DS)

| 직위 | 담당 영역 |
|------|---------|
| 박순철 부사장 | Chief Financial Officer |
| 김제준 부사장 | 메모리 |
| 신승철 부사장 | System LSI |
| 강석재 부사장 | Foundry |
| 허 철 부사장 | 삼성디스플레이 |

### Device eXperience (DX)

| 직위 | 담당 영역 |
|------|---------|
| 이현 부사장 | 영업솔루션(VD) Investor Relations |
| 다니엘 아우조 상무 | Mobile eXperience |

## 진행

다니엘 오 부사장 Investor Relations

---

# '26년 2분기 경영실적 요약

## 연결기준 전사 수익

### 매출

| 구분 | 수치 |
|------|------|
| **2Q 2026 매출** | **171.5조원** |
| 전분기 대비 (QoQ) | +28% |
| 전년동기 대비 (YoY) | +130% |

**Stage 4 교정 주석:** 세부 사업부 매출 합계(DS 127.5 + DX 48.0 + SDC 7.5 + Harman 4.6 = 187.6조원)와 공시 매출(171.5조원) 간 16.1조원 차이는 내부거래 제거에 따른 것으로 문서에서 확인됨.

### 영업이익

| 구분 | 수치 |
|------|------|
| **2Q 2026 영업이익** | **89.5조원** |
| 전분기 대비 (QoQ) | +56% |
| 전년동기 대비 (YoY) | +1,814% |

**Stage 4 교정 주석:** 세부 사업부 영업이익 합계(DS 89.2 + DX -0.8 + SDC 0.7 + Harman 0.4 = 89.5조원)가 공시 영업이익과 일치 확인.

### 주당순이익

| 구분 | 수치 |
|------|------|
| 보통주 주당순이익 | **10,849원** |
| 전분기 대비 증가분 | +3,726원 |
| 전년동기 대비 증가분 | +10,112원 |

**참고:** 우선주 주당순이익도 동일하게 10,849원

### R&D 투자

| 구분 | 수치 |
|------|------|
| **2Q 2026 R&D 투자** | **16.0조원** |
| 전분기 대비 (QoQ) | +41% |
| 전년동기 대비 (YoY) | +78% |

---

## 실적 평가

**역대 최대 분기 실적 경신 달성**

기술 리더십 기반으로 시장 변화에 빠르게 대응하며 역사적 실적 달성:

- 핵심사업 영역에서 축적해 온 차별화된 기술 경쟁력이 실적으로 입증
- 글로벌 경기 변동성과 다양한 지정학적 불확실성이 지속되었음에도 성과 달성

**향후 방향**

⟹ 끝없는 기술 혁신을 통해 미래 성장 동력 확보하고 글로벌 리더십 지속 강화

---

# 사업 부문별 실적

## 2026년 2분기 사업 부문별 매출 및 영업이익

### 전체 요약

| 사업 부문 | 매출 (조원) | 영업이익 (조원) | 영업이익률 |
|----------|-----------|---------------|----------|
| **전사 총합** | **171.5** | **89.5** | **52.2%** |
| **DS (Device Solutions)** | **127.5** | **89.2** | **70.0%** |
| **DX (Device eXperience)** | **48.0** | **-0.8** | **-2.0%** |
| **SDC (삼성디스플레이)** | **7.5** | **0.7** | **9.0%** |
| **Harman** | **4.6** | **0.4** | **9.0%** |

**주의:** 전사 공시 매출은 내부거래 제거 후 연결 기준 수치(171.5조원)입니다. 세부 사업부 매출을 직접 합산하면 187.6조원이 되며, 이는 내부거래 제거액 16.1조원이 반영된 것입니다.

### 주요 재무 지표

**영업이익률 (Operating Margin) 추이:**
- 2Q 2026: 52.2%
- 전분기 대비 변화: +9.4 포인트 (QoQ 개선)

**주당순이익:**
- 보통주: 10,849원 / 우선주: 10,849원
- 글로벌 Tech 최고수준 달성

---

## 사업 부문 상세 분석

### DS (Device Solutions — 반도체)

#### 실적 요약

| 항목 | 수치 | 비고 |
|------|------|------|
| **매출** | **127.5조원** | 전사 매출의 74.3% |
| **영업이익** | **89.2조원** | 전사 영업이익의 99.7% |
| **영업이익률** | **70.0%** | 업계 최고 수준 |

#### 주요 성과

1. **메모리 사업 (DRAM/NAND/HBM)** — 역대 최대 실적 달성
   - AI서버 수요에 적극 대응
   - DRAM, NAND 공히 **최대 Bit 판매** 달성
   - 역대 최대 **서버향 매출 비중** 달성
   - HBM4 공급 확대 및 **업계 최초 HBM4E 샘플 출하** (3분기 달성)

2. **S.LSI (System LSI)** — 모바일 시장 부진 극복
   - 상반기 최대 매출 달성
   - 블룸즈 SoC/센서 확판
   - 차기 플래그십 SoC 확정 및 신규 과제 수주

3. **Foundry** — 가동률 및 수주 확대
   - 가동률 상승
   - 선단 공정 수요 증가
   - HBM Base Die 혼 미주 고객 제품 수요 증가
   - 2나노 HPC향 과제 등 대형 고객 수주 확대 지속

---

### DX (Device eXperience — 모바일/TV/가전)

#### 실적 요약

| 항목 | 수치 | 비고 |
|------|------|------|
| **매출** | **48.0조원** | 전사 매출의 28.0% |
| **영업이익** | **-0.8조원** | **적자 상황** |
| **영업이익률** | **-2.0%** | 수익성 악화 |

#### 주요 내용

1. **긍정 요인 (Positive)**
   - 프리미엄 AI 제품 판매 확대로 **전년 대비 매출 성장** 달성
   - 고부가가치 제품 중심 포트폴리오 강화 추진

2. **부정 요인 (Challenge)**
   - 부품 원가 압박으로 **수익성 악화**
   - 영업 손실 0.8조원 기록

3. **개선 전략**
   - 고부가가치 제품 중심의 포트폴리오 강화
   - 프로세스 최적화 및 비용 개선 추진 중

**평가:** DX 부문의 적자는 전체 영업이익에 미미한 영향 (DS 89.2조원의 99.7%)

---

### SDC (삼성디스플레이)

#### 실적 요약

| 항목 | 수치 | 비고 |
|------|------|------|
| **매출** | **7.5조원** | 전사 매출의 4.4% |
| **영업이익** | **0.7조원** | 전분기 대비 개선 |
| **영업이익률** | **9.0%** | 수익성 회복 중 |

#### 주요 내용

1. **중소형 디스플레이**
   - 스마트폰 OLED 초조 현상으로 **전분기 대비 실적 개선**

2. **대형 디스플레이**
   - Gaming 모니터 시장 확대로 매출 증가

**평가:** 시장 수급 개선 신호로 순차적 실적 회복 중

---

### Harman (오토모티브 및 라이프스타일)

#### 실적 요약

| 항목 | 수치 | 비고 |
|------|------|------|
| **매출** | **4.6조원** | 전사 매출의 2.7% |
| **영업이익** | **0.4조원** | 전분기 대비 개선 |
| **영업이익률** | **9.0%** | 수익성 안정 |

#### 주요 내용

1. **오토모티브 (Automotive)**
   - 전장(電裝) 매출 확대
   - 시장 확대 추세 지속

2. **라이프스타일 (Lifestyle)**
   - 포트폴리오 강화 및 소비자 오디오 판매 호조

**평가:** 포트폴리오 다변화로 순차적 실적 개선

---

# 메모리 사업 상세 분석

## 경영실적

### 2026년 2분기 메모리 사업 성과

#### 사상 최대 분기 실적 경신

**핵심 성과:**
- 제한된 생산 캐파 내에서 **AI 서버 응용 중심 수요에 적극 대응**
- 전반적인 시장 가격 상승세 지속

**제품 경쟁력 강화:**
- **역대 최대 서버향 매출 비중 달성** — AI 인프라 투자 수혜의 핵심
- **업계 최고 성능의 HBM4 공급 확대**
- **업계 최초 주요 고객사 HBM4E 샘플 출하** (3분기 달성)

#### 제품군

| 제품 | 주요 특징 | 현황 |
|------|---------|------|
| **PM1763** | Enterprise SSD | 공급 중 |
| **HBM4** | 고대역폭 메모리 | 공급 확대 중 |
| **HBM4E** | 차세대 고성능 HBM | 샘플 출하 시작 (3분기) |

---

### DS(Device Solutions) 메모리 부문 재무 추이

#### 메모리 사업 매출 및 DS 영업이익

| 기간 | DS 총 매출 (조원) | 메모리 매출 (조원) | DS 영업이익 (조원) | 영업이익률 |
|------|------------------|------------------|------------------|----------|
| 2026년 Q1 | 81.7 | 53.7 | - | - |
| 2026년 Q2 | 127.5 | 120.8 | 89.2 | 70.0% |
```


---

## DART 연결재무제표 (삼성전자, 2025년)
<!-- source: OpenDART API | ground_truth: true -->

| 계정 | 금액(억원) | 출처 |
|------|--------:|------|
| 매출액 | 3,336,059.4 | DART |
| 영업이익 | 436,010.5 | DART |
| 당기순이익 | 452,068.0 | DART |
| 자산총계 | 5,669,421.1 | DART |
| 부채총계 | 1,306,217.7 | DART |
| 자본총계 | 4,363,203.4 | DART |
| 영업활동현금흐름 | 853,151.5 | DART |
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
