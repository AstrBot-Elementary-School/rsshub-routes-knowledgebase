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
- Maintainers: `igxlin, nczitzk, FlanChanXwO`
- Source Location: `tieba/user.ts`
- Source Module: `_None_`

## Description
用户 ID 可以通过打开用户的主页后查看地址栏的 `un` 字段来获取。

## Parameters
- `uid`: 用户 ID


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
  "description": "用户 ID 可以通过打开用户的主页后查看地址栏的 `un` 字段来获取。",
  "example": "/baidu/tieba/user/斗鱼游戏君",
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
  "heat": 12,
  "location": "tieba/user.ts",
  "maintainers": [
    "igxlin",
    "nczitzk",
    "FlanChanXwO"
  ],
  "name": "用户帖子",
  "parameters": {
    "uid": "用户 ID"
  },
  "path": "/tieba/user/:uid",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "米利阿鲁德 的贴吧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86266828598569984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/home/main?un=%E7%B1%B3%E5%88%A9%E9%98%BF%E9%B2%81%E5%BE%B7",
      "title": "米利阿鲁德 的贴吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/user/%E7%B1%B3%E5%88%A9%E9%98%BF%E9%B2%81%E5%BE%B7"
    },
    {
      "description": "阳光下的咪西 的贴吧 - Powered by RSSHub",
      "errorAt": "2026-04-05T11:51:29.923Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/home/main?un=阳光下的咪西\": 403 Forbidden\n",
      "id": "69911701157875712",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/home/main?un=%E9%98%B3%E5%85%89%E4%B8%8B%E7%9A%84%E5%92%AA%E8%A5%BF",
      "title": "阳光下的咪西 的贴吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/user/%E9%98%B3%E5%85%89%E4%B8%8B%E7%9A%84%E5%92%AA%E8%A5%BF"
    }
  ]
}
```
