# ClickMe - 文章

## Coverage
`index-only`

## Route
- Namespace: `clickme`
- Namespace Name: `ClickMe`
- Route Path: `/clickme/:site/:grouping/:name`
- Route Name: `文章`
- Example: `/clickme/default/category/beauty`
- URL: `clickme.net`
- Language: `_None_`
- Categories: `other`
- Maintainers: `hoilc`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `site`: 站点，`default`为普通站，`r18`为成人站，其它值默认为普通站
- `grouping`: 分组方式，`category`为分类，`tag`为标签，其他值默认为分类
- `name`: 分类名或标签名，分类名为英文，可以在分类 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/clickme/default/category/beauty",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 43,
  "location": "index.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "文章",
  "parameters": {
    "grouping": "分组方式，`category`为分类，`tag`为标签，其他值默认为分类",
    "name": "分类名或标签名，分类名为英文，可以在分类 URL 中找到",
    "site": "站点，`default`为普通站，`r18`为成人站，其它值默认为普通站"
  },
  "path": "/:site/:grouping/:name",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "ClickMe R18 - 女優 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "154786575534138368",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://r18.clickme.net/c/av",
      "title": "ClickMe R18 - 女優",
      "type": "feed",
      "url": "rsshub://clickme/r18/category/av"
    },
    {
      "description": "ClickMe R18 - 最新 - Powered by RSSHub",
      "errorAt": "2026-08-01T08:00:39.443Z",
      "errorMessage": "[POST] \"https://api.clickme.net/article/list?key=clickme\": 404 Not Found\n",
      "id": "156717605498762240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://r18.clickme.net/c/new",
      "title": "ClickMe R18 - 最新",
      "type": "feed",
      "url": "rsshub://clickme/r18/category/new"
    }
  ]
}
```
