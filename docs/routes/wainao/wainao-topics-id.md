# 歪脑 - 主题

## Coverage
`index-only`

## Route
- Namespace: `wainao`
- Namespace Name: `歪脑`
- Route Path: `/wainao/topics/:id?`
- Route Name: `主题`
- Example: `/wainao/topics/hotspot`
- URL: `wainao.me`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `shuiRong, nczitzk`
- Source Location: `topics.tsx`
- Source Module: `_None_`

## Description
::: tip
若订阅 [人物](https://www.wainao.me/topics/people)，网址为 `https://www.wainao.me/topics/people`，请截取 `https://www.wainao.me/topics/` 到末尾的部分 `people` 作为 `id` 参数填入，此时目标路由为 [`/wainao/topics/people`](https://rsshub.app/wainao/topics/people)。
:::

| [热点](https://www.wainao.me/topics/hotspot)        | [人物](https://www.wainao.me/topics/people)       | [身份](https://www.wainao.me/topics/identity)         | [政治](https://www.wainao.me/topics/politics)         | [社会](https://www.wainao.me/topics/society)        | [文化](https://www.wainao.me/topics/culture)        | [经济](https://www.wainao.me/topics/economics)          | [环境](https://www.wainao.me/topics/environment)            | [FUN](https://www.wainao.me/topics/fun)     |
| --------------------------------------------------- | ------------------------------------------------- | ----------------------------------------------------- | ----------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------------------- |
| [hotspot](https://rsshub.app/wainao/topics/hotspot) | [people](https://rsshub.app/wainao/topics/people) | [identity](https://rsshub.app/wainao/topics/identity) | [politics](https://rsshub.app/wainao/topics/politics) | [society](https://rsshub.app/wainao/topics/society) | [culture](https://rsshub.app/wainao/topics/culture) | [economics](https://rsshub.app/wainao/topics/economics) | [environment](https://rsshub.app/wainao/topics/environment) | [fun](https://rsshub.app/wainao/topics/fun) |

## Parameters
- `id`: {"description": "主题 id，默认为 `hotspot`，即热点，可在对应主题页 URL 中找到", "options": [{"label": "热点", "value": "hotspot"}, {"label": "人物", "value": "people"}, {"label": "身份", "value": "identity"}, {"label": "政治", "value": "politics"}, {"label": "社会", "value": "society"}, {"label": "文化", "value": "culture"}, {"label": "经济", "value": "economics"}, {"label": "环境", "value": "environment"}, {"label": "FUN", "value": "fun"}]}


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
  - `www.wainao.me/topics/:id`
- `target`: `/topics/:id`
### Rule 2
- `title`: `热点`
- `source`:
  - `www.wainao.me/topics/hotspot`
- `target`: `/topics/hotspot`
### Rule 3
- `title`: `人物`
- `source`:
  - `www.wainao.me/topics/people`
- `target`: `/topics/people`
### Rule 4
- `title`: `身份`
- `source`:
  - `www.wainao.me/topics/identity`
- `target`: `/topics/identity`
### Rule 5
- `title`: `政治`
- `source`:
  - `www.wainao.me/topics/politics`
- `target`: `/topics/politics`
### Rule 6
- `title`: `社会`
- `source`:
  - `www.wainao.me/topics/society`
- `target`: `/topics/society`
### Rule 7
- `title`: `文化`
- `source`:
  - `www.wainao.me/topics/culture`
- `target`: `/topics/culture`
### Rule 8
- `title`: `经济`
- `source`:
  - `www.wainao.me/topics/economics`
- `target`: `/topics/economics`
### Rule 9
- `title`: `环境`
- `source`:
  - `www.wainao.me/topics/environment`
- `target`: `/topics/environment`
### Rule 10
- `title`: `FUN`
- `source`:
  - `www.wainao.me/topics/fun`
- `target`: `/topics/fun`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n若订阅 [人物](https://www.wainao.me/topics/people)，网址为 `https://www.wainao.me/topics/people`，请截取 `https://www.wainao.me/topics/` 到末尾的部分 `people` 作为 `id` 参数填入，此时目标路由为 [`/wainao/topics/people`](https://rsshub.app/wainao/topics/people)。\n:::\n\n| [热点](https://www.wainao.me/topics/hotspot)        | [人物](https://www.wainao.me/topics/people)       | [身份](https://www.wainao.me/topics/identity)         | [政治](https://www.wainao.me/topics/politics)         | [社会](https://www.wainao.me/topics/society)        | [文化](https://www.wainao.me/topics/culture)        | [经济](https://www.wainao.me/topics/economics)          | [环境](https://www.wainao.me/topics/environment)            | [FUN](https://www.wainao.me/topics/fun)     |\n| --------------------------------------------------- | ------------------------------------------------- | ----------------------------------------------------- | ----------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------------------- |\n| [hotspot](https://rsshub.app/wainao/topics/hotspot) | [people](https://rsshub.app/wainao/topics/people) | [identity](https://rsshub.app/wainao/topics/identity) | [politics](https://rsshub.app/wainao/topics/politics) | [society](https://rsshub.app/wainao/topics/society) | [culture](https://rsshub.app/wainao/topics/culture) | [economics](https://rsshub.app/wainao/topics/economics) | [environment](https://rsshub.app/wainao/topics/environment) | [fun](https://rsshub.app/wainao/topics/fun) |",
  "example": "/wainao/topics/hotspot",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 3,
  "location": "topics.tsx",
  "maintainers": [
    "shuiRong",
    "nczitzk"
  ],
  "name": "主题",
  "parameters": {
    "id": {
      "description": "主题 id，默认为 `hotspot`，即热点，可在对应主题页 URL 中找到",
      "options": [
        {
          "label": "热点",
          "value": "hotspot"
        },
        {
          "label": "人物",
          "value": "people"
        },
        {
          "label": "身份",
          "value": "identity"
        },
        {
          "label": "政治",
          "value": "politics"
        },
        {
          "label": "社会",
          "value": "society"
        },
        {
          "label": "文化",
          "value": "culture"
        },
        {
          "label": "经济",
          "value": "economics"
        },
        {
          "label": "环境",
          "value": "environment"
        },
        {
          "label": "FUN",
          "value": "fun"
        }
      ]
    }
  },
  "path": "/topics/:id?",
  "radar": [
    {
      "source": [
        "www.wainao.me/topics/:id"
      ],
      "target": "/topics/:id"
    },
    {
      "source": [
        "www.wainao.me/topics/hotspot"
      ],
      "target": "/topics/hotspot",
      "title": "热点"
    },
    {
      "source": [
        "www.wainao.me/topics/people"
      ],
      "target": "/topics/people",
      "title": "人物"
    },
    {
      "source": [
        "www.wainao.me/topics/identity"
      ],
      "target": "/topics/identity",
      "title": "身份"
    },
    {
      "source": [
        "www.wainao.me/topics/politics"
      ],
      "target": "/topics/politics",
      "title": "政治"
    },
    {
      "source": [
        "www.wainao.me/topics/society"
      ],
      "target": "/topics/society",
      "title": "社会"
    },
    {
      "source": [
        "www.wainao.me/topics/culture"
      ],
      "target": "/topics/culture",
      "title": "文化"
    },
    {
      "source": [
        "www.wainao.me/topics/economics"
      ],
      "target": "/topics/economics",
      "title": "经济"
    },
    {
      "source": [
        "www.wainao.me/topics/environment"
      ],
      "target": "/topics/environment",
      "title": "环境"
    },
    {
      "source": [
        "www.wainao.me/topics/fun"
      ],
      "target": "/topics/fun",
      "title": "FUN"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "热点 - Wainao - Powered by RSSHub",
      "errorAt": "2025-03-06T02:34:40.461Z",
      "errorMessage": "terminated\n",
      "id": "118195542971350016",
      "image": "https://www.wainao.me/resizer/v2/https%3A%2F%2Fstatic.themebuilder.aws.arc.pub%2Fradiofreeasia%2F1730929154842.png?auth=46d25eedb529be1f271f4530ba42081d2f32310870e394d5ef29b5e95c643a38&width=1200",
      "ownerUserId": null,
      "siteUrl": "https://www.wainao.me/topics/hotspot",
      "title": "热点 - Wainao",
      "type": "feed",
      "url": "rsshub://wainao/topics/hotspot"
    }
  ],
  "url": "wainao.me",
  "view": 0
}
```
