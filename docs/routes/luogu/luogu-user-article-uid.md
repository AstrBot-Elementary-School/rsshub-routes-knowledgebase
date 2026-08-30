# 洛谷 - 用户文章

## Coverage
`index-only`

## Route
- Namespace: `luogu`
- Namespace Name: `洛谷`
- Route Path: `/luogu/user/article/:uid`
- Route Name: `用户文章`
- Example: `/luogu/user/article/1`
- URL: `luogu.com.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `user-article.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: 用户 UID


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
  - `luogu.com/user/:uid`
### Rule 2
- `source`:
  - `luogu.com.cn/user/:uid`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/luogu/user/article/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "user-article.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "用户文章",
  "parameters": {
    "name": "用户 UID"
  },
  "path": "/user/article/:uid",
  "radar": [
    {
      "source": [
        "luogu.com/user/:uid"
      ]
    },
    {
      "source": [
        "luogu.com.cn/user/:uid"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "北海虽赊，扶摇可接。 - Powered by RSSHub",
      "errorAt": "2025-10-11T03:36:01.555Z",
      "errorMessage": "Cannot read properties of undefined (reading 'user')\n",
      "id": "103364842331496448",
      "image": "https://cdn.luogu.com.cn/upload/usericon/115864.png",
      "ownerUserId": null,
      "siteUrl": "https://www.luogu.com/user/115864#article",
      "title": "NaCly_Fish 的个人中心 - 洛谷 | 计算机科学教育新生态",
      "type": "feed",
      "url": "rsshub://luogu/user/article/115864"
    },
    {
      "description": "洛谷吉祥物 DA✩ZE - Powered by RSSHub",
      "errorAt": "2025-10-11T00:19:16.836Z",
      "errorMessage": "Cannot read properties of undefined (reading 'user')\n",
      "id": "121037877502622720",
      "image": "https://cdn.luogu.com.cn/upload/usericon/1.png",
      "ownerUserId": null,
      "siteUrl": "https://www.luogu.com/user/1#article",
      "title": "kkksc03 的个人中心 - 洛谷 | 计算机科学教育新生态",
      "type": "feed",
      "url": "rsshub://luogu/user/article/1"
    }
  ]
}
```
