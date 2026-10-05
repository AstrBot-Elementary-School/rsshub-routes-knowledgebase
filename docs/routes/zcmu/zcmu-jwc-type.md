# 浙江中医药大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `zcmu`
- Namespace Name: `浙江中医药大学`
- Route Path: `/zcmu/jwc/:type?`
- Route Name: `教务处`
- Example: `/zcmu/jwc/1`
- URL: `jwc.zcmu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `CCraftY`
- Source Location: `jwc/index.ts`
- Source Module: `_None_`

## Description
| 教务管理 | 成绩管理 | 学籍管理 | 考试管理 | 选课管理 | 排课管理 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| 0        | 1        | 2        | 3        | 4        | 5        |

## Parameters
- `type`: 通知模块id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
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
  "description": "| 教务管理 | 成绩管理 | 学籍管理 | 考试管理 | 选课管理 | 排课管理 |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| 0        | 1        | 2        | 3        | 4        | 5        |",
  "example": "/zcmu/jwc/1",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 17,
  "location": "jwc/index.ts",
  "maintainers": [
    "CCraftY"
  ],
  "name": "教务处",
  "parameters": {
    "type": "通知模块id"
  },
  "path": "/jwc/:type?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "教务处 -- 排课管理 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84227265299092494",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jwc.zcmu.edu.cn/jwgl/pkgl",
      "title": "教务处 -- 排课管理",
      "type": "feed",
      "url": "rsshub://zcmu/jwc/5"
    },
    {
      "description": "教务处 -- 成绩管理 - Powered by RSSHub",
      "errorAt": "2025-09-02T09:21:09.522Z",
      "errorMessage": "[GET] \"https://jwc.zcmu.edu.cn//jwgl/cjgl.htm\": 404 Not Found\n",
      "id": "84227265299092496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jwc.zcmu.edu.cn/jwgl/cjgl",
      "title": "教务处 -- 成绩管理",
      "type": "feed",
      "url": "rsshub://zcmu/jwc/1"
    }
  ]
}
```
