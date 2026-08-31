# Telecompaper - Search

## Coverage
`index-only`

## Route
- Namespace: `telecompaper`
- Namespace Name: `Telecompaper`
- Route Path: `/telecompaper/search/:keyword?/:company?/:sort?/:period?`
- Route Name: `Search`
- Example: `/telecompaper/search/Nokia`
- URL: `telecompaper.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
Sorting

| Date Ascending | Date Descending |
| -------------- | --------------- |
| 1              | 2               |

Date selection

| 1 month | 3 months | 6 months | 12 months | 24 months |
| ------- | -------- | -------- | --------- | --------- |
| 1       | 3        | 6        | 12        | 24        |

## Parameters
- `keyword`: Keyword
- `company`: Company name, empty by default
- `sort`: Sorting, see table below, `Date Descending` by default
- `period`: Date selection, Last 12 months by default


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
    "journal"
  ],
  "description": "Sorting\n\n| Date Ascending | Date Descending |\n| -------------- | --------------- |\n| 1              | 2               |\n\nDate selection\n\n| 1 month | 3 months | 6 months | 12 months | 24 months |\n| ------- | -------- | -------- | --------- | --------- |\n| 1       | 3        | 6        | 12        | 24        |",
  "example": "/telecompaper/search/Nokia",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "search.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Search",
  "parameters": {
    "company": "Company name, empty by default",
    "keyword": "Keyword",
    "period": "Date selection, Last 12 months by default",
    "sort": "Sorting, see table below, `Date Descending` by default"
  },
  "path": "/search/:keyword?/:company?/:sort?/:period?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
