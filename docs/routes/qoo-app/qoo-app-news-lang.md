# QooApp - News

## Coverage
`index-only`

## Route
- Namespace: `qoo-app`
- Namespace Name: `QooApp`
- Route Path: `/qoo-app/news/:lang?`
- Route Name: `News`
- Example: `/qoo-app/news/en`
- URL: `apps.qoo-app.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 中文 | English |
| ---- | ------- |
|      | en      |

## Parameters
- `lang`: Language, see the table below, empty means `中文`


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
  "description": "| 中文 | English |\n| ---- | ------- |\n|      | en      |",
  "example": "/qoo-app/news/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 12,
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "News",
  "parameters": {
    "lang": "Language, see the table below, empty means `中文`"
  },
  "path": "/news/:lang?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "QooApp 是專注二次元的專業平台，旨在聚集世界各地熱愛ACG的用戶，為他們創造有價值的服務和產品。從遊戲商店、新聞資訊、玩家社群，到線下聚會、漫畫閱讀、遊戲發行——QooApp不斷進化中，拓展突破次元的遊玩體驗。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67202305898513410",
      "image": "https://o.qoo-img.com/statics.qoo-app.com/cdn/img/QooApp_512.v-0d0fd2.png",
      "ownerUserId": null,
      "siteUrl": "https://news.qoo-app.com/",
      "title": "QooApp : Anime Game Platform",
      "type": "feed",
      "url": "rsshub://qoo-app/news"
    },
    {
      "description": "QooApp is a professional platform specialising in Anime, Comics and Games (ACG) culture. We aim to unite ACG fans around the globe and help them as thoroughly as we can. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "98963537844495360",
      "image": "https://o.qoo-img.com/statics.qoo-app.com/cdn/img/QooApp_512.v-0d0fd2.png",
      "ownerUserId": null,
      "siteUrl": "https://news.qoo-app.com/en",
      "title": "QooApp : Anime Game Platform",
      "type": "feed",
      "url": "rsshub://qoo-app/news/en"
    }
  ]
}
```
