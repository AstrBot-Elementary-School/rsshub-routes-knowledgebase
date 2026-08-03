# 微博 - 关键词

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/weibo/keyword/:keyword/:routeParams?`
- Route Name: `关键词`
- Example: `/weibo/keyword/RSSHub`
- URL: `weibo.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod, Rongronggg9`
- Source Location: `keyword.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 你想订阅的微博关键词
- `routeParams`: 额外参数；请参阅上面的说明和表格


## Features
- `requireConfig`: [{"description": "", "name": "WEIBO_COOKIES", "optional": true}]
- `requirePuppeteer`: true
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
    "social-media"
  ],
  "example": "/weibo/keyword/RSSHub",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "WEIBO_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1142,
  "location": "keyword.ts",
  "maintainers": [
    "DIYgod",
    "Rongronggg9"
  ],
  "name": "关键词",
  "parameters": {
    "keyword": "你想订阅的微博关键词",
    "routeParams": "额外参数；请参阅上面的说明和表格"
  },
  "path": "/keyword/:keyword/:routeParams?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "又有人在微博提到obsidian了 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55288652424312832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://s.weibo.com/weibo/obsidian&b=1&nodup=1",
      "title": "又有人在微博提到obsidian了",
      "type": "feed",
      "url": "rsshub://weibo/keyword/obsidian"
    },
    {
      "description": "又有人在微博提到RSSHub了 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41147805276726295",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://s.weibo.com/weibo/RSSHub&b=1&nodup=1",
      "title": "又有人在微博提到RSSHub了",
      "type": "feed",
      "url": "rsshub://weibo/keyword/RSSHub"
    }
  ],
  "view": 1
}
```
