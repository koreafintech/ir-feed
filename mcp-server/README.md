# irfeed-mcp

MCP server for Korean listed company IR data. Access DART earnings reports, financial disclosures, and key figures directly from Claude Desktop.

한국 상장기업 IR 공시 데이터를 Claude Desktop에서 바로 조회할 수 있는 MCP 서버입니다.

## Tools

| Tool | Description |
|------|-------------|
| `list_filings` | List IR filings with filters (company, date, type) |
| `get_filing` | Get full details of a specific filing |
| `search_filings` | Search filings by keyword |
| `get_key_figures` | Query key financial metrics (revenue, operating profit, etc.) |

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
| `IRFEED_SUPABASE_ANON_KEY` | Yes* | Supabase anon key (read-only, RLS enforced) |
| `IRFEED_SUPABASE_URL` | Yes | Supabase project URL |
| `IRFEED_SUPABASE_SERVICE_KEY` | No | Fallback for anon key |

*Get your key at [irfeed.dev](https://irfeed.dev)

## Usage Examples

Once configured in Claude Desktop, just ask in natural language:

```
삼성전자의 최근 실적발표 공시 5건 보여줘
```

```
2024년 4분기 SK하이닉스 영업이익이 얼마야?
```

```
'반도체 설비투자' 관련 공시 검색해줘
```

```
Show me Samsung Electronics Q4 2024 earnings
```

## Data Coverage

- 335 filings from 120 Korean listed companies
- DART consolidated financial statements
- Structured key figures (revenue, operating profit, net income, margins)
- English summaries included for global accessibility
- Updated quarterly with new DART filings

## Development

```bash
git clone https://github.com/koreafintech/ir-feed.git
cd ir-feed/mcp-server
npm install
npm run build
npm start
```

## License

MIT
