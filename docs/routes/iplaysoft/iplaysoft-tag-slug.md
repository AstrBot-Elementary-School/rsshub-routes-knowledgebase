# 异次元软件世界 - 标签

## Coverage
`index-only`

## Route
- Namespace: `iplaysoft`
- Namespace Name: `异次元软件世界`
- Route Path: `/iplaysoft/tag/:slug`
- Route Name: `标签`
- Example: `/iplaysoft/tag/windows`
- URL: `www.iplaysoft.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `cscnk52`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `slug`: 标签名称


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.iplaysoft.com/tag/:slug`
- `target`: `/tag/:slug`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/iplaysoft/tag/windows",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 13,
  "location": "tag.ts",
  "maintainers": [
    "cscnk52"
  ],
  "name": "标签",
  "parameters": {
    "slug": "标签名称"
  },
  "path": "/tag/:slug",
  "radar": [
    {
      "source": [
        "www.iplaysoft.com/tag/:slug"
      ],
      "target": "/tag/:slug"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "软件改变生活 - Powered by RSSHub",
      "errorAt": "2025-03-06T20:03:23.967Z",
      "errorMessage": "[GET] \"https://www.iplaysoft.com/wp-json/wp/v2/tags?slug=windows\": 403 Forbidden\n",
      "id": "112436974444936192",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.iplaysoft.com/tag/windows",
      "title": "windows - 异次元软件世界",
      "type": "feed",
      "url": "rsshub://iplaysoft/tag/windows"
    }
  ],
  "url": "www.iplaysoft.com",
  "view": 0
}
```
