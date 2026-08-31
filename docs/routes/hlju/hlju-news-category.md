# 黑龙江大学 - 新闻网

## Coverage
`index-only`

## Route
- Namespace: `hlju`
- Namespace Name: `黑龙江大学`
- Route Path: `/hlju/news/:category?`
- Route Name: `新闻网`
- Example: `/hlju/news/hdyw`
- URL: `hlju.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `LCMs-YoRHa`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"description": "新闻分类，默认为黑大要闻", "options": [{"label": "黑大要闻", "value": "hdyw"}, {"label": "菁菁校园", "value": "jjxy"}, {"label": "人物风采", "value": "rwfc"}, {"label": "新闻动态", "value": "xwdt"}, {"label": "教学科研", "value": "jxky"}, {"label": "学院经纬", "value": "xyjw"}, {"label": "交流合作", "value": "jlhz"}, {"label": "创新创业", "value": "cxcy"}]}


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
  - `hdxw.hlju.edu.cn/:category.htm`
  - `hdxw.hlju.edu.cn/`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/hlju/news/hdyw",
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
    "LCMs-YoRHa"
  ],
  "name": "新闻网",
  "parameters": {
    "category": {
      "description": "新闻分类，默认为黑大要闻",
      "options": [
        {
          "label": "黑大要闻",
          "value": "hdyw"
        },
        {
          "label": "菁菁校园",
          "value": "jjxy"
        },
        {
          "label": "人物风采",
          "value": "rwfc"
        },
        {
          "label": "新闻动态",
          "value": "xwdt"
        },
        {
          "label": "教学科研",
          "value": "jxky"
        },
        {
          "label": "学院经纬",
          "value": "xyjw"
        },
        {
          "label": "交流合作",
          "value": "jlhz"
        },
        {
          "label": "创新创业",
          "value": "cxcy"
        }
      ]
    }
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "hdxw.hlju.edu.cn/:category.htm",
        "hdxw.hlju.edu.cn/"
      ],
      "target": "/news/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
