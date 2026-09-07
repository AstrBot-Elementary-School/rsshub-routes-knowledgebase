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
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "【纯心相依】 快了 plus........的最新回复 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "104695101579488256",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/p/8109266086?see_lz=0",
      "title": "【纯心相依】 快了 plus........",
      "type": "feed",
      "url": "rsshub://baidu/tieba/post/8109266086"
    },
    {
      "description": "【模组汉化发布】重铸整合发布的最新回复 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "105885254821548032",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/p/9208385243?see_lz=0",
      "title": "【模组汉化发布】重铸整合发布",
      "type": "feed",
      "url": "rsshub://baidu/tieba/post/9208385243"
    }
  ]
}
```
