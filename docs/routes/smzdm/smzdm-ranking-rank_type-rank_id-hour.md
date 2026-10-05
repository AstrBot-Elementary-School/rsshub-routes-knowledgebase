# 什么值得买 - 排行榜

## Coverage
`index-only`

## Route
- Namespace: `smzdm`
- Namespace Name: `什么值得买`
- Route Path: `/smzdm/ranking/:rank_type/:rank_id/:hour`
- Route Name: `排行榜`
- Example: `/smzdm/ranking/pinlei/11/3`
- URL: `post.smzdm.com`
- Language: `_None_`
- Categories: `shopping, popular`
- Maintainers: `DIYgod`
- Source Location: `ranking.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `rank_type`: {"description": "榜单类型", "options": [{"label": "好价品类榜", "value": "pinlei"}, {"label": "好价电商榜", "value": "dianshang"}, {"label": "海淘 TOP 榜", "value": "haitao"}, {"label": "好文排行榜", "value": "haowen"}, {"label": "好物排行榜", "value": "haowu"}]}
- `rank_id`: {"description": "榜单ID", "options": [{"label": "好价品类榜-全部", "value": "11"}, {"label": "好价品类榜-食品生鲜", "value": "12"}, {"label": "好价品类榜-电脑数码", "value": "13"}, {"label": "好价品类榜-运动户外", "value": "14"}, {"label": "好价品类榜-家用电器", "value": "15"}, {"label": "好价品类榜-白菜", "value": "17"}, {"label": "好价品类榜-服饰鞋包", "value": "74"}, {"label": "好价品类榜-日用百货", "value": "75"}, {"label": "好价电商榜-券活动", "value": "24"}, {"label": "好价电商榜-京东", "value": "23"}, {"label": "好价电商榜-天猫", "value": "25"}, {"label": "好价电商榜-亚马逊中国", "value": "26"}, {"label": "好价电商榜-国美在线", "value": "27"}, {"label": "好价电商榜-苏宁易购", "value": "28"}, {"label": "好价电商榜-网易", "value": "29"}, {"label": "好价电商榜-西集网", "value": "30"}, {"label": "好价电商榜-美国亚马逊", "value": "31"}, {"label": "好价电商榜-日本亚马逊", "value": "32"}, {"label": "好价电商榜-ebay", "value": "33"}, {"label": "海淘 TOP 榜-全部", "value": "39"}, {"label": "海淘 TOP 榜-海外直邮", "value": "34"}, {"label": "海淘 TOP 榜-美国榜", "value": "35"}, {"label": "海淘 TOP 榜-欧洲榜", "value": "36"}, {"label": "海淘 TOP 榜-澳新榜", "value": "37"}, {"label": "海淘 TOP 榜-亚洲榜", "value": "38"}, {"label": "海淘 TOP 榜-晒物榜", "value": "hsw"}, {"label": "好文排行榜-原创", "value": "yc"}, {"label": "好文排行榜-资讯", "value": "zx"}, {"label": "好物排行榜-新晋榜", "value": "hwall"}, {"label": "好物排行榜-消费众测", "value": "zc"}, {"label": "好物排行榜-新锐品牌", "value": "nb"}, {"label": "好物排行榜-好物榜单", "value": "hw"}]}
- `hour`: {"description": "时间跨度", "options": [{"label": "3 小时", "value": "3"}, {"label": "12 小时", "value": "12"}, {"label": "24 小时", "value": "24"}]}


## Features
- `requireConfig`: [{"description": "什么值得买登录后的 Cookie 值", "name": "SMZDM_COOKIE"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "shopping",
    "popular"
  ],
  "example": "/smzdm/ranking/pinlei/11/3",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "什么值得买登录后的 Cookie 值",
        "name": "SMZDM_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5043,
  "location": "ranking.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "排行榜",
  "parameters": {
    "hour": {
      "description": "时间跨度",
      "options": [
        {
          "label": "3 小时",
          "value": "3"
        },
        {
          "label": "12 小时",
          "value": "12"
        },
        {
          "label": "24 小时",
          "value": "24"
        }
      ]
    },
    "rank_id": {
      "description": "榜单ID",
      "options": [
        {
          "label": "好价品类榜-全部",
          "value": "11"
        },
        {
          "label": "好价品类榜-食品生鲜",
          "value": "12"
        },
        {
          "label": "好价品类榜-电脑数码",
          "value": "13"
        },
        {
          "label": "好价品类榜-运动户外",
          "value": "14"
        },
        {
          "label": "好价品类榜-家用电器",
          "value": "15"
        },
        {
          "label": "好价品类榜-白菜",
          "value": "17"
        },
        {
          "label": "好价品类榜-服饰鞋包",
          "value": "74"
        },
        {
          "label": "好价品类榜-日用百货",
          "value": "75"
        },
        {
          "label": "好价电商榜-券活动",
          "value": "24"
        },
        {
          "label": "好价电商榜-京东",
          "value": "23"
        },
        {
          "label": "好价电商榜-天猫",
          "value": "25"
        },
        {
          "label": "好价电商榜-亚马逊中国",
          "value": "26"
        },
        {
          "label": "好价电商榜-国美在线",
          "value": "27"
        },
        {
          "label": "好价电商榜-苏宁易购",
          "value": "28"
        },
        {
          "label": "好价电商榜-网易",
          "value": "29"
        },
        {
          "label": "好价电商榜-西集网",
          "value": "30"
        },
        {
          "label": "好价电商榜-美国亚马逊",
          "value": "31"
        },
        {
          "label": "好价电商榜-日本亚马逊",
          "value": "32"
        },
        {
          "label": "好价电商榜-ebay",
          "value": "33"
        },
        {
          "label": "海淘 TOP 榜-全部",
          "value": "39"
        },
        {
          "label": "海淘 TOP 榜-海外直邮",
          "value": "34"
        },
        {
          "label": "海淘 TOP 榜-美国榜",
          "value": "35"
        },
        {
          "label": "海淘 TOP 榜-欧洲榜",
          "value": "36"
        },
        {
          "label": "海淘 TOP 榜-澳新榜",
          "value": "37"
        },
        {
          "label": "海淘 TOP 榜-亚洲榜",
          "value": "38"
        },
        {
          "label": "海淘 TOP 榜-晒物榜",
          "value": "hsw"
        },
        {
          "label": "好文排行榜-原创",
          "value": "yc"
        },
        {
          "label": "好文排行榜-资讯",
          "value": "zx"
        },
        {
          "label": "好物排行榜-新晋榜",
          "value": "hwall"
        },
        {
          "label": "好物排行榜-消费众测",
          "value": "zc"
        },
        {
          "label": "好物排行榜-新锐品牌",
          "value": "nb"
        },
        {
          "label": "好物排行榜-好物榜单",
          "value": "hw"
        }
      ]
    },
    "rank_type": {
      "description": "榜单类型",
      "options": [
        {
          "label": "好价品类榜",
          "value": "pinlei"
        },
        {
          "label": "好价电商榜",
          "value": "dianshang"
        },
        {
          "label": "海淘 TOP 榜",
          "value": "haitao"
        },
        {
          "label": "好文排行榜",
          "value": "haowen"
        },
        {
          "label": "好物排行榜",
          "value": "haowu"
        }
      ]
    }
  },
  "path": "/ranking/:rank_type/:rank_id/:hour",
  "topFeeds": [
    {
      "description": "什么值得买好价品类榜-好价品类榜-全部-3小时 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42006425715388416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.smzdm.com/top/",
      "title": "什么值得买好价品类榜-好价品类榜-全部-3小时",
      "type": "feed",
      "url": "rsshub://smzdm/ranking/pinlei/11/3"
    },
    {
      "description": "什么值得买好价品类榜-好价品类榜-全部-24小时 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41356126035548160",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.smzdm.com/top/",
      "title": "什么值得买好价品类榜-好价品类榜-全部-24小时",
      "type": "feed",
      "url": "rsshub://smzdm/ranking/pinlei/11/24"
    }
  ],
  "view": 5
}
```
