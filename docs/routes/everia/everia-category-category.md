# EVERIA.CLUB - Images with category

## Coverage
`index-only`

## Route
- Namespace: `everia`
- Namespace Name: `EVERIA.CLUB`
- Route Path: `/everia/category/:category`
- Route Name: `Images with category`
- Example: `/everia/category/cosplay`
- URL: `everia.club`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `KTachibanaM, AiraNadih`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category of the image stream


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `everia.club/category/:category`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/everia/category/cosplay",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 154,
  "location": "category.ts",
  "maintainers": [
    "KTachibanaM",
    "AiraNadih"
  ],
  "name": "Images with category",
  "parameters": {
    "category": "Category of the image stream"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "everia.club/category/:category"
      ],
      "target": "/category/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "EVERIA.CLUB - Category: chinese - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "160206686101994527",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://everia.club/category/chinese/",
      "title": "EVERIA.CLUB - Category: chinese",
      "type": "feed",
      "url": "rsshub://everia/category/chinese"
    },
    {
      "description": "EVERIA.CLUB - Category: korea - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "160206686101994524",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://everia.club/category/korea/",
      "title": "EVERIA.CLUB - Category: korea",
      "type": "feed",
      "url": "rsshub://everia/category/korea"
    }
  ]
}
```
