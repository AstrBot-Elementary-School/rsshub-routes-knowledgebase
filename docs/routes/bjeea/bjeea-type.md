# 北京教育考试院 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `bjeea`
- Namespace Name: `北京教育考试院`
- Route Path: `/bjeea/:type`
- Route Name: `通知公告`
- Example: `/bjeea/bjeeagg`
- URL: `www.bjeea.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `gavin-k`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 招考政策 | 自考快递 |
| :------: | :------: | :------: |
|  bjeeagg |   zkzc   |   zkkd   |

## Parameters
- `type`: 分类名


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.bjeea.com/bjeeagg`
- `target`: `/bjeeagg`
### Rule 2
- `source`:
  - `www.bjeea.com/zkzc`
- `target`: `/zkzc`
### Rule 3
- `source`:
  - `www.bjeea.com/zkkd`
- `target`: `/zkkd`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 通知公告 | 招考政策 | 自考快递 |\n| :------: | :------: | :------: |\n|  bjeeagg |   zkzc   |   zkkd   |",
  "example": "/bjeea/bjeeagg",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "gavin-k"
  ],
  "name": "通知公告",
  "parameters": {
    "type": "分类名"
  },
  "path": "/:type",
  "radar": [
    {
      "source": [
        "www.bjeea.com/bjeeagg"
      ],
      "target": "/bjeeagg"
    },
    {
      "source": [
        "www.bjeea.com/zkzc"
      ],
      "target": "/zkzc"
    },
    {
      "source": [
        "www.bjeea.com/zkkd"
      ],
      "target": "/zkkd"
    }
  ],
  "topFeeds": []
}
```
