# 清华大学 - 清华新闻

## Coverage
`index-only`

## Route
- Namespace: `tsinghua`
- Namespace Name: `清华大学`
- Route Path: `/tsinghua/news/:category?`
- Route Name: `清华新闻`
- Example: `/tsinghua/news`
- URL: `www.tsinghua.edu.cn/news.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 分类，可在对应分类页 URL 中找到，留空为 `zxdt`


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
  - `www.tsinghua.edu.cn/news.htm`
- `target`: `/news`
### Rule 2
- `source`:
  - `www.tsinghua.edu.cn/news/ttxw.htm`
- `target`: `/news/ttxw`
### Rule 3
- `source`:
  - `www.tsinghua.edu.cn/news/zttj.htm`
- `target`: `/news/zttj`
### Rule 4
- `source`:
  - `www.tsinghua.edu.cn/news/zxdt.htm`
- `target`: `/news/zxdt`
### Rule 5
- `source`:
  - `www.tsinghua.edu.cn/news/mtqh.htm`
- `target`: `/news/mtqh`
### Rule 6
- `source`:
  - `www.tsinghua.edu.cn/news/zhsx.htm`
- `target`: `/news/zhsx`
### Rule 7
- `source`:
  - `www.tsinghua.edu.cn/news/rcpy.htm`
- `target`: `/news/rcpy`
### Rule 8
- `source`:
  - `www.tsinghua.edu.cn/news/xsky.htm`
- `target`: `/news/xsky`
### Rule 9
- `source`:
  - `www.tsinghua.edu.cn/news/jlhz.htm`
- `target`: `/news/jlhz`
### Rule 10
- `source`:
  - `www.tsinghua.edu.cn/news/qhrw.htm`
- `target`: `/news/qhrw`
### Rule 11
- `source`:
  - `www.tsinghua.edu.cn/news/qqxy.htm`
- `target`: `/news/qqxy`
### Rule 12
- `source`:
  - `www.tsinghua.edu.cn/news/qhly.htm`
- `target`: `/news/qhly`
### Rule 13
- `source`:
  - `www.tsinghua.edu.cn/news/qhgj.htm`
- `target`: `/news/qhgj`
### Rule 14
- `source`:
  - `www.tsinghua.edu.cn/news/qhsy.htm`
- `target`: `/news/qhsy`
### Rule 15
- `source`:
  - `www.tsinghua.edu.cn/news/qhsk.htm`
- `target`: `/news/qhsk`
### Rule 16
- `source`:
  - `www.tsinghua.edu.cn/news/qhxk.htm`
- `target`: `/news/qhxk`
### Rule 17
- `source`:
  - `www.tsinghua.edu.cn/news/xwhj.htm`
- `target`: `/news/xwhj`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/tsinghua/news",
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
    "TonyRL"
  ],
  "name": "清华新闻",
  "parameters": {
    "category": "分类，可在对应分类页 URL 中找到，留空为 `zxdt`"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "www.tsinghua.edu.cn/news.htm"
      ],
      "target": "/news"
    },
    {
      "source": [
        "www.tsinghua.edu.cn/news/ttxw.htm"
      ],
      "target": "/news/ttxw"
    },
    {
      "source": [
        "www.tsinghua.edu.cn/news/zttj.htm"
      ],
      "target": "/news/zttj"
    },
    {
      "source": [
        "www.tsinghua.edu.cn/news/zxdt.htm"
      ],
      "target": "/news/zxdt"
    },
    {
      "source": [
        "www.tsinghua.edu.cn/news/mtqh.htm"
      ],
      "target": "/news/mtqh"
    },
    {
      "source": [
        "www.tsinghua.edu.cn/news/zhsx.htm"
      ],
      "target": "/news/zhsx"
    },
    {
      "source": [
        "www.tsinghua.edu.cn/news/rcpy.htm"
      ],
      "target": "/news/rcpy"
    },
    {
      "source": [
        "www.tsinghua.edu.cn/news/xsky.htm"
      ],
      "target": "/news/xsky"
    },
    {
      "source": [
        "www.tsinghua.edu.cn/news/jlhz.htm"
      ],
      "target": "/news/jlhz"
    },
    {
      "source": [
        "www.tsinghua.edu.cn/news/qhrw.htm"
      ],
      "target": "/news/qhrw"
    },
    {
      "source": [
        "www.tsinghua.edu.cn/news/qqxy.htm"
      ],
      "target": "/news/qqxy"
    },
    {
      "source": [
        "www.tsinghua.edu.cn/news/qhly.htm"
      ],
      "target": "/news/qhly"
    },
    {
      "source": [
        "www.tsinghua.edu.cn/news/qhgj.htm"
      ],
      "target": "/news/qhgj"
    },
    {
      "source": [
        "www.tsinghua.edu.cn/news/qhsy.htm"
      ],
      "target": "/news/qhsy"
    },
    {
      "source": [
        "www.tsinghua.edu.cn/news/qhsk.htm"
      ],
      "target": "/news/qhsk"
    },
    {
      "source": [
        "www.tsinghua.edu.cn/news/qhxk.htm"
      ],
      "target": "/news/qhxk"
    },
    {
      "source": [
        "www.tsinghua.edu.cn/news/xwhj.htm"
      ],
      "target": "/news/xwhj"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "www.tsinghua.edu.cn/news.htm"
}
```
