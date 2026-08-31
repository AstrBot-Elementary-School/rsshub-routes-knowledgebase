# UK Parliament - Commonlibrary

## Coverage
`index-only`

## Route
- Namespace: `parliament.uk`
- Namespace Name: `UK Parliament`
- Route Path: `/parliament.uk/commonslibrary/type/:topic?`
- Route Name: `Commonlibrary`
- Example: `/parliament.uk/commonslibrary/type/research-briefing`
- URL: `parliament.uk`
- Language: `_None_`
- Categories: `government`
- Maintainers: `AntiKnot`
- Source Location: `commonslibrary.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: research by topic, string, example: [research-briefing|data-dashboard]


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
    "government"
  ],
  "example": "/parliament.uk/commonslibrary/type/research-briefing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "commonslibrary.ts",
  "maintainers": [
    "AntiKnot"
  ],
  "name": "Commonlibrary",
  "parameters": {
    "topic": "research by topic, string, example: [research-briefing|data-dashboard]"
  },
  "path": "/commonslibrary/type/:topic?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "parliament - lordslibrary - research-briefing - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68554046044185600",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://commonslibrary.parliament.uk/type/research-briefing/",
      "title": "parliament - lordslibrary - research-briefing",
      "type": "feed",
      "url": "rsshub://parliament.uk/commonslibrary/type/research-briefing"
    }
  ]
}
```
