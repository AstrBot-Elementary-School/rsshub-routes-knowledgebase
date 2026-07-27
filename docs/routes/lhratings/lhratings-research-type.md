# 联合资信评估股份有限公司 - 研究报告

## Coverage
`index-only`

## Route
- Namespace: `lhratings`
- Namespace Name: `联合资信评估股份有限公司`
- Route Path: `/lhratings/research/:type?`
- Route Name: `研究报告`
- Example: `/lhratings/research/92`
- URL: `www.lhratings.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `research.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [宏观经济](https://www.lhratings.com/research.html?type=92)，网址为 `https://www.lhratings.com/research.html?type=92`，请截取 `https://www.lhratings.com/research.html?type=` 到末尾的部分 `92` 作为 `type` 参数填入，此时目标路由为 [`/lhratings/research/92`](https://rsshub.app/lhratings/research/92)。
:::

| 宏观经济 | 债券市场 | 行业研究 | 每日资讯 | 其他 |
| -------- | -------- | -------- | -------- | ---- |
| 92       | 93       | 94       | 95       | 96   |

## Parameters
- `type`: 分类，默认为 `92`，即宏观经济，可在对应分类页 URL 中找到


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
  - `www.lhratings.com/research.html`
### Rule 2
- `title`: `宏观经济`
- `source`:
  - `www.lhratings.com/research.html?type=92`
- `target`: `/research/92`
### Rule 3
- `title`: `债券市场`
- `source`:
  - `www.lhratings.com/research.html?type=93`
- `target`: `/research/93`
### Rule 4
- `title`: `行业研究`
- `source`:
  - `www.lhratings.com/research.html?type=94`
- `target`: `/research/94`
### Rule 5
- `title`: `每日资讯`
- `source`:
  - `www.lhratings.com/research.html?type=95`
- `target`: `/research/95`
### Rule 6
- `title`: `其他`
- `source`:
  - `www.lhratings.com/research.html?type=96`
- `target`: `/research/96`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n若订阅 [宏观经济](https://www.lhratings.com/research.html?type=92)，网址为 `https://www.lhratings.com/research.html?type=92`，请截取 `https://www.lhratings.com/research.html?type=` 到末尾的部分 `92` 作为 `type` 参数填入，此时目标路由为 [`/lhratings/research/92`](https://rsshub.app/lhratings/research/92)。\n:::\n\n| 宏观经济 | 债券市场 | 行业研究 | 每日资讯 | 其他 |\n| -------- | -------- | -------- | -------- | ---- |\n| 92       | 93       | 94       | 95       | 96   |",
  "example": "/lhratings/research/92",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 30,
  "location": "research.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "研究报告",
  "parameters": {
    "type": "分类，默认为 `92`，即宏观经济，可在对应分类页 URL 中找到"
  },
  "path": "/research/:type?",
  "radar": [
    {
      "source": [
        "www.lhratings.com/research.html"
      ]
    },
    {
      "source": [
        "www.lhratings.com/research.html?type=92"
      ],
      "target": "/research/92",
      "title": "宏观经济"
    },
    {
      "source": [
        "www.lhratings.com/research.html?type=93"
      ],
      "target": "/research/93",
      "title": "债券市场"
    },
    {
      "source": [
        "www.lhratings.com/research.html?type=94"
      ],
      "target": "/research/94",
      "title": "行业研究"
    },
    {
      "source": [
        "www.lhratings.com/research.html?type=95"
      ],
      "target": "/research/95",
      "title": "每日资讯"
    },
    {
      "source": [
        "www.lhratings.com/research.html?type=96"
      ],
      "target": "/research/96",
      "title": "其他"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "行业研究 - Powered by RSSHub",
      "errorAt": "2026-07-06T13:36:00.029Z",
      "errorMessage": "[GET] \"https://www.lhratings.com/research.html?type=3\": 404 Not Found\n",
      "id": "104824308798705664",
      "image": "https://www.lhratings.com/static/imgs/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.lhratings.com/research.html?type=3",
      "title": "联合资信评估股份有限公司 - 行业研究",
      "type": "feed",
      "url": "rsshub://lhratings/research/3"
    },
    {
      "description": "宏观经济 - Powered by RSSHub",
      "errorAt": "2026-07-06T08:12:08.247Z",
      "errorMessage": "[GET] \"https://www.lhratings.com/research.html?type=1\": 404 Not Found\n",
      "id": "101364983690255360",
      "image": "https://www.lhratings.com/static/imgs/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.lhratings.com/research.html?type=1",
      "title": "联合资信评估股份有限公司 - 宏观经济",
      "type": "feed",
      "url": "rsshub://lhratings/research/1"
    }
  ],
  "url": "www.lhratings.com",
  "view": 0
}
```
