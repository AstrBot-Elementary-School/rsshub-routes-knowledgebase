# 差评 - 快讯

## Coverage
`index-only`

## Route
- Namespace: `chaping`
- Namespace Name: `差评`
- Route Path: `/chaping/newsflash`
- Route Name: `快讯`
- Example: `/chaping/newsflash`
- URL: `chaping.cn/newsflash`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Fatpandac`
- Source Location: `newsflash.ts`
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
  - `chaping.cn/newsflash`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/chaping/newsflash",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 285,
  "location": "newsflash.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "快讯",
  "parameters": {},
  "path": "/newsflash",
  "radar": [
    {
      "source": [
        "chaping.cn/newsflash"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "差评 快讯 - Powered by RSSHub",
      "errorAt": "2025-05-11T00:29:28.699Z",
      "errorMessage": "[GET] \"https://chaping.cn/api/official/information/newsflash?page=1&limit=21\": 502 Bad Gateway\n[GET] \"https://chaping.cn/api/official/information/newsflash?page=1&limit=21\": 502 Bad Gateway\n[GET] \"https://chaping.cn/api/official/information/newsflash?page=1&limit=21\": 502 Bad Gateway\n",
      "id": "42594386603806720",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://chaping.cn/newsflash",
      "title": "差评 快讯",
      "type": "feed",
      "url": "rsshub://chaping/newsflash"
    }
  ],
  "url": "chaping.cn/newsflash"
}
```
