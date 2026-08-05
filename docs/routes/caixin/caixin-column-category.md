# 财新博客 - 新闻分类

## Coverage
`index-only`

## Route
- Namespace: `caixin`
- Namespace Name: `财新博客`
- Route Path: `/caixin/:column/:category`
- Route Name: `新闻分类`
- Example: `/caixin/finance/regulation`
- URL: `caixin.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `idealclover`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
Column 列表：

| 经济    | 金融    | 政经  | 环科    | 世界          | 观点网  | 文化    | 周刊   |
| ------- | ------- | ----- | ------- | ------------- | ------- | ------- | ------ |
| economy | finance | china | science | international | opinion | culture | weekly |

以金融板块为例的 category 列表：（其余 column 以类似方式寻找）

| 监管       | 银行 | 证券基金 | 信托保险         | 投资       | 创新       | 市场   |
| ---------- | ---- | -------- | ---------------- | ---------- | ---------- | ------ |
| regulation | bank | stock    | insurance\_trust | investment | innovation | market |

Category 列表：

| 封面报道   | 开卷  | 社论      | 时事             | 编辑寄语     | 经济    | 金融    | 商业     | 环境与科技              | 民生    | 副刊   |
| ---------- | ----- | --------- | ---------------- | ------------ | ------- | ------- | -------- | ----------------------- | ------- | ------ |
| coverstory | first | editorial | current\_affairs | editor\_desk | economy | finance | business | environment\_technology | cwcivil | column |

## Parameters
- `column`: 栏目名
- `category`: 栏目下的子分类名


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Column 列表：\n\n| 经济    | 金融    | 政经  | 环科    | 世界          | 观点网  | 文化    | 周刊   |\n| ------- | ------- | ----- | ------- | ------------- | ------- | ------- | ------ |\n| economy | finance | china | science | international | opinion | culture | weekly |\n\n以金融板块为例的 category 列表：（其余 column 以类似方式寻找）\n\n| 监管       | 银行 | 证券基金 | 信托保险         | 投资       | 创新       | 市场   |\n| ---------- | ---- | -------- | ---------------- | ---------- | ---------- | ------ |\n| regulation | bank | stock    | insurance\\_trust | investment | innovation | market |\n\nCategory 列表：\n\n| 封面报道   | 开卷  | 社论      | 时事             | 编辑寄语     | 经济    | 金融    | 商业     | 环境与科技              | 民生    | 副刊   |\n| ---------- | ----- | --------- | ---------------- | ------------ | ------- | ------- | -------- | ----------------------- | ------- | ------ |\n| coverstory | first | editorial | current\\_affairs | editor\\_desk | economy | finance | business | environment\\_technology | cwcivil | column |",
  "example": "/caixin/finance/regulation",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 162,
  "location": "category.ts",
  "maintainers": [
    "idealclover"
  ],
  "name": "新闻分类",
  "parameters": {
    "category": "栏目下的子分类名",
    "column": "栏目名"
  },
  "path": "/:column/:category",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "财新网 - 提供财经新闻及资讯服务 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42855045334971395",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://weekly.caixin.com/coverstory",
      "title": "封面报道_财新周刊频道_财新网",
      "type": "feed",
      "url": "rsshub://caixin/weekly/coverstory"
    },
    {
      "description": "财新网 - 提供财经新闻及资讯服务 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60143536924270599",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://finance.caixin.com/regulation",
      "title": "监管_金融频道_财新网",
      "type": "feed",
      "url": "rsshub://caixin/finance/regulation"
    }
  ]
}
```
