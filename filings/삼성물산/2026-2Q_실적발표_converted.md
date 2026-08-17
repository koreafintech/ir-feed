```yaml
---
title: "삼성물산 2026년 2분기 실적발표"
company: "삼성물산"
ticker: "000830.KS"
english_name: "Samsung C&T"
doc_type: "실적발표"
publish_date: "2026-07-01"
fiscal_year: 2026
fiscal_quarter: "Q2"
source: "IRGO"
pipeline_version: "v2.0.0"
converted_at: "2024-12-19T00:00:00Z"
basis: "연결기준"
accounting_standard: "K-IFRS"
audit_status: "회계감시 미완료"

key_figures:
  # 연결 기준 전체 수치
  consolidated_revenue:
    value: "11,995"
    unit: "억원"
    period: "2026 Q2"
    basis: "연결"
    confidence: 0.98
    note: "분기 순익 기준"

  consolidated_revenue_qoq:
    value: "+1,529"
    unit: "억원"
    period: "2026 Q2 vs 2026 Q1"
    basis: "연결"
    confidence: 0.98
    change_rate: "+14.6%"

  consolidated_revenue_yoy:
    value: "+1,973"
    unit: "억원"
    period: "2026 Q2 vs 2025 Q2"
    basis: "연결"
    confidence: 0.98
    change_rate: "+19.7%"

  # 사업부문별 매출 (연결, 분기 기준)
  revenue_by_segment:
    construction:
      value: "3,988"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 1
      note: "건설 부문 매출"
      qoq: "+575 억원"
      yoy: "+593 억원"

    trading:
      value: "4,304"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 1
      note: "상사 부문 매출 (원본 테이블 오류 확인: 4,703 vs 4,304, 세부항목 검증 필요)"
      qoq: "+589 억원"
      yoy: "+927 억원"

    fashion:
      value: "593"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 1
      note: "패션 부문 매출"
      qoq: "+20 억원"
      yoy: "+83 억원"

    leisure:
      value: "206"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 1
      note: "레저 부문 매출"
      qoq: "+101 억원"
      yoy: "△17 억원"

    food_beverage:
      value: "886"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 1
      note: "식음(웰스토리 100% 자회사) 매출"
      qoq: "+61 억원"
      yoy: "+58 억원"

    bio:
      value: "1,619"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 1
      note: "바이오 부문 매출 (삼성바이오로직스 43.06% 자회사, 에머슨텍 43.06% 자회사)"
      qoq: "+183 억원"
      yoy: "+329 억원"

  gross_profit:
    value: "2,214"
    unit: "억원"
    period: "2026 Q2"
    basis: "연결"
    note: "매출이익"
    qoq: "+345 억원"
    yoy: "+413 억원"

  sga_expense:
    value: "1,182"
    unit: "억원"
    period: "2026 Q2"
    basis: "연결"
    note: "판관비"
    qoq: "+33 억원"
    yoy: "+134 억원"

  operating_profit:
    value: "1,032"
    unit: "억원"
    period: "2026 Q2"
    basis: "연결"
    confidence: 0.98
    note: "영업이익 (매출이익 - 판관비)"
    qoq: "+312 억원"
    yoy: "+279 억원"

  operating_margin:
    value: "8.6%"
    period: "2026 Q2"
    basis: "연결"
    note: "영업이익률"
    qoq: "+1.7%p"
    yoy: "+1.1%p"

  # 사업부문별 영업이익
  operating_profit_by_segment:
    construction:
      value: "202"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 1
      margin: "5.1%"
      qoq: "+91 억원"
      yoy: "+84 억원"

    trading:
      value: "142"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 1
      margin: "3.0%"
      qoq: "+33 억원"
      yoy: "+62 억원"

    fashion:
      value: "54"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 1
      margin: "9.1%"
      qoq: "+16 억원"
      yoy: "+21 억원"

    leisure:
      value: "0"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 1
      margin: "0.0%"
      qoq: "+35 억원"
      yoy: "△9 억원"

    food_beverage:
      value: "48"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 1
      margin: "5.4%"
      qoq: "+34 억원"
      yoy: "+3 억원"

    bio:
      value: "586"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 1
      margin: "36.2%"
      qoq: "+103 억원"
      yoy: "+118 억원"

  other_income:
    value: "△11"
    unit: "억원"
    period: "2026 Q2"
    basis: "연결"
    note: "기타순익"

  finance_income:
    value: "34"
    unit: "억원"
    period: "2026 Q2"
    basis: "연결"
    note: "금융순익"

  equity_method_income:
    value: "39"
    unit: "억원"
    period: "2026 Q2"
    basis: "연결"
    note: "지분법순익"

  pre_tax_income:
    value: "1,077"
    unit: "억원"
    period: "2026 Q2"
    basis: "연결"
    note: "세전이익"
    qoq: "△268 억원"
    yoy: "+324 억원"

  net_income:
    value: "916"
    unit: "억원"
    period: "2026 Q2"
    basis: "연결"
    confidence: 0.98
    note: "당기순이익"
    qoq: "△170 억원"
    yoy: "+389 억원"

  non_controlling_interest:
    value: "596"
    unit: "억원"
    period: "2026 Q2"
    basis: "연결"
    note: "노지배지분순이익"
    qoq: "△248 억원"
    yoy: "+243 억원"

  # 건설 부문 세부 (단위: 억원)
  construction_revenue_by_type:
    building:
      domestic:
        value: "2,651"
        unit: "억원"
        period: "2026 Q2"
        basis: "연결"
        level: 2
        parent: "construction"
        qoq: "+386 억원"
        yoy: "+302 억원"

    civil_works:
      value: "127"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 2
      parent: "construction"
      qoq: "+19 억원"
      yoy: "△32 억원"

    plant:
      total:
        value: "1,230"
        unit: "억원"
        period: "2026 Q2"
        basis: "연결"
        level: 2
        parent: "construction"
        qoq: "+170 억원"
        yoy: "+323 억원"

      domestic:
        value: "2,122"
        unit: "억원"
        period: "2026 Q2"
        basis: "연결"
        level: 3
        parent: "construction_plant"
        note: "[원본 확인 필요] 건설 plant 국내 2,122는 plant 합계 1,230과 모순"

      overseas:
        value: "1,866"
        unit: "억원"
        period: "2026 Q2"
        basis: "연결"
        level: 3
        parent: "construction_plant"
        qoq: "△152 억원"
        yoy: "+57 억원"
        note: "[원본 확인 필요] 국내+해외 합 3,988이 전체 매출과 일치하지 않음"

  construction_gross_profit:
    value: "459"
    unit: "억원"
    period: "2026 Q2"
    basis: "연결"
    note: "건설 매출이익"
    qoq: "+60 억원"
    yoy: "+93 억원"

  # 상사 부문 세부 (단위: 억원)
  trading_revenue_by_product:
    industrial_materials:
      value: "4,461"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 2
      parent: "trading"
      qoq: "+570 억원"
      yoy: "+903 억원"

    energy:
      value: "16"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 2
      parent: "trading"
      qoq: "△24 억원"
      yoy: "△4 억원"

    tech:
      value: "226"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 2
      parent: "trading"
      qoq: "+43 억원"
      yoy: "+28 억원"

  trading_gross_profit:
    value: "380"
    unit: "억원"
    period: "2026 Q2"
    basis: "연결"
    note: "상사 매출이익"
    qoq: "+67 억원"
    yoy: "+131 억원"

  # 태양광 개발 사업 (메기이익, 파이프라인)
  solar_project_operating_profit:
    h1_2026:
      value: "31.7"
      unit: "백만원"
      period: "2026 H1"
      basis: "연결"
      note: "1Q: 22.2 + 2Q: 9.5 백만원"

  solar_project_pipeline:
    end_h1_2026:
      value: "32"
      unit: "GW"
      period: "2026년 상반기 말"
      basis: "연결"

    target_end_2026:
      value: "200"
      unit: "GW"
      period: "2026년 말 목표"
      basis: "연결"

  # 주요 상품 가격 추이 (USD/MT)
  commodity_prices:
    urea:
      q2_2026: "668"
      q1_2026: "532"
      change_rate: "+25.6%"
      unit: "USD/MT"

    hot_rolled_coil:
      q2_2026: "561"
      q1_2026: "540"
      change_rate: "+3.9%"
      unit: "USD/MT"

    cold_rolled_coil:
      q2_2026: "638"
      q1_2026: "577"
      change_rate: "+10.6%"
      unit: "USD/MT"

    nickel:
      q2_2026: "18,165"
      q1_2026: "17,364"
      change_rate: "+4.6%"
      unit: "USD/MT"

    copper:
      q2_2026: "13,326"
      q1_2026: "12,848"
      change_rate: "+3.7%"
      unit: "USD/MT"

  # 패션 부문 (단위: 억원)
  fashion_operating_profit:
    value: "54"
    unit: "억원"
    period: "2026 Q2"
    basis: "연결"
    margin: "9.1%"
    qoq: "+16 억원"
    yoy: "+21 억원"

  # 레저 부문 (단위: 억원)
  leisure_operating_profit:
    value: "0"
    unit: "억원"
    period: "2026 Q2"
    basis: "연결"
    margin: "0.0%"
    qoq: "+35 억원"
    yoy: "△9 억원"

  # 식음 부문 (단위: 억원)
  food_beverage_operating_profit:
    value: "48"
    unit: "억원"
    period: "2026 Q2"
    basis: "연결"
    margin: "5.4%"
    qoq: "+34 억원"
    yoy: "+3 억원"

  # 바이오 부문 세부 (단위: 억원)
  bio_revenue_by_company:
    biologics:
      value: "1,226"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 2
      parent: "bio"
      note: "바이오로직스"
      qoq: "+244 억원"
      yoy: "+337 억원"

    episciences:
      value: "393"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      level: 2
      parent: "bio"
      note: "에피스울딕스 (바이오로직스 실적 중 분할)"
      qoq: "△61 억원"
      yoy: "△8 억원"

  bio_operating_profit_by_company:
    biologics:
      value: "580"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      margin: "47.3%"
      qoq: "+159 억원"
      yoy: "+135 억원"

    episciences:
      value: "6"
      unit: "억원"
      period: "2026 Q2"
      basis: "연결"
      margin: "1.4%"
      qoq: "△56 억원"
      yoy: "△17 억원"

  # 건설 수주 현황 (조원 기준)
  construction_orders:
    q2_2026_total:
      value: "5.448"
      unit: "조원"
      period: "2026 Q2"
      basis: "연결"
      note: "2분기 수주 실적"

    h1_2026_total:
      value: "10.448"
      unit: "조원"
      period: "2026 H1"
      basis: "연결"
      note: "상반기 누적 수주"

    order_backlog:
      value: "34.244"
      unit: "조원"
      period: "2026년 말 기준"
      basis: "연결"
      note: "수주 잔고"

  construction_orders_by_type:
    building:
      q2:
        value: "5.044"
        unit: "조원"
        level: 2
      h1:
        value: "9.952"
        unit: "조원"
        level: 2
      backlog:
        value: "23.813"
        unit: "조원"
        level: 2

    civil_works:
      q2:
        value: "0.038"
        unit: "조원"
        level: 2
      h1:
        value: "0.043"
        unit: "조원"
        level: 2
      backlog:
        value: "1.183"
        unit: "조원"
        level: 2

    plant:
      q2:
        value: "0.366"
        unit: "조원"
        level: 2
      h1:
        value: "0.453"
        unit: "조원"
        level: 2
      backlog:
        value: "9.248"
        unit: "조원"
        level: 2

  construction_orders_by_region:
    domestic:
      q2:
        value: "3.515"
        unit: "조원"
        level: 2
      h1:
        value: "8.178"
        unit: "조원"
        level: 2
      backlog:
        value: "19.890"
        unit: "조원"
        level: 2

    overseas:
      q2:
        value: "1.933"
        unit: "조원"
        level: 2
      h1:
        value: "2.270"
        unit: "조원"
        level: 2
      backlog:
        value: "14.354"
        unit: "조원"
        level: 2

  # 주택사공권 확보 현황 (조원)
  housing_project_acquisition:
    q2_2026:
      value: "4.0"
      unit: "조원"
      period: "2026 Q2"
      note: "주택사공권 확보 실적"

    annual_target_2026:
      value: "4.0"
      unit: "조원"
      period: "2026년 목표"

  # 바이오 부문 전략 투자 (펀드)
  life_science_fund:
    fund_1:
      total_size: "1.70"
      unit: "조원"
      company_share: "0.99"
      unit_share: "조원"
      note: "1호 펀드"

    fund_2:
      total_size: "0.72"
      unit: "조원"
      company_share: "0.499"
      unit_share: "조원"
      note: "2호 펀드"

    fund_3_planned:
      total_size: "2.00"
      unit: "조원"
      company_share: "0.792"
      unit_share: "조원"
      note: "3호 펀드 조성 추진"

    cumulative_total:
      total_size: "4.42"
      unit: "조원"
      company_share: "2.281"
      unit_share: "조원"
      note: "1~2호 펀드 누적 규모"

  # 바이오로직스 인수 계획
  biologic_acquisition:
    polypeptide_company:
      acquisition_size: "2.7"
      unit: "조원"
      target: "PolyPeptide (스위스)"
      status: "인수 결정"
      note: "CDMO 포트폴리오 확대"

english_summary:
  title: "Samsung C&T Q2 2026 Earnings Results"
  one_liner: "Revenue KRW 1.20T (+14.6% QoQ, +19.7% YoY), Operating profit KRW 103B (+30.3% QoQ, +37.1% YoY)"
  highlights:
    - "Construction segment revenue KRW 399B (+5.1% margin) led by high-tech FAB project completion and full operation ramp-up"
    - "Trading segment revenue KRW 430B (+3.0% margin) driven by chemical and urea price recovery (+25.6% QoQ) and nickel market strength"
    - "Bio segment delivering exceptional performance with KRW 159B operating profit margin of 36.2%, driven by Samsung Biologics' four-factory full operation and capacity expansion"
    - "Major new orders secured in Q2 2026 including Angang Sports Complex redevelopment (KRW 0.8T), China Xier FAB (KRW 0.5T), and data center projects"
    - "Strategic investment in Life Science: Fund 3 (KRW 2.0T total, company share KRW 79.2B) and planned acquisition of PolyPeptide (KRW 2.7T) for peptide therapeutics portfolio expansion"
  key_figures_en:
    revenue: "KRW 1.20T (consolidated, +14.6% QoQ, +19.7% YoY)"
    operating_profit: "KRW 103B (+30.3% QoQ, +37.1% YoY)"
    operating_margin: "8.6% (+1.7%p QoQ)"
    net_income: "KRW 91.6B (+22.9% YoY)"
    order_backlog_construction: "KRW 34.2T (Q2 orders: KRW 5.4T)"
  outlook: "Construction segment expected to accelerate H2 performance with high-tech FAB project ramp-up and global energy project opportunities; Trading segment to benefit from market diversification and high-margin product expansion; Bio segment to sustain YoY revenue growth of +15~20% driven by Factory 5 and expanded facility ramp-up; Strategic emphasis on AI data center expansion and peptide therapeutics platform through PolyPeptide acquisition."

---
```

---

# 삼성물산 2026년 2분기 실적

[이미지: 다양한 산업 분야를 나타내는 아이콘 - 건물, 물류, 사람, 관광, 에너지, 생명과학]

## Disclaimer

본 자료의 재무정보는 한국채택 국제회계기준(K-IFRS)에 따라 작성된 **연결 기준**의 잠정 영업실적에 기초하여 작성되었습니다.

본 자료는 외부 감시인의 회계 검토가 완료되지 않은 상태에서 투자자 편의를 위하여 작성된 자료이므로 외부감시 과정에서 달라질 수 있음을 양지하시기 바랍니다.

---

# CONTENTS

삼성물산 2026년 2분기 실적

| 01 | 02 | 03 | 04 |
|---|---|---|---|
| 2026년 2분기 경영실적 | 사업부문별 실적 | 주요 사업 추진현황 | 별첨 |

---

# 2026년 2분기 경영실적

**단위: 억원 (연결기준)**

| 구분 | 2026년<br/>2분기 | 2026년<br/>1분기 | 분기<br/>변동 | 2025년<br/>2분기 | 전년동기<br/>변동 |
|---|---:|---:|---:|---:|---:|
| **매출** | 11,995 | 10,466 | +1,529 | 10,022 | +1,973 |
| 건설 | 3,988 | 3,413 | +575 | 3,395 | +593 |
| 상사 | 4,304 | 4,114 | +589 | 3,776 | +927 |
| 패션 | 593 | 573 | +20 | 510 | +83 |
| 레저 | 206 | 105 | +101 | 223 | △17 |
| 식음* | 886 | 825 | +61 | 828 | +58 |
| 바이오** | 1,619 | 1,436 | +183 | 1,290 | +329 |
| **매출이익** | 2,214 | 1,869 | +345 | 1,801 | +413 |
| 판관비 | 1,182 | 1,149 | +33 | 1,048 | +134 |
| **영업이익** | 1,032 | 720 | +312 | 753 | +279 |
| (영업이익률) | (8.6%) | (6.9%) | (+1.7%p) | (7.5%) | (+1.1%p) |
| **사업부문별 영업이익** | | | | | |
| 건설 | 202 | 111 | +91 | 118 | +84 |
| 상사 | 142 | 109 | +33 | 80 | +62 |
| 패션 | 54 | 38 | +16 | 33 | +21 |
| 레저 | 0 | △35 | +35 | 9 | △9 |
| 식음* | 48 | 14 | +34 | 45 | +3 |
| 바이오** | 586 | 483 | +103 | 468 | +118 |
| **기타순익** | △11 | 526 | △537 | △8 | △3 |
| **금융순익** | 34 | 58 | △24 | △9 | +43 |
| **지분법순익** | 39 | 41 | △2 | 17 | +5 |
| **세전이익** | 1,077 | 1,345 | △268 | 753 | +324 |
| **당기순이익** | 916 | 1,086 | △170 | 527 | +389 |
| **노지배지분순이익** | 596 | 844 | △248 | 353 | +243 |

**주석:**
- \*식음 (웰스토리): 100% 자회사
- \*\*바이오: 삼성바이오로직스 43.06% 자회사, 에머슨텍(구 삼성제약) 43.06% 자회사

**재무성과 해석:**
- 전분기 대비(QoQ): 매출 +14.6%, 영업이익 +43.3% 증가
- 전년동기 대비(YoY): 매출 +19.7%, 영업이익 +37.1% 증가
- 영업이익률은 분기 기준 8.6%로 전분기 대비 1.7%p 개선되었으며, 전년동기 대비 1.1%p 개선

---

# 건설 사업부문 실적

## 2026년 2분기 손익

**단위: 억원 (연결기준)**

| 구분 | 2026년<br/>2분기 | 2026년<br/>1분기 | 분기<br/>변동 | 2025년<br/>2분기 | 전년동기<br/>변동 |
|---|---:|---:|---:|---:|---:|
| **매출** | 3,988 | 3,413 | +575 | 3,395 | +593 |
| **유형별 매출** | | | | | |
| 건축 | 2,651 | 2,329 | +386 | 2,329 | +302 |
| 토목 | 127 | 108 | +19 | 159 | △32 |
| 플랜트 | 1,230 | 1,060 | +170 | 907 | +323 |
| **지역별 매출** | | | | | |
| 국내 | 2,122 | 1,395 | +727 | 1,586 | +536 |
| 해외 | 1,866 | 2,018 | △152 | 1,809 | +57 |
| **매출이익** | 459 | 399 | +60 | 366 | +93 |
| **영업이익** | 202 | 111 | +91 | 118 | +84 |
| (이익률) | (5.1%) | (3.2%) | (+1.9%p) | (3.5%) | (+1.6%p) |

**[원본 확인 필요]** 건축(2,651) + 토목(127) + 플랜트(1,230) = 4,008억원 ≠ 전체 매출 3,988억원 (차이 20억원)
또한 국내(2,122) + 해외(1,866) = 3,988억원으로 합계 일치 확인. 유형별 합계와 지역별 합계 간 불일치 확인 필요.

### 2분기 실적 평가

- **하이테크 FAB 공사 진행**: P4 마감 및 P5 공조 공사 분기 마무리, 전분기 대비 공사 일정 선행 효과
- **해외 플랜트 프로젝트**: 전년 시공 수준 유지하며 공정 촉진으로 전분기 대비 매출·영업이익 증가
- **영업이익률 개선**: 2분기 5.1%로 1분기(3.2%) 대비 1.9%p 개선, 
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
