# Corona Virus Disease 2019 - News

## Coverage
`index-only`

## Route
- Namespace: `scmp`
- Namespace Name: `Corona Virus Disease 2019`
- Route Path: `/scmp/:category_id`
- Route Name: `News`
- Example: `/scmp/3`
- URL: `scmp.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `proletarius101`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
See the [official RSS page](https://www.scmp.com/rss) to get the ID of each category. This route provides fulltext that the offical feed doesn't.

## Parameters
- `category_id`: Category


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
  - `scmp.com/rss/:category_id/feed`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "See the [official RSS page](https://www.scmp.com/rss) to get the ID of each category. This route provides fulltext that the offical feed doesn't.",
  "example": "/scmp/3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 173,
  "location": "index.ts",
  "maintainers": [
    "proletarius101"
  ],
  "name": "News",
  "parameters": {
    "category_id": "Category"
  },
  "path": "/:category_id",
  "radar": [
    {
      "source": [
        "scmp.com/rss/:category_id/feed"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "The latest breaking news from China. - Powered by RSSHub",
      "errorAt": "2026-08-13T23:31:29.273Z",
      "errorMessage": "Cannot read properties of undefined (reading 'summary')\n",
      "id": "58381798255721484",
      "image": "https://assets.i-scmp.com/static/img/icons/scmp-meta-1200x630.png",
      "ownerUserId": null,
      "siteUrl": "https://www.scmp.com/rss/4/feed",
      "title": "China - South China Morning Post",
      "type": "feed",
      "url": "rsshub://scmp/4"
    },
    {
      "description": "Breaking news, analysis and opinion from the SCMP's Asia edition. - Powered by RSSHub",
      "errorAt": "2026-08-13T09:15:31.620Z",
      "errorMessage": "Failed to fetch\nCannot read properties of undefined (reading 'summary')\n",
      "id": "58381798255721483",
      "image": "https://assets.i-scmp.com/static/img/icons/scmp-meta-1200x630.png",
      "ownerUserId": null,
      "siteUrl": "https://www.scmp.com/rss/3/feed",
      "title": "Asia - South China Morning Post",
      "type": "feed",
      "url": "rsshub://scmp/3"
    }
  ]
}
```
