# 华尔街见闻 - 财经日历

## Coverage
`index-only`

## Route
- Namespace: `wallstreetcn`
- Namespace Name: `华尔街见闻`
- Route Path: `/wallstreetcn/calendar/:section?`
- Route Name: `财经日历`
- Example: `/wallstreetcn/calendar`
- URL: `wallstreetcn.com/calendar`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `calendar.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `section`: `macrodatas` 或 `report`，默认为 `macrodatas`


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
  - `wallstreetcn.com/calendar`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/wallstreetcn/calendar",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 99,
  "location": "calendar.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "财经日历",
  "parameters": {
    "section": "`macrodatas` 或 `report`，默认为 `macrodatas`"
  },
  "path": "/calendar/:section?",
  "radar": [
    {
      "source": [
        "wallstreetcn.com/calendar"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "财经日历 - 华尔街见闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80430906726720512",
      "image": "https://static.wscn.net/wscn/_static/favicon.png",
      "ownerUserId": null,
      "siteUrl": "https://wallstreetcn.com/calendar",
      "title": "财经日历 - 华尔街见闻",
      "type": "feed",
      "url": "rsshub://wallstreetcn/calendar"
    },
    {
      "description": "财经日历 - 华尔街见闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "165321950833192960",
      "image": "https://static.wscn.net/wscn/_static/favicon.png",
      "ownerUserId": null,
      "siteUrl": "https://wallstreetcn.com/calendar",
      "title": "财经日历 - 华尔街见闻",
      "type": "feed",
      "url": "rsshub://wallstreetcn/calendar/macrodatas"
    }
  ],
  "url": "wallstreetcn.com/calendar"
}
```
