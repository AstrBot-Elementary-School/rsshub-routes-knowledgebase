# Link3 - Link3 Profile

## Coverage
`index-only`

## Route
- Namespace: `link3`
- Namespace Name: `Link3`
- Route Path: `/link3/profile/:handle`
- Route Name: `Link3 Profile`
- Example: `/link3/profile/synfutures_defi`
- URL: `link3.to`
- Language: `_None_`
- Categories: `other`
- Maintainers: `cxheng315`
- Source Location: `profile.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `handle`: Profile handle


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
  - `link3.to/:handle`
- `target`: `/:handle`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/link3/profile/synfutures_defi",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "profile.ts",
  "maintainers": [
    "cxheng315"
  ],
  "name": "Link3 Profile",
  "parameters": {
    "handle": "Profile handle"
  },
  "path": "/profile/:handle",
  "radar": [
    {
      "source": [
        "link3.to/:handle"
      ],
      "target": "/:handle"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "link3.to"
}
```
