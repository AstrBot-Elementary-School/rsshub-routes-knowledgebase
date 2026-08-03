# 上海第二工业大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `sspu`
- Namespace Name: `上海第二工业大学`
- Route Path: `/sspu/jwc/:listId`
- Route Name: `教务处`
- Example: `/sspu/jwc/897`
- URL: `jwc.sspu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `TonyRL`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 学生专栏 | 教师专栏 |
| -------- | -------- |
| 897      | 898      |

## Parameters
- `listId`: 专栏 ID，见下表


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `jwc.sspu.edu.cn/jwc/:listId/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学生专栏 | 教师专栏 |\n| -------- | -------- |\n| 897      | 898      |",
  "example": "/sspu/jwc/897",
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "教务处",
  "parameters": {
    "listId": "专栏 ID，见下表"
  },
  "path": "/jwc/:listId",
  "radar": [
    {
      "source": [
        "jwc.sspu.edu.cn/jwc/:listId/list.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
