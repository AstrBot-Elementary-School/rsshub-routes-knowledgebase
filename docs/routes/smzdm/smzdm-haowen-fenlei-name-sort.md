# 什么值得买 - 好文分类

## Coverage
`index-only`

## Route
- Namespace: `smzdm`
- Namespace Name: `什么值得买`
- Route Path: `/smzdm/haowen/fenlei/:name/:sort?`
- Route Name: `好文分类`
- Example: `/smzdm/haowen/fenlei/shenghuodianqi`
- URL: `post.smzdm.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `LogicJake`
- Source Location: `haowen-fenlei.ts`
- Source Module: `_None_`

## Description
| 最新 | 周排行 | 月排行 |
| ---- | ------ | ------ |
| 0    | 7      | 30     |

## Parameters
- `name`: 分类名，可在 URL 中查看
- `sort`: 排序方式，默认为最新


## Features
- `requireConfig`: [{"description": "什么值得买登录后的 Cookie 值", "name": "SMZDM_COOKIE"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `post.smzdm.com/fenlei/:name`
- `target`: `/haowen/fenlei/:name`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "| 最新 | 周排行 | 月排行 |\n| ---- | ------ | ------ |\n| 0    | 7      | 30     |",
  "example": "/smzdm/haowen/fenlei/shenghuodianqi",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "什么值得买登录后的 Cookie 值",
        "name": "SMZDM_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 348,
  "location": "haowen-fenlei.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "好文分类",
  "parameters": {
    "name": "分类名，可在 URL 中查看",
    "sort": "排序方式，默认为最新"
  },
  "path": "/haowen/fenlei/:name/:sort?",
  "radar": [
    {
      "source": [
        "post.smzdm.com/fenlei/:name"
      ],
      "target": "/haowen/fenlei/:name"
    }
  ],
  "topFeeds": [
    {
      "description": "NAS存储 - 什么值得买好文分类 - Powered by RSSHub",
      "errorAt": "2025-04-23T01:49:36.639Z",
      "errorMessage": "200 ",
      "id": "63960223947361280",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://post.smzdm.com/fenlei/nascunchufuwuqi/",
      "title": "NAS存储 - 什么值得买好文分类",
      "type": "feed",
      "url": "rsshub://smzdm/haowen/fenlei/nascunchufuwuqi"
    },
    {
      "description": "软件应用 - 什么值得买好文分类 - Powered by RSSHub",
      "errorAt": "2025-05-17T21:30:41.594Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "62650278906211328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://post.smzdm.com/fenlei/ruanjianyingyong/",
      "title": "软件应用 - 什么值得买好文分类",
      "type": "feed",
      "url": "rsshub://smzdm/haowen/fenlei/ruanjianyingyong"
    }
  ]
}
```
