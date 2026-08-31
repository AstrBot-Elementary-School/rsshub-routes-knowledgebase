# Digg - Community Posts

## Coverage
`index-only`

## Route
- Namespace: `digg`
- Namespace Name: `Digg`
- Route Path: `/digg/community/:community`
- Route Name: `Community Posts`
- Example: `/digg/community/askdigg`
- URL: `digg.com/`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `community.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `community`: Community slug, can be found in the URL


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
  - `digg.com/:community`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/digg/community/askdigg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "community.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Community Posts",
  "parameters": {
    "community": "Community slug, can be found in the URL"
  },
  "path": "/community/:community",
  "radar": [
    {
      "source": [
        "digg.com/:community"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "digg.com/"
}
```
