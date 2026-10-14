# 郑州大学 - 商学院

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/zzu/sxy/:type`
- Route Name: `商学院`
- Example: `/zzu/sxy/xyxw`
- URL: `www.zzu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `amandus1990`
- Source Location: `sxy.ts`
- Source Module: `_None_`

## Description
| 学院新闻 | 通知公告 | 教学科研 | 党工团学 | 讲座报告 | 学者观点 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| xyxw     | tzgg     | jxky     | dgtx     | jzbg     | xzgd     |

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
  - `www5.zzu.edu.cn/sxy/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学院新闻 | 通知公告 | 教学科研 | 党工团学 | 讲座报告 | 学者观点 |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| xyxw     | tzgg     | jxky     | dgtx     | jzbg     | xzgd     |",
  "example": "/zzu/sxy/xyxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "sxy.ts",
  "maintainers": [
    "amandus1990"
  ],
  "name": "商学院",
  "parameters": {
    "type": "分类名"
  },
  "path": "/sxy/:type",
  "radar": [
    {
      "source": [
        "www5.zzu.edu.cn/sxy/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
