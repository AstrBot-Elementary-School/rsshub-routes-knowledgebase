# 哔哩哔哩 bilibili - UP 主投币视频

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/user/coin/:uid/:embed?`
- Route Name: `UP 主投币视频`
- Example: `/bilibili/user/coin/208259`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `coin.ts`
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
- `target`: `/user/coin/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/coin/208259",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 17,
  "location": "coin.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "UP 主投币视频",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/coin/:uid/:embed?",
  "radar": [
    {
      "source": [
        "space.bilibili.com/:uid"
      ],
      "target": "/user/coin/:uid"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "大闲人贾白 的 bilibili 投币视频 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59183499828667392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/549117578",
      "title": "大闲人贾白 的 bilibili 投币视频",
      "type": "feed",
      "url": "rsshub://bilibili/user/coin/549117578"
    },
    {
      "description": "undefined 的 bilibili 投币视频 - Powered by RSSHub",
      "errorAt": "2025-10-10T12:34:35.139Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "156121534429763584",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/3546738526784312",
      "title": "undefined 的 bilibili 投币视频",
      "type": "feed",
      "url": "rsshub://bilibili/user/coin/3546738526784312"
    }
  ]
}
```
