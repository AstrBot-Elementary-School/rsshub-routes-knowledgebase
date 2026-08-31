# 青空文庫 - 新着リスト

## Coverage
`index-only`

## Route
- Namespace: `aozora`
- Namespace Name: `青空文庫`
- Route Path: `/aozora/newbook/:count?`
- Route Name: `新着リスト`
- Example: `/aozora/newbook/10`
- URL: `www.aozora.gr.jp`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `sgqy`
- Source Location: `newbook.ts`
- Source Module: `_None_`

## Description
书籍网站每日一更。信息更新时间为书籍最初出版时间，排序可能不符合网络发表时间，请认准未读消息.

## Parameters
- `count`: 更新数量. 设置每次下载列表大小. 范围是 1 到 50.


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "书籍网站每日一更。信息更新时间为书籍最初出版时间，排序可能不符合网络发表时间，请认准未读消息.",
  "example": "/aozora/newbook/10",
  "heat": 0,
  "location": "newbook.ts",
  "maintainers": [
    "sgqy"
  ],
  "name": "新着リスト",
  "parameters": {
    "count": "更新数量. 设置每次下载列表大小. 范围是 1 到 50."
  },
  "path": "/newbook/:count?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 351565912914 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
