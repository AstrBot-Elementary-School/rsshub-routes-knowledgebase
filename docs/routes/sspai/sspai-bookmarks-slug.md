# 少数派 sspai - 用户收藏

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/sspai/bookmarks/:slug`
- Route Name: `用户收藏`
- Example: `/sspai/bookmarks/urfp0d9i`
- URL: `sspai.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `curly210102`
- Source Location: `bookmarks.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `slug`: 用户 slug，可在个人主页URL中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `sspai.com/u/:slug/bookmark_posts`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/sspai/bookmarks/urfp0d9i",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "bookmarks.ts",
  "maintainers": [
    "curly210102"
  ],
  "name": "用户收藏",
  "parameters": {
    "slug": "用户 slug，可在个人主页URL中找到"
  },
  "path": "/bookmarks/:slug",
  "radar": [
    {
      "source": [
        "sspai.com/u/:slug/bookmark_posts"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "少数派用户「少数派14596354」的全部收藏 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "110921126744929280",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sspai.com/u/ug91u8wp/bookmark_posts",
      "title": "少数派14596354 的全部收藏 - 少数派",
      "type": "feed",
      "url": "rsshub://sspai/bookmarks/ug91u8wp"
    },
    {
      "description": "少数派用户「即将成为南极探险大师」的全部收藏 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86230044663152640",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sspai.com/u/l42otgmg/bookmark_posts",
      "title": "即将成为南极探险大师 的全部收藏 - 少数派",
      "type": "feed",
      "url": "rsshub://sspai/bookmarks/l42otgmg"
    }
  ]
}
```
