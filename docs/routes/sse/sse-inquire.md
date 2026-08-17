# 上海证券交易所 - 监管问询

## Coverage
`index-only`

## Route
- Namespace: `sse`
- Namespace Name: `上海证券交易所`
- Route Path: `/sse/inquire`
- Route Name: `监管问询`
- Example: `/sse/inquire`
- URL: `www.sse.com.cn/disclosure/credibility/supervision/inquiries`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `Jeason0228`
- Source Location: `inquire.tsx`
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
  - `www.sse.com.cn/disclosure/credibility/supervision/inquiries`
  - `www.sse.com.cn/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/sse/inquire",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 30,
  "location": "inquire.tsx",
  "maintainers": [
    "Jeason0228"
  ],
  "name": "监管问询",
  "parameters": {},
  "path": "/inquire",
  "radar": [
    {
      "source": [
        "www.sse.com.cn/disclosure/credibility/supervision/inquiries",
        "www.sse.com.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "上海证券交易所 - 科创板股票审核 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64364739096153088",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.sse.com.cn/disclosure/credibility/supervision/inquiries/",
      "title": "上海证券交易所 - 科创板股票审核",
      "type": "feed",
      "url": "rsshub://sse/inquire"
    }
  ],
  "url": "www.sse.com.cn/disclosure/credibility/supervision/inquiries"
}
```
