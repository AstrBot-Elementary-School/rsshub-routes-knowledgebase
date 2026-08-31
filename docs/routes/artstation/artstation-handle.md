# ArtStation - Artist Profolio

## Coverage
`index-only`

## Route
- Namespace: `artstation`
- Namespace Name: `ArtStation`
- Route Path: `/artstation/:handle`
- Route Name: `Artist Profolio`
- Example: `/artstation/wlop`
- URL: `www.artstation.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `handle`: Artist handle, can be found in URL


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
  - `www.artstation.com/:handle`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/artstation/wlop",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Artist Profolio",
  "parameters": {
    "handle": "Artist handle, can be found in URL"
  },
  "path": "/:handle",
  "radar": [
    {
      "source": [
        "www.artstation.com/:handle"
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
