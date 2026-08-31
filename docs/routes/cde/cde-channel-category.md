# 国家药品审评网站 - 首页

## Coverage
`index-only`

## Route
- Namespace: `cde`
- Namespace Name: `国家药品审评网站`
- Route Path: `/cde/:channel/:category`
- Route Name: `首页`
- Example: `/cde/news/gzdt`
- URL: `www.cde.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
- 频道

| 新闻中心 | 政策法规 |
| :------: | :------: |
|   news   |  policy  |

- 类别

| 新闻中心 | 政务新闻 | 要闻导读 | 图片新闻 | 工作动态 |
| :------: | :------: | :------: | :------: | :------: |
|          |   zwxw   |   ywdd   |   tpxw   |   gzdt   |

| 政策法规 | 法律法规 | 中心规章 |
| :------: | :------: | :------: |
|          |   flfg   |   zxgz   |

## Parameters
- `channel`: 频道
- `category`: 类别


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
    "government"
  ],
  "description": "- 频道\n\n| 新闻中心 | 政策法规 |\n| :------: | :------: |\n|   news   |  policy  |\n\n- 类别\n\n| 新闻中心 | 政务新闻 | 要闻导读 | 图片新闻 | 工作动态 |\n| :------: | :------: | :------: | :------: | :------: |\n|          |   zwxw   |   ywdd   |   tpxw   |   gzdt   |\n\n| 政策法规 | 法律法规 | 中心规章 |\n| :------: | :------: | :------: |\n|          |   flfg   |   zxgz   |",
  "example": "/cde/news/gzdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "首页",
  "parameters": {
    "category": "类别",
    "channel": "频道"
  },
  "path": "/:channel/:category",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-09-13T01:51:47.539Z",
      "errorMessage": "Cannot read properties of undefined (reading 'set-cookie')\n",
      "id": "189505746675782660",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://cde/policy/flfg"
    }
  ]
}
```
