# 中国无线电协会业余无线电分会 - 最新资讯

## Coverage
`index-only`

## Route
- Namespace: `crac`
- Namespace Name: `中国无线电协会业余无线电分会`
- Route Path: `/crac/:type?`
- Route Name: `最新资讯`
- Example: `/crac/2`
- URL: `www.crac.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `Misaka13514`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 新闻动态 | 通知公告 | 政策法规 | 常见问题 | 资料下载 | English | 业余中继台 | 科普专栏 |
| -------- | -------- | -------- | -------- | -------- | ------- | ---------- | -------- |
| 1        | 2        | 3        | 5        | 6        | 7       | 8          | 9        |

## Parameters
- `type`: 类型，见下表，默认为全部


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
  - `www.crac.org.cn/News/*`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 新闻动态 | 通知公告 | 政策法规 | 常见问题 | 资料下载 | English | 业余中继台 | 科普专栏 |\n| -------- | -------- | -------- | -------- | -------- | ------- | ---------- | -------- |\n| 1        | 2        | 3        | 5        | 6        | 7       | 8          | 9        |",
  "example": "/crac/2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "index.ts",
  "maintainers": [
    "Misaka13514"
  ],
  "name": "最新资讯",
  "parameters": {
    "type": "类型，见下表，默认为全部"
  },
  "path": "/:type?",
  "radar": [
    {
      "source": [
        "www.crac.org.cn/News/*"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "通知公告-中国无线电协会业余无线电分会 - Powered by RSSHub",
      "errorAt": "2026-07-22T20:13:12.408Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "83759460466149376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.crac.org.cn/News/List?type=2",
      "title": "通知公告-中国无线电协会业余无线电分会",
      "type": "feed",
      "url": "rsshub://crac/2"
    },
    {
      "description": "业余中继台-中国无线电协会业余无线电分会 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82679004863584256",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.crac.org.cn/News/List?type=8",
      "title": "业余中继台-中国无线电协会业余无线电分会",
      "type": "feed",
      "url": "rsshub://crac/8"
    }
  ]
}
```
