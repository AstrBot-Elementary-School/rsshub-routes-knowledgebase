# DT 财经 - 数据洞察

## Coverage
`index-only`

## Route
- Namespace: `dtcj`
- Namespace Name: `DT 财经`
- Route Path: `/dtcj/datainsight/:id?`
- Route Name: `数据洞察`
- Example: `/dtcj/datainsight`
- URL: `dtcj.com/dtcj/datainsight`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `datainsight.ts`
- Source Module: `_None_`

## Description
| 城数 | NEXT 情报局 | 专业精选 |
| ---- | ----------- | -------- |
| 3    | 1           | 4        |

## Parameters
- `id`: 分类，见下表，默认为全部


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
  - `dtcj.com/insighttopic/:id`
- `target`: `/datainsight/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 城数 | NEXT 情报局 | 专业精选 |\n| ---- | ----------- | -------- |\n| 3    | 1           | 4        |",
  "example": "/dtcj/datainsight",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 15,
  "location": "datainsight.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "数据洞察",
  "parameters": {
    "id": "分类，见下表，默认为全部"
  },
  "path": "/datainsight/:id?",
  "radar": [
    {
      "source": [
        "dtcj.com/insighttopic/:id"
      ],
      "target": "/datainsight/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-07-08T17:59:20.055Z",
      "errorMessage": "[GET] \"https://dtcj.com/datainsight\": 503 Service Temporarily Unavailable\n",
      "id": "165445337069434883",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://dtcj/datainsight"
    },
    {
      "description": null,
      "errorAt": "2025-05-26T04:23:57.082Z",
      "errorMessage": "[GET] \"https://dtcj.com/insighttopic/4\": 503 Service Temporarily Unavailable\n",
      "id": "149642094386478091",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://dtcj/datainsight/4"
    }
  ],
  "url": "dtcj.com/dtcj/datainsight"
}
```
