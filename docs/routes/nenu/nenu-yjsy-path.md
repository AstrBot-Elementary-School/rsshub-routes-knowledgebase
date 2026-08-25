# 东北师范大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `nenu`
- Namespace Name: `东北师范大学`
- Route Path: `/nenu/yjsy/:path{.+}?`
- Route Name: `研究生院`
- Example: `/nenu/yjsy`
- URL: `sohac.nenu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `yjsy.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [通知公告](https://yjsy.nenu.edu.cn/tzgg.htm)，网址为 `https://yjsy.nenu.edu.cn/tzgg.htm`。截取 `https://yjsy.nenu.edu.cn/` 到末尾 `.htm` 的部分 `tzgg` 作为参数，此时路由为 [`/nenu/yjsy/tzgg`](https://rsshub.app/nenu/yjsy/tzgg)。

若订阅 [校内新闻](https://yjsy.nenu.edu.cn/xwdt/xnxw.htm)，网址为 `https://yjsy.nenu.edu.cn/xwdt/xnxw.htm`。截取 `https://yjsy.nenu.edu.cn/` 到末尾 `.htm` 的部分 `xwdt/xnxw` 作为参数，此时路由为 [`/nenu/yjsy/xwdt/xnxw`](https://rsshub.app/nenu/yjsy/xwdt/xnxw)。
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
  "description": "::: tip\n若订阅 [通知公告](https://yjsy.nenu.edu.cn/tzgg.htm)，网址为 `https://yjsy.nenu.edu.cn/tzgg.htm`。截取 `https://yjsy.nenu.edu.cn/` 到末尾 `.htm` 的部分 `tzgg` 作为参数，此时路由为 [`/nenu/yjsy/tzgg`](https://rsshub.app/nenu/yjsy/tzgg)。\n\n若订阅 [校内新闻](https://yjsy.nenu.edu.cn/xwdt/xnxw.htm)，网址为 `https://yjsy.nenu.edu.cn/xwdt/xnxw.htm`。截取 `https://yjsy.nenu.edu.cn/` 到末尾 `.htm` 的部分 `xwdt/xnxw` 作为参数，此时路由为 [`/nenu/yjsy/xwdt/xnxw`](https://rsshub.app/nenu/yjsy/xwdt/xnxw)。\n:::",
  "example": "/nenu/yjsy",
  "heat": 0,
  "location": "yjsy.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "研究生院",
  "parameters": {
    "path": "路径，默认为通知公告"
  },
  "path": "/yjsy/:path{.+}?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
