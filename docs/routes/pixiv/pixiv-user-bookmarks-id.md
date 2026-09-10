# pixiv - User Bookmark

## Coverage
`index-only`

## Route
- Namespace: `pixiv`
- Namespace Name: `pixiv`
- Route Path: `/pixiv/user/bookmarks/:id`
- Route Name: `User Bookmark`
- Example: `/pixiv/user/bookmarks/15288095`
- URL: `www.pixiv.net`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `EYHN`
- Source Location: `bookmarks.ts`
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
  - `www.pixiv.net/users/:id/bookmarks/artworks`
  - `www.pixiv.net/en/users/:id/bookmarks/artworks`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/pixiv/user/bookmarks/15288095",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 21,
  "location": "bookmarks.ts",
  "maintainers": [
    "EYHN"
  ],
  "name": "User Bookmark",
  "parameters": {
    "id": "user id, available in user's homepage URL"
  },
  "path": "/user/bookmarks/:id",
  "radar": [
    {
      "source": [
        "www.pixiv.net/users/:id/bookmarks/artworks",
        "www.pixiv.net/en/users/:id/bookmarks/artworks"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "DIYgod 的 pixiv 最新收藏 - Powered by RSSHub",
      "errorAt": "2026-09-09T05:35:55.405Z",
      "errorMessage": "[GET] \"https://app-api.pixiv.net/v1/user/detail?user_id=15288095\": 403 Forbidden\n",
      "id": "57236269888968706",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pixiv.net/users/15288095/bookmarks/artworks",
      "title": "DIYgod 的收藏",
      "type": "feed",
      "url": "rsshub://pixiv/user/bookmarks/15288095"
    },
    {
      "description": "Egami(えがみ) 的 pixiv 最新收藏 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "198288028097028112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pixiv.net/users/64390150/bookmarks/artworks",
      "title": "Egami(えがみ) 的收藏",
      "type": "feed",
      "url": "rsshub://pixiv/user/bookmarks/64390150"
    }
  ]
}
```
