# 武汉大学 - 计算机学院公告

## Coverage
`index-only`

## Route
- Namespace: `whu`
- Namespace Name: `武汉大学`
- Route Path: `/whu/cs/:type`
- Route Name: `计算机学院公告`
- Example: `/whu/cs/2`
- URL: `cs.whu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ttyfly`
- Source Location: `cs.ts`
- Source Module: `_None_`

## Description
| 公告类型 | 学院新闻 | 学术交流 | 通知公告 | 科研进展 |
| -------- | -------- | -------- | -------- | -------- |
| 参数     | 0        | 1        | 2        | 3        |

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
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 公告类型 | 学院新闻 | 学术交流 | 通知公告 | 科研进展 |\n| -------- | -------- | -------- | -------- | -------- |\n| 参数     | 0        | 1        | 2        | 3        |",
  "example": "/whu/cs/2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "cs.ts",
  "maintainers": [
    "ttyfly"
  ],
  "name": "计算机学院公告",
  "parameters": {
    "type": "公告类型，详见表格"
  },
  "path": "/cs/:type",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "通知公告-武汉大学计算机学院 - Powered by RSSHub",
      "errorAt": "2026-09-08T11:01:57.045Z",
      "errorMessage": "[GET] \"https://cs.whu.edu.cn/xwdt/tzgg.htm\": 525 <none>\n",
      "id": "60249215166679040",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cs.whu.edu.cn/xwdt/tzgg.htm",
      "title": "通知公告-武汉大学计算机学院",
      "type": "feed",
      "url": "rsshub://whu/cs/2"
    }
  ]
}
```
