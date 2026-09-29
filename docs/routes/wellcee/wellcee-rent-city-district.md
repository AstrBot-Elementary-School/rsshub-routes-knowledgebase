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
      "description": "62K+ available Total 322K+ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "145865475543337984",
      "image": "https://qnimg1.wellcee.com/o_1ept4fjt6ho61844qd0102d132o1n.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://www.wellcee.com/rent-apartment/hangzhou/list?cityId=15960848556202921&lang=zh",
      "title": "杭州租房信息 - Wellcee",
      "type": "feed",
      "url": "rsshub://wellcee/rent/%E6%9D%AD%E5%B7%9E"
    },
    {
      "description": "98K+ available Total 716K+ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72676239808601088",
      "image": "https://qnimg1.wellcee.com/o_1ept4dnug1fv1msq7gf11r117gnu.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.wellcee.com/rent-apartment/shanghai/list?cityId=15102233103895305&lang=zh",
      "title": "上海租房信息 - Wellcee",
      "type": "feed",
      "url": "rsshub://wellcee/rent/%E4%B8%8A%E6%B5%B7"
    }
  ],
  "url": "www.wellcee.com"
}
```
