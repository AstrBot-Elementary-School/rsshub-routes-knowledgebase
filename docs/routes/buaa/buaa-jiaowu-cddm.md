# 北京航空航天大学 - 教务部

## Coverage
`index-only`

## Route
- Namespace: `buaa`
- Namespace Name: `北京航空航天大学`
- Route Path: `/buaa/jiaowu/:cddm?`
- Route Name: `教务部`
- Example: `/buaa/jiaowu/02`
- URL: `jiaowu.buaa.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `OverflowCat`
- Source Location: `jiaowu.ts`
- Source Module: `_None_`

## Description
通知公告取官网首页的通知列表，包含学生和教师通知。旧站 newsList 接口已下线；目前公示专区页面返回系统提示，需等待官网恢复该栏目。

## Parameters
- `cddm`: 栏目代码：02（通知公告，默认）、03（新闻快讯）、0203（公示专区）


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: false
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
  "description": "通知公告取官网首页的通知列表，包含学生和教师通知。旧站 newsList 接口已下线；目前公示专区页面返回系统提示，需等待官网恢复该栏目。",
  "example": "/buaa/jiaowu/02",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jiaowu.ts",
  "maintainers": [
    "OverflowCat"
  ],
  "name": "教务部",
  "parameters": {
    "cddm": "栏目代码：02（通知公告，默认）、03（新闻快讯）、0203（公示专区）"
  },
  "path": "/jiaowu/:cddm?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "jiaowu.buaa.edu.cn"
}
```
