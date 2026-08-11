# 华尔街见闻 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `wallstreetcn`
- Namespace Name: `华尔街见闻`
- Route Path: `/wallstreetcn/news/:category?`
- Route Name: `资讯`
- Example: `/wallstreetcn/news`
- URL: `wallstreetcn.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| id           | 分类  |
| ------------ | ----- |
| global       | 最新  |
| shares       | 股市  |
| bonds        | 债市  |
| commodities  | 商品  |
| forex        | 外汇  |
| finance      | 金融  |
| enterprise   | 公司  |
| asset-manage | 资管  |
| tmt          | 科技  |
| ai           | 硬 AI |
| estate       | 地产  |
| car          | 汽车  |
| medicine     | 医药  |

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `wallstreetcn.com/news/:category`
  - `wallstreetcn.com/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| id           | 分类  |\n| ------------ | ----- |\n| global       | 最新  |\n| shares       | 股市  |\n| bonds        | 债市  |\n| commodities  | 商品  |\n| forex        | 外汇  |\n| finance      | 金融  |\n| enterprise   | 公司  |\n| asset-manage | 资管  |\n| tmt          | 科技  |\n| ai           | 硬 AI |\n| estate       | 地产  |\n| car          | 汽车  |\n| medicine     | 医药  |",
  "example": "/wallstreetcn/news",
  "heat": 223,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "资讯",
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "wallstreetcn.com/news/:category",
        "wallstreetcn.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "华尔街见闻 - 资讯 - 最新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61254696782946304",
      "image": "https://static.wscn.net/wscn/_static/favicon.png",
      "ownerUserId": null,
      "siteUrl": "https://wallstreetcn.com/news/global",
      "title": "华尔街见闻 - 资讯 - 最新",
      "type": "feed",
      "url": "rsshub://wallstreetcn/news"
    },
    {
      "description": "华尔街见闻 - 资讯 - 最新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41965184796581995",
      "image": "https://static.wscn.net/wscn/_static/favicon.png",
      "ownerUserId": null,
      "siteUrl": "https://wallstreetcn.com/news/global",
      "title": "华尔街见闻 - 资讯 - 最新",
      "type": "feed",
      "url": "rsshub://wallstreetcn/news/global"
    }
  ]
}
```
