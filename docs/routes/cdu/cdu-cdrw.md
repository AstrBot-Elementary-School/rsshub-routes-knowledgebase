# 成都大学 - 成大人物

## Coverage
`index-only`

## Route
- Namespace: `cdu`
- Namespace Name: `成都大学`
- Route Path: `/cdu/cdrw`
- Route Name: `成大人物`
- Example: `/cdu/cdrw`
- URL: `news.cdu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `uuwor`
- Source Location: `cdrw.ts`
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
  - `news.cdu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cdu/cdrw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "cdrw.ts",
  "maintainers": [
    "uuwor"
  ],
  "name": "成大人物",
  "parameters": {},
  "path": "/cdrw",
  "radar": [
    {
      "source": [
        "news.cdu.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "news.cdu.edu.cn/"
}
```
