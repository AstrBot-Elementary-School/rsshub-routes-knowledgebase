# 无产者评论 - 分类 / 标签

## Coverage
`index-only`

## Route
- Namespace: `proletar`
- Namespace Name: `无产者评论`
- Route Path: `/proletar/:type?/:id?`
- Route Name: `分类 / 标签`
- Example: `/proletar`
- URL: `review.proletar.ink`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 全部文章 | 中流击水 | 革命文艺 | 当代中国 | 理论视野 | 国际观察 | 史海沉钩 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- |
|          | 中流击水 | 革命文艺 | 当代中国 | 理论视野 | 国际观察 | 史海沉钩 |

## Parameters
- `type`: 类型，`categories` 分类或 `tags` 标签，默认为全部文章
- `id`: 分类见下表，标签名参见 [所有标签](https://review.proletar.ink/tags)


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
  "description": "| 全部文章 | 中流击水 | 革命文艺 | 当代中国 | 理论视野 | 国际观察 | 史海沉钩 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n|          | 中流击水 | 革命文艺 | 当代中国 | 理论视野 | 国际观察 | 史海沉钩 |",
  "example": "/proletar",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类 / 标签",
  "parameters": {
    "id": "分类见下表，标签名参见 [所有标签](https://review.proletar.ink/tags)",
    "type": "类型，`categories` 分类或 `tags` 标签，默认为全部文章"
  },
  "path": "/:type?/:id?",
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": []
}
```
