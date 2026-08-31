# 湖北大学 - 主页

## Coverage
`index-only`

## Route
- Namespace: `hubu`
- Namespace Name: `湖北大学`
- Route Path: `/hubu/www/:category{.+}?`
- Route Name: `主页`
- Example: `/hubu/www/index/tzgg`
- URL: `hubu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `cijiugechu, nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [通知公告](https://www.hubu.edu.cn/index/tzgg.htm)，网址为 `https://www.hubu.edu.cn/index/tzgg.htm`。截取 `https://www.hubu.edu.cn/` 到末尾 `.htm` 的部分 `index/tzgg` 作为参数填入，此时路由为 [`/hubu/www/index/tzgg`](https://rsshub.app/hubu/www/index/tzgg)。
:::

| 通知公告   | 学术预告   | 综合新闻   | 湖大要闻   | 媒体湖大   |
| ---------- | ---------- | ---------- | ---------- | ---------- |
| index/tzgg | index/xsyg | index/zhxw | index/hdyw | index/mthd |

## Parameters
- `category`: 分类，可在对应分类页 URL 中找到，默认为[通知公告](https://www.hubu.edu.cn/index/tzgg.htm)


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `通知公告`
- `source`:
  - `hubu.edu.cn/index/tzgg.htm`
- `target`: `/www/index/tzgg`
### Rule 2
- `title`: `学术预告`
- `source`:
  - `hubu.edu.cn/index/xsyg.htm`
- `target`: `/www/index/xsyg`
### Rule 3
- `title`: `综合新闻`
- `source`:
  - `hubu.edu.cn/index/zhxw.htm`
- `target`: `/www/index/zhxw`
### Rule 4
- `title`: `湖大要闻`
- `source`:
  - `hubu.edu.cn/index/hdyw.htm`
- `target`: `/www/index/hdyw`
### Rule 5
- `title`: `媒体湖大`
- `source`:
  - `hubu.edu.cn/index/mthd.htm`
- `target`: `/www/index/mthd`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: tip\n若订阅 [通知公告](https://www.hubu.edu.cn/index/tzgg.htm)，网址为 `https://www.hubu.edu.cn/index/tzgg.htm`。截取 `https://www.hubu.edu.cn/` 到末尾 `.htm` 的部分 `index/tzgg` 作为参数填入，此时路由为 [`/hubu/www/index/tzgg`](https://rsshub.app/hubu/www/index/tzgg)。\n:::\n\n| 通知公告   | 学术预告   | 综合新闻   | 湖大要闻   | 媒体湖大   |\n| ---------- | ---------- | ---------- | ---------- | ---------- |\n| index/tzgg | index/xsyg | index/zhxw | index/hdyw | index/mthd |",
  "example": "/hubu/www/index/tzgg",
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
  "location": "index.ts",
  "maintainers": [
    "cijiugechu",
    "nczitzk"
  ],
  "name": "主页",
  "parameters": {
    "category": "分类，可在对应分类页 URL 中找到，默认为[通知公告](https://www.hubu.edu.cn/index/tzgg.htm)"
  },
  "path": "/www/:category{.+}?",
  "radar": [
    {
      "source": [
        "hubu.edu.cn/index/tzgg.htm"
      ],
      "target": "/www/index/tzgg",
      "title": "通知公告"
    },
    {
      "source": [
        "hubu.edu.cn/index/xsyg.htm"
      ],
      "target": "/www/index/xsyg",
      "title": "学术预告"
    },
    {
      "source": [
        "hubu.edu.cn/index/zhxw.htm"
      ],
      "target": "/www/index/zhxw",
      "title": "综合新闻"
    },
    {
      "source": [
        "hubu.edu.cn/index/hdyw.htm"
      ],
      "target": "/www/index/hdyw",
      "title": "湖大要闻"
    },
    {
      "source": [
        "hubu.edu.cn/index/mthd.htm"
      ],
      "target": "/www/index/mthd",
      "title": "媒体湖大"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "hubu.edu.cn"
}
```
