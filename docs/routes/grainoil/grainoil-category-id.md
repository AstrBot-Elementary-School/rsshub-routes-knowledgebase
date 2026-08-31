# 国家粮油信息中心 - 分类

## Coverage
`index-only`

## Route
- Namespace: `grainoil`
- Namespace Name: `国家粮油信息中心`
- Route Path: `/grainoil/:category/:id`
- Route Name: `分类`
- Example: `/grainoil/newsListHome/3`
- URL: `load.grainoil.com.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [政务信息](http://load.grainoil.com.cn/newsListHome/1430.jspx)，网址为 `http://load.grainoil.com.cn/newsListHome/1430.jspx`，请截取 `https://load.grainoil.com.cn/` 到末尾 `.jspx` 的部分 `newsListHome/1430` 作为 `category` 和 `id`参数填入，此时目标路由为 [`/grainoil/newsListHome/1430`](https://rsshub.app/grainoil/newsListHome/1430)。
:::

<details>
  <summary>更多分类</summary>

| 分类     | ID                 |
| -------- | ------------------ |
| 政务信息 | newsListHome/1430  |
| 要闻动态 | newsListHome/3     |
| 产业经济 | newsListHome/1469  |
| 产业信息 | newsListHome/1471  |
| 爱粮节粮 | newsListHome/1470  |
| 政策法规 | newsListChannel/18 |
| 生产气象 | newsListChannel/19 |
| 统计资料 | newsListChannel/20 |
| 综合信息 | newsListChannel/21 |

</details>

## Parameters
- `category`: {"description": "分类，默认为 `newsListHome`，可在对应分类页 URL 中找到", "options": [{"label": "newsListHome", "value": "newsListHome"}, {"label": "newsListChannel", "value": "newsListChannel"}]}
- `id`: {"description": "分类 ID，可在对应分类页 URL 中找到"}


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
  - `load.grainoil.com.cn/:category/:id`
### Rule 2
- `title`: `政务信息`
- `source`:
  - `load.grainoil.com.cn/newsListHome/1430.jspx`
- `target`: `/newsListHome/1430`
### Rule 3
- `title`: `要闻动态`
- `source`:
  - `load.grainoil.com.cn/newsListHome/3.jspx`
- `target`: `/newsListHome/3`
### Rule 4
- `title`: `产业经济`
- `source`:
  - `load.grainoil.com.cn/newsListHome/1469.jspx`
- `target`: `/newsListHome/1469`
### Rule 5
- `title`: `产业信息`
- `source`:
  - `load.grainoil.com.cn/newsListHome/1471.jspx`
- `target`: `/newsListHome/1471`
### Rule 6
- `title`: `爱粮节粮`
- `source`:
  - `load.grainoil.com.cn/newsListHome/1470.jspx`
- `target`: `/newsListHome/1470`
### Rule 7
- `title`: `政策法规`
- `source`:
  - `load.grainoil.com.cn/newsListChannel/18.jspx`
- `target`: `/newsListChannel/18`
### Rule 8
- `title`: `生产气象`
- `source`:
  - `load.grainoil.com.cn/newsListChannel/19.jspx`
- `target`: `/newsListChannel/19`
### Rule 9
- `title`: `统计资料`
- `source`:
  - `load.grainoil.com.cn/newsListChannel/20.jspx`
- `target`: `/newsListChannel/20`
### Rule 10
- `title`: `综合信息`
- `source`:
  - `load.grainoil.com.cn/newsListChannel/21.jspx`
- `target`: `/newsListChannel/21`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n若订阅 [政务信息](http://load.grainoil.com.cn/newsListHome/1430.jspx)，网址为 `http://load.grainoil.com.cn/newsListHome/1430.jspx`，请截取 `https://load.grainoil.com.cn/` 到末尾 `.jspx` 的部分 `newsListHome/1430` 作为 `category` 和 `id`参数填入，此时目标路由为 [`/grainoil/newsListHome/1430`](https://rsshub.app/grainoil/newsListHome/1430)。\n:::\n\n<details>\n  <summary>更多分类</summary>\n\n| 分类     | ID                 |\n| -------- | ------------------ |\n| 政务信息 | newsListHome/1430  |\n| 要闻动态 | newsListHome/3     |\n| 产业经济 | newsListHome/1469  |\n| 产业信息 | newsListHome/1471  |\n| 爱粮节粮 | newsListHome/1470  |\n| 政策法规 | newsListChannel/18 |\n| 生产气象 | newsListChannel/19 |\n| 统计资料 | newsListChannel/20 |\n| 综合信息 | newsListChannel/21 |\n\n</details>",
  "example": "/grainoil/newsListHome/3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": {
      "description": "分类，默认为 `newsListHome`，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "newsListHome",
          "value": "newsListHome"
        },
        {
          "label": "newsListChannel",
          "value": "newsListChannel"
        }
      ]
    },
    "id": {
      "description": "分类 ID，可在对应分类页 URL 中找到"
    }
  },
  "path": "/:category/:id",
  "radar": [
    {
      "source": [
        "load.grainoil.com.cn/:category/:id"
      ]
    },
    {
      "source": [
        "load.grainoil.com.cn/newsListHome/1430.jspx"
      ],
      "target": "/newsListHome/1430",
      "title": "政务信息"
    },
    {
      "source": [
        "load.grainoil.com.cn/newsListHome/3.jspx"
      ],
      "target": "/newsListHome/3",
      "title": "要闻动态"
    },
    {
      "source": [
        "load.grainoil.com.cn/newsListHome/1469.jspx"
      ],
      "target": "/newsListHome/1469",
      "title": "产业经济"
    },
    {
      "source": [
        "load.grainoil.com.cn/newsListHome/1471.jspx"
      ],
      "target": "/newsListHome/1471",
      "title": "产业信息"
    },
    {
      "source": [
        "load.grainoil.com.cn/newsListHome/1470.jspx"
      ],
      "target": "/newsListHome/1470",
      "title": "爱粮节粮"
    },
    {
      "source": [
        "load.grainoil.com.cn/newsListChannel/18.jspx"
      ],
      "target": "/newsListChannel/18",
      "title": "政策法规"
    },
    {
      "source": [
        "load.grainoil.com.cn/newsListChannel/19.jspx"
      ],
      "target": "/newsListChannel/19",
      "title": "生产气象"
    },
    {
      "source": [
        "load.grainoil.com.cn/newsListChannel/20.jspx"
      ],
      "target": "/newsListChannel/20",
      "title": "统计资料"
    },
    {
      "source": [
        "load.grainoil.com.cn/newsListChannel/21.jspx"
      ],
      "target": "/newsListChannel/21",
      "title": "综合信息"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "load.grainoil.com.cn",
  "view": 0
}
```
