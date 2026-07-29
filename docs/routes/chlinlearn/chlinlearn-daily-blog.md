# chlinlearn 的技术博客 - 值得一读技术博客

## Coverage
`index-only`

## Route
- Namespace: `chlinlearn`
- Namespace Name: `chlinlearn 的技术博客`
- Route Path: `/chlinlearn/daily-blog`
- Route Name: `值得一读技术博客`
- Example: `/chlinlearn/daily-blog`
- URL: `daily-blog.chlinlearn.top`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `huyyi`
- Source Location: `daily-blog.ts`
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
  - `daily-blog.chlinlearn.top/blogs/*`
- `target`: `/chlinlearn/daily-blog`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/chlinlearn/daily-blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 329,
  "location": "daily-blog.ts",
  "maintainers": [
    "huyyi"
  ],
  "name": "值得一读技术博客",
  "path": "/daily-blog",
  "radar": [
    {
      "source": [
        "daily-blog.chlinlearn.top/blogs/*"
      ],
      "target": "/chlinlearn/daily-blog"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "值得一读技术博客 - Powered by RSSHub",
      "errorAt": "2025-11-15T17:37:54.148Z",
      "errorMessage": "Authentication failed. Access denied.\n/chlinlearn/daily-blog\n[GET] \"https://daily-blog.chlinlearn.top/api/daily-blog/getBlogs/new?type=new&pageNum=1&pageSize=20\": <no response> fetch failed (Connect Timeout Error (attempted address: daily-blog.chlinlearn.top:443, timeout: 10000ms))\n[GET] \"https://daily-blog.chlinlearn.top/api/daily-blog/getBlogs/new?type=new&pageNum=1&pageSize=20\": <no response> fetch failed (Connect Timeout Error (attempted address: daily-blog.chlinlearn.top:443, timeout: 10000ms))\n[GET] \"https://daily-blog.chlinlearn.top/api/daily-blog/getBlogs/new?type=new&pageNum=1&pageSize=20\": <no response> fetch failed (Connect Timeout Error (attempted address: daily-blog.chlinlearn.top:443, timeout: 10000ms))\n502 \n[GET] \"https://daily-blog.chlinlearn.top/api/daily-blog/getBlogs/new?type=new&pageNum=1&pageSize=20\": <no response> fetch failed (Connect Timeout Error (attempted address: daily-blog.chlinlearn.top:443, timeout: 10000ms))\n",
      "id": "55155355881001984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://daily-blog.chlinlearn.top/blogs/1",
      "title": "值得一读技术博客",
      "type": "feed",
      "url": "rsshub://chlinlearn/daily-blog"
    }
  ]
}
```
