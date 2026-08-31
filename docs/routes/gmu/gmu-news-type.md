# 赣南医科大学 - 新闻中心

## Coverage
`index-only`

## Route
- Namespace: `gmu`
- Namespace Name: `赣南医科大学`
- Route Path: `/gmu/news/:type?`
- Route Name: `新闻中心`
- Example: `/gmu/news/gyyw`
- URL: `gmu.cn/xwzx/gyyw.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `FrankFahey`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"default": "gyyw", "description": "新闻类型，见下表，默认为 gyyw", "options": [{"label": "赣医要闻", "value": "gyyw"}, {"label": "院部动态", "value": "ybdt"}, {"label": "媒体赣医", "value": "mtgy"}, {"label": "学术讲座", "value": "xsjz"}]}


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
  - `gmu.cn/xwzx/gyyw.htm`
  - `gmu.cn/`
- `target`: `/news/gyyw`
### Rule 2
- `source`:
  - `gmu.cn/xwzx/ybdt.htm`
- `target`: `/news/ybdt`
### Rule 3
- `source`:
  - `gmu.cn/xwzx/mtgy.htm`
- `target`: `/news/mtgy`
### Rule 4
- `source`:
  - `gmu.cn/xwzx/xsjz.htm`
- `target`: `/news/xsjz`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/gmu/news/gyyw",
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
    "FrankFahey"
  ],
  "name": "新闻中心",
  "parameters": {
    "type": {
      "default": "gyyw",
      "description": "新闻类型，见下表，默认为 gyyw",
      "options": [
        {
          "label": "赣医要闻",
          "value": "gyyw"
        },
        {
          "label": "院部动态",
          "value": "ybdt"
        },
        {
          "label": "媒体赣医",
          "value": "mtgy"
        },
        {
          "label": "学术讲座",
          "value": "xsjz"
        }
      ]
    }
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "gmu.cn/xwzx/gyyw.htm",
        "gmu.cn/"
      ],
      "target": "/news/gyyw"
    },
    {
      "source": [
        "gmu.cn/xwzx/ybdt.htm"
      ],
      "target": "/news/ybdt"
    },
    {
      "source": [
        "gmu.cn/xwzx/mtgy.htm"
      ],
      "target": "/news/mtgy"
    },
    {
      "source": [
        "gmu.cn/xwzx/xsjz.htm"
      ],
      "target": "/news/xsjz"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "gmu.cn/xwzx/gyyw.htm"
}
```
