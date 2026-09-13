# 游侠网 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `ali213`
- Namespace Name: `游侠网`
- Route Path: `/ali213/news/:category?`
- Route Name: `资讯`
- Example: `/ali213/news/new`
- URL: `www.ali213.net`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [游戏资讯](https://www.ali213.net/news/game/)，网址为 `https://www.ali213.net/news/game/`，请截取 `https://www.ali213.net/news/` 到末尾 `/` 的部分 `game` 作为 `category` 参数填入，此时目标路由为 [`/ali213/news/game`](https://rsshub.app/ali213/news/game)。
:::

| 分类名称 | 分类 ID |
| -------- | ------- |
| 最新资讯 | new     |
| 评测     | pingce  |
| 游戏     | game    |
| 动漫     | comic   |
| 影视     | movie   |
| 科技     | tech    |
| 电竞     | esports |
| 娱乐     | amuse   |
| 手游     | mobile  |

## Parameters
- `category`: 分类，默认为 `new`，即最新资讯，可在对应分类页 URL 中找到


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
  - `www.ali213.net/news/:category`
### Rule 2
- `title`: `最新资讯`
- `source`:
  - `www.ali213.net/news/new`
- `target`: `/news/new`
### Rule 3
- `title`: `评测`
- `source`:
  - `www.ali213.net/news/pingce`
- `target`: `/news/pingce`
### Rule 4
- `title`: `游戏`
- `source`:
  - `www.ali213.net/news/game`
- `target`: `/news/game`
### Rule 5
- `title`: `动漫`
- `source`:
  - `www.ali213.net/news/comic`
- `target`: `/news/comic`
### Rule 6
- `title`: `影视`
- `source`:
  - `www.ali213.net/news/movie`
- `target`: `/news/movie`
### Rule 7
- `title`: `科技`
- `source`:
  - `www.ali213.net/news/tech`
- `target`: `/news/tech`
### Rule 8
- `title`: `电竞`
- `source`:
  - `www.ali213.net/news/esports`
- `target`: `/news/esports`
### Rule 9
- `title`: `娱乐`
- `source`:
  - `www.ali213.net/news/amuse`
- `target`: `/news/amuse`
### Rule 10
- `title`: `手游`
- `source`:
  - `www.ali213.net/news/mobile`
- `target`: `/news/mobile`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n若订阅 [游戏资讯](https://www.ali213.net/news/game/)，网址为 `https://www.ali213.net/news/game/`，请截取 `https://www.ali213.net/news/` 到末尾 `/` 的部分 `game` 作为 `category` 参数填入，此时目标路由为 [`/ali213/news/game`](https://rsshub.app/ali213/news/game)。\n:::\n\n| 分类名称 | 分类 ID |\n| -------- | ------- |\n| 最新资讯 | new     |\n| 评测     | pingce  |\n| 游戏     | game    |\n| 动漫     | comic   |\n| 影视     | movie   |\n| 科技     | tech    |\n| 电竞     | esports |\n| 娱乐     | amuse   |\n| 手游     | mobile  |",
  "example": "/ali213/news/new",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 71,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "资讯",
  "parameters": {
    "category": "分类，默认为 `new`，即最新资讯，可在对应分类页 URL 中找到"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "www.ali213.net/news/:category"
      ]
    },
    {
      "source": [
        "www.ali213.net/news/new"
      ],
      "target": "/news/new",
      "title": "最新资讯"
    },
    {
      "source": [
        "www.ali213.net/news/pingce"
      ],
      "target": "/news/pingce",
      "title": "评测"
    },
    {
      "source": [
        "www.ali213.net/news/game"
      ],
      "target": "/news/game",
      "title": "游戏"
    },
    {
      "source": [
        "www.ali213.net/news/comic"
      ],
      "target": "/news/comic",
      "title": "动漫"
    },
    {
      "source": [
        "www.ali213.net/news/movie"
      ],
      "target": "/news/movie",
      "title": "影视"
    },
    {
      "source": [
        "www.ali213.net/news/tech"
      ],
      "target": "/news/tech",
      "title": "科技"
    },
    {
      "source": [
        "www.ali213.net/news/esports"
      ],
      "target": "/news/esports",
      "title": "电竞"
    },
    {
      "source": [
        "www.ali213.net/news/amuse"
      ],
      "target": "/news/amuse",
      "title": "娱乐"
    },
    {
      "source": [
        "www.ali213.net/news/mobile"
      ],
      "target": "/news/mobile",
      "title": "手游"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "最新资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "88780205724889088",
      "image": "https://www.ali213.net/news/images/ali213_app_big.png",
      "ownerUserId": null,
      "siteUrl": "https://www.ali213.net/news/new/",
      "title": "游侠网 - 最新资讯",
      "type": "feed",
      "url": "rsshub://ali213/news/new"
    },
    {
      "description": "最新资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "89124148162380800",
      "image": "https://www.ali213.net/news/images/ali213_app_big.png",
      "ownerUserId": null,
      "siteUrl": "https://www.ali213.net/news/new/",
      "title": "游侠网 - 最新资讯",
      "type": "feed",
      "url": "rsshub://ali213/news"
    }
  ],
  "url": "www.ali213.net",
  "view": 0
}
```
