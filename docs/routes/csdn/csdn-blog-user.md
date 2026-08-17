# CSDN - User Feed

## Coverage
`index-only`

## Route
- Namespace: `csdn`
- Namespace Name: `CSDN`
- Route Path: `/csdn/blog/:user`
- Route Name: `User Feed`
- Example: `/csdn/blog/csdngeeknews`
- URL: `blog.csdn.net`
- Language: `_None_`
- Categories: `blog, popular`
- Maintainers: `Jkker`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: `user` is the username of a CSDN blog which can be found in the url of the home page


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
  - `blog.csdn.net/:user`

## Raw JSON
```json
{
  "categories": [
    "blog",
    "popular"
  ],
  "example": "/csdn/blog/csdngeeknews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1336,
  "location": "blog.ts",
  "maintainers": [
    "Jkker"
  ],
  "name": "User Feed",
  "parameters": {
    "user": "`user` is the username of a CSDN blog which can be found in the url of the home page"
  },
  "path": "/blog/:user",
  "radar": [
    {
      "source": [
        "blog.csdn.net/:user"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "苏杰（iamsujie） - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57360050739377164",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://blog.csdn.net/iamsujie",
      "title": "人人都是产品经理 - CSDN博客",
      "type": "feed",
      "url": "rsshub://csdn/blog/iamsujie"
    },
    {
      "description": "给技术人奉上当日新鲜的科技资讯和技术干货！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63118600077338631",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://blog.csdn.net/weixin_39786569",
      "title": "极客日报 - CSDN博客",
      "type": "feed",
      "url": "rsshub://csdn/blog/csdngeeknews"
    }
  ]
}
```
