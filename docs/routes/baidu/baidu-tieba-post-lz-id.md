# 百度 - 楼主动态

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/baidu/tieba/post/lz/:id`
- Route Name: `楼主动态`
- Example: `/baidu/tieba/post/lz/686961453`
- URL: `www.baidu.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `u3u, FlanChanXwO`
- Source Location: `tieba/post-lz.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 帖子 ID


## Features
- `requireConfig`: [{"description": "百度 cookie 值，用于需要登录的贴吧页面", "name": "BAIDU_COOKIE", "optional": true}]
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/baidu/tieba/post/lz/686961453",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "百度 cookie 值，用于需要登录的贴吧页面",
        "name": "BAIDU_COOKIE",
        "optional": true
      }
    ]
  },
  "heat": 9,
  "location": "tieba/post-lz.ts",
  "maintainers": [
    "u3u",
    "FlanChanXwO"
  ],
  "name": "楼主动态",
  "parameters": {
    "id": "帖子 ID"
  },
  "path": "/tieba/post/lz/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 363964592480 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "回复：2024主机配置新帖的最新回复 - Powered by RSSHub",
      "errorAt": "2025-03-29T11:22:25.149Z",
      "errorMessage": "Tieba API error: 该贴已被删除，请浏览其他贴子\n",
      "id": "73922058150935552",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/p/9083587772?see_lz=1",
      "title": "【只看楼主】回复：2024主机配置新帖",
      "type": "feed",
      "url": "rsshub://baidu/tieba/post/lz/9083587772"
    },
    {
      "description": "回复：【饿殍第三线】——落荒的最新回复 - Powered by RSSHub",
      "errorAt": "2026-03-01T23:08:24.204Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/p/9093613735?see_lz=1&pn=7000000&ajax=1\": 403 Forbidden\n[GET] \"https://tieba.baidu.com/p/9093613735?see_lz=1&pn=7000000&ajax=1\": 403 Forbidden\n",
      "id": "137785439754288128",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/p/9093613735?see_lz=1",
      "title": "【只看楼主】回复：【饿殍第三线】——落荒",
      "type": "feed",
      "url": "rsshub://baidu/tieba/post/lz/9093613735"
    }
  ]
}
```
