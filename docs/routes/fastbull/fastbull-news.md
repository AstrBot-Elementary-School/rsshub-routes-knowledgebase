# FastBull - News

## Coverage
`index-only`

## Route
- Namespace: `fastbull`
- Namespace Name: `FastBull`
- Route Path: `/fastbull/news`
- Route Name: `News`
- Example: `/fastbull/news`
- URL: `fastbull.com/news`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `news.tsx`
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
  - `fastbull.com/cn/news`
  - `fastbull.com/cn`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/fastbull/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 190,
  "location": "news.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "fastbull.com/cn/news",
        "fastbull.com/cn"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(4) ] to not include 'https://www.fastbull.com/cn/news-deta…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "财经头条、财经新闻、最新资讯 - FastBull - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59799220289372189",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.fastbull.com/cn/news",
      "title": "财经头条、财经新闻、最新资讯 - FastBull",
      "type": "feed",
      "url": "rsshub://fastbull/news"
    }
  ],
  "url": "fastbull.com/news",
  "view": 0
}
```
