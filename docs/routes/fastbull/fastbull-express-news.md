# FastBull - News Flash

## Coverage
`index-only`

## Route
- Namespace: `fastbull`
- Namespace Name: `FastBull`
- Route Path: `/fastbull/express-news`
- Route Name: `News Flash`
- Example: `/fastbull/express-news`
- URL: `fastbull.com/express-news`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `express-news.ts`
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
  - `fastbull.com/express-news`
  - `fastbull.com/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/fastbull/express-news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 547,
  "location": "express-news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News Flash",
  "parameters": {},
  "path": "/express-news",
  "radar": [
    {
      "source": [
        "fastbull.com/express-news",
        "fastbull.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ Array(1) ] to not include 'https://www.fastbull.comundefined/'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "实时财经快讯 - FastBull - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60338304723722240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.fastbull.com/express-news",
      "title": "实时财经快讯 - FastBull",
      "type": "feed",
      "url": "rsshub://fastbull/express-news"
    }
  ],
  "url": "fastbull.com/express-news",
  "view": 0
}
```
