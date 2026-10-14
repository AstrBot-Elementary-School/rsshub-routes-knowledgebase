# 北京市科学技术协会 - 通用

## Coverage
`index-only`

## Route
- Namespace: `bast`
- Namespace Name: `北京市科学技术协会`
- Route Path: `/bast/:path{.+}?`
- Route Name: `通用`
- Example: `/bast/col/col31266`
- URL: `bast.net.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
路径处填写对应页面 URL 中 `https://www.bast.net.cn/` 后的字段。下面是两个例子。

若订阅 [通知公告](https://www.bast.net.cn/sy/tzgg/) 则将对应页面 URL <https://www.bast.net.cn/sy/tzgg/> 中 `https://www.bast.net.cn/` 后的字段 `sy/tzgg` 作为路径填入。此时路由为 [`/bast/sy/tzgg`](https://rsshub.app/bast/sy/tzgg)

若订阅 [学术动态](https://www.bast.net.cn/xxjl/xsdt/) 则将对应页面 URL <https://www.bast.net.cn/xxjl/xsdt/> 中 `https://www.bast.net.cn/` 后的字段 `xxjl/xsdt` 作为路径填入。此时路由为 [`/bast/xxjl/xsdt`](https://rsshub.app/bast/xxjl/xsdt)

旧栏目 `31266`、`32942`（通知公告）和 `31530`（学术动态）以及 `col/colXXXXX` 格式继续兼容。其他栏目请使用当前网站路径。

## Parameters
- `path`: 路径，默认为通知公告


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "路径处填写对应页面 URL 中 `https://www.bast.net.cn/` 后的字段。下面是两个例子。\n\n若订阅 [通知公告](https://www.bast.net.cn/sy/tzgg/) 则将对应页面 URL <https://www.bast.net.cn/sy/tzgg/> 中 `https://www.bast.net.cn/` 后的字段 `sy/tzgg` 作为路径填入。此时路由为 [`/bast/sy/tzgg`](https://rsshub.app/bast/sy/tzgg)\n\n若订阅 [学术动态](https://www.bast.net.cn/xxjl/xsdt/) 则将对应页面 URL <https://www.bast.net.cn/xxjl/xsdt/> 中 `https://www.bast.net.cn/` 后的字段 `xxjl/xsdt` 作为路径填入。此时路由为 [`/bast/xxjl/xsdt`](https://rsshub.app/bast/xxjl/xsdt)\n\n旧栏目 `31266`、`32942`（通知公告）和 `31530`（学术动态）以及 `col/colXXXXX` 格式继续兼容。其他栏目请使用当前网站路径。",
  "example": "/bast/col/col31266",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "通用",
  "parameters": {
    "path": "路径，默认为通知公告"
  },
  "path": "/:path{.+}?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
