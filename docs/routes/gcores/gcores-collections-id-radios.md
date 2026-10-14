# 机核网 - 专题 - 播客

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/gcores/collections/:id/radios`
- Route Name: `专题 - 播客`
- Example: `/gcores/collections/64/radios`
- URL: `www.gcores.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `kudryavka1013, nczitzk`
- Source Location: `collections-radios.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [文章 - 文章](https://www.gcores.com/collections/64?tab=articles)，网址为 `https://www.gcores.com/collections/64?tab=articles`，请截取 `https://www.gcores.com/collections/` 到末尾的部分 `64` 作为 `id` 参数填入，截取 `articles` 作为 `tab` 参数填入，此时目标路由为 [`/gcores/collections/64/articles`](https://rsshub.app/gcores/collections/64/articles)。
:::

| 全部 | 播客   | 文章     | 资讯 | 视频   |
| ---- | ------ | -------- | ---- | ------ |
|      | radios | articles | news | videos |

## Parameters
- `id`: {"description": "专题 ID，可在对应专题页 URL 中找到"}


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
  "description": "::: tip\n若订阅 [文章 - 文章](https://www.gcores.com/collections/64?tab=articles)，网址为 `https://www.gcores.com/collections/64?tab=articles`，请截取 `https://www.gcores.com/collections/` 到末尾的部分 `64` 作为 `id` 参数填入，截取 `articles` 作为 `tab` 参数填入，此时目标路由为 [`/gcores/collections/64/articles`](https://rsshub.app/gcores/collections/64/articles)。\n:::\n\n| 全部 | 播客   | 文章     | 资讯 | 视频   |\n| ---- | ------ | -------- | ---- | ------ |\n|      | radios | articles | news | videos |",
  "example": "/gcores/collections/64/radios",
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
  "location": "collections-radios.ts",
  "maintainers": [
    "kudryavka1013",
    "nczitzk"
  ],
  "name": "专题 - 播客",
  "parameters": {
    "id": {
      "description": "专题 ID，可在对应专题页 URL 中找到"
    }
  },
  "path": "/collections/:id/radios",
  "radar": [],
  "topFeeds": [],
  "url": "www.gcores.com",
  "view": 4
}
```
