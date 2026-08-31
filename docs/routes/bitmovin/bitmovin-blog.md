# Bitmovin - Blog

## Coverage
`index-only`

## Route
- Namespace: `bitmovin`
- Namespace Name: `Bitmovin`
- Route Path: `/bitmovin/blog`
- Route Name: `Blog`
- Example: `/bitmovin/blog`
- URL: `bitmovin.com/blog`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `elxy`
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
  - `bitmovin.com/blog`
  - `bitmovin.com/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/bitmovin/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "blog.ts",
  "maintainers": [
    "elxy"
  ],
  "name": "Blog",
  "parameters": {},
  "path": "/blog",
  "radar": [
    {
      "source": [
        "bitmovin.com/blog",
        "bitmovin.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Blog - Bitmovin - Powered by RSSHub",
      "errorAt": "2025-04-15T21:50:56.111Z",
      "errorMessage": "[GET] \"https://bitmovin.com/wp-json/wp/v2/posts?per_page=100\": 403 Forbidden\n",
      "id": "65418280634804224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bitmovin.com/blog/",
      "title": "Blog - Bitmovin",
      "type": "feed",
      "url": "rsshub://bitmovin/blog"
    }
  ],
  "url": "bitmovin.com/blog"
}
```
