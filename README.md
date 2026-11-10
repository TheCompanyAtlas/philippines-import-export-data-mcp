# Philippines Import Export Data MCP

**Philippines Customs Data: Importers, Suppliers & HS Codes.** Philippines import export data for your AI assistant. Search Philippines customs shipment records, find importers and foreign suppliers, and break down trade by HS code, partner country and counterparty company, through the Model Context Protocol.

An AI-native alternative to Philippines trade data from Panjiva, ImportGenius, Volza, Seair, TradeInt and ExportGenius: ask in plain language instead of exporting spreadsheets.

The MCP connection is provided by [The Company Atlas](https://thecompanyatlas.com). This repository does not run a separate server.

## Connect

```
https://thecompanyatlas.com/mcp/trade/philippines
```

Add this URL as a custom MCP connector in Claude, ChatGPT, Cursor, or any MCP-compatible client. Sign in with Google when prompted.

- Transport: Streamable HTTP
- Auth: Google OAuth (sign in once, stays authorized)
- Free accounts get 50 credits per calendar month
- Defaults to Philippines: the server tells your AI to filter on `PH` unless you ask about another country

## Philippines data coverage

- **Years:** 2019–2026
- **Records:** Import declarations: Philippine importer, foreign supplier, origin country, HS code, goods description, value, quantity, port and date.
- **Country code:** `PH` (use `buyerCountry: "PH"` for imports into Philippines)
- **Common products:** integrated circuits (HS 8542), refined fuel (HS 2710), cars (HS 8703), rice (HS 1006)

## Notable traders in the data

Companies that appear most often in recent Philippines records (by number of declaration lines, not value):

**Importers**

- SFA Semicon Philippines
- Petron Corporation
- Texas Instruments Philippines
- Toyota Motor Philippines
- Mitsubishi Motors Philippines

## Example prompts

- *"Who are the top importers of rice (HS 1006) into the Philippines?"*
- *"What does SFA Semicon Philippines import, and from which countries?"*
- *"List Philippine importers of cars (HS 8703) in 2025"*
- *"Which suppliers ship fuel to Petron Corporation?"*
- *"Show recent shipments for Toyota Motor Philippines"*

## Tools

### Trade search

| Tool | Description |
|---|---|
| `Trade_search_trades` | Paginated customs shipment search: filter by HS code, buyer, seller, country, port, value and date range |
| `Trade_company_trade_volume_by_year` | Rank importers or exporters by declared value and line counts per year, with HS code and country filters |

### Trade analytics

| Tool | Description |
|---|---|
| `Trade_hs_code_breakdown` | For one company, import and export value by HS chapter, heading or subheading |
| `Trade_year_country_breakdown` | For one company, trade value by year and counterparty country |
| `Trade_partner_breakdown` | For one company, trade value by year and matched counterparty company |

### Company registry

| Tool | Description |
|---|---|
| `Company_search` | Search the global company registry by name or id, with optional country filter |
| `Company_get_by_id` | Full company profile by id |

## Keywords

Philippines import data, Philippines export data, Philippines customs data, Philippines shipment data, importers in Philippines, Philippines buyers and suppliers, HS code search, Philippines import data, Bureau of Customs data, list of importers in the Philippines, HS code
