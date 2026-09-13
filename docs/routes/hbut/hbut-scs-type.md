# 湖北工业大学 - 计算机科学与人工智能学院

## Coverage
`index-only`

## Route
- Namespace: `hbut`
- Namespace Name: `湖北工业大学`
- Route Path: `/hbut/scs/:type`
- Route Name: `计算机科学与人工智能学院`
- Example: `/hbut/scs/xwdt`
- URL: `www.hbut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `LandonLi`
- Source Location: `scs.ts`
- Source Module: `_None_`

## Description
| 新闻动态 | 通知公告 | 教学信息 | 科研动态 | 党建活动 |
| -------- | -------- | -------- | -------- | -------- |
| xwdt     | tzgg     | jxxx     | kydt     | djhd     |

::: warning
scs.hbut.edu.cn 证书链不全，自建 RSSHub 可设置环境变量 NODE\_TLS\_REJECT\_UNAUTHORIZED = 0
:::

## Parameters
- `type`: 分类


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `title`: `新闻动态`
- `source`:
  - `scs.hbut.edu.cn/index/xwdt.htm`
- `target`: `/scs/xwdt`
### Rule 2
- `title`: `通知公告`
- `source`:
  - `scs.hbut.edu.cn/index/tzgg.htm`
- `target`: `/scs/tzgg`
### Rule 3
- `title`: `教学信息`
- `source`:
  - `scs.hbut.edu.cn/jxxx/jxxx.htm`
- `target`: `/scs/jxxx`
### Rule 4
- `title`: `科研动态`
- `source`:
  - `scs.hbut.edu.cn/kxyj/kydt.htm`
- `target`: `/scs/kydt`
### Rule 5
- `title`: `党建活动`
- `source`:
  - `scs.hbut.edu.cn/djhd/djhd.htm`
- `target`: `/scs/djhd`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻动态 | 通知公告 | 教学信息 | 科研动态 | 党建活动 |\n| -------- | -------- | -------- | -------- | -------- |\n| xwdt     | tzgg     | jxxx     | kydt     | djhd     |\n\n::: warning\nscs.hbut.edu.cn 证书链不全，自建 RSSHub 可设置环境变量 NODE\\_TLS\\_REJECT\\_UNAUTHORIZED = 0\n:::",
  "example": "/hbut/scs/xwdt",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "scs.ts",
  "maintainers": [
    "LandonLi"
  ],
  "name": "计算机科学与人工智能学院",
  "parameters": {
    "type": "分类"
  },
  "path": "/scs/:type",
  "radar": [
    {
      "source": [
        "scs.hbut.edu.cn/index/xwdt.htm"
      ],
      "target": "/scs/xwdt",
      "title": "新闻动态"
    },
    {
      "source": [
        "scs.hbut.edu.cn/index/tzgg.htm"
      ],
      "target": "/scs/tzgg",
      "title": "通知公告"
    },
    {
      "source": [
        "scs.hbut.edu.cn/jxxx/jxxx.htm"
      ],
      "target": "/scs/jxxx",
      "title": "教学信息"
    },
    {
      "source": [
        "scs.hbut.edu.cn/kxyj/kydt.htm"
      ],
      "target": "/scs/kydt",
      "title": "科研动态"
    },
    {
      "source": [
        "scs.hbut.edu.cn/djhd/djhd.htm"
      ],
      "target": "/scs/djhd",
      "title": "党建活动"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
