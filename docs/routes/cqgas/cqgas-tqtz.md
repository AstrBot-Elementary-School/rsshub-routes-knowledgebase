# 重庆燃气 - 停气检修通知

## Coverage
`index-only`

## Route
- Namespace: `cqgas`
- Namespace Name: `重庆燃气`
- Route Path: `/cqgas/tqtz`
- Route Name: `停气检修通知`
- Example: `/cqgas/tqtz`
- URL: `cqgas.cn/`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `Mai19930513`
- Source Location: `tqtz.ts`
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
  - `cqgas.cn/`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/cqgas/tqtz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "tqtz.ts",
  "maintainers": [
    "Mai19930513"
  ],
  "name": "停气检修通知",
  "parameters": {},
  "path": "/tqtz",
  "radar": [
    {
      "source": [
        "cqgas.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "重庆燃气——停气检修通知 - Powered by RSSHub",
      "errorAt": "2025-10-17T13:29:28.731Z",
      "errorMessage": "[GET] \"http://www.cqgas.cn/portal/article/page?cateId=1082&pageNo=1\": 403 Forbidden\n",
      "id": "66381483312011264",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.cqgas.cn/portal/article/page?cateId=1082&pageNo=1",
      "title": "重庆燃气——停气检修通知",
      "type": "feed",
      "url": "rsshub://cqgas/tqtz"
    }
  ],
  "url": "cqgas.cn/"
}
```
