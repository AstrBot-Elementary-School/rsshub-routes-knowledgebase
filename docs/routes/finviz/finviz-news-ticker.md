# finviz - US Stock News

## Coverage
`index-only`

## Route
- Namespace: `finviz`
- Namespace Name: `finviz`
- Route Path: `/finviz/news/:ticker`
- Route Name: `US Stock News`
- Example: `/finviz/news/AAPL`
- URL: `finviz.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `HenryQW`
- Source Location: `quote.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `ticker`: The stock ticker


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
    "finance"
  ],
  "example": "/finviz/news/AAPL",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 134,
  "location": "quote.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "US Stock News",
  "parameters": {
    "ticker": "The stock ticker"
  },
  "path": "/news/:ticker",
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "A collection of news aggregated by Finviz. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "79424087027101706",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://finviz.com/quote.ashx?t=AAPL",
      "title": "AAPL News by Finviz",
      "type": "feed",
      "url": "rsshub://finviz/news/AAPL"
    },
    {
      "description": "A collection of news aggregated by Finviz. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "99092999437425664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://finviz.com/quote.ashx?t=NVDA",
      "title": "NVDA News by Finviz",
      "type": "feed",
      "url": "rsshub://finviz/news/NVDA"
    }
  ]
}
```
