# 链新闻 ABMedia - 类别

## Coverage
`index-only`

## Route
- Namespace: `abmedia`
- Namespace Name: `链新闻 ABMedia`
- Route Path: `/abmedia/:category?`
- Route Name: `类别`
- Example: `/abmedia/technology-development`
- URL: `www.abmedia.io`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Fatpandac`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
参数可以从链接中拿到，如：

`https://www.abmedia.io/category/technology-development` 对应 `/abmedia/technology-development`

## Parameters
- `category`: 类别，默认为产品技术


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
  - `www.abmedia.io/category/:catehory`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "参数可以从链接中拿到，如：\n\n`https://www.abmedia.io/category/technology-development` 对应 `/abmedia/technology-development`",
  "example": "/abmedia/technology-development",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "category.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "类别",
  "parameters": {
    "category": "类别，默认为产品技术"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.abmedia.io/category/:catehory"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
