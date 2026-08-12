# 西北师范大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `nwnu`
- Namespace Name: `西北师范大学`
- Route Path: `/nwnu/department/academic-affairs/:column`
- Route Name: `教务处`
- Example: `/nwnu/department/academic-affairs/tzgg`
- URL: `www.nwnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `PrinOrange`
- Source Location: `routes/department/academic-affairs.ts`
- Source Module: `_None_`

## Description
| column | 标题     | 描述                     |
| ------ | -------- | ------------------------ |
| tzgg   | 通知公告 | 西北师范大学教务通知公告 |
| jwkx   | 教务快讯 | 西北师范大学教务快讯     |

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportRadar`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `jwc.nwnu.edu.cn/:column/list.htm`
- `target`: `/department/academic-affairs/:column`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| column | 标题     | 描述                     |\n| ------ | -------- | ------------------------ |\n| tzgg   | 通知公告 | 西北师范大学教务通知公告 |\n| jwkx   | 教务快讯 | 西北师范大学教务快讯     |",
  "example": "/nwnu/department/academic-affairs/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "routes/department/academic-affairs.ts",
  "maintainers": [
    "PrinOrange"
  ],
  "name": "教务处",
  "path": "/department/academic-affairs/:column",
  "radar": [
    {
      "source": [
        "jwc.nwnu.edu.cn/:column/list.htm"
      ],
      "target": "/department/academic-affairs/:column"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
