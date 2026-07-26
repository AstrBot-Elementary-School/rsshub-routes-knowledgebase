# Shaanxi Normal University - 计算机科学学院

## Coverage
`index-only`

## Route
- Namespace: `snnu`
- Namespace Name: `Shaanxi Normal University`
- Route Path: `/snnu/ccs/:type?`
- Route Name: `计算机科学学院`
- Example: `/snnu/ccs`
- URL: `ccs.snnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `alterkeyy`
- Source Location: `ccs.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: 类型，默认为通知公告 (tzgg)，可选学院动态 (news)、学术活动 (xshd)


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `ccs.snnu.edu.cn/tzgg/zhgl1.htm`
- `target`: `/ccs/tzgg`
### Rule 2
- `source`:
  - `ccs.snnu.edu.cn/xydt/zhxw1.htm`
- `target`: `/ccs/news`
### Rule 3
- `source`:
  - `ccs.snnu.edu.cn/xssq/xshd.htm`
- `target`: `/ccs/xshd`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/snnu/ccs",
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
  "location": "ccs.ts",
  "maintainers": [
    "alterkeyy"
  ],
  "name": "计算机科学学院",
  "parameters": {
    "type": "类型，默认为通知公告 (tzgg)，可选学院动态 (news)、学术活动 (xshd)"
  },
  "path": "/ccs/:type?",
  "radar": [
    {
      "source": [
        "ccs.snnu.edu.cn/tzgg/zhgl1.htm"
      ],
      "target": "/ccs/tzgg"
    },
    {
      "source": [
        "ccs.snnu.edu.cn/xydt/zhxw1.htm"
      ],
      "target": "/ccs/news"
    },
    {
      "source": [
        "ccs.snnu.edu.cn/xssq/xshd.htm"
      ],
      "target": "/ccs/xshd"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "ccs.snnu.edu.cn"
}
```
