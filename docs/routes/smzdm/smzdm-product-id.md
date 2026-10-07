# 什么值得买 - 商品

## Coverage
`index-only`

## Route
- Namespace: `smzdm`
- Namespace Name: `什么值得买`
- Route Path: `/smzdm/product/:id`
- Route Name: `商品`
- Example: `/smzdm/product/zm5vzpe`
- URL: `post.smzdm.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `chesha1`
- Source Location: `product.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 商品 id，网址上直接可以看到


## Features
- `requireConfig`: [{"description": "什么值得买登录后的 Cookie 值", "name": "SMZDM_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `wiki.smzdm.com/p/:id`
- `target`: `/product/:id`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/smzdm/product/zm5vzpe",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "什么值得买登录后的 Cookie 值",
        "name": "SMZDM_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "product.ts",
  "maintainers": [
    "chesha1"
  ],
  "name": "商品",
  "parameters": {
    "id": "商品 id，网址上直接可以看到"
  },
  "path": "/product/:id",
  "radar": [
    {
      "source": [
        "wiki.smzdm.com/p/:id"
      ],
      "target": "/product/:id"
    }
  ],
  "topFeeds": [
    {
      "description": "Apple/苹果 iPhone 16 Pro Max 【报价 价格 评测 怎么样】 -什么值得买 - Powered by RSSHub",
      "errorAt": "2026-06-04T16:46:45.743Z",
      "errorMessage": "Cannot create property 'link' on string 'null'\n",
      "id": "70620977987371008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://wiki.smzdm.com/p/8m6vgjn",
      "title": "Apple/苹果 iPhone 16 Pro Max 【报价 价格 评测 怎么样】 -什么值得买",
      "type": "feed",
      "url": "rsshub://smzdm/product/8m6vgjn"
    },
    {
      "description": "创立于2014年的保温杯品牌。REVOMAX专注生产定制保温杯多年，可为用户提供非常丰富的选择，满足用户的各类定制需求，品牌在做到水杯样式精美的同时，严格把关生产标准，保证了产品耐用性的同时且对于人体无任何害处。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71434452393312256",
      "image": "https://qny.smzdm.com/202110/10/616280dc633036394.jpg_d320.jpg",
      "ownerUserId": null,
      "siteUrl": "https://wiki.smzdm.com/p/5qomwyd",
      "title": "【REVOMAX/锐虎70283保温杯报价】REVOMAX 锐虎 70283 保温杯套装 266ml+6颗【最新报价 最低价格 多少钱】 -什么值得买",
      "type": "feed",
      "url": "rsshub://smzdm/product/5qomwyd"
    }
  ]
}
```
