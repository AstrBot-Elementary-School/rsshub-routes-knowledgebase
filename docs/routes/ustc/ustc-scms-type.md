# 中国科学技术大学 - 化学与材料科学学院

## Coverage
`index-only`

## Route
- Namespace: `ustc`
- Namespace Name: `中国科学技术大学`
- Route Path: `/ustc/scms/:type?`
- Route Name: `化学与材料科学学院`
- Example: `/ustc/scms/tzgg`
- URL: `scms.ustc.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `boxie123`
- Source Location: `scms.ts`
- Source Module: `_None_`

## Description
| 院内新闻 | 通知公告 | 科研动态 | 学术活动 | 其他      |
| -------- | -------- | -------- | -------- | --------- |
| ynxw     | tzgg     | kydt     | xshd     | 自定义 id |

## Parameters
- `type`: 分类，见下表，默认为通知公告


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
  - `scms.ustc.edu.cn/:type/list.htm`
- `target`: `/scms/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 院内新闻 | 通知公告 | 科研动态 | 学术活动 | 其他      |\n| -------- | -------- | -------- | -------- | --------- |\n| ynxw     | tzgg     | kydt     | xshd     | 自定义 id |",
  "example": "/ustc/scms/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "scms.ts",
  "maintainers": [
    "boxie123"
  ],
  "name": "化学与材料科学学院",
  "parameters": {
    "type": "分类，见下表，默认为通知公告"
  },
  "path": "/scms/:type?",
  "radar": [
    {
      "source": [
        "scms.ustc.edu.cn/:type/list.htm"
      ],
      "target": "/scms/:type"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "scms.ustc.edu.cn/"
}
```
