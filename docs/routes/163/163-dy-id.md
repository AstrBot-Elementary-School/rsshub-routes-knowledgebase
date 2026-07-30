# 网易公开课 - 更新

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/163/dy/:id`
- Route Name: `更新`
- Example: `/163/dy/W4983108759592548559`
- URL: `163.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `HendricksZheng`
- Source Location: `dy.ts`
- Source Module: `_None_`

## Description
1. 在[网易号搜索页面](https://dy.163.com/v2/media/tosearch.html) 搜索想要订阅的网易号。
2. 打开网易号的任意文章。
3. 查看源代码，搜索 `data-wemediaid`，查看紧随其后的引号内的属性值（类似 `W1966190042455428950`）即为网易号 ID。

## Parameters
- `id`: 网易号 ID


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
    "new-media"
  ],
  "description": "1. 在[网易号搜索页面](https://dy.163.com/v2/media/tosearch.html) 搜索想要订阅的网易号。\n2. 打开网易号的任意文章。\n3. 查看源代码，搜索 `data-wemediaid`，查看紧随其后的引号内的属性值（类似 `W1966190042455428950`）即为网易号 ID。",
  "example": "/163/dy/W4983108759592548559",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 39,
  "location": "dy.ts",
  "maintainers": [
    "HendricksZheng"
  ],
  "name": "更新",
  "parameters": {
    "id": "网易号 ID"
  },
  "path": "/dy/:id",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "中国主流财经全媒体平台。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "130488664186003456",
      "image": "https://nimg.ws.126.net/?url=http://dingyue.ws.126.net/2021/0510/e3aaf33fj00qsvpi60003c0004g004gc.jpg&thumbnail=160y160&quality=80&type=jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.163.com/dy/media/T1374537989920.html",
      "title": "网易号 - 每日经济新闻",
      "type": "feed",
      "url": "rsshub://163/dy/W7833496354712145699"
    },
    {
      "description": "基本就是讲游戏 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75380151210504192",
      "image": "https://nimg.ws.126.net/?url=http://dingyue.ws.126.net/rWGD5AEjpGC44D1S3QW1RMpLS=WvMkP1e2eAIAFhUurxv1494839069359.jpg&thumbnail=160y160&quality=80&type=jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.163.com/dy/media/T1494839070435.html",
      "title": "网易号 - BB姬",
      "type": "feed",
      "url": "rsshub://163/dy/W7415853145461076134"
    }
  ]
}
```
