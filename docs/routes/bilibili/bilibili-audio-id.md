# 哔哩哔哩 bilibili - 歌单

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/audio/:id`
- Route Name: `歌单`
- Example: `/bilibili/audio/10624`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `LogicJake`
- Source Location: `audio.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 歌单 id, 可在歌单页 URL 中找到


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
  "example": "/bilibili/audio/10624",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "audio.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "歌单",
  "parameters": {
    "id": "歌单 id, 可在歌单页 URL 中找到"
  },
  "path": "/audio/:id",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "每天11:00更新，为你推送最新音乐 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61348084539081728",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/audio/am10624",
      "title": "新曲推荐",
      "type": "feed",
      "url": "rsshub://bilibili/audio/10624"
    }
  ]
}
```
