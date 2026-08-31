# 前端早早聊 - 文章

## Coverage
`index-only`

## Route
- Namespace: `zaozao`
- Namespace Name: `前端早早聊`
- Route Path: `/zaozao/article/:type?`
- Route Name: `文章`
- Example: `/zaozao/article/quality`
- URL: `www.zaozao.run`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `shaomingbo`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
| 精品推荐  | 技术干货 | 职场成长 | 社区动态  | 组件物料 | 行业动态 |
| --------- | -------- | -------- | --------- | -------- | -------- |
| recommend | quality  | growth   | community | material | industry |

## Parameters
- `type`: 文章分类


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
  - `www.zaozao.run/article/:type`
- `target`: `/article/:type`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| 精品推荐  | 技术干货 | 职场成长 | 社区动态  | 组件物料 | 行业动态 |\n| --------- | -------- | -------- | --------- | -------- | -------- |\n| recommend | quality  | growth   | community | material | industry |",
  "example": "/zaozao/article/quality",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "article.ts",
  "maintainers": [
    "shaomingbo"
  ],
  "name": "文章",
  "parameters": {
    "type": "文章分类"
  },
  "path": "/article/:type?",
  "radar": [
    {
      "source": [
        "www.zaozao.run/article/:type"
      ],
      "target": "/article/:type"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-05-22T04:35:53.311Z",
      "errorMessage": "503 Service Unavailable\n",
      "id": "148190845698993152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://zaozao/article/quality"
    }
  ]
}
```
