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
      "description": "dengchunlai 的贴吧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "104695101579488257",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/home/main?un=dengchunlai",
      "title": "dengchunlai 的贴吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/user/dengchunlai"
    },
    {
      "description": "林子君 的贴吧 - Powered by RSSHub",
      "errorAt": "2026-07-26T02:15:19.346Z",
      "errorMessage": "Tieba user 林子◎君 not found\n",
      "id": "86267276958861312",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/home/main?un=%E6%9E%97%E5%AD%90%E2%97%8E%E5%90%9B",
      "title": "林子君 的贴吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/user/%E6%9E%97%E5%AD%90%E2%97%8E%E5%90%9B"
    }
  ]
}
```
