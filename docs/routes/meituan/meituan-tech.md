# 美团 - 技术团队博客

## Coverage
`index-only`

## Route
- Namespace: `meituan`
- Namespace Name: `美团`
- Route Path: `/meituan/tech`
- Route Name: `技术团队博客`
- Example: `/meituan/tech`
- URL: `tech.meituan.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `ktKongTong, cscnk52`
- Source Location: `tech.ts`
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
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `tech.meituan.com`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/meituan/tech",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 1018,
  "location": "tech.ts",
  "maintainers": [
    "ktKongTong",
    "cscnk52"
  ],
  "name": "技术团队博客",
  "parameters": {},
  "path": "/tech",
  "radar": [
    {
      "source": [
        "tech.meituan.com"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "美团技术团队|前端|后端|IOS|安卓|客户端 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41467081627747351",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tech.meituan.com/",
      "title": "美团 · 技术团队",
      "type": "feed",
      "url": "rsshub://meituan/tech"
    }
  ],
  "url": "tech.meituan.com"
}
```
