# 金十数据 - 主题文章

## Coverage
`index-only`

## Route
- Namespace: `jin10`
- Namespace Name: `金十数据`
- Route Path: `/jin10/topic/:id`
- Route Name: `主题文章`
- Example: `/jin10/topic/396`
- URL: `jin10.com/`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `miles170`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: N


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
  - `xnews.jin10.com/topic/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/jin10/topic/396",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 271,
  "location": "topic.ts",
  "maintainers": [
    "miles170"
  ],
  "name": "主题文章",
  "parameters": {
    "id": "N"
  },
  "path": "/topic/:id",
  "radar": [
    {
      "source": [
        "xnews.jin10.com/topic/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "关于美联储的那些事 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "88845418189377536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xnews.jin10.com/topic/20",
      "title": "订阅美联储动态",
      "type": "feed",
      "url": "rsshub://jin10/topic/20"
    },
    {
      "description": "交易员的故事 每日为您连载呈现 - Powered by RSSHub",
      "errorAt": "2025-10-29T08:00:39.150Z",
      "errorMessage": "Cannot read properties of undefined (reading 'list')\n",
      "id": "61438939744634880",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xnews.jin10.com/topic/396",
      "title": "《交易员故事》系列",
      "type": "feed",
      "url": "rsshub://jin10/topic/396"
    }
  ],
  "url": "jin10.com/",
  "view": 0
}
```
