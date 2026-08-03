# 东北师范大学 - 历史文化学院

## Coverage
`index-only`

## Route
- Namespace: `nenu`
- Namespace Name: `东北师范大学`
- Route Path: `/nenu/sohac/:path{.+}?`
- Route Name: `历史文化学院`
- Example: `/nenu/sohac`
- URL: `sohac.nenu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `sohac.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [通知公告](https://sohac.nenu.edu.cn/index/tzgg.htm)，网址为 `https://sohac.nenu.edu.cn/index/tzgg.htm`。截取 `https://sohac.nenu.edu.cn/` 到末尾 `.htm` 的部分 `index/tzgg` 作为参数，此时路由为 [`/nenu/sohac/index/tzgg`](https://rsshub.app/nenu/sohac/index/tzgg)。

若订阅 [学院信息](https://sohac.nenu.edu.cn/index/xyxx.htm)，网址为 `https://sohac.nenu.edu.cn/index/xyxx.htm`。截取 `https://sohac.nenu.edu.cn/` 到末尾 `.htm` 的部分 `index/xyxx` 作为参数，此时路由为 [`/nenu/sohac/index/xyxx`](https://rsshub.app/nenu/sohac/index/xyxx)。
:::

## Parameters
- `path`: 路径，默认为通知公告


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: tip\n若订阅 [通知公告](https://sohac.nenu.edu.cn/index/tzgg.htm)，网址为 `https://sohac.nenu.edu.cn/index/tzgg.htm`。截取 `https://sohac.nenu.edu.cn/` 到末尾 `.htm` 的部分 `index/tzgg` 作为参数，此时路由为 [`/nenu/sohac/index/tzgg`](https://rsshub.app/nenu/sohac/index/tzgg)。\n\n若订阅 [学院信息](https://sohac.nenu.edu.cn/index/xyxx.htm)，网址为 `https://sohac.nenu.edu.cn/index/xyxx.htm`。截取 `https://sohac.nenu.edu.cn/` 到末尾 `.htm` 的部分 `index/xyxx` 作为参数，此时路由为 [`/nenu/sohac/index/xyxx`](https://rsshub.app/nenu/sohac/index/xyxx)。\n:::",
  "example": "/nenu/sohac",
  "heat": 0,
  "location": "sohac.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "历史文化学院",
  "parameters": {
    "path": "路径，默认为通知公告"
  },
  "path": "/sohac/:path{.+}?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
