# National Geographic - Daily Selection

## Coverage
`index-only`

## Route
- Namespace: `natgeo`
- Namespace Name: `National Geographic`
- Route Path: `/natgeo/dailyselection`
- Route Name: `Daily Selection`
- Example: `/natgeo/dailyselection`
- URL: `nationalgeographic.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `OrangeEd1t`
- Source Location: `dailyselection.ts`
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

## Radar
### Rule 1
- `source`:
  - `nationalgeographic.com/`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/natgeo/dailyselection",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false
  },
  "heat": 0,
  "location": "dailyselection.ts",
  "maintainers": [
    "OrangeEd1t"
  ],
  "name": "Daily Selection",
  "parameters": {},
  "path": "/dailyselection",
  "radar": [
    {
      "source": [
        "nationalgeographic.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "view": 2
}
```
