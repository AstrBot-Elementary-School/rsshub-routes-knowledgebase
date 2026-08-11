# 清华大学 - 图书馆通知公告

## Coverage
`index-only`

## Route
- Namespace: `tsinghua`
- Namespace Name: `清华大学`
- Route Path: `/tsinghua/lib/tzgg/:category?`
- Route Name: `图书馆通知公告`
- Example: `/tsinghua/lib/tzgg/qtkx`
- URL: `lib.tsinghua.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `linsenwang, Aquarius-Situla`
- Source Location: `lib/tzgg.ts`
- Source Module: `_None_`

## Description
| 全部 | 开馆通知 | 施工维修 | 服务通知 | 违规通报 | 清图快讯 | 馆际通知 |
| ---- | -------- | -------- | -------- | -------- | -------- | -------- |
| 留空 | kgtz     | sgwx     | fwtz     | wgtb     | qtkx     | gjtz     |

## Parameters
- `category`: 分类，可在对应分类页 URL 中找到，留空则获取全局通知公告


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
  - `lib.tsinghua.edu.cn/tzgg/:category`
  - `lib.tsinghua.edu.cn/tzgg.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 全部 | 开馆通知 | 施工维修 | 服务通知 | 违规通报 | 清图快讯 | 馆际通知 |\n| ---- | -------- | -------- | -------- | -------- | -------- | -------- |\n| 留空 | kgtz     | sgwx     | fwtz     | wgtb     | qtkx     | gjtz     |",
  "example": "/tsinghua/lib/tzgg/qtkx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "lib/tzgg.ts",
  "maintainers": [
    "linsenwang",
    "Aquarius-Situla"
  ],
  "name": "图书馆通知公告",
  "parameters": {
    "category": "分类，可在对应分类页 URL 中找到，留空则获取全局通知公告"
  },
  "path": "/lib/tzgg/:category?",
  "radar": [
    {
      "source": [
        "lib.tsinghua.edu.cn/tzgg/:category",
        "lib.tsinghua.edu.cn/tzgg.htm"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "lib.tsinghua.edu.cn"
}
```
