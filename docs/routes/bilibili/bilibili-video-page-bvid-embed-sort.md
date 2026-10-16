# 哔哩哔哩 bilibili - 视频选集列表

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/video/page/:bvid/:embed?/:sort?`
- Route Name: `视频选集列表`
- Example: `/bilibili/video/page/BV1i7411M7N9`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `sxzz`
- Source Location: `page.ts`
- Source Module: `_None_`

## Description
默认返回最近 10 个分 P，可使用通用参数 `limit` 增加条数。使用 `/:embed/asc` 可按选集顺序升序输出。

## Parameters
- `bvid`: 可在视频页 URL 中找到
- `embed`: 默认为开启内嵌视频, 任意值为关闭
- `sort`: 选集排序：desc（默认，降序）或 asc（升序）


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
  "description": "默认返回最近 10 个分 P，可使用通用参数 `limit` 增加条数。使用 `/:embed/asc` 可按选集顺序升序输出。",
  "example": "/bilibili/video/page/BV1i7411M7N9",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 23,
  "location": "page.ts",
  "maintainers": [
    "sxzz"
  ],
  "name": "视频选集列表",
  "parameters": {
    "bvid": "可在视频页 URL 中找到",
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "sort": "选集排序：desc（默认，降序）或 asc（升序）"
  },
  "path": "/video/page/:bvid/:embed?/:sort?",
  "topFeeds": [
    {
      "description": "视频 【国际象棋基础教程】【143集全】B站最牛国际象棋初级教程，最好的青少年启蒙教程 的视频选集列表 - Powered by RSSHub",
      "errorAt": "2026-09-01T05:33:25.125Z",
      "errorMessage": "[GET] \"https://api.bilibili.com/x/player/pagelist?bvid=BV1g14y1b7ME\": 412 Precondition Failed\n",
      "id": "77620127529375744",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/video/BV1g14y1b7ME",
      "title": "视频 【国际象棋基础教程】【143集全】B站最牛国际象棋初级教程，最好的青少年启蒙教程 的选集列表",
      "type": "feed",
      "url": "rsshub://bilibili/video/page/BV1g14y1b7ME"
    },
    {
      "description": "视频 美女热舞合集 的视频选集列表 - Powered by RSSHub",
      "errorAt": "2025-05-30T12:00:46.109Z",
      "errorMessage": "[GET] \"https://api.bilibili.com/x/player/pagelist?bvid=BV1nU1kYgEKE\": 412 Precondition Failed\n",
      "id": "69945630785231872",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/video/BV1nU1kYgEKE",
      "title": "视频 美女热舞合集 的选集列表",
      "type": "feed",
      "url": "rsshub://bilibili/video/page/BV1nU1kYgEKE"
    }
  ]
}
```
