# 集思录 - 分类

## Coverage
`index-only`

## Route
- Namespace: `jisilu`
- Namespace Name: `集思录`
- Route Path: `/jisilu/category/:id`
- Route Name: `分类`
- Example: `/jisilu/category/4`
- URL: `www.jisilu.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [债券 / 可转债](https://www.jisilu.cn/category/4)，网址为 `https://www.jisilu.cn/category/4`，请截取 `https://www.jisilu.cn/category/` 到末尾的部分 `4` 作为 `id` 参数填入，此时目标路由为 [`/jisilu/category/4`](https://rsshub.app/jisilu/category/4)。
:::

| 新股 | 债券 / 可转债 | 套利 | 其他 | 基金 | 股票 |
| ---- | ------------- | ---- | ---- | ---- | ---- |
| 3    | 4             | 5    | 6    | 7    | 8    |

## Parameters
- `id`: 分类 id，可在对应分类页 URL 中找到


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
  - `www.jisilu.cn/category/:id`
- `target`: `/category/:id`
### Rule 2
- `title`: `新股`
- `source`:
  - `www.jisilu.cn/category/3`
- `target`: `/category/3`
### Rule 3
- `title`: `债券/可转债`
- `source`:
  - `www.jisilu.cn/category/4`
- `target`: `/category/4`
### Rule 4
- `title`: `套利`
- `source`:
  - `www.jisilu.cn/category/5`
- `target`: `/category/5`
### Rule 5
- `title`: `其他`
- `source`:
  - `www.jisilu.cn/category/6`
- `target`: `/category/6`
### Rule 6
- `title`: `基金`
- `source`:
  - `www.jisilu.cn/category/7`
- `target`: `/category/7`
### Rule 7
- `title`: `股票`
- `source`:
  - `www.jisilu.cn/category/8`
- `target`: `/category/8`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n若订阅 [债券 / 可转债](https://www.jisilu.cn/category/4)，网址为 `https://www.jisilu.cn/category/4`，请截取 `https://www.jisilu.cn/category/` 到末尾的部分 `4` 作为 `id` 参数填入，此时目标路由为 [`/jisilu/category/4`](https://rsshub.app/jisilu/category/4)。\n:::\n\n| 新股 | 债券 / 可转债 | 套利 | 其他 | 基金 | 股票 |\n| ---- | ------------- | ---- | ---- | ---- | ---- |\n| 3    | 4             | 5    | 6    | 7    | 8    |",
  "example": "/jisilu/category/4",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 48,
  "location": "category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "id": "分类 id，可在对应分类页 URL 中找到"
  },
  "path": "/category/:id",
  "radar": [
    {
      "source": [
        "www.jisilu.cn/category/:id"
      ],
      "target": "/category/:id"
    },
    {
      "source": [
        "www.jisilu.cn/category/3"
      ],
      "target": "/category/3",
      "title": "新股"
    },
    {
      "source": [
        "www.jisilu.cn/category/4"
      ],
      "target": "/category/4",
      "title": "债券/可转债"
    },
    {
      "source": [
        "www.jisilu.cn/category/5"
      ],
      "target": "/category/5",
      "title": "套利"
    },
    {
      "source": [
        "www.jisilu.cn/category/6"
      ],
      "target": "/category/6",
      "title": "其他"
    },
    {
      "source": [
        "www.jisilu.cn/category/7"
      ],
      "target": "/category/7",
      "title": "基金"
    },
    {
      "source": [
        "www.jisilu.cn/category/8"
      ],
      "target": "/category/8",
      "title": "股票"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "债券/可转债 - 经典固定收益类 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "126653937076005888",
      "image": "https://www.jisilu.cn/static/css/jisilu/img/logo_jisilu.png",
      "ownerUserId": null,
      "siteUrl": "https://www.jisilu.cn/category/4",
      "title": "债券/可转债 - 集思录 - 最新",
      "type": "feed",
      "url": "rsshub://jisilu/category/4"
    },
    {
      "description": "股票 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "115953821908145152",
      "image": "https://www.jisilu.cn/static/css/jisilu/img/logo_jisilu.png",
      "ownerUserId": null,
      "siteUrl": "https://www.jisilu.cn/category/8",
      "title": "股票 - 集思录 -",
      "type": "feed",
      "url": "rsshub://jisilu/category/8"
    }
  ],
  "url": "www.jisilu.cn",
  "view": 0
}
```
