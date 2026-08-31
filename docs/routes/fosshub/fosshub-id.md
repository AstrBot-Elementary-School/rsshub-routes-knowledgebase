# FossHub - Software Update

## Coverage
`index-only`

## Route
- Namespace: `fosshub`
- Namespace Name: `FossHub`
- Route Path: `/fosshub/:id`
- Route Name: `Software Update`
- Example: `/fosshub/qBittorrent`
- URL: `fosshub.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Software id, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/fosshub/qBittorrent",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Software Update",
  "parameters": {
    "id": "Software id, can be found in URL"
  },
  "path": "/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
