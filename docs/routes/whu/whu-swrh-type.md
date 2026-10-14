# 武汉大学 - 水利水电学院公告

## Coverage
`index-only`

## Route
- Namespace: `whu`
- Namespace Name: `武汉大学`
- Route Path: `/whu/swrh/:type`
- Route Name: `水利水电学院公告`
- Example: `/whu/swrh/2`
- URL: `cs.whu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `FanofZY`
- Source Location: `swrh.ts`
- Source Module: `_None_`

## Description
| 公告类型 | 学院新闻 | 学术科研 | 通知公告 |
| -------- | -------- | -------- | -------- |
| 参数     | 0        | 1        | 2        |

## Parameters
- `type`: 公告类型，详见表格


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `swrh.whu.edu.cn/index/xyxw.htm`
  - `swrh.whu.edu.cn/0`
- `target`: `/swrh/0`
### Rule 2
- `source`:
  - `swrh.whu.edu.cn/index/xsky.htm`
  - `swrh.whu.edu.cn/1`
- `target`: `/swrh/1`
### Rule 3
- `source`:
  - `swrh.whu.edu.cn/xxgk/tzgg.htm`
  - `swrh.whu.edu.cn/2`
- `target`: `/swrh/2`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 公告类型 | 学院新闻 | 学术科研 | 通知公告 |\n| -------- | -------- | -------- | -------- |\n| 参数     | 0        | 1        | 2        |",
  "example": "/whu/swrh/2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "swrh.ts",
  "maintainers": [
    "FanofZY"
  ],
  "name": "水利水电学院公告",
  "parameters": {
    "type": "公告类型，详见表格"
  },
  "path": "/swrh/:type",
  "radar": [
    {
      "source": [
        "swrh.whu.edu.cn/index/xyxw.htm",
        "swrh.whu.edu.cn/0"
      ],
      "target": "/swrh/0"
    },
    {
      "source": [
        "swrh.whu.edu.cn/index/xsky.htm",
        "swrh.whu.edu.cn/1"
      ],
      "target": "/swrh/1"
    },
    {
      "source": [
        "swrh.whu.edu.cn/xxgk/tzgg.htm",
        "swrh.whu.edu.cn/2"
      ],
      "target": "/swrh/2"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
