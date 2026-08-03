# 深圳大学 - 研究生招生网

## Coverage
`index-only`

## Route
- Namespace: `szu`
- Namespace Name: `深圳大学`
- Route Path: `/szu/yz/:type?`
- Route Name: `研究生招生网`
- Example: `/szu/yz/1`
- URL: `yz.szu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `NagaruZ`
- Source Location: `yz/index.ts`
- Source Module: `_None_`

## Description
| 研究生 | 博士生 |
| ------ | ------ |
| 1      | 2      |

## Parameters
- `type`: 默认为 `1`


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
  "description": "| 研究生 | 博士生 |\n| ------ | ------ |\n| 1      | 2      |",
  "example": "/szu/yz/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "yz/index.ts",
  "maintainers": [
    "NagaruZ"
  ],
  "name": "研究生招生网",
  "parameters": {
    "type": "默认为 `1`"
  },
  "path": "/yz/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-09-24T12:25:49.253Z",
      "errorMessage": "Cannot read properties of null (reading '0')\n",
      "id": "193651466559953922",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://szu/yz/1"
    }
  ]
}
```
