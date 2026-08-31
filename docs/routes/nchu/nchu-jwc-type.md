# 南昌航空大学 - 教务处公告与新闻

## Coverage
`index-only`

## Route
- Namespace: `nchu`
- Namespace Name: `南昌航空大学`
- Route Path: `/nchu/jwc/:type?`
- Route Name: `教务处公告与新闻`
- Example: `/nchu/jwc/notice`
- URL: `nchu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Sg4Dylan`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 教务公告 | 教务新闻 |
| -------- | -------- |
| notice   | news     |

## Parameters
- `type`: 默认为 `notice`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `jwc.nchu.edu.cn/xwzx/gg`
- `target`: `/jwc/notice`
### Rule 2
- `source`:
  - `jwc.nchu.edu.cn/xwzx/xw`
- `target`: `/jwc/news`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 教务公告 | 教务新闻 |\n| -------- | -------- |\n| notice   | news     |",
  "example": "/nchu/jwc/notice",
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "Sg4Dylan"
  ],
  "name": "教务处公告与新闻",
  "parameters": {
    "type": "默认为 `notice`"
  },
  "path": "/jwc/:type?",
  "radar": [
    {
      "source": [
        "jwc.nchu.edu.cn/xwzx/gg"
      ],
      "target": "/jwc/notice"
    },
    {
      "source": [
        "jwc.nchu.edu.cn/xwzx/xw"
      ],
      "target": "/jwc/news"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
