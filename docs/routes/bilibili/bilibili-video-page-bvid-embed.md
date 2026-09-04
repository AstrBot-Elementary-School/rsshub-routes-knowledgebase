# 哔哩哔哩 bilibili - 视频选集列表

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/video/page/:bvid/:embed?`
- Route Name: `视频选集列表`
- Example: `/bilibili/video/page/BV1i7411M7N9`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `sxzz`
- Source Location: `page.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `bvid`: 可在视频页 URL 中找到
- `embed`: 默认为开启内嵌视频, 任意值为关闭


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
  "example": "/bilibili/video/page/BV1i7411M7N9",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 72,
  "location": "page.ts",
  "maintainers": [
    "sxzz"
  ],
  "name": "视频选集列表",
  "parameters": {
    "bvid": "可在视频页 URL 中找到",
    "embed": "默认为开启内嵌视频, 任意值为关闭"
  },
  "path": "/video/page/:bvid/:embed?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "视频 美女热舞合集 的视频选集列表 - Powered by RSSHub",
      "errorAt": "2025-05-30T12:00:46.109Z",
      "errorMessage": "[GET] \"https://api.bilibili.com/x/web-interface/view?bvid=BV1nU1kYgEKE\": 412 Precondition Failed\n",
      "id": "69945630785231872",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/video/BV1nU1kYgEKE",
      "title": "视频 美女热舞合集 的选集列表",
      "type": "feed",
      "url": "rsshub://bilibili/video/page/BV1nU1kYgEKE"
    },
    {
      "description": "视频 STM32入门教程-2023版 细致讲解 中文字幕 的视频选集列表 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61191357866744832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/video/BV1th411z7sn",
      "title": "视频 STM32入门教程-2023版 细致讲解 中文字幕 的选集列表",
      "type": "feed",
      "url": "rsshub://bilibili/video/page/BV1th411z7sn"
    }
  ]
}
```
