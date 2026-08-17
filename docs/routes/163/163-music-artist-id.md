# 网易公开课 - 歌手专辑

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/163/music/artist/:id`
- Route Name: `歌手专辑`
- Example: `/163/music/artist/2116`
- URL: `163.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `metowolf`
- Source Location: `music/artist.ts`
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
  - `music.163.com/artist/album`
- `target`: `/music/artist/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/163/music/artist/2116",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 91,
  "location": "music/artist.ts",
  "maintainers": [
    "metowolf"
  ],
  "name": "歌手专辑",
  "parameters": {
    "id": "歌手 id, 可在歌手详情页 URL 中找到"
  },
  "path": "/music/artist/:id",
  "radar": [
    {
      "source": [
        "music.163.com/artist/album"
      ],
      "target": "/music/artist/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "网易云音乐歌手专辑 - 塞壬唱片-MSR - Powered by RSSHub",
      "errorAt": "2026-08-15T22:53:20.035Z",
      "errorMessage": "200 ",
      "id": "65815027588922368",
      "image": "https://p1.music.126.net/J8mrQPu9oKSva8ziYrGmJQ==/109951164481886292.jpg",
      "ownerUserId": null,
      "siteUrl": "https://music.163.com/#/artist/album?id=32540734",
      "title": "塞壬唱片-MSR",
      "type": "feed",
      "url": "rsshub://163/music/artist/32540734"
    },
    {
      "description": "网易云音乐歌手专辑 - betcover!! - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "129229946062307328",
      "image": "https://p2.music.126.net/lrJiX7k6gV4GJorJUj8-zw==/109951171287877555.jpg",
      "ownerUserId": null,
      "siteUrl": "https://music.163.com/#/artist/album?id=30986109",
      "title": "betcover!!",
      "type": "feed",
      "url": "rsshub://163/music/artist/30986109"
    }
  ]
}
```
