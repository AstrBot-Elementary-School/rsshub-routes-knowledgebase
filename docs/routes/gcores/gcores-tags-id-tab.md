# 机核网 - 标签

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/gcores/tags/:id/:tab?`
- Route Name: `标签`
- Example: `/gcores/tags/1/articles`
- URL: `www.gcores.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `StevenRCE0, nczitzk`
- Source Location: `tags.ts`
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
- `tab`: {"description": "类型，默认为空，即全部，可在对应标签页 URL 中找到", "options": [{"label": "全部", "value": ""}, {"label": "播客", "value": "radios"}, {"label": "文章", "value": "articles"}, {"label": "资讯", "value": "news"}, {"label": "视频", "value": "videos"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `全部`
- `source`:
  - `www.gcores.com/tags/:id/originals`
- `target`: `/tags/:id`
### Rule 2
- `title`: `播客`
- `source`:
  - `www.gcores.com/tags/:id/originals`
- `target`: `/tags/:id/radios`
### Rule 3
- `title`: `文章`
- `source`:
  - `www.gcores.com/tags/:id/originals`
- `target`: `/tags/:id/articles`
### Rule 4
- `title`: `资讯`
- `source`:
  - `www.gcores.com/tags/:id/originals`
- `target`: `/tags/:id/news`
### Rule 5
- `title`: `视频`
- `source`:
  - `www.gcores.com/tags/:id/originals`
- `target`: `/tags/:id/videos`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n若订阅 [美国 - 文章](https://www.gcores.com/tags/1/originals?tab=articles)，网址为 `https://www.gcores.com/tags/1/originals?tab=articles`，请截取 `https://www.gcores.com/tags/` 到末尾 `/originals` 的部分 `1` 作为 `id` 参数填入，截取 `articles` 作为 `tab` 参数填入，此时目标路由为 [`/gcores/tags/1/articles`](https://rsshub.app/gcores/tags/1/articles)。\n:::\n\n| 全部 | 播客   | 文章     | 资讯 | 视频   |\n| ---- | ------ | -------- | ---- | ------ |\n|      | radios | articles | news | videos |",
  "example": "/gcores/tags/1/articles",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 1,
  "location": "tags.ts",
  "maintainers": [
    "StevenRCE0",
    "nczitzk"
  ],
  "name": "标签",
  "parameters": {
    "id": {
      "description": "标签 ID，可在对应标签页 URL 中找到"
    },
    "tab": {
      "description": "类型，默认为空，即全部，可在对应标签页 URL 中找到",
      "options": [
        {
          "label": "全部",
          "value": ""
        },
        {
          "label": "播客",
          "value": "radios"
        },
        {
          "label": "文章",
          "value": "articles"
        },
        {
          "label": "资讯",
          "value": "news"
        },
        {
          "label": "视频",
          "value": "videos"
        }
      ]
    }
  },
  "path": "/tags/:id/:tab?",
  "radar": [
    {
      "source": [
        "www.gcores.com/tags/:id/originals"
      ],
      "target": "/tags/:id",
      "title": "全部"
    },
    {
      "source": [
        "www.gcores.com/tags/:id/originals"
      ],
      "target": "/tags/:id/radios",
      "title": "播客"
    },
    {
      "source": [
        "www.gcores.com/tags/:id/originals"
      ],
      "target": "/tags/:id/articles",
      "title": "文章"
    },
    {
      "source": [
        "www.gcores.com/tags/:id/originals"
      ],
      "target": "/tags/:id/news",
      "title": "资讯"
    },
    {
      "source": [
        "www.gcores.com/tags/:id/originals"
      ],
      "target": "/tags/:id/videos",
      "title": "视频"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "机核从2010年开始一直致力于分享游戏玩家的生活，以及深入探讨游戏相关的文化。我们开发原创的播客以及视频节目，一直在不断寻找民间高质量的内容创作者。 我们坚信游戏不止是游戏，游戏中包含的科学，文化，历史等各个层面的知识和故事，它们同时也会辐射到二次元甚至电影的领域，这些内容非常值得分享给热爱游戏的您。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "112357158002525184",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gcores.com/tags/1/originals?tab=articles",
      "title": "美国 | 机核 GCORES",
      "type": "feed",
      "url": "rsshub://gcores/tags/1/articles"
    }
  ],
  "url": "www.gcores.com",
  "view": 0
}
```
