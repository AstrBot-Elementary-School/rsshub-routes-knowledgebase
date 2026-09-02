# 淘股吧 - 淘股论坛

## Coverage
`index-only`

## Route
- Namespace: `taoguba`
- Namespace Name: `淘股吧`
- Route Path: `/taoguba/:category?`
- Route Name: `淘股论坛`
- Example: `/taoguba`
- URL: `tgb.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 淘股论坛 | 社区总版 | 精华加油 | 网友点赞 |
| -------- | -------- | -------- | -------- |
| bbs      | zongban  | jinghua  | dianzan  |

## Parameters
- `id`: 分类，见下表，默认为社区总版


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 淘股论坛 | 社区总版 | 精华加油 | 网友点赞 |\n| -------- | -------- | -------- | -------- |\n| bbs      | zongban  | jinghua  | dianzan  |",
  "example": "/taoguba",
  "heat": 250,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "淘股论坛",
  "parameters": {
    "id": "分类，见下表，默认为社区总版"
  },
  "path": "/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "淘股吧股票论坛总版 - Powered by RSSHub",
      "errorAt": "2026-06-24T21:12:43.752Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://www.tgb.cn//a/2uIgSGDTpJb\": 404 \n[GET] \"https://www.tgb.cn//a/2uIa4bWzFXt\": 404 Not Found\n",
      "id": "101439531051305984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.tgb.cn/zongban/",
      "title": "淘股吧股票论坛总版",
      "type": "feed",
      "url": "rsshub://taoguba"
    },
    {
      "description": "淘股吧散户炒股交流点赞牛贴 - Powered by RSSHub",
      "errorAt": "2026-07-02T22:09:34.740Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://www.tgb.cn//a/2uD3N20OCMF\": 404 \n[GET] \"https://www.tgb.cn//a/2uIb5S67QCv\": 404 Not Found\n",
      "id": "115961018043937792",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.tgb.cn/dianzan/",
      "title": "淘股吧散户炒股交流点赞牛贴",
      "type": "feed",
      "url": "rsshub://taoguba/dianzan"
    }
  ]
}
```
