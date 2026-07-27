# EU Disinfo Lab - Publications

## Coverage
`index-only`

## Route
- Namespace: `disinfo`
- Namespace Name: `EU Disinfo Lab`
- Route Path: `/disinfo/publications`
- Route Name: `Publications`
- Example: `/disinfo/publications`
- URL: `disinfo.eu/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `publications.ts`
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
  - `disinfo.eu/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/disinfo/publications",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "publications.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Publications",
  "parameters": {},
  "path": "/publications",
  "radar": [
    {
      "source": [
        "disinfo.eu/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Publications - EU DisinfoLab - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73308935271149568",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.disinfo.eu/publications",
      "title": "Publications - EU DisinfoLab",
      "type": "feed",
      "url": "rsshub://disinfo/publications"
    }
  ],
  "url": "disinfo.eu/"
}
```
