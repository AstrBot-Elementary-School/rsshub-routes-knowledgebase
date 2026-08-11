# 哔哩哔哩 bilibili - 分区视频排行榜

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/partion/ranking/:tid/:days?/:embed?`
- Route Name: `分区视频排行榜`
- Example: `/bilibili/partion/ranking/171/3`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `lengthmin`
- Source Location: `partion-ranking.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tid`: 分区 id, 见上方表格
- `days`: 缺省为 7, 指最近多少天内的热度排序
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
  "example": "/bilibili/partion/ranking/171/3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 113,
  "location": "partion-ranking.ts",
  "maintainers": [
    "lengthmin"
  ],
  "name": "分区视频排行榜",
  "parameters": {
    "days": "缺省为 7, 指最近多少天内的热度排序",
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "tid": "分区 id, 见上方表格"
  },
  "path": "/partion/ranking/:tid/:days?/:embed?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "bilibili 未知分区 最热视频 - Powered by RSSHub",
      "errorAt": "2026-08-09T09:12:43.914Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "63858618178298888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/",
      "title": "bilibili 未知 最热视频",
      "type": "feed",
      "url": "rsshub://bilibili/partion/ranking/95/3"
    },
    {
      "description": "bilibili 未知分区 最热视频 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70095114504796160",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/",
      "title": "bilibili 未知 最热视频",
      "type": "feed",
      "url": "rsshub://bilibili/partion/ranking/233/30"
    }
  ]
}
```
