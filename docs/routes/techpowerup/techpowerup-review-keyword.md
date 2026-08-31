# TechPowerUp - Reviews

## Coverage
`index-only`

## Route
- Namespace: `techpowerup`
- Namespace Name: `TechPowerUp`
- Route Path: `/techpowerup/review/:keyword?`
- Route Name: `Reviews`
- Example: `/techpowerup/review/amd`
- URL: `www.techpowerup.com/review/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `review.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: Search Keyword


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
  - `techpowerup.com/review/search`
  - `techpowerup.com/review`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/techpowerup/review/amd",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "review.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Reviews",
  "parameters": {
    "keyword": "Search Keyword"
  },
  "path": "/review/:keyword?",
  "radar": [
    {
      "source": [
        "techpowerup.com/review/search",
        "techpowerup.com/review"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Reviews | TechPowerUp - Powered by RSSHub",
      "errorAt": "2026-01-05T01:45:48.523Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "186171888516931584",
      "image": "https://tpucdn.com/apple-touch-icon-v1684568903519.png",
      "ownerUserId": null,
      "siteUrl": "https://www.techpowerup.com/review/",
      "title": "Reviews | TechPowerUp",
      "type": "feed",
      "url": "rsshub://techpowerup/review"
    }
  ],
  "url": "www.techpowerup.com/review/"
}
```
