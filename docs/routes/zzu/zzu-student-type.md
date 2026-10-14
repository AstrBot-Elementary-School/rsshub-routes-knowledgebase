# 郑州大学 - 学生处

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/zzu/student/:type`
- Route Name: `学生处`
- Example: `/zzu/student/xwzx`
- URL: `www.zzu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `amandus1990`
- Source Location: `student.ts`
- Source Module: `_None_`

## Description
| 新闻资讯 | 通知公告 |
| -------- | -------- |
| xwzx     | tzgg     |

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
### Rule 1
- `source`:
  - `www5.zzu.edu.cn/student/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻资讯 | 通知公告 |\n| -------- | -------- |\n| xwzx     | tzgg     |",
  "example": "/zzu/student/xwzx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "student.ts",
  "maintainers": [
    "amandus1990"
  ],
  "name": "学生处",
  "parameters": {
    "type": "分类名"
  },
  "path": "/student/:type",
  "radar": [
    {
      "source": [
        "www5.zzu.edu.cn/student/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
