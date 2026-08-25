# 猫眼电影 - 正在热映 - 完整版

## Coverage
`index-only`

## Route
- Namespace: `maoyan`
- Namespace Name: `猫眼电影`
- Route Path: `/maoyan/hotComplete/:orderby?/:ascOrDesc?/:top?`
- Route Name: `正在热映 - 完整版`
- Example: `/maoyan/hotComplete`
- URL: `maoyan.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `chenbstack`
- Source Location: `hot-complete.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `orderby`: 排序条件，(score: 评分, pubDate: 发布时间)
- `ascOrDesc`: 正序或倒序 (asc: 正序, desc: 倒序) 默认倒序
- `top`: 取前多少条，默认取所有


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/maoyan/hotComplete",
  "heat": 0,
  "location": "hot-complete.ts",
  "maintainers": [
    "chenbstack"
  ],
  "name": "正在热映 - 完整版",
  "parameters": {
    "ascOrDesc": "正序或倒序 (asc: 正序, desc: 倒序) 默认倒序",
    "orderby": "排序条件，(score: 评分, pubDate: 发布时间)",
    "top": "取前多少条，默认取所有"
  },
  "path": "/hotComplete/:orderby?/:ascOrDesc?/:top?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected -2043345441 to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
