# 普世社会科学研究所 - 最新文章

## Coverage
`index-only`

## Route
- Namespace: `pacilution`
- Namespace Name: `普世社会科学研究所`
- Route Path: `/pacilution/latest`
- Route Name: `最新文章`
- Example: `/pacilution/latest`
- URL: `www.pacilution.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `PrinOrange`
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
  - `www.pacilution.com`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/pacilution/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 24,
  "location": "latest.ts",
  "maintainers": [
    "PrinOrange"
  ],
  "name": "最新文章",
  "path": "/latest",
  "radar": [
    {
      "source": [
        "www.pacilution.com"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "普世社会科学研究网首页上不同板块的最新文章汇总集合 - Powered by RSSHub",
      "errorAt": "2025-04-07T15:03:34.897Z",
      "errorMessage": "[GET] \"http://www.pacilution.com/\": <no response> fetch failed (getaddrinfo ENOTFOUND www.pacilution.com)\n",
      "id": "97986765433683968",
      "image": "http://www.pacilution.com/img/top_banner.jpg",
      "ownerUserId": null,
      "siteUrl": "http://www.pacilution.com/",
      "title": "普世社会科学研究网最新文章",
      "type": "feed",
      "url": "rsshub://pacilution/latest"
    }
  ]
}
```
