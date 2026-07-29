# AInvest - Latest News

## Coverage
`index-only`

## Route
- Namespace: `ainvest`
- Namespace Name: `AInvest`
- Route Path: `/ainvest/news`
- Route Name: `Latest News`
- Example: `/ainvest/news`
- URL: `www.ainvest.com/news/`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `TonyRL`
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
### Rule 1
- `source`:
  - `www.ainvest.com/news/`

## Raw JSON
```json
{
  "categories": [
    "finance",
    "popular"
  ],
  "example": "/ainvest/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1536,
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Latest News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.ainvest.com/news/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(17) ] to not include 'https://www.ainvest.com/news/microsof…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "AInvest - Latest News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63585517712903168",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ainvest.com/news/",
      "title": "AInvest - Latest News",
      "type": "feed",
      "url": "rsshub://ainvest/news"
    }
  ],
  "url": "www.ainvest.com/news/",
  "view": 0
}
```
