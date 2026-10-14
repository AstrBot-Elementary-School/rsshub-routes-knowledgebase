# 潍坊学院 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `wfu`
- Namespace Name: `潍坊学院`
- Route Path: `/wfu/news/:type?`
- Route Name: `新闻`
- Example: `/wfu/news/wyyw`
- URL: `www.wfu.edu.cn/50/list.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `cccht`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| **内容** | **参数** |
| :------: | :------: |
| 潍院要闻 |   wyyw   |
| 综合新闻 |   zhxw   |
| 学术纵横 |   xszh   |

## Parameters
- `type`: 分类，默认为 `wyyw`，具体参数见下表


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
  - `news.wfu.edu.cn/`
- `target`: `/news`
### Rule 2
- `source`:
  - `www.wfu.edu.cn/50/list.htm`
- `target`: `/news/wyyw`
### Rule 3
- `source`:
  - `www.wfu.edu.cn/52/list.htm`
- `target`: `/news/zhxw`
### Rule 4
- `source`:
  - `www.wfu.edu.cn/xszh/list.htm`
- `target`: `/news/xszh`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| **内容** | **参数** |\n| :------: | :------: |\n| 潍院要闻 |   wyyw   |\n| 综合新闻 |   zhxw   |\n| 学术纵横 |   xszh   |",
  "example": "/wfu/news/wyyw",
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
    "cccht"
  ],
  "name": "新闻",
  "parameters": {
    "type": "分类，默认为 `wyyw`，具体参数见下表"
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "news.wfu.edu.cn/"
      ],
      "target": "/news"
    },
    {
      "source": [
        "www.wfu.edu.cn/50/list.htm"
      ],
      "target": "/news/wyyw"
    },
    {
      "source": [
        "www.wfu.edu.cn/52/list.htm"
      ],
      "target": "/news/zhxw"
    },
    {
      "source": [
        "www.wfu.edu.cn/xszh/list.htm"
      ],
      "target": "/news/xszh"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "www.wfu.edu.cn/50/list.htm"
}
```
