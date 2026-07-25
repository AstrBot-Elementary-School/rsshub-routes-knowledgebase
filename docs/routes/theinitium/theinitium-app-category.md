# The Initium - App

## Coverage
`index-only`

## Route
- Namespace: `theinitium`
- Namespace Name: `The Initium`
- Route Path: `/theinitium/app/:category?`
- Route Name: `App`
- Example: `/theinitium/app`
- URL: `theinitium.com`
- Language: `_None_`
- Categories: `new-media, popular`
- Maintainers: `quiniapiezoelectricity, pseudoyu`
- Source Location: `app.ts`
- Source Module: `_None_`

## Description
Category 栏目：

| ----- | 简体中文          | 繁體中文          |
| ----- | ----------------- | ----------------- |
| 最新  | latest\_sc        | latest\_tc        |
| 日报  | daily\_brief\_sc  | daily\_brief\_tc  |
| 速递  | whats\_new\_sc    | whats\_new\_tc    |
| 专题  | report\_sc        | report\_tc        |
| 评论  | opinion\_sc       | opinion\_tc       |
| 国际  | international\_sc | international\_tc |
| 大陆  | mainland\_sc      | mainland\_tc      |
| 香港  | hongkong\_sc      | hongkong\_tc      |
| 台湾  | taiwan\_sc        | taiwan\_tc        |

::: tip
原 App 路由已迁移至 Ghost CMS API。播客（article\_audio）分类已停用，请改用 `/theinitium/channel` 路由。
:::

## Parameters
- `category`: Category, see below, latest_sc by default


## Features
- `requireConfig`: [{"description": "端传媒会员登录后的 Cookie，用于获取付费文章全文。", "name": "INITIUM_MEMBER_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `theinitium.com/latest/`
- `target`: `/app/latest_sc`

## Raw JSON
```json
{
  "categories": [
    "new-media",
    "popular"
  ],
  "description": "Category 栏目：\n\n| ----- | 简体中文          | 繁體中文          |\n| ----- | ----------------- | ----------------- |\n| 最新  | latest\\_sc        | latest\\_tc        |\n| 日报  | daily\\_brief\\_sc  | daily\\_brief\\_tc  |\n| 速递  | whats\\_new\\_sc    | whats\\_new\\_tc    |\n| 专题  | report\\_sc        | report\\_tc        |\n| 评论  | opinion\\_sc       | opinion\\_tc       |\n| 国际  | international\\_sc | international\\_tc |\n| 大陆  | mainland\\_sc      | mainland\\_tc      |\n| 香港  | hongkong\\_sc      | hongkong\\_tc      |\n| 台湾  | taiwan\\_sc        | taiwan\\_tc        |\n\n::: tip\n原 App 路由已迁移至 Ghost CMS API。播客（article\\_audio）分类已停用，请改用 `/theinitium/channel` 路由。\n:::",
  "example": "/theinitium/app",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "端传媒会员登录后的 Cookie，用于获取付费文章全文。",
        "name": "INITIUM_MEMBER_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1546,
  "location": "app.ts",
  "maintainers": [
    "quiniapiezoelectricity",
    "pseudoyu"
  ],
  "name": "App",
  "parameters": {
    "category": "Category, see below, latest_sc by default"
  },
  "path": "/app/:category?",
  "radar": [
    {
      "source": [
        "theinitium.com/latest/"
      ],
      "target": "/app/latest_sc"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "端传媒 - 最新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59337321303625728",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://theinitium.com/latest/",
      "title": "端传媒 - 最新",
      "type": "feed",
      "url": "rsshub://theinitium/app"
    },
    {
      "description": "端传媒 - 最新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62028044872836096",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://theinitium.com/latest/",
      "title": "端传媒 - 最新",
      "type": "feed",
      "url": "rsshub://theinitium/app/latest_sc"
    }
  ]
}
```
