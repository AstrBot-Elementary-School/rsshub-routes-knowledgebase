# Liaoning Provincial Museum - Temporary Exhibition

## Coverage
`index-only`

## Route
- Namespace: `lnmuseum`
- Namespace Name: `Liaoning Provincial Museum`
- Route Path: `/lnmuseum/exhibition/temporary/:type?`
- Route Name: `Temporary Exhibition`
- Example: `/lnmuseum/exhibition/temporary/now`
- URL: `www.lnmuseum.com.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `temporary.tsx`
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
  - `www.lnmuseum.com.cn`
- `target`: `/exhibition/temporary`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/lnmuseum/exhibition/temporary/now",
  "heat": 0,
  "location": "temporary.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Temporary Exhibition",
  "path": "/exhibition/temporary/:type?",
  "radar": [
    {
      "source": [
        "www.lnmuseum.com.cn"
      ],
      "target": "/exhibition/temporary"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at processImmediate (node:internal/timers:472:9)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
