# 哔哩哔哩 bilibili - UP 主默认收藏夹

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/user/fav/:uid/:embed?`
- Route Name: `UP 主默认收藏夹`
- Example: `/bilibili/user/fav/2267573`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `user-fav.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到
- `embed`: 默认为开启内嵌视频, 任意值为关闭


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
  - `space.bilibili.com/:uid`
  - `space.bilibili.com/:uid/favlist`
- `target`: `/user/fav/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/fav/2267573",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 36,
  "location": "user-fav.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "UP 主默认收藏夹",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/fav/:uid/:embed?",
  "radar": [
    {
      "source": [
        "space.bilibili.com/:uid",
        "space.bilibili.com/:uid/favlist"
      ],
      "target": "/user/fav/:uid"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "undefined 的 bilibili 收藏夹 - Powered by RSSHub",
      "errorAt": "2025-10-13T10:49:28.910Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "72888942362905600",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/3546568336607683/#/favlist",
      "title": "undefined 的 bilibili 收藏夹",
      "type": "feed",
      "url": "rsshub://bilibili/user/fav/3546568336607683"
    },
    {
      "description": "undefined 的 bilibili 收藏夹 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "90023075203380224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/3546564563831207/#/favlist",
      "title": "undefined 的 bilibili 收藏夹",
      "type": "feed",
      "url": "rsshub://bilibili/user/fav/3546564563831207"
    }
  ]
}
```
