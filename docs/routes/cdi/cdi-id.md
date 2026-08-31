# 国家高端智库 / 综合开发研究院 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `cdi`
- Namespace Name: `国家高端智库 / 综合开发研究院`
- Route Path: `/cdi/:id?`
- Route Name: `栏目`
- Example: `/cdi`
- URL: `cdi.com.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 樊纲观点 | 综研国策 | 综研观察 | 综研专访 | 综研视点 | 银湖新能源 |
| -------- | -------- | -------- | -------- | -------- | ---------- |
| 102      | 152      | 150      | 153      | 154      | 151        |

## Parameters
- `id`: 分类，见下表，默认为综研国策


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
    "new-media"
  ],
  "description": "| 樊纲观点 | 综研国策 | 综研观察 | 综研专访 | 综研视点 | 银湖新能源 |\n| -------- | -------- | -------- | -------- | -------- | ---------- |\n| 102      | 152      | 150      | 153      | 154      | 151        |",
  "example": "/cdi",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 82,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "id": "分类，见下表，默认为综研国策"
  },
  "path": "/:id?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "综研国策 - 国家高端智库/综合开发研究院 - Powered by RSSHub",
      "errorAt": "2025-12-25T11:11:36.802Z",
      "errorMessage": "[GET] \"http://www.cdi.com.cn/Article/List?ColumnId=152\": 404 Not Found\n",
      "id": "55135298544042027",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.cdi.com.cn/Article/List?ColumnId=152",
      "title": "综研国策 - 国家高端智库/综合开发研究院",
      "type": "feed",
      "url": "rsshub://cdi"
    },
    {
      "description": "综研观察 - 国家高端智库/综合开发研究院 - Powered by RSSHub",
      "errorAt": "2025-03-10T07:15:28.291Z",
      "errorMessage": "[GET] \"http://www.cdi.com.cn/Article/List?ColumnId=150\": 404 Not Found\n",
      "id": "65950460200200203",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.cdi.com.cn/Article/List?ColumnId=150",
      "title": "综研观察 - 国家高端智库/综合开发研究院",
      "type": "feed",
      "url": "rsshub://cdi/150"
    }
  ]
}
```
