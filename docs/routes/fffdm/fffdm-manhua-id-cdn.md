# 风之动漫 - 在线漫画

## Coverage
`index-only`

## Route
- Namespace: `fffdm`
- Namespace Name: `风之动漫`
- Route Path: `/fffdm/manhua/:id/:cdn?`
- Route Name: `在线漫画`
- Example: `/fffdm/manhua/93`
- URL: `manhua.fffdm.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `zytomorrow`
- Source Location: `manhua/manhua.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 漫画ID。默认获取全部，建议使用通用参数limit获取指定数量
- `cdn`: cdn加速器。默认5，当前可选1-5


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
  - `www.fffdm.com/manhua/:id`
  - `www.fffdm.com/:id`
- `target`: `/manhua/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/fffdm/manhua/93",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "manhua/manhua.tsx",
  "maintainers": [
    "zytomorrow"
  ],
  "name": "在线漫画",
  "parameters": {
    "cdn": "cdn加速器。默认5，当前可选1-5",
    "id": "漫画ID。默认获取全部，建议使用通用参数limit获取指定数量"
  },
  "path": "/manhua/:id/:cdn?",
  "radar": [
    {
      "source": [
        "www.fffdm.com/manhua/:id",
        "www.fffdm.com/:id"
      ],
      "target": "/manhua/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-09T21:57:34.174Z",
      "errorMessage": "Cannot read properties of undefined (reading 'title')\nFailed to fetch\n",
      "id": "70455789093681153",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://fffdm/manhua/2"
    }
  ]
}
```
