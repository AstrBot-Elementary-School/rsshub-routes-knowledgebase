# 爱范儿 - 快讯

## Coverage
`index-only`

## Route
- Namespace: `ifanr`
- Namespace Name: `爱范儿`
- Route Path: `/ifanr/digest`
- Route Name: `快讯`
- Example: `/ifanr/digest`
- URL: `www.ifanr.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `digest.ts`
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
  - `www.ifanr.comdigest`
- `target`: `/digest`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/ifanr/digest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 152,
  "location": "digest.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "快讯",
  "path": "/digest",
  "radar": [
    {
      "source": [
        "www.ifanr.comdigest"
      ],
      "target": "/digest"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at processImmediate (node:internal/timers:541:9)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "快讯 | 爱范儿 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "97457366708658176",
      "image": "https://images.ifanr.cn/wp-content/themes/ifanr-5.0-pc/static/images/ifanr/ifanr-logo.svg",
      "ownerUserId": null,
      "siteUrl": "https://www.ifanr.com/digest",
      "title": "快讯 | 爱范儿",
      "type": "feed",
      "url": "rsshub://ifanr/digest"
    }
  ],
  "url": "www.ifanr.com",
  "view": 0
}
```
