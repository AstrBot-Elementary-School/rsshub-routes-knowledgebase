# 广东外语外贸大学 - 新闻学院-新闻中心

## Coverage
`index-only`

## Route
- Namespace: `gdufs`
- Namespace Name: `广东外语外贸大学`
- Route Path: `/gdufs/xwxy/:category?`
- Route Name: `新闻学院-新闻中心`
- Example: `/gdufs/xwxy/news`
- URL: `xwxy.gdufs.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `gz4zzxc`
- Source Location: `xwxy/index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"description": "分类，默认为 `news`", "options": [{"label": "学院新闻", "value": "news"}, {"label": "通知", "value": "notices"}, {"label": "公告", "value": "announcements"}, {"label": "媒体聚焦", "value": "media"}]}


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
- `source`:
  - `xwxy.gdufs.edu.cn/xwzx/xyxw`
  - `xwxy.gdufs.edu.cn/`
- `target`: `/xwxy/news`
### Rule 2
- `source`:
  - `xwxy.gdufs.edu.cn/xwzx/tzgg/tz`
- `target`: `/xwxy/notices`
### Rule 3
- `source`:
  - `xwxy.gdufs.edu.cn/xwzx/tzgg/gg`
- `target`: `/xwxy/announcements`
### Rule 4
- `source`:
  - `xwxy.gdufs.edu.cn/xwzx/mtjj`
- `target`: `/xwxy/media`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/gdufs/xwxy/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 4,
  "location": "xwxy/index.ts",
  "maintainers": [
    "gz4zzxc"
  ],
  "name": "新闻学院-新闻中心",
  "parameters": {
    "category": {
      "description": "分类，默认为 `news`",
      "options": [
        {
          "label": "学院新闻",
          "value": "news"
        },
        {
          "label": "通知",
          "value": "notices"
        },
        {
          "label": "公告",
          "value": "announcements"
        },
        {
          "label": "媒体聚焦",
          "value": "media"
        }
      ]
    }
  },
  "path": "/xwxy/:category?",
  "radar": [
    {
      "source": [
        "xwxy.gdufs.edu.cn/xwzx/xyxw",
        "xwxy.gdufs.edu.cn/"
      ],
      "target": "/xwxy/news"
    },
    {
      "source": [
        "xwxy.gdufs.edu.cn/xwzx/tzgg/tz"
      ],
      "target": "/xwxy/notices"
    },
    {
      "source": [
        "xwxy.gdufs.edu.cn/xwzx/tzgg/gg"
      ],
      "target": "/xwxy/announcements"
    },
    {
      "source": [
        "xwxy.gdufs.edu.cn/xwzx/mtjj"
      ],
      "target": "/xwxy/media"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "广东外语外贸大学新闻与传播学院官网-新闻中心 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "192034066149117952",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xwxy.gdufs.edu.cn/xwzx/mtjj.htm",
      "title": "广外新传学院-媒体聚焦",
      "type": "feed",
      "url": "rsshub://gdufs/xwxy/media"
    },
    {
      "description": "广东外语外贸大学新闻与传播学院官网-新闻中心 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "192033567747366912",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xwxy.gdufs.edu.cn/xwzx/xyxw.htm",
      "title": "广外新传学院-学院新闻",
      "type": "feed",
      "url": "rsshub://gdufs/xwxy/news"
    }
  ],
  "url": "xwxy.gdufs.edu.cn"
}
```
