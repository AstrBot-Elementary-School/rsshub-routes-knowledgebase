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
  - `hdxw.hlju.edu.cn/`
- `target`: `/news`
### Rule 2
- `source`:
  - `hdxw.hlju.edu.cn/hdyw.htm`
- `target`: `/news/hdyw`
### Rule 3
- `source`:
  - `hdxw.hlju.edu.cn/jjxy.htm`
- `target`: `/news/jjxy`
### Rule 4
- `source`:
  - `hdxw.hlju.edu.cn/rwfc.htm`
- `target`: `/news/rwfc`
### Rule 5
- `source`:
  - `hdxw.hlju.edu.cn/xwdt.htm`
- `target`: `/news/xwdt`
### Rule 6
- `source`:
  - `hdxw.hlju.edu.cn/jxky.htm`
- `target`: `/news/jxky`
### Rule 7
- `source`:
  - `hdxw.hlju.edu.cn/xyjw.htm`
- `target`: `/news/xyjw`
### Rule 8
- `source`:
  - `hdxw.hlju.edu.cn/jlhz.htm`
- `target`: `/news/jlhz`
### Rule 9
- `source`:
  - `hdxw.hlju.edu.cn/cxcy.htm`
- `target`: `/news/cxcy`

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
        "hdxw.hlju.edu.cn/"
      ],
      "target": "/news"
    },
    {
      "source": [
        "hdxw.hlju.edu.cn/hdyw.htm"
      ],
      "target": "/news/hdyw"
    },
    {
      "source": [
        "hdxw.hlju.edu.cn/jjxy.htm"
      ],
      "target": "/news/jjxy"
    },
    {
      "source": [
        "hdxw.hlju.edu.cn/rwfc.htm"
      ],
      "target": "/news/rwfc"
    },
    {
      "source": [
        "hdxw.hlju.edu.cn/xwdt.htm"
      ],
      "target": "/news/xwdt"
    },
    {
      "source": [
        "hdxw.hlju.edu.cn/jxky.htm"
      ],
      "target": "/news/jxky"
    },
    {
      "source": [
        "hdxw.hlju.edu.cn/xyjw.htm"
      ],
      "target": "/news/xyjw"
    },
    {
      "source": [
        "hdxw.hlju.edu.cn/jlhz.htm"
      ],
      "target": "/news/jlhz"
    },
    {
      "source": [
        "hdxw.hlju.edu.cn/cxcy.htm"
      ],
      "target": "/news/cxcy"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
