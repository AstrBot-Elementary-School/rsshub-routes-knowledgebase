# 創新拿鐵 - 分类

## Coverage
`index-only`

## Route
- Namespace: `startuplatte`
- Namespace Name: `創新拿鐵`
- Route Path: `/startuplatte/:category?`
- Route Name: `分类`
- Example: `/startuplatte`
- URL: `startuplatte.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 首頁 | 大師智慧 | 深度分析 | 新知介紹 |
| ---- | -------- | -------- | -------- |
|      | quote    | analysis | trend    |

## Parameters
- `category`: 分类，见下表，默认为首頁


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
  - `startuplatte.com/category/:category`
  - `startuplatte.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 首頁 | 大師智慧 | 深度分析 | 新知介紹 |\n| ---- | -------- | -------- | -------- |\n|      | quote    | analysis | trend    |",
  "example": "/startuplatte",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 53,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为首頁"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "startuplatte.com/category/:category",
        "startuplatte.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "創新拿鐵 - Powered by RSSHub",
      "errorAt": "2026-02-21T11:08:57.570Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "61252688943239172",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://startuplatte.com/",
      "title": "創新拿鐵",
      "type": "feed",
      "url": "rsshub://startuplatte"
    },
    {
      "description": "大師智慧 | 創新拿鐵 - Powered by RSSHub",
      "errorAt": "2026-02-21T06:41:32.058Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "81622319635482624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://startuplatte.com/category/quote",
      "title": "大師智慧 | 創新拿鐵",
      "type": "feed",
      "url": "rsshub://startuplatte/quote"
    }
  ]
}
```
