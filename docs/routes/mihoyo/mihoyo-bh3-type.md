# 米哈游 - 崩坏 3 - 游戏公告

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/mihoyo/bh3/:type`
- Route Name: `崩坏 3 - 游戏公告`
- Example: `/mihoyo/bh3/latest`
- URL: `genshin.hoyoverse.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `deepred5, nczitzk`
- Source Location: `bh3.ts`
- Source Module: `_None_`

## Description
| 最新   | 新闻 | 公告   | 活动     | 资讯 |
| ------ | ---- | ------ | -------- | ---- |
| latest | news | notice | activity | info |

## Parameters
- `type`: 公告种类


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 最新   | 新闻 | 公告   | 活动     | 资讯 |\n| ------ | ---- | ------ | -------- | ---- |\n| latest | news | notice | activity | info |",
  "example": "/mihoyo/bh3/latest",
  "heat": 0,
  "location": "bh3.ts",
  "maintainers": [
    "deepred5",
    "nczitzk"
  ],
  "name": "崩坏 3 - 游戏公告",
  "parameters": {
    "type": "公告种类"
  },
  "path": "/bh3/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
