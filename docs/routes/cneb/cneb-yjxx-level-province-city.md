# 中国国家应急广播 - 预警信息

## Coverage
`index-only`

## Route
- Namespace: `cneb`
- Namespace Name: `中国国家应急广播`
- Route Path: `/cneb/yjxx/:level?/:province?/:city?`
- Route Name: `预警信息`
- Example: `/cneb/yjxx`
- URL: `cneb.gov.cn/yjxx`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `muzea, nczitzk`
- Source Location: `yjxx.ts`
- Source Module: `_None_`

## Description
灾害级别

| 全部 | 红色 | 橙色 | 黄色 | 蓝色 |
| ---- | ---- | ---- | ---- | ---- |
|      | 红色 | 橙色 | 黄色 | 蓝色 |

::: tip
若订阅全国的全部预警信息，此时路由为 [`/cneb/yjxx`](https://rsshub.app/cneb/yjxx)。

若订阅全国的 **红色** 预警信息，此时路由为 [`/cneb/yjxx/红色`](https://rsshub.app/cneb/yjxx/红色)。

若订阅 **北京市** 的全部预警信息，此时路由为 [`/cneb/yjxx/北京市`](https://rsshub.app/cneb/yjxx/北京市)。

若订阅 **北京市** 的 **蓝色** 预警信息，此时路由为 [`/cneb/yjxx/北京市/蓝色`](https://rsshub.app/cneb/yjxx/北京市/蓝色)。

若订阅 **广东省** 的 **橙色** 预警信息，此时路由为 [`/cneb/yjxx/广东省/橙色`](https://rsshub.app/cneb/yjxx/广东省/橙色)。

若订阅 **广东省广州市** 的全部预警信息，此时路由为 [`/cneb/yjxx/广东省/广州市`](https://rsshub.app/cneb/yjxx/广东省/广州市)。

若订阅 **广东省广州市** 的 **黄色** 预警信息，此时路由为 [`/cneb/yjxx/广东省/广州市/黄色`](https://rsshub.app/cneb/yjxx/广东省/广州市/黄色)。
:::

## Parameters
- `level`: 灾害级别，见下表，默认为全部
- `province`: 省份，默认为空，即全国
- `city`: 城市，默认为空，即全省


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `cneb.gov.cn/yjxx`
  - `cneb.gov.cn/`
- `target`: `/yjxx`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "description": "灾害级别\n\n| 全部 | 红色 | 橙色 | 黄色 | 蓝色 |\n| ---- | ---- | ---- | ---- | ---- |\n|      | 红色 | 橙色 | 黄色 | 蓝色 |\n\n::: tip\n若订阅全国的全部预警信息，此时路由为 [`/cneb/yjxx`](https://rsshub.app/cneb/yjxx)。\n\n若订阅全国的 **红色** 预警信息，此时路由为 [`/cneb/yjxx/红色`](https://rsshub.app/cneb/yjxx/红色)。\n\n若订阅 **北京市** 的全部预警信息，此时路由为 [`/cneb/yjxx/北京市`](https://rsshub.app/cneb/yjxx/北京市)。\n\n若订阅 **北京市** 的 **蓝色** 预警信息，此时路由为 [`/cneb/yjxx/北京市/蓝色`](https://rsshub.app/cneb/yjxx/北京市/蓝色)。\n\n若订阅 **广东省** 的 **橙色** 预警信息，此时路由为 [`/cneb/yjxx/广东省/橙色`](https://rsshub.app/cneb/yjxx/广东省/橙色)。\n\n若订阅 **广东省广州市** 的全部预警信息，此时路由为 [`/cneb/yjxx/广东省/广州市`](https://rsshub.app/cneb/yjxx/广东省/广州市)。\n\n若订阅 **广东省广州市** 的 **黄色** 预警信息，此时路由为 [`/cneb/yjxx/广东省/广州市/黄色`](https://rsshub.app/cneb/yjxx/广东省/广州市/黄色)。\n:::",
  "example": "/cneb/yjxx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 39,
  "location": "yjxx.ts",
  "maintainers": [
    "muzea",
    "nczitzk"
  ],
  "name": "预警信息",
  "parameters": {
    "city": "城市，默认为空，即全省",
    "level": "灾害级别，见下表，默认为全部",
    "province": "省份，默认为空，即全国"
  },
  "path": "/yjxx/:level?/:province?/:city?",
  "radar": [
    {
      "source": [
        "cneb.gov.cn/yjxx",
        "cneb.gov.cn/"
      ],
      "target": "/yjxx"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "国家应急广播 - 预警信息 - Powered by RSSHub",
      "errorAt": "2026-08-03T09:47:25.645Z",
      "errorMessage": "Failed query: select \"id\", \"guid\", \"media\" from \"entries\" \"entries\" where \"entries\".\"feed_id\" = $1\nparams: 62187667731240974",
      "id": "62187667731240974",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.cneb.gov.cn/yjxx",
      "title": "国家应急广播 - 预警信息",
      "type": "feed",
      "url": "rsshub://cneb/yjxx"
    },
    {
      "description": "国家应急广播 - 北京市海淀区预警信息 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60199571398524980",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.cneb.gov.cn/yjxx",
      "title": "国家应急广播 - 北京市海淀区预警信息",
      "type": "feed",
      "url": "rsshub://cneb/yjxx/%E5%8C%97%E4%BA%AC%E5%B8%82/%E6%B5%B7%E6%B7%80%E5%8C%BA"
    }
  ],
  "url": "cneb.gov.cn/yjxx"
}
```
