# 即刻 - 圈子 - 纯文字

## Coverage
`index-only`

## Route
- Namespace: `jike`
- Namespace Name: `即刻`
- Route Path: `/jike/topic/text/:id`
- Route Name: `圈子 - 纯文字`
- Example: `/jike/topic/text/553870e8e4b0cafb0a1bef68`
- URL: `m.okjike.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `HenryQW`
- Source Location: `topic-text.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 圈子 id, 可在即刻 web 端圈子页或 APP 分享出来的圈子页 URL 中找到


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
  - `web.okjike.com/topic/:id`
- `target`: `/topic/text/:id`
### Rule 2
- `source`:
  - `m.okjike.com/topics/:id`
- `target`: `/topic/text/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/jike/topic/text/553870e8e4b0cafb0a1bef68",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1213,
  "location": "topic-text.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "圈子 - 纯文字",
  "parameters": {
    "id": "圈子 id, 可在即刻 web 端圈子页或 APP 分享出来的圈子页 URL 中找到"
  },
  "path": "/topic/text/:id",
  "radar": [
    {
      "source": [
        "web.okjike.com/topic/:id"
      ],
      "target": "/topic/text/:id"
    },
    {
      "source": [
        "m.okjike.com/topics/:id"
      ],
      "target": "/topic/text/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "我劝天公降人才。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67048226833723416",
      "image": "https://cdnv2.ruguoapp.com/FpJETOhvDmwGcyprO9qXqC0prErx.png?imageMogr2/auto-orient/heic-exif/1/format/jpeg/thumbnail/1000x1000%3E",
      "ownerUserId": null,
      "siteUrl": "https://m.okjike.com/topics/5af18fe3064445001748dcb8",
      "title": "招聘发布市场 - 即刻圈子",
      "type": "feed",
      "url": "rsshub://jike/topic/text/5af18fe3064445001748dcb8"
    },
    {
      "description": "每天早上向你汇报当你睡觉的时候世界发生了什么，快速一览昨夜今晨要闻。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53733146806773775",
      "image": "https://cdnv2.ruguoapp.com/FtOtKoJy3PqcbQ9STCam-fcvN4NY.png?imageMogr2/auto-orient/heic-exif/1/format/jpeg/thumbnail/1000x1000%3E",
      "ownerUserId": null,
      "siteUrl": "https://m.okjike.com/topics/553870e8e4b0cafb0a1bef68",
      "title": "一觉醒来发生了什么 - 即刻圈子",
      "type": "feed",
      "url": "rsshub://jike/topic/text/553870e8e4b0cafb0a1bef68"
    }
  ]
}
```
