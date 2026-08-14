# 网易公开课 - 歌单歌曲

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/163/music/playlist/:id`
- Route Name: `歌单歌曲`
- Example: `/163/music/playlist/35798529`
- URL: `163.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `DIYgod`
- Source Location: `music/playlist.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 歌单 id, 可在歌单页 URL 中找到


## Features
- `requireConfig`: [{"description": "网易云音乐登陆后的 cookie 值，可在浏览器控制台通过`document.cookie`获取。", "name": "NCM_COOKIES", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `music.163.com/playlist`
- `target`: `/music/playlist/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/163/music/playlist/35798529",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "网易云音乐登陆后的 cookie 值，可在浏览器控制台通过`document.cookie`获取。",
        "name": "NCM_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 313,
  "location": "music/playlist.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "歌单歌曲",
  "parameters": {
    "id": "歌单 id, 可在歌单页 URL 中找到"
  },
  "path": "/music/playlist/:id",
  "radar": [
    {
      "source": [
        "music.163.com/playlist"
      ],
      "target": "/music/playlist/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "网易云音乐歌单 - DIYgod喜欢的音乐 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60553915874505728",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://music.163.com/#/playlist?id=35798529",
      "title": "DIYgod喜欢的音乐",
      "type": "feed",
      "url": "rsshub://163/music/playlist/35798529"
    },
    {
      "description": "网易云音乐歌单 - Khat喵喜欢的音乐 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67058999583684608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://music.163.com/#/playlist?id=508862123",
      "title": "Khat喵喜欢的音乐",
      "type": "feed",
      "url": "rsshub://163/music/playlist/508862123"
    }
  ]
}
```
