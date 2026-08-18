# 不太灵影视 - 最新资源列表

## Coverage
`index-only`

## Route
- Namespace: `bt0`
- Namespace Name: `不太灵影视`
- Route Path: `/bt0/tlist/:sc/:domain?`
- Route Name: `最新资源列表`
- Example: `/bt0/tlist/1`
- URL: `2bt0.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `miemieYaho`
- Source Location: `tlist.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `sc`: 分类(1-5), 1:电影, 2:电视剧, 3:近日热门, 4:本周热门, 5:本月热门
- `domain`: 数字1-9, 比如1表示请求域名为 1bt0.com, 默认为 2


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `2bt0.com/tlist/`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/bt0/tlist/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 81,
  "location": "tlist.ts",
  "maintainers": [
    "miemieYaho"
  ],
  "name": "最新资源列表",
  "parameters": {
    "domain": "数字1-9, 比如1表示请求域名为 1bt0.com, 默认为 2",
    "sc": "分类(1-5), 1:电影, 2:电视剧, 3:近日热门, 4:本周热门, 5:本月热门"
  },
  "path": "/tlist/:sc/:domain?",
  "radar": [
    {
      "source": [
        "2bt0.com/tlist/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "不太灵-最新资源列表-电影 - Powered by RSSHub",
      "errorAt": "2025-02-09T15:45:47.426Z",
      "errorMessage": "api error\n",
      "id": "66737530237513732",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.2bt0.com/tlist/1_1.html",
      "title": "不太灵-最新资源列表-电影",
      "type": "feed",
      "url": "rsshub://bt0/tlist/1"
    },
    {
      "description": "不太灵-最新资源列表-近日热门 - Powered by RSSHub",
      "errorAt": "2025-02-09T16:19:02.013Z",
      "errorMessage": "api error\napi error\napi error\n",
      "id": "68593706262930432",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.2bt0.com/tlist/3_1.html",
      "title": "不太灵-最新资源列表-近日热门",
      "type": "feed",
      "url": "rsshub://bt0/tlist/3"
    }
  ]
}
```
