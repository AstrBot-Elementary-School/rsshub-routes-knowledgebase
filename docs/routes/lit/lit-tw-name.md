# 洛阳理工学院 - 团委

## Coverage
`index-only`

## Route
- Namespace: `lit`
- Namespace Name: `洛阳理工学院`
- Route Path: `/lit/tw/:name?`
- Route Name: `团委`
- Example: `/lit/tw`
- URL: `www.lit.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `vhxubo`
- Source Location: `tw.ts`
- Source Module: `_None_`

## Description
| 全部 | 新闻动态 | 公示公告 |
| ---- | -------- | -------- |
| all  | xwdt     | gsgg     |

## Parameters
- `name`: 默认为 `all`


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
  "description": "| 全部 | 新闻动态 | 公示公告 |\n| ---- | -------- | -------- |\n| all  | xwdt     | gsgg     |",
  "example": "/lit/tw",
  "heat": 0,
  "location": "tw.ts",
  "maintainers": [
    "vhxubo"
  ],
  "name": "团委",
  "parameters": {
    "name": "默认为 `all`"
  },
  "path": "/tw/:name?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
