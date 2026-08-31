# 电子发烧友 - 文章

## Coverage
`index-only`

## Route
- Namespace: `elecfans`
- Namespace Name: `电子发烧友`
- Route Path: `/elecfans/article/:atype`
- Route Name: `文章`
- Example: `/elecfans/article/special`
- URL: `www.elecfans.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `tian051011`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `atype`: 需获取文章的类别


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
  - `www.elecfans.com`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/elecfans/article/special",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "article.ts",
  "maintainers": [
    "tian051011"
  ],
  "name": "文章",
  "parameters": {
    "atype": "需获取文章的类别"
  },
  "path": "/article/:atype",
  "radar": [
    {
      "source": [
        "www.elecfans.com"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "elecfans special articles - Powered by RSSHub",
      "errorAt": "2026-07-09T04:22:34.438Z",
      "errorMessage": "[GET] \"https://www.elecfans.com/article/special/\": 468 \n",
      "id": "182701002532529152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.elecfans.com/article/special/",
      "title": "elecfans special articles",
      "type": "feed",
      "url": "rsshub://elecfans/article/special"
    }
  ]
}
```
