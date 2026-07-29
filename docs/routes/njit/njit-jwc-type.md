# 南京工程学院 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `njit`
- Namespace Name: `南京工程学院`
- Route Path: `/njit/jwc/:type?`
- Route Name: `教务处`
- Example: `/njit/jwc/jx`
- URL: `jwc.njit.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `zefengdaguo`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 教学 | 考试 | 信息 | 实践 |
| ---- | ---- | ---- | ---- |
| jx   | ks   | xx   | sj   |

## Parameters
- `type`: 默认为 `jx`


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
    "university"
  ],
  "description": "| 教学 | 考试 | 信息 | 实践 |\n| ---- | ---- | ---- | ---- |\n| jx   | ks   | xx   | sj   |",
  "example": "/njit/jwc/jx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "zefengdaguo"
  ],
  "name": "教务处",
  "parameters": {
    "type": "默认为 `jx`"
  },
  "path": "/jwc/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at listOnTimeout (node:internal/timers:567:9)\n    at processTimers (node:internal/timers:541:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
