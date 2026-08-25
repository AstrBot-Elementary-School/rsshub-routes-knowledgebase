# 选股宝 - 主题

## Coverage
`index-only`

## Route
- Namespace: `xuangubao`
- Namespace Name: `选股宝`
- Route Path: `/xuangubao/subject/:subject_id`
- Route Name: `主题`
- Example: `/xuangubao/subject/41`
- URL: `xuangubao.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `hillerliao`
- Source Location: `subject.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `subject_id`: 主题 id，网址 https://xuangubao.cn/subject/41 中最后的数字


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
  "example": "/xuangubao/subject/41",
  "heat": 0,
  "location": "subject.ts",
  "maintainers": [
    "hillerliao"
  ],
  "name": "主题",
  "parameters": {
    "subject_id": "主题 id，网址 https://xuangubao.cn/subject/41 中最后的数字"
  },
  "path": "/subject/:subject_id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
