# Openrice開飯喇 - 香港餐厅滋讯

## Coverage
`index-only`

## Route
- Namespace: `openrice`
- Namespace Name: `Openrice開飯喇`
- Route Path: `/openrice/:lang/hongkong/promos`
- Route Name: `香港餐厅滋讯`
- Example: `/openrice/zh/hongkong/promos`
- URL: `www.openrice.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `after9`
- Source Location: `promos.ts`
- Source Module: `_None_`

## Description
| 简体  | 繁體 | EN |
| ----- | ---- | -- |
| zh-cn | zh   | en |

## Parameters
- `lang`: 语言，缺省为 zh


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
  "description": "| 简体  | 繁體 | EN |\n| ----- | ---- | -- |\n| zh-cn | zh   | en |",
  "example": "/openrice/zh/hongkong/promos",
  "heat": 13,
  "location": "promos.ts",
  "maintainers": [
    "after9"
  ],
  "name": "香港餐厅滋讯",
  "parameters": {
    "lang": "语言，缺省为 zh"
  },
  "path": "/:lang/hongkong/promos",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "OpenRice為你搜羅香港今期既飲食熱話，絕對值得一試。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72523198167038976",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.openrice.com/zh/hongkong/promos",
      "title": "餐廳滋訊 | OpenRice 香港開飯喇",
      "type": "feed",
      "url": "rsshub://openrice/zh/hongkong/promos"
    },
    {
      "description": "OpenRice為你搜羅香港今期既飲食熱話，絕對值得一試。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "85408863792574464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.openrice.com/zh/hongkong/promos",
      "title": "餐廳滋訊 | OpenRice 香港開飯喇",
      "type": "feed",
      "url": "rsshub://openrice/:lang/hongkong/promos"
    }
  ]
}
```
