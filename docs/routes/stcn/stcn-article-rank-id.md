# 证券时报网 - 热榜

## Coverage
`index-only`

## Route
- Namespace: `stcn`
- Namespace Name: `证券时报网`
- Route Path: `/stcn/article/rank/:id?`
- Route Name: `热榜`
- Example: `/stcn/article/rank/yw`
- URL: `www.stcn.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `rank.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [要闻](https://www.stcn.com/article/list/yw.html)，网址为 `https://www.stcn.com/article/list/yw.html`，请截取 `https://www.stcn.com/article/list/` 到末尾 `.html` 的部分 `yw` 作为 `id` 参数填入，此时目标路由为 [`/stcn/article/rank/yw`](https://rsshub.app/stcn/article/rank/yw)。
:::

| 要闻 | 股市 | 公司    | 基金 | 金融    | 评论    |
| ---- | ---- | ------- | ---- | ------- | ------- |
| yw   | gs   | company | fund | finance | comment |

| 产经 | 科创板 | 新三板 | ESG | 滚动 |
| ---- | ------ | ------ | --- | ---- |
| cj   | kcb    | xsb    | zk  | gd   |

## Parameters
- `category`: {"description": "分类，默认为 `yw`，即要闻，可在对应分类页 URL 中找到", "options": [{"label": "要闻", "value": "yw"}, {"label": "股市", "value": "gs"}, {"label": "公司", "value": "company"}, {"label": "基金", "value": "fund"}, {"label": "金融", "value": "finance"}, {"label": "评论", "value": "comment"}, {"label": "产经", "value": "cj"}, {"label": "科创板", "value": "kcb"}, {"label": "新三板", "value": "xsb"}, {"label": "ESG", "value": "zk"}, {"label": "滚动", "value": "gd"}]}


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
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/:id`
### Rule 2
- `title`: `要闻`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/yw.html`
- `target`: `/article/rank/yw`
### Rule 3
- `title`: `股市`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/gs.html`
- `target`: `/article/rank/gs`
### Rule 4
- `title`: `公司`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/company.html`
- `target`: `/article/rank/company`
### Rule 5
- `title`: `基金`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/fund.html`
- `target`: `/article/rank/fund`
### Rule 6
- `title`: `金融`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/finance.html`
- `target`: `/article/rank/finance`
### Rule 7
- `title`: `评论`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/comment.html`
- `target`: `/article/rank/comment`
### Rule 8
- `title`: `产经`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/cj.html`
- `target`: `/article/rank/cj`
### Rule 9
- `title`: `科创板`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/kcb.html`
- `target`: `/article/rank/kcb`
### Rule 10
- `title`: `新三板`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/xsb.html`
- `target`: `/article/rank/xsb`
### Rule 11
- `title`: `ESG`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/zk.html`
- `target`: `/article/rank/zk`
### Rule 12
- `title`: `滚动`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/gd.html`
- `target`: `/article/rank/gd`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n若订阅 [要闻](https://www.stcn.com/article/list/yw.html)，网址为 `https://www.stcn.com/article/list/yw.html`，请截取 `https://www.stcn.com/article/list/` 到末尾 `.html` 的部分 `yw` 作为 `id` 参数填入，此时目标路由为 [`/stcn/article/rank/yw`](https://rsshub.app/stcn/article/rank/yw)。\n:::\n\n| 要闻 | 股市 | 公司    | 基金 | 金融    | 评论    |\n| ---- | ---- | ------- | ---- | ------- | ------- |\n| yw   | gs   | company | fund | finance | comment |\n\n| 产经 | 科创板 | 新三板 | ESG | 滚动 |\n| ---- | ------ | ------ | --- | ---- |\n| cj   | kcb    | xsb    | zk  | gd   |",
  "example": "/stcn/article/rank/yw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 167,
  "location": "rank.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "热榜",
  "parameters": {
    "category": {
      "description": "分类，默认为 `yw`，即要闻，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "要闻",
          "value": "yw"
        },
        {
          "label": "股市",
          "value": "gs"
        },
        {
          "label": "公司",
          "value": "company"
        },
        {
          "label": "基金",
          "value": "fund"
        },
        {
          "label": "金融",
          "value": "finance"
        },
        {
          "label": "评论",
          "value": "comment"
        },
        {
          "label": "产经",
          "value": "cj"
        },
        {
          "label": "科创板",
          "value": "kcb"
        },
        {
          "label": "新三板",
          "value": "xsb"
        },
        {
          "label": "ESG",
          "value": "zk"
        },
        {
          "label": "滚动",
          "value": "gd"
        }
      ]
    }
  },
  "path": "/article/rank/:id?",
  "radar": [
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/:id"
      ]
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/yw.html"
      ],
      "target": "/article/rank/yw",
      "title": "要闻"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/gs.html"
      ],
      "target": "/article/rank/gs",
      "title": "股市"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/company.html"
      ],
      "target": "/article/rank/company",
      "title": "公司"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/fund.html"
      ],
      "target": "/article/rank/fund",
      "title": "基金"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/finance.html"
      ],
      "target": "/article/rank/finance",
      "title": "金融"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/comment.html"
      ],
      "target": "/article/rank/comment",
      "title": "评论"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/cj.html"
      ],
      "target": "/article/rank/cj",
      "title": "产经"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/kcb.html"
      ],
      "target": "/article/rank/kcb",
      "title": "科创板"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/xsb.html"
      ],
      "target": "/article/rank/xsb",
      "title": "新三板"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/zk.html"
      ],
      "target": "/article/rank/zk",
      "title": "ESG"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/gd.html"
      ],
      "target": "/article/rank/gd",
      "title": "滚动"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "证券时报，证券时报网，由人民日报社主管主办，是证券市场权威信息披露媒体，也是中国资本市场的重要信息披露平台。提供全天候7*24小时财经证券类资讯，内容丰富，包括时报快讯、股市新闻、财经资讯、基金净值、债券、期货、上市公司公告等，为用户提供全方位、最新鲜的财经信息。打造了“信披168”综合服务专区，资本市场投教“星火计划”，是权威、全面的资本市场服务平台。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "128558925444651008",
      "image": "https://static-web.stcn.com/static/images/stcn.png",
      "ownerUserId": null,
      "siteUrl": "https://www.stcn.com/article/list/yw.html",
      "title": "财经要闻频道,今日要闻，炒股消息，股市重大消息-证券时报要闻栏目",
      "type": "feed",
      "url": "rsshub://stcn/article/rank/yw"
    },
    {
      "description": "证券时报，证券时报网，由人民日报社主管主办，是证券市场权威信息披露媒体，也是中国资本市场的重要信息披露平台。提供全天候7*24小时财经证券类资讯，内容丰富，包括时报快讯、股市新闻、财经资讯、基金净值、债券、期货、上市公司公告等，为用户提供全方位、最新鲜的财经信息。打造了“信披168”综合服务专区，资本市场投教“星火计划”，是权威、全面的资本市场服务平台。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "155491933131558912",
      "image": "https://static-web.stcn.com/static/images/stcn.png",
      "ownerUserId": null,
      "siteUrl": "https://www.stcn.com/article/list/yw.html",
      "title": "财经要闻频道,今日要闻，炒股消息，股市重大消息-证券时报要闻栏目",
      "type": "feed",
      "url": "rsshub://stcn/article/rank"
    }
  ],
  "url": "www.stcn.com",
  "view": 0
}
```
