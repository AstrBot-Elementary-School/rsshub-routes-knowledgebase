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
默认订阅[首页](https://cbaigui.com)的妖怪词条、杂谈和站点公告。网站改版后，原分类和标签路径仍可作为路由参数，名称对应[妖怪列表](https://cbaigui.com/monster)中的属性或书籍筛选项。

| 筛选项   | 路径参数                           |
| -------- | ---------------------------------- |
| 妖怪词条 | monster                            |
| 杂谈     | essays                             |
| 站点公告 | notice                             |
| 妖       | post-tag / 妖                      |
| 埃及     | post-category / 世界 / 非洲 / 埃及 |
| 白泽图   | post-category / 词条 / 白泽图      |

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
  "description": "默认订阅[首页](https://cbaigui.com)的妖怪词条、杂谈和站点公告。网站改版后，原分类和标签路径仍可作为路由参数，名称对应[妖怪列表](https://cbaigui.com/monster)中的属性或书籍筛选项。\n\n| 筛选项   | 路径参数                           |\n| -------- | ---------------------------------- |\n| 妖怪词条 | monster                            |\n| 杂谈     | essays                             |\n| 站点公告 | notice                             |\n| 妖       | post-tag / 妖                      |\n| 埃及     | post-category / 世界 / 非洲 / 埃及 |\n| 白泽图   | post-category / 词条 / 白泽图      |",
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
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
