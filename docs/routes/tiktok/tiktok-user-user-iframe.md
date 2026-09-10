# TikTok - User

## Coverage
`index-only`

## Route
- Namespace: `tiktok`
- Namespace Name: `TikTok`
- Route Path: `/tiktok/user/:user/:iframe?`
- Route Name: `User`
- Example: `/tiktok/user/@linustech/true`
- URL: `tiktok.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: User ID, including @
- `iframe`: Use the official iframe to embed the video, which allows you to view the video if the default option does not work. Default to `false`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.tiktok.com/:user`
- `target`: `/user/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/tiktok/user/@linustech/true",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User",
  "parameters": {
    "iframe": "Use the official iframe to embed the video, which allows you to view the video if the default option does not work. Default to `false`",
    "user": "User ID, including @"
  },
  "path": "/user/:user/:iframe?",
  "radar": [
    {
      "source": [
        "www.tiktok.com/:user"
      ],
      "target": "/user/:user"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Cuenta oficial de TikTok Policía Nacional de Colombia. 🇨🇴👮🏻‍♂️👮🏻‍♀️ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1118368279467786240",
      "image": "https://p16-common-sign.tiktokcdn-eu.com/tos-alisg-avt-0068/3282e877c0ed5a7e1d7bac9f192e7033~tplv-tiktokx-cropcenter:100:100.jpeg?dr=10399&refresh_token=f490a24f&x-expires=1789117200&x-signature=Kbfqhb4AUHs0hLl1CC8%2FoBvoGgk%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=81f88b70&idc=no1a",
      "ownerUserId": null,
      "siteUrl": "https://www.tiktok.com/@policiadecolombia",
      "title": "Policía de Colombia (@policiadecolombia) | TikTok",
      "type": "feed",
      "url": "rsshub://tiktok/user/@policiadecolombia"
    },
    {
      "description": "@kittilyse on Instagram :) COMMISSIONS OPEN.. Check IG - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1278676995072196608",
      "image": "https://p16-common-sign.tiktokcdn-eu.com/tos-alisg-avt-0068/ac1dc85419c1c34bab0ff508e8847c8b~tplv-tiktokx-cropcenter:100:100.jpeg?dr=10399&refresh_token=e3b5e986&x-expires=1789120800&x-signature=wTy2XZ9DMycVqsRTXms5CogAHKM%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=81f88b70&idc=no1a",
      "ownerUserId": null,
      "siteUrl": "https://www.tiktok.com/@kittilyse",
      "title": "kittilyse [Commissions Open] (@kittilyse) | TikTok",
      "type": "feed",
      "url": "rsshub://tiktok/user/@kittilyse/true"
    }
  ]
}
```
