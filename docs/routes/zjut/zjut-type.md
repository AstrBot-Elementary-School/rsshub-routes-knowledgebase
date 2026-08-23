# 浙江工业大学 - 浙江工业大学

## Coverage
`index-only`

## Route
- Namespace: `zjut`
- Namespace Name: `浙江工业大学`
- Route Path: `/zjut/:type?`
- Route Name: `浙江工业大学`
- Example: `/zjut/4528`
- URL: `www.zjut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `junbaor`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 学术探索 | 三创・人物 | 通知公告 | 美誉工大 | 智库工大 | 学术动态   |
| -------- | ---------- | -------- | -------- | -------- | ---------- |
| 4526     | 4527       | 4528     | 5389     | 5390     | xsdt\_4662 |

## Parameters
- `type`: 板块 id，默认为 4528，即通知公告


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.zjut.edu.cn/:type/list.htm`
- `target`: `/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学术探索 | 三创・人物 | 通知公告 | 美誉工大 | 智库工大 | 学术动态   |\n| -------- | ---------- | -------- | -------- | -------- | ---------- |\n| 4526     | 4527       | 4528     | 5389     | 5390     | xsdt\\_4662 |",
  "example": "/zjut/4528",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "junbaor"
  ],
  "name": "浙江工业大学",
  "parameters": {
    "type": "板块 id，默认为 4528，即通知公告"
  },
  "path": "/:type?",
  "radar": [
    {
      "source": [
        "www.zjut.edu.cn/:type/list.htm"
      ],
      "target": "/:type"
    }
  ],
  "topFeeds": [],
  "url": "www.zjut.edu.cn"
}
```
