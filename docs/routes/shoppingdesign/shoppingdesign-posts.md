# Shopping Design - 文章列表

## Coverage
`index-only`

## Route
- Namespace: `shoppingdesign`
- Namespace Name: `Shopping Design`
- Route Path: `/shoppingdesign/posts`
- Route Name: `文章列表`
- Example: `/shoppingdesign/posts`
- URL: `www.shoppingdesign.com.tw/post`
- Language: `_None_`
- Categories: `design`
- Maintainers: `miles170`
- Source Location: `posts.ts`
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
  - `www.shoppingdesign.com.tw/post`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "example": "/shoppingdesign/posts",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "posts.ts",
  "maintainers": [
    "miles170"
  ],
  "name": "文章列表",
  "parameters": {},
  "path": "/posts",
  "radar": [
    {
      "source": [
        "www.shoppingdesign.com.tw/post"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-10-09T15:32:27.662Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "199134341005156437",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://shoppingdesign/posts"
    }
  ],
  "url": "www.shoppingdesign.com.tw/post"
}
```
