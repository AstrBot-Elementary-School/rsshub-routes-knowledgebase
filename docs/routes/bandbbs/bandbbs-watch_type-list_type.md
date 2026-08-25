# 米坛社区 - 表盘更新

## Coverage
`index-only`

## Route
- Namespace: `bandbbs`
- Namespace Name: `米坛社区`
- Route Path: `/bandbbs/:watch_type?/:list_type?`
- Route Name: `表盘更新`
- Example: `/bandbbs/mi4`
- URL: `bandbbs.cn`
- Language: `_None_`
- Categories: `other`
- Maintainers: `hoilc`
- Source Location: `update.ts`
- Source Module: `_None_`

## Description
表盘型号

| 小米手环 4 | 华米 GTR 47mm | 华米智能手表青春版 |
| ---------- | ------------- | ------------------ |
| mi4        | gtr47         | gvlite             |

列表类型

| 最新上传 | 最多下载 | 编辑推荐   |
| -------- | -------- | ---------- |
| 0        | 1        | recommends |

## Parameters
- `watch_type`: 手环型号, 默认为 `小米手环4`
- `list_type`: 列表类型, 默认为 `最新上传`


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
  "description": "表盘型号\n\n| 小米手环 4 | 华米 GTR 47mm | 华米智能手表青春版 |\n| ---------- | ------------- | ------------------ |\n| mi4        | gtr47         | gvlite             |\n\n列表类型\n\n| 最新上传 | 最多下载 | 编辑推荐   |\n| -------- | -------- | ---------- |\n| 0        | 1        | recommends |",
  "example": "/bandbbs/mi4",
  "heat": 0,
  "location": "update.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "表盘更新",
  "parameters": {
    "list_type": "列表类型, 默认为 `最新上传`",
    "watch_type": "手环型号, 默认为 `小米手环4`"
  },
  "path": "/:watch_type?/:list_type?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
