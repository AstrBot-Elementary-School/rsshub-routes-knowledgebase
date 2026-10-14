# 机核网 - 视频

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/gcores/videos`
- Route Name: `视频`
- Example: `/gcores/videos`
- URL: `www.gcores.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `videos.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `www.gcores.com/`
- `target`: `/videos`
### Rule 2
- `source`:
  - `www.gcores.com/videos`
- `target`: `/videos`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/gcores/videos",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 15,
  "location": "videos.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "视频",
  "path": "/videos",
  "radar": [
    {
      "source": [
        "www.gcores.com/"
      ],
      "target": "/videos"
    },
    {
      "source": [
        "www.gcores.com/videos"
      ],
      "target": "/videos"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "观看机核出品的视频节目、评测、访谈与社区投稿内容。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "114624152852011008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gcores.com/videos",
      "title": "视频 | 机核 GCORES",
      "type": "feed",
      "url": "rsshub://gcores/videos"
    }
  ],
  "url": "www.gcores.com",
  "view": 3
}
```
