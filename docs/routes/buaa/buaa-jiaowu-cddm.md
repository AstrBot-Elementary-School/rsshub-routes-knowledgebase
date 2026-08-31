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
::: tip

菜单代码（`cddm`）应填写链接中调用的 newsList 接口的参数，可以是 2 位或者 4 位数字。若为 2 位，则为 `fcd`（父菜单）；若为 4 位，则为 `cddm`（菜单代码），其中前 2 位为 `fcd`。
示例：

1. 新闻快讯页面的链接中 `onclick="javascript:onNewsList('03');return false;"`，对应的路径参数为 `03`，完整路由为 `/buaa/jiaowu/03`；
2. 通知公告 > 公示专区页面的链接中 `onclick="javascript:onNewsList2('0203','2');return false;"`，对应的路径参数为 `0203`，完整路由为 `/buaa/jiaowu/0203`。

:::

## Parameters
- `cddm`: 菜单代码，可以是 2 位或者 4 位，默认为 `02`（通知公告）


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
  "description": "::: tip\n\n菜单代码（`cddm`）应填写链接中调用的 newsList 接口的参数，可以是 2 位或者 4 位数字。若为 2 位，则为 `fcd`（父菜单）；若为 4 位，则为 `cddm`（菜单代码），其中前 2 位为 `fcd`。\n示例：\n\n1. 新闻快讯页面的链接中 `onclick=\"javascript:onNewsList('03');return false;\"`，对应的路径参数为 `03`，完整路由为 `/buaa/jiaowu/03`；\n2. 通知公告 > 公示专区页面的链接中 `onclick=\"javascript:onNewsList2('0203','2');return false;\"`，对应的路径参数为 `0203`，完整路由为 `/buaa/jiaowu/0203`。\n\n:::",
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
    "cddm": "菜单代码，可以是 2 位或者 4 位，默认为 `02`（通知公告）"
  },
  "path": "/jiaowu/:cddm?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "jiaowu.buaa.edu.cn"
}
```
