# Rattibha - User Threads

## Coverage
`index-only`

## Route
- Namespace: `rattibha`
- Namespace Name: `Rattibha`
- Route Path: `/rattibha/user/:user`
- Route Name: `User Threads`
- Example: `/rattibha/user/elonmusk`
- URL: `rattibha.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `yshalsager`
- Source Location: `user.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: Twitter username, without @


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
  - `rattibha.com/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/rattibha/user/elonmusk",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "user.tsx",
  "maintainers": [
    "yshalsager"
  ],
  "name": "User Threads",
  "parameters": {
    "user": "Twitter username, without @"
  },
  "path": "/user/:user",
  "radar": [
    {
      "source": [
        "rattibha.com/:user"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "سلاسل تغريدات elonmusk - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "147096924904794112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://rattibha.com/elonmusk",
      "title": "سلاسل تغريدات elonmusk",
      "type": "feed",
      "url": "rsshub://rattibha/user/elonmusk"
    }
  ]
}
```
