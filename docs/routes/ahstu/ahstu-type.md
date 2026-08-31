# 安徽科技工程大学 - 官网通知与新闻

## Coverage
`index-only`

## Route
- Namespace: `ahstu`
- Namespace Name: `安徽科技工程大学`
- Route Path: `/ahstu/:type?`
- Route Name: `官网通知与新闻`
- Example: `/ahstu/akyw`
- URL: `ahstu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `JizzCruiy`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 栏目     | type |
| -------- | ---- |
| 安科要闻 | akyw |
| 通知公告 | tzgg |
| 学术安科 | xsak |
| 校园动态 | xydt |
| 媒体聚焦 | mtak |
| 人物风采 | rwfc |
| 视觉校园 | sjxy |

## Parameters
- `type`: 栏目类型，见下表，默认为 `akyw`


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
  - `www.ahstu.edu.cn/index/:type.htm`
- `target`: `/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 栏目     | type |\n| -------- | ---- |\n| 安科要闻 | akyw |\n| 通知公告 | tzgg |\n| 学术安科 | xsak |\n| 校园动态 | xydt |\n| 媒体聚焦 | mtak |\n| 人物风采 | rwfc |\n| 视觉校园 | sjxy |",
  "example": "/ahstu/akyw",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "JizzCruiy"
  ],
  "name": "官网通知与新闻",
  "parameters": {
    "type": "栏目类型，见下表，默认为 `akyw`"
  },
  "path": "/:type?",
  "radar": [
    {
      "source": [
        "www.ahstu.edu.cn/index/:type.htm"
      ],
      "target": "/:type"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
