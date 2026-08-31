# 小黑盒 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `xiaoheihe`
- Namespace Name: `小黑盒`
- Route Path: `/xiaoheihe/user/:id`
- Route Name: `用户动态`
- Example: `/xiaoheihe/user/30664023`
- URL: `xiaoheihe.cn`
- Language: `_None_`
- Categories: `game`
- Maintainers: `tssujt`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户 ID


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
    "game"
  ],
  "example": "/xiaoheihe/user/30664023",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 42,
  "location": "user.ts",
  "maintainers": [
    "tssujt"
  ],
  "name": "用户动态",
  "parameters": {
    "id": "用户 ID"
  },
  "path": "/user/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "三角洲行动 的动态 - Powered by RSSHub",
      "errorAt": "2026-03-19T13:40:53.604Z",
      "errorMessage": "Cannot read properties of undefined (reading 'username')\nCannot read properties of undefined (reading 'username')\n",
      "id": "89892270853491712",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xiaoheihe.cn/",
      "title": "三角洲行动 的动态",
      "type": "feed",
      "url": "rsshub://xiaoheihe/user/55764561"
    },
    {
      "description": "游戏资讯BOT 的动态 - Powered by RSSHub",
      "errorAt": "2026-05-03T01:25:09.582Z",
      "errorMessage": "Cannot read properties of undefined (reading 'username')\n",
      "id": "91867369650236416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xiaoheihe.cn/",
      "title": "游戏资讯BOT 的动态",
      "type": "feed",
      "url": "rsshub://xiaoheihe/user/23741741"
    }
  ]
}
```
