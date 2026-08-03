# 北京师范大学 - 党委学生工作部

## Coverage
`index-only`

## Route
- Namespace: `bnu`
- Namespace Name: `北京师范大学`
- Route Path: `/bnu/dwxgb/:category/:type`
- Route Name: `党委学生工作部`
- Example: `/bnu/dwxgb/xwzx/tzgg`
- URL: `bs.bnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Fatpandac`
- Source Location: `dwxgb.ts`
- Source Module: `_None_`

## Description
`https://dwxgb.bnu.edu.cn/xwzx/tzgg/index.html` 则对应为 \`/bnu/dwxgb/xwzx/tzgg

## Parameters
- `category`: 大分类
- `type`: 子分类，例子如下


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
  - `dwxgb.bnu.edu.cn/:category/:type/index.html`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "`https://dwxgb.bnu.edu.cn/xwzx/tzgg/index.html` 则对应为 \\`/bnu/dwxgb/xwzx/tzgg",
  "example": "/bnu/dwxgb/xwzx/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "dwxgb.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "党委学生工作部",
  "parameters": {
    "category": "大分类",
    "type": "子分类，例子如下"
  },
  "path": "/dwxgb/:category/:type",
  "radar": [
    {
      "source": [
        "dwxgb.bnu.edu.cn/:category/:type/index.html"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 'RSSHub' not to be 'RSSHub' // Object.is equality\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:69:30)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "新闻中心 - 通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "188383956694418432",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://dwxgb.bnu.edu.cn/xwzx/tzgg/index.html",
      "title": "新闻中心 - 通知公告",
      "type": "feed",
      "url": "rsshub://bnu/dwxgb/xwzx/tzgg"
    }
  ]
}
```
