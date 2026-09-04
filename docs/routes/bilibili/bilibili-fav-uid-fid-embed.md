# 哔哩哔哩 bilibili - UP 主非默认收藏夹

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/fav/:uid/:fid/:embed?`
- Route Name: `UP 主非默认收藏夹`
- Example: `/bilibili/fav/756508/50948568`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Qixingchen`
- Source Location: `fav.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到
- `fid`: 收藏夹 ID, 可在收藏夹的 URL 中找到, 默认收藏夹建议使用 UP 主默认收藏夹功能
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
  "example": "/bilibili/fav/756508/50948568",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 32,
  "location": "fav.ts",
  "maintainers": [
    "Qixingchen"
  ],
  "name": "UP 主非默认收藏夹",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "fid": "收藏夹 ID, 可在收藏夹的 URL 中找到, 默认收藏夹建议使用 UP 主默认收藏夹功能",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/fav/:uid/:fid/:embed?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "观海聽风声 的 bilibili 收藏夹 二次元 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "152013966170646528",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/399964818/#/favlist?fid=1771644318",
      "title": "观海聽风声 的 bilibili 收藏夹 二次元",
      "type": "feed",
      "url": "rsshub://bilibili/fav/399964818/1771644318"
    },
    {
      "description": "观海聽风声 的 bilibili 收藏夹 续搬运 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "95590863863326720",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/399964818/#/favlist?fid=3241215618",
      "title": "观海聽风声 的 bilibili 收藏夹 续搬运",
      "type": "feed",
      "url": "rsshub://bilibili/fav/399964818/3241215618"
    }
  ]
}
```
