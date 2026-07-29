# 吉首大学 - 创新中心

## Coverage
`index-only`

## Route
- Namespace: `jsu`
- Namespace Name: `吉首大学`
- Route Path: `/jsu/cxzx/:types?`
- Route Name: `创新中心`
- Example: `/jsu/cxzx/xkjs`
- URL: `jsu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `wenjia03`
- Source Location: `cxzx.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 学科竞赛公告 | 创新项目公告 | 竞赛新闻 | 竞赛通知 |
| -------- | ------------ | ------------ | -------- | -------- |
| tzgg     | xkjs         | cxtz         | jsxw     | jstz     |

## Parameters
- `types`: 通知分类 默认为`xkjs`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 学科竞赛公告 | 创新项目公告 | 竞赛新闻 | 竞赛通知 |\n| -------- | ------------ | ------------ | -------- | -------- |\n| tzgg     | xkjs         | cxtz         | jsxw     | jstz     |",
  "example": "/jsu/cxzx/xkjs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "cxzx.ts",
  "maintainers": [
    "wenjia03"
  ],
  "name": "创新中心",
  "parameters": {
    "types": "通知分类 默认为`xkjs`"
  },
  "path": "/cxzx/:types?",
  "topFeeds": []
}
```
