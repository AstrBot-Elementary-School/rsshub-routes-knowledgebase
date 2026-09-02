# 什么值得买 - 好文

## Coverage
`index-only`

## Route
- Namespace: `smzdm`
- Namespace Name: `什么值得买`
- Route Path: `/smzdm/haowen/:day?`
- Route Name: `好文`
- Example: `/smzdm/haowen/1`
- URL: `post.smzdm.com`
- Language: `_None_`
- Categories: `shopping, popular`
- Maintainers: `LogicJake, pseudoyu`
- Source Location: `haowen.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `day`: {"default": "1", "description": "以天为时间跨度，默认为 `1`", "options": [{"label": "今日热门", "value": "1"}, {"label": "周热门", "value": "7"}, {"label": "月热门", "value": "30"}]}


## Features
- `requireConfig`: [{"description": "什么值得买登录后的 Cookie 值", "name": "SMZDM_COOKIE"}]
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
    "shopping",
    "popular"
  ],
  "example": "/smzdm/haowen/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "什么值得买登录后的 Cookie 值",
        "name": "SMZDM_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2019,
  "location": "haowen.ts",
  "maintainers": [
    "LogicJake",
    "pseudoyu"
  ],
  "name": "好文",
  "parameters": {
    "day": {
      "default": "1",
      "description": "以天为时间跨度，默认为 `1`",
      "options": [
        {
          "label": "今日热门",
          "value": "1"
        },
        {
          "label": "周热门",
          "value": "7"
        },
        {
          "label": "月热门",
          "value": "30"
        }
      ]
    }
  },
  "path": "/haowen/:day?",
  "topFeeds": [
    {
      "description": "周热门-什么值得买好文 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41423034778090522",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://post.smzdm.com/hot_7/",
      "title": "周热门-什么值得买好文",
      "type": "feed",
      "url": "rsshub://smzdm/haowen/7"
    },
    {
      "description": "今日热门-什么值得买好文 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42520977153904661",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://post.smzdm.com/hot_1/",
      "title": "今日热门-什么值得买好文",
      "type": "feed",
      "url": "rsshub://smzdm/haowen/1"
    }
  ]
}
```
