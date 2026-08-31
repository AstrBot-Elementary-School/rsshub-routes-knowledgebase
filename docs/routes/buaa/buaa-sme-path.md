# 北京航空航天大学 - 集成电路科学与工程学院

## Coverage
`index-only`

## Route
- Namespace: `buaa`
- Namespace Name: `北京航空航天大学`
- Route Path: `/buaa/sme/:path{.+}?`
- Route Name: `集成电路科学与工程学院`
- Example: `/buaa/sme/tzgg`
- URL: `www.sme.buaa.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `MeanZhang`
- Source Location: `sme.ts`
- Source Module: `_None_`

## Description
::: tip

版块路径（`path`）应填写板块 URL 中 `http://www.sme.buaa.edu.cn/` 和 `.htm` 之间的字段。

示例：

1. [通知公告](http://www.sme.buaa.edu.cn/tzgg.htm) 页面的 URL 为 `http://www.sme.buaa.edu.cn/tzgg.htm`，对应的路径参数为 `tzgg`，完整路由为 `/buaa/sme/tzgg`；
2. [就业信息](http://www.sme.buaa.edu.cn/zsjy/jyxx.htm) 页面的 URL 为 `http://www.sme.buaa.edu.cn/zsjy/jyxx.htm`，对应的路径参数为 `zsjy/jyxx`，完整路由为 `/buaa/sme/zsjy/jyxx`。

:::

::: warning

部分页面（如[学院介绍](http://www.sme.buaa.edu.cn/xygk/xyjs.htm)、[微纳中心](http://www.sme.buaa.edu.cn/wnzx.htm)、[院学生会](http://www.sme.buaa.edu.cn/xsgz/yxsh.htm)）存在无内容、内容跳转至外站等情况，因此可能出现解析失败的现象。

:::

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
  "description": "::: tip\n\n版块路径（`path`）应填写板块 URL 中 `http://www.sme.buaa.edu.cn/` 和 `.htm` 之间的字段。\n\n示例：\n\n1. [通知公告](http://www.sme.buaa.edu.cn/tzgg.htm) 页面的 URL 为 `http://www.sme.buaa.edu.cn/tzgg.htm`，对应的路径参数为 `tzgg`，完整路由为 `/buaa/sme/tzgg`；\n2. [就业信息](http://www.sme.buaa.edu.cn/zsjy/jyxx.htm) 页面的 URL 为 `http://www.sme.buaa.edu.cn/zsjy/jyxx.htm`，对应的路径参数为 `zsjy/jyxx`，完整路由为 `/buaa/sme/zsjy/jyxx`。\n\n:::\n\n::: warning\n\n部分页面（如[学院介绍](http://www.sme.buaa.edu.cn/xygk/xyjs.htm)、[微纳中心](http://www.sme.buaa.edu.cn/wnzx.htm)、[院学生会](http://www.sme.buaa.edu.cn/xsgz/yxsh.htm)）存在无内容、内容跳转至外站等情况，因此可能出现解析失败的现象。\n\n:::",
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
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.sme.buaa.edu.cn"
}
```
