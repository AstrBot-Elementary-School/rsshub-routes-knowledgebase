# Sky Sports - News

## Coverage
`index-only`

## Route
- Namespace: `skysports`
- Namespace Name: `Sky Sports`
- Route Path: `/skysports/news/:team`
- Route Name: `News`
- Example: `/skysports/news/ac-milan`
- URL: `skysports.com`
- Language: `_None_`
- Categories: `sport`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `team`: Team id, can be found in URL to the team page


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
    "sport"
  ],
  "example": "/skysports/news/ac-milan",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "parameters": {
    "team": "Team id, can be found in URL to the team page"
  },
  "path": "/news/:team",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
