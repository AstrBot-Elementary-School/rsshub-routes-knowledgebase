# 福利吧 - 最新

## Coverage
`index-only`

## Route
- Namespace: `fuliba`
- Namespace Name: `福利吧`
- Route Path: `/fuliba/latest`
- Route Name: `最新`
- Example: `/fuliba/latest`
- URL: `fuliba2023.net/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `shinemoon`
- Source Location: `latest.ts`
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
  - `fuliba2023.net/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/fuliba/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 489,
  "location": "latest.ts",
  "maintainers": [
    "shinemoon"
  ],
  "name": "最新",
  "parameters": {},
  "path": "/latest",
  "radar": [
    {
      "source": [
        "fuliba2023.net/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "福利吧 - Powered by RSSHub",
      "errorAt": "2026-06-15T11:07:58.453Z",
      "errorMessage": "[GET] \"https://fuliba2023.net/wp-json/wp/v2/posts?per_page=100&_embed=1\": 410 Gone\n[GET] \"https://fuliba2023.net/wp-json/wp/v2/posts?per_page=100&_embed=1\": 410 Gone\n[GET] \"https://fuliba2023.net/wp-json/wp/v2/posts?per_page=100&_embed=1\": 410 Gone\n[GET] \"https://fuliba2023.net/wp-json/wp/v2/posts?per_page=100&_embed=1\": 410 \n[GET] \"https://fuliba2023.net/wp-json/wp/v2/posts?per_page=100&_embed=1\": 410 \n[GET] \"https://fuliba2023.net/wp-json/wp/v2/posts?per_page=100&_embed=1\": 410 Gone\n[GET] \"https://fuliba2023.net/wp-json/wp/v2/posts?per_page=100&_embed=1\": 410 Gone\n",
      "id": "55989776559142912",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://fuliba2023.net/",
      "title": "福利吧",
      "type": "feed",
      "url": "rsshub://fuliba/latest"
    }
  ],
  "url": "fuliba2023.net/"
}
```
