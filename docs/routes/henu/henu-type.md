# 河南大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `henu`
- Namespace Name: `河南大学`
- Route Path: `/henu/:type?`
- Route Name: `教务处`
- Example: `/henu/tzgg`
- URL: `henu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `CasterWx`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 教学动态 | 媒体报道 |
| -------- | -------- | -------- |
| tzgg     | jxdt     | mtbd     |

## Parameters
- `type`: 分类，见下表，默认为通知公告


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
  "description": "| 通知公告 | 教学动态 | 媒体报道 |\n| -------- | -------- | -------- |\n| tzgg     | jxdt     | mtbd     |",
  "example": "/henu/tzgg",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "CasterWx"
  ],
  "name": "教务处",
  "parameters": {
    "type": "分类，见下表，默认为通知公告"
  },
  "path": "/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
