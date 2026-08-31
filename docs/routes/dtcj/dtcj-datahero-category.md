# DT 财经 - 数据侠专栏

## Coverage
`index-only`

## Route
- Namespace: `dtcj`
- Namespace Name: `DT 财经`
- Route Path: `/dtcj/datahero/:category?`
- Route Name: `数据侠专栏`
- Example: `/dtcj/datahero`
- URL: `dtcj.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `datahero.ts`
- Source Module: `_None_`

## Description
| 侠创 | 纽约数据科学学院 | RS 实验所 | 阿里云天池 |
| ---- | ---------------- | --------- | ---------- |
| 5    | 6                | 9         | 10         |

## Parameters
- `category`: 分类，见下表，默认为全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 侠创 | 纽约数据科学学院 | RS 实验所 | 阿里云天池 |\n| ---- | ---------------- | --------- | ---------- |\n| 5    | 6                | 9         | 10         |",
  "example": "/dtcj/datahero",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "datahero.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "数据侠专栏",
  "parameters": {
    "category": "分类，见下表，默认为全部"
  },
  "path": "/datahero/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-07-08T17:59:19.428Z",
      "errorMessage": "[GET] \"https://dtcj.com/api/v1/data_hero_informations?per=15&page=1&topic_id=\": 503 Service Temporarily Unavailable\n[GET] \"https://dtcj.com/api/v1/data_hero_informations?per=15&page=1&topic_id=\": 503 Service Temporarily Unavailable\n",
      "id": "165445337069434884",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://dtcj/datahero"
    }
  ]
}
```
