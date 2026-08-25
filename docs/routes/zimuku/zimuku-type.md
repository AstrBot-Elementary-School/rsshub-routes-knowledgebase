# 字幕库 - 字幕列表

## Coverage
`index-only`

## Route
- Namespace: `zimuku`
- Namespace Name: `字幕库`
- Route Path: `/zimuku/:type?`
- Route Name: `字幕列表`
- Example: `/zimuku/mv`
- URL: `zimuku.org`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `sanmmm`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
类型

| 最新电影 | 最新美剧 |
| -------- | -------- |
| mv       | tv       |

## Parameters
- `type`: 类型, 默认为 `mv` 电影


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "类型\n\n| 最新电影 | 最新美剧 |\n| -------- | -------- |\n| mv       | tv       |",
  "example": "/zimuku/mv",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "sanmmm"
  ],
  "name": "字幕列表",
  "parameters": {
    "type": "类型, 默认为 `mv` 电影"
  },
  "path": "/:type?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
