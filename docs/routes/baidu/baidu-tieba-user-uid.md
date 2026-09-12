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
      "description": "星芒√月幻 的贴吧 - Powered by RSSHub",
      "errorAt": "2025-11-02T10:12:38.476Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/home/main?un=星芒√月幻\": 403 Forbidden\n",
      "id": "105199795080017920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/home/main?un=%E6%98%9F%E8%8A%92%E2%88%9A%E6%9C%88%E5%B9%BB",
      "title": "星芒√月幻 的贴吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/user/%E6%98%9F%E8%8A%92%E2%88%9A%E6%9C%88%E5%B9%BB"
    },
    {
      "description": "天马失望 的贴吧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "200148619577121792",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/home/main?un=%E5%A4%A9%E9%A9%AC%E5%A4%B1%E6%9C%9B",
      "title": "天马失望 的贴吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/user/%E5%A4%A9%E9%A9%AC%E5%A4%B1%E6%9C%9B"
    }
  ]
}
```
