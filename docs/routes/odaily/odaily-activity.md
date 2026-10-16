# Odaily 星球日报 - 活动

## Coverage
`index-only`

## Route
- Namespace: `odaily`
- Namespace Name: `Odaily 星球日报`
- Route Path: `/odaily/activity`
- Route Name: `活动`
- Example: `/odaily/activity`
- URL: `www.odaily.news/zh-CN/activity`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `activity.ts`
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
  - `www.odaily.news/:locale/activity`
  - `www.odaily.news/activity`
  - `www.odaily.news/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/odaily/activity",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 28,
  "location": "activity.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "活动",
  "parameters": {},
  "path": "/activity",
  "radar": [
    {
      "source": [
        "www.odaily.news/:locale/activity",
        "www.odaily.news/activity",
        "www.odaily.news/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "活动 - Odaily星球日报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59954233475243008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.odaily.news/zh-CN/activity",
      "title": "活动 - Odaily星球日报",
      "type": "feed",
      "url": "rsshub://odaily/activity"
    }
  ],
  "url": "www.odaily.news/zh-CN/activity"
}
```
