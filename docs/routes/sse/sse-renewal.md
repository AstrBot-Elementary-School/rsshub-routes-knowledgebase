# 上海证券交易所 - 科创板项目动态

## Coverage
`index-only`

## Route
- Namespace: `sse`
- Namespace Name: `上海证券交易所`
- Route Path: `/sse/renewal`
- Route Name: `科创板项目动态`
- Example: `/sse/renewal`
- URL: `kcb.sse.com.cn/home`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `Jeason0228`
- Source Location: `renewal.tsx`
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
  - `kcb.sse.com.cn/home`
  - `kcb.sse.com.cn/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/sse/renewal",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 32,
  "location": "renewal.tsx",
  "maintainers": [
    "Jeason0228"
  ],
  "name": "科创板项目动态",
  "parameters": {},
  "path": "/renewal",
  "radar": [
    {
      "source": [
        "kcb.sse.com.cn/home",
        "kcb.sse.com.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "上海证券交易所 - 科创板项目动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64720907961984057",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://kcb.sse.com.cn/renewal/",
      "title": "上海证券交易所 - 科创板项目动态",
      "type": "feed",
      "url": "rsshub://sse/renewal"
    }
  ],
  "url": "kcb.sse.com.cn/home"
}
```
