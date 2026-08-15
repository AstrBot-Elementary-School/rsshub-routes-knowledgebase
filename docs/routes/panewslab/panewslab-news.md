# PANews - 快讯

## Coverage
`index-only`

## Route
- Namespace: `panewslab`
- Namespace Name: `PANews`
- Route Path: `/panewslab/news`
- Route Name: `快讯`
- Example: `/panewslab/news`
- URL: `panewslab.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

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
  "example": "/panewslab/news",
  "heat": 496,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "快讯",
  "path": "/news",
  "radar": [
    {
      "source": [
        "panewslab.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "PANews - 快讯 - Powered by RSSHub",
      "errorAt": "2026-03-19T16:21:55.279Z",
      "errorMessage": "[GET] \"https://panewslab.com/webapi/flashnews?LId=1&Rn=50&tw=0\": 404 Not Found\n[GET] \"https://panewslab.com/webapi/flashnews?LId=1&Rn=50&tw=0\": 404 Not Found\n",
      "id": "56552117750210620",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://panewslab.com/zh/news/index.html",
      "title": "PANews - 快讯",
      "type": "feed",
      "url": "rsshub://panewslab/news"
    }
  ],
  "url": "panewslab.com/"
}
```
