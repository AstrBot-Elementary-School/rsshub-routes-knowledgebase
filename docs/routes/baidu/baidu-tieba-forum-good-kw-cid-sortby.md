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
  "topFeeds": [
    {
      "description": "本吧热帖: 1-最忧郁的入 2-今天心情不好想胡说八道 3-好久没联系的高中同桌突然联系我了 4-有没有聊聊天的 直接一点的那种 5-关于我开小号装纯情女高骗班上的??压抑?男这件事 6-《百度贴吧关于整治不良网络生态的公告》 7-鼠鼠我啊终于找到自己的大姐姐了? 8-江西彩礼局 9-我是老资历，按照俺们山东习俗，过年了小资历得给我磕头！ 10-为什么互助板块没有了 11-晚辈对我动手动脚怎么办 - Powered by RSSHub",
      "errorAt": "2026-02-25T03:24:21.114Z",
      "errorMessage": "Baidu Tieba RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#baidu\">BAIDU_COOKIE</a>\n",
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
