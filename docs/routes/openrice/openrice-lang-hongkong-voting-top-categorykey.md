# Openrice開飯喇 - OpenRice 開飯熱店 - 年度餐廳投票

## Coverage
`index-only`

## Route
- Namespace: `openrice`
- Namespace Name: `Openrice開飯喇`
- Route Path: `/openrice/:lang/hongkong/voting/top/:categoryKey`
- Route Name: `OpenRice 開飯熱店 - 年度餐廳投票`
- Example: `/openrice/zh/hongkong/voting/top/chinese`
- URL: `www.openrice.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `after9`
- Source Location: `voting.ts`
- Source Module: `_None_`

## Description
lang: 语言，见下方列表

| 简体  | 繁體 | EN |
| ----- | ---- | -- |
| zh-cn | zh   | en |

categoryKey: 部分类别，见下方列表 (更多的类别可以在页面的 link 中对照获取)

| 中菜館  | 上海菜       | 粵菜      | 川菜    | 港式    | 粥粉麵店        | 廚師發辦 | 韓國菜 | 泰國菜 | 越南菜     |
| ------- | ------------ | --------- | ------- | ------- | --------------- | -------- | ------ | ------ | ---------- |
| chinese | shanghainese | guangdong | sichuan | hkstyle | congee\_noodles | omakase  | korean | thai   | vietnamese |

## Parameters
- `lang`: 语言，缺省为 zh
- `categoryKey`: 类别，缺省为 chinese


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
  "description": "lang: 语言，见下方列表\n\n| 简体  | 繁體 | EN |\n| ----- | ---- | -- |\n| zh-cn | zh   | en |\n\ncategoryKey: 部分类别，见下方列表 (更多的类别可以在页面的 link 中对照获取)\n\n| 中菜館  | 上海菜       | 粵菜      | 川菜    | 港式    | 粥粉麵店        | 廚師發辦 | 韓國菜 | 泰國菜 | 越南菜     |\n| ------- | ------------ | --------- | ------- | ------- | --------------- | -------- | ------ | ------ | ---------- |\n| chinese | shanghainese | guangdong | sichuan | hkstyle | congee\\_noodles | omakase  | korean | thai   | vietnamese |",
  "example": "/openrice/zh/hongkong/voting/top/chinese",
  "heat": 2,
  "location": "voting.ts",
  "maintainers": [
    "after9"
  ],
  "name": "OpenRice 開飯熱店 - 年度餐廳投票",
  "parameters": {
    "categoryKey": "类别，缺省为 chinese",
    "lang": "语言，缺省为 zh"
  },
  "path": "/:lang/hongkong/voting/top/:categoryKey",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "OpenRice用戶可以在網站或手機應用程式，點擊餐廳頁面中「投票」按鈕，即可完成投票。參加投票的用戶有機會參加大抽獎，贏取豐富獎品。 - Powered by RSSHub",
      "errorAt": "2025-07-16T11:07:38.235Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "77037193957576704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.openrice.com/zh/hongkong/voting/top",
      "title": "OpenRice 開飯熱店",
      "type": "feed",
      "url": "rsshub://openrice/zh/hongkong/voting/top/chinese"
    }
  ]
}
```
