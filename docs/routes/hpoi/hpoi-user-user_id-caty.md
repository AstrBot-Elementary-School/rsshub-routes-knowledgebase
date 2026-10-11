# Hpoi 手办维基 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `hpoi`
- Namespace Name: `Hpoi 手办维基`
- Route Path: `/hpoi/user/:user_id/:caty`
- Route Name: `用户动态`
- Example: `/hpoi/user/116297/buy`
- URL: `www.hpoi.net`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `DIYgod, luyuhuang`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user_id`: {"description": "用户ID"}
- `caty`: {"default": "buy", "description": "类别", "options": [{"label": "想买", "value": "want"}, {"label": "预定", "value": "preorder"}, {"label": "已入", "value": "buy"}, {"label": "关注", "value": "care"}, {"label": "有过", "value": "resell"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/hpoi/user/116297/buy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 86,
  "location": "user.ts",
  "maintainers": [
    "DIYgod",
    "luyuhuang"
  ],
  "name": "用户动态",
  "parameters": {
    "caty": {
      "default": "buy",
      "description": "类别",
      "options": [
        {
          "label": "想买",
          "value": "want"
        },
        {
          "label": "预定",
          "value": "preorder"
        },
        {
          "label": "已入",
          "value": "buy"
        },
        {
          "label": "关注",
          "value": "care"
        },
        {
          "label": "有过",
          "value": "resell"
        }
      ]
    },
    "user_id": {
      "description": "用户ID"
    }
  },
  "path": "/user/:user_id/:caty",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "DIYgod的手办 - 已入 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65439658397984768",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hpoi.net/user/116297/hobby?order=actionDate&view=2&favState=buy",
      "title": "DIYgod的手办 - 已入",
      "type": "feed",
      "url": "rsshub://hpoi/user/116297/buy"
    },
    {
      "description": "DIYgod的手办 - 想买 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65439580772686848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hpoi.net/user/116297/hobby?order=actionDate&view=2&favState=want",
      "title": "DIYgod的手办 - 想买",
      "type": "feed",
      "url": "rsshub://hpoi/user/116297/want"
    }
  ]
}
```
