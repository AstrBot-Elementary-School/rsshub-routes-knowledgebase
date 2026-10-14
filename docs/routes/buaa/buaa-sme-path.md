# 北京航空航天大学 - 集成电路科学与工程学院

## Coverage
`index-only`

## Route
- Namespace: `buaa`
- Namespace Name: `北京航空航天大学`
- Route Path: `/buaa/sme/:path{.+}?`
- Route Name: `集成电路科学与工程学院`
- Example: `/buaa/sme/tzgg`
- URL: `ic.buaa.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `MeanZhang`
- Source Location: `sme.ts`
- Source Module: `_None_`

## Description
版块路径（`path`）填写官网 URL 中 `https://ic.buaa.edu.cn/` 和 `.htm` 之间的字段。

示例：

1. [通知公告](https://ic.buaa.edu.cn/tzgg.htm)：`/buaa/sme/tzgg`；
2. [就业信息](https://ic.buaa.edu.cn/zsjy/jyxx.htm)：`/buaa/sme/zsjy/jyxx`。

请使用栏目列表页；学院介绍等单篇页面不提供文章列表。

## Parameters
- `path`: 版块路径，默认为 `tzgg`（通知公告）


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
  "description": "版块路径（`path`）填写官网 URL 中 `https://ic.buaa.edu.cn/` 和 `.htm` 之间的字段。\n\n示例：\n\n1. [通知公告](https://ic.buaa.edu.cn/tzgg.htm)：`/buaa/sme/tzgg`；\n2. [就业信息](https://ic.buaa.edu.cn/zsjy/jyxx.htm)：`/buaa/sme/zsjy/jyxx`。\n\n请使用栏目列表页；学院介绍等单篇页面不提供文章列表。",
  "example": "/buaa/sme/tzgg",
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
  "location": "sme.ts",
  "maintainers": [
    "MeanZhang"
  ],
  "name": "集成电路科学与工程学院",
  "parameters": {
    "path": "版块路径，默认为 `tzgg`（通知公告）"
  },
  "path": "/sme/:path{.+}?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "ic.buaa.edu.cn"
}
```
