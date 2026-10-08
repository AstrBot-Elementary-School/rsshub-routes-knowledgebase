# 百度 - 精品帖子

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/baidu/tieba/forum/good/:kw/:cid?/:sortBy?`
- Route Name: `精品帖子`
- Example: `/baidu/tieba/forum/good/女图`
- URL: `www.baidu.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `u3u, FlanChanXwO`
- Source Location: `tieba/forum-good.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `kw`: 吧名
- `cid`: 精品分类，默认为 `0`（全部分类），如果不传 `cid` 则获取全部分类
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
  "example": "/baidu/tieba/forum/good/女图",
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
  "heat": 84,
  "location": "tieba/forum-good.ts",
  "maintainers": [
    "u3u",
    "FlanChanXwO"
  ],
  "name": "精品帖子",
  "parameters": {
    "cid": "精品分类，默认为 `0`（全部分类），如果不传 `cid` 则获取全部分类",
    "kw": "吧名",
    "sortBy": "排序方式：`created`, `replied`。默认为 `created`"
  },
  "path": "/tieba/forum/good/:kw/:cid?/:sortBy?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "孙笑川吧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59474368564173828",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/f?kw=%E5%AD%99%E7%AC%91%E5%B7%9D",
      "title": "孙笑川吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/forum/good/%E5%AD%99%E7%AC%91%E5%B7%9D"
    },
    {
      "description": "弱智吧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84969943583648768",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/f?kw=%E5%BC%B1%E6%99%BA",
      "title": "弱智吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/forum/good/%E5%BC%B1%E6%99%BA"
    }
  ]
}
```
