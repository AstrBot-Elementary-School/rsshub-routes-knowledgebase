# Paul Graham - Essays

## Coverage
`index-only`

## Route
- Namespace: `paulgraham`
- Namespace Name: `Paul Graham`
- Route Path: `/paulgraham/articles`
- Route Name: `Essays`
- Example: `/paulgraham/articles`
- URL: `paulgraham.com/articles.html`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `Maecenas, nczitzk, dvorak0`
- Source Location: `article.ts`
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
  - `paulgraham.com/articles.html`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/paulgraham/articles",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 541,
  "location": "article.ts",
  "maintainers": [
    "Maecenas",
    "nczitzk",
    "dvorak0"
  ],
  "name": "Essays",
  "parameters": {},
  "path": [
    "/articles",
    "/essays",
    "/"
  ],
  "radar": [
    {
      "source": [
        "paulgraham.com/articles.html"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Essays - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41468521403732992",
      "image": "https://s.turbifycdn.com/aah/paulgraham/essays-8.gif",
      "ownerUserId": null,
      "siteUrl": "https://paulgraham.com/articles.html",
      "title": "Paul Graham - Essays",
      "type": "feed",
      "url": "rsshub://paulgraham/articles"
    }
  ],
  "url": "paulgraham.com/articles.html"
}
```
