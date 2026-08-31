# Comics Kingdom - Archive

## Coverage
`index-only`

## Route
- Namespace: `comicskingdom`
- Namespace Name: `Comics Kingdom`
- Route Path: `/comicskingdom/:name`
- Route Name: `Archive`
- Example: `/comicskingdom/pardon-my-planet`
- URL: `comicskingdom.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `stjohnjohnson`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: URL path of the strip on comicskingdom.com


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
  - `comicskingdom.com/:name/*`
  - `comicskingdom.com/:name`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/comicskingdom/pardon-my-planet",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.tsx",
  "maintainers": [
    "stjohnjohnson"
  ],
  "name": "Archive",
  "parameters": {
    "name": "URL path of the strip on comicskingdom.com"
  },
  "path": "/:name",
  "radar": [
    {
      "source": [
        "comicskingdom.com/:name/*",
        "comicskingdom.com/:name"
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
