# The New York Times - News

## Coverage
`index-only`

## Route
- Namespace: `nytimes`
- Namespace Name: `The New York Times`
- Route Path: `/nytimes/rss/:cat?`
- Route Name: `News`
- Example: `/nytimes/rss/HomePage`
- URL: `nytimes.com/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `HenryQW, pseudoyu, dzx-dzx`
- Source Location: `rss.ts`
- Source Module: `_None_`

## Description
Enhance the official EN RSS feed

## Parameters
- `cat`: {"description": "Category name, corresponding to the last segment of [official feed's](https://www.nytimes.com/rss) url."}


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
  - `nytimes.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Enhance the official EN RSS feed",
  "example": "/nytimes/rss/HomePage",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 299,
  "location": "rss.ts",
  "maintainers": [
    "HenryQW",
    "pseudoyu",
    "dzx-dzx"
  ],
  "name": "News",
  "parameters": {
    "cat": {
      "description": "Category name, corresponding to the last segment of [official feed's](https://www.nytimes.com/rss) url."
    }
  },
  "path": "/rss/:cat?",
  "radar": [
    {
      "source": [
        "nytimes.com/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "纽约时报中文网 - Powered by RSSHub",
      "errorAt": "2025-02-19T21:09:22.196Z",
      "errorMessage": "Status code 404\n",
      "id": "76515556102948864",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.nytimes.com/",
      "title": "纽约时报中文网",
      "type": "feed",
      "url": "rsshub://nytimes/rss"
    },
    {
      "description": "NYT > Top Stories - Powered by RSSHub",
      "errorAt": "2025-06-11T21:30:37.105Z",
      "errorMessage": "[GET] \"https://www.nytimes.com/2026/07/30/us/politics/minnesota-water-cyberattack-iran.html\": 403 Forbidden\n[GET] \"https://www.nytimes.com/2026/07/30/world/europe/ukraine-poland-russia-missile.html\": 403 Forbidden\n",
      "id": "76533237937860608",
      "image": "{\"link\":\"https://www.nytimes.com\",\"url\":\"https://static01.nyt.com/images/misc/NYT_logo_rss_250x40.png\",\"title\":\"NYT > Top Stories\"}",
      "ownerUserId": null,
      "siteUrl": "https://www.nytimes.com/",
      "title": "NYT > Top Stories",
      "type": "feed",
      "url": "rsshub://nytimes/rss/HomePage"
    }
  ],
  "url": "nytimes.com/",
  "view": 0
}
```
