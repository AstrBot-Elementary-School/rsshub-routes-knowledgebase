# Eventbrite - Events

## Coverage
`index-only`

## Route
- Namespace: `eventbrite`
- Namespace Name: `Eventbrite`
- Route Path: `/eventbrite/:region/:eventType?/:includePromoted?`
- Route Name: `Events`
- Example: `/eventbrite/canada--toronto/all-events`
- URL: `eventbrite.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `elibroftw`
- Source Location: `events.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `eventType`: category of events for filtering
- `region`: Region or scope of events


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
  - `eventbrite.com/d/:region/:eventType`
- `target`: `/:region/:eventType`
### Rule 2
- `source`:
  - `eventbrite.ca/d/:region/:eventType`
- `target`: `/:region/:eventType`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/eventbrite/canada--toronto/all-events",
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
    "elibroftw"
  ],
  "name": "Events",
  "parameters": {
    "eventType": "category of events for filtering",
    "region": "Region or scope of events"
  },
  "path": "/:region/:eventType?/:includePromoted?",
  "radar": [
    {
      "source": [
        "eventbrite.com/d/:region/:eventType"
      ],
      "target": "/:region/:eventType"
    },
    {
      "source": [
        "eventbrite.ca/d/:region/:eventType"
      ],
      "target": "/:region/:eventType"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
