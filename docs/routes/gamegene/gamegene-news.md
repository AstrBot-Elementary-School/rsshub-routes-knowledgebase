# 游戏基因 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `gamegene`
- Namespace Name: `游戏基因`
- Route Path: `/gamegene/news`
- Route Name: `资讯`
- Example: `/gamegene/news`
- URL: `news.gamegene.cn/news`
- Language: `_None_`
- Categories: `game`
- Maintainers: `lone1y-51`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `news.gamegene.cn/news`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/gamegene/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "lone1y-51"
  ],
  "name": "资讯",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "news.gamegene.cn/news"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "news.gamegene.cn/news"
}
```
