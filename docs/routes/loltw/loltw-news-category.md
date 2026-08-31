# 英雄联盟 - 台服新闻

## Coverage
`index-only`

## Route
- Namespace: `loltw`
- Namespace Name: `英雄联盟`
- Route Path: `/loltw/news/:category?`
- Route Name: `台服新闻`
- Example: `/loltw/news`
- URL: `lol.garena.tw`
- Language: `_None_`
- Categories: `game`
- Maintainers: `hoilc`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
| 活动  | 资讯 | 系统   | 电竞   | 版本资讯 | 战棋资讯 |
| ----- | ---- | ------ | ------ | -------- | -------- |
| event | info | system | esport | patch    | TFTpatch |

## Parameters
- `category`: 新闻分类，置空为全部新闻


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
    "game"
  ],
  "description": "| 活动  | 资讯 | 系统   | 电竞   | 版本资讯 | 战棋资讯 |\n| ----- | ---- | ------ | ------ | -------- | -------- |\n| event | info | system | esport | patch    | TFTpatch |",
  "example": "/loltw/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.tsx",
  "maintainers": [
    "hoilc"
  ],
  "name": "台服新闻",
  "parameters": {
    "category": "新闻分类，置空为全部新闻"
  },
  "path": "/news/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
