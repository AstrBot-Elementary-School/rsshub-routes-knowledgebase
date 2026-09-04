# 中国技术经济学会 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `cste`
- Namespace Name: `中国技术经济学会`
- Route Path: `/cste/:id?`
- Route Name: `栏目`
- Example: `/cste`
- URL: `cste.org.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 学会新闻 | 科协简讯 | 学科动态 | 往事钩沉 |
| -------- | -------- | -------- | -------- | -------- |
| 16       | 18       | 19       | 20       | 21       |

## Parameters
- `id`: 分类，见下表，默认为 16，即通知公告


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
    "study"
  ],
  "description": "| 通知公告 | 学会新闻 | 科协简讯 | 学科动态 | 往事钩沉 |\n| -------- | -------- | -------- | -------- | -------- |\n| 16       | 18       | 19       | 20       | 21       |",
  "example": "/cste",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "id": "分类，见下表，默认为 16，即通知公告"
  },
  "path": "/:id?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "中国技术经济学会 - 通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1228421102376452096",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cste.org.cn/site/term/16.html",
      "title": "中国技术经济学会 - 通知公告",
      "type": "feed",
      "url": "rsshub://cste/16"
    }
  ]
}
```
