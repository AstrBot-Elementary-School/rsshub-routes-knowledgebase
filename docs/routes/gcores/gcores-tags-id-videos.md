# 机核网 - 标签 - 视频

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/gcores/tags/:id/videos`
- Route Name: `标签 - 视频`
- Example: `/gcores/tags/1/videos`
- URL: `www.gcores.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `StevenRCE0, nczitzk`
- Source Location: `tags-videos.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [美国 - 文章](https://www.gcores.com/tags/1/originals?tab=articles)，网址为 `https://www.gcores.com/tags/1/originals?tab=articles`，请截取 `https://www.gcores.com/tags/` 到末尾 `/originals` 的部分 `1` 作为 `id` 参数填入，截取 `articles` 作为 `tab` 参数填入，此时目标路由为 [`/gcores/tags/1/articles`](https://rsshub.app/gcores/tags/1/articles)。
:::

| 全部 | 播客   | 文章     | 资讯 | 视频   |
| ---- | ------ | -------- | ---- | ------ |
|      | radios | articles | news | videos |

## Parameters
- `id`: {"description": "标签 ID，可在对应标签页 URL 中找到"}


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
  "description": "::: tip\n若订阅 [美国 - 文章](https://www.gcores.com/tags/1/originals?tab=articles)，网址为 `https://www.gcores.com/tags/1/originals?tab=articles`，请截取 `https://www.gcores.com/tags/` 到末尾 `/originals` 的部分 `1` 作为 `id` 参数填入，截取 `articles` 作为 `tab` 参数填入，此时目标路由为 [`/gcores/tags/1/articles`](https://rsshub.app/gcores/tags/1/articles)。\n:::\n\n| 全部 | 播客   | 文章     | 资讯 | 视频   |\n| ---- | ------ | -------- | ---- | ------ |\n|      | radios | articles | news | videos |",
  "example": "/gcores/tags/1/videos",
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
  "location": "tags-videos.ts",
  "maintainers": [
    "StevenRCE0",
    "nczitzk"
  ],
  "name": "标签 - 视频",
  "parameters": {
    "id": {
      "description": "标签 ID，可在对应标签页 URL 中找到"
    }
  },
  "path": "/tags/:id/videos",
  "radar": [],
  "topFeeds": [],
  "url": "www.gcores.com",
  "view": 3
}
```
