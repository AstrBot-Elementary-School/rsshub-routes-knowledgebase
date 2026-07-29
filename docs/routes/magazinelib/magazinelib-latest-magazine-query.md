# MagazineLib - Latest Magazine

## Coverage
`index-only`

## Route
- Namespace: `magazinelib`
- Namespace Name: `MagazineLib`
- Route Path: `/magazinelib/latest-magazine/:query?`
- Route Name: `Latest Magazine`
- Example: `/magazinelib/latest-magazine/new+yorker`
- URL: `magazinelib.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `IvanWng97`
- Source Location: `latest-magazine.tsx`
- Source Module: `_None_`

## Description
For instance, when doing search at <https://magazinelib.com> and you get url `https://magazinelib.com/?s=new+yorker`, the query is `new+yorker`

## Parameters
- `query`: query, search page querystring


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
    "reading"
  ],
  "description": "For instance, when doing search at <https://magazinelib.com> and you get url `https://magazinelib.com/?s=new+yorker`, the query is `new+yorker`",
  "example": "/magazinelib/latest-magazine/new+yorker",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "latest-magazine.tsx",
  "maintainers": [
    "IvanWng97"
  ],
  "name": "Latest Magazine",
  "parameters": {
    "query": "query, search page querystring"
  },
  "path": "/latest-magazine/:query?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "MagazineLib - Latest Magazines - NEW YORKER - Powered by RSSHub",
      "errorAt": "2026-06-19T16:22:54.214Z",
      "errorMessage": "[GET] \"https://magazinelib.com/wp-json/wp/v2/posts/?search=new+yorker&per_page=30&_embed=1\": 403 Forbidden\n",
      "id": "258938409787591680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://magazinelib.com/?s=new%20yorker",
      "title": "MagazineLib - Latest Magazines - NEW YORKER",
      "type": "feed",
      "url": "rsshub://magazinelib/latest-magazine/new%20yorker"
    }
  ]
}
```
