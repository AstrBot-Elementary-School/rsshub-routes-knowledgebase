# pixiv - User Activity

## Coverage
`index-only`

## Route
- Namespace: `pixiv`
- Namespace Name: `pixiv`
- Route Path: `/pixiv/user/:id`
- Route Name: `User Activity`
- Example: `/pixiv/user/15288095`
- URL: `www.pixiv.net`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: user id, available in user's homepage URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.pixiv.net/users/:id`
  - `www.pixiv.net/en/users/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/pixiv/user/15288095",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 37678,
  "location": "user.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "User Activity",
  "parameters": {
    "id": "user id, available in user's homepage URL"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "www.pixiv.net/users/:id",
        "www.pixiv.net/en/users/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "藤ちょこ（藤原） 的 pixiv 最新动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41679126529608704",
      "image": "https://pixiv.rss3.workers.dev/user-profile/img/2022/02/03/15/54/20/22159592_fce9f5c7a908c9b601dc7e9da7a412a3_170.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.pixiv.net/users/27517",
      "title": "藤ちょこ（藤原） 的 pixiv 动态",
      "type": "feed",
      "url": "rsshub://pixiv/user/27517"
    },
    {
      "description": "ATDAN- 的 pixiv 最新动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "52720946495913984",
      "image": "https://pixiv.rss3.workers.dev/user-profile/img/2024/06/21/11/54/21/26020985_15d347f457455848d0d56acaab7f180a_170.png",
      "ownerUserId": null,
      "siteUrl": "https://www.pixiv.net/users/6662895",
      "title": "ATDAN- 的 pixiv 动态",
      "type": "feed",
      "url": "rsshub://pixiv/user/6662895"
    }
  ],
  "view": 2
}
```
