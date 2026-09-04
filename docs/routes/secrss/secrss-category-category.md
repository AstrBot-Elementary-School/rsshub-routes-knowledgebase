# 安全内参 - 分类

## Coverage
`index-only`

## Route
- Namespace: `secrss`
- Namespace Name: `安全内参`
- Route Path: `/secrss/category/:category?`
- Route Name: `分类`
- Example: `/secrss/category/产业趋势`
- URL: `secrss.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `XinRoom, SunBK201`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: N


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
    "programming"
  ],
  "example": "/secrss/category/产业趋势",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 246,
  "location": "category.ts",
  "maintainers": [
    "XinRoom",
    "SunBK201"
  ],
  "name": "分类",
  "parameters": {
    "category": "N"
  },
  "path": "/category/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "安全内参- - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56216388194039808",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.secrss.com/",
      "title": "安全内参-",
      "type": "feed",
      "url": "rsshub://secrss/category"
    },
    {
      "description": "安全内参-产业趋势 - Powered by RSSHub",
      "errorAt": "2025-03-26T04:39:26.148Z",
      "errorMessage": "Cannot read properties of undefined (reading 'map')\n",
      "id": "59424053436911616",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.secrss.com/",
      "title": "安全内参-产业趋势",
      "type": "feed",
      "url": "rsshub://secrss/category/%E4%BA%A7%E4%B8%9A%E8%B6%8B%E5%8A%BF"
    }
  ]
}
```
