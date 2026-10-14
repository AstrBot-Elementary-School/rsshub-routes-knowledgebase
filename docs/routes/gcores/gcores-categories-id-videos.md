# 机核网 - 分类 - 视频

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/gcores/categories/:id/videos`
- Route Name: `分类 - 视频`
- Example: `/gcores/categories/61/videos`
- URL: `www.gcores.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `MoguCloud, StevenRCE0, nczitzk`
- Source Location: `categories-videos.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [文章 - 文章](https://www.gcores.com/categories/1?tab=articles)，网址为 `https://www.gcores.com/categories/1?tab=articles`，请截取 `https://www.gcores.com/categories/` 到末尾的部分 `1` 作为 `id` 参数填入，截取 `articles` 作为 `tab` 参数填入，此时目标路由为 [`/gcores/categories/1/articles`](https://rsshub.app/gcores/categories/1/articles)。
:::

| 全部 | 播客   | 文章     | 资讯 | 视频   |
| ---- | ------ | -------- | ---- | ------ |
|      | radios | articles | news | videos |

## Parameters
- `id`: {"description": "分类 ID，可在对应分类页 URL 中找到"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n若订阅 [文章 - 文章](https://www.gcores.com/categories/1?tab=articles)，网址为 `https://www.gcores.com/categories/1?tab=articles`，请截取 `https://www.gcores.com/categories/` 到末尾的部分 `1` 作为 `id` 参数填入，截取 `articles` 作为 `tab` 参数填入，此时目标路由为 [`/gcores/categories/1/articles`](https://rsshub.app/gcores/categories/1/articles)。\n:::\n\n| 全部 | 播客   | 文章     | 资讯 | 视频   |\n| ---- | ------ | -------- | ---- | ------ |\n|      | radios | articles | news | videos |",
  "example": "/gcores/categories/61/videos",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "categories-videos.ts",
  "maintainers": [
    "MoguCloud",
    "StevenRCE0",
    "nczitzk"
  ],
  "name": "分类 - 视频",
  "parameters": {
    "id": {
      "description": "分类 ID，可在对应分类页 URL 中找到"
    }
  },
  "path": "/categories/:id/videos",
  "radar": [],
  "topFeeds": [],
  "url": "www.gcores.com",
  "view": 3
}
```
