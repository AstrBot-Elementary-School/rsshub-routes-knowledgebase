# 机核网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/gcores/categories/:id/:tab?`
- Route Name: `分类`
- Example: `/gcores/categories/1/articles`
- URL: `www.gcores.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `MoguCloud, StevenRCE0, nczitzk`
- Source Location: `categories.ts`
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
- `tab`: {"description": "类型，默认为空，即全部，可在对应分类页 URL 中找到", "options": [{"label": "全部", "value": ""}, {"label": "播客", "value": "radios"}, {"label": "文章", "value": "articles"}, {"label": "资讯", "value": "news"}, {"label": "视频", "value": "videos"}]}


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
- `source`:
  - `www.gcores.com/categories/:id`
### Rule 2
- `title`: `全部`
- `source`:
  - `www.gcores.com/categories/:id`
- `target`: `/gcores/categories/:id`
### Rule 3
- `title`: `播客`
- `source`:
  - `www.gcores.com/categories/:id`
- `target`: `/categories/:id/radios`
### Rule 4
- `title`: `文章`
- `source`:
  - `www.gcores.com/categories/:id`
- `target`: `/categories/:id/articles`
### Rule 5
- `title`: `资讯`
- `source`:
  - `www.gcores.com/categories/:id`
- `target`: `/categories/:id/news`
### Rule 6
- `title`: `视频`
- `source`:
  - `www.gcores.com/categories/:id`
- `target`: `/categories/:id/videos`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n若订阅 [文章 - 文章](https://www.gcores.com/categories/1?tab=articles)，网址为 `https://www.gcores.com/categories/1?tab=articles`，请截取 `https://www.gcores.com/categories/` 到末尾的部分 `1` 作为 `id` 参数填入，截取 `articles` 作为 `tab` 参数填入，此时目标路由为 [`/gcores/categories/1/articles`](https://rsshub.app/gcores/categories/1/articles)。\n:::\n\n| 全部 | 播客   | 文章     | 资讯 | 视频   |\n| ---- | ------ | -------- | ---- | ------ |\n|      | radios | articles | news | videos |",
  "example": "/gcores/categories/1/articles",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 23,
  "location": "categories.ts",
  "maintainers": [
    "MoguCloud",
    "StevenRCE0",
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "id": {
      "description": "分类 ID，可在对应分类页 URL 中找到"
    },
    "tab": {
      "description": "类型，默认为空，即全部，可在对应分类页 URL 中找到",
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
  "path": "/categories/:id/:tab?",
  "radar": [
    {
      "source": [
        "www.gcores.com/categories/:id"
      ]
    },
    {
      "source": [
        "www.gcores.com/categories/:id"
      ],
      "target": "/gcores/categories/:id",
      "title": "全部"
    },
    {
      "source": [
        "www.gcores.com/categories/:id"
      ],
      "target": "/categories/:id/radios",
      "title": "播客"
    },
    {
      "source": [
        "www.gcores.com/categories/:id"
      ],
      "target": "/categories/:id/articles",
      "title": "文章"
    },
    {
      "source": [
        "www.gcores.com/categories/:id"
      ],
      "target": "/categories/:id/news",
      "title": "资讯"
    },
    {
      "source": [
        "www.gcores.com/categories/:id"
      ],
      "target": "/categories/:id/videos",
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
      "id": "116739843787561984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gcores.com/categories/20",
      "title": "知识挖掘机 | 机核 GCORES",
      "type": "feed",
      "url": "rsshub://gcores/categories/20"
    },
    {
      "description": "机核从2010年开始一直致力于分享游戏玩家的生活，以及深入探讨游戏相关的文化。我们开发原创的播客以及视频节目，一直在不断寻找民间高质量的内容创作者。 我们坚信游戏不止是游戏，游戏中包含的科学，文化，历史等各个层面的知识和故事，它们同时也会辐射到二次元甚至电影的领域，这些内容非常值得分享给热爱游戏的您。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "129756947742224384",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gcores.com/categories/20?tab=articles",
      "title": "知识挖掘机 | 机核 GCORES",
      "type": "feed",
      "url": "rsshub://gcores/categories/20/articles"
    }
  ],
  "url": "www.gcores.com",
  "view": 0
}
```
