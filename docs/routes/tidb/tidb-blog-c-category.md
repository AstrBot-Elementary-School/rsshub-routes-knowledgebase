# TiDB 社区 - 专栏分类

## Coverage
`index-only`

## Route
- Namespace: `tidb`
- Namespace Name: `TiDB 社区`
- Route Path: `/tidb/blog/c/:category?`
- Route Name: `专栏分类`
- Example: `/tidb/blog/c/latest`
- URL: `tidb.net`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
::: tip
订阅 [管理与运维](https://tidb.net/blog/c/management-and-operation)，其源网址为 `https://tidb.net/blog/c/management-and-operation`，请参考该 URL 指定部分构成参数，此时路由为 [`/tidb/blog/c/management-and-operation`](https://rsshub.app/tidb/blog/c/management-and-operation)。
:::

| 分类                                                           | ID                                                                                  |
| -------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| [全部文章](https://tidb.net/blog)                              | [latest](https://rsshub.app/tidb/blog)                                              |
| [管理与运维](https://tidb.net/blog/c/management-and-operation) | [management-and-operation](https://rsshub.app/tidb/blog/c/management-and-operation) |
| [实践案例](https://tidb.net/blog/c/practical-case)             | [practical-case](https://rsshub.app/tidb/blog/c/practical-case)                     |
| [架构选型](https://tidb.net/blog/c/architecture-selection)     | [architecture-selection](https://rsshub.app/tidb/blog/c/architecture-selection)     |
| [原理解读](https://tidb.net/blog/c/principle-interpretation)   | [principle-interpretation](https://rsshub.app/tidb/blog/c/principle-interpretation) |
| [应用开发](https://tidb.net/blog/c/application-development)    | [application-development](https://rsshub.app/tidb/blog/c/application-development)   |
| [社区动态](https://tidb.net/blog/c/community-feeds)            | [community-feeds](https://rsshub.app/tidb/blog/c/community-feeds)                   |

## Parameters
- `category`: {"description": "分类，默认为 `latest`，即全部文章，可在对应分类页 URL 中找到", "options": [{"label": "全部文章", "value": "latest"}, {"label": "管理与运维", "value": "management-and-operation"}, {"label": "实践案例", "value": "practical-case"}, {"label": "架构选型", "value": "architecture-selection"}, {"label": "原理解读", "value": "principle-interpretation"}, {"label": "应用开发", "value": "application-development"}, {"label": "社区动态", "value": "community-feeds"}]}


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
  - `tidb.net/blog`
  - `tidb.net/blog/c/:category`
### Rule 2
- `title`: `全部文章`
- `source`:
  - `tidb.net/blog`
- `target`: `/blog/c/latest`
### Rule 3
- `title`: `管理与运维`
- `source`:
  - `tidb.net/blog/c/management-and-operation`
- `target`: `/blog/c/management-and-operation`
### Rule 4
- `title`: `实践案例`
- `source`:
  - `tidb.net/blog/c/practical-case`
- `target`: `/blog/c/practical-case`
### Rule 5
- `title`: `架构选型`
- `source`:
  - `tidb.net/blog/c/architecture-selection`
- `target`: `/blog/c/architecture-selection`
### Rule 6
- `title`: `原理解读`
- `source`:
  - `tidb.net/blog/c/principle-interpretation`
- `target`: `/blog/c/principle-interpretation`
### Rule 7
- `title`: `应用开发`
- `source`:
  - `tidb.net/blog/c/application-development`
- `target`: `/blog/c/application-development`
### Rule 8
- `title`: `社区动态`
- `source`:
  - `tidb.net/blog/c/community-feeds`
- `target`: `/blog/c/community-feeds`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "::: tip\n订阅 [管理与运维](https://tidb.net/blog/c/management-and-operation)，其源网址为 `https://tidb.net/blog/c/management-and-operation`，请参考该 URL 指定部分构成参数，此时路由为 [`/tidb/blog/c/management-and-operation`](https://rsshub.app/tidb/blog/c/management-and-operation)。\n:::\n\n| 分类                                                           | ID                                                                                  |\n| -------------------------------------------------------------- | ----------------------------------------------------------------------------------- |\n| [全部文章](https://tidb.net/blog)                              | [latest](https://rsshub.app/tidb/blog)                                              |\n| [管理与运维](https://tidb.net/blog/c/management-and-operation) | [management-and-operation](https://rsshub.app/tidb/blog/c/management-and-operation) |\n| [实践案例](https://tidb.net/blog/c/practical-case)             | [practical-case](https://rsshub.app/tidb/blog/c/practical-case)                     |\n| [架构选型](https://tidb.net/blog/c/architecture-selection)     | [architecture-selection](https://rsshub.app/tidb/blog/c/architecture-selection)     |\n| [原理解读](https://tidb.net/blog/c/principle-interpretation)   | [principle-interpretation](https://rsshub.app/tidb/blog/c/principle-interpretation) |\n| [应用开发](https://tidb.net/blog/c/application-development)    | [application-development](https://rsshub.app/tidb/blog/c/application-development)   |\n| [社区动态](https://tidb.net/blog/c/community-feeds)            | [community-feeds](https://rsshub.app/tidb/blog/c/community-feeds)                   |",
  "example": "/tidb/blog/c/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 5,
  "location": "blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "专栏分类",
  "parameters": {
    "category": {
      "description": "分类，默认为 `latest`，即全部文章，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "全部文章",
          "value": "latest"
        },
        {
          "label": "管理与运维",
          "value": "management-and-operation"
        },
        {
          "label": "实践案例",
          "value": "practical-case"
        },
        {
          "label": "架构选型",
          "value": "architecture-selection"
        },
        {
          "label": "原理解读",
          "value": "principle-interpretation"
        },
        {
          "label": "应用开发",
          "value": "application-development"
        },
        {
          "label": "社区动态",
          "value": "community-feeds"
        }
      ]
    }
  },
  "path": "/blog/c/:category?",
  "radar": [
    {
      "source": [
        "tidb.net/blog",
        "tidb.net/blog/c/:category"
      ]
    },
    {
      "source": [
        "tidb.net/blog"
      ],
      "target": "/blog/c/latest",
      "title": "全部文章"
    },
    {
      "source": [
        "tidb.net/blog/c/management-and-operation"
      ],
      "target": "/blog/c/management-and-operation",
      "title": "管理与运维"
    },
    {
      "source": [
        "tidb.net/blog/c/practical-case"
      ],
      "target": "/blog/c/practical-case",
      "title": "实践案例"
    },
    {
      "source": [
        "tidb.net/blog/c/architecture-selection"
      ],
      "target": "/blog/c/architecture-selection",
      "title": "架构选型"
    },
    {
      "source": [
        "tidb.net/blog/c/principle-interpretation"
      ],
      "target": "/blog/c/principle-interpretation",
      "title": "原理解读"
    },
    {
      "source": [
        "tidb.net/blog/c/application-development"
      ],
      "target": "/blog/c/application-development",
      "title": "应用开发"
    },
    {
      "source": [
        "tidb.net/blog/c/community-feeds"
      ],
      "target": "/blog/c/community-feeds",
      "title": "社区动态"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "这里有来自 TiDB 社区用户分享的管理与运维、实践案例、架构选型、原理解读、应用开发、社区动态等一系列技术文章，也期待你的分享~ - Powered by RSSHub",
      "errorAt": "2026-02-11T12:35:53.842Z",
      "errorMessage": "[GET] \"https://tidb.net/blog/c/application-development\": <no response> fetch failed\n",
      "id": "190044814664594432",
      "image": "https://img1.tidb.net/favicons/android-chrome-512x512.png",
      "ownerUserId": null,
      "siteUrl": "https://tidb.net/blog/c/application-development",
      "title": "博客 - 开发实践 | TiDB 社区",
      "type": "feed",
      "url": "rsshub://tidb/blog/c/application-development"
    },
    {
      "description": "这里有来自 TiDB 社区用户分享的管理与运维、实践案例、架构选型、原理解读、应用开发、社区动态等一系列技术文章，也期待你的分享~ - Powered by RSSHub",
      "errorAt": "2026-02-11T14:31:24.424Z",
      "errorMessage": "[GET] \"https://tidb.net/blog/c/principle-interpretation\": <no response> fetch failed\n",
      "id": "190044741201359872",
      "image": "https://img1.tidb.net/favicons/android-chrome-512x512.png",
      "ownerUserId": null,
      "siteUrl": "https://tidb.net/blog/c/principle-interpretation",
      "title": "博客 - 产品技术解读 | TiDB 社区",
      "type": "feed",
      "url": "rsshub://tidb/blog/c/principle-interpretation"
    }
  ],
  "url": "tidb.net",
  "view": 0
}
```
