# FashionNetwork - FashionNetwork 中国

## Coverage
`index-only`

## Route
- Namespace: `fashionnetwork`
- Namespace Name: `FashionNetwork`
- Route Path: `/fashionnetwork/cn/lists/:id?`
- Route Name: `FashionNetwork 中国`
- Example: `/fashionnetwork/cn/lists/0`
- URL: `fashionnetwork.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [独家新闻](https://fashionnetwork.cn)，网址为 `https://fashionnetwork.cn/lists/13.html`。截取 `https://fashionnetwork.cn/` 到末尾 `.html` 的部分 `13` 作为参数填入，此时路由为 [`/fashionnetwork/cn/lists/13`](https://rsshub.app/fashionnetwork/cn/lists/13)。
:::

| 分类                                           | ID                                                  |
| ---------------------------------------------- | --------------------------------------------------- |
| [独家](https://fashionnetwork.cn/lists/13)     | [13](https://rsshub.app/fashionnetwork/cn/lists/13) |
| [商业](https://fashionnetwork.cn/lists/1)      | [1](https://rsshub.app/fashionnetwork/cn/lists/1)   |
| [人物](https://fashionnetwork.cn/lists/8)      | [8](https://rsshub.app/fashionnetwork/cn/lists/8)   |
| [设计](https://fashionnetwork.cn/lists/3)      | [3](https://rsshub.app/fashionnetwork/cn/lists/3)   |
| [产业](https://fashionnetwork.cn/lists/5)      | [5](https://rsshub.app/fashionnetwork/cn/lists/5)   |
| [创新研究](https://fashionnetwork.cn/lists/6)  | [6](https://rsshub.app/fashionnetwork/cn/lists/6)   |
| [人事变动](https://fashionnetwork.cn/lists/12) | [12](https://rsshub.app/fashionnetwork/cn/lists/12) |
| [新闻资讯](https://fashionnetwork.cn/lists/11) | [11](https://rsshub.app/fashionnetwork/cn/lists/11) |

## Parameters
- `category`: 分类，默认为 0，可在对应分类页 URL 中找到


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
  - `fashionnetwork.cn/lists/:id`
### Rule 2
- `title`: `独家`
- `source`:
  - `fashionnetwork.cn/lists/13`
- `target`: `/cn/lists/13`
### Rule 3
- `title`: `商业`
- `source`:
  - `fashionnetwork.cn/lists/1`
- `target`: `/cn/lists/1`
### Rule 4
- `title`: `人物`
- `source`:
  - `fashionnetwork.cn/lists/8`
- `target`: `/cn/lists/8`
### Rule 5
- `title`: `设计`
- `source`:
  - `fashionnetwork.cn/lists/3`
- `target`: `/cn/lists/3`
### Rule 6
- `title`: `产业`
- `source`:
  - `fashionnetwork.cn/lists/5`
- `target`: `/cn/lists/5`
### Rule 7
- `title`: `创新研究`
- `source`:
  - `fashionnetwork.cn/lists/6`
- `target`: `/cn/lists/6`
### Rule 8
- `title`: `人事变动`
- `source`:
  - `fashionnetwork.cn/lists/12`
- `target`: `/cn/lists/12`
### Rule 9
- `title`: `新闻资讯`
- `source`:
  - `fashionnetwork.cn/lists/11`
- `target`: `/cn/lists/11`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n若订阅 [独家新闻](https://fashionnetwork.cn)，网址为 `https://fashionnetwork.cn/lists/13.html`。截取 `https://fashionnetwork.cn/` 到末尾 `.html` 的部分 `13` 作为参数填入，此时路由为 [`/fashionnetwork/cn/lists/13`](https://rsshub.app/fashionnetwork/cn/lists/13)。\n:::\n\n| 分类                                           | ID                                                  |\n| ---------------------------------------------- | --------------------------------------------------- |\n| [独家](https://fashionnetwork.cn/lists/13)     | [13](https://rsshub.app/fashionnetwork/cn/lists/13) |\n| [商业](https://fashionnetwork.cn/lists/1)      | [1](https://rsshub.app/fashionnetwork/cn/lists/1)   |\n| [人物](https://fashionnetwork.cn/lists/8)      | [8](https://rsshub.app/fashionnetwork/cn/lists/8)   |\n| [设计](https://fashionnetwork.cn/lists/3)      | [3](https://rsshub.app/fashionnetwork/cn/lists/3)   |\n| [产业](https://fashionnetwork.cn/lists/5)      | [5](https://rsshub.app/fashionnetwork/cn/lists/5)   |\n| [创新研究](https://fashionnetwork.cn/lists/6)  | [6](https://rsshub.app/fashionnetwork/cn/lists/6)   |\n| [人事变动](https://fashionnetwork.cn/lists/12) | [12](https://rsshub.app/fashionnetwork/cn/lists/12) |\n| [新闻资讯](https://fashionnetwork.cn/lists/11) | [11](https://rsshub.app/fashionnetwork/cn/lists/11) |",
  "example": "/fashionnetwork/cn/lists/0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 8,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "FashionNetwork 中国",
  "parameters": {
    "category": "分类，默认为 0，可在对应分类页 URL 中找到"
  },
  "path": "/cn/lists/:id?",
  "radar": [
    {
      "source": [
        "fashionnetwork.cn/lists/:id"
      ]
    },
    {
      "source": [
        "fashionnetwork.cn/lists/13"
      ],
      "target": "/cn/lists/13",
      "title": "独家"
    },
    {
      "source": [
        "fashionnetwork.cn/lists/1"
      ],
      "target": "/cn/lists/1",
      "title": "商业"
    },
    {
      "source": [
        "fashionnetwork.cn/lists/8"
      ],
      "target": "/cn/lists/8",
      "title": "人物"
    },
    {
      "source": [
        "fashionnetwork.cn/lists/3"
      ],
      "target": "/cn/lists/3",
      "title": "设计"
    },
    {
      "source": [
        "fashionnetwork.cn/lists/5"
      ],
      "target": "/cn/lists/5",
      "title": "产业"
    },
    {
      "source": [
        "fashionnetwork.cn/lists/6"
      ],
      "target": "/cn/lists/6",
      "title": "创新研究"
    },
    {
      "source": [
        "fashionnetwork.cn/lists/12"
      ],
      "target": "/cn/lists/12",
      "title": "人事变动"
    },
    {
      "source": [
        "fashionnetwork.cn/lists/11"
      ],
      "target": "/cn/lists/11",
      "title": "新闻资讯"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "新闻 - 时尚商业网|时尚全方位商业报道 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "125749806716230656",
      "image": "https://fashionnetwork.cn/static/images/fashion-network-logo.webp",
      "ownerUserId": null,
      "siteUrl": "https://fashionnetwork.cn/lists/11.html",
      "title": "新闻 - FashionNetwork.com 中国",
      "type": "feed",
      "url": "rsshub://fashionnetwork/cn/lists/11.html"
    },
    {
      "description": "新闻 - 时尚商业网|时尚全方位商业报道 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "125750058291721216",
      "image": "https://fashionnetwork.cn/static/images/fashion-network-logo.webp",
      "ownerUserId": null,
      "siteUrl": "https://fashionnetwork.cn/lists/3.html",
      "title": "新闻 - FashionNetwork.com 中国",
      "type": "feed",
      "url": "rsshub://fashionnetwork/cn/lists/3.html"
    }
  ],
  "url": "fashionnetwork.cn"
}
```
