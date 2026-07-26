# 飞客茶馆 - 优惠信息

## Coverage
`index-only`

## Route
- Namespace: `flyert`
- Namespace Name: `飞客茶馆`
- Route Path: `/flyert/preferential`
- Route Name: `优惠信息`
- Example: `/flyert/preferential`
- URL: `flyert.com/`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `howel52`
- Source Location: `preferential.ts`
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
  - `flyert.com/`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/flyert/preferential",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 22,
  "location": "preferential.ts",
  "maintainers": [
    "howel52"
  ],
  "name": "优惠信息",
  "parameters": {},
  "path": "/preferential",
  "radar": [
    {
      "source": [
        "flyert.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "飞客茶馆优惠 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56540861752061952",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.flyert.com/",
      "title": "飞客茶馆优惠",
      "type": "feed",
      "url": "rsshub://flyert/preferential"
    }
  ],
  "url": "flyert.com/"
}
```
