# 游侠网 - 大侠号

## Coverage
`index-only`

## Route
- Namespace: `ali213`
- Namespace Name: `游侠网`
- Route Path: `/ali213/zl/:category?`
- Route Name: `大侠号`
- Example: `/ali213/zl`
- URL: `www.ali213.net`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `zl.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [游戏](https://www.ali213.net/news/zl/game/)，网址为 `https://www.ali213.net/news/zl/game/`，请截取 `https://www.ali213.net/news/zl/` 到末尾 `/` 的部分 `game` 作为 `category` 参数填入，此时目标路由为 [`/ali213/zl/game`](https://rsshub.app/ali213/zl/game)。
:::

| 首页                                     | 游戏                                         | 动漫                                           | 影视                                           | 娱乐                                           |
| ---------------------------------------- | -------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- |
| [index](https://www.ali213.net/news/zl/) | [game](https://www.ali213.net/news/zl/game/) | [comic](https://www.ali213.net/news/zl/comic/) | [movie](https://www.ali213.net/news/zl/movie/) | [amuse](https://www.ali213.net/news/zl/amuse/) |

## Parameters
- `category`: 分类，默认为首页，可在对应分类页 URL 中找到


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
  - `www.ali213.net/news/zl/:category`
### Rule 2
- `title`: `首页`
- `source`:
  - `www.ali213.net/news/zl/`
- `target`: `/zl`
### Rule 3
- `title`: `游戏`
- `source`:
  - `www.ali213.net/news/zl/game/`
- `target`: `/zl/game`
### Rule 4
- `title`: `动漫`
- `source`:
  - `www.ali213.net/news/zl/comic/`
- `target`: `/zl/comic`
### Rule 5
- `title`: `影视`
- `source`:
  - `www.ali213.net/news/zl/movie/`
- `target`: `/zl/movie`
### Rule 6
- `title`: `娱乐`
- `source`:
  - `www.ali213.net/news/zl/amuse/`
- `target`: `/zl/amuse`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n若订阅 [游戏](https://www.ali213.net/news/zl/game/)，网址为 `https://www.ali213.net/news/zl/game/`，请截取 `https://www.ali213.net/news/zl/` 到末尾 `/` 的部分 `game` 作为 `category` 参数填入，此时目标路由为 [`/ali213/zl/game`](https://rsshub.app/ali213/zl/game)。\n:::\n\n| 首页                                     | 游戏                                         | 动漫                                           | 影视                                           | 娱乐                                           |\n| ---------------------------------------- | -------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- |\n| [index](https://www.ali213.net/news/zl/) | [game](https://www.ali213.net/news/zl/game/) | [comic](https://www.ali213.net/news/zl/comic/) | [movie](https://www.ali213.net/news/zl/movie/) | [amuse](https://www.ali213.net/news/zl/amuse/) |",
  "example": "/ali213/zl",
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
  "location": "zl.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "大侠号",
  "parameters": {
    "category": "分类，默认为首页，可在对应分类页 URL 中找到"
  },
  "path": "/zl/:category?",
  "radar": [
    {
      "source": [
        "www.ali213.net/news/zl/:category"
      ]
    },
    {
      "source": [
        "www.ali213.net/news/zl/"
      ],
      "target": "/zl",
      "title": "首页"
    },
    {
      "source": [
        "www.ali213.net/news/zl/game/"
      ],
      "target": "/zl/game",
      "title": "游戏"
    },
    {
      "source": [
        "www.ali213.net/news/zl/comic/"
      ],
      "target": "/zl/comic",
      "title": "动漫"
    },
    {
      "source": [
        "www.ali213.net/news/zl/movie/"
      ],
      "target": "/zl/movie",
      "title": "影视"
    },
    {
      "source": [
        "www.ali213.net/news/zl/amuse/"
      ],
      "target": "/zl/amuse",
      "title": "娱乐"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "游侠网资讯中心是国内资深、全面的单机新闻发布站点之一，24小时报道国内、全球单机新闻以及各类游戏相关资讯！ - Powered by RSSHub",
      "errorAt": "2026-07-04T09:02:02.124Z",
      "errorMessage": "[GET] \"https://mp.ali213.net/ajax/newslist?type=new\": <no response> fetch failed (Connect Timeout Error (attempted address: mp.ali213.net:443, timeout: 10000ms))\n",
      "id": "122926847767308288",
      "image": "https://www.ali213.net/news/images/dxhlogo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.ali213.net/news/zl/",
      "title": "大侠号_单机游戏新闻_游侠网",
      "type": "feed",
      "url": "rsshub://ali213/zl"
    }
  ],
  "url": "www.ali213.net",
  "view": 0
}
```
