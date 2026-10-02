# 掘金 - 单个收藏夹

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/juejin/collection/:collectionId`
- Route Name: `单个收藏夹`
- Example: `/juejin/collection/6845243180586123271`
- URL: `juejin.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `yang131323`
- Source Location: `collection.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `collectionId`: 收藏夹唯一标志符, 在浏览器地址栏URL中能够找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `juejin.cn/collection/:collectionId`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/juejin/collection/6845243180586123271",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "collection.ts",
  "maintainers": [
    "yang131323"
  ],
  "name": "单个收藏夹",
  "parameters": {
    "collectionId": "收藏夹唯一标志符, 在浏览器地址栏URL中能够找到"
  },
  "path": "/collection/:collectionId",
  "radar": [
    {
      "source": [
        "juejin.cn/collection/:collectionId"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "掘金，用户单个收藏夹 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "99764432283070464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://juejin.cn/collection/7304865158035685387",
      "title": "复杂场景实现 - 我在云上啊的收藏集 - 掘金",
      "type": "feed",
      "url": "rsshub://juejin/collection/7304865158035685387"
    },
    {
      "description": "掘金，用户单个收藏夹 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74294662018781184",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://juejin.cn/collection/7173498935204397087",
      "title": "细读好文 - 人群三三两两的收藏集 - 掘金",
      "type": "feed",
      "url": "rsshub://juejin/collection/7173498935204397087"
    }
  ]
}
```
