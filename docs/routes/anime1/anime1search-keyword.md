# Anime1 - Search

## Coverage
`index-only`

## Route
- Namespace: `anime1`
- Namespace Name: `Anime1`
- Route Path: `/anime1search/:keyword`
- Route Name: `Search`
- Example: `/anime1/search/神之塔`
- URL: `anime1.me`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `cxheng315`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: Anime1 Search Keyword


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
    "anime"
  ],
  "example": "/anime1/search/神之塔",
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
    "cxheng315"
  ],
  "name": "Search",
  "parameters": {
    "keyword": "Anime1 Search Keyword"
  },
  "path": "search/:keyword",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 'RSSHub' not to be 'RSSHub' // Object.is equality\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:69:30)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "anime1.me"
}
```
