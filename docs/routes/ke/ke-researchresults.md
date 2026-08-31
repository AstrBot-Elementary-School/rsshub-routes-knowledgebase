# 贝壳研究院 - 研究成果

## Coverage
`index-only`

## Route
- Namespace: `ke`
- Namespace Name: `贝壳研究院`
- Route Path: `/ke/researchResults`
- Route Name: `研究成果`
- Example: `/ke/researchResults`
- URL: `www.research.ke.com/researchResults`
- Language: `_None_`
- Categories: `other`
- Maintainers: `shaomingbo`
- Source Location: `results.ts`
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
  - `www.research.ke.com/researchResults`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/ke/researchResults",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "results.ts",
  "maintainers": [
    "shaomingbo"
  ],
  "name": "研究成果",
  "parameters": {},
  "path": "/researchResults",
  "radar": [
    {
      "source": [
        "www.research.ke.com/researchResults"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-19T04:04:26.773Z",
      "errorMessage": "503 \n",
      "id": "158366990849381376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://ke/researchResults"
    }
  ],
  "url": "www.research.ke.com/researchResults"
}
```
