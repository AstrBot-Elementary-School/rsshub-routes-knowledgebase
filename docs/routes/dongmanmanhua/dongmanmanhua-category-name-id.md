# 咚漫 - 漫画更新

## Coverage
`index-only`

## Route
- Namespace: `dongmanmanhua`
- Namespace Name: `咚漫`
- Route Path: `/dongmanmanhua/:category/:name/:id`
- Route Name: `漫画更新`
- Example: `/dongmanmanhua/COMEDY/xin-xinlingdeshengyin/381`
- URL: `www.dongmanmanhua.cn`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `machsix`
- Source Location: `comic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 类别
- `name`: 名称
- `id`: ID


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/dongmanmanhua/COMEDY/xin-xinlingdeshengyin/381",
  "heat": 0,
  "location": "comic.ts",
  "maintainers": [
    "machsix"
  ],
  "name": "漫画更新",
  "parameters": {
    "category": "类别",
    "id": "ID",
    "name": "名称"
  },
  "path": "/:category/:name/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 365822741567 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
