# Rockstar Games - 在线活动

## Coverage
`index-only`

## Route
- Namespace: `rockstargames`
- Namespace Name: `Rockstar Games`
- Route Path: `/rockstargames/socialclub/events/:game?`
- Route Name: `在线活动`
- Example: `/rockstargames/socialclub/events/GTAV`
- URL: `www.rockstargames.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `kookxiang`
- Source Location: `events.ts`
- Source Module: `_None_`

## Description
| 游戏代码 | 游戏名称     |
| -------- | ------------ |
| GTAV     | 侠盗猎车手 5 |
| RDR2     | 荒野大镖客 2 |

## Parameters
- `game`: 游戏代码（默认所有）


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
  "description": "| 游戏代码 | 游戏名称     |\n| -------- | ------------ |\n| GTAV     | 侠盗猎车手 5 |\n| RDR2     | 荒野大镖客 2 |",
  "example": "/rockstargames/socialclub/events/GTAV",
  "heat": 0,
  "location": "events.ts",
  "maintainers": [
    "kookxiang"
  ],
  "name": "在线活动",
  "parameters": {
    "game": "游戏代码（默认所有）"
  },
  "path": "/socialclub/events/:game?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ Array(1) ] to not include 'https://socialclub.rockstargames.com/…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
