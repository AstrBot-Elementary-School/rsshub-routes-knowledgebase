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
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "广东外语外贸大学新闻与传播学院官网-新闻中心 - Powered by RSSHub",
      "errorAt": "2026-08-13T18:45:17.884Z",
      "errorMessage": "[GET] \"https://xwxy.gdufs.edu.cn/xwzx/%E7%AC%AC%E4%BA%8C%E6%9C%9F%E5%B9%BF%E4%B8%9C%E7%9C%81%E9%AB%98%E6%A0%A1%E9%A9%AC%E5%85%8B%E6%80%9D%E4%B8%BB%E4%B9%89%E6%96%B0%E9%97%BB%E8%A7%82%E9%AA%A8%E5%B9%B2%E5%B8%88%E8%B5%84%E7%A0%94%E4%BF%AE%E7%8F%AD%E4%B8%BE%E5%8A%9E\": 400 Bad Request\n",
      "id": "192033567747366912",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xwxy.gdufs.edu.cn/xwzx/xyxw.htm",
      "title": "广外新传学院-学院新闻",
      "type": "feed",
      "url": "rsshub://gdufs/xwxy/news"
    },
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
    }
  ],
  "url": "xwxy.gdufs.edu.cn"
}
```
