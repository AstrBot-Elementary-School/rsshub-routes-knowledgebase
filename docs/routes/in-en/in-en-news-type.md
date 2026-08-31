# 国际能源网 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `in-en`
- Namespace Name: `国际能源网`
- Route Path: `/in-en/news/:type`
- Route Name: `新闻`
- Example: `/in-en/news/solar`
- URL: `www.in-en.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Harviewang`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 频道       | type 参数 |
| ---------- | --------- |
| 光伏太阳能 | solar     |
| 风电       | wind      |
| 储能       | chuneng   |
| 氢能       | h2        |
| 充换电     | chd       |
| 新能源综合 | newenergy |
| 电力       | power     |
| 环保       | huanbao   |

## Parameters
- `type`: Channel type, see table below


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
    "new-media"
  ],
  "description": "| 频道       | type 参数 |\n| ---------- | --------- |\n| 光伏太阳能 | solar     |\n| 风电       | wind      |\n| 储能       | chuneng   |\n| 氢能       | h2        |\n| 充换电     | chd       |\n| 新能源综合 | newenergy |\n| 电力       | power     |\n| 环保       | huanbao   |",
  "example": "/in-en/news/solar",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "Harviewang"
  ],
  "name": "新闻",
  "parameters": {
    "type": "Channel type, see table below"
  },
  "path": "/news/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
