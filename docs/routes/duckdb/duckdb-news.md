# DuckDB Foundation - 新闻

## Coverage
`index-only`

## Route
- Namespace: `duckdb`
- Namespace Name: `DuckDB Foundation`
- Route Path: `/duckdb/news`
- Route Name: `新闻`
- Example: `/duckdb/news`
- URL: `duckdb.org`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `mocusez`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/duckdb/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 19,
  "location": "news.ts",
  "maintainers": [
    "mocusez"
  ],
  "name": "新闻",
  "parameters": {},
  "path": "/news",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "DuckDB News - Powered by RSSHub",
      "errorAt": "2025-10-07T17:37:20.808Z",
      "errorMessage": "[GET] \"https://duckdb.orghttps://ducklake.select/2026/05/04/ducklake-dataframe/\": <no response> fetch failed (getaddrinfo ENOTFOUND duckdb.orghttps)\n",
      "id": "69641222629419008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://duckdb.org/news/",
      "title": "DuckDB News",
      "type": "feed",
      "url": "rsshub://duckdb/news"
    }
  ]
}
```
