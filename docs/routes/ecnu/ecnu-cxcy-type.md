# East China Normal University 华东师范大学 - 本科创新创业教育网

## Coverage
`index-only`

## Route
- Namespace: `ecnu`
- Namespace Name: `East China Normal University 华东师范大学`
- Route Path: `/ecnu/cxcy/:type?`
- Route Name: `本科创新创业教育网`
- Example: `/ecnu/cxcy`
- URL: `www.ecnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `FrozenStarrrr, ChiyoYuki, ECNU-minus`
- Source Location: `cxcy.ts`
- Source Module: `_None_`

## Description
| 通知公告     | 新闻动态 | 学科竞赛 | 常用资源  |
| ------------ | -------- | -------- | --------- |
| announcement | news     | contest  | resources |

## Parameters
- `type`: 默认为 announcement


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `cxcy.ecnu.edu.cn`
- `target`: `/cxcy`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告     | 新闻动态 | 学科竞赛 | 常用资源  |\n| ------------ | -------- | -------- | --------- |\n| announcement | news     | contest  | resources |",
  "example": "/ecnu/cxcy",
  "heat": 0,
  "location": "cxcy.ts",
  "maintainers": [
    "FrozenStarrrr",
    "ChiyoYuki",
    "ECNU-minus"
  ],
  "name": "本科创新创业教育网",
  "parameters": {
    "type": "默认为 announcement"
  },
  "path": "/cxcy/:type?",
  "radar": [
    {
      "source": [
        "cxcy.ecnu.edu.cn"
      ],
      "target": "/cxcy"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
