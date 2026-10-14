# 东北大学 - 新闻网

## Coverage
`index-only`

## Route
- Namespace: `neu`
- Namespace Name: `东北大学`
- Route Path: `/neu/news/:type`
- Route Name: `新闻网`
- Example: `/neu/news/ddyw`
- URL: `neunews.neu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `JeasonLau`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 种类名   | 参数 |
| -------- | ---- |
| 东大要闻 | ddyw |
| 媒体东大 | mtdd |
| 通知公告 | tzgg |
| 新闻纵横 | xwzh |
| 人才培养 | rcpy |
| 学术科研 | xsky |
| 英文新闻 | 217  |
| 招生就业 | zsjy |
| 考研出国 | kycg |
| 校园文学 | xywx |
| 校友风采 | xyfc |
| 时事热点 | ssrd |
| 教育前沿 | jyqy |
| 文化体育 | whty |
| 最新科技 | zxkj |

## Parameters
- `type`: 种类名，见下表


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
  - `neunews.neu.edu.cn/`
- `target`: `/news/ddyw`
### Rule 2
- `source`:
  - `neunews.neu.edu.cn/ddyw.htm`
- `target`: `/news/ddyw`
### Rule 3
- `source`:
  - `neunews.neu.edu.cn/mtdd.htm`
- `target`: `/news/mtdd`
### Rule 4
- `source`:
  - `neunews.neu.edu.cn/tzgg.htm`
- `target`: `/news/tzgg`
### Rule 5
- `source`:
  - `neunews.neu.edu.cn/rcpy.htm`
- `target`: `/news/rcpy`
### Rule 6
- `source`:
  - `neunews.neu.edu.cn/zhxw.htm`
- `target`: `/news/zhxw`
### Rule 7
- `source`:
  - `neunews.neu.edu.cn/yxdt.htm`
- `target`: `/news/yxdt`
### Rule 8
- `source`:
  - `neunews.neu.edu.cn/jsdd.htm`
- `target`: `/news/jsdd`
### Rule 9
- `source`:
  - `neunews.neu.edu.cn/tsdd.htm`
- `target`: `/news/tsdd`
### Rule 10
- `source`:
  - `neunews.neu.edu.cn/xykd.htm`
- `target`: `/news/xykd`
### Rule 11
- `source`:
  - `neunews.neu.edu.cn/rmdd.htm`
- `target`: `/news/rmdd`
### Rule 12
- `source`:
  - `neunews.neu.edu.cn/wsd.htm`
- `target`: `/news/wsd`
### Rule 13
- `source`:
  - `neunews.neu.edu.cn/Focus.htm`
- `target`: `/news/Focus`
### Rule 14
- `source`:
  - `neunews.neu.edu.cn/Media.htm`
- `target`: `/news/Media`
### Rule 15
- `source`:
  - `neunews.neu.edu.cn/Research.htm`
- `target`: `/news/Research`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 种类名   | 参数 |\n| -------- | ---- |\n| 东大要闻 | ddyw |\n| 媒体东大 | mtdd |\n| 通知公告 | tzgg |\n| 新闻纵横 | xwzh |\n| 人才培养 | rcpy |\n| 学术科研 | xsky |\n| 英文新闻 | 217  |\n| 招生就业 | zsjy |\n| 考研出国 | kycg |\n| 校园文学 | xywx |\n| 校友风采 | xyfc |\n| 时事热点 | ssrd |\n| 教育前沿 | jyqy |\n| 文化体育 | whty |\n| 最新科技 | zxkj |",
  "example": "/neu/news/ddyw",
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
    "JeasonLau"
  ],
  "name": "新闻网",
  "parameters": {
    "type": "种类名，见下表"
  },
  "path": "/news/:type",
  "radar": [
    {
      "source": [
        "neunews.neu.edu.cn/"
      ],
      "target": "/news/ddyw"
    },
    {
      "source": [
        "neunews.neu.edu.cn/ddyw.htm"
      ],
      "target": "/news/ddyw"
    },
    {
      "source": [
        "neunews.neu.edu.cn/mtdd.htm"
      ],
      "target": "/news/mtdd"
    },
    {
      "source": [
        "neunews.neu.edu.cn/tzgg.htm"
      ],
      "target": "/news/tzgg"
    },
    {
      "source": [
        "neunews.neu.edu.cn/rcpy.htm"
      ],
      "target": "/news/rcpy"
    },
    {
      "source": [
        "neunews.neu.edu.cn/zhxw.htm"
      ],
      "target": "/news/zhxw"
    },
    {
      "source": [
        "neunews.neu.edu.cn/yxdt.htm"
      ],
      "target": "/news/yxdt"
    },
    {
      "source": [
        "neunews.neu.edu.cn/jsdd.htm"
      ],
      "target": "/news/jsdd"
    },
    {
      "source": [
        "neunews.neu.edu.cn/tsdd.htm"
      ],
      "target": "/news/tsdd"
    },
    {
      "source": [
        "neunews.neu.edu.cn/xykd.htm"
      ],
      "target": "/news/xykd"
    },
    {
      "source": [
        "neunews.neu.edu.cn/rmdd.htm"
      ],
      "target": "/news/rmdd"
    },
    {
      "source": [
        "neunews.neu.edu.cn/wsd.htm"
      ],
      "target": "/news/wsd"
    },
    {
      "source": [
        "neunews.neu.edu.cn/Focus.htm"
      ],
      "target": "/news/Focus"
    },
    {
      "source": [
        "neunews.neu.edu.cn/Media.htm"
      ],
      "target": "/news/Media"
    },
    {
      "source": [
        "neunews.neu.edu.cn/Research.htm"
      ],
      "target": "/news/Research"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
