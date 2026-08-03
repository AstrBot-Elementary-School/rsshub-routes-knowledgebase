# 纪妖 - 通用

## Coverage
`index-only`

## Route
- Namespace: `cbaigui`
- Namespace Name: `纪妖`
- Route Path: `/cbaigui/:path{.+}?`
- Route Name: `通用`
- Example: `/cbaigui`
- URL: `cbaigui.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
若订阅 [标签：妖](https://www.cbaigui.com/post-tag/妖)，网址为 `https://www.cbaigui.com/post-tag/妖`。截取 `https://www.cbaigui.com` 到末尾的部分 `/post-tag/妖` 作为参数，此时路由为 [`/cbaigui/post-tag/妖`](https://rsshub.app/cbaigui/post-tag/妖)。

若订阅 [分类：埃及](https://www.cbaigui.com/post-category/世界/非洲/埃及)，网址为 `https://www.cbaigui.com/post-category/世界/非洲/埃及`。截取 `https://www.cbaigui.com` 到末尾的部分 `/post-category/世界/非洲/埃及` 作为参数，此时路由为 [`/cbaigui/post-category/世界/非洲/埃及`](https://rsshub.app/cbaigui/post-category/世界/非洲/埃及)。

若订阅 [词条：白泽图](https://www.cbaigui.com/post-category/词条/白泽图)，网址为 `https://www.cbaigui.com/post-category/词条/白泽图`。截取 `https://www.cbaigui.com` 到末尾的部分 `/post-category/词条/白泽图` 作为参数，此时路由为 [`/cbaigui/post-category/词条/白泽图`](https://rsshub.app/cbaigui/post-category/词条/白泽图)。

## Parameters
- `path`: 路径，默认为首页


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "若订阅 [标签：妖](https://www.cbaigui.com/post-tag/妖)，网址为 `https://www.cbaigui.com/post-tag/妖`。截取 `https://www.cbaigui.com` 到末尾的部分 `/post-tag/妖` 作为参数，此时路由为 [`/cbaigui/post-tag/妖`](https://rsshub.app/cbaigui/post-tag/妖)。\n\n若订阅 [分类：埃及](https://www.cbaigui.com/post-category/世界/非洲/埃及)，网址为 `https://www.cbaigui.com/post-category/世界/非洲/埃及`。截取 `https://www.cbaigui.com` 到末尾的部分 `/post-category/世界/非洲/埃及` 作为参数，此时路由为 [`/cbaigui/post-category/世界/非洲/埃及`](https://rsshub.app/cbaigui/post-category/世界/非洲/埃及)。\n\n若订阅 [词条：白泽图](https://www.cbaigui.com/post-category/词条/白泽图)，网址为 `https://www.cbaigui.com/post-category/词条/白泽图`。截取 `https://www.cbaigui.com` 到末尾的部分 `/post-category/词条/白泽图` 作为参数，此时路由为 [`/cbaigui/post-category/词条/白泽图`](https://rsshub.app/cbaigui/post-category/词条/白泽图)。",
  "example": "/cbaigui",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "通用",
  "parameters": {
    "path": "路径，默认为首页"
  },
  "path": "/:path{.+}?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
