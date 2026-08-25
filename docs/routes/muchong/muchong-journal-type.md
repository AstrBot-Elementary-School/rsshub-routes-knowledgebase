# 小木虫论坛 - 期刊点评

## Coverage
`index-only`

## Route
- Namespace: `muchong`
- Namespace Name: `小木虫论坛`
- Route Path: `/muchong/journal/:type?`
- Route Name: `期刊点评`
- Example: `/muchong/journal`
- URL: `muchong.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `journal.ts`
- Source Module: `_None_`

## Description
| SCI 期刊 | 中文期刊 |
| -------- | -------- |
|          | cn       |

## Parameters
- `type`: 类型，见下表


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
  "description": "| SCI 期刊 | 中文期刊 |\n| -------- | -------- |\n|          | cn       |",
  "example": "/muchong/journal",
  "heat": 0,
  "location": "journal.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "期刊点评",
  "parameters": {
    "type": "类型，见下表"
  },
  "path": "/journal/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ Array(1) ] to not include 'http://muchong.com/bbs/journal.php?vi…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
