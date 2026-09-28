# Henan Museum - Special Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `chnmus`
- Namespace Name: `Henan Museum`
- Route Path: `/chnmus/information/exhibition/:type?`
- Route Name: `Special Exhibitions`
- Example: `/chnmus/information/exhibition/special`
- URL: `www.chnmus.net`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `exhibition.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type, supported values: special（特展详情）. Default: All.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.chnmus.net/ch/information/exhibition/index.html`
- `target`: `/information/exhibition`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/chnmus/information/exhibition/special",
  "heat": 0,
  "location": "exhibition.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Special Exhibitions",
  "parameters": {
    "type": "Exhibition type, supported values: special（特展详情）. Default: All."
  },
  "path": "/information/exhibition/:type?",
  "radar": [
    {
      "source": [
        "www.chnmus.net/ch/information/exhibition/index.html"
      ],
      "target": "/information/exhibition"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
