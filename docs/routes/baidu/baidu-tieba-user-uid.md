# 百度 - 用户帖子

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/baidu/tieba/user/:uid`
- Route Name: `用户帖子`
- Example: `/baidu/tieba/user/斗鱼游戏君`
- URL: `www.baidu.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `igxlin, nczitzk`
- Source Location: `tieba/user.ts`
- Source Module: `_None_`

## Description
用户 ID 可以通过打开用户的主页后查看地址栏的 `un` 字段来获取。

## Parameters
- `uid`: 用户 ID


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
    "bbs"
  ],
  "description": "用户 ID 可以通过打开用户的主页后查看地址栏的 `un` 字段来获取。",
  "example": "/baidu/tieba/user/斗鱼游戏君",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 12,
  "location": "tieba/user.ts",
  "maintainers": [
    "igxlin",
    "nczitzk"
  ],
  "name": "用户帖子",
  "parameters": {
    "uid": "用户 ID"
  },
  "path": "/tieba/user/:uid",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "dengchunlai 的贴吧 - Powered by RSSHub",
      "errorAt": "2026-06-28T17:36:38.883Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/home/main?un=dengchunlai\": 403 Forbidden\n",
      "id": "104695101579488257",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/home/main?un=dengchunlai",
      "title": "dengchunlai 的贴吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/user/dengchunlai"
    },
    {
      "description": "米利阿鲁德 的贴吧 - Powered by RSSHub",
      "errorAt": "2026-05-26T01:17:33.906Z",
      "errorMessage": "Authentication failed. Access denied.\n/baidu/tieba/user/%E7%B1%B3%E5%88%A9%E9%98%BF%E9%B2%81%E5%BE%B7\n[GET] \"https://tieba.baidu.com/home/main?un=米利阿鲁德\": 403 Forbidden\n",
      "id": "86266828598569984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/home/main?un=%E7%B1%B3%E5%88%A9%E9%98%BF%E9%B2%81%E5%BE%B7",
      "title": "米利阿鲁德 的贴吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/user/%E7%B1%B3%E5%88%A9%E9%98%BF%E9%B2%81%E5%BE%B7"
    }
  ]
}
```
