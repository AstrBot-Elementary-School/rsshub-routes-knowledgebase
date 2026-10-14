# 郑州大学 - 人事部

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/zzu/rsc/:type`
- Route Name: `人事部`
- Example: `/zzu/rsc/rsyw`
- URL: `www.zzu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `amandus1990`
- Source Location: `rsc.ts`
- Source Module: `_None_`

## Description
| 人事要闻 | 通知公告 | 招聘公告 |
| -------- | -------- | -------- |
| rsyw     | tzgg     | zpxx     |

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
  - `www5.zzu.edu.cn/rsc/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 人事要闻 | 通知公告 | 招聘公告 |\n| -------- | -------- | -------- |\n| rsyw     | tzgg     | zpxx     |",
  "example": "/zzu/rsc/rsyw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "rsc.ts",
  "maintainers": [
    "amandus1990"
  ],
  "name": "人事部",
  "parameters": {
    "type": "分类名"
  },
  "path": "/rsc/:type",
  "radar": [
    {
      "source": [
        "www5.zzu.edu.cn/rsc/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
