# 爱范儿 - 分类

## Coverage
`index-only`

## Route
- Namespace: `ifanr`
- Namespace Name: `爱范儿`
- Route Path: `/ifanr/category/:name`
- Route Name: `分类`
- Example: `/ifanr/category/早报`
- URL: `www.ifanr.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `donghongfei`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
支持分类：早报、评测、糖纸众测、产品

## Parameters
- `name`: {"description": "分类名称", "options": [{"label": "早报", "value": "早报"}, {"label": "评测", "value": "评测"}, {"label": "糖纸众测", "value": "糖纸众测"}, {"label": "产品", "value": "产品"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.ifanr.com/category/:name`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "支持分类：早报、评测、糖纸众测、产品",
  "example": "/ifanr/category/早报",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 123,
  "location": "category.ts",
  "maintainers": [
    "donghongfei"
  ],
  "name": "分类",
  "parameters": {
    "name": {
      "description": "分类名称",
      "options": [
        {
          "label": "早报",
          "value": "早报"
        },
        {
          "label": "评测",
          "value": "评测"
        },
        {
          "label": "糖纸众测",
          "value": "糖纸众测"
        },
        {
          "label": "产品",
          "value": "产品"
        }
      ]
    }
  },
  "path": "/category/:name",
  "radar": [
    {
      "source": [
        "www.ifanr.com/category/:name"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "早报 更新推送 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "95441108348436480",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ifanr.com/category/ifanrnews",
      "title": "#早报 - iFanr 爱范儿",
      "type": "feed",
      "url": "rsshub://ifanr/category/%E6%97%A9%E6%8A%A5"
    },
    {
      "description": "产品 更新推送 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "113269047681741824",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ifanr.com/category/product",
      "title": "#产品 - iFanr 爱范儿",
      "type": "feed",
      "url": "rsshub://ifanr/category/%E4%BA%A7%E5%93%81"
    }
  ]
}
```
