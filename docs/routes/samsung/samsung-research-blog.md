# Samsung - Research Blog

## Coverage
`index-only`

## Route
- Namespace: `samsung`
- Namespace Name: `Samsung`
- Route Path: `/samsung/research/blog`
- Route Name: `Research Blog`
- Example: `/samsung/research/blog`
- URL: `research.samsung.com/blog`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `research/blog.ts`
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
  - `research.samsung.com/blog`
  - `research.samsung.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/samsung/research/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "research/blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Research Blog",
  "parameters": {},
  "path": "/research/blog",
  "radar": [
    {
      "source": [
        "research.samsung.com/blog",
        "research.samsung.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "BLOG | Samsung Research - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70851835716090880",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://research.samsung.com/blog",
      "title": "BLOG | Samsung Research",
      "type": "feed",
      "url": "rsshub://samsung/research/blog"
    }
  ],
  "url": "research.samsung.com/blog"
}
```
