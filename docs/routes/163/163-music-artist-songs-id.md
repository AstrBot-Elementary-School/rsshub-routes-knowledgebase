# 网易公开课 - 歌手歌曲

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/163/music/artist/songs/:id`
- Route Name: `歌手歌曲`
- Example: `/163/music/artist/songs/2116`
- URL: `163.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `ZhongMingKun`
- Source Location: `music/artist-songs.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 歌手 id, 可在歌手详情页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `music.163.com/artist`
- `target`: `/music/artist/songs/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/163/music/artist/songs/2116",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 56,
  "location": "music/artist-songs.ts",
  "maintainers": [
    "ZhongMingKun"
  ],
  "name": "歌手歌曲",
  "parameters": {
    "id": "歌手 id, 可在歌手详情页 URL 中找到"
  },
  "path": "/music/artist/songs/:id",
  "radar": [
    {
      "source": [
        "music.163.com/artist"
      ],
      "target": "/music/artist/songs/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "网易云音乐 - 歌手歌曲 - G.E.M.邓紫棋 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "142474967276926976",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://music.163.com/#/artist?id=7763",
      "title": "G.E.M.邓紫棋 - 歌手歌曲",
      "type": "feed",
      "url": "rsshub://163/music/artist/songs/7763"
    },
    {
      "description": "网易云音乐 - 歌手歌曲 - 薛之谦 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86308435497826304",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://music.163.com/#/artist?id=5781",
      "title": "薛之谦 - 歌手歌曲",
      "type": "feed",
      "url": "rsshub://163/music/artist/songs/5781"
    }
  ]
}
```
