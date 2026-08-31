# 12306 - 售票信息

## Coverage
`index-only`

## Route
- Namespace: `12306`
- Namespace Name: `12306`
- Route Path: `/12306/:date/:from/:to/:type?`
- Route Name: `售票信息`
- Example: `/12306/2022-02-19/重庆/永川东`
- URL: `kyfw.12306.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `Fatpandac`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `date`: 时间，格式为（YYYY-MM-DD）
- `from`: 始发站
- `to`: 终点站
- `type`: 售票类型，成人和学生可选，默认为成人


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
    "travel"
  ],
  "example": "/12306/2022-02-19/重庆/永川东",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "售票信息",
  "parameters": {
    "date": "时间，格式为（YYYY-MM-DD）",
    "from": "始发站",
    "to": "终点站",
    "type": "售票类型，成人和学生可选，默认为成人"
  },
  "path": "/:date/:from/:to/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
