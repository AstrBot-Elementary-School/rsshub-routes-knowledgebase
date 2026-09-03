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
  "topFeeds": [
    {
      "description": "回复：2024主机配置新帖的最新回复 - Powered by RSSHub",
      "errorAt": "2025-03-29T11:22:25.149Z",
      "errorMessage": "Baidu Tieba RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#baidu\">BAIDU_COOKIE</a>\n",
      "id": "73922058150935552",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/p/9083587772?see_lz=1",
      "title": "【只看楼主】回复：2024主机配置新帖",
      "type": "feed",
      "url": "rsshub://baidu/tieba/post/lz/9083587772"
    },
    {
      "description": "回复：2024电脑配置新帖的最新回复 - Powered by RSSHub",
      "errorAt": "2025-04-23T06:23:58.705Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/p/8884338949?see_lz=1&pn=7000000&ajax=1\": 403 Forbidden\n",
      "id": "73923057056335872",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/p/8884338949?see_lz=1",
      "title": "【只看楼主】回复：2024电脑配置新帖",
      "type": "feed",
      "url": "rsshub://baidu/tieba/post/lz/8884338949"
    }
  ]
}
```
