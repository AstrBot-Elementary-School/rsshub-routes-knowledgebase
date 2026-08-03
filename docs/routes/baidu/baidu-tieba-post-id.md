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
- Source Location: `tieba/post.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 帖子 ID


## Features
- `requireConfig`: [{"description": "百度 cookie 值，用于需要登录的贴吧页面", "name": "BAIDU_COOKIE", "optional": false}]
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

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
        "optional": false
      }
    ],
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "tieba/post.tsx",
  "maintainers": [
    "u3u",
    "FlanChanXwO"
  ],
  "name": "帖子动态",
  "parameters": {
    "id": "帖子 ID"
  },
  "path": [
    "/tieba/post/:id",
    "/tieba/post/lz/:id"
  ],
  "radar": [
    {
      "source": [
        "tieba.baidu.com/p/:id"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "回复：【纯心相依】 快了 plus........的最新回复 - Powered by RSSHub",
      "errorAt": "2026-06-04T22:22:07.147Z",
      "errorMessage": "Baidu Tieba RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#baidu\">BAIDU_COOKIE</a>\n",
      "id": "104695101579488256",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/p/8109266086?see_lz=0",
      "title": "回复：【纯心相依】 快了 plus........",
      "type": "feed",
      "url": "rsshub://baidu/tieba/post/8109266086"
    },
    {
      "description": "回复：【模组汉化发布】重铸整合发布的最新回复 - Powered by RSSHub",
      "errorAt": "2026-05-30T00:41:37.252Z",
      "errorMessage": "Baidu Tieba RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#baidu\">BAIDU_COOKIE</a>\n",
      "id": "105885254821548032",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/p/9208385243?see_lz=0",
      "title": "回复：【模组汉化发布】重铸整合发布",
      "type": "feed",
      "url": "rsshub://baidu/tieba/post/9208385243"
    }
  ]
}
```
