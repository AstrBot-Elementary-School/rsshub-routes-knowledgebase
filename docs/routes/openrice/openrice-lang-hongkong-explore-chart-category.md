# Openrice開飯喇 - 香港餐廳排行榜

## Coverage
`index-only`

## Route
- Namespace: `openrice`
- Namespace Name: `Openrice開飯喇`
- Route Path: `/openrice/:lang/hongkong/explore/chart/:category`
- Route Name: `香港餐廳排行榜`
- Example: `/openrice/zh/hongkong/explore/chart/most-bookmarked`
- URL: `www.openrice.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `after9`
- Source Location: `chart.tsx`
- Source Module: `_None_`

## Description
| 简体  | 繁體 | EN |
| ----- | ---- | -- |
| zh-cn | zh   | en |

| 最多收藏        | 每周最高评分 | 最高浏览     | 最佳甜品餐厅 |
| --------------- | ------------ | ------------ | ------------ |
| most-bookmarked | best-rating  | most-popular | best-dessert |

## Parameters
- `lang`: 语言，缺省为 zh
- `category`: 类别，缺省为 most-bookmarked


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "| 简体  | 繁體 | EN |\n| ----- | ---- | -- |\n| zh-cn | zh   | en |\n\n| 最多收藏        | 每周最高评分 | 最高浏览     | 最佳甜品餐厅 |\n| --------------- | ------------ | ------------ | ------------ |\n| most-bookmarked | best-rating  | most-popular | best-dessert |",
  "example": "/openrice/zh/hongkong/explore/chart/most-bookmarked",
  "heat": 34,
  "location": "chart.tsx",
  "maintainers": [
    "after9"
  ],
  "name": "香港餐廳排行榜",
  "parameters": {
    "category": "类别，缺省为 most-bookmarked",
    "lang": "语言，缺省为 zh"
  },
  "path": "/:lang/hongkong/explore/chart/:category",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "最多收藏 – 香港餐廳排行榜 – 搵食 | OpenRice 香港開飯喇 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76433972999429120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.openrice.com/zh/hongkong/explore/chart/most-bookmarked",
      "title": "最多收藏 – 香港餐廳排行榜 – 搵食 | OpenRice 香港開飯喇",
      "type": "feed",
      "url": "rsshub://openrice/zh/hongkong/explore/chart/most-bookmarked"
    },
    {
      "description": "最佳甜品餐廳 – 香港餐廳排行榜 – 搵食 | OpenRice 香港開飯喇 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76442757221974016",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.openrice.com/zh/hongkong/explore/chart/best-dessert",
      "title": "最佳甜品餐廳 – 香港餐廳排行榜 – 搵食 | OpenRice 香港開飯喇",
      "type": "feed",
      "url": "rsshub://openrice/zh/hongkong/explore/chart/best-dessert"
    }
  ]
}
```
