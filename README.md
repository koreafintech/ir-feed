# IRFeed — Korean Listed Company IR Data, AI-Ready

> **Korean listed company IR data, AI-ready. Finally.**

[![GitHub Stars](https://img.shields.io/github/stars/koreafintech/ir-feed?style=flat-square)](https://github.com/koreafintech/ir-feed)
[![X Follow](https://img.shields.io/twitter/follow/IRAIFeed?style=flat-square)](https://x.com/IRAIFeed)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg?style=flat-square)](https://creativecommons.org/licenses/by-nc/4.0/)

---

## What is IRFeed?

IRFeed converts Korean listed company IR PDFs into **AI-ready structured Markdown/JSON** with 99% accuracy.

Bloomberg and OpenDART provide financial numbers — but not management commentary, guidance, or strategic context. IRFeed provides all of it, structured for AI agents.

**All data is free and open.** Clone the repo, use the API, or connect via MCP — no API key required for read access.

```yaml
# Example: Samsung Electronics Q4 2025
company: "삼성전자"
ticker: "005930"
fiscal_quarter: "Q4"
fiscal_year: 2025
quality_score: 0.99
dart_verified: true

key_figures:
  revenue: { value: "79.1조원", yoy: "+7%", confidence: 0.99 }
  operating_profit: { value: "6.5조원", yoy: "+23.4%", confidence: 0.99 }

english_summary:
  one_liner: "Revenue KRW 79.1T (+7% YoY), Operating profit KRW 6.5T (+23% YoY)"
  highlights:
    - "HBM3E memory demand recovery driving semiconductor turnaround"
    - "Management guided for continued HBM capacity expansion in H1 2026"
```

---

## Data Coverage

| Category | Count | Description |
|----------|-------|-------------|
| **Companies** | 73 | KOSPI large-cap + mid-cap |
| **Total Filings** | 298 | Structured Markdown with YAML frontmatter |
| **Quarterly Earnings** | 262 | Q1~Q4 2025 (+ some 2026) |
| **NDR / ValueUp / Other** | 36 | Non-Deal Roadshows, Corporate Value-Up plans |
| **Accuracy** | 99% | With DART financial data merge |

### Document Types

- **Q1~Q4** — Quarterly earnings presentations
- **NDR** — Non-Deal Roadshow materials
- **ValueUp** — Corporate Value-Up program disclosures
- **H1** — Half-year reports
- **Split** — Corporate restructuring materials

---

## Folder Structure

```
filings/
├── 005930_삼성전자/
│   └── 2025/
│       ├── Q1.md
│       ├── Q2.md
│       ├── Q3.md
│       └── Q4.md          ← includes english_summary
├── 000660_SK하이닉스/
│   └── 2025/
│       ├── Q1.md ~ Q4.md
├── 000880_한화/
│   ├── 2025/
│   │   ├── Q1.md ~ Q4.md
│   │   ├── NDR.md
│   │   └── ValueUp.md
│   └── 2026/
│       └── ValueUp.md
└── ... (73 companies)
```

Each MD file contains:
- **YAML frontmatter** — metadata, key_figures, english_summary
- **Structured body** — tables, charts, management commentary
- **Disclaimer** — source attribution

---

## Quick Start

### 1. Direct from GitHub (Easiest)

```bash
# Clone entire repo
git clone https://github.com/koreafintech/ir-feed.git

# Or fetch a single file
curl https://raw.githubusercontent.com/koreafintech/ir-feed/main/filings/005930_삼성전자/2025/Q4.md
```

### 2. MCP (Claude Desktop)

```json
{
  "mcpServers": {
    "irfeed": {
      "command": "npx",
      "args": ["irfeed-mcp"]
    }
  }
}
```

Then ask Claude: *"삼성전자 최근 실적 분석해줘"*

### 3. REST API

```bash
# No API key required for read access
curl https://api.irfeed.dev/v1/filings?company_name=삼성전자&limit=5

curl https://api.irfeed.dev/v1/financials?ticker=005930&period=2025Q4
```

---

## How It Works

```
IR PDF (Company IR Page)
        ↓
Stage 1: Claude Haiku Vision — PDF → PNG → Text extraction
        ↓
Stage 2: Claude Sonnet — Context injection, YAML frontmatter, english_summary
        ↓
Stage 3: Claude Haiku — Cross-validation audit
        ↓
Stage 4: Claude Haiku — Auto-correction
        ↓
Stage 5: OpenDART API — Ground truth financial merge (confidence 0.99)
        ↓
AI-Ready Markdown / JSON
```

**Accuracy**: 99% (with DART merge) | **Cost**: ~$0.12/filing | **Speed**: ~2.5 min/filing

---

## AEO Keywords

Queries this data answers:

- *"Korean company IR data API"*
- *"KOSPI financial data AI-ready"*
- *"Korea stock earnings structured data"*
- *"삼성전자 실적 AI 분석"*
- *"한국 기업 IR 데이터 API"*
- *"Korean IR PDF to JSON converter"*

---

## Roadmap

- [x] Q4 2025 full coverage (70 companies)
- [x] Q1~Q3 2025 migration (298 filings total)
- [ ] Q1 2026 earnings season (April 2026~)
- [ ] npm publish irfeed-mcp
- [ ] PyPI publish irfeed SDK
- [ ] Personalized push notifications
- [ ] KOSPI 200 full coverage

---

## Disclaimer

> All converted documents are AI-structured versions of original IR materials for research and analysis purposes.
> Original copyright belongs to the respective companies.
> Do not use for investment decisions without consulting original source materials.
> Original sources: Company IR pages, OpenDART API

---

## Links

- **Website**: [irfeed.dev](https://www.irfeed.dev)
- **X**: [@IRAIFeed](https://x.com/IRAIFeed)
- **Contact**: hello@irfeed.dev
- **DART API**: [opendart.fss.or.kr](https://opendart.fss.or.kr)

---

*IRFeed — Built for AI agents that need Korean market data. All data free and open.*
