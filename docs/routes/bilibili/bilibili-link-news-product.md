# 哔哩哔哩 bilibili - link 公告

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/link/news/:product`
- Route Name: `link 公告`
- Example: `/bilibili/link/news/live`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Qixingchen`
- Source Location: `link-news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `product`: 公告分类, 包括 直播:live 小视频:vc 相簿:wh


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
    "social-media"
  ],
  "example": "/bilibili/link/news/live",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "link-news.ts",
  "maintainers": [
    "Qixingchen"
  ],
  "name": "link 公告",
  "parameters": {
    "product": "公告分类, 包括 直播:live 小视频:vc 相簿:wh"
  },
  "path": "/link/news/:product",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "bilibili 直播公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66134159856662528",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://link.bilibili.com/p/eden/news#/?tab=live&tag=all&page_no=1",
      "title": "bilibili 直播公告",
      "type": "feed",
      "url": "rsshub://bilibili/link/news/live"
    }
  ]
}
```
