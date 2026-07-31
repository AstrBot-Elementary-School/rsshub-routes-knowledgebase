# 同济大学 - 经济与管理学院通知

## Coverage
`index-only`

## Route
- Namespace: `tongji`
- Namespace Name: `同济大学`
- Route Path: `/tongji/sem/:type?`
- Route Name: `经济与管理学院通知`
- Example: `/tongji/sem/notice`
- URL: `sem.tongji.edu.cn/semch`
- Language: `_None_`
- Categories: `university`
- Maintainers: `sitdownkevin`
- Source Location: `sem/notice.ts`
- Source Module: `_None_`

## Description
| 学院通知 | 招生通知   | 学术观点       | 新闻 | 活动   | 视点  | 教师与行政人员招聘 |
| -------- | ---------- | -------------- | ---- | ------ | ----- | ------------------ |
| notice   | enrollment | academic-paper | news | events | focus | collegerecruitment |

## Parameters
- `type`: 通知类型，默认为 `notice`


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
  "description": "| 学院通知 | 招生通知   | 学术观点       | 新闻 | 活动   | 视点  | 教师与行政人员招聘 |\n| -------- | ---------- | -------------- | ---- | ------ | ----- | ------------------ |\n| notice   | enrollment | academic-paper | news | events | focus | collegerecruitment |",
  "example": "/tongji/sem/notice",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "sem/notice.ts",
  "maintainers": [
    "sitdownkevin"
  ],
  "name": "经济与管理学院通知",
  "parameters": {
    "type": "通知类型，默认为 `notice`"
  },
  "path": "/sem/:type?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "学术观点 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "79124130475658240",
      "image": "https://upload.wikimedia.org/wikipedia/zh/f/f8/Tongji_University_Emblem.svg",
      "ownerUserId": null,
      "siteUrl": "https://sem.tongji.edu.cn/semch",
      "title": "同济大学经济与管理学院",
      "type": "feed",
      "url": "rsshub://tongji/sem/academic-paper"
    },
    {
      "description": "活动 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "79122838265601024",
      "image": "https://upload.wikimedia.org/wikipedia/zh/f/f8/Tongji_University_Emblem.svg",
      "ownerUserId": null,
      "siteUrl": "https://sem.tongji.edu.cn/semch",
      "title": "同济大学经济与管理学院",
      "type": "feed",
      "url": "rsshub://tongji/sem/events"
    }
  ],
  "url": "sem.tongji.edu.cn/semch"
}
```
