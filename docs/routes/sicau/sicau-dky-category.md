# 四川农业大学 - 动物科技学院

## Coverage
`index-only`

## Route
- Namespace: `sicau`
- Namespace Name: `四川农业大学`
- Route Path: `/sicau/dky/:category?`
- Route Name: `动物科技学院`
- Example: `/sicau/dky/tzgg`
- URL: `dky.sicau.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `dky.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 学院动态 | 教学管理 | 动科大讲堂 | 就业信息 |
| -------- | -------- | -------- | ---------- | -------- |
| tzgg     | xydt     | jxgl     | dkdjt      | zpxx     |

## Parameters
- `category`: 分类，见下表，默认为通知公告


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `dky.sicau.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 学院动态 | 教学管理 | 动科大讲堂 | 就业信息 |\n| -------- | -------- | -------- | ---------- | -------- |\n| tzgg     | xydt     | jxgl     | dkdjt      | zpxx     |",
  "example": "/sicau/dky/tzgg",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "dky.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "动物科技学院",
  "parameters": {
    "category": "分类，见下表，默认为通知公告"
  },
  "path": "/dky/:category?",
  "radar": [
    {
      "source": [
        "dky.sicau.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "dky.sicau.edu.cn/"
}
```
