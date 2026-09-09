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
  "heat": 9277,
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
      "errorAt": "2026-09-08T08:50:24.365Z",
      "errorMessage": "Failed query: update \"feeds\" set \"url\" = $1, \"title\" = $2, \"description\" = $3, \"site_url\" = $4, \"checked_at\" = $5, \"refresh_enqueued_at\" = $6, \"last_modified_header\" = $7, \"etag_header\" = $8, \"ttl\" = $9, \"error_message\" = $10, \"error_at\" = $11, \"rsshub_route\" = $12, \"rsshub_namespace\" = $13 where (\"feeds\".\"id\" = $14 and (\"feeds\".\"refresh_enqueued_at\" is null or \"feeds\".\"refresh_enqueued_at\" < $15)) returning \"checked_at\"\nparams: rsshub://bilibili/ranking/0,bilibili 排行榜-全站,bilibili 排行榜-全站 - Powered by RSSHub,https://www.bilibili.com/v/popular/rank/all,2026-09-08T08:50:07.255Z,2026-09-08T08:46:32.082Z,Tue, 08 Sep 2026 08:50:04 GMT,\"19445-YzzHmZwbzTyKK+CGdYSaLTEN4tY\",60,,,/bilibili/ranking/:rid?/:embed?/:redirect1?/:redirect2?,bilibili,78806242632741888,2026-09-08T08:46:32.082Z",
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
      "errorMessage": "请求错误\n-352\n[GET] \"https://api.bilibili.com/x/web-interface/ranking/v2?rid=9&type=all&web_location=333.934\": 412 Precondition Failed\n",
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
