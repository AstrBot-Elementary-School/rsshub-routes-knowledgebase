# 北京林业大学 - 教务处通知公告

## Coverage
`index-only`

## Route
- Namespace: `bjfu`
- Namespace Name: `北京林业大学`
- Route Path: `/bjfu/jwc/:type`
- Route Name: `教务处通知公告`
- Example: `/bjfu/jwc/jwkx`
- URL: `graduate.bjfu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `markmingjie`
- Source Location: `jwc/index.ts`
- Source Module: `_None_`

## Description
| 教务快讯 | 考试信息 | 课程信息 | 教改动态 | 图片新闻 |
| -------- | -------- | -------- | -------- | -------- |
| jwkx     | ksxx     | kcxx     | jgdt     | tpxw     |

## Parameters
- `type`: 通知类别


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
  - `jwc.bjfu.edu.cn/:type/index.html`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 教务快讯 | 考试信息 | 课程信息 | 教改动态 | 图片新闻 |\n| -------- | -------- | -------- | -------- | -------- |\n| jwkx     | ksxx     | kcxx     | jgdt     | tpxw     |",
  "example": "/bjfu/jwc/jwkx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwc/index.ts",
  "maintainers": [
    "markmingjie"
  ],
  "name": "教务处通知公告",
  "parameters": {
    "type": "通知类别"
  },
  "path": "/jwc/:type",
  "radar": [
    {
      "source": [
        "jwc.bjfu.edu.cn/:type/index.html"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
