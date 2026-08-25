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
  "heat": 2,
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
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "@policiadecolombia 828.9k Followers, 13 Following, 8.2m Likes - Watch awesome short videos created by Policía de Colombia - Powered by RSSHub",
      "errorAt": "2026-05-20T00:38:28.972Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "1118368279467786240",
      "image": "https://p16-common-sign.tiktokcdn.com/tos-maliva-avt-0068/b0997e2e6fe717f31736b97de7253aa4~tplv-tiktokx-cropcenter:1080:1080.jpeg?dr=14579&refresh_token=b8d90eb6&x-expires=1779379200&x-signature=TzthJcVwd65eQaFN%2BM7aodDqaN0%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=81f88b70&idc=my",
      "ownerUserId": null,
      "siteUrl": "https://www.tiktok.com/@policiadecolombia",
      "title": "Policía de Colombia on TikTok",
      "type": "feed",
      "url": "rsshub://tiktok/user/@policiadecolombia"
    }
  ]
}
```
