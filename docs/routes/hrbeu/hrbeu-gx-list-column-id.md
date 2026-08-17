# 哈尔滨工程大学 - 工学新闻 - 列表页面

## Coverage
`index-only`

## Route
- Namespace: `hrbeu`
- Namespace Name: `哈尔滨工程大学`
- Route Path: `/hrbeu/gx/list/:column/:id?`
- Route Name: `工学新闻 - 列表页面`
- Example: `/hrbeu/gx/list/xw/yw`
- URL: `yjsy.hrbeu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Derekmini, XYenon`
- Source Location: `gx/list.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `column`: 主栏，如 `新闻：xw`，由 `URL` 中获取；
- `id`: 次栏，如 `要闻：yw`，如果次栏存在，则为必选，由 `URL` 中获取。


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/hrbeu/gx/list/xw/yw",
  "heat": 0,
  "location": "gx/list.ts",
  "maintainers": [
    "Derekmini",
    "XYenon"
  ],
  "name": "工学新闻 - 列表页面",
  "parameters": {
    "column": "主栏，如 `新闻：xw`，由 `URL` 中获取；",
    "id": "次栏，如 `要闻：yw`，如果次栏存在，则为必选，由 `URL` 中获取。"
  },
  "path": "/gx/list/:column/:id?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
