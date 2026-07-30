# Product Hunt - Top Products Launching Today

## Coverage
`index-only`

## Route
- Namespace: `producthunt`
- Namespace Name: `Product Hunt`
- Route Path: `/producthunt/today`
- Route Name: `Top Products Launching Today`
- Example: `/producthunt/today`
- URL: `www.producthunt.com/`
- Language: `_None_`
- Categories: `other`
- Maintainers: `miaoyafeng, Fatpandac`
- Source Location: `today.tsx`
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
  - `www.producthunt.com/`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/producthunt/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 203,
  "location": "today.tsx",
  "maintainers": [
    "miaoyafeng",
    "Fatpandac"
  ],
  "name": "Top Products Launching Today",
  "path": "/today",
  "radar": [
    {
      "source": [
        "www.producthunt.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Product Hunt Today Popular - Powered by RSSHub",
      "errorAt": "2025-10-28T05:52:00.116Z",
      "errorMessage": "Authentication failed. Access denied.\n/producthunt/today\n[GET] \"https://www.producthunt.com/\": 403 \nCannot read properties of undefined (reading 'post')\n[GET] \"https://www.producthunt.com/\": 403 Forbidden\n",
      "id": "41369544201246720",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.producthunt.com/",
      "title": "Product Hunt Today Popular",
      "type": "feed",
      "url": "rsshub://producthunt/today"
    }
  ],
  "url": "www.producthunt.com/"
}
```
