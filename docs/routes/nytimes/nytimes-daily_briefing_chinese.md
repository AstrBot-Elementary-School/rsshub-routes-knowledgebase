# The New York Times - Daily Briefing

## Coverage
`index-only`

## Route
- Namespace: `nytimes`
- Namespace Name: `The New York Times`
- Route Path: `/nytimes/daily_briefing_chinese`
- Route Name: `Daily Briefing`
- Example: `/nytimes/daily_briefing_chinese`
- URL: `nytimes.com/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `yueyericardo, nczitzk`
- Source Location: `daily-briefing-chinese.tsx`
- Source Module: `_None_`

## Description
URL: <https://www.nytimes.com/zh-hans/series/daily-briefing-chinese>

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
  - `nytimes.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "URL: <https://www.nytimes.com/zh-hans/series/daily-briefing-chinese>",
  "example": "/nytimes/daily_briefing_chinese",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 64,
  "location": "daily-briefing-chinese.tsx",
  "maintainers": [
    "yueyericardo",
    "nczitzk"
  ],
  "name": "Daily Briefing",
  "parameters": {},
  "path": "/daily_briefing_chinese",
  "radar": [
    {
      "source": [
        "nytimes.com/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Daily Briefing - The New York Times - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "148631391178206293",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nytimes.com/zh-hans/series/daily-briefing-chinese",
      "title": "Daily Briefing - The New York Times",
      "type": "feed",
      "url": "rsshub://nytimes/daily_briefing_chinese"
    }
  ],
  "url": "nytimes.com/"
}
```
