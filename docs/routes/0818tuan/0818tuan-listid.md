# 0818 团 - 分类

## Coverage
`index-only`

## Route
- Namespace: `0818tuan`
- Namespace Name: `0818 团`
- Route Path: `/0818tuan/:listId?`
- Route Name: `分类`
- Example: `/0818tuan`
- URL: `0818tuan.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 最新线报 | 实测活动 | 优惠券 |
| -------- | -------- | ------ |
| 1        | 2        | 3      |

## Parameters
- `listId`: 活动分类，见下表，默认为 `1`


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
    "shopping"
  ],
  "description": "| 最新线报 | 实测活动 | 优惠券 |\n| -------- | -------- | ------ |\n| 1        | 2        | 3      |",
  "example": "/0818tuan",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 600,
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "分类",
  "parameters": {
    "listId": "活动分类，见下表，默认为 `1`"
  },
  "path": "/:listId?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "最新线报活动-最新线报活动/教程攻略-0818团 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65670452855599106",
      "image": "http://www.0818tuan.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "http://www.0818tuan.com/list-1-0.html",
      "title": "最新线报活动-最新线报活动/教程攻略-0818团",
      "type": "feed",
      "url": "rsshub://0818tuan/1"
    },
    {
      "description": "最新线报活动-最新线报活动/教程攻略-0818团 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61413843131719680",
      "image": "http://www.0818tuan.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "http://www.0818tuan.com/list-1-0.html",
      "title": "最新线报活动-最新线报活动/教程攻略-0818团",
      "type": "feed",
      "url": "rsshub://0818tuan"
    }
  ]
}
```
