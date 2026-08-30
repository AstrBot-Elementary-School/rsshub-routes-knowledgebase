# 中房网 - 列表

## Coverage
`index-only`

## Route
- Namespace: `fangchan`
- Namespace Name: `中房网`
- Route Path: `/fangchan/list/:id?`
- Route Name: `列表`
- Example: `/fangchan/list/datalist`
- URL: `www.fangchan.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `list.tsx`
- Source Module: `_None_`

## Description
::: tip
若订阅 [列表](https://www.fangchan.com/)，网址为 `https://www.fangchan.com/`，请截取 `https://www.fangchan.com/` 到末尾 `.html` 的部分 `datalist` 作为 `id` 参数填入，此时目标路由为 [`/fangchan/datalist`](https://rsshub.app/fangchan/datalist)。
:::

| [数据研究](https://www.fangchan.com/datalist)         | [行业测评](https://www.fangchan.com/industrylist)             | [政策法规](https://www.fangchan.com/policylist)           |
| ----------------------------------------------------- | ------------------------------------------------------------- | --------------------------------------------------------- |
| [datalist](https://rsshub.app/fangchan/list/datalist) | [industrylist](https://rsshub.app/fangchan/list/industrylist) | [policylist](https://rsshub.app/fangchan/list/policylist) |

## Parameters
- `id`: {"description": "分类，默认为 `datalist`，即数据研究，可在对应分类页 URL 中找到", "options": [{"label": "数据研究", "value": "datalist"}, {"label": "行业测评", "value": "industrylist"}, {"label": "政策法规", "value": "policylist"}]}


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
  - `www.fangchan.com/:id`
### Rule 2
- `title`: `数据研究`
- `source`:
  - `www.fangchan.com/datalist`
- `target`: `/list/datalist`
### Rule 3
- `title`: `行业测评`
- `source`:
  - `www.fangchan.com/industrylist`
- `target`: `/list/industrylist`
### Rule 4
- `title`: `政策法规`
- `source`:
  - `www.fangchan.com/policylist`
- `target`: `/list/policylist`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n若订阅 [列表](https://www.fangchan.com/)，网址为 `https://www.fangchan.com/`，请截取 `https://www.fangchan.com/` 到末尾 `.html` 的部分 `datalist` 作为 `id` 参数填入，此时目标路由为 [`/fangchan/datalist`](https://rsshub.app/fangchan/datalist)。\n:::\n\n| [数据研究](https://www.fangchan.com/datalist)         | [行业测评](https://www.fangchan.com/industrylist)             | [政策法规](https://www.fangchan.com/policylist)           |\n| ----------------------------------------------------- | ------------------------------------------------------------- | --------------------------------------------------------- |\n| [datalist](https://rsshub.app/fangchan/list/datalist) | [industrylist](https://rsshub.app/fangchan/list/industrylist) | [policylist](https://rsshub.app/fangchan/list/policylist) |",
  "example": "/fangchan/list/datalist",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 59,
  "location": "list.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "列表",
  "parameters": {
    "id": {
      "description": "分类，默认为 `datalist`，即数据研究，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "数据研究",
          "value": "datalist"
        },
        {
          "label": "行业测评",
          "value": "industrylist"
        },
        {
          "label": "政策法规",
          "value": "policylist"
        }
      ]
    }
  },
  "path": "/list/:id?",
  "radar": [
    {
      "source": [
        "www.fangchan.com/:id"
      ]
    },
    {
      "source": [
        "www.fangchan.com/datalist"
      ],
      "target": "/list/datalist",
      "title": "数据研究"
    },
    {
      "source": [
        "www.fangchan.com/industrylist"
      ],
      "target": "/list/industrylist",
      "title": "行业测评"
    },
    {
      "source": [
        "www.fangchan.com/policylist"
      ],
      "target": "/list/policylist",
      "title": "政策法规"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "中房网是中国房地产业协会的官方网站，致力于政府、行业、专业三大资源的整合，以权威及时的房地产行业资讯、数据与信用信息，打造房地产政策解读、市场判研、测评研究、信用管理的权威公信力平台。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "118187917104194560",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.fangchan.com/datalist/",
      "title": "中房网 - 数据研究",
      "type": "feed",
      "url": "rsshub://fangchan/list/datalist"
    },
    {
      "description": "中房网是中国房地产业协会的官方网站，致力于政府、行业、专业三大资源的整合，以权威及时的房地产行业资讯、数据与信用信息，打造房地产政策解读、市场判研、测评研究、信用管理的权威公信力平台。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "168523701006919680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.fangchan.com/industrylist/",
      "title": "中房网 - 行业测评",
      "type": "feed",
      "url": "rsshub://fangchan/list/industrylist"
    }
  ],
  "url": "www.fangchan.com",
  "view": 0
}
```
