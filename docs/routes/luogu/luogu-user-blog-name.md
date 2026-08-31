# 洛谷 - 用户博客

## Coverage
`index-only`

## Route
- Namespace: `luogu`
- Namespace Name: `洛谷`
- Route Path: `/luogu/user/blog/:name`
- Route Name: `用户博客`
- Example: `/luogu/user/blog/ftiasch`
- URL: `luogu.com.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `ftiasch`
- Source Location: `user-blog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: 博客名称


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
  - `luogu.com/blog/:name`
### Rule 2
- `source`:
  - `luogu.com.cn/blog/:name`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/luogu/user/blog/ftiasch",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "user-blog.ts",
  "maintainers": [
    "ftiasch"
  ],
  "name": "用户博客",
  "parameters": {
    "name": "博客名称"
  },
  "path": "/user/blog/:name",
  "radar": [
    {
      "source": [
        "luogu.com/blog/:name"
      ]
    },
    {
      "source": [
        "luogu.com.cn/blog/:name"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
