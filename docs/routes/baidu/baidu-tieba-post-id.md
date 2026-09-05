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
  "heat": 6,
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
  "topFeeds": [
    {
      "description": "回复：记录&讨论贴 和艾米的日常的最新回复 - Powered by RSSHub",
      "errorAt": "2026-01-28T05:24:41.240Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/p/9180129054?see_lz=0&pn=7000000&ajax=1\": 403 Forbidden\n",
      "id": "159278410530255872",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/p/9180129054?see_lz=0",
      "title": "回复：记录&讨论贴 和艾米的日常",
      "type": "feed",
      "url": "rsshub://baidu/tieba/post/9180129054"
    },
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
    }
  ]
}
```
