```yaml
---
title: "KB금융 2026년 2분기 실적발표"
company: "KB금융"
english_name: "KB Financial Group"
ticker: ""
ticker_us: ""
doc_type: "실적발표"
publish_date: "2026-07-23"
fiscal_year: 2026
fiscal_quarter: "Q2"
source: "IRGO"
pipeline_version: "v2.1.0"
converted_at: "2025-01-XX"

key_figures:
  dart_operating_profit_annual:
    value: "108,805.9"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_net_income_annual:
    value: "58,407.2"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_total_assets:
    value: "7,979,230.3"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_total_liabilities:
    value: "7,370,930.4"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  dart_total_equity:
    value: "608,299.9"
    unit: "억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    source: "DART"
    note: "OpenDART API Ground Truth"
  # 그룹 당기순이익 (지배기업소유익 기준)
  net_income_group:
    value: "3,885"
    unit: "십억원"
    basis: "연결"
    period: "1H26"
    yoy_growth: "+13.1%"
    confidence: 0.99
    note: "지배기업소유익 기준, 자본시장 관련 순수료이익 중심의 비이자이익 개선"
  
  net_income_group_fy25:
    value: "5,833"
    unit: "십억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.99
    note: "연간 기준"
  
  net_income_1h25:
    value: "3,436"
    unit: "십억원"
    basis: "연결"
    period: "1H25"
    confidence: 0.99
    note: "비교 기준"
  
  # ROE (지배기업소유익의 수익성 지표)
  roe:
    value: "11.87"
    unit: "%"
    basis: "연결"
    period: "1H26"
    yoy_growth: "+1.06%p"
    confidence: 0.99
    note: "Return on Common Equity(ROCE) 기준"
  
  roe_1h25:
    value: "11.52"
    unit: "%"
    basis: "연결"
    period: "1H25"
    confidence: 0.99
  
  roe_special_items_excluded:
    value: "14.09"
    unit: "%"
    basis: "연결"
    period: "1H26"
    confidence: 0.99
    note: "신중자본충격 영향을 제외한 ROE"
  
  roe_special_items_excluded_1h25:
    value: "13.04"
    unit: "%"
    basis: "연결"
    period: "1H25"
    confidence: 0.99
  
  # ROA
  roa:
    value: "0.95"
    unit: "%"
    basis: "연결"
    period: "1H26"
    confidence: 0.99
  
  roa_1h25:
    value: "0.90"
    unit: "%"
    basis: "연결"
    period: "1H25"
    confidence: 0.99
  
  # 당기순이익 세부 분석 (1H25 vs 1H26 증감 요인) - Stage 4 교정
  income_increase_breakdown:
    revenue_improvement:
      value: "26"
      unit: "십억원"
      note: "순수수익이익 증가"
      confidence: 0.95
      stage_4_note: "⚠️ 원본 확인 필요 - 합계 검증 실패"
    
    non_interest_income:
      value: "995"
      unit: "십억원"
      note: "유기증진 및 뮤직·인베스팅 수익 증가"
      confidence: 0.95
      stage_4_note: "⚠️ 원본 확인 필요 - 합계 검증 실패"
    
    operating_expense_decrease:
      value: "298"
      unit: "십억원"
      note: "영업비용 감소"
      confidence: 0.95
      stage_4_note: "⚠️ 원본 확인 필요 - 합계 검증 실패"
    
    credit_impairment_decrease:
      value: "110"
      unit: "십억원"
      note: "신용·순동급금 정손금 감소"
      confidence: 0.95
      stage_4_note: "⚠️ 원본 확인 필요 - 합계 검증 실패"
    
    other_expense_decrease:
      value: "299"
      unit: "십억원"
      note: "기타 비용 감소"
      confidence: 0.95
      stage_4_note: "⚠️ 원본 확인 필요 - 합계 검증 실패"
    
    provision_increase:
      value: "-287"
      unit: "십억원"
      note: "대손비용 등 증가 (마이너스 요인)"
      confidence: 0.95
      stage_4_note: "⚠️ 원본 확인 필요 - 합계 검증 실패"
    
    total_net_income_increase:
      value: "449"
      unit: "십억원"
      note: "1H25(3,436십억원) → 1H26(3,885십억원) | ⚠️ Stage 4 교정: 구성요소 합계(26+995+298+110+299-287=1,441십억원)가 표시된 총액(449십억원)과 불일치. 원본 문서에서 해당 수치들이 동일 지표를 나타내는지 또는 추가 조정이 있는지 확인 필요. 구성요소가 상이한 메트릭을 대표하거나 분석이 불완전할 수 있음."
      confidence: 0.85
  
  # 계열사별 순이익 (1H26, 연결조정 등 제외)
  subsidiary_net_income:
    banking:
      value: "2,225"
      unit: "십억원"
      basis: "연결"
      period: "1H26"
      contribution_pct: "56%"
      confidence: 0.99
      note: "은행 부문"
    
    securities:
      value: "479"
      unit: "십억원"
      basis: "연결"
      period: "1H26"
      contribution_pct: "12%"
      confidence: 0.99
      note: "증권 부문"
    
    non_life_insurance:
      value: "796"
      unit: "십억원"
      basis: "연결"
      period: "1H26"
      contribution_pct: "20%"
      confidence: 0.99
      note: "손해보험 부문"
    
    card:
      value: "219"
      unit: "십억원"
      basis: "연결"
      period: "1H26"
      contribution_pct: "6%"
      confidence: 0.99
      note: "카드 부문 (연결조정 등 제외)"
    
    life_insurance:
      value: "142"
      unit: "십억원"
      basis: "연결"
      period: "1H26"
      contribution_pct: "4%"
      confidence: 0.99
      note: "생명보험(라이프생명) 부문"
    
    others:
      value: "24"
      unit: "십억원"
      basis: "연결"
      period: "1H26"
      contribution_pct: "1%"
      confidence: 0.99
      note: "기타"
    
    total:
      value: "3,885"
      unit: "십억원"
      basis: "연결"
      period: "1H26"
      confidence: 0.99
      note: "지배기업소유익 기준, 은행 56% + 비은행 44%"
  
  # 은행·비은행 부문 기여도
  sector_contribution:
    banking_sector:
      pct: "56%"
      note: "은행 부문"
    
    non_banking_sector:
      pct: "44%"
      note: "비은행 부문 (증권+손해보험+카드+생명보험+기타)"
  
  # 주요 자본지표
  cet1_ratio_25dec:
    value: "13.00"
    unit: "%"
    basis: "선제적 자본관리비율"
    date: "2025-12-31"
    confidence: 0.95
    note: "13.0% 초과 자본 확대, 79bp 개선"
  
  cet1_ratio_26h1:
    value: "13.50"
    unit: "%"
    basis: "선제적 자본관리비율"
    date: "2026-06-30"
    confidence: 0.95
    note: "13.5% 초과 자본 확대, 24bp 개선"
  
  # 자본시장 관련 주요 지표
  capital_market_indicators:
    kb_wealth_management_fee_1h25:
      value: "256"
      unit: "십억원"
      basis: "연결"
      period: "1H25"
      entity: "KB국민은행"
      metric: "WM수수료이익"
      confidence: 0.95
    
    kb_wealth_management_fee_1h26:
      value: "146"
      unit: "십억원"
      basis: "연결"
      period: "1H26"
      entity: "KB국민은행"
      metric: "WM수수료이익"
      confidence: 0.60
      note: "⚠️ Stage 4 교정: 1H25(256십억원) → 1H26(146십억원) 급감. 원본에서 'needs reverification' 표기. 수치 재확인 필요 - confidence 0.60으로 조정"
    
    kb_asset_mgmt_aum_1h25:
      value: "151"
      unit: "조원"
      basis: "연결"
      period: "1H25"
      entity: "KB자산운용"
      metric: "AUM(자산관리규모)"
      confidence: 0.95
    
    kb_asset_mgmt_aum_1h26:
      value: "188"
      unit: "조원"
      basis: "연결"
      period: "1H26"
      entity: "KB자산운용"
      metric: "AUM"
      yoy_growth: "+24.5%"
      confidence: 0.95
    
    kb_investment_asset_mgmt_income_1h25:
      value: "70"
      unit: "십억원"
      basis: "연결"
      period: "1H25"
      entity: "KB인베스트먼트"
      metric: "자산관리이익"
      confidence: 0.95
    
    kb_investment_asset_mgmt_income_1h26:
      value: "146"
      unit: "십억원"
      basis: "연결"
      period: "1H26"
      entity: "KB인베스트먼트"
      metric: "자산관리이익"
      yoy_growth: "+108.6%"
      confidence: 0.95
    
    kb_securities_roe_1h25:
      value: "10.1"
      unit: "%"
      basis: "연결"
      period: "1H25"
      entity: "KB증권"
      metric: "ROE"
      confidence: 0.95
    
    kb_securities_roe_1h26:
      value: "21.0"
      unit: "%"
      basis: "연결"
      period: "1H26"
      entity: "KB증권"
      metric: "ROE"
      yoy_growth: "+10.9%p"
      confidence: 0.95
      note: "자본시장 부문 성장 가속화"
    
    kb_securities_fee_income_1h25:
      value: "410"
      unit: "십억원"
      basis: "연결"
      period: "1H25"
      entity: "KB증권"
      metric: "순수수익이익"
      confidence: 0.95
    
    kb_securities_fee_income_1h26:
      value: "1,151"
      unit: "십억원"
      basis: "연결"
      period: "1H26"
      entity: "KB증권"
      metric: "순수수익이익"
      yoy_growth: "+180.7%"
      confidence: 0.95
    
    kb_securities_brokerage_aum_1h26_variant1:
      value: "1,853"
      unit: "조원"
      basis: "연결"
      period: "1H26"
      entity: "KB증권"
      metric: "Brokerage AUM"
      confidence: 0.30
      note: "⚠️ Stage 4 교정: 원본에 두 가지 충돌하는 수치 표시 (1,853조원 vs 212조원). 둘 다 confidence 0.70으로 표시되어 있으나 실제 신뢰도 매우 낮음. 원본 문서에서 출처 명확화 필요. confidence 0.30으로 조정"
    
    kb_securities_brokerage_aum_1h26_variant2:
      value: "212"
      unit: "조원"
      basis: "연결"
      period: "1H26"
      entity: "KB증권"
      metric: "Brokerage AUM"
      confidence: 0.30
      note: "⚠️ Stage 4 교정: 원본에 두 가지 충돌하는 수치 표시 (1,853조원 vs 212조원). 둘 다 confidence 0.70으로 표시되어 있으나 실제 신뢰도 매우 낮음. 원본 문서에서 출처 명확화 필요. confidence 0.30으로 조정"
    
    kb_securities_brokerage_aum_1h25:
      value: "26.6"
      unit: "조원"
      basis: "연결"
      period: "1H25"
      entity: "KB증권"
      metric: "Brokerage AUM"
      confidence: 0.95
    
    kb_securities_aum_alt_1h25:
      value: "25.6"
      unit: "조원"
      basis: "연결"
      period: "1H25"
      entity: "KB증권"
      metric: "AUM (alternative figure)"
      confidence: 0.35
      note: "⚠️ Stage 4 교정: 1H25에 두 가지 수치 표시 (25.6조원 vs 26.6조원). 정의 불명확. 원본에서 조정 필요. confidence 0.35로 조정"
    
    kb_securities_aum_alt_1h26:
      value: "107"
      unit: "조원"
      basis: "연결"
      period: "1H26"
      entity: "KB증권"
      metric: "AUM (alternative figure)"
      confidence: 0.35
      note: "⚠️ Stage 4 교정: 원본에 두 가지 수치 표시. 1H25 대비 정의가 불명확하고 brokerage AUM과의 관계 불명확. 원본 문서에서 메트릭 정의 및 reconciliation 필요. confidence 0.35로 조정"
  
  # 주주환원
  shareholder_return:
    total_return_2026_estimate:
      value: "3,700"
      unit: "십억원"
      basis: "연결"
      period: "FY2026(예상)"
      confidence: 0.85
      note: "1Q배당+상반기자사주+하반기자사주+2Q배당+3Q배당+4Q배당"
    
    dividend_1q26:
      value: "405"
      unit: "십억원"
      basis: "연결"
      period: "1Q26"
      type: "배당금"
      confidence: 0.95
    
    share_buyback_h1_actual:
      value: "1,200"
      unit: "십억원"
      basis: "연결"
      period: "1H26"
      type: "자사주 매입"
      status: "완료"
      confidence: 0.95
    
    share_buyback_h2_plan:
      value: "700"
      unit: "십억원"
      basis: "연결"
      period: "2H26"
      type: "자사주 매입"
      status: "계획"
      confidence: 0.85
      note: "26.7.23 현기 기준"
    
    dividend_2q26:
      value: "405"
      unit: "십억원"
      basis: "연결"
      period: "2Q26"
      type: "배당금"
      confidence: 0.95
    
    dividend_3q26:
      value: "405"
      unit: "십억원"
      basis: "연결"
      period: "3Q26"
      type: "배당금"
      status: "예상"
      confidence: 0.85
    
    dividend_4q26:
      value: "180"
      unit: "십억원"
      basis: "연결"
      period: "4Q26"
      type: "배당금"
      status: "예상"
      confidence: 0.85
    
    total_shareholder_return_2026:
      value: "3,700"
      unit: "십억원"
      basis: "연결"
      period: "FY2026(E)"
      breakdown: "배당 1,395 + 자사주 2,305"
      confidence: 0.85
      note: "역대 최대 규모 주주환원"
    
    historical_shareholder_return:
      fy2022:
        value: "1,149"
        unit: "십억원"
      fy2023:
        value: "1,174"
        unit: "십억원"
      fy2024:
        value: "1,198"
        unit: "십억원"
      fy2025:
        value: "3,198"
        unit: "십억원"
        note: "배당 1,578 + 자사주 1,620"
      fy2026e:
        value: "3,700"
        unit: "십억원"
        note: "예상"

english_summary:
  title: "KB Financial Group 1H 2026 Earnings Results"
  one_liner: "Net income KRW 3.88 trillion (+13.1% YoY), led by strong non-interest income growth; ROE expanded to 11.87% from 11.52%"
  highlights:
    - "Group consolidated net income reached KRW 3.88 trillion in 1H26 (+13.1% YoY), driven by robust performance in capital markets-related fee income and investment returns"
    - "Non-interest income surged by KRW 99.5 billion, reflecting growth in music and investing revenue; KB Asset Management AUM expanded to KRW 18.8 trillion (+24.5% YoY)"
    - "KB Securities achieved record profitability with net fee income of KRW 115.1 billion (+180.7% YoY) and ROE of 21.0% (+10.9%p), demonstrating successful portfolio repositioning toward higher-return segments"
    - "CET-1 ratio improved to 13.50% at end-1H26 from 13.00% at end-2025, maintaining strong capital buffer above regulatory threshold"
    - "Record shareholder return of KRW 3.70 trillion planned for FY2026, including KRW 1.40 trillion in dividends and KRW 2.30 trillion in share buybacks (1H actual: KRW 1.20 trillion completed, 2H planned: KRW 700 billion)"
    - "Banking segment contributed 56% of group net income (KRW 2.22 trillion), while non-banking sectors contributed 44%, demonstrating well-diversified earnings portfolio"
  key_figures_en:
    consolidated_net_income_1h26: "KRW 3.88 trillion (consolidated, +13.1% YoY)"
    roe_1h26: "11.87% (up 1.06%p YoY)"
    roe_excl_special_items: "14.09% (excluding special capital impact)"
    roa_1h26: "0.95% (up 5bp YoY)"
    banking_net_income: "KRW 2.22 trillion (56% of group total)"
    securities_net_income: "KRW 47.9 billion (12% of group total)"
    non_life_insurance_net_income: "KRW 79.6 billion (20% of group total)"
    kb_asset_mgmt_aum: "KRW 18.8 trillion (+24.5% YoY)"
    kb_securities_fee_income: "KRW 115.1 billion (+180.7% YoY)"
    kb_securities_roe: "21.0% (up 10.9%p YoY)"
    cet1_ratio: "13.50% as of 30 June 2026"
    planned_shareholder_return_2026: "KRW 3.70 trillion (record high)"
  outlook: "KB Financial Group is executing dynamic capital reallocation strategy to shift portfolio toward higher-return segments, with strategic capital injection into KB Securities and focus on capital markets businesses. Management targets continued momentum in non-interest income and expects to maintain strong capital position above regulatory thresholds while delivering record shareholder returns."
---
```

# 2026년 상반기 경영실적
## 2026년 7월

**KB Financial Group**

---

## Disclaimer

1. 본 자료에 포함된 경영실적은 한국채택국제회계기준(K-IFRS)에 따라 작성되었으며, 2026년 2분기 결산은 **외부감사인의 회계검증 전 상태**에서 작성된 것으로 **추후 변경될 수 있습니다.**

2. 본 자료에 포함된 2022년 및 2023년 경영실적은 기업회계기준 제1117호 보험계약(IFRS17)에 대한 금융감독원의 회계처리 질의회신 등을 반영하여 **재작성**하였습니다.

3. 본 자료는 공시용으로 준비되었으며, 추가 검증이 필요한 항목들은 Stage 4 교정 시점에 원본 문서와 재확인되어야 합니다.

---

## Stage 4 교정 내역

### 수정된 항목 (fail 판정 4개)

| 항목 | 상태 | 조치 |
|------|------|------|
| income_increase_breakdown_sum | fail | 합계 검증 실패(26+995+298+110+299-287=1,441 vs stated 449) - total_net_income_increase에 상세 주석 추가, confidence 0.85 유지 |
| kb_wealth_management_fee_anomaly | fail | 1H25(256) → 1H26(146) 급감 - confidence 0.60으로 조정, "⚠️ 원본 확인 필요" 주석 추가 |
| kb_securities_brokerage_aum_conflict | fail | 1H26 충돌값(1,853 vs 212조원) - 두 variant 모두 confidence 0.30으로 조정, "⚠️ 원본 확인 필요" 주석 추가 |
| kb_securities_aum_alternative | fail | 1H25(25.6 vs 26.6), 1H26(107) 정의 불명확 - 두 항목 모두 confidence 0.35로 조정, "⚠️ 원본 확인 필요" 주석 추가 |

### 교정 원칙 적용
- ✅ 원본 데이터 수치 변경 없음
- ✅ confidence 값만 조정 (0.9 미만)
- ✅ "⚠️ 원본 확인 필요" 주석 추가
- ✅ "Stage 4 교정" 표시 추가
- ✅ 각 실패 항목에 상세 설명 포함
```


---

## DART 연결재무제표 (KB금융, 2025년)
<!-- source: OpenDART API | ground_truth: true -->

| 계정 | 금액(억원) | 출처 |
|------|--------:|------|
| 영업이익 | 108,805.9 | DART |
| 당기순이익 | 58,407.2 | DART |
| 자산총계 | 7,979,230.3 | DART |
| 부채총계 | 7,370,930.4 | DART |
| 자본총계 | 608,299.9 | DART |
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
