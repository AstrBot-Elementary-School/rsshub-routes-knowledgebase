# 逛丢 - 国内折扣 / 海外折扣

## Coverage
`index-only`

## Route
- Namespace: `guangdiu`
- Namespace Name: `逛丢`
- Route Path: `/guangdiu/:query?`
- Route Name: `国内折扣 / 海外折扣`
- Example: `/guangdiu/k=daily`
- URL: `guangdiu.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
海外折扣: [`/guangdiu/k=daily&c=us`](https://rsshub.app/guangdiu/k=daily\&c=us)
:::

## Parameters
- `query`: 链接参数，对应网址问号后的内容


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
    "shopping"
  ],
  "description": "::: tip\n海外折扣: [`/guangdiu/k=daily&c=us`](https://rsshub.app/guangdiu/k=daily\\&c=us)\n:::",
  "example": "/guangdiu/k=daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 36,
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "国内折扣 / 海外折扣",
  "parameters": {
    "query": "链接参数，对应网址问号后的内容"
  },
  "path": "/:query?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "逛丢 - 国内 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "155513414809226240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://guangdiu.com/",
      "title": "逛丢 - 国内",
      "type": "feed",
      "url": "rsshub://guangdiu"
    },
    {
      "description": "逛丢 - 国内 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65670452855599110",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://guangdiu.com/cate.php?k=daily",
      "title": "逛丢 - 国内",
      "type": "feed",
      "url": "rsshub://guangdiu/k=daily"
    }
  ]
}
```
