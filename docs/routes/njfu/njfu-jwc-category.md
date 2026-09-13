# 南京林业大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `njfu`
- Namespace Name: `南京林业大学`
- Route Path: `/njfu/jwc/:category?`
- Route Name: `教务处`
- Example: `/njfu/jwc/tzgg`
- URL: `njfu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `kiusiudeng`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 校级发文 | 通知公告 | 上级发文 | 下载专区 |
| -------- | -------- | -------- | -------- |
| xjfw     | tzgg     | sjfw     | xzzq     |

## Parameters
- `category`: 省略则默认为 tzgg


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
  "description": "| 校级发文 | 通知公告 | 上级发文 | 下载专区 |\n| -------- | -------- | -------- | -------- |\n| xjfw     | tzgg     | sjfw     | xzzq     |",
  "example": "/njfu/jwc/tzgg",
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "kiusiudeng"
  ],
  "name": "教务处",
  "parameters": {
    "category": "省略则默认为 tzgg"
  },
  "path": "/jwc/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
