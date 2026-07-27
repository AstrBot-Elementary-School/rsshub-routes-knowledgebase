# Capital Museum - Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `capitalmuseum`
- Namespace Name: `Capital Museum`
- Route Path: `/capitalmuseum/exhibition/:type?`
- Route Name: `Exhibitions`
- Example: `/capitalmuseum/exhibition`
- URL: `www.capitalmuseum.org.cn/`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `exhibition.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type, supported values: new(最新展览), review(展览回顾), default: All exhibitions.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.capitalmuseum.org.cn/exhibition`
- `target`: `/exhibition`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/capitalmuseum/exhibition",
  "heat": 0,
  "location": "exhibition.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Exhibitions",
  "parameters": {
    "type": "Exhibition type, supported values: new(最新展览), review(展览回顾), default: All exhibitions."
  },
  "path": "/exhibition/:type?",
  "radar": [
    {
      "source": [
        "www.capitalmuseum.org.cn/exhibition"
      ],
      "target": "/exhibition"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 311764603311 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
