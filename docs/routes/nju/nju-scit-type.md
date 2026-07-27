# 南京大学 - 科学技术处

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/nju/scit/:type`
- Route Name: `科学技术处`
- Example: `/nju/scit/tzgg`
- URL: `admission.nju.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ret-1`
- Source Location: `scit.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 科研动态 |
| -------- | -------- |
| tzgg     | kydt     |

## Parameters
- `type`: 分类名


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
  "description": "| 通知公告 | 科研动态 |\n| -------- | -------- |\n| tzgg     | kydt     |",
  "example": "/nju/scit/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "scit.ts",
  "maintainers": [
    "ret-1"
  ],
  "name": "科学技术处",
  "parameters": {
    "type": "分类名"
  },
  "path": "/scit/:type",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "科学技术处-通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62660807098104832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://scit.nju.edu.cn/10916/list.htm",
      "title": "科学技术处-通知公告",
      "type": "feed",
      "url": "rsshub://nju/scit/tzgg"
    }
  ]
}
```
