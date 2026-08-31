# 国家药品审评网站 - 信息公开

## Coverage
`index-only`

## Route
- Namespace: `cde`
- Namespace Name: `国家药品审评网站`
- Route Path: `/cde/xxgk/:category`
- Route Name: `信息公开`
- Example: `/cde/xxgk/priorityApproval`
- URL: `www.cde.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `TonyRL`
- Source Location: `xxgk.tsx`
- Source Module: `_None_`

## Description
|   优先审评公示   |  突破性治疗公示  | 临床试验默示许可 |
| :--------------: | :--------------: | :--------------: |
| priorityApproval | breakthroughCure |     cliniCal     |

## Parameters
- `category`: 类别，见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "|   优先审评公示   |  突破性治疗公示  | 临床试验默示许可 |\n| :--------------: | :--------------: | :--------------: |\n| priorityApproval | breakthroughCure |     cliniCal     |",
  "example": "/cde/xxgk/priorityApproval",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "xxgk.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "信息公开",
  "parameters": {
    "category": "类别，见下表"
  },
  "path": "/xxgk/:category",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
