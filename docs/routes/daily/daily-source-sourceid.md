# Daily.dev - Source Posts

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/daily/source/:sourceId`
- Route Name: `Source Posts`
- Example: `/daily/source/hn`
- URL: `app.daily.dev`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `source.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `sourceId`: The source id


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `app.daily.dev/sources/:sourceId`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/daily/source/hn",
  "heat": 0,
  "location": "source.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Source Posts",
  "parameters": {
    "sourceId": "The source id"
  },
  "path": "/source/:sourceId",
  "radar": [
    {
      "source": [
        "app.daily.dev/sources/:sourceId"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "app.daily.dev"
}
```
