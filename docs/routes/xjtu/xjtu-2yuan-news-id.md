# 西安交通大学 - 第二附属医院新闻

## Coverage
`index-only`

## Route
- Namespace: `xjtu`
- Namespace Name: `西安交通大学`
- Route Path: `/xjtu/2yuan/news/:id?`
- Route Name: `第二附属医院新闻`
- Example: `/xjtu/2yuan/news`
- URL: `2yuan.xjtu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `2yuan/news.ts`
- Source Module: `_None_`

## Description
| 分类     | 编号 |
| -------- | ---- |
| 通知公告 | 110  |
| 综合新闻 | 6    |
| 科室动态 | 8    |
| 教学动态 | 45   |
| 科研动态 | 51   |
| 护理动态 | 57   |
| 媒体二院 | 14   |

## Parameters
- `id`: 编号，见下表，默认为通知公告


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
  "description": "| 分类     | 编号 |\n| -------- | ---- |\n| 通知公告 | 110  |\n| 综合新闻 | 6    |\n| 科室动态 | 8    |\n| 教学动态 | 45   |\n| 科研动态 | 51   |\n| 护理动态 | 57   |\n| 媒体二院 | 14   |",
  "example": "/xjtu/2yuan/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "2yuan/news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "第二附属医院新闻",
  "parameters": {
    "id": "编号，见下表，默认为通知公告"
  },
  "path": "/2yuan/news/:id?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
