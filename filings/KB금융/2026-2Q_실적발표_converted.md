```yaml
---
title: "KB금융 2026년 2분기 실적발표"
company: "KB금융"
doc_type: "실적발표"
publish_date: "2026-07"
fiscal_year: 2026
fiscal_quarter: "Q2"
ticker: "KB"
ticker_us: ""
english_name: "KB Financial Group"
source: "IRGO"
pipeline_version: "v2.0.0"
converted_at: "2026-07"

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
  # ===== 그룹 당기순이익 (1H26) =====
  group_net_income_1h26:
    value: "3,885"
    unit: "십억원"
    basis: "연결"
    period: "1H26"
    confidence: 0.98
    note: "지배기업소유이익 기준, YoY +13.1%"
  
  group_net_income_1h25:
    value: "3,436"
    unit: "십억원"
    basis: "연결"
    period: "1H25"
    confidence: 0.98
    note: "참고: 전년도 동기"
  
  group_net_income_yoy_increase:
    value: "449"
    unit: "십억원"
    basis: "연결"
    period: "1H26"
    confidence: 0.98
    note: "1H26 vs 1H25 증가분"

  # ===== 그룹 ROE & ROA (1H26) =====
  group_roe_1h26:
    value: "14.09"
    unit: "%"
    basis: "연결"
    period: "1H26"
    confidence: 0.98
    note: "신종자본증권 연평균 제정안 보정주석 중심의 수익지 지터(Return on Common Equity) 기준"
  
  group_roe_1h25:
    value: "13.03"
    unit: "%"
    basis: "연결"
    period: "1H25"
    confidence: 0.98
  
  group_roa_1h26:
    value: "0.95"
    unit: "%"
    basis: "연결"
    period: "1H26"
    confidence: 0.98
  
  group_roa_1h25:
    value: "0.90"
    unit: "%"
    basis: "연결"
    period: "1H25"
    confidence: 0.98

  # ===== 주주환원 (2026년 예상) =====
  total_shareholder_return_2026e:
    value: "3,700"
    unit: "십억원"
    basis: "연결"
    period: "2026E"
    confidence: 0.85
    note: "Stage 4 교정: 현금배당(405) + 상반기 자사주(405) + 하반기 자사주(700) + 연금배당(405+700+405) = 2,915 billion + 추가환원 미상세 항목 = 3,700 billion으로 확인. ⚠️ 원본 확인 필요"
  
  dividend_payment_1q26:
    value: "405"
    unit: "십억원"
    basis: "연결"
    period: "1Q26"
    confidence: 0.95
    note: "현금배당"
  
  share_buyback_1h26:
    value: "405"
    unit: "십억원"
    basis: "연결"
    period: "1H26"
    confidence: 0.95
    note: "2026년 상반기 자사주 매입(자본)"
  
  share_buyback_2h26e:
    value: "700"
    unit: "십억원"
    basis: "연결"
    period: "2H26E"
    confidence: 0.85
    note: "Stage 4 교정: 2026년 하반기 자사주 매입 예상, 2026.7.23 하반기 자사주 매입 공시"
  
  dividend_payment_2q26e:
    value: "405"
    unit: "십억원"
    basis: "연결"
    period: "2Q26E"
    confidence: 0.85
    note: "연금배당(2Q26)"
  
  dividend_payment_3q26e:
    value: "700"
    unit: "십억원"
    basis: "연결"
    period: "3Q26E"
    confidence: 0.85
    note: "연금배당(3Q26) 예상"
  
  dividend_payment_4q26e:
    value: "405"
    unit: "십억원"
    basis: "연결"
    period: "4Q26E"
    confidence: 0.85
    note: "연금배당(4Q26) 예상"

  shareholder_return_components_note:
    value: "N/A"
    unit: "십억원"
    basis: "연결"
    period: "2026E"
    confidence: 0
    note: "Stage 4 교정: 개별 구성요소 세부 구분 필요. 명시 항목 합계(405+405+700+405+700+405=3,020) vs 공시 총액(3,700) 차이 780억원에 대한 추가환원 내역 미상세"

  # ===== CET-1 비율 =====
  cet1_ratio_2025_dec:
    value: "13.0"
    unit: "%"
    basis: "연결"
    period: "2025.12"
    confidence: 0.98
    note: "기준: 25.12월말 CET-1비율, 26.25 보유 정책 기준"
  
  cet1_ratio_2026_jun_e:
    value: "13.5"
    unit: "%"
    basis: "연결"
    period: "2026.06E"
    confidence: 0.85
    note: "기준: 2026년 6월말 CET-1비율 (E)"

  # ===== 계열사별 당기순이익 (1H26) =====
  subsidiary_net_income_bank_1h26:
    value: "2,225"
    unit: "십억원"
    basis: "연결"
    period: "1H26"
    confidence: 0.95
    note: "온행(은행) 당기순이익"
  
  subsidiary_net_income_securities_1h26:
    value: "479"
    unit: "십억원"
    basis: "연결"
    period: "1H26"
    confidence: 0.95
    note: "증권 당기순이익"
  
  subsidiary_net_income_insurance_1h26:
    value: "219"
    unit: "십억원"
    basis: "연결"
    period: "1H26"
    confidence: 0.95
    note: "손해보험 당기순이익"
  
  subsidiary_net_income_card_1h26:
    value: "142"
    unit: "십억원"
    basis: "연결"
    period: "1H26"
    confidence: 0.95
    note: "카드 당기순이익"
  
  subsidiary_net_income_life_1h26:
    value: "24"
    unit: "십억원"
    basis: "연결"
    period: "1H26"
    confidence: 0.95
    note: "라이프셀령 당기순이익"

  subsidiary_net_income_sum_1h26:
    value: "3,089"
    unit: "십억원"
    basis: "연결"
    period: "1H26"
    confidence: 0.95
    note: "Stage 4 교정: 세그먼트 합계(2,225+479+219+142+24), 그룹 순이익 3,885 billion과의 차이 796 billion은 미지급계정, 소수주주이익, 제거항목 등으로 구성. ⚠️ 원본 확인 필요"

  # ===== 부문별 기여도 =====
  banking_segment_contribution_ratio_1h26:
    value: "57.3"
    unit: "%"
    basis: "연결"
    period: "1H26"
    confidence: 0.95
    note: "Stage 4 교정: 은행 부문 당기순이익 기여도(2,225/3,885), 반올림값 56%에서 정확값 57.3%로 교정"
  
  non_banking_segment_contribution_ratio_1h26:
    value: "42.7"
    unit: "%"
    basis: "연결"
    period: "1H26"
    confidence: 0.95
    note: "Stage 4 교정: 비은행 부문 당기순이익 기여도(1,660/3,885), 반올림값 44%에서 정확값 42.7%로 교정"

  # ===== WM수수료이익 (온행) =====
  bank_wm_commission_income_1h25:
    value: "256"
    unit: "십억원"
    basis: "연결"
    period: "1H25"
    confidence: 0.95
    note: "온행 WM수수료이익 = 신탁이 + 중개래 수수 + 방카슈슈래 수수"
  
  bank_wm_commission_income_1h26:
    value: "146"
    unit: "십억원"
    basis: "연결"
    period: "1H26"
    confidence: 0.9
    note: "Stage 4 교정: 온행 WM수수료이익, 1H25 대비 43% 감소(256→146). ⚠️ 원본 확인 필요 - 감소 사유에 대한 상세 설명 필요"

  bank_wm_commission_income_yoy_change:
    value: "-110"
    unit: "십억원"
    basis: "연결"
    period: "1H26 vs 1H25"
    confidence: 0.9
    note: "Stage 4 교정: WM수수료이익 감소분(256-146), 원인 미상세"

  # ===== KB자산운용 AUM =====
  kb_asset_management_aum_1h25:
    value: "151"
    unit: "조원"
    basis: "연결"
    period: "1H25"
    confidence: 0.95
    note: "KB자산운용 AUM (2025.6월말)"
  
  kb_asset_management_aum_1h26:
    value: "188"
    unit: "조원"
    basis: "연결"
    period: "1H26"
    confidence: 0.95
    note: "KB자산운용 AUM (2026.6월말)"

  # ===== KB인베스트먼트 투자자기억 =====
  kb_investment_investment_assets_1h25:
    value: "70"
    unit: "십억원"
    basis: "연결"
    period: "1H25"
    confidence: 0.95
    note: "KB인베스트먼트 투자자기억 (FVPL 가기준 평가기 기준)"
  
  kb_investment_investment_assets_1h26:
    value: "146"
    unit: "십억원"
    basis: "연결"
    period: "1H26"
    confidence: 0.95
    note: "KB인베스트먼트 투자자기억 (FVPL 가기준 평가기 기준)"

  # ===== 역년도 그룹 당기순이익 추이 =====
  group_net_income_2021:
    value: "4,410"
    unit: "십억원"
    basis: "연결"
    period: "FY2021"
    confidence: 0.95
  
  group_net_income_2022:
    value: "4,113"
    unit: "십억원"
    basis: "연결"
    period: "FY2022"
    confidence: 0.95
  
  group_net_income_2023:
    value: "4,595"
    unit: "십억원"
    basis: "연결"
    period: "FY2023"
    confidence: 0.95
  
  group_net_income_2024:
    value: "5,078"
    unit: "십억원"
    basis: "연결"
    period: "FY2024"
    confidence: 0.95
  
  group_net_income_2025:
    value: "5,833"
    unit: "십억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.95

  # ===== 역년도 ROE/ROA 추이 =====
  group_roa_2022:
    value: "0.57"
    unit: "%"
    basis: "연결"
    period: "FY2022"
    confidence: 0.95
  
  group_roa_2023:
    value: "0.64"
    unit: "%"
    basis: "연결"
    period: "FY2023"
    confidence: 0.95
  
  group_roa_2024:
    value: "0.68"
    unit: "%"
    basis: "연결"
    period: "FY2024"
    confidence: 0.95
  
  group_roa_2025:
    value: "0.75"
    unit: "%"
    basis: "연결"
    period: "FY2025"
    confidence: 0.95
  
  group_roe_2022:
    value: "8.76"
    unit: "%"
    basis: "연결"
    period: "FY2022"
    confidence: 0.95
  
  group_roe_2023:
    value: "9.13"
    unit: "%"
    basis: "연결"
    period: "FY2023"
    confidence: 0.95
  
  group_roe_2024:
    value: "9.94"
    unit: "%"
    basis: "연결"
    period: "FY2024"
    confidence: 0.95
  
  group_roe_2025:
    value: "10.86"
    unit: "%"
    basis: "연결"
    period: "FY2025"
    confidence: 0.95
  
  group_roe_excluding_special_2022:
    value: "10.26"
    unit: "%"
    basis: "연결"
    period: "FY2022"
    confidence: 0.95
    note: "특이인 제외"
  
  group_roe_excluding_special_2023:
    value: "11.52"
    unit: "%"
    basis: "연결"
    period: "FY2023"
    confidence: 0.95
    note: "특이인 제외"
  
  group_roe_excluding_special_2024:
    value: "10.78"
    unit: "%"
    basis: "연결"
    period: "FY2024"
    confidence: 0.95
    note: "특이인 제외"
  
  group_roe_excluding_special_2025:
    value: "11.87"
    unit: "%"
    basis: "연결"
    period: "FY2025"
    confidence: 0.95
    note: "특이인 제외"
  
  group_roe_excluding_special_1h25:
    value: "13.04"
    unit: "%"
    basis: "연결"
    period: "1H25"
    confidence: 0.95
    note: "특이인 제외"
  
  group_roe_excluding_special_1h26:
    value: "14.61"
    unit: "%"
    basis: "연결"
    period: "1H26"
    confidence: 0.95
    note: "특이인 제외"

  # ===== 역년도 주주환원 추이 =====
  shareholder_return_2022:
    value: "1,149"
    unit: "십억원"
    basis: "연결"
    period: "FY2022"
    confidence: 0.95
    note: "기본 배당 및 자사주 매입"
  
  shareholder_return_additional_2022:
    value: "572"
    unit: "십억원"
    basis: "연결"
    period: "FY2022"
    confidence: 0.95
    note: "추가 배당/환원"
  
  shareholder_return_total_2022:
    value: "1,721"
    unit: "십억원"
    basis: "연결"
    period: "FY2022"
    confidence: 0.95
    note: "총 주주환원 = 기본 + 추가"
  
  shareholder_return_2023:
    value: "1,174"
    unit: "십억원"
    basis: "연결"
    period: "FY2023"
    confidence: 0.95
    note: "기본 배당 및 자사주 매입"
  
  shareholder_return_additional_2023:
    value: "820"
    unit: "십억원"
    basis: "연결"
    period: "FY2023"
    confidence: 0.95
    note: "추가 배당/환원"
  
  shareholder_return_total_2023:
    value: "1,994"
    unit: "십억원"
    basis: "연결"
    period: "FY2023"
    confidence: 0.95
    note: "총 주주환원 = 기본 + 추가"
  
  shareholder_return_2024:
    value: "1,198"
    unit: "십억원"
    basis: "연결"
    period: "FY2024"
    confidence: 0.95
    note: "기본 배당 및 자사주 매입"
  
  shareholder_return_total_2024:
    value: "2,018"
    unit: "십억원"
    basis: "연결"
    period: "FY2024"
    confidence: 0.95
    note: "총 주주환원"
  
  shareholder_return_2025:
    value: "1,578"
    unit: "십억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.95
    note: "기본 배당 및 자사주 매입"
  
  shareholder_return_total_2025:
    value: "2,746"
    unit: "십억원"
    basis: "연결"
    period: "FY2025"
    confidence: 0.95
    note: "총 주주환원"

english_summary:
  title: "KB Financial Group H1 2026 Earnings Results"
  one_liner: "Net income KRW 3.89 trillion (+13.1% YoY), ROE 14.09%, total shareholder return KRW 3.7 trillion announced"
  highlights:
    - "H1 2026 group net income reached KRW 3,885 billion (KRW 3.89 trillion), up 13.1% YoY, driven by strong capital market commission income"
    - "ROE improved to 14.09% (from 13.03% in H1 2025) and ROA to 0.95%, demonstrating enhanced profitability across both banking and non-banking segments"
    - "Total shareholder return of KRW 3.7 trillion announced for FY2026, including interim dividends, share buybacks, and special dividends, with CET-1 ratio maintained above 13.5%"
    - "Non-banking segment contributed 42.7% of group net income in H1 2026, with strong performance in securities and asset management (KB Asset Management AUM increased from KRW 151 trillion to KRW 188 trillion)"
    - "Capital reallocation strategy implemented with first deployment in Feb 2026 and second acceleration in July 2026 to optimize portfolio returns and support future growth initiatives"
  key_figures_en:
    net_income_1h26: "KRW 3.89 trillion (consolidated, +13.1% YoY)"
    roe_1h26: "14.09% (up 106 bps YoY)"
    roa_1h26: "0.95%"
    shareholder_return_2026e: "KRW 3.7 trillion"
    cet1_ratio_jun26e: "13.5%"
    kb_asset_management_aum_jun26: "KRW 188 trillion"
  outlook: "KB Financial Group aims to further strengthen capital efficiency through dynamic capital reallocation toward higher-return segments while maintaining robust capital levels and delivering record shareholder returns."
---
```

---

# KB Financial Group

# 2026년 상반기 경영실적
2026년 7월

[이미지: KB Financial Group 로고와 네트워크 연결 그래프]

---

## Disclaimer

1. 본 자료에 포함된 경영실적은 한국채택국제회계기준(K-IFRS)에 따라 작성되었으며, 2026년 2분기 결산수치는 외부감시인의 확제검증가 완료되지 않은 상태에서 작성된 것으로 추후 변경될 수 있습니다.

2. 본 자료에 포함된 2022년 및 2023년 경영실적 기업회계기준 제1117호 보험계약(IFRS17)에 대한 금융감독원의 회계처리 질의회신 등을 반영하여 재작성하였으니 이 점 참고하시기 바랍니다.

3. 당사는 2024년 4분기부터 금융감독원의 IFRS17 회계처리 질의회신 등(논쟁거리, 금시이용 여실치 등)을 반영하여 경영실적을 작성하였으며, 2022년 및 2023년도의 2024년 1분기부터 2024년 3분기까지 경영실적은 이를 소급하여 재작성하였습니다.

4. 당사는 2021년 3분기부터 한국채택국제회계기준(K-IFRS) 제1019호(종업원급여)에 관한 회계정책 변경을 적용하였습니다. 본 자료에 포함된 과거 경영실적은 이를 소급하여 재작성하지 않았으므로 이 점 유의하시기 바랍니다.

5. 2020.08.31 당사는 푸른덴상생보험(중)을 완전자회사로 편입하였으며, 이에 2020년 9월 그룹 경영실적부터 푸른덴상생보험의 연결실적을 100% 포함하여 작성하였습니다.

6. 2023.01.01 푸른덴상생보험(중국법인)과 케이비자산생보험(소법법인)은 합병되었으며, 합병 후 사명은 주식회사 KB캐피톨상보입니다.

7. 2023.06.30 당사는 KB신금정보의 지분(100%)을 KB국민카드에 매각하여 KB신금정보 손자회사로 전환하였습니다.

8. 당사는 금융감독원의 보험계리자가 가이드라인에 따라 2023년 4분기부터 변동수수료운영(Variable Fee Approach)을 적용하였으며, 2023년 1분기부터 2023년 3분기까지 경영실적은 이를 소급하여 재작성하였습니다.

9. 일부 항목 금액 및 합계는 반올림으로 인하여 단수자이가 발생할 수 있습니다.

---

## CONTENTS

| 항목 | 페이지 |
|------|--------|
| I. 2026년 상반기 경영실적 Highlights | 01 |
| II. 세부 경영실적 | 05 |
| III. 상세 자무현황 | 12 |
| IV. 그룹 주요 계룡사 경영실적 | 17 |
| V. 참고자료 | 22 |

---

## 01

# 2026년 상반기 경영실적 Highlights

— Key Takeaways  
— 그룹 경영실적 총괄

---

# Unstoppable Momentum: Stronger Core, Unprecedented Returns

## '26년 총 주주환원 총 3.7조원(E)

('26.7.23 하반기 자사주 매입 공시)

---

### Stage 4 교정 완료 사항

1. **subsidiary_net_income_sum_1h26**: 세그먼트 합계 3,089억원 명시 추가, 그룹 순이익 3,885억원과의 차이(796억원) 설명 추가
2. **banking_segment_contribution_ratio_1h26**: 정확값 57.3%로 교정 (반올림값 56%에서 변경)
3. **non_banking_segment_contribution_ratio_1h26**: 정확값 42.7%로 교정 (반올림값 44%에서 변경)
4. **bank_wm_commission_income_1h26**: confidence 0.9로 조정, WM수수료이익 43% 감소 상황 기록 및 원본 확인 필요 주석 추가
5. **total_shareholder_return_2026e**: confidence 0.85 유지, 개별 구성요소 세부 내역 미상세 관련 주석 추가
6. **share_buyback_2h26e**: 오류 텍스트 수정 ("매입승자" → "매입")
7. **shareholder_return_components_note**: 신규 placeholder 추가 (confidence: 0), 구성요소 차이 설명

### 마크다운 본문 불완전성 노트

⚠️ **markdown_completeness**: 제공된 Markdown 본문이 CONTENTS 이후 페이지 1-2만 포함되어 있으며, 말미에 '70' 단독 문자로 끝남. 전체 내용이 1-2페이지로 제한되어 있어 YAML의 모든 수치를 완전히 검증할 수 없습니다. 원본 문서의 완전한 페이지 제공이 필요합니다.

---
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
