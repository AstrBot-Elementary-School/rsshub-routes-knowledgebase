# 求是网 - 在线读刊

## Coverage
`index-only`

## Route
- Namespace: `qstheory`
- Namespace Name: `求是网`
- Route Path: `/qstheory/magazine/:magazine`
- Route Name: `在线读刊`
- Example: `/qstheory/magazine/qs`
- URL: `www.qstheory.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL, cscnk52`
- Source Location: `magazine.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `magazine`: 刊物，`qs` 为求是，`hqwglist` 为红旗文稿


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.qstheory.cn/:magazine/mulu.htm`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/qstheory/magazine/qs",
  "heat": 507,
  "location": "magazine.ts",
  "maintainers": [
    "TonyRL",
    "cscnk52"
  ],
  "name": "在线读刊",
  "parameters": {
    "magazine": "刊物，`qs` 为求是，`hqwglist` 为红旗文稿"
  },
  "path": "/magazine/:magazine",
  "radar": [
    {
      "source": [
        "www.qstheory.cn/:magazine/mulu.htm"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "《求是》 - 求是网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80433099883252736",
      "image": "http://www.qstheory.cn/20260916/fd06d8d2be9141b3a1aa990e066f7aa2/e82c577defe44bb096b65dfe35b44139.jpg",
      "ownerUserId": null,
      "siteUrl": "http://www.qstheory.cn/qs/mulu.htm",
      "title": "《求是》 - 求是网",
      "type": "feed",
      "url": "rsshub://qstheory/magazine/qs"
    },
    {
      "description": "《红旗文稿》 - 求是网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80489063705907200",
      "image": "http://www.qstheory.cn/20260911/7022c3e1914f42ddbd851dcfce3ff8cf/d4694037b2ec474ba201e994459cb43d.jpg",
      "ownerUserId": null,
      "siteUrl": "http://www.qstheory.cn/hqwglist/mulu.htm",
      "title": "《红旗文稿》 - 求是网",
      "type": "feed",
      "url": "rsshub://qstheory/magazine/hqwglist"
    }
  ]
}
```
