# 财联社 - 深度

## Coverage
`index-only`

## Route
- Namespace: `cls`
- Namespace Name: `财联社`
- Route Path: `/cls/depth/:category?`
- Route Name: `深度`
- Example: `/cls/depth/1000`
- URL: `cls.cn`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `nczitzk`
- Source Location: `depth.ts`
- Source Module: `_None_`

## Description
| 头条 | 股市 | 港股 | 环球 | 公司 | 券商 | 基金 | 地产 | 金融 | 汽车 | 科创 | 创业版 | 品见 | 期货 | 投教 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ | ---- | ---- | ---- |
| 1000 | 1003 | 1135 | 1007 | 1005 | 1118 | 1110 | 1006 | 1032 | 1119 | 1111 | 1127   | 1160 | 1124 | 1176 |

## Parameters
- `category`: 分类代码，可在首页导航栏的目标网址 URL 中找到


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
    "finance",
    "popular"
  ],
  "description": "| 头条 | 股市 | 港股 | 环球 | 公司 | 券商 | 基金 | 地产 | 金融 | 汽车 | 科创 | 创业版 | 品见 | 期货 | 投教 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ | ---- | ---- | ---- |\n| 1000 | 1003 | 1135 | 1007 | 1005 | 1118 | 1110 | 1006 | 1032 | 1119 | 1111 | 1127   | 1160 | 1124 | 1176 |",
  "example": "/cls/depth/1000",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3644,
  "location": "depth.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "深度",
  "parameters": {
    "category": "分类代码，可在首页导航栏的目标网址 URL 中找到"
  },
  "path": "/depth/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "财联社 - 头条 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55126637721518105",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cls.cn/depth?id=1000",
      "title": "财联社 - 头条",
      "type": "feed",
      "url": "rsshub://cls/depth/1000"
    },
    {
      "description": "财联社 - 头条 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84970828729518080",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cls.cn/depth?id=1000",
      "title": "财联社 - 头条",
      "type": "feed",
      "url": "rsshub://cls/depth"
    }
  ]
}
```
