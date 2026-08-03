# 集思录 - 广场

## Coverage
`index-only`

## Route
- Namespace: `jisilu`
- Namespace Name: `集思录`
- Route Path: `/jisilu/explore/:filter?`
- Route Name: `广场`
- Example: `/jisilu/explore`
- URL: `www.jisilu.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `explore.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [债券 / 可转债 - 热门 - 30 天](https://www.jisilu.cn/home/explore/category-4__sort_type-hot__day-30)，网址为 `https://www.jisilu.cn/home/explore/category-4__sort_type-hot__day-30`，请截取 `https://www.jisilu.cn/home/explore/` 到末尾的部分 `category-4__sort_type-hot__day-30` 作为 `filter` 参数填入，此时目标路由为 [`/jisilu/explore/category-4__sort_type-hot__day-30`](https://rsshub.app/jisilu/explore/category-4__sort_type-hot__day-30)。
:::

## Parameters
- `category`: 过滤器，默认为空，可在对应页 URL 中找到


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
  - `www.jisilu.cn/home/explore/:filter`
  - `www.jisilu.cn/home/explore`
  - `www.jisilu.cn/explore`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n若订阅 [债券 / 可转债 - 热门 - 30 天](https://www.jisilu.cn/home/explore/category-4__sort_type-hot__day-30)，网址为 `https://www.jisilu.cn/home/explore/category-4__sort_type-hot__day-30`，请截取 `https://www.jisilu.cn/home/explore/` 到末尾的部分 `category-4__sort_type-hot__day-30` 作为 `filter` 参数填入，此时目标路由为 [`/jisilu/explore/category-4__sort_type-hot__day-30`](https://rsshub.app/jisilu/explore/category-4__sort_type-hot__day-30)。\n:::",
  "example": "/jisilu/explore",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 299,
  "location": "explore.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "广场",
  "parameters": {
    "category": "过滤器，默认为空，可在对应页 URL 中找到"
  },
  "path": "/explore/:filter?",
  "radar": [
    {
      "source": [
        "www.jisilu.cn/home/explore/:filter",
        "www.jisilu.cn/home/explore",
        "www.jisilu.cn/explore"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "集思录，一个以数据为本的投资社区 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60339440727459840",
      "image": "https://www.jisilu.cn/static/css/jisilu/img/logo_jisilu.png",
      "ownerUserId": null,
      "siteUrl": "https://www.jisilu.cn/explore/",
      "title": "集思录 - 最新",
      "type": "feed",
      "url": "rsshub://jisilu/explore"
    },
    {
      "description": "集思录，一个以数据为本的投资社区 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "133377208716175360",
      "image": "https://www.jisilu.cn/static/css/jisilu/img/logo_jisilu.png",
      "ownerUserId": null,
      "siteUrl": "https://www.jisilu.cn/home/explore/sort_type-hot____day-1",
      "title": "集思录 - 热门|当天",
      "type": "feed",
      "url": "rsshub://jisilu/explore/sort_type-hot____day-1"
    }
  ],
  "url": "www.jisilu.cn",
  "view": 0
}
```
