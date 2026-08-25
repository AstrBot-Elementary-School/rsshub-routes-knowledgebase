# Manus - Blog

## Coverage
`index-only`

## Route
- Namespace: `manus`
- Namespace Name: `Manus`
- Route Path: `/manus/blog`
- Route Name: `Blog`
- Example: `/manus/blog`
- URL: `manus.im`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `cscnk52`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
Manus Blog

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
  - `www.manus.im`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "Manus Blog",
  "example": "/manus/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 65,
  "location": "blog.ts",
  "maintainers": [
    "cscnk52"
  ],
  "name": "Blog",
  "parameters": {},
  "path": "/blog",
  "radar": [
    {
      "source": [
        "www.manus.im"
      ],
      "target": "/blog"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Manus Blog - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "170866434027417600",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://manus.im/blog",
      "title": "Manus Blog",
      "type": "feed",
      "url": "rsshub://manus/blog"
    }
  ],
  "url": "manus.im",
  "view": 5
}
```
