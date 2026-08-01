# 微博 - 超话

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/weibo/super_index/:id/:type?/:routeParams?`
- Route Name: `超话`
- Example: `/weibo/super_index/1008084989d223732bf6f02f75ea30efad58a9/sort_time`
- URL: `weibo.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `zengxs, Rongronggg9`
- Source Location: `super-index.ts`
- Source Module: `_None_`

## Description
| type       | 备注             |
| ---------- | ---------------- |
| soul       | 精华             |
| video      | 视频（暂不支持） |
| album      | 相册（暂不支持） |
| hot\_sort  | 热门             |
| sort\_time | 最新帖子         |
| feed       | 最新评论         |

## Parameters
- `id`: 超话ID
- `type`: 类型：见下表
- `routeParams`: 额外参数；请参阅上面的说明和表格


## Features
- `requireConfig`: [{"description": "", "name": "WEIBO_COOKIES", "optional": true}]
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `weibo.com/p/:id/super_index`
- `target`: `/super_index/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "| type       | 备注             |\n| ---------- | ---------------- |\n| soul       | 精华             |\n| video      | 视频（暂不支持） |\n| album      | 相册（暂不支持） |\n| hot\\_sort  | 热门             |\n| sort\\_time | 最新帖子         |\n| feed       | 最新评论         |",
  "example": "/weibo/super_index/1008084989d223732bf6f02f75ea30efad58a9/sort_time",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "WEIBO_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 95,
  "location": "super-index.ts",
  "maintainers": [
    "zengxs",
    "Rongronggg9"
  ],
  "name": "超话",
  "parameters": {
    "id": "超话ID",
    "routeParams": "额外参数；请参阅上面的说明和表格",
    "type": "类型：见下表"
  },
  "path": "/super_index/:id/:type?/:routeParams?",
  "radar": [
    {
      "source": [
        "weibo.com/p/:id/super_index"
      ],
      "target": "/super_index/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "#elizabetholsen# 的超话 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "96189998246796288",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://weibo.com/p/1008080894c105ac1b0e2f37cf6ed086d5dbb3/super_index",
      "title": "微博超话 - elizabetholsen",
      "type": "feed",
      "url": "rsshub://weibo/super_index/1008080894c105ac1b0e2f37cf6ed086d5dbb3"
    },
    {
      "description": "#井川里予# 的超话 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "122613879912649728",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://weibo.com/p/100808962d1e482e947f1e20fd0981358db42f/super_index",
      "title": "微博超话 - 井川里予",
      "type": "feed",
      "url": "rsshub://weibo/super_index/100808962d1e482e947f1e20fd0981358db42f/sort_time"
    }
  ]
}
```
