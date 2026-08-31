# Evri - Parcel Tracking

## Coverage
`index-only`

## Route
- Namespace: `evri`
- Namespace Name: `Evri`
- Route Path: `/evri/:tracking`
- Route Name: `Parcel Tracking`
- Example: `/evri/H04AQA0004726589`
- URL: `www.evri.com/track-a-parcel`
- Language: `_None_`
- Categories: `other`
- Maintainers: `HenryQW`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tracking`: Tracking number


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.evri.com/track/parcel/:tracking/details`
- `target`: `/:tracking`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/evri/H04AQA0004726589",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "Parcel Tracking",
  "parameters": {
    "tracking": "Tracking number"
  },
  "path": "/:tracking",
  "radar": [
    {
      "source": [
        "www.evri.com/track/parcel/:tracking/details"
      ],
      "target": "/:tracking"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.evri.com/track-a-parcel"
}
```
