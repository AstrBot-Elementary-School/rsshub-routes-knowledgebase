# 差评 - 图片墙

## Coverage
`index-only`

## Route
- Namespace: `chaping`
- Namespace Name: `差评`
- Route Path: `/chaping/banner`
- Route Name: `图片墙`
- Example: `/chaping/banner`
- URL: `chaping.cn/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `banner.ts`
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
  - `chaping.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/chaping/banner",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 196,
  "location": "banner.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "图片墙",
  "parameters": {},
  "path": "/banner",
  "radar": [
    {
      "source": [
        "chaping.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "差评 - 首页图片墙 - Powered by RSSHub",
      "errorAt": "2025-05-10T23:18:22.754Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://chaping.cn/\": 502 Bad Gateway\n",
      "id": "55178476295845997",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://chaping.cn/",
      "title": "差评 - 首页图片墙",
      "type": "feed",
      "url": "rsshub://chaping/banner"
    }
  ],
  "url": "chaping.cn/"
}
```
