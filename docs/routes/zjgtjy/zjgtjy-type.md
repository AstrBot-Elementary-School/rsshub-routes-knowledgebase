# 浙江省土地使用权网上交易系统 - 公告信息

## Coverage
`index-only`

## Route
- Namespace: `zjgtjy`
- Namespace Name: `浙江省土地使用权网上交易系统`
- Route Path: `/zjgtjy/:type?`
- Route Name: `公告信息`
- Example: `/zjgtjy/all`
- URL: `zjgtjy.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 全部公告 | 挂牌公告 | 拍卖公告 | 补充公告 |
| :------: | :------: | :------: | :------: |
|    all   |   gpgg   |   pmgg   |   bcgg   |

## Parameters
- `type`: 分类名


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 全部公告 | 挂牌公告 | 拍卖公告 | 补充公告 |\n| :------: | :------: | :------: | :------: |\n|    all   |   gpgg   |   pmgg   |   bcgg   |",
  "example": "/zjgtjy/all",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "公告信息",
  "parameters": {
    "type": "分类名"
  },
  "path": "/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
