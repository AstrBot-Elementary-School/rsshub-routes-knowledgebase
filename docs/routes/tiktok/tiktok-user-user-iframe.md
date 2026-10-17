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
  "heat": 10,
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
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Sponsorships Contact - itsboyinspace@gmail.com - ALT Account ➡️ @BenOnEarth - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1294380587930222592",
      "image": "https://p16-common-sign.tiktokcdn-eu.com/tos-maliva-avt-0068/b30be983bf7d4626f133d94aaee6f31b~tplv-tiktokx-cropcenter:100:100.jpeg?dr=10399&refresh_token=599ba2b4&x-expires=1792321200&x-signature=sGMoYTRAkqG%2BjpknmAdtvMNQVUU%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=81f88b70&idc=no1a",
      "ownerUserId": null,
      "siteUrl": "https://www.tiktok.com/@itsboyinspace",
      "title": "Ben Pendergast (@itsboyinspace) | TikTok",
      "type": "feed",
      "url": "rsshub://tiktok/user/@itsboyinspace"
    },
    {
      "description": "Cuenta oficial de TikTok Policía Nacional de Colombia. 🇨🇴👮🏻‍♂️👮🏻‍♀️ #DiosYPatria - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1118368279467786240",
      "image": "https://p16-common-sign.tiktokcdn-eu.com/tos-alisg-avt-0068/3282e877c0ed5a7e1d7bac9f192e7033~tplv-tiktokx-cropcenter:100:100.jpeg?dr=10399&refresh_token=15c5e778&x-expires=1792011600&x-signature=8r34ZtHtrOc%2F9K1Oh%2BWJtjijTaQ%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=81f88b70&idc=no1a",
      "ownerUserId": null,
      "siteUrl": "https://www.tiktok.com/@policiadecolombia",
      "title": "Policía de Colombia (@policiadecolombia) | TikTok",
      "type": "feed",
      "url": "rsshub://tiktok/user/@policiadecolombia"
    }
  ]
}
```
