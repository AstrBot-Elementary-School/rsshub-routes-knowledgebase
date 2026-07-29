# Netflix - Research

## Coverage
`index-only`

## Route
- Namespace: `netflix`
- Namespace Name: `Netflix`
- Route Path: `/netflix/research`
- Route Name: `Research`
- Example: `/netflix/research`
- URL: `research.netflix.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `research.ts`
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
  - `research.netflix.com/archive`
  - `research.netflix.com`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/netflix/research",
  "heat": 0,
  "location": "research.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Research",
  "path": "/research",
  "radar": [
    {
      "source": [
        "research.netflix.com/archive",
        "research.netflix.com"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 311193232853 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "research.netflix.com/"
}
```
