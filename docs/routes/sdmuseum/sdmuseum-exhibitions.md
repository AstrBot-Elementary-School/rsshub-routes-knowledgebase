# Shan Dong Museum - Temporary Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `sdmuseum`
- Namespace Name: `Shan Dong Museum`
- Route Path: `/sdmuseum/exhibitions`
- Route Name: `Temporary Exhibitions`
- Example: `/sdmuseum/exhibitions`
- URL: `www.sdmuseum.com/`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `exhibitions.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.sdmuseum.com/col/col271702/index.html`
- `target`: `/exhibitions`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/sdmuseum/exhibitions",
  "heat": 0,
  "location": "exhibitions.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Temporary Exhibitions",
  "parameters": {},
  "path": "/exhibitions",
  "radar": [
    {
      "source": [
        "www.sdmuseum.com/col/col271702/index.html"
      ],
      "target": "/exhibitions"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at listOnTimeout (node:internal/timers:597:9)\n    at processTimers (node:internal/timers:571:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
