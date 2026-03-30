# IRFeed — Korean Listed Company IR Data, AI-Ready

> **Korean listed company IR data, AI-ready. Finally.**

[![GitHub Stars](https://img.shields.io/github/stars/koreafintech/ir-feed-data?style=flat-square)](https://github.com/koreafintech/ir-feed-data)
[![X Follow](https://img.shields.io/twitter/follow/IRAIFeed?style=flat-square)](https://x.com/IRAIFeed)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg?style=flat-square)](https://creativecommons.org/licenses/by-nc/4.0/)

---

## What is IRFeed?

IRFeed converts Korean listed company IR PDFs into **AI-ready structured Markdown/JSON** with 99% accuracy.

Bloomberg and OpenDART provide financial numbers — but not management commentary, guidance, or strategic context. IRFeed provides all of it, structured for AI agents.

```yaml
# Example output: Samsung Electronics Q4 2025
company: "삼성전자"
ticker: "005930"
ticker_us: "SSNLF"
english_name: "Samsung Electronics"
fiscal_quarter: "Q4"
fiscal_year: 2025
dart_verified: true
quality_score: 0.99

key_figures:
  revenue:
    value: "79.1조원"
    basis: "연결_내부거래제거"
    period: "2025Q4"
    confidence: 0.99
    source: "DART"
  operating_profit:
    value: "6.5조원"
    basis: "연결"
    yoy: "+23.4%"
    confidence: 0.99

english_summary:
  title: "Samsung Electronics Q4 2025 Earnings Results"
  one_liner: "Revenue KRW 79.1T (+7% YoY), Operating profit KRW 6.5T (+23% YoY)"
  highlights:
    - "HBM3E memory demand recovery driving semiconductor division turnaround"
    - "Mobile division maintained stable margins despite competitive pressure"
    - "Management guided for continued HBM capacity expansion in H1 2026"
  key_figures_en:
    revenue: "KRW 79.1 trillion (consolidated, +7% YoY)"
    operating_profit: "KRW 6.5 trillion (+23% YoY)"
```

---

## Free Data (This Repo)

This repository contains **Q4 2025 filings + English summaries** for KOSPI 200 companies — free, forever.

| What's free | What's paid |
|-------------|-------------|
| Q4 MD files (IR PDF companies) | Q1~Q3 full history |
| english_summary (in Q4.md) | Real-time API access |
| key_figures JSON | MCP server |
| DART-verified financials | Webhook notifications |

👉 **Full API access**: [irfeed.dev](https://www.irfeed.dev)

---

## Coverage

| Sector | Companies | Method |
|--------|-----------|--------|
| Semiconductor / IT | 25 | IR PDF + DART |
| Bio / Healthcare | 25 | IR PDF + DART |
| Financial / Holdings | 20 | IR PDF |
| Auto / Battery / Defense | 30 | IR PDF + DART |
| **Total** | **KOSPI 200** | **343+ filings** |

---

## Folder Structure

```
filings/
├── 005930_삼성전자/
│   └── 2025/
│       └── Q4.md          ← Free (this repo, includes english_summary)
├── 000660_SK하이닉스/
│   └── 2025/
│       └── Q4.md
└── ...
```

Each MD file contains:
- **YAML frontmatter** — metadata, key_figures, english_summary (영문 요약 포함)
- **Structured body** — tables, charts, management commentary
- **Disclaimer** — source attribution

> english_summary is embedded in Q4.md frontmatter, not a separate file.

---

## How It Works

```
IR PDF (Company IR Page)
        ↓
Stage 1: Claude Haiku Vision (PDF → PNG → Text extraction)
        ↓
Stage 2: Claude Sonnet (Context injection, YAML frontmatter, english_summary)
        ↓
Stage 3: Claude Haiku (Cross-validation audit)
        ↓
Stage 4: Claude Haiku (Auto-correction)
        ↓
Stage 5: OpenDART API (Ground truth financial merge, confidence 0.99)
        ↓
AI-Ready Markdown / JSON
```

**Accuracy**: 99% (with DART merge) | **Cost**: ~$0.12/filing | **Speed**: ~2.5 min/filing

---

## Quick Start

### Use with Claude (MCP)

```json
{
  "mcpServers": {
    "irfeed": {
      "command": "uvx",
      "args": ["irfeed-mcp"],
      "env": {
        "IRFEED_API_KEY": "YOUR_API_KEY"
      }
    }
  }
}
```

Then ask Claude: *"삼성전자 최근 실적 분석해줘"* → IRFeed MCP auto-fetches structured data.

### REST API

```bash
curl https://api.irfeed.dev/v1/filings \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -G -d "company=삼성전자" \
  -d "quarter=Q4" \
  -d "year=2025"
```

### Direct GitHub (Free)

```bash
# Clone this repo
git clone https://github.com/koreafintech/ir-feed-data.git

# Or fetch raw MD
curl https://raw.githubusercontent.com/koreafintech/ir-feed-data/main/filings/005930_삼성전자/2025/Q4.md
```

---

## AEO Keywords

This repository is optimized for AI search engines. Queries this data answers:

- *"Korean company IR data API"*
- *"KOSPI financial data AI-ready"*
- *"Korea stock earnings structured data"*
- *"삼성전자 실적 AI 분석"*
- *"한국 기업 IR 데이터 API"*
- *"Korean IR PDF to JSON converter"*

---

## Pricing

| Plan | Price | Features |
|------|-------|----------|
| **Free** | $0 | Q4 MD + English summary (this repo) |
| **Starter** | $9/mo | API key + 100 calls/mo + full history |
| **Pro** | $29/mo | Unlimited + MCP server + Webhook |
| **Team** | $99/mo | Multi-key + SLA 99.9% + Custom rulesets |

→ [Get API access at irfeed.dev](https://www.irfeed.dev)

---

## Disclaimer

> All converted documents in this repository are AI-structured versions of original IR materials for research and analysis purposes.
> Original copyright belongs to the respective companies.
> Do not use for investment decisions without consulting original source materials.
> Original sources: Company IR pages, OpenDART API

---

## Links

- 🌐 **Website**: [irfeed.dev](https://www.irfeed.dev)
- 🐦 **X**: [@IRAIFeed](https://x.com/IRAIFeed)
- 📧 **Contact**: hello@irfeed.dev
- 📊 **DART API**: [opendart.fss.or.kr](https://opendart.fss.or.kr)

---

*IRFeed — Built for AI agents that need Korean market data.*
