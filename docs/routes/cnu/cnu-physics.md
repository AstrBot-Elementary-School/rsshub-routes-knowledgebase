# 首都师范大学 - 物理系院系新闻

## Coverage
`index-only`

## Route
- Namespace: `cnu`
- Namespace Name: `首都师范大学`
- Route Path: `/cnu/physics`
- Route Name: `物理系院系新闻`
- Example: `/cnu/physics`
- URL: `physics.cnu.edu.cn/news/index.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `liueic`
- Source Location: `physics.ts`
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
  - `physics.cnu.edu.cn/news/index.htm`
- `target`: `/cnu/physics`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cnu/physics",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "physics.ts",
  "maintainers": [
    "liueic"
  ],
  "name": "物理系院系新闻",
  "parameters": {},
  "path": "/physics",
  "radar": [
    {
      "source": [
        "physics.cnu.edu.cn/news/index.htm"
      ],
      "target": "/cnu/physics"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "physics.cnu.edu.cn/news/index.htm"
}
```
