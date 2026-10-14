# 哈尔滨理工大学 - 新闻网

## Coverage
`index-only`

## Route
- Namespace: `hrbust`
- Namespace Name: `哈尔滨理工大学`
- Route Path: `/hrbust/news/:category?`
- Route Name: `新闻网`
- Example: `/hrbust/news`
- URL: `news.hrbust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `cscnk52`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 理工要闻 | 新闻导读 | 图文报道 | 综合新闻 | 教学科研 | 院处动态 | 学术科创 | 交流合作 | 学生天地 | 招生就业 | 党建思政 | 在线播放 | 理工人物 | 理工校报 | 媒体理工 | 讲座论坛 | 人才招聘 | 学科建设 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| lgyw     | xwdd     | twbd     | zhenew   | jxky     | ycdt     | xskc     | jlhz     | xstd     | zsjy     | djsz     | zxbf     | lgrw     | lgxb     | mtlg     | jzlt     | rczp     | xkjs     |

## Parameters
- `category`: 栏目标识，默认为 lgyw（理工要闻）


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `news.hrbust.edu.cn/lgyw.htm`
- `target`: `/news/lgyw`
### Rule 2
- `source`:
  - `news.hrbust.edu.cn/xwdd.htm`
- `target`: `/news/xwdd`
### Rule 3
- `source`:
  - `news.hrbust.edu.cn/twbd.htm`
- `target`: `/news/twbd`
### Rule 4
- `source`:
  - `news.hrbust.edu.cn/zhenew.htm`
- `target`: `/news/zhenew`
### Rule 5
- `source`:
  - `news.hrbust.edu.cn/jxky.htm`
- `target`: `/news/jxky`
### Rule 6
- `source`:
  - `news.hrbust.edu.cn/ycdt.htm`
- `target`: `/news/ycdt`
### Rule 7
- `source`:
  - `news.hrbust.edu.cn/xskc.htm`
- `target`: `/news/xskc`
### Rule 8
- `source`:
  - `news.hrbust.edu.cn/jlhz.htm`
- `target`: `/news/jlhz`
### Rule 9
- `source`:
  - `news.hrbust.edu.cn/xstd.htm`
- `target`: `/news/xstd`
### Rule 10
- `source`:
  - `news.hrbust.edu.cn/zsjy.htm`
- `target`: `/news/zsjy`
### Rule 11
- `source`:
  - `news.hrbust.edu.cn/djsz.htm`
- `target`: `/news/djsz`
### Rule 12
- `source`:
  - `news.hrbust.edu.cn/zxbf.htm`
- `target`: `/news/zxbf`
### Rule 13
- `source`:
  - `news.hrbust.edu.cn/lgrw.htm`
- `target`: `/news/lgrw`
### Rule 14
- `source`:
  - `news.hrbust.edu.cn/lgxb.htm`
- `target`: `/news/lgxb`
### Rule 15
- `source`:
  - `news.hrbust.edu.cn/mtlg.htm`
- `target`: `/news/mtlg`
### Rule 16
- `source`:
  - `news.hrbust.edu.cn/jzlt.htm`
- `target`: `/news/jzlt`
### Rule 17
- `source`:
  - `news.hrbust.edu.cn/rczp.htm`
- `target`: `/news/rczp`
### Rule 18
- `source`:
  - `news.hrbust.edu.cn/xkjs.htm`
- `target`: `/news/xkjs`
### Rule 19
- `source`:
  - `news.hrbust.edu.cn/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 理工要闻 | 新闻导读 | 图文报道 | 综合新闻 | 教学科研 | 院处动态 | 学术科创 | 交流合作 | 学生天地 | 招生就业 | 党建思政 | 在线播放 | 理工人物 | 理工校报 | 媒体理工 | 讲座论坛 | 人才招聘 | 学科建设 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| lgyw     | xwdd     | twbd     | zhenew   | jxky     | ycdt     | xskc     | jlhz     | xstd     | zsjy     | djsz     | zxbf     | lgrw     | lgxb     | mtlg     | jzlt     | rczp     | xkjs     |",
  "example": "/hrbust/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "cscnk52"
  ],
  "name": "新闻网",
  "parameters": {
    "category": "栏目标识，默认为 lgyw（理工要闻）"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "news.hrbust.edu.cn/lgyw.htm"
      ],
      "target": "/news/lgyw"
    },
    {
      "source": [
        "news.hrbust.edu.cn/xwdd.htm"
      ],
      "target": "/news/xwdd"
    },
    {
      "source": [
        "news.hrbust.edu.cn/twbd.htm"
      ],
      "target": "/news/twbd"
    },
    {
      "source": [
        "news.hrbust.edu.cn/zhenew.htm"
      ],
      "target": "/news/zhenew"
    },
    {
      "source": [
        "news.hrbust.edu.cn/jxky.htm"
      ],
      "target": "/news/jxky"
    },
    {
      "source": [
        "news.hrbust.edu.cn/ycdt.htm"
      ],
      "target": "/news/ycdt"
    },
    {
      "source": [
        "news.hrbust.edu.cn/xskc.htm"
      ],
      "target": "/news/xskc"
    },
    {
      "source": [
        "news.hrbust.edu.cn/jlhz.htm"
      ],
      "target": "/news/jlhz"
    },
    {
      "source": [
        "news.hrbust.edu.cn/xstd.htm"
      ],
      "target": "/news/xstd"
    },
    {
      "source": [
        "news.hrbust.edu.cn/zsjy.htm"
      ],
      "target": "/news/zsjy"
    },
    {
      "source": [
        "news.hrbust.edu.cn/djsz.htm"
      ],
      "target": "/news/djsz"
    },
    {
      "source": [
        "news.hrbust.edu.cn/zxbf.htm"
      ],
      "target": "/news/zxbf"
    },
    {
      "source": [
        "news.hrbust.edu.cn/lgrw.htm"
      ],
      "target": "/news/lgrw"
    },
    {
      "source": [
        "news.hrbust.edu.cn/lgxb.htm"
      ],
      "target": "/news/lgxb"
    },
    {
      "source": [
        "news.hrbust.edu.cn/mtlg.htm"
      ],
      "target": "/news/mtlg"
    },
    {
      "source": [
        "news.hrbust.edu.cn/jzlt.htm"
      ],
      "target": "/news/jzlt"
    },
    {
      "source": [
        "news.hrbust.edu.cn/rczp.htm"
      ],
      "target": "/news/rczp"
    },
    {
      "source": [
        "news.hrbust.edu.cn/xkjs.htm"
      ],
      "target": "/news/xkjs"
    },
    {
      "source": [
        "news.hrbust.edu.cn/"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "news.hrbust.edu.cn",
  "view": 5
}
```
