# QuestN - Community Events

## Coverage
`index-only`

## Route
- Namespace: `questn`
- Namespace Name: `QuestN`
- Route Path: `/questn/community/:communityUrl`
- Route Name: `Community Events`
- Example: `/questn/community/gmnetwork`
- URL: `app.questn.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `cxheng315`
- Source Location: `community.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `community_url`: Community URL


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
  - `app.questn.com/:communityUrl`
- `target`: `/community/:communityUrl`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/questn/community/gmnetwork",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "community.ts",
  "maintainers": [
    "cxheng315"
  ],
  "name": "Community Events",
  "parameters": {
    "community_url": "Community URL"
  },
  "path": "/community/:communityUrl",
  "radar": [
    {
      "source": [
        "app.questn.com/:communityUrl"
      ],
      "target": "/community/:communityUrl"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "app.questn.com"
}
```
