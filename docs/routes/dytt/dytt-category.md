# 电影天堂 - 分类

## Coverage
`index-only`

## Route
- Namespace: `dytt`
- Namespace Name: `电影天堂`
- Route Path: `/dytt/:category{.+}?`
- Route Name: `分类`
- Example: `/dytt/gndy/dyzz`
- URL: `www.dydytt.net`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `junfengP, nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [最新影片](https://www.dydytt.net/html/gndy/dyzz)，网址为 `https://www.dydytt.net/html/gndy/dyzz`，请截取 `https://www.dydytt.net/html/` 到末尾的部分 `gndy/dyzz` 作为 `category` 参数填入，此时目标路由为 [`/dytt/gndy/dyzz`](https://rsshub.app/dytt/gndy/dyzz)。
:::

<details>
<summary>更多分类</summary>

| 分类                                                  | ID                                               |
| ----------------------------------------------------- | ------------------------------------------------ |
| [最新影片](https://www.dydytt.net/html/gndy/dyzz/index.html)      | [gndy/dyzz](https://rsshub.app/dytt/gndy/dyzz)   |
| [经典影片](https://www.dydytt.net/html/gndy/index.html)           | [gndy](https://rsshub.app/dytt/gndy)             |
| [国内电影](https://www.dydytt.net/html/gndy/china/index.html)     | [gndy/china](https://rsshub.app/dytt/gndy/china) |
| [欧美电影](https://www.dydytt.net/html/gndy/oumei/index.html)     | [gndy/oumei](https://rsshub.app/dytt/gndy/oumei) |
| [其它电影](https://www.dydytt.net/html/gndy/rihan/index.html)     | [gndy/rihan](https://rsshub.app/dytt/gndy/rihan) |
| [华语电视](https://www.dydytt.net/html/tv/hytv/index.html)        | [tv/hytv](https://rsshub.app/dytt/tv/hytv)       |
| [欧美电视](https://www.dydytt.net/html/tv/oumeitv/index.html)     | [tv/oumeitv](https://rsshub.app/dytt/tv/oumeitv) |
| [最新综艺](https://www.dydytt.net/html/zongyi2013/index.html)     | [zongyi2013](https://rsshub.app/dytt/zongyi2013) |
| [旧版综艺](https://www.dydytt.net/html/2009zongyi/index.html)     | [2009zongyi](https://rsshub.app/dytt/2009zongyi) |
| [动漫资源](https://www.dydytt.net/html/dongman/index.html)        | [dongman](https://rsshub.app/dytt/dongman)       |
| [旧版游戏](https://www.dydytt.net/html/game/index.html)           | [game](https://rsshub.app/dytt/game)             |
| [游戏下载](https://www.dydytt.net/html/newgame/index.html)        | [newgame](https://rsshub.app/dytt/newgame)       |
| [日韩剧集专区](https://www.dydytt.net/html/tv/rihantv/index.html) | [tv/rihantv](https://rsshub.app/dytt/tv/rihantv) |

</details>

## Parameters
- `category`: {"description": "分类，默认为 `gndy/dyzz`，即最新影片，可在对应分类页 URL 中找到", "options": [{"label": "最新影片", "value": "gndy/dyzz"}, {"label": "经典影片", "value": "gndy"}, {"label": "国内电影", "value": "gndy/china"}, {"label": "欧美电影", "value": "gndy/oumei"}, {"label": "其它电影", "value": "gndy/rihan"}, {"label": "华语电视", "value": "tv/hytv"}, {"label": "欧美电视", "value": "tv/oumeitv"}, {"label": "最新综艺", "value": "zongyi2013"}, {"label": "旧版综艺", "value": "2009zongyi"}, {"label": "动漫资源", "value": "dongman"}, {"label": "旧版游戏", "value": "game"}, {"label": "游戏下载", "value": "newgame"}, {"label": "日韩剧集专区", "value": "tv/rihantv"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `${domain}/index.htm`
  - `www.dydytt.net/html/:category`
### Rule 2
- `title`: `最新影片`
- `source`:
  - `https://www.dydytt.net/html/gndy/dyzz/index.html`
- `target`: `/gndy/dyzz`
### Rule 3
- `title`: `经典影片`
- `source`:
  - `https://www.dydytt.net/html/gndy/index.html`
- `target`: `/gndy`
### Rule 4
- `title`: `国内电影`
- `source`:
  - `https://www.dydytt.net/html/gndy/china/index.html`
- `target`: `/gndy/china`
### Rule 5
- `title`: `欧美电影`
- `source`:
  - `https://www.dydytt.net/html/gndy/oumei/index.html`
- `target`: `/gndy/oumei`
### Rule 6
- `title`: `其它电影`
- `source`:
  - `https://www.dydytt.net/html/gndy/rihan/index.html`
- `target`: `/gndy/rihan`
### Rule 7
- `title`: `华语电视`
- `source`:
  - `https://www.dydytt.net/html/tv/hytv/index.html`
- `target`: `/tv/hytv`
### Rule 8
- `title`: `欧美电视`
- `source`:
  - `https://www.dydytt.net/html/tv/oumeitv/index.html`
- `target`: `/tv/oumeitv`
### Rule 9
- `title`: `最新综艺`
- `source`:
  - `https://www.dydytt.net/html/zongyi2013/index.html`
- `target`: `/zongyi2013`
### Rule 10
- `title`: `旧版综艺`
- `source`:
  - `https://www.dydytt.net/html/2009zongyi/index.html`
- `target`: `/2009zongyi`
### Rule 11
- `title`: `动漫资源`
- `source`:
  - `https://www.dydytt.net/html/dongman/index.html`
- `target`: `/dongman`
### Rule 12
- `title`: `旧版游戏`
- `source`:
  - `https://www.dydytt.net/html/game/index.html`
- `target`: `/game`
### Rule 13
- `title`: `游戏下载`
- `source`:
  - `https://www.dydytt.net/html/newgame/index.html`
- `target`: `/newgame`
### Rule 14
- `title`: `日韩剧集专区`
- `source`:
  - `https://www.dydytt.net/html/tv/rihantv/index.html`
- `target`: `/tv/rihantv`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n若订阅 [最新影片](https://www.dydytt.net/html/gndy/dyzz)，网址为 `https://www.dydytt.net/html/gndy/dyzz`，请截取 `https://www.dydytt.net/html/` 到末尾的部分 `gndy/dyzz` 作为 `category` 参数填入，此时目标路由为 [`/dytt/gndy/dyzz`](https://rsshub.app/dytt/gndy/dyzz)。\n:::\n\n<details>\n<summary>更多分类</summary>\n\n| 分类                                                  | ID                                               |\n| ----------------------------------------------------- | ------------------------------------------------ |\n| [最新影片](https://www.dydytt.net/html/gndy/dyzz/index.html)      | [gndy/dyzz](https://rsshub.app/dytt/gndy/dyzz)   |\n| [经典影片](https://www.dydytt.net/html/gndy/index.html)           | [gndy](https://rsshub.app/dytt/gndy)             |\n| [国内电影](https://www.dydytt.net/html/gndy/china/index.html)     | [gndy/china](https://rsshub.app/dytt/gndy/china) |\n| [欧美电影](https://www.dydytt.net/html/gndy/oumei/index.html)     | [gndy/oumei](https://rsshub.app/dytt/gndy/oumei) |\n| [其它电影](https://www.dydytt.net/html/gndy/rihan/index.html)     | [gndy/rihan](https://rsshub.app/dytt/gndy/rihan) |\n| [华语电视](https://www.dydytt.net/html/tv/hytv/index.html)        | [tv/hytv](https://rsshub.app/dytt/tv/hytv)       |\n| [欧美电视](https://www.dydytt.net/html/tv/oumeitv/index.html)     | [tv/oumeitv](https://rsshub.app/dytt/tv/oumeitv) |\n| [最新综艺](https://www.dydytt.net/html/zongyi2013/index.html)     | [zongyi2013](https://rsshub.app/dytt/zongyi2013) |\n| [旧版综艺](https://www.dydytt.net/html/2009zongyi/index.html)     | [2009zongyi](https://rsshub.app/dytt/2009zongyi) |\n| [动漫资源](https://www.dydytt.net/html/dongman/index.html)        | [dongman](https://rsshub.app/dytt/dongman)       |\n| [旧版游戏](https://www.dydytt.net/html/game/index.html)           | [game](https://rsshub.app/dytt/game)             |\n| [游戏下载](https://www.dydytt.net/html/newgame/index.html)        | [newgame](https://rsshub.app/dytt/newgame)       |\n| [日韩剧集专区](https://www.dydytt.net/html/tv/rihantv/index.html) | [tv/rihantv](https://rsshub.app/dytt/tv/rihantv) |\n\n</details>\n",
  "example": "/dytt/gndy/dyzz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 241,
  "location": "index.ts",
  "maintainers": [
    "junfengP",
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": {
      "description": "分类，默认为 `gndy/dyzz`，即最新影片，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "最新影片",
          "value": "gndy/dyzz"
        },
        {
          "label": "经典影片",
          "value": "gndy"
        },
        {
          "label": "国内电影",
          "value": "gndy/china"
        },
        {
          "label": "欧美电影",
          "value": "gndy/oumei"
        },
        {
          "label": "其它电影",
          "value": "gndy/rihan"
        },
        {
          "label": "华语电视",
          "value": "tv/hytv"
        },
        {
          "label": "欧美电视",
          "value": "tv/oumeitv"
        },
        {
          "label": "最新综艺",
          "value": "zongyi2013"
        },
        {
          "label": "旧版综艺",
          "value": "2009zongyi"
        },
        {
          "label": "动漫资源",
          "value": "dongman"
        },
        {
          "label": "旧版游戏",
          "value": "game"
        },
        {
          "label": "游戏下载",
          "value": "newgame"
        },
        {
          "label": "日韩剧集专区",
          "value": "tv/rihantv"
        }
      ]
    }
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "${domain}/index.htm",
        "www.dydytt.net/html/:category"
      ]
    },
    {
      "source": [
        "https://www.dydytt.net/html/gndy/dyzz/index.html"
      ],
      "target": "/gndy/dyzz",
      "title": "最新影片"
    },
    {
      "source": [
        "https://www.dydytt.net/html/gndy/index.html"
      ],
      "target": "/gndy",
      "title": "经典影片"
    },
    {
      "source": [
        "https://www.dydytt.net/html/gndy/china/index.html"
      ],
      "target": "/gndy/china",
      "title": "国内电影"
    },
    {
      "source": [
        "https://www.dydytt.net/html/gndy/oumei/index.html"
      ],
      "target": "/gndy/oumei",
      "title": "欧美电影"
    },
    {
      "source": [
        "https://www.dydytt.net/html/gndy/rihan/index.html"
      ],
      "target": "/gndy/rihan",
      "title": "其它电影"
    },
    {
      "source": [
        "https://www.dydytt.net/html/tv/hytv/index.html"
      ],
      "target": "/tv/hytv",
      "title": "华语电视"
    },
    {
      "source": [
        "https://www.dydytt.net/html/tv/oumeitv/index.html"
      ],
      "target": "/tv/oumeitv",
      "title": "欧美电视"
    },
    {
      "source": [
        "https://www.dydytt.net/html/zongyi2013/index.html"
      ],
      "target": "/zongyi2013",
      "title": "最新综艺"
    },
    {
      "source": [
        "https://www.dydytt.net/html/2009zongyi/index.html"
      ],
      "target": "/2009zongyi",
      "title": "旧版综艺"
    },
    {
      "source": [
        "https://www.dydytt.net/html/dongman/index.html"
      ],
      "target": "/dongman",
      "title": "动漫资源"
    },
    {
      "source": [
        "https://www.dydytt.net/html/game/index.html"
      ],
      "target": "/game",
      "title": "旧版游戏"
    },
    {
      "source": [
        "https://www.dydytt.net/html/newgame/index.html"
      ],
      "target": "/newgame",
      "title": "游戏下载"
    },
    {
      "source": [
        "https://www.dydytt.net/html/tv/rihantv/index.html"
      ],
      "target": "/tv/rihantv",
      "title": "日韩剧集专区"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "迅雷电影下载,迅雷电视剧下载,迅雷综艺下载,最好的电影下载网站 - Powered by RSSHub",
      "errorAt": "2025-05-23T15:59:29.973Z",
      "errorMessage": "Authentication failed. Access denied.\n/dytt/gndy/dyzz\n[GET] \"https://www.dydytt.net/html/gndy/dyzz\": <no response> fetch failed\n[GET] \"https://www.dydytt.net/html/gndy/dyzz\": <no response> fetch failed (getaddrinfo EAI_AGAIN www.dydytt.net)\n",
      "id": "106371402907978752",
      "image": "https://www.dydytt.net/images/logo.gif",
      "ownerUserId": null,
      "siteUrl": "https://www.dydytt.net/html/gndy/dyzz",
      "title": "电影 / 最新电影_第一电影天堂",
      "type": "feed",
      "url": "rsshub://dytt/gndy/dyzz"
    },
    {
      "description": "迅雷电影下载,迅雷电视剧下载,迅雷综艺下载,最好的电影下载网站 - Powered by RSSHub",
      "errorAt": "2025-05-23T13:26:02.685Z",
      "errorMessage": "[GET] \"https://www.dydytt.net/html/gndy/dyzz\": <no response> fetch failed (getaddrinfo EAI_AGAIN www.dydytt.net)\n[GET] \"https://www.dydytt.net/html/gndy/dyzz\": <no response> fetch failed (getaddrinfo ENOTFOUND www.dydytt.net)\n[GET] \"https://www.dydytt.net/html/gndy/dyzz\": <no response> fetch failed (getaddrinfo EAI_AGAIN www.dydytt.net)\n",
      "id": "95293305985206272",
      "image": "https://www.dydytt.net/images/logo.gif",
      "ownerUserId": null,
      "siteUrl": "https://www.dydytt.net/html/gndy/dyzz",
      "title": "电影 / 最新电影_第一电影天堂",
      "type": "feed",
      "url": "rsshub://dytt"
    }
  ],
  "url": "www.dydytt.net",
  "view": 0
}
```
