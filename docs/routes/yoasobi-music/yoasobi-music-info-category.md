# Yoasobi Official - News & Biography

## Coverage
`index-only`

## Route
- Namespace: `yoasobi-music`
- Namespace Name: `Yoasobi Official`
- Route Path: `/yoasobi-music/info/:category?`
- Route Name: `News & Biography`
- Example: `/yoasobi-music/info/news`
- URL: `www.yoasobi-music.jp/`
- Language: `_None_`
- Categories: `live`
- Maintainers: `Kiotlin`
- Source Location: `info.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: `news`, `biography`


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
  - `www.yoasobi-music.jp/`
  - `www.yoasobi-music.jp/:category`
- `target`: `/info/:category`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/yoasobi-music/info/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "info.tsx",
  "maintainers": [
    "Kiotlin"
  ],
  "name": "News & Biography",
  "parameters": {
    "category": "`news`, `biography`"
  },
  "path": "/info/:category?",
  "radar": [
    {
      "source": [
        "www.yoasobi-music.jp/",
        "www.yoasobi-music.jp/:category"
      ],
      "target": "/info/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Yoasobi's latest biography - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59199683879800832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yoasobi-music.jp/biography",
      "title": "LATEST BIOGRAPHY",
      "type": "feed",
      "url": "rsshub://yoasobi-music/info/biography"
    },
    {
      "description": "Yoasobi's latest news - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59198663955091456",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yoasobi-music.jp/news",
      "title": "LATEST NEWS",
      "type": "feed",
      "url": "rsshub://yoasobi-music/info/news"
    }
  ],
  "url": "www.yoasobi-music.jp/"
}
```
