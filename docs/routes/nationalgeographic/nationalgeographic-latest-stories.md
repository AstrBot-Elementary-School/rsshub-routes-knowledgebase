# National Geographic - Latest Stories

## Coverage
`index-only`

## Route
- Namespace: `nationalgeographic`
- Namespace Name: `National Geographic`
- Route Path: `/nationalgeographic/latest-stories`
- Route Name: `Latest Stories`
- Example: `/nationalgeographic/latest-stories`
- URL: `www.nationalgeographic.com/pages/topic/latest-stories`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `miles170`
- Source Location: `latest-stories.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `www.nationalgeographic.com/pages/topic/latest-stories`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/nationalgeographic/latest-stories",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 150,
  "location": "latest-stories.tsx",
  "maintainers": [
    "miles170"
  ],
  "name": "Latest Stories",
  "parameters": {},
  "path": "/latest-stories",
  "radar": [
    {
      "source": [
        "www.nationalgeographic.com/pages/topic/latest-stories"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 567293586415 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Latest Stories - Powered by RSSHub",
      "errorAt": "2026-07-24T04:15:54.516Z",
      "errorMessage": "Authentication failed. Access denied.\n/nationalgeographic/latest-stories\n502 \nFailed to fetch\n",
      "id": "47544732473072640",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nationalgeographic.com/pages/topic/latest-stories",
      "title": "Latest Stories",
      "type": "feed",
      "url": "rsshub://nationalgeographic/latest-stories"
    }
  ],
  "url": "www.nationalgeographic.com/pages/topic/latest-stories"
}
```
