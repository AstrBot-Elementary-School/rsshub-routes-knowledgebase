# 半月谈 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `banyuetan`
- Namespace Name: `半月谈`
- Route Path: `/banyuetan/:id?`
- Route Name: `栏目`
- Example: `/banyuetan/jinritan`
- URL: `www.banyuetan.org`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
订阅 [今日谈](http://www.banyuetan.org/byt/jinritan/)，其源网址为 `http://www.banyuetan.org/byt/jinritan/`，请参考该 URL 指定部分构成参数，此时路由为 [`/banyuetan/jinritan`](https://rsshub.app/banyuetan/jinritan)。
:::

| 栏目                                                                 | ID                                                                |
| -------------------------------------------------------------------- | ----------------------------------------------------------------- |
| [今日谈](http://www.banyuetan.org/byt/jinritan/index.html)           | [jinritan](https://rsshub.app/banyuetan/jinritan)                 |
| [时政讲解](http://www.banyuetan.org/byt/shizhengjiangjie/index.html) | [shizhengjiangjie](https://rsshub.app/banyuetan/shizhengjiangjie) |
| [评论](http://www.banyuetan.org/byt/banyuetanpinglun/index.html)     | [banyuetanpinglun](https://rsshub.app/banyuetan/banyuetanpinglun) |
| [基层治理](http://www.banyuetan.org/byt/jicengzhili/index.html)      | [jicengzhili](https://rsshub.app/banyuetan/jicengzhili)           |
| [文化](http://www.banyuetan.org/byt/wenhua/index.html)               | [wenhua](https://rsshub.app/banyuetan/wenhua)                     |
| [教育](http://www.banyuetan.org/byt/jiaoyu/index.html)               | [jiaoyu](https://rsshub.app/banyuetan/jiaoyu)                     |

## Parameters
- `id`: {"description": "栏目 ID，默认为 `jinritan`，即今日谈，可在对应分类页 URL 中找到", "options": [{"label": "今日谈", "value": "jinritan"}, {"label": "时政讲解", "value": "shizhengjiangjie"}, {"label": "评论", "value": "banyuetanpinglun"}, {"label": "基层治理", "value": "jicengzhili"}, {"label": "文化", "value": "wenhua"}, {"label": "教育", "value": "jiaoyu"}]}


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
  - `www.banyuetan.org/byt/:id`
- `target`: `/:id`
### Rule 2
- `title`: `今日谈`
- `source`:
  - `www.banyuetan.org/byt/jinritan/index.html`
- `target`: `/jinritan`
### Rule 3
- `title`: `时政讲解`
- `source`:
  - `www.banyuetan.org/byt/shizhengjiangjie/index.html`
- `target`: `/shizhengjiangjie`
### Rule 4
- `title`: `评论`
- `source`:
  - `www.banyuetan.org/byt/banyuetanpinglun/index.html`
- `target`: `/banyuetanpinglun`
### Rule 5
- `title`: `基层治理`
- `source`:
  - `www.banyuetan.org/byt/jicengzhili/index.html`
- `target`: `/jicengzhili`
### Rule 6
- `title`: `文化`
- `source`:
  - `www.banyuetan.org/byt/wenhua/index.html`
- `target`: `/wenhua`
### Rule 7
- `title`: `教育`
- `source`:
  - `www.banyuetan.org/byt/jiaoyu/index.html`
- `target`: `/jiaoyu`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\n订阅 [今日谈](http://www.banyuetan.org/byt/jinritan/)，其源网址为 `http://www.banyuetan.org/byt/jinritan/`，请参考该 URL 指定部分构成参数，此时路由为 [`/banyuetan/jinritan`](https://rsshub.app/banyuetan/jinritan)。\n:::\n\n| 栏目                                                                 | ID                                                                |\n| -------------------------------------------------------------------- | ----------------------------------------------------------------- |\n| [今日谈](http://www.banyuetan.org/byt/jinritan/index.html)           | [jinritan](https://rsshub.app/banyuetan/jinritan)                 |\n| [时政讲解](http://www.banyuetan.org/byt/shizhengjiangjie/index.html) | [shizhengjiangjie](https://rsshub.app/banyuetan/shizhengjiangjie) |\n| [评论](http://www.banyuetan.org/byt/banyuetanpinglun/index.html)     | [banyuetanpinglun](https://rsshub.app/banyuetan/banyuetanpinglun) |\n| [基层治理](http://www.banyuetan.org/byt/jicengzhili/index.html)      | [jicengzhili](https://rsshub.app/banyuetan/jicengzhili)           |\n| [文化](http://www.banyuetan.org/byt/wenhua/index.html)               | [wenhua](https://rsshub.app/banyuetan/wenhua)                     |\n| [教育](http://www.banyuetan.org/byt/jiaoyu/index.html)               | [jiaoyu](https://rsshub.app/banyuetan/jiaoyu)                     |",
  "example": "/banyuetan/jinritan",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 367,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "id": {
      "description": "栏目 ID，默认为 `jinritan`，即今日谈，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "今日谈",
          "value": "jinritan"
        },
        {
          "label": "时政讲解",
          "value": "shizhengjiangjie"
        },
        {
          "label": "评论",
          "value": "banyuetanpinglun"
        },
        {
          "label": "基层治理",
          "value": "jicengzhili"
        },
        {
          "label": "文化",
          "value": "wenhua"
        },
        {
          "label": "教育",
          "value": "jiaoyu"
        }
      ]
    }
  },
  "path": "/:id?",
  "radar": [
    {
      "source": [
        "www.banyuetan.org/byt/:id"
      ],
      "target": "/:id"
    },
    {
      "source": [
        "www.banyuetan.org/byt/jinritan/index.html"
      ],
      "target": "/jinritan",
      "title": "今日谈"
    },
    {
      "source": [
        "www.banyuetan.org/byt/shizhengjiangjie/index.html"
      ],
      "target": "/shizhengjiangjie",
      "title": "时政讲解"
    },
    {
      "source": [
        "www.banyuetan.org/byt/banyuetanpinglun/index.html"
      ],
      "target": "/banyuetanpinglun",
      "title": "评论"
    },
    {
      "source": [
        "www.banyuetan.org/byt/jicengzhili/index.html"
      ],
      "target": "/jicengzhili",
      "title": "基层治理"
    },
    {
      "source": [
        "www.banyuetan.org/byt/wenhua/index.html"
      ],
      "target": "/wenhua",
      "title": "文化"
    },
    {
      "source": [
        "www.banyuetan.org/byt/jiaoyu/index.html"
      ],
      "target": "/jiaoyu",
      "title": "教育"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "时政讲解—半月谈网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "148757739569766416",
      "image": "http://www.banyuetan.org/static/v1/image/logo.png",
      "ownerUserId": null,
      "siteUrl": "http://www.banyuetan.org/byt/shizhengjiangjie/index.html",
      "title": "时政讲解—半月谈网",
      "type": "feed",
      "url": "rsshub://banyuetan/shizhengjiangjie"
    },
    {
      "description": "今日谈—半月谈网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "148757739569766415",
      "image": "http://www.banyuetan.org/static/v1/image/logo.png",
      "ownerUserId": null,
      "siteUrl": "http://www.banyuetan.org/byt/jinritan/index.html",
      "title": "今日谈—半月谈网",
      "type": "feed",
      "url": "rsshub://banyuetan/jinritan"
    }
  ],
  "url": "www.banyuetan.org",
  "view": 0
}
```
