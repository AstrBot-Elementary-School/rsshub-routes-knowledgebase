# 小米 - 小米众筹

## Coverage
`index-only`

## Route
- Namespace: `mi`
- Namespace Name: `小米`
- Route Path: `/mi/crowdfunding`
- Route Name: `小米众筹`
- Example: `/mi/crowdfunding`
- URL: `mi.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `DIYgod, nuomi1`
- Source Location: `crowdfunding.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `m.mi.com/crowdfunding/home`
- `target`: `/crowdfunding`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/mi/crowdfunding",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 286,
  "location": "crowdfunding.ts",
  "maintainers": [
    "DIYgod",
    "nuomi1"
  ],
  "name": "小米众筹",
  "path": "/crowdfunding",
  "radar": [
    {
      "source": [
        "m.mi.com/crowdfunding/home"
      ],
      "target": "/crowdfunding"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected -865514591 to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:64:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:90:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:109:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "小米众筹 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42123928726287360",
      "image": "https://m.mi.com/static/img/icons/apple-touch-icon-152x152.png",
      "ownerUserId": null,
      "siteUrl": "https://m.mi.com/crowdfunding/home",
      "title": "小米众筹",
      "type": "feed",
      "url": "rsshub://mi/crowdfunding"
    }
  ],
  "view": 5
}
```
