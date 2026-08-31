# 南京理工大学 - 电光学院

## Coverage
`index-only`

## Route
- Namespace: `njust`
- Namespace Name: `南京理工大学`
- Route Path: `/njust/eoe/:type?`
- Route Name: `电光学院`
- Example: `/njust/eoe/tzgg`
- URL: `jwc.njust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `jasongzy`
- Source Location: `eoe.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 新闻动态 |
| -------- | -------- |
| tzgg     | xwdt     |

## Parameters
- `type`: 分类名，见下表，默认为通知公告


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
    "university"
  ],
  "description": "| 通知公告 | 新闻动态 |\n| -------- | -------- |\n| tzgg     | xwdt     |",
  "example": "/njust/eoe/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "eoe.ts",
  "maintainers": [
    "jasongzy"
  ],
  "name": "电光学院",
  "parameters": {
    "type": "分类名，见下表，默认为通知公告"
  },
  "path": "/eoe/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
