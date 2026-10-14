# 浙江工业大学 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `zjut`
- Namespace Name: `浙江工业大学`
- Route Path: `/zjut/news/:type`
- Route Name: `新闻`
- Example: `/zjut/news/5414`
- URL: `www.news.zjut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `junbaor, yikZero`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 图片新闻 | 工大要闻 | 综合新闻 | 学术・探索 | 三创・人物 | 智库工大 | 美誉工大 | 葵园融媒 |
| -------- | -------- | -------- | ---------- | ---------- | -------- | -------- | -------- |
| 5414     | 5415     | 5416     | 5422       | 5423       | 5424     | 5425     | 5419     |

## Parameters
- `type`: 分类，见下表


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
  - `www.news.zjut.edu.cn/:type/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 图片新闻 | 工大要闻 | 综合新闻 | 学术・探索 | 三创・人物 | 智库工大 | 美誉工大 | 葵园融媒 |\n| -------- | -------- | -------- | ---------- | ---------- | -------- | -------- | -------- |\n| 5414     | 5415     | 5416     | 5422       | 5423       | 5424     | 5425     | 5419     |",
  "example": "/zjut/news/5414",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "junbaor",
    "yikZero"
  ],
  "name": "新闻",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/news/:type",
  "radar": [
    {
      "source": [
        "www.news.zjut.edu.cn/:type/list.htm"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "www.news.zjut.edu.cn"
}
```
