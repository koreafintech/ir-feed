# irfeed-mcp

MCP server for Korean listed company IR data. Access DART earnings reports, financial disclosures, and key figures directly from Claude Desktop.

한국 상장기업 IR 공시 데이터를 Claude Desktop에서 바로 조회할 수 있는 MCP 서버입니다.

## Tools

| Tool | Description | Annotations |
|------|-------------|-------------|
| `list_filings` | List IR filings with filters (company, date, type) | readOnly, idempotent |
| `get_filing` | Get full details of a specific filing | readOnly, idempotent |
| `search_filings` | Search filings by keyword | readOnly, idempotent |
| `get_key_figures` | Query key financial metrics (revenue, operating profit, etc.) | readOnly, idempotent |

All tools are **read-only** — they only query publicly available data and never modify any state.

## Quick Start

### Option A: npx (no install)

```json
{
  "mcpServers": {
    "irfeed": {
      "command": "npx",
      "args": ["-y", "irfeed-mcp"],
      "env": {
        "IRFEED_SUPABASE_URL": "YOUR_SUPABASE_PROJECT_URL",
        "IRFEED_SUPABASE_ANON_KEY": "YOUR_ANON_KEY"
      }
    }
  }
}
```

### Option B: Global install

```bash
npm install -g irfeed-mcp
```

Claude Desktop config (`claude_desktop_config.json`):

**macOS:** `~/Library/Application Support/Claude/claude_desktop_config.json`
**Windows:** `%APPDATA%\Claude\claude_desktop_config.json`

```json
{
  "mcpServers": {
    "irfeed": {
      "command": "irfeed-mcp",
      "env": {
        "IRFEED_SUPABASE_URL": "YOUR_SUPABASE_PROJECT_URL",
        "IRFEED_SUPABASE_ANON_KEY": "YOUR_ANON_KEY"
      }
    }
  }
}
```

## Environment Variables

| Variable | Required | Description |
|----------|----------|-------------|
| `IRFEED_SUPABASE_URL` | Yes | Supabase project URL |
| `IRFEED_SUPABASE_ANON_KEY` | Yes* | Supabase anon key (read-only, RLS enforced) |
| `IRFEED_SUPABASE_SERVICE_KEY` | No | Fallback for anon key |

*Get your free key at [irfeed.dev](https://irfeed.dev)

## Usage Examples

Once configured in Claude Desktop, just ask in natural language:

### Use Case 1: Quarterly Earnings Research

Quickly review a company's latest earnings announcements for investment research or competitive analysis.

```
삼성전자의 최근 실적발표 공시 5건 보여줘
Show me Samsung Electronics' last 5 earnings filings
```

### Use Case 2: Financial Metrics Comparison

Pull key financial figures (revenue, operating profit, margins) to compare companies or track trends over time.

```
2024년 4분기 SK하이닉스 영업이익이 얼마야?
What was SK Hynix's operating profit in Q4 2024?
```

### Use Case 3: Industry & Keyword Research

Search across all filings by keyword to find industry-specific disclosures like capex plans, M&A activity, or sector trends.

```
'반도체 설비투자' 관련 공시 검색해줘
Search for filings related to 'semiconductor capex'
```

### Use Case 4: Bilingual IR Access

All filings include English summaries, enabling global investors and analysts to access Korean market data without language barriers.

```
Show me Samsung Electronics Q4 2024 earnings
카카오의 2024년 사업보고서 찾아줘
```

## Data Coverage

- **335 filings** from **120 Korean listed companies** (KOSPI/KOSDAQ)
- DART consolidated financial statements (연결재무제표)
- Structured key figures: revenue, operating profit, net income, margins, debt ratio
- English summaries included for global accessibility
- Updated quarterly with new DART filings
- Sectors: semiconductors, electronics, telecom, internet, gaming, financials, chemicals, and more

## Development

```bash
git clone https://github.com/koreafintech/ir-feed.git
cd ir-feed/mcp-server
npm install
npm run build
npm start
```

## Privacy Policy

IRFeed MCP Server is committed to protecting user privacy.

**Data Collection:** This MCP server does NOT collect, store, or transmit any personal data. It operates as a local stdio process on the user's machine and only queries publicly available Korean listed company IR data from a read-only database.

**What we access:**
- Supabase database queries for publicly filed IR documents and DART financial statements
- No user credentials, chat history, or personal information is accessed or stored

**What we do NOT access:**
- No previous chat history or memory contents
- No personal files or data on the user's device
- No browsing history, cookies, or session data
- No user analytics or tracking beyond anonymous API usage counts

**Network requests:** The server makes outbound HTTPS requests only to the configured Supabase project URL to fetch IR filing data. No other network connections are made. The User-Agent header (`irfeed-mcp/<version>`) is sent for anonymous usage monitoring only.

**Third-party sharing:** No data is shared with any third parties. The server is fully open-source under MIT license.

**Data retention:** The server itself stores no data. API usage logs (endpoint, timestamp, anonymous client IP) are retained for up to 30 days for service monitoring and then automatically deleted.

**Contact:** For privacy inquiries, contact us at contact@irfeed.dev or visit [irfeed.dev](https://irfeed.dev).

## Support & Contact

- **Website:** [irfeed.dev](https://irfeed.dev)
- **Email:** contact@irfeed.dev
- **GitHub Issues:** [github.com/koreafintech/ir-feed/issues](https://github.com/koreafintech/ir-feed/issues)
- **npm:** [npmjs.com/package/irfeed-mcp](https://www.npmjs.com/package/irfeed-mcp)

## License

MIT
