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
  "heat": 381,
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
  "test": {
    "code": 0
  },
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
      "description": "本吧热帖: 1-【有奖找人】寻找本吧你心目中的大神！ 2-【250927】交易类内容提醒 3-【250628】【第六版】百度PT吧吧规 4-【百度PT吧黑名单！】 5-【260916】发几个PTT*4 6-【250525】求助帖水楼 7-【260730】想入个音乐站，求吧友们推荐下 8-【20260908】大佬们，求点红豆fans魔力 - Powered by RSSHub",
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
