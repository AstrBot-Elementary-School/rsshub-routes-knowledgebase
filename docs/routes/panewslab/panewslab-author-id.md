# PANews - 专栏

## Coverage
`index-only`

## Route
- Namespace: `panewslab`
- Namespace Name: `PANews`
- Route Path: `/panewslab/author/:id`
- Route Name: `专栏`
- Example: `/panewslab/author/166`
- URL: `panewslab.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `author.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 专栏 id，可在地址栏 URL 中找到


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
  - `panewslab.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/panewslab/author/166",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "author.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "专栏",
  "parameters": {
    "id": "专栏 id，可在地址栏 URL 中找到"
  },
  "path": [
    "/author/:id",
    "/column/:id"
  ],
  "radar": [
    {
      "source": [
        "panewslab.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "PANews - Tim - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63209480024421376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://panewslab.com/zh/author/166.html",
      "title": "PANews - Tim",
      "type": "feed",
      "url": "rsshub://panewslab/author/166"
    }
  ],
  "url": "panewslab.com/"
}
```
