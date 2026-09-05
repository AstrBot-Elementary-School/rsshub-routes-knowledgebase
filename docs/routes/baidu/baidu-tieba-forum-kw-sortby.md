# 百度 - 帖子列表

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/baidu/tieba/forum/:kw/:sortBy?`
- Route Name: `帖子列表`
- Example: `/baidu/tieba/forum/孙笑川`
- URL: `www.baidu.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `u3u, FlanChanXwO`
- Source Location: `tieba/forum.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `kw`: 吧名
- `sortBy`: 排序方式：`created`, `replied`。默认为 `created`


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
  "example": "/baidu/tieba/forum/孙笑川",
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
  "heat": 372,
  "location": "tieba/forum.ts",
  "maintainers": [
    "u3u",
    "FlanChanXwO"
  ],
  "name": "帖子列表",
  "parameters": {
    "kw": "吧名",
    "sortBy": "排序方式：`created`, `replied`。默认为 `created`"
  },
  "path": "/tieba/forum/:kw/:sortBy?",
  "topFeeds": [
    {
      "description": "孙笑川吧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70443380786893824",
      "image": null,
      "ownerUserId": "75347449854502912",
      "siteUrl": "https://tieba.baidu.com/f?kw=%E5%AD%99%E7%AC%91%E5%B7%9D",
      "title": "孙笑川吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/forum/%E5%AD%99%E7%AC%91%E5%B7%9D"
    },
    {
      "description": "pt吧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65268258673897472",
      "image": null,
      "ownerUserId": "55797500342129664",
      "siteUrl": "https://tieba.baidu.com/f?kw=pt",
      "title": "pt吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/forum/pt"
    }
  ]
}
```
