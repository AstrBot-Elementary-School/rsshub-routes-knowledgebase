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
- Source Location: `tieba/user.tsx`
- Source Module: `_None_`

## Description
用户 ID 可以通过打开用户的主页后查看地址栏的 `un` 字段来获取。

## Parameters
- `uid`: 用户 ID


## Features
- `requireConfig`: [{"description": "百度 cookie 值，用于需要登录的贴吧页面", "name": "BAIDU_COOKIE", "optional": false}]
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

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
        "optional": false
      }
    ],
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 12,
  "location": "tieba/user.tsx",
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
  "topFeeds": [
    {
      "description": "dengchunlai 的贴吧 - Powered by RSSHub",
      "errorAt": "2026-06-28T17:36:38.883Z",
      "errorMessage": "Baidu Tieba RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#baidu\">BAIDU_COOKIE</a>\n",
      "id": "104695101579488257",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/home/main?un=dengchunlai",
      "title": "dengchunlai 的贴吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/user/dengchunlai"
    },
    {
      "description": "K盘音 的贴吧 - Powered by RSSHub",
      "errorAt": "2025-11-16T04:13:10.675Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/home/main?un=TheKickInside\": 403 Forbidden\n",
      "id": "197372964709496832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/home/main?un=TheKickInside",
      "title": "K盘音 的贴吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/user/TheKickInside"
    }
  ]
}
```
