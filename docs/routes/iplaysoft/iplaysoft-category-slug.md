# 异次元软件世界 - 分类

## Coverage
`index-only`

## Route
- Namespace: `iplaysoft`
- Namespace Name: `异次元软件世界`
- Route Path: `/iplaysoft/category/:slug`
- Route Name: `分类`
- Example: `/iplaysoft/category/system`
- URL: `www.iplaysoft.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `cscnk52`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `slug`: 分类名称


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
  - `www.iplaysoft.com/category/:slug`
- `target`: `/category/:slug`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/iplaysoft/category/system",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 40,
  "location": "category.ts",
  "maintainers": [
    "cscnk52"
  ],
  "name": "分类",
  "parameters": {
    "slug": "分类名称"
  },
  "path": "/category/:slug",
  "radar": [
    {
      "source": [
        "www.iplaysoft.com/category/:slug"
      ],
      "target": "/category/:slug"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "软件改变生活 - Powered by RSSHub",
      "errorAt": "2025-03-06T22:40:32.067Z",
      "errorMessage": "[GET] \"https://www.iplaysoft.com/wp-json/wp/v2/categories?slug=network\": 403 Forbidden\nAuthentication failed. Access denied.\n/iplaysoft/category/network\n[GET] \"https://www.iplaysoft.com/wp-json/wp/v2/categories?slug=network\": 403 Forbidden\n",
      "id": "117435061031429120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.iplaysoft.com/category/network",
      "title": "网络软件 - 异次元软件世界",
      "type": "feed",
      "url": "rsshub://iplaysoft/category/network"
    },
    {
      "description": "软件改变生活 - Powered by RSSHub",
      "errorAt": "2025-03-06T19:01:36.406Z",
      "errorMessage": "[GET] \"https://www.iplaysoft.com/wp-json/wp/v2/categories?slug=security\": 403 Forbidden\n",
      "id": "117436204713032704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.iplaysoft.com/category/security",
      "title": "安全隐私 - 异次元软件世界",
      "type": "feed",
      "url": "rsshub://iplaysoft/category/security"
    }
  ],
  "url": "www.iplaysoft.com",
  "view": 0
}
```
