# Bandcamp - Weekly

## Coverage
`index-only`

## Route
- Namespace: `bandcamp`
- Namespace Name: `Bandcamp`
- Route Path: `/bandcamp/weekly`
- Route Name: `Weekly`
- Example: `/bandcamp/weekly`
- URL: `bandcamp.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `weekly.tsx`
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
  - `bandcamp.com/`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/bandcamp/weekly",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 26,
  "location": "weekly.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Weekly",
  "parameters": {},
  "path": "/weekly",
  "radar": [
    {
      "source": [
        "bandcamp.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Bandcamp Weekly - Powered by RSSHub",
      "errorAt": "2026-08-05T23:45:56.184Z",
      "errorMessage": "Cannot read properties of undefined (reading 'slice')\n",
      "id": "56759431236675595",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bandcamp.com/",
      "title": "Bandcamp Weekly",
      "type": "feed",
      "url": "rsshub://bandcamp/weekly"
    }
  ],
  "url": "bandcamp.com/"
}
```
