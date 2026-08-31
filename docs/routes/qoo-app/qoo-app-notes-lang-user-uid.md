# QooApp - User Notes

## Coverage
`index-only`

## Route
- Namespace: `qoo-app`
- Namespace Name: `QooApp`
- Route Path: `/qoo-app/notes/:lang?/user/:uid`
- Route Name: `User Notes`
- Example: `/qoo-app/notes/en/user/35399143`
- URL: `apps.qoo-app.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `notes/user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: Language, see the table above, empty means `中文`
- `uid`: User ID, can be found in URL


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
    "anime"
  ],
  "example": "/qoo-app/notes/en/user/35399143",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "notes/user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User Notes",
  "parameters": {
    "lang": "Language, see the table above, empty means `中文`",
    "uid": "User ID, can be found in URL"
  },
  "path": "/notes/:lang?/user/:uid",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
