# 多抓鱼 - 搜索结果

## Coverage
`index-only`

## Route
- Namespace: `duozhuayu`
- Namespace Name: `多抓鱼`
- Route Path: `/duozhuayu/search/:wd`
- Route Name: `搜索结果`
- Example: `/duozhuayu/search/JavaScript`
- URL: `duozhuayu.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `fengkx`
- Source Location: `search.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `wd`: 搜索关键词


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
  - `duozhuayu.com/search/book/:wd`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/duozhuayu/search/JavaScript",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "search.tsx",
  "maintainers": [
    "fengkx"
  ],
  "name": "搜索结果",
  "parameters": {
    "wd": "搜索关键词"
  },
  "path": "/search/:wd",
  "radar": [
    {
      "source": [
        "duozhuayu.com/search/book/:wd"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "多抓鱼搜索-e.g.JavaScript - Powered by RSSHub",
      "errorAt": "2026-04-10T11:02:40.690Z",
      "errorMessage": "[GET] \"https://www.duozhuayu.com/api/search/book?type=normal&q=e.g.JavaScript\": 401 Unauthorized\n",
      "id": "169279781328462848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.duozhuayu.com/search/book/e.g.JavaScript",
      "title": "多抓鱼搜索-e.g.JavaScript",
      "type": "feed",
      "url": "rsshub://duozhuayu/search/e.g.JavaScript"
    },
    {
      "description": "多抓鱼搜索-djryan - Powered by RSSHub",
      "errorAt": "2026-04-10T07:01:59.055Z",
      "errorMessage": "[GET] \"https://www.duozhuayu.com/api/search/book?type=normal&q=djryan\": 401 Unauthorized\n",
      "id": "182734632654007296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.duozhuayu.com/search/book/djryan",
      "title": "多抓鱼搜索-djryan",
      "type": "feed",
      "url": "rsshub://duozhuayu/search/djryan"
    }
  ]
}
```
