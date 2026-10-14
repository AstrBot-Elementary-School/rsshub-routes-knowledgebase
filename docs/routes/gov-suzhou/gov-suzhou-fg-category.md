# 苏州市人民政府 - 发展和改革委员会

## Coverage
`index-only`

## Route
- Namespace: `gov/suzhou`
- Namespace Name: `苏州市人民政府`
- Route Path: `/gov/suzhou/fg/:category{.+}?`
- Route Name: `发展和改革委员会`
- Example: `/gov/suzhou/fg/szfgw/ggl/nav_list`
- URL: `www.suzhou.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `fg.ts`
- Source Module: `_None_`

## Description
| 通知公告            | 发改要闻             |
| ------------------- | -------------------- |
| szfgw/ggl/nav\_list | szfgw/gzdt/nav\_list |

## Parameters
- `category`: 分类，见下表，默认为通知公告


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `fg.suzhou.gov.cn/szfgw/ggl/nav_list.shtml`
- `target`: `/fg/szfgw/ggl/nav_list`
### Rule 2
- `source`:
  - `fg.suzhou.gov.cn/szfgw/gzdt/nav_list.shtml`
- `target`: `/fg/szfgw/gzdt/nav_list`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 通知公告            | 发改要闻             |\n| ------------------- | -------------------- |\n| szfgw/ggl/nav\\_list | szfgw/gzdt/nav\\_list |",
  "example": "/gov/suzhou/fg/szfgw/ggl/nav_list",
  "heat": 0,
  "location": "fg.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "发展和改革委员会",
  "parameters": {
    "category": "分类，见下表，默认为通知公告"
  },
  "path": "/fg/:category{.+}?",
  "radar": [
    {
      "source": [
        "fg.suzhou.gov.cn/szfgw/ggl/nav_list.shtml"
      ],
      "target": "/fg/szfgw/ggl/nav_list"
    },
    {
      "source": [
        "fg.suzhou.gov.cn/szfgw/gzdt/nav_list.shtml"
      ],
      "target": "/fg/szfgw/gzdt/nav_list"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
