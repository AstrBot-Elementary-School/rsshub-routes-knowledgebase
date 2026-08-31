# Aqara - 分类、标签

## Coverage
`index-only`

## Route
- Namespace: `aqara`
- Namespace Name: `Aqara`
- Route Path: `/aqara/:path{.+}?`
- Route Name: `分类、标签`
- Example: `/aqara/en/category/press-release`
- URL: `aqara.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk`
- Source Location: `post.tsx`
- Source Module: `_None_`

## Description
路径处填写对应页面 URL 中 `https://aqara.com/` 后的字段，形如 `:region/category/:id` 或 `:region/tag/:id`。

| 参数   | 说明                                                     |
| ------ | -------------------------------------------------------- |
| region | 地区 id，可在对应分类页 URL 中找到，默认为 en，即 Global |
| id     | 分类 id 或标签 id，可在对应分类页或标签页 URL 中找到     |

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
    "other"
  ],
  "description": "路径处填写对应页面 URL 中 `https://aqara.com/` 后的字段，形如 `:region/category/:id` 或 `:region/tag/:id`。\n\n| 参数   | 说明                                                     |\n| ------ | -------------------------------------------------------- |\n| region | 地区 id，可在对应分类页 URL 中找到，默认为 en，即 Global |\n| id     | 分类 id 或标签 id，可在对应分类页或标签页 URL 中找到     |",
  "example": "/aqara/en/category/press-release",
  "heat": 0,
  "location": "post.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类、标签",
  "parameters": {
    "path": "路径，默认为首页"
  },
  "path": "/:path{.+}?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
