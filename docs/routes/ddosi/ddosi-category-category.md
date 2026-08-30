# 雨苁博客 - 分类

## Coverage
`index-only`

## Route
- Namespace: `ddosi`
- Namespace Name: `雨苁博客`
- Route Path: `/ddosi/category/:category?`
- Route Name: `分类`
- Example: `/ddosi/category/黑客工具`
- URL: `ddosi.org/`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `XinRoom`
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
### Rule 1
- `source`:
  - `ddosi.org/category/:category/`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/ddosi/category/黑客工具",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 40,
  "location": "category.ts",
  "maintainers": [
    "XinRoom"
  ],
  "name": "分类",
  "parameters": {
    "category": "N"
  },
  "path": "/category/:category?",
  "radar": [
    {
      "source": [
        "ddosi.org/category/:category/"
      ],
      "target": "/category/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "雨苁-黑客工具 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70734921116407808",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ddosi.org/category/%E9%BB%91%E5%AE%A2%E5%B7%A5%E5%85%B7/",
      "title": "雨苁-黑客工具",
      "type": "feed",
      "url": "rsshub://ddosi/category/%E9%BB%91%E5%AE%A2%E5%B7%A5%E5%85%B7"
    },
    {
      "description": "雨苁-渗透测试 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70735449588062208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ddosi.org/category/%E6%B8%97%E9%80%8F%E6%B5%8B%E8%AF%95/",
      "title": "雨苁-渗透测试",
      "type": "feed",
      "url": "rsshub://ddosi/category/%E6%B8%97%E9%80%8F%E6%B5%8B%E8%AF%95"
    }
  ],
  "url": "ddosi.org/"
}
```
