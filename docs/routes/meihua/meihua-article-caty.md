# 梅花网 - 文章

## Coverage
`index-only`

## Route
- Namespace: `meihua`
- Namespace Name: `梅花网`
- Route Path: `/meihua/article/:caty`
- Route Name: `文章`
- Example: `/meihua/article/latest`
- URL: `www.meihua.info`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
| 最新   | 热门 |
| ------ | ---- |
| latest | hot  |

## Parameters
- `caty`: 分类，见下表


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 最新   | 热门 |\n| ------ | ---- |\n| latest | hot  |",
  "example": "/meihua/article/latest",
  "heat": 0,
  "location": "article.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "文章",
  "parameters": {
    "caty": "分类，见下表"
  },
  "path": "/article/:caty",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
