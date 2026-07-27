# Wellcee 唯心所寓 - 租房信息

## Coverage
`index-only`

## Route
- Namespace: `wellcee`
- Namespace Name: `Wellcee 唯心所寓`
- Route Path: `/wellcee/rent/:city/:district?`
- Route Name: `租房信息`
- Example: `/wellcee/rent/北京`
- URL: `www.wellcee.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `TonyRL`
- Source Location: `rent.tsx`
- Source Module: `_None_`

## Description
支持的城市可以通过 [/wellcee/support-city](https://rsshub.app/wellcee/support-city) 获取

## Parameters
- `city`: 城市
- `district`: 地区


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "支持的城市可以通过 [/wellcee/support-city](https://rsshub.app/wellcee/support-city) 获取",
  "example": "/wellcee/rent/北京",
  "heat": 8,
  "location": "rent.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "租房信息",
  "parameters": {
    "city": "城市",
    "district": "地区"
  },
  "path": "/rent/:city/:district?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "28K+ available Total 149K+ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "104852188412374016",
      "image": "https://qnimg1.wellcee.com/o_1ept4f34n7le86r1r0h14t8h1h1i.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://www.wellcee.com/rent-apartment/guangzhou/list?cityId=15903782307947352&lang=zh",
      "title": "广州租房信息 - Wellcee",
      "type": "feed",
      "url": "rsshub://wellcee/rent/%E5%B9%BF%E5%B7%9E"
    },
    {
      "description": "60K+ available Total 311K+ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "145865475543337984",
      "image": "https://qnimg1.wellcee.com/o_1ept4fjt6ho61844qd0102d132o1n.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://www.wellcee.com/rent-apartment/hangzhou/list?cityId=15960848556202921&lang=zh",
      "title": "杭州租房信息 - Wellcee",
      "type": "feed",
      "url": "rsshub://wellcee/rent/%E6%9D%AD%E5%B7%9E"
    }
  ],
  "url": "www.wellcee.com"
}
```
