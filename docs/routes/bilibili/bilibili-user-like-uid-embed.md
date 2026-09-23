# 哔哩哔哩 bilibili - UP 主点赞视频

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/user/like/:uid/:embed?`
- Route Name: `UP 主点赞视频`
- Example: `/bilibili/user/like/208259`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `ygguorun`
- Source Location: `like.ts`
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
- `target`: `/user/like/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/like/208259",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 46,
  "location": "like.ts",
  "maintainers": [
    "ygguorun"
  ],
  "name": "UP 主点赞视频",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/like/:uid/:embed?",
  "radar": [
    {
      "source": [
        "space.bilibili.com/:uid"
      ],
      "target": "/user/like/:uid"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "bili_1287649879 的 bilibili 点赞视频 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "91131582967148544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/1287649879",
      "title": "bili_1287649879 的 bilibili 点赞视频",
      "type": "feed",
      "url": "rsshub://bilibili/user/like/1287649879"
    },
    {
      "description": "undefined 的 bilibili 点赞视频 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "83420536653454336",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/1737838338",
      "title": "undefined 的 bilibili 点赞视频",
      "type": "feed",
      "url": "rsshub://bilibili/user/like/1737838338"
    }
  ]
}
```
