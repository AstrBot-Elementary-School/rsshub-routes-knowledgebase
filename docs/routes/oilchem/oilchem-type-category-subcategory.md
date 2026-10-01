# 隆众资讯 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `oilchem`
- Namespace Name: `隆众资讯`
- Route Path: `/oilchem/:type?/:category?/:subCategory?`
- Route Name: `资讯`
- Example: `/oilchem/list/140/18263`
- URL: `oilchem.net`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
以下是几个例子：

[**化工**](https://chem.oilchem.net) `https://chem.oilchem.net` 中，类别 id 为 `chem`，分类 id 为空，子分类 id 为空，对应路由即为 [`/oilchem/chem`](https://rsshub.app/oilchem/list/140/18263)

[**甲醇**](https://chem.oilchem.net/chemical/methanol.shtml) 的相关资讯有两个页面入口：其一 `https://chem.oilchem.net/chemical/methanol.shtml` 中，类别 id 为 `chem`，分类 id 为 `chemical`，子分类 id 为 `methanol`，对应路由即为 [`/oilchem/chem/chemical/methanol`](https://rsshub.app/oilchem/chem/chemical/methanol) 或其二 `https://list.oilchem.net/140` 中，类别 id 为 `list`，分类 id 为 `140`，子分类 id 为空，对应路由即为 [`/oilchem/list/140`](https://rsshub.app/oilchem/list/140)；

[**甲醇热点聚焦**](https://list.oilchem.net/140/18263) `https://list.oilchem.net/140/18263` 中，类别 id 为 `list`，分类 id 为 `140`，子分类 id 为 `18263`，对应路由即为 [`/oilchem/list/140/18263`](https://rsshub.app/oilchem/list/140/18263)

## Parameters
- `type`: 类别 id，可在对应类别页中找到，默认为首页
- `category`: 分类 id，可在对应分类页中找到
- `subCategory`: 子分类 id，可在对应分类页中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "以下是几个例子：\n\n[**化工**](https://chem.oilchem.net) `https://chem.oilchem.net` 中，类别 id 为 `chem`，分类 id 为空，子分类 id 为空，对应路由即为 [`/oilchem/chem`](https://rsshub.app/oilchem/list/140/18263)\n\n[**甲醇**](https://chem.oilchem.net/chemical/methanol.shtml) 的相关资讯有两个页面入口：其一 `https://chem.oilchem.net/chemical/methanol.shtml` 中，类别 id 为 `chem`，分类 id 为 `chemical`，子分类 id 为 `methanol`，对应路由即为 [`/oilchem/chem/chemical/methanol`](https://rsshub.app/oilchem/chem/chemical/methanol) 或其二 `https://list.oilchem.net/140` 中，类别 id 为 `list`，分类 id 为 `140`，子分类 id 为空，对应路由即为 [`/oilchem/list/140`](https://rsshub.app/oilchem/list/140)；\n\n[**甲醇热点聚焦**](https://list.oilchem.net/140/18263) `https://list.oilchem.net/140/18263` 中，类别 id 为 `list`，分类 id 为 `140`，子分类 id 为 `18263`，对应路由即为 [`/oilchem/list/140/18263`](https://rsshub.app/oilchem/list/140/18263)",
  "example": "/oilchem/list/140/18263",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "资讯",
  "parameters": {
    "category": "分类 id，可在对应分类页中找到",
    "subCategory": "子分类 id，可在对应分类页中找到",
    "type": "类别 id，可在对应类别页中找到，默认为首页"
  },
  "path": "/:type?/:category?/:subCategory?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "首页 - 隆众资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "245770043138465792",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.oilchem.net/1/",
      "title": "首页 - 隆众资讯",
      "type": "feed",
      "url": "rsshub://oilchem"
    },
    {
      "description": "甲醇热点聚焦 - 隆众资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82667463412830208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://list.oilchem.net/140/18263",
      "title": "甲醇热点聚焦 - 隆众资讯",
      "type": "feed",
      "url": "rsshub://oilchem/list/140/18263"
    }
  ]
}
```
