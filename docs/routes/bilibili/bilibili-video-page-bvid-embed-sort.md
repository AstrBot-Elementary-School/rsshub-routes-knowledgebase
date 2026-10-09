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
  "heat": 0,
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
  "topFeeds": []
}
```
