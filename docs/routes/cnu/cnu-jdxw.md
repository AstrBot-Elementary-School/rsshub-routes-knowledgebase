# 首都师范大学 - 焦点关注

## Coverage
`index-only`

## Route
- Namespace: `cnu`
- Namespace Name: `首都师范大学`
- Route Path: `/cnu/jdxw`
- Route Name: `焦点关注`
- Example: `/cnu/jdxw`
- URL: `news.cnu.edu.cn/xysx/jdxw/index.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `liueic`
- Source Location: `jdxw.ts`
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
  - `news.cnu.edu.cn/xysx/jdxw/index.htm`
- `target`: `/cnu/jdxw`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cnu/jdxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jdxw.ts",
  "maintainers": [
    "liueic"
  ],
  "name": "焦点关注",
  "parameters": {},
  "path": "/jdxw",
  "radar": [
    {
      "source": [
        "news.cnu.edu.cn/xysx/jdxw/index.htm"
      ],
      "target": "/cnu/jdxw"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "news.cnu.edu.cn/xysx/jdxw/index.htm"
}
```
