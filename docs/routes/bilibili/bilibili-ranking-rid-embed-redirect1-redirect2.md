# 哔哩哔哩 bilibili - 排行榜

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/ranking/:rid?/:embed?/:redirect1?/:redirect2?`
- Route Name: `排行榜`
- Example: `/bilibili/ranking/all`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod, hyoban`
- Source Location: `ranking.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `rid`: {"default": "all", "description": "排行榜分区代号或 rid，可在 URL 中找到", "options": [{"label": "全站", "value": "all"}, {"label": "影视", "value": "cinephile"}, {"label": "娱乐", "value": "ent"}, {"label": "音乐", "value": "music"}, {"label": "舞蹈", "value": "dance"}, {"label": "动画", "value": "douga"}, {"label": "鬼畜", "value": "kichiku"}, {"label": "游戏", "value": "game"}, {"label": "知识", "value": "knowledge"}, {"label": "科技数码", "value": "tech"}, {"label": "汽车", "value": "car"}, {"label": "时尚美妆", "value": "fashion"}, {"label": "体育运动", "value": "sports"}, {"label": "美食", "value": "food"}, {"label": "动物", "value": "animal"}]}
- `embed`: 默认为开启内嵌视频，任意值为关闭
- `redirect1`: 留空，用于兼容之前的路由
- `redirect2`: 留空，用于兼容之前的路由


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.bilibili.com/v/popular/rank/:rid`
- `target`: `/ranking/:rid`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/bilibili/ranking/all",
  "heat": 9270,
  "location": "ranking.ts",
  "maintainers": [
    "DIYgod",
    "hyoban"
  ],
  "name": "排行榜",
  "parameters": {
    "embed": "默认为开启内嵌视频，任意值为关闭",
    "redirect1": "留空，用于兼容之前的路由",
    "redirect2": "留空，用于兼容之前的路由",
    "rid": {
      "default": "all",
      "description": "排行榜分区代号或 rid，可在 URL 中找到",
      "options": [
        {
          "label": "全站",
          "value": "all"
        },
        {
          "label": "影视",
          "value": "cinephile"
        },
        {
          "label": "娱乐",
          "value": "ent"
        },
        {
          "label": "音乐",
          "value": "music"
        },
        {
          "label": "舞蹈",
          "value": "dance"
        },
        {
          "label": "动画",
          "value": "douga"
        },
        {
          "label": "鬼畜",
          "value": "kichiku"
        },
        {
          "label": "游戏",
          "value": "game"
        },
        {
          "label": "知识",
          "value": "knowledge"
        },
        {
          "label": "科技数码",
          "value": "tech"
        },
        {
          "label": "汽车",
          "value": "car"
        },
        {
          "label": "时尚美妆",
          "value": "fashion"
        },
        {
          "label": "体育运动",
          "value": "sports"
        },
        {
          "label": "美食",
          "value": "food"
        },
        {
          "label": "动物",
          "value": "animal"
        }
      ]
    }
  },
  "path": "/ranking/:rid?/:embed?/:redirect1?/:redirect2?",
  "radar": [
    {
      "source": [
        "www.bilibili.com/v/popular/rank/:rid"
      ],
      "target": "/ranking/:rid"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "bilibili 排行榜-全站 - Powered by RSSHub",
      "errorAt": "2026-09-01T04:37:23.624Z",
      "errorMessage": "Failed to fetch\n530 \nInvalid RSSHub JSON Feed from 98292582055262208\n[GET] \"https://api.bilibili.com/x/web-interface/view?bvid=BV18s4k6gESU\": 412 Precondition Failed\n[GET] \"https://api.bilibili.com/x/web-interface/view?bvid=BV1o74y6XEcM\": 412 Precondition Failed\n-352\n-352\n-352\nAuthentication failed. Access denied.\n/bilibili/ranking/0\nbrowserType.connect: WebSocket error: ws://browserless:3000/ 429 Too Many Requests\n\r\nToo Many Requests\nCall log:\n  - <ws connecting> ws://browserless:3000/\n  - <ws unexpected response> ws://browserless:3000/ 429 Too Many Requests\n\r\nToo Many Requests\n  - <ws error> ws://browserless:3000/ error WebSocket was closed before the connection was established\n  - <ws connect error> ws://browserless:3000/ WebSocket was closed before the connection was established\n  - <ws disconnected> ws://browserless:3000/ code=1006 reason=\n\n404 \n[GET] \"https://api.bilibili.com/x/web-interface/view?bvid=BV1YNtb66ErA\": 412 \nCould not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /home/sbx_user1051/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nbrowserType.connect: WebSocket error: ws://browserless:3000/ 429 Too Many Requests\n\r\nToo Many Requests\nCall log:\n  - <ws connecting> ws://browserless:3000/\n  - <ws unexpected response> ws://browserless:3000/ 429 Too Many Requests\n\r\nToo Many Requests\n  - <ws error> ws://browserless:3000/ error WebSocket was closed before the connection was established\n  - <ws connect error> ws://browserless:3000/ WebSocket was closed before the connection was established\n  - <ws disconnected> ws://browserless:3000/ code=1006 reason=\n\n-352\n[GET] \"https://api.bilibili.com/x/web-interface/view?bvid=BV1YNtb66ErA\": 412 Precondition Failed\n[GET] \"https://api.bilibili.com/x/web-interface/view?bvid=BV1a3th65EQb\": 412 Precondition Failed\n",
      "id": "78806242632741888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/v/popular/rank/all",
      "title": "bilibili 排行榜-全站",
      "type": "feed",
      "url": "rsshub://bilibili/ranking/0"
    },
    {
      "description": "bilibili 排行榜-知识 - Powered by RSSHub",
      "errorAt": "2026-07-15T05:32:42.190Z",
      "errorMessage": "Failed to fetch\n请求错误\n-352\n请求错误\n",
      "id": "78844164657093632",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/v/popular/rank/knowledge",
      "title": "bilibili 排行榜-知识",
      "type": "feed",
      "url": "rsshub://bilibili/ranking/9"
    }
  ],
  "view": 3
}
```
