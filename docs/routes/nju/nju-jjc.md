# 南京大学 - 基建处

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/nju/jjc`
- Route Name: `基建处`
- Example: `/nju/jjc`
- URL: `jjc.nju.edu.cn/main.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ret-1`
- Source Location: `jjc.ts`
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
  - `jjc.nju.edu.cn/main.htm`
  - `jjc.nju.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/nju/jjc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jjc.ts",
  "maintainers": [
    "ret-1"
  ],
  "name": "基建处",
  "parameters": {},
  "path": "/jjc",
  "radar": [
    {
      "source": [
        "jjc.nju.edu.cn/main.htm",
        "jjc.nju.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "jjc.nju.edu.cn/main.htm"
}
```
