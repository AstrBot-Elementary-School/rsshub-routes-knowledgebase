# 电鸭社区 - 工作机会

## Coverage
`index-only`

## Route
- Namespace: `eleduck`
- Namespace Name: `电鸭社区`
- Route Path: `/eleduck/jobs`
- Route Name: `工作机会`
- Example: `/eleduck/jobs`
- URL: `eleduck.com/categories/5`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `sfyumi`
- Source Location: `jobs.ts`
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
  - `eleduck.com/categories/5`
  - `eleduck.com/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/eleduck/jobs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 258,
  "location": "jobs.ts",
  "maintainers": [
    "sfyumi"
  ],
  "name": "工作机会",
  "parameters": {},
  "path": "/jobs",
  "radar": [
    {
      "source": [
        "eleduck.com/categories/5",
        "eleduck.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "招聘 | 电鸭社区 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57251990358714368",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://eleduck.com/category/5",
      "title": "招聘 | 电鸭社区",
      "type": "feed",
      "url": "rsshub://eleduck/jobs"
    }
  ],
  "url": "eleduck.com/categories/5"
}
```
