# 掌上查询助手 - 95598 停电查询网

## Coverage
`index-only`

## Route
- Namespace: `sttcq`
- Namespace Name: `掌上查询助手`
- Route Path: `/sttcq/:province/:city/:district?`
- Route Name: `95598 停电查询网`
- Example: `/sttcq/hb1/wh/wc`
- URL: `www.sttcq.com`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `mjysci`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `province`: 省，2~3位拼音缩写，详情见 https://www.sttcq.com/td/
- `city`: 市，同上
- `district`: 区，同上


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.sttcq.com/td/:province/:city/:district/`
  - `www.sttcq.com/td/:province/:city/`
  - `www.sttcq.com/td/:province/`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/sttcq/hb1/wh/wc",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "mjysci"
  ],
  "name": "95598 停电查询网",
  "parameters": {
    "city": "市，同上",
    "district": "区，同上",
    "province": "省，2~3位拼音缩写，详情见 https://www.sttcq.com/td/"
  },
  "path": "/:province/:city/:district?",
  "radar": [
    {
      "source": [
        "www.sttcq.com/td/:province/:city/:district/",
        "www.sttcq.com/td/:province/:city/",
        "www.sttcq.com/td/:province/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
