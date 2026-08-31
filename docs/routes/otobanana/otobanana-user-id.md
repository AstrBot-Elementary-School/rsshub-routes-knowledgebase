# OTOBANANA - Timeline タイムライン

## Coverage
`index-only`

## Route
- Namespace: `otobanana`
- Namespace Name: `OTOBANANA`
- Route Path: `/otobanana/user/:id`
- Route Name: `Timeline タイムライン`
- Example: `/otobanana/user/cee16401-96b1-420f-8188-abd4d33093f1`
- URL: `otobanana.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `timeline.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: User ID, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `otobanana.com/user/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/otobanana/user/cee16401-96b1-420f-8188-abd4d33093f1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "timeline.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Timeline タイムライン",
  "parameters": {
    "id": "User ID, can be found in URL"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "otobanana.com/user/:id"
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
