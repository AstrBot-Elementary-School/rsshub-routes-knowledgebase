# Link3 - Link3 Events

## Coverage
`index-only`

## Route
- Namespace: `link3`
- Namespace Name: `Link3`
- Route Path: `/link3/events`
- Route Name: `Link3 Events`
- Example: `/link3/events`
- URL: `link3.to`
- Language: `_None_`
- Categories: `other`
- Maintainers: `cxheng315`
- Source Location: `events.ts`
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
  - `link3.to/events`
- `target`: `/events`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/link3/events",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "events.ts",
  "maintainers": [
    "cxheng315"
  ],
  "name": "Link3 Events",
  "path": "/events",
  "radar": [
    {
      "source": [
        "link3.to/events"
      ],
      "target": "/events"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "link3.to"
}
```
