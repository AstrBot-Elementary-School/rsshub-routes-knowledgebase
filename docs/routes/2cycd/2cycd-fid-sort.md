# 二次元虫洞 - 板块

## Coverage
`index-only`

## Route
- Namespace: `2cycd`
- Namespace Name: `二次元虫洞`
- Route Path: `/2cycd/:fid/:sort?`
- Route Name: `板块`
- Example: `/2cycd/43/dateline`
- URL: `2cycd.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `shelken`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
板块（更多板块请自行 [查看](http://www.2cycd.com)）

| 音乐下载（默认） | 动漫下载 | 游戏下载 |
| ---------------- | -------- | -------- |
| 43               | 53       | 42       |

排序

| 发布时间排序（默认） | 回复／查看 | 查看  |
| -------------------- | ---------- | ----- |
| dateline             | replies    | views |

## Parameters
- `fid`: 板块
- `sort`: 排序


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "板块（更多板块请自行 [查看](http://www.2cycd.com)）\n\n| 音乐下载（默认） | 动漫下载 | 游戏下载 |\n| ---------------- | -------- | -------- |\n| 43               | 53       | 42       |\n\n排序\n\n| 发布时间排序（默认） | 回复／查看 | 查看  |\n| -------------------- | ---------- | ----- |\n| dateline             | replies    | views |",
  "example": "/2cycd/43/dateline",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "shelken"
  ],
  "name": "板块",
  "parameters": {
    "fid": "板块",
    "sort": "排序"
  },
  "path": "/:fid/:sort?",
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": []
}
```
