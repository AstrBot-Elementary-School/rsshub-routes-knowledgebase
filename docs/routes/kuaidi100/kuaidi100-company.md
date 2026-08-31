# 快递 100 - 支持的快递公司列表

## Coverage
`index-only`

## Route
- Namespace: `kuaidi100`
- Namespace Name: `快递 100`
- Route Path: `/kuaidi100/company`
- Route Name: `支持的快递公司列表`
- Example: `/kuaidi100/company`
- URL: `kuaidi100.com/`
- Language: `_None_`
- Categories: `other`
- Maintainers: `NeverBehave`
- Source Location: `supported-company.ts`
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
  - `kuaidi100.com/`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/kuaidi100/company",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "supported-company.ts",
  "maintainers": [
    "NeverBehave"
  ],
  "name": "支持的快递公司列表",
  "parameters": {},
  "path": "/company",
  "radar": [
    {
      "source": [
        "kuaidi100.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "kuaidi100.com/"
}
```
