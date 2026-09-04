# 哔哩哔哩 bilibili - 视频评论

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/video/reply/:bvid`
- Route Name: `视频评论`
- Example: `/bilibili/video/reply/BV1vA411b7ip`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Qixingchen`
- Source Location: `reply.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `bvid`: 可在视频页 URL 中找到


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
  "example": "/bilibili/video/reply/BV1vA411b7ip",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 12,
  "location": "reply.ts",
  "maintainers": [
    "Qixingchen"
  ],
  "name": "视频评论",
  "parameters": {
    "bvid": "可在视频页 URL 中找到"
  },
  "path": "/video/reply/:bvid",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "一个让你重构认知的顶级思维：如何走出内耗、上瘾、焦虑、无意义 的评论 - Powered by RSSHub",
      "errorAt": "2026-09-03T04:57:51.446Z",
      "errorMessage": "[GET] \"https://api.bilibili.com/x/web-interface/view?bvid=BV1bdZAYLEZb\": 412 Precondition Failed\n",
      "id": "138771689583685632",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/video/BV1bdZAYLEZb",
      "title": "一个让你重构认知的顶级思维：如何走出内耗、上瘾、焦虑、无意义 的 评论",
      "type": "feed",
      "url": "rsshub://bilibili/video/reply/BV1bdZAYLEZb"
    },
    {
      "description": "【第240期】《老特的反击，解密、战争、发币》 的评论 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "122540831734417408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/video/BV15wPQeMEYt",
      "title": "【第240期】《老特的反击，解密、战争、发币》 的 评论",
      "type": "feed",
      "url": "rsshub://bilibili/video/reply/BV15wPQeMEYt"
    }
  ]
}
```
