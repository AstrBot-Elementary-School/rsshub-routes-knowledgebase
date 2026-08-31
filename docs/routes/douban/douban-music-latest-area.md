# 豆瓣 - 最新增加的音乐

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/music/latest/:area?`
- Route Name: `最新增加的音乐`
- Example: `/douban/music/latest/chinese`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `fengkx, xyqfer`
- Source Location: `other/latest-music.ts`
- Source Module: `_None_`

## Description
| 华语    | 欧美    | 日韩        |
| ------- | ------- | ----------- |
| chinese | western | japankorean |

## Parameters
- `area`: 区域类型，默认全部


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
    "social-media"
  ],
  "description": "| 华语    | 欧美    | 日韩        |\n| ------- | ------- | ----------- |\n| chinese | western | japankorean |",
  "example": "/douban/music/latest/chinese",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "other/latest-music.ts",
  "maintainers": [
    "fengkx",
    "xyqfer"
  ],
  "name": "最新增加的音乐",
  "parameters": {
    "area": "区域类型，默认全部"
  },
  "path": "/music/latest/:area?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "豆瓣最新增加的音乐 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "155012285947975680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://music.douban.com/latest",
      "title": "豆瓣最新增加的音乐",
      "type": "feed",
      "url": "rsshub://douban/music/latest"
    },
    {
      "description": null,
      "errorAt": "2025-07-29T07:17:23.141Z",
      "errorMessage": "Cannot read properties of null (reading 'value')\n",
      "id": "172916789107213316",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://douban/music/latest/chinese"
    }
  ]
}
```
