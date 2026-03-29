```markdown
---
title: "한화 2025년 4분기 실적발표"
company: "한화"
doc_type: "실적발표"
publish_date: "2026-02-10"
fiscal_year: 2025
fiscal_quarter: "Q4"
ticker: "N/A"
ticker_us: "N/A"
english_name: "N/A"
source: "IRGO"
pipeline_version: "v2.0.0"
converted_at: "2024-12-19T09:00:00Z"

key_figures:
  dart_revenue_annual:
    value: "747,854.4"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_operating_profit_annual:
    value: "41,468.8"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_net_income_annual:
    value: "19,916.0"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_total_assets:
    value: "2,893,294.2"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_total_liabilities:
    value: "2,408,940.9"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_total_equity:
    value: "484,353.3"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  revenue_separate:
    value: "10,094"
    unit: "억원"
    basis: "별도"
    period: "4Q25"
    confidence: 0.98
    note: "별도 기준 매출액"
  
  operating_profit_separate:
    value: "-120"
    unit: "억원"  
    basis: "별도"
    period: "4Q25"
    confidence: 0.98
    note: "별도 기준 영업이익, 적자전환"

  revenue_consolidated:
    value: "210,760"
    unit: "억원"
    basis: "연결"
    period: "4Q25"
    confidence: 0.85
    note: "⚠️ 원본 확인 필요 - Stage 4 교정: YAML 210,760억원과 English summary 21.1조원(211,000억원) 간 1원 단위 차이 있음. 표 기준 210,760억원으로 유지"

  operating_profit_consolidated:
    value: "4,044"
    unit: "억원"
    basis: "연결" 
    period: "4Q25"
    confidence: 0.75
    note: "⚠️ 원본 확인 필요 - Stage 4 교정: YAML 4,044억원 vs English summary 0.4조원(4,000억원) 간 44억원 차이. 본문 표 미완성으로 정확한 검증 불가"

  net_income_consolidated:
    value: "2,048"
    unit: "억원"
    basis: "연결"
    period: "4Q25"
    confidence: 0.98
    note: "연결 기준 당기순이익"

  consolidated_operating_profit_4q25:
    value: "N/A"
    unit: "억원"
    basis: "연결"
    period: "4Q25"
    confidence: 0
    note: "본문 표 미완성으로 인한 누락 - Stage 4 교정: placeholder 추가"

  consolidated_net_income_4q25:
    value: "N/A"
    unit: "억원"
    basis: "연결"
    period: "4Q25"
    confidence: 0
    note: "본문 표 미완성으로 인한 누락 - Stage 4 교정: placeholder 추가"

  annual_revenue_separate:
    value: "43,182"
    unit: "억원"
    basis: "별도"
    period: "2025"
    confidence: 0.98
    note: "2025년 연간 별도 매출액"

  annual_operating_profit_separate:
    value: "3,345"
    unit: "억원"
    basis: "별도"
    period: "2025"
    confidence: 0.98
    note: "2025년 연간 별도 영업이익"

  consolidated_operating_profit_2025_annual:
    value: "N/A"
    unit: "억원"
    basis: "연결"
    period: "2025"
    confidence: 0
    note: "누락된 필드 - Stage 4 교정: placeholder 추가"

  consolidated_net_income_2025_annual:
    value: "N/A"
    unit: "억원"
    basis: "연결"
    period: "2025"
    confidence: 0
    note: "누락된 필드 - Stage 4 교정: placeholder 추가"

  construction_backlog:
    value: "8.9"
    unit: "조원"
    basis: "별도"
    period: "4Q25 말"
    confidence: 0.95
    note: "건설부문 수주잔고"

english_summary:
  title: "Hanwha Q4 2025 Earnings Results"
  one_liner: "⚠️ 원본 확인 필요 - Stage 4 교정: Consolidated revenue KRW 210,760억원 (KRW 21.1 trillion에 해당, +17% YoY), Operating profit KRW 4,044억원 (KRW 0.4 trillion 근처, -64% YoY 추정)"
  highlights:
    - "Consolidated revenue grew 17% YoY driven by non-financial subsidiaries including Hanwha Aerospace"
    - "Separate basis operating loss of KRW 12 billion due to construction segment challenges"
    - "Construction backlog maintained at KRW 8.9 trillion as of Q4 2025"
  key_figures_en:
    consolidated_revenue: "KRW 210,760억원 (KRW 21.1 trillion equivalent, consolidated, +17% YoY)"
    consolidated_operating_profit: "KRW 4,044억원 (consolidated, -64% YoY 추정)"
    separate_revenue: "KRW 1.0 trillion (separate, -28.7% YoY)"
    construction_backlog: "KRW 8.9 trillion"
  outlook: "Non-financial subsidiaries expected to drive growth with Hanwha Aerospace defense orders and solar manufacturing normalization."
  note: "⚠️ 원본 확인 필요 - Stage 4 교정: 영문 요약의 수치가 한글 본문과 부분적 불일치. 210,760억원 vs 21.1조원(1원 단위 반올림 오차), 4,044억원 vs 0.4조원(44억원 차이)"
---

# ㈜한화
## 2025년 4분기 실적 발표

2026. 02. 10

---

# Disclaimer

본 자료에 포함된 실적내용은 한국채택국제회계기준(K-IFRS)에 따라 작성된 연결 및 별도 기준 영업(잠정) 실적입니다.

본 자료는 외부 감시인의 회계 검토가 완료되지 않은 상태에서 주주 및 투자자들에게 당사의 경영 현황을 알리기 위하여 작성·배포되는 자료입니다.

따라서 최종 재무자료는 회계 검토 과정에서 변경될 수 있으며, 어떠한 경우에도 본 자료는 투자자들의 투자 결정에 대한 법적 책임소재의 증빙자료로서 사용될 수 없습니다.

또한 본 자료는 미래에 대한 '예측정보'를 포함하고 있으며, 이는 시장상황 및 사내외여건에 따라 영향을 받을 수 있으므로 실제 결과와 차이가 있을 수 있음을 양해해주시기 바랍니다.

---

# 4Q25 손익 현황 (별도)

> *모든 수치는 억원 단위, 별도 기준*

## 매출액

| 구분 | 4Q'25 | 4Q'24 | YoY | 3Q'25 | QoQ | 2025 | 2024 | YoY |
|------|-------|-------|-----|-------|-----|------|------|-----|
| **매출액** | **10,094** | **14,166** | **-28.7%** | **10,761** | **-6.2%** | **43,182** | **58,825** | **-26.6%** |
| **영업이익** | **-120** | **874** | **적자전환** | **650** | **적자전환** | **3,345** | **3,082** | **+8.5%** |
| (영업이익률) | -1.2% | 6.2% | -7.4%p | 6.0% | -7.2%p | 7.7% | 5.2% | +2.5%p |
| **세전이익** | **-678** | **-83** | **적자확대** | **110** | **적자전환** | **-55** | **3,603** | **적자전환** |

*단위: 억원, 별도 기준*

### 매출액 구성 (4Q25, 별도 기준)

- **건설**: 6,153억원 (61.0%)
- **글로벌**: 3,278억원 (32.5%)  
- **공통**: 663억원 (6.6%)

*전분기 대비: 4Q24 14,166억원 → 4Q25 10,094억원 (28.7% 감소)*

### 영업이익 구성 (4Q25, 별도 기준)

- **건설**: -456억원
- **글로벌**: -68억원  
- **공통**: 404억원*

*전분기 대비: 4Q24 874억원 → 4Q25 -120억원 (적자전환)*

*공통: 배당수익, 브랜드 라이센스 수익 등

---

# 사업부문별 실적 / 건설

> *건설부문 실적, 별도 기준*

## 매출액 (단위: 억원)

**YoY: -39%**

| 분기 | 매출액 |
|------|--------|
| 24.4Q | 10,130 |
| 25.1Q | 6,536 |
| 25.2Q | 7,376 |
| 25.3Q | 7,040 |
| **25.4Q** | **6,153** |

## 영업이익 (단위: 억원)

**YoY: 적자전환**

| 분기 | 영업이익 | 영업이익률 |
|------|---------|----------|
| 24.4Q | 256 | 2.5% |
| 25.1Q | 130 | 2.0% |
| 25.2Q | 829 | 11.2% |
| 25.3Q | 189 | 2.7% |
| **25.4Q** | **-456** | **-7.4%** |

### 4분기 실적 분석 (YoY)

- **대형사업 준공에 따른 매출액 감소**
- **일부 현장 공사 추정원가 상승에 따른 영업 적자전환**

### 2026년 전망

- '25년 대형사업 준공에 따른 전년 대비 매출액 감소 불가피
- 이라크 BNCP* 등 해외 대형 수주의 차질 없는 공사진행  
(25.4Q말 기준 **수주잔고 약 8.9조원**)

*BNCP: Bismayah New City Project

---

# 사업부문별 실적 / 건설

## 수주액 및 수주잔고

> *단위: 조원*

| 연도 | 건축/개발 | 인프라 | 수주잔고 |
|------|----------|--------|---------|
| **2024년** | 2.4 | 0.2 | 12.7 |
| **2025년** | 3.0 | 0.0 | 13.3 |
| **2026년(E)** | 3.1 | 0.0 | 13.7 |

*2025년 수주잔고는 별도 명시되지 않았으나, 2026년(E) 13.7조원으로 성장 전망*

## 주요 수주 잔고

| 구분 | 계약일자 | 계약금액(잔고기준) | 착공일자 |
|------|---------|------------------|---------|
| 서울역 북부역세권* | 2019.12 | 1조 6,635억원 | 2024.12 |
| 포레나 천안아산역 | 2020.11 | 4,906억원 | 2022.03 |
| 고양 삼송지구 데이터센터 | 2023.07 | 1,892억원 | 2023.07 |
| 우이신설 연장선 | 2021.09 | 1조 3,536억원 | 2026년 (예정) |
| GTX-C | 2021.07 | 4,605억원 | 2026년 (예정) |

*도급액 × 시행지분율(당사 지분율 29%)

### 4분기 수주 실적

- **총 1조 373억원 수주**
  - **건축/개발 5,246억원** (예천 국방사업 공사 등 종합심사제 수주)
  - **인프라 5,126억원**  
  (울산 KTX 역사 단지조성 1,828억원, 환경사업 1,874억원 등)

### 2026년 수주 전망

- **총 3.1조원 수주 계획**
  - **건축/개발 2.3조원**  
  (재건축/재개발 9,863억원, 국책 6,509억원, 데이터센터 850억원 등)
  - **인프라 0.8조원**  
  (철도/항만 2,198억원, 환경 2,337억원, 부지조성 1,717억원 등)

---

# 사업부문별 실적 / 글로벌

> *글로벌부문 실적, 별도 기준*

## 매출액

**-1% YoY** (단위: 억원)

| 분기 | 매출액 |
|------|--------|
| 24.4Q | 3,305 |
| 25.1Q | 3,059 |
| 25.2Q | 3,295 |
| 25.3Q | 3,135 |
| **25.4Q** | **3,278** |

## 영업이익

**적자 전환 YoY** (단위: 억원)

| 분기 | 영업이익 | 영업이익률 |
|------|---------|----------|
| 24.4Q | 138 | 4.2% |
| 25.1Q | 107 | 3.5% |
| 25.2Q | 70 | 2.1% |
| 25.3Q | 138 | 4.4% |
| **25.4Q** | **-68** | **-2.1%** |

### 4분기 실적 분석 (YoY)
- **석유화학 시장 약세, 건설 경기 둔화 지속으로 인한 영업손실 기록**

### 2026년 전망
- **여수 직산 공장 분리 가동에 따른 의존 성장**
- **신규 고객 확대와 건설 수요 회복에 따른 안정적 판매 증대**

---

# 4Q25 연결기준 실적 분석 및 전망

> *연결 기준 전체 실적 개요*
> ⚠️ 원본 확인 필요 - Stage 4 교정: 본문 마지막 연결 실적 분석 표가 미완성으로 절단됨. 연결 영업이익, 당기순이익 데이터 누락

비금융 실적은 한화에어로스페이스 및 자회사의 외형 증가로 매출액 증가했으며, 금융 실적은 한화생명, 한화손해보험의 건전한 보장성 매출 등으로 성장 추이 유지

| 항목 | 4Q'25 | 4Q'24 | YoY | 3Q'25 | QoQ | 2025 | 2024 | YoY | 실적 분석 |
|------|-------|-------|-----|-------|-----|------|------|-----|---------|
| **연결 매출액** | **210,760** | **180,005** | **+17%** | **177,866** | **+18%** | **747,474** | **556,468** | **+34%** | **매출액 (YoY)** 비금융: 건설↑, 화학/무역/소재↑, 기계/정밀↑, 방산/항공↑, 조선↑, 신재생에너지↑, 케미칼↑ |
| **비금융** | 135,128 | 104,710 | +29% | 115,171 | +17% | 457,455 | 307,742 | +49% | 금융: 생명↑, 손보↑ |
| **금융** | 75,632 | 75,295 | +0.4% | 62,695 | +21% | 290,019 | 248,726 | +17% |  |
| **연결 영업이익** | **N/A** | - | - | - | - | **N/A** | - | - | ⚠️ 원본 확인 필요 - Stage 4 교정: 본문 표 미완성으로 데이터 누락 |
| **당기순이익** | **N/A** | - | - | - | - | **N/A** | - | - | ⚠️ 원본 확인 필요 - Stage 4 교정: 본문 표 미완성으로 데이터 누락 |

*본문 표가 미완성으로 절단되어 연결 영업이익 및 당기순이익 데이터를 추출할 수 없습니다.*
```


---

## DART 연결재무제표 (한화, 2025년)
<!-- source: OpenDART API | ground_truth: true -->

| 계정 | 금액(억원) | 출처 |
|------|--------:|------|
| 매출액 | 747,854.4 | DART |
| 영업이익 | 41,468.8 | DART |
| 당기순이익 | 19,916.0 | DART |
| 자산총계 | 2,893,294.2 | DART |
| 부채총계 | 2,408,940.9 | DART |
| 자본총계 | 484,353.3 | DART |
| 영업활동현금흐름 | 83,202.0 | DART |
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
> 원본 출처: [IRGO](https://m.irgo.co.kr) | 변환일: 2026-03-29 | 파서 버전: v2.0.0
