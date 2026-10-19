# 百度 - 帖子动态

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/baidu/tieba/post/:id`
- Route Name: `帖子动态`
- Example: `/baidu/tieba/post/686961453`
- URL: `www.baidu.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `u3u, FlanChanXwO`
- Source Location: `tieba/post.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 帖子 ID


## Features
- `requireConfig`: [{"description": "百度 cookie 值，用于需要登录的贴吧页面", "name": "BAIDU_COOKIE", "optional": true}]
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `tieba.baidu.com/p/:id`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/baidu/tieba/post/686961453",
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
  "heat": 7,
  "location": "tieba/post.ts",
  "maintainers": [
    "u3u",
    "FlanChanXwO"
  ],
  "name": "帖子动态",
  "parameters": {
    "id": "帖子 ID"
  },
  "path": "/tieba/post/:id",
  "radar": [
    {
      "source": [
        "tieba.baidu.com/p/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "都2052年了，UE还是没法做到啊的最新回复 - Powered by RSSHub",
      "errorAt": "2025-10-24T21:42:44.797Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/p/9797499443?see_lz=0&pn=7000000&ajax=1\": 403 Forbidden\n",
      "id": "157675353152621568",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/p/9797499443?see_lz=0",
      "title": "都2052年了，UE还是没法做到啊",
      "type": "feed",
      "url": "rsshub://baidu/tieba/post/9797499443"
    },
    {
      "description": "省通信管理局事实认定联通米粉卡限速服务不属于有效协议的最新回复 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1285465934365851648",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/p/11012631140?see_lz=0",
      "title": "省通信管理局事实认定联通米粉卡限速服务不属于有效协议",
      "type": "feed",
      "url": "rsshub://baidu/tieba/post/11012631140"
    }
  ]
}
```
