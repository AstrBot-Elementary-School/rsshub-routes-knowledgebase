# FX Markets - Channel

## Coverage
`index-only`

## Route
- Namespace: `fx-markets`
- Namespace Name: `FX Markets`
- Route Path: `/fx-markets/:channel`
- Route Name: `Channel`
- Example: `/fx-markets/trading`
- URL: `fx-markets.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `mikkkee`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
| Trading | Infrastructure | Tech and Data | Regulation |
| ------- | -------------- | ------------- | ---------- |
| trading | infrastructure | tech-and-data | regulation |

## Parameters
- `channel`: channel, can be found in the navi bar links at the home page


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
    "finance"
  ],
  "description": "| Trading | Infrastructure | Tech and Data | Regulation |\n| ------- | -------------- | ------------- | ---------- |\n| trading | infrastructure | tech-and-data | regulation |",
  "example": "/fx-markets/trading",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 41,
  "location": "channel.ts",
  "maintainers": [
    "mikkkee"
  ],
  "name": "Channel",
  "parameters": {
    "channel": "channel, can be found in the navi bar links at the home page"
  },
  "path": "/:channel",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "FX-Markets Trading - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59063696285536256",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.fx-markets.com/trading",
      "title": "FX-Markets Trading",
      "type": "feed",
      "url": "rsshub://fx-markets/trading"
    },
    {
      "description": "FX-Markets Tech and data - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "91579916169767936",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.fx-markets.com/tech-and-data",
      "title": "FX-Markets Tech and data",
      "type": "feed",
      "url": "rsshub://fx-markets/tech-and-data"
    }
  ]
}
```
