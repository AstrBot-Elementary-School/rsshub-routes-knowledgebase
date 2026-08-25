# 超理论坛 - 板块

## Coverage
`index-only`

## Route
- Namespace: `chaoli`
- Namespace Name: `超理论坛`
- Route Path: `/chaoli/:channel?`
- Route Name: `板块`
- Example: `/chaoli`
- URL: `chaoli.club`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 数学 | 物理    | 化学 | 生物    | 天文  | 技术 | 管理  | 公告   |
| ---- | ------- | ---- | ------- | ----- | ---- | ----- | ------ |
| math | physics | chem | biology | astro | tech | admin | announ |

| 其他   | 语言 | 社科   | 科幻   | 辑录        |
| ------ | ---- | ------ | ------ | ----------- |
| others | lang | socsci | sci-fi | collections |

## Parameters
- `channel`: 板块，见下表，默认为全部


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
  "description": "| 数学 | 物理    | 化学 | 生物    | 天文  | 技术 | 管理  | 公告   |\n| ---- | ------- | ---- | ------- | ----- | ---- | ----- | ------ |\n| math | physics | chem | biology | astro | tech | admin | announ |\n\n| 其他   | 语言 | 社科   | 科幻   | 辑录        |\n| ------ | ---- | ------ | ------ | ----------- |\n| others | lang | socsci | sci-fi | collections |",
  "example": "/chaoli",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "板块",
  "parameters": {
    "channel": "板块，见下表，默认为全部"
  },
  "path": "/:channel?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
