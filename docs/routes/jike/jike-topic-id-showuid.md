# 即刻 - 圈子

## Coverage
`index-only`

## Route
- Namespace: `jike`
- Namespace Name: `即刻`
- Route Path: `/jike/topic/:id/:showUid?`
- Route Name: `圈子`
- Example: `/jike/topic/556688fae4b00c57d9dd46ee`
- URL: `m.okjike.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod, prnake`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 圈子 id, 可在即刻 web 端圈子页或 APP 分享出来的圈子页 URL 中找到
- `showUid`: {"description": "是否在内容中显示用户信息，设置为 1 则开启", "options": [{"label": "显示", "value": "1"}]}


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
- `target`: `/topic/:id`
### Rule 2
- `source`:
  - `m.okjike.com/topics/:id`
- `target`: `/topic/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/jike/topic/556688fae4b00c57d9dd46ee",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 21846,
  "location": "topic.ts",
  "maintainers": [
    "DIYgod",
    "prnake"
  ],
  "name": "圈子",
  "parameters": {
    "id": "圈子 id, 可在即刻 web 端圈子页或 APP 分享出来的圈子页 URL 中找到",
    "showUid": {
      "description": "是否在内容中显示用户信息，设置为 1 则开启",
      "options": [
        {
          "label": "显示",
          "value": "1"
        }
      ]
    }
  },
  "path": "/topic/:id/:showUid?",
  "radar": [
    {
      "source": [
        "web.okjike.com/topic/:id"
      ],
      "target": "/topic/:id"
    },
    {
      "source": [
        "m.okjike.com/topics/:id"
      ],
      "target": "/topic/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "笔记交流站 - 即刻圈子 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41359648684677185",
      "image": "https://cdnv2.ruguoapp.com/FgDcr12wCOv_HsvuIwl9qugwWkywv3.jpg?imageMogr2/auto-orient/heic-exif/1/format/jpeg/thumbnail/1000x1000%3E",
      "ownerUserId": null,
      "siteUrl": "https://m.okjike.com/topics/660165c504703c909c6d8b2e",
      "title": "笔记交流站 - 即刻圈子",
      "type": "feed",
      "url": "rsshub://jike/topic/660165c504703c909c6d8b2e"
    },
    {
      "description": "每天早上向你汇报当你睡觉的时候世界发生了什么，快速一览昨夜今晨要闻。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41501088760162311",
      "image": "https://cdnv2.ruguoapp.com/FtOtKoJy3PqcbQ9STCam-fcvN4NY.png?imageMogr2/auto-orient/heic-exif/1/format/jpeg/thumbnail/1000x1000%3E",
      "ownerUserId": null,
      "siteUrl": "https://m.okjike.com/topics/553870e8e4b0cafb0a1bef68",
      "title": "一觉醒来发生了什么 - 即刻圈子",
      "type": "feed",
      "url": "rsshub://jike/topic/553870e8e4b0cafb0a1bef68"
    }
  ],
  "view": 1
}
```
