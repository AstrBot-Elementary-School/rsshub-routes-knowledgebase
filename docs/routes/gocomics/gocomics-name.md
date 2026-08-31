# GoComics - Comic Strips

## Coverage
`index-only`

## Route
- Namespace: `gocomics`
- Namespace Name: `GoComics`
- Route Path: `/gocomics/:name`
- Route Name: `Comic Strips`
- Example: `/gocomics/foxtrot`
- URL: `www.gocomics.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `stjohnjohnson`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: URL path of the strip on gocomics.com


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.gocomics.com/:name`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/gocomics/foxtrot",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "stjohnjohnson"
  ],
  "name": "Comic Strips",
  "parameters": {
    "name": "URL path of the strip on gocomics.com"
  },
  "path": "/:name",
  "radar": [
    {
      "source": [
        "www.gocomics.com/:name"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.gocomics.com"
}
```
