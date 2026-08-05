# 中国科学技术协会 - 通用

## Coverage
`index-only`

## Route
- Namespace: `cast`
- Namespace Name: `中国科学技术协会`
- Route Path: `/cast/:column/:subColumn/:category?`
- Route Name: `通用`
- Example: `/cast/xw/tzgg/ZH`
- URL: `cast.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `KarasuShin, TonyRL`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
在路由末尾处加上 `?limit=限制获取数目` 来限制获取条目数量，默认值为`10`
:::

| 分类     | 编码 |
| -------- | ---- |
| 全景科协 | qjkx |
| 智库     | zk   |
| 学术     | xs   |
| 科普     | kp   |
| 党建     | dj   |
| 数据     | sj   |
| 新闻     | xw   |

## Parameters
- `column`: 栏目编号，见下表
- `subColumn`: 二级栏目编号
- `category`: 分类


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `cast.org.cn/:column/:subColumn/:category/index.html`
  - `cast.org.cn/:column/:subColumn/index.html`
- `target`: `/:column/:subColumn/:category?`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n在路由末尾处加上 `?limit=限制获取数目` 来限制获取条目数量，默认值为`10`\n:::\n\n| 分类     | 编码 |\n| -------- | ---- |\n| 全景科协 | qjkx |\n| 智库     | zk   |\n| 学术     | xs   |\n| 科普     | kp   |\n| 党建     | dj   |\n| 数据     | sj   |\n| 新闻     | xw   |",
  "example": "/cast/xw/tzgg/ZH",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "index.ts",
  "maintainers": [
    "KarasuShin",
    "TonyRL"
  ],
  "name": "通用",
  "parameters": {
    "category": "分类",
    "column": "栏目编号，见下表",
    "subColumn": "二级栏目编号"
  },
  "path": "/:column/:subColumn/:category?",
  "radar": [
    {
      "source": [
        "cast.org.cn/:column/:subColumn/:category/index.html",
        "cast.org.cn/:column/:subColumn/index.html"
      ],
      "target": "/:column/:subColumn/:category?"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "综合 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61596470433482760",
      "image": "https://www.cast.org.cn/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.cast.org.cn/xw/tzgg/ZH/index.html",
      "title": "综合",
      "type": "feed",
      "url": "rsshub://cast/xw/tzgg/ZH"
    }
  ]
}
```
