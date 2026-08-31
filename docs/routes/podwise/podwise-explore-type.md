# Podwise - Episodes

## Coverage
`index-only`

## Route
- Namespace: `podwise`
- Namespace Name: `Podwise`
- Route Path: `/podwise/explore/:type`
- Route Name: `Episodes`
- Example: `/podwise/explore/latest`
- URL: `podwise.ai`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `lyling`
- Source Location: `episodes.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: latest or all episodes.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `podwise.ai/explore/:type`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/podwise/explore/latest",
  "heat": 0,
  "location": "episodes.ts",
  "maintainers": [
    "lyling"
  ],
  "name": "Episodes",
  "parameters": {
    "type": "latest or all episodes."
  },
  "path": "/explore/:type",
  "radar": [
    {
      "source": [
        "podwise.ai/explore/:type"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
