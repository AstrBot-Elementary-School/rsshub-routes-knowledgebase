# Macfilos - Blog

## Coverage
`index-only`

## Route
- Namespace: `macfilos`
- Namespace Name: `Macfilos`
- Route Path: `/macfilos/blog`
- Route Name: `Blog`
- Example: `/macfilos/blog`
- URL: `macfilos.com/blog`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
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
  - `macfilos.com/blog`
  - `macfilos.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/macfilos/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 33,
  "location": "blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Blog",
  "parameters": {},
  "path": "/blog",
  "radar": [
    {
      "source": [
        "macfilos.com/blog",
        "macfilos.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Blog page - Macfilos - Powered by RSSHub",
      "errorAt": "2026-08-30T10:06:50.455Z",
      "errorMessage": "[GET] \"https://www.macfilos.com/blog\": 401 Unauthorized\n",
      "id": "73534875400660992",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.macfilos.com/blog",
      "title": "Blog page - Macfilos",
      "type": "feed",
      "url": "rsshub://macfilos/blog"
    }
  ],
  "url": "macfilos.com/blog"
}
```
