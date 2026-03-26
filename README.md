# ir-feed-data

**한국 상장기업 IR PDF → AI-Ready 구조화 데이터**

> 매일 업데이트되는 IR 자료를 99% 정합성으로 자동 변환합니다.
> AI 에이전트, LLM 앱, 퀀트 분석에 바로 사용 가능한 Markdown/YAML 포맷.

---

## 이 Repo는 무엇인가요?

[IRFeed](https://ir-feed-landing-production.up.railway.app) 서비스의 **Free Tier 공개 데이터**입니다.

- 최근 7일 변환 결과를 무료로 제공합니다
- 전체 이력 + API + MCP 서버는 유료 플랜에서 제공됩니다
- 변환 파이프라인: PDF → Claude Vision → DART 병합 → 구조화 YAML

---

## 폴더 구조

```
filings/
├── 삼성전자/
│   └── 2025-4Q_실적발표_converted.md
├── 현대자동차/
│   └── 2025-4Q_실적발표_converted.md
└── (매일 추가됩니다)
```

---

## 데이터 포맷

각 MD 파일은 **YAML frontmatter + Markdown 본문** 구조입니다.

```yaml
---
company: "삼성전자"
doc_type: "실적발표"
fiscal_quarter: "Q4"
dart_verified: true        # OpenDART API로 검증된 수치
quality_score: 0.99        # 변환 정합성 점수

key_figures:
  revenue_q4:
    value: "93.8"
    unit: "조원"
    basis: "연결"           # 연결/별도 명시
    confidence: 0.95
    source: "DART"         # Ground Truth 출처
---
```

### 핵심 차별화: 숫자의 맥락 명시

단순 텍스트 추출이 아닌 **"이 숫자가 어떤 기준인가"**를 AI가 이해할 수 있도록 태깅합니다.

| 필드 | 설명 |
|------|------|
| `basis` | 연결/별도, 내부거래 제거 여부 |
| `confidence` | 변환 정합성 점수 (0~1) |
| `source` | DART(정형) / IR PDF 구분 |
| `dart_verified` | OpenDART API 교차검증 여부 |

---

## GitHub Raw로 바로 사용하기

```python
import httpx

# 삼성전자 최신 실적 가져오기
url = "https://raw.githubusercontent.com/koreafintech/ir-feed-data/main/filings/삼성전자/2025-4Q_실적발표_converted.md"
res = httpx.get(url)
print(res.text)
```

```javascript
// JavaScript
const res = await fetch(
  "https://raw.githubusercontent.com/koreafintech/ir-feed-data/main/filings/%EC%82%BC%EC%84%B1%EC%A0%84%EC%9E%90/2025-4Q_%EC%8B%A4%EC%A0%81%EB%B0%9C%ED%91%9C_converted.md"
);
const md = await res.text();
```

---

## 변환 파이프라인

```
[IRGO PDF] ──→ Stage 1: Claude Vision (PDF→Raw MD)
              ↓
           Stage 2: 맥락 주입 (단위·기준·연결/별도 태깅)
              ↓
           Stage 3: 검수 (숫자 교차검증, 합계 검산)
              ↓
           Stage 4: 수정 반영
              ↓
           Stage 5: DART 병합 (OpenDART API Ground Truth)
              ↓
           [구조화 MD/YAML] → GitHub (Free) / API (유료)
```

**평균 처리 비용**: ~$0.08/건 | **평균 정합성**: 93~99%

---

## 유료 플랜 (API / MCP)

| 플랜 | 가격 | 내용 |
|------|-----:|------|
| Free | $0 | 이 Repo (최근 7일) |
| Starter | $9/월 | REST API + 100건/월 |
| Pro | $29/월 | 무제한 + MCP 서버 + 영어 요약 |
| Team | $99/월 | 멀티키 + Webhook + SLA |

👉 **[베타 무료 신청 →](https://ir-feed-landing-production.up.railway.app/#beta)**

---

## 면책 고지

본 데이터는 IR PDF를 AI 분석 목적으로 자동 변환한 것입니다.
투자 판단 시 반드시 원본 IR 자료를 참고하세요.
원본 저작권은 해당 기업에 있습니다.

---

## 기여 / 문의

- 이슈: GitHub Issues
- 이메일: hello@irfeed.dev
- X(Twitter): [@irfeed_dev](https://x.com)
