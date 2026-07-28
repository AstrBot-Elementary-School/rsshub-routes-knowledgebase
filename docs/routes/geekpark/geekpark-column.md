# 极客公园 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `geekpark`
- Namespace Name: `极客公园`
- Route Path: `/geekpark/:column?`
- Route Name: `栏目`
- Example: `/geekpark`
- URL: `geekpark.net`
- Language: `_None_`
- Categories: `new-media, popular`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [综合报道](https://www.geekpark.net/column/179)，网址为 `https://www.geekpark.net/column/179`。截取 `https://www.geekpark.net/column/` 到末尾的部分 `179` 作为参数填入，此时路由为 [`/geekpark/179`](https://rsshub.app/geekpark/179)。
:::

| 栏目                                                         | ID                                     |
| ------------------------------------------------------------ | -------------------------------------- |
| [综合报道](https://www.geekpark.net/column/179)              | [179](https://rsshub.app/geekpark/179) |
| [AI 新浪潮观察](https://www.geekpark.net/column/304)         | [304](https://rsshub.app/geekpark/304) |
| [新造车观察](https://www.geekpark.net/column/305)            | [305](https://rsshub.app/geekpark/305) |
| [财报解读](https://www.geekpark.net/column/271)              | [271](https://rsshub.app/geekpark/271) |
| [底稿对话 CEO 系列](https://www.geekpark.net/column/308)     | [308](https://rsshub.app/geekpark/308) |
| [Geek Insight 特稿系列](https://www.geekpark.net/column/306) | [306](https://rsshub.app/geekpark/306) |
| [心科技](https://www.geekpark.net/column/307)                | [307](https://rsshub.app/geekpark/307) |
| [行业资讯](https://www.geekpark.net/column/2)                | [2](https://rsshub.app/geekpark/2)     |

## Parameters
- `column`: 栏目 id，默认为空，即首页资讯，可在对应栏目页 URL 中找到


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
  - `geekpark.net`
- `target`: `/`
### Rule 2
- `source`:
  - `geekpark.net/column/:column?`
### Rule 3
- `title`: `综合报道`
- `source`:
  - `www.geekpark.net/column/179`
- `target`: `/179`
### Rule 4
- `title`: `AI新浪潮观察`
- `source`:
  - `www.geekpark.net/column/304`
- `target`: `/304`
### Rule 5
- `title`: `新造车观察`
- `source`:
  - `www.geekpark.net/column/305`
- `target`: `/305`
### Rule 6
- `title`: `财报解读`
- `source`:
  - `www.geekpark.net/column/271`
- `target`: `/271`
### Rule 7
- `title`: `底稿对话CEO系列`
- `source`:
  - `www.geekpark.net/column/308`
- `target`: `/308`
### Rule 8
- `title`: `Geek Insight 特稿系列`
- `source`:
  - `www.geekpark.net/column/306`
- `target`: `/306`
### Rule 9
- `title`: `心科技`
- `source`:
  - `www.geekpark.net/column/307`
- `target`: `/307`
### Rule 10
- `title`: `行业资讯`
- `source`:
  - `www.geekpark.net/column/2`
- `target`: `/2`

## Raw JSON
```json
{
  "categories": [
    "new-media",
    "popular"
  ],
  "description": "::: tip\n若订阅 [综合报道](https://www.geekpark.net/column/179)，网址为 `https://www.geekpark.net/column/179`。截取 `https://www.geekpark.net/column/` 到末尾的部分 `179` 作为参数填入，此时路由为 [`/geekpark/179`](https://rsshub.app/geekpark/179)。\n:::\n\n| 栏目                                                         | ID                                     |\n| ------------------------------------------------------------ | -------------------------------------- |\n| [综合报道](https://www.geekpark.net/column/179)              | [179](https://rsshub.app/geekpark/179) |\n| [AI 新浪潮观察](https://www.geekpark.net/column/304)         | [304](https://rsshub.app/geekpark/304) |\n| [新造车观察](https://www.geekpark.net/column/305)            | [305](https://rsshub.app/geekpark/305) |\n| [财报解读](https://www.geekpark.net/column/271)              | [271](https://rsshub.app/geekpark/271) |\n| [底稿对话 CEO 系列](https://www.geekpark.net/column/308)     | [308](https://rsshub.app/geekpark/308) |\n| [Geek Insight 特稿系列](https://www.geekpark.net/column/306) | [306](https://rsshub.app/geekpark/306) |\n| [心科技](https://www.geekpark.net/column/307)                | [307](https://rsshub.app/geekpark/307) |\n| [行业资讯](https://www.geekpark.net/column/2)                | [2](https://rsshub.app/geekpark/2)     |",
  "example": "/geekpark",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 1687,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "column": "栏目 id，默认为空，即首页资讯，可在对应栏目页 URL 中找到"
  },
  "path": "/:column?",
  "radar": [
    {
      "source": [
        "geekpark.net"
      ],
      "target": "/"
    },
    {
      "source": [
        "geekpark.net/column/:column?"
      ]
    },
    {
      "source": [
        "www.geekpark.net/column/179"
      ],
      "target": "/179",
      "title": "综合报道"
    },
    {
      "source": [
        "www.geekpark.net/column/304"
      ],
      "target": "/304",
      "title": "AI新浪潮观察"
    },
    {
      "source": [
        "www.geekpark.net/column/305"
      ],
      "target": "/305",
      "title": "新造车观察"
    },
    {
      "source": [
        "www.geekpark.net/column/271"
      ],
      "target": "/271",
      "title": "财报解读"
    },
    {
      "source": [
        "www.geekpark.net/column/308"
      ],
      "target": "/308",
      "title": "底稿对话CEO系列"
    },
    {
      "source": [
        "www.geekpark.net/column/306"
      ],
      "target": "/306",
      "title": "Geek Insight 特稿系列"
    },
    {
      "source": [
        "www.geekpark.net/column/307"
      ],
      "target": "/307",
      "title": "心科技"
    },
    {
      "source": [
        "www.geekpark.net/column/2"
      ],
      "target": "/2",
      "title": "行业资讯"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "极客公园-Geek Things Up! - Powered by RSSHub",
      "errorAt": "2026-05-21T02:24:28.716Z",
      "errorMessage": "[GET] \"https://geekpark.net/\": 403 Forbidden\n[GET] \"https://geekpark.net/\": 403 Forbidden\n502 \n[GET] \"https://geekpark.net/\": 403 Forbidden\nAuthentication failed. Access denied.\n/geekpark\n[GET] \"https://geekpark.net/\": 403 Forbidden\n",
      "id": "57009158758355968",
      "image": "https://imgslim.geekpark.net/geekpark-icon-196-black.png",
      "ownerUserId": null,
      "siteUrl": "https://geekpark.net/",
      "title": "极客公园-Geek Things Up!",
      "type": "feed",
      "url": "rsshub://geekpark"
    },
    {
      "description": "盘点科技圈热点 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60967874020185088",
      "image": "https://imgslim.geekpark.net/uploads/image/file/ea/32/ea326b146aa0b556a65b6139091454a3.jpg",
      "ownerUserId": null,
      "siteUrl": "https://geekpark.net/column/179",
      "title": "综合报道 | 极客公园",
      "type": "feed",
      "url": "rsshub://geekpark/179"
    }
  ],
  "url": "geekpark.net"
}
```
