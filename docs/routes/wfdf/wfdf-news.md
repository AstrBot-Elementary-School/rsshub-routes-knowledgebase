# WFDF - News

## Coverage
`index-only`

## Route
- Namespace: `wfdf`
- Namespace Name: `WFDF`
- Route Path: `/wfdf/news`
- Route Name: `News`
- Example: `/wfdf/news`
- URL: `wfdf.sport/news/`
- Language: `_None_`
- Categories: `sport`
- Maintainers: `HankChow`
- Source Location: `news.ts`
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
  - `wfdf.sport/news/`
  - `wfdf.sport/`

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "example": "/wfdf/news",
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
    "HankChow"
  ],
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "wfdf.sport/news/",
        "wfdf.sport/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "wfdf.sport/news/"
}
```
