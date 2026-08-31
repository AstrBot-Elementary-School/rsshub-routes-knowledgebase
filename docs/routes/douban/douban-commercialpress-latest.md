# 豆瓣 - 商务印书馆新书速递

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/commercialpress/latest`
- Route Name: `商务印书馆新书速递`
- Example: `/douban/commercialpress/latest`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `xyqfer`
- Source Location: `commercialpress/latest.ts`
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
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/douban/commercialpress/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "commercialpress/latest.ts",
  "maintainers": [
    "xyqfer"
  ],
  "name": "商务印书馆新书速递",
  "parameters": {},
  "path": "/commercialpress/latest",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-21T12:26:09.117Z",
      "errorMessage": "[GET] \"https://site.douban.com/commercialpress/room/827243/\": 404 Not Found\n",
      "id": "159222015361512474",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://douban/commercialpress/latest"
    }
  ]
}
```
