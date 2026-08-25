# Stock Edge - Daily Updates News

## Coverage
`index-only`

## Route
- Namespace: `stockedge`
- Namespace Name: `Stock Edge`
- Route Path: `/stockedge/daily-updates/news`
- Route Name: `Daily Updates News`
- Example: `/stockedge/daily-updates/news`
- URL: `web.stockedge.com/daily-updates/news`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `Rjnishant530`
- Source Location: `daily-news.ts`
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
### Rule 1
- `source`:
  - `web.stockedge.com/daily-updates/news`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/stockedge/daily-updates/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 265,
  "location": "daily-news.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Daily Updates News",
  "parameters": {},
  "path": "/daily-updates/news",
  "radar": [
    {
      "source": [
        "web.stockedge.com/daily-updates/news"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(6) ] to not include 'https://web.stockedge.com/share/pace-…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Daily Updates on stockedge.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72635895363612672",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://web.stockedge.com/daily-updates?section=news",
      "title": "Stock Edge",
      "type": "feed",
      "url": "rsshub://stockedge/daily-updates/news"
    }
  ],
  "url": "web.stockedge.com/daily-updates/news",
  "view": 5
}
```
