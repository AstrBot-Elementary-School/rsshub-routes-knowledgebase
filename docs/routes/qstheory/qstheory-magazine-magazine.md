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
  "heat": 489,
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
      "image": "http://www.qstheory.cn/20260801/9a9fcda050c34a8fa7c85d93da974278/f38ad131caed4d30b43cdeef7cdd0064.jpg",
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
      "image": "http://www.qstheory.cn/20260727/e49650ce8c774d6b8c9ea7d7a6426e3c/4384ee4ad0464f8abbb169f652b4764d.jpg",
      "ownerUserId": null,
      "siteUrl": "http://www.qstheory.cn/hqwglist/mulu.htm",
      "title": "《红旗文稿》 - 求是网",
      "type": "feed",
      "url": "rsshub://qstheory/magazine/hqwglist"
    }
  ]
}
```
