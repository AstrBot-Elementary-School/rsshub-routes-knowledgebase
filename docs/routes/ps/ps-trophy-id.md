# PlayStation Store - PlayStation Network user trophy

## Coverage
`index-only`

## Route
- Namespace: `ps`
- Namespace Name: `PlayStation Store`
- Route Path: `/ps/trophy/:id`
- Route Name: `PlayStation Network user trophy`
- Example: `/ps/trophy/DIYgod_`
- URL: `www.playstation.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `DIYgod`
- Source Location: `trophy.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: User ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/ps/trophy/DIYgod_",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 36,
  "location": "trophy.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "PlayStation Network user trophy",
  "parameters": {
    "id": "User ID"
  },
  "path": "/trophy/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "DIYgod_ 的 PSN 奖杯 - Powered by RSSHub",
      "errorAt": "2024-10-23T01:28:06.858Z",
      "errorMessage": "[GET] \"https://psnprofiles.com/DIYgod_?order=last-trophy\": 403 Forbidden\n",
      "id": "65439345539341312",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://psnprofiles.com/DIYgod_/log",
      "title": "DIYgod_ 的 PSN 奖杯",
      "type": "feed",
      "url": "rsshub://ps/trophy/DIYgod_"
    },
    {
      "description": "raiuka 的 PSN 奖杯 - Powered by RSSHub",
      "errorAt": "2024-10-23T00:18:18.066Z",
      "errorMessage": "[GET] \"https://psnprofiles.com/raiuka?order=last-trophy\": 403 Forbidden\n",
      "id": "63467474622024704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://psnprofiles.com/raiuka/log",
      "title": "raiuka 的 PSN 奖杯",
      "type": "feed",
      "url": "rsshub://ps/trophy/raiuka"
    }
  ]
}
```
