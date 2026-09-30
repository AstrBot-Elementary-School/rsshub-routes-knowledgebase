# The Atlantic - News

## Coverage
`index-only`

## Route
- Namespace: `theatlantic`
- Namespace Name: `The Atlantic`
- Route Path: `/theatlantic/:category`
- Route Name: `News`
- Example: `/theatlantic/latest`
- URL: `www.theatlantic.com`
- Language: `_None_`
- Categories: `traditional-media, popular`
- Maintainers: `IvanWng97, pseudoyu`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| Popular      | Latest | Politics | Technology | Business |
| ------------ | ------ | -------- | ---------- | -------- |
| most-popular | latest | politics | technology | business |

More categories (except photo) can be found within the navigation bar at <https://www.theatlantic.com>

## Parameters
- `category`: category, see below


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
  - `www.theatlantic.com/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media",
    "popular"
  ],
  "description": "| Popular      | Latest | Politics | Technology | Business |\n| ------------ | ------ | -------- | ---------- | -------- |\n| most-popular | latest | politics | technology | business |\n\nMore categories (except photo) can be found within the navigation bar at <https://www.theatlantic.com>",
  "example": "/theatlantic/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1401,
  "location": "news.ts",
  "maintainers": [
    "IvanWng97",
    "pseudoyu"
  ],
  "name": "News",
  "parameters": {
    "category": "category, see below"
  },
  "path": "/:category",
  "radar": [
    {
      "source": [
        "www.theatlantic.com/:category"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "The Atlantic - LATEST - Powered by RSSHub",
      "errorAt": "2026-09-20T22:33:52.921Z",
      "errorMessage": "502 \n[GET] \"https://www.theatlantic.com/latest/\": 403 Forbidden\n[GET] \"https://www.theatlantic.com/latest/\": 403 Forbidden\n",
      "id": "61228164717836288",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.theatlantic.com/latest/",
      "title": "The Atlantic - LATEST",
      "type": "feed",
      "url": "rsshub://theatlantic/latest"
    },
    {
      "description": "The Atlantic - TECHNOLOGY - Powered by RSSHub",
      "errorAt": "2026-09-22T20:46:05.326Z",
      "errorMessage": "[GET] \"https://www.theatlantic.com/technology/\": 403 Forbidden\n",
      "id": "62408054287669248",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.theatlantic.com/technology/",
      "title": "The Atlantic - TECHNOLOGY",
      "type": "feed",
      "url": "rsshub://theatlantic/technology"
    }
  ]
}
```
