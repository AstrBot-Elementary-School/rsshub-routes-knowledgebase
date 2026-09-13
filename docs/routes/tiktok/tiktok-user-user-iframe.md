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
      "image": "https://p16-common-sign.tiktokcdn-eu.com/tos-alisg-avt-0068/3282e877c0ed5a7e1d7bac9f192e7033~tplv-tiktokx-cropcenter:100:100.jpeg?dr=10399&refresh_token=2c77e82b&x-expires=1789380000&x-signature=ZjkpkV3saORYZCi4ZucelGya0XE%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=81f88b70&idc=no1a",
      "ownerUserId": null,
      "siteUrl": "https://www.tiktok.com/@policiadecolombia",
      "title": "Policía de Colombia (@policiadecolombia) | TikTok",
      "type": "feed",
      "url": "rsshub://tiktok/user/@policiadecolombia"
    },
    {
      "description": "Pony artist 🎠 ENG/FR I use Clip Studio Paint EX for animation and illustration ! ❌️ COMMISSIONS CLOSED ! Active on Insta and YT - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1278674266593558528",
      "image": "https://p19-common-sign.tiktokcdn-eu.com/tos-no1a-avt-0068c001-no/14b1c1420174ce022d506dae4d15bcd9~tplv-tiktokx-cropcenter:100:100.jpeg?dr=10399&refresh_token=e980b87d&x-expires=1789369200&x-signature=mmULElLHcOJ2N0w0EHGbP3WsQ0E%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=81f88b70&idc=no1a",
      "ownerUserId": null,
      "siteUrl": "https://www.tiktok.com/@lovely.brew",
      "title": "💕 LovelyBrew ☕️ (@lovely.brew) | TikTok",
      "type": "feed",
      "url": "rsshub://tiktok/user/@lovely.brew/true"
    }
  ]
}
```
