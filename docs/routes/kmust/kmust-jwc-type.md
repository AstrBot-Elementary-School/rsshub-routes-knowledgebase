# 昆明理工大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `kmust`
- Namespace Name: `昆明理工大学`
- Route Path: `/kmust/jwc/:type?`
- Route Name: `教务处`
- Example: `/kmust/jwc/notify`
- URL: `www.kmust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `geekrainy`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 教务通知 | 教务新闻 |
| -------- | -------- |
| notify   | news     |

## Parameters
- `type`: 默认为 `notify`


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
  "description": "| 教务通知 | 教务新闻 |\n| -------- | -------- |\n| notify   | news     |",
  "example": "/kmust/jwc/notify",
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "geekrainy"
  ],
  "name": "教务处",
  "parameters": {
    "type": "默认为 `notify`"
  },
  "path": "/jwc/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
