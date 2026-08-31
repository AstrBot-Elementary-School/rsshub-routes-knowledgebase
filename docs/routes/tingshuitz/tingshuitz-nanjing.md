# 停水通知 - 南京市

## Coverage
`index-only`

## Route
- Namespace: `tingshuitz`
- Namespace Name: `停水通知`
- Route Path: `/tingshuitz/nanjing`
- Route Name: `南京市`
- Example: `/tingshuitz/nanjing`
- URL: `jlwater.com/portal/10000015`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `ocleo1, pseudoyu`
- Source Location: `nanjing.ts`
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
  - `jlwater.com/portal/10000015`
  - `jlwater.com/`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/tingshuitz/nanjing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "nanjing.ts",
  "maintainers": [
    "ocleo1",
    "pseudoyu"
  ],
  "name": "南京市",
  "parameters": {},
  "path": "/nanjing",
  "radar": [
    {
      "source": [
        "jlwater.com/portal/10000015",
        "jlwater.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "jlwater.com/portal/10000015"
}
```
