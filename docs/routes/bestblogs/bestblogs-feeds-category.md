# bestblogs.dev - 文章列表

## Coverage
`index-only`

## Route
- Namespace: `bestblogs`
- Namespace Name: `bestblogs.dev`
- Route Path: `/bestblogs/feeds/:category?`
- Route Name: `文章列表`
- Example: `/bestblogs/feeds/featured`
- URL: `www.bestblogs.dev`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `zhenlohuang`
- Source Location: `feeds.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: the category of articles. Can be `programming`, `ai`, `product`, `business` or `featured`. Default is `featured`


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
    "programming"
  ],
  "example": "/bestblogs/feeds/featured",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 94,
  "location": "feeds.ts",
  "maintainers": [
    "zhenlohuang"
  ],
  "name": "文章列表",
  "parameters": {
    "category": "the category of articles. Can be `programming`, `ai`, `product`, `business` or `featured`. Default is `featured`"
  },
  "path": "/feeds/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Bestblogs.dev - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55765580939819008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bestblogs.dev/explore?type=article",
      "title": "Bestblogs.dev",
      "type": "feed",
      "url": "rsshub://bestblogs/feeds/featured"
    },
    {
      "description": "Bestblogs.dev - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "120316345262161920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bestblogs.dev/explore?type=article",
      "title": "Bestblogs.dev",
      "type": "feed",
      "url": "rsshub://bestblogs/feeds"
    }
  ]
}
```
