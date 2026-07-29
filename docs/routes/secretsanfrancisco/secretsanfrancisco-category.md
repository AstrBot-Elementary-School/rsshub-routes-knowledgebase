# Secret San francisco - Category

## Coverage
`index-only`

## Route
- Namespace: `secretsanfrancisco`
- Namespace Name: `Secret San francisco`
- Route Path: `/secretsanfrancisco/:category?`
- Route Name: `Category`
- Example: `/secretsanfrancisco/top-news`
- URL: `secretsanfrancisco.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `IvanWng97`
- Source Location: `rss.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: category name, can be found in url


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
  - `secretsanfrancisco.com/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/secretsanfrancisco/top-news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "rss.tsx",
  "maintainers": [
    "IvanWng97"
  ],
  "name": "Category",
  "parameters": {
    "category": "category name, can be found in url"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "secretsanfrancisco.com/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Secret San Francisco - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "206885643304709120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://secretsanfrancisco.com/",
      "title": "Secret San Francisco",
      "type": "feed",
      "url": "rsshub://secretsanfrancisco"
    }
  ]
}
```
