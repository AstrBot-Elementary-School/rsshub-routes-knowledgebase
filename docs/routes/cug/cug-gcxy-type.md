# 中国地质大学（武汉） - 工程学院

## Coverage
`index-only`

## Route
- Namespace: `cug`
- Namespace Name: `中国地质大学（武汉）`
- Route Path: `/cug/gcxy/:type?`
- Route Name: `工程学院`
- Example: `/cug/gcxy/xyxw`
- URL: `www.cug.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Doradx`
- Source Location: `gcxy.ts`
- Source Module: `_None_`

## Description
| 学院新闻 | 通知公告 | 党建新闻 | 学术动态 | 本科生培养 | 研究生教育 |
| -------- | -------- | -------- | -------- | ---------- | ---------- |
| xyxw     | tzgg     | djxw     | xsdt     | bkspy      | yjsjy      |

## Parameters
- `type`: 分类，见下表，默认为所有


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
  "description": "| 学院新闻 | 通知公告 | 党建新闻 | 学术动态 | 本科生培养 | 研究生教育 |\n| -------- | -------- | -------- | -------- | ---------- | ---------- |\n| xyxw     | tzgg     | djxw     | xsdt     | bkspy      | yjsjy      |",
  "example": "/cug/gcxy/xyxw",
  "heat": 0,
  "location": "gcxy.ts",
  "maintainers": [
    "Doradx"
  ],
  "name": "工程学院",
  "parameters": {
    "type": "分类，见下表，默认为所有"
  },
  "path": "/gcxy/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
