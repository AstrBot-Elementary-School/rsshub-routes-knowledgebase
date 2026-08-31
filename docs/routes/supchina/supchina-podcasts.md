# SupChina - Podcasts

## Coverage
`index-only`

## Route
- Namespace: `supchina`
- Namespace Name: `SupChina`
- Route Path: `/supchina/podcasts`
- Route Name: `Podcasts`
- Example: `/supchina/podcasts`
- URL: `supchina.com/podcasts`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `podcasts.ts`
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
  - `supchina.com/podcasts`
  - `supchina.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/supchina/podcasts",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "podcasts.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Podcasts",
  "parameters": {},
  "path": "/podcasts",
  "radar": [
    {
      "source": [
        "supchina.com/podcasts",
        "supchina.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "supchina.com/podcasts"
}
```
