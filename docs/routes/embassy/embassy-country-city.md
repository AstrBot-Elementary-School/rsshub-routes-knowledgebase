# 中国驻外使领馆 - 使领馆重要通知

## Coverage
`index-only`

## Route
- Namespace: `embassy`
- Namespace Name: `中国驻外使领馆`
- Route Path: `/embassy/:country/:city?`
- Route Name: `使领馆重要通知`
- Example: `/embassy/us/chicago`
- URL: `ca.china-embassy.org`
- Language: `_None_`
- Categories: `government`
- Maintainers: `HenryQW`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `country`: 国家短代码, 见支持国家列表
- `city`: 城市, 对应国家列表下的`领事馆城市列表`，不填则为大使馆


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/embassy/us/chicago",
  "heat": 29,
  "location": "index.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "使领馆重要通知",
  "parameters": {
    "city": "城市, 对应国家列表下的`领事馆城市列表`，不填则为大使馆",
    "country": "国家短代码, 见支持国家列表"
  },
  "path": "/:country/:city?",
  "topFeeds": [
    {
      "description": "中国驻美国大使馆 -- 重要通知 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "103274970550038533",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://us.china-embassy.gov.cn/zytz/",
      "title": "中国驻美国大使馆 -- 重要通知",
      "type": "feed",
      "url": "rsshub://embassy/us"
    },
    {
      "description": "中国驻新加坡大使馆 -- 重要通知 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "103274970550038532",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://sg.china-embassy.gov.cn/lsfw_0/zytz/",
      "title": "中国驻新加坡大使馆 -- 重要通知",
      "type": "feed",
      "url": "rsshub://embassy/sg"
    }
  ]
}
```
