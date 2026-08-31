# Mozilla - Firefox Monitor

## Coverage
`index-only`

## Route
- Namespace: `firefox`
- Namespace Name: `Mozilla`
- Route Path: `/firefox/breaches`
- Route Name: `Firefox Monitor`
- Example: `/firefox/breaches`
- URL: `monitor.firefox.com/`
- Language: `_None_`
- Categories: `other`
- Maintainers: `TonyRL`
- Source Location: `breaches.ts`
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
  - `monitor.firefox.com/`
  - `monitor.firefox.com/breaches`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/firefox/breaches",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "breaches.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Firefox Monitor",
  "parameters": {},
  "path": "/breaches",
  "radar": [
    {
      "source": [
        "monitor.firefox.com/",
        "monitor.firefox.com/breaches"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "monitor.firefox.com/"
}
```
