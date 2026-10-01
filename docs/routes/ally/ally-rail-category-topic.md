# 艾莱资讯 - 世界轨道交通资讯网

## Coverage
`index-only`

## Route
- Namespace: `ally`
- Namespace Name: `艾莱资讯`
- Route Path: `/ally/rail/:category?/:topic?`
- Route Name: `世界轨道交通资讯网`
- Example: `/ally/rail/hyzix/chengguijiaotong`
- URL: `rail.ally.net.cn/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Rongronggg9`
- Source Location: `rail.ts`
- Source Module: `_None_`

## Description
::: tip
默认抓取前 20 条，可通过 `?limit=` 改变。
:::

## Parameters
- `category`: 分类，可在 URL 中找到；略去则抓取首页
- `topic`: 话题，可在 URL 中找到；并非所有页面均有此字段


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
  - `rail.ally.net.cn/`
  - `rail.ally.net.cn/html/:category?/:topic?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n默认抓取前 20 条，可通过 `?limit=` 改变。\n:::",
  "example": "/ally/rail/hyzix/chengguijiaotong",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "rail.ts",
  "maintainers": [
    "Rongronggg9"
  ],
  "name": "世界轨道交通资讯网",
  "parameters": {
    "category": "分类，可在 URL 中找到；略去则抓取首页",
    "topic": "话题，可在 URL 中找到；并非所有页面均有此字段"
  },
  "path": "/rail/:category?/:topic?",
  "radar": [
    {
      "source": [
        "rail.ally.net.cn/",
        "rail.ally.net.cn/html/:category?/:topic?"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "世界轨道交通资讯网是为关注轨道交通、轨道、铁路、轨道交通资讯、火车、高铁、铁路行业发展最新动态的决策者和研究者提供信息服务的中英文网站；在广泛全面地为业内读者提供世界轨道交通行业信息的同时，通过电子 信息化的表现手段，全方位、跨时空为企业推广提供了全景的展示平台。为企业提供新闻稿发布，协助企业提高知名度、塑造企业形象以及企业品牌或项目品牌推广。该网是由世界轨道发展研究会以及北京艾莱时代资讯有限公司共同主办的《世界轨道交通》杂志的官方网站。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72207824857851904",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://rail.ally.net.cn/html/hyzix/chengguijiaotong/",
      "title": "世界轨道交通资讯网 - 资讯 - 行业资讯 - 城轨交通",
      "type": "feed",
      "url": "rsshub://ally/rail/hyzix/chengguijiaotong"
    }
  ],
  "url": "rail.ally.net.cn/"
}
```
