```yaml
---
title: "삼성전자 2026년 2분기 실적발표"
company: "삼성전자"
doc_type: "실적발표"
publish_date: "2026-08" # 정확한 발표일자는 PDF에 명시되지 않음
fiscal_year: 2026
fiscal_quarter: "Q2"
ticker: "005930"
ticker_us: "SSNLF"
english_name: "Samsung Electronics"
source: "IRGO"
pipeline_version: "v2.0.0"
converted_at: "2025-01-16T00:00:00Z"

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
  # 전사 연결기준 주요 수치
  revenue_total:
    value: "171.5"
    unit: "조원"
    basis: "연결"
    period: "2Q 2026"
    confidence: 0.98
    note: "QoQ +28%, YoY +130%"
  
  operating_profit_total:
    value: "89.5"
    unit: "조원"
    basis: "연결"
    period: "2Q 2026"
    confidence: 0.98
    note: "QoQ +56%, YoY +1,814%"
  
  operating_margin_total:
    value: 52.2
    unit: "%"
    basis: "연결"
    period: "2Q 2026"
    confidence: 0.98
    note: "QoQ +9.4p"
  
  eps_common:
    value: 10849
    unit: "원"
    basis: "연결"
    period: "2Q 2026"
    confidence: 0.98
    note: "보통주 주당순이익, QoQ +3,726원, YoY +10,112원"
  
  eps_preferred:
    value: 10849
    unit: "원"
    basis: "연결"
    period: "2Q 2026"
    confidence: 0.98
    note: "우선주 주당순이익"
  
  rd_investment:
    value: "16.0"
    unit: "조원"
    basis: "연결"
    period: "2Q 2026"
    confidence: 0.98
    note: "QoQ +41%, YoY +78%"

  # 사업부문별 매출 (Level 1 - 대분류)
  revenue_by_segment_ds:
    value: "127.5"
    unit: "조원"
    basis: "연결"
    period: "2Q 2026"
    level: 1
    parent: null
    confidence: 0.92
    note: "⚠️ Stage 4 교정: Device Solutions (반도체), 전체 매출의 74.3%. [원본 확인 필요] DS(127.5) + DX(48.0) = 175.5조원인데 전체 171.5조원과 4조원(2.3%) 오차 발생. 미배분 부분(SDC 7.5 + Harman 4.6 = 12.1조원) 소속 관계 명확히 필요"
  
  revenue_by_segment_dx:
    value: "48.0"
    unit: "조원"
    basis: "연결"
    period: "2Q 2026"
    level: 1
    parent: null
    confidence: 0.98
    note: "Device eXperience (모바일/TV/가전), 전체 매출의 27.9%"

  # 사업부문별 영업이익 (Level 1 - 대분류)
  operating_profit_by_segment_ds:
    value: "89.2"
    unit: "조원"
    basis: "연결"
    period: "2Q 2026"
    level: 1
    parent: null
    confidence: 0.92
    note: "⚠️ Stage 4 교정: Device Solutions 영업이익, 영업이익률 70%. [원본 확인 필요] DS(89.2) + DX(-0.8) = 88.4조원인데 전체 89.5조원과 1.1조원 오차 발생. 미배분 부분(SDC 0.7 + Harman 0.4 = 1.1조원) 소속 관계 명확히 필요"
  
  operating_profit_by_segment_dx:
    value: "-0.8"
    unit: "조원"
    basis: "연결"
    period: "2Q 2026"
    level: 1
    parent: null
    confidence: 0.98
    note: "Device eXperience 영업손실, 영업이익률 -2%"

  # 세부 사업부문 - 메모리 (Level 2)
  revenue_memory:
    value: "81.7"
    unit: "조원"
    basis: "연결"
    period: "2Q 2026"
    level: 2
    parent: "Device Solutions (DS)"
    confidence: 0.7
    note: "⚠️ Stage 4 교정 필수: 메모리 부문 매출 (2Q 2025: 0.4조원, 1Q 2026: 74.8조원). [원본 표 검토 필요] 메모리 81.7조원이 DS 127.5조원의 64%를 차지. System LSI(27.9조원) 및 기타와의 합산 검증 필요. 수치 일관성 재확인 권장"

  operating_profit_memory:
    value: "120.8"
    unit: "조원"
    basis: "연결"
    period: "2Q 2026"
    level: 2
    parent: "Device Solutions (DS)"
    confidence: 0.6
    note: "⚠️ Stage 4 교정 필수: [원본 표 검토 필요] 메모리 영업이익 120.8조원이 DS 영업이익 89.2조원보다 큼. 논리적 모순 발생. 원본 데이터의 정확성 재검증 절실히 필요. 표에서 2Q 2026 영업이익이 명확하지 않음"

  # 세부 사업부문 - 모바일/PC (S.LSI) (Level 2)
  revenue_slsi:
    value: "27.9"
    unit: "조원"
    basis: "연결"
    period: "2Q 2026"
    level: 2
    parent: "Device Solutions (DS)"
    confidence: 0.5
    note: "⚠️ Stage 4 교정 필수: [원본 표 검토 필요] System LSI 매출이 '2Q 2025 수치로 표시'되어 있음. 실제 2Q 2026 수치 누락. 표에서 2Q 2026 정확한 수치 재확인 필요"

  operating_profit_slsi:
    value: "N/A"
    unit: "조원"
    basis: "연결"
    period: "2Q 2026"
    level: 2
    parent: "Device Solutions (DS)"
    confidence: 0
    note: "Stage 4 교정: missing_fields - System LSI 영업이익 데이터 누락"

  # 세부 사업부문 - 디스플레이 (SDC) (Level 2)
  revenue_sdc:
    value: "7.5"
    unit: "조원"
    basis: "연결"
    period: "2Q 2026"
    level: 2
    parent: null
    confidence: 0.75
    note: "⚠️ Stage 4 교정: 삼성디스플레이 (SDC), QoQ +12%. [원본 확인 필요] SDC(7.5) + Harman(4.6) = 12.1조원이 DS나 DX 중 어디에 속하는지 불명확. parent 필드 확인 필요"

  operating_profit_sdc:
    value: "0.7"
    unit: "조원"
    basis: "연결"
    period: "2Q 2026"
    level: 2
    parent: null
    confidence: 0.98
    note: "삼성디스플레이 영업이익, 영업이익률 9%"

  # Harman (오토모티브/라이프스타일) (Level 2)
  revenue_harman:
    value: "4.6"
    unit: "조원"
    basis: "연결"
    period: "2Q 2026"
    level: 2
    parent: null
    confidence: 0.75
    note: "⚠️ Stage 4 교정: Harman (오토모티브/라이프스타일), QoQ +19%. [원본 확인 필요] SDC(7.5) + Harman(4.6) = 12.1조원이 DS나 DX 중 어디에 속하는지 불명확. parent 필드 확인 필요"

  operating_profit_harman:
    value: "0.4"
    unit: "조원"
    basis: "연결"
    period: "2Q 2026"
    level: 2
    parent: null
    confidence: 0.98
    note: "Harman 영업이익, 영업이익률 9%"

  # 기타 집계 수치
  ds_revenue_1q26:
    value: "74.8"
    unit: "조원"
    basis: "연결"
    period: "1Q 2026"
    confidence: 0.98
    note: "Device Solutions 메모리 부문 1Q 2026 매출"

  dx_revenue_qoq_change:
    value: -9
    unit: "%"
    basis: "연결"
    period: "2Q 2026"
    confidence: 0.98
    note: "Device eXperience QoQ 매출 감소율"

english_summary:
  title: "Samsung Electronics Q2 2026 Earnings Results"
  one_liner: "Record operating profit of KRW 89.5 trillion (+56% QoQ, +1,814% YoY) on consolidated revenue of KRW 171.5 trillion (+28% QoQ, +130% YoY), driven by strong memory demand from AI server infrastructure."
  highlights:
    - "Memory achieved record quarterly results with maximum server revenue contribution and expanded HBM4/HBM4E supply to lead customers"
    - "Device Solutions (DS) delivered operating profit of KRW 89.2 trillion (70% margin) leveraging strong server and AI demand"
    - "Record EPS of KRW 10,849 per share reflects global tech leadership and successful technology differentiation amid geopolitical uncertainties"
    - "R&D investment reached KRW 16.0 trillion (+78% YoY) to maintain technological leadership in memory, System LSI, Foundry, and display sectors"
  key_figures_en:
    revenue: "KRW 171.5 trillion (consolidated, +130% YoY)"
    operating_profit: "KRW 89.5 trillion (+1,814% YoY), 52.2% margin"
    eps: "KRW 10,849 per share (+10,112 won YoY)"
    device_solutions_revenue: "KRW 127.5 trillion (74.3% of total)"
    device_experience_revenue: "KRW 48.0 trillion (27.9% of total)"
    rd_investment: "KRW 16.0 trillion (+78% YoY)"
  outlook: "H2 2026 outlook expects sustained AI infrastructure investment demand with continued memory tight supply, while S.LSI and Foundry segments target double-digit growth through 2-nano process ramp and expanded HPC/AI orders."
---
```

# 삼성전자 2026년 2분기 실적발표

## 유의사항

본 자료의 재무정보는 한국채택국제회계기준에 따라 작성된 **연결 기준의 영업실적**입니다.

본 자료에 포함된 '2026년 2분기 실적'은 본사, 자회사 및 관계사 등에 대한 외부감사인의 회계감사가 완료되지 않은 상태에서 투자자 여러분의 편의를 위해 작성된 자료이므로, 그 내용 중 일부는 회계감사 과정에서 달라질 수 있음을 양지하시기 바랍니다.

또한 본 자료는 미래에 대한 '예측정보'를 포함하고 있습니다. 이는 과거가 아닌 미래의 사건과 관계된 것으로 회사의 향후 예상되는 경영현황 및 재무실적을 의미하며, 표현상으로는 '예상', '전망', '계획', '기대' 등과 같은 단어를 포함합니다.

'예측정보'는 그 성격상 불확실한 사건들을 언급하는데, 회사의 향후 경영현황 및 재무실적에 긍정적 또는 부정적으로 영향을 미칠 수 있는 불확실성에는 다음과 같은 것들이 포함됩니다.

- 환율, 이자율 등의 변동을 포함한 국내외 금융시장의 동향
- 사업의 처분, 인수 등을 포함한 회사의 전략적인 의사결정
- DX (Device eXperience), DS (Device Solutions) 등 회사가 우위하는 주요 사업분야의 예상치 못한 금결된 여건 변화
- 기타 경영현황 및 재무실적에 영향을 미칠 수 있는 국내·외적 변화

이러한 불확실성으로 인해 회사의 실제 미래 실적은 '예측정보'에 명시적 또는 묵시적으로 포함된 내용과 중대하게 차이가 있을 수 있음을 양지하시기 바랍니다.

---

## 목차

| 구성 | 내용 |
|------|------|
| 발표자 소개 | 경영진 소개 |
| '26년 2분기 경영실적 | 전사 연결 손익 현황 |
| 사업 부문별 실적 및 전망 | Device Solutions (DS), Device eXperience (DX) 상세 분석 |
| 별첨 | 추가 자료 |

---

## 실적발표

### 발표자

| 직책 | 이름 | 담당 부문 |
|------|------|---------|
| Chief Financial Officer (부사장) | 박순철 | 경영 총괄 |
| 부사장 | 김재준 | 메모리 |
| 부사장 | 신승철 | System LSI |
| 부사장 | 강석재 | Foundry |
| 부사장 | 허 철 | 삼성디스플레이 |
| 상무 | 다니엘라우조 | Mobile eXperience |
| 부사장 | 이현 | VD (영업 스플레이) |
| 부사장 | 다니엘 오 | Investor Relations |

---

## '26년 2분기 경영실적 요약

### 연결기준 전사 손익

#### 매출

**171.5조원** (연결 기준)
- **QoQ**: +28% (1Q 2026 대비)
- **YoY**: +130% (2Q 2025 대비)

#### 영업이익

**89.5조원** (연결 기준)
- **QoQ**: +56%
- **YoY**: +1,814%
- **영업이익률**: 52.2% (QoQ +9.4p)

#### 주당순이익 (EPS)

| 구분 | 수익 |
|------|------|
| 보통주 주당순이익 | **10,849원** |
| 우선주 주당순이익 | **10,849원** |
| 주요 변동 | QoQ +3,726원, YoY +10,112원 |

#### R&D 투자

**16.0조원** (연결 기준)
- **QoQ**: +41%
- **YoY**: +78%

### 실적 평가

기술 리더십 기반으로 시장 변화에 빠르게 대응하며 **역대 최대 실적 자경신** 달성

**주요 배경**:
- 글로벌 경기 변동성과 다양한 지정학적 불확실성이 지속되었음에도 불구하고
- 핵심사업 영역에서 축적해 온 **차별화된 기술 경쟁력이 실적으로 입증**된 결과

**향후 전략**:
- 끝임없는 기술 혁신을 통해 미래 성장 동력 확보
- 글로벌 리더십 지속 강화

---

# 사업 부문별 실적

## 2026년 2분기 사업 부문별 매출 및 이익

### 매출 현황 (단위: 조원)

| 사업부문 | 매출 (2Q 2026) | 매출 비중 | QoQ 변동 |
|---------|----------------|---------|---------|
| **전체** | **171.5** | **100%** | **+28%** |
| **DS (Device Solutions 반도체)** | **127.5** | **74.3%** | **+56%** |
| **DX (Device eXperience 모바일/TV/가전)** | **48.0** | **27.9%** | **-9%** |
| **SDC (삼성디스플레이)** | **7.5** | **4.4%** | **+12%** |
| **Harman (오토모티브/라이프스타일)** | **4.6** | **2.7%** | **+19%** |

> **Stage 4 교정 주석**: DS(127.5) + DX(48.0) + SDC(7.5) + Harman(4.6) = 187.6조원으로 전체 171.5조원과 16.1조원 오차. ⚠️ **[원본 표 검토 필요]** SDC와 Harman의 연결 관계(DS/DX 포함 또는 별도) 명확히 필요. 세부 보고서에서 계층 구조 확인 권장.

### 영업이익 현황 (단위: 조원)

| 사업부문 | 영업이익 (2Q 2026) | 영업이익률 |
|---------|-------------|---------|
| **전체** | **89.5** | **52.2%** |
| **DS (Device Solutions 반도체)** | **89.2** | **70%** |
| **DX (Device eXperience 모바일/TV/가전)** | **-0.8** | **-2%** |
| **SDC (삼성디스플레이)** | **0.7** | **9%** |
| **Harman (오토모티브/라이프스타일)** | **0.4** | **9%** |

> **Stage 4 교정 주석**: DS(89.2) + DX(-0.8) + SDC(0.7) + Harman(0.4) = 89.5조원 ✓ (일치). 다만 SDC와 Harman의 세부 구성 및 미배분 비용 존재 여부 재확인 필요.

---

## 세부 사업부문별 실적 현황

### 전체 부문 비교표 (단위: 조원)

| 사업부문 | DS (반도체)<br/>(메모리/System LSI/<br/>Foundry) | DX (모바일/<br/>TV/가전) | SDC<br/>(디스플레이) | Harman<br/>(오토모티브/<br/>라이프스타일) |
|---------|-------|-------|-------|-------|
| **2Q 2026 매출** | 127.5 | 48.0 | 7.5 | 4.6 |
| **QoQ 변동** | +56% | -9% | +12% | +19% |
| **2Q 2026 영업이익** | 89.2 | -0.8 | 0.7 | 0.4 |
| **영업이익률** | 70% | -2% | 9% | 9% |

> **Stage 4 교정 주석**: 기존 마크다운 표 재정렬 완료. 영업이익 합계는 일치하나 매출액 합계(187.6조원) > 전체(171.5조원) 불일치. ⚠️ **[원본 표 검토 필수]** 계층 구조(SDC, Harman이 DS 또는 DX 포함인지, 아니면 별도인지) 명확히 필요.

---

## 주요 부문별 성과 및 과제

### Device Solutions (DS, 반도체)

**성과**:
- **메모리**: DRAM, NAND 공히 최대 Bit 판매 달성
- **System LSI**: 모바일 시장 부진에도 불구하고 상반기 최대 매출 달성
- **Foundry**: 가동률 상승과 선단 공정 수요 증가

**특징**: AI 서버 수요의 적극 대응으로 역대 최대 분기 실적 기록

---

### Device eXperience (DX, 모바일/TV/가전)

**매출 성장 요인**:
- **프리미엄 AI칩품 판매 확대**로 전년 대비 매출 성장

**수익성 악화 요인**:
- 부품 원가 약세에 따른 수익성 악화로 **적자 전환** (-0.8조원)

**대응 방안**:
- 고부가가치 제품 중심의 포트폴리오 강화
- 프로세스 최적화
- 비용층 개선을 통해 이익 감소 최소화 노력

---

### 삼성디스플레이 (SDC, Level 2 사업)

**성과**:
- **중소형, 스마트폰 OLED 초조**로 전분기 대비 실적 개선
- **대형, Gaming 모니터 시장 확대**로 매출 증가

**재무 현황** (2Q 2026):
- 매출: 7.5조원 (QoQ +12%)
- 영업이익: 0.7조원
- 영업이익률: 9%

---

### Harman (오토모티브/라이프스타일)

**성과**:
- **전장 매출 확대** 및 포트폴리오 강화를 통한 소비자 오디오 판매 증대
- 효조로 실적 개선

**재무 현황** (2Q 2026):
- 매출: 4.6조원 (QoQ +19%)
- 영업이익: 0.4조원
- 영업이익률: 9%

---

# 메모리 부문

## 2026년 2분기 경영실적

### 주요 성과

#### 사상 최대 분기 실적 경성

- **지속된 생산 캐파 내 서버 응용 증심 AI 수요 적극 대응**
  - 제한된 생산 능력 범위 내에서 고수익 서버 칩셋에 집중
  
- **전반적인 시장 가격 상승세 지속**
  - DRAM, NAND 공급 부족으로 인한 가격 상승 혜택

#### 업계 선도적 제품을 통해 시장 경쟁력 강화

- **역대 최대 서버향 매출 비중 달성**
  - AI 인프라 투자 집중화에 따른 서버 칩 수요 급증
  
- **업계 최고 성능의 HBM4 공급 확대**
  - 차세대 고성능 메모리 시장 리더십 강화
  
- **업계 최초로 주요 고객사 HBM4E 샘플 중합**
  - 초고성능 메모리 기술에서 업계 최선단 입지 확보

---

## 메모리 부문 재무 현황

### DS(Device Solutions) 및 메모리 매출/영업이익 추이

⚠️ **Stage 4 교정 필수**: 다음 테이블의 수치는 원본 검수 결과 다수의 불일치 사항이 있습니다. 아래 데이터는 원본에서 직접 추출한 수치이나, **[원본 표 검토 필수]** 주석 참고 바랍니다.

(단위: 조원)

| 항목 | 2Q 2025 | 1Q 2026 | 2Q 2026 | 주석 |
|------|---------|---------|---------|------|
| **DS 전체 매출** | 0.4 | 74.8 | 127.5 | ⚠️ 원본 확인 필요: 세부 구성(메모리/System LSI/Foundry) 확인 필요 |
| **메모리 부문 매출** | - | 74.8 | 81.7 | ⚠️ 원본 확인 필요: 메모리가 DS의 64%인데, System LSI(27.9조원) 및 기타와의 합산 정합성 미확인 |
| **DS 전체 영업이익** | - | 53.7 | 89.2 | ⚠️ 원본 확인 필요: 메모리 영업이익과의 관계 명확화 필요 |
| **메모리 부문 영업이익** | - | 89.2 | 120.8 | **⚠️ 원본 확인 필요 [심각]**: 메모리 영업이익(120.8조원) > DS 영업이익(89.2조원) 논리적 모순. 수치 재검증 절실함 |

> **Stage 4 교정 주석**: 
> - 메모리 매출이 DS 매출의 64%이며, System LSI 27.9조원 등과 합산했을 때 127.5조원이 되는지 원본 재확인 필요
> - **메모리 영업이익(120.8조원)이 DS 영업이익(89.2조원)보다 큰 것은 논리적 모순**. 표 작성 오류 또는 데이터 입력 오류로 의심됨. 반드시 원본 문서 재검증 필요
> - 미배분 부분(SDC 0.7조원 + Harman 0.4조원 = 1.1조원)의 소속 관계 확인 필요

---

## 메모리 부문 2026년 하반기 전망

### 수요 전망

#### AI 인프라 투자 지속에 따른 서버 증심의 수요 강세 기대

- **Agentic AI 확산으로 서버 전반의 수요 강세**
  - 차세대 AI 에이전트 기술의 산업 확대로 서버급 고성능 메모리 수요 지속
  
- **일부 모바일/PC향 수요가 메산 되나, 서버향 DRAM, Enterprise SSD 및 HBM 주요 성장 가속화**
  - 소비자용 기기 수요 약화는 제한적 영향
  - 데이터센터/서버향 메모리가 주요 성장축으로 작용
  
- **금금 부족 현상은 지속될 전망**
  - 서버 메모리 공급 부족이 계속되어 가격 경쟁력 유지

### 경쟁 전략

#### 기술 리더십


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
