# Bandcamp - Upcoming Live Streams

## Coverage
`index-only`

## Route
- Namespace: `bandcamp`
- Namespace Name: `Bandcamp`
- Route Path: `/bandcamp/live`
- Route Name: `Upcoming Live Streams`
- Example: `/bandcamp/live`
- URL: `bandcamp.com/live_schedule`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `live.ts`
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
  - `bandcamp.com/live_schedule`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/bandcamp/live",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "live.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Upcoming Live Streams",
  "parameters": {},
  "path": "/live",
  "radar": [
    {
      "source": [
        "bandcamp.com/live_schedule"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "bandcamp.com/live_schedule"
}
```
