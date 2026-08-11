# 52hrtt 华人头条 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `52hrtt`
- Namespace Name: `52hrtt 华人头条`
- Route Path: `/52hrtt/:area?/:type?`
- Route Name: `新闻`
- Example: `/52hrtt/global`
- URL: `52hrtt.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
地区和分类皆可在浏览器地址栏中找到，下面是一个例子。

访问华人头条全球站的国际分类，会跳转到 `https://www.52hrtt.com/global/n/w?infoTypeId=A1459145516533`。其中 `global` 即为 **全球** 对应的地区代码，`A1459145516533` 即为 **国际** 对应的分类代码。

## Parameters
- `area`: 地区，默认为全球
- `type`: 分类，默认为新闻


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
  "description": "地区和分类皆可在浏览器地址栏中找到，下面是一个例子。\n\n访问华人头条全球站的国际分类，会跳转到 `https://www.52hrtt.com/global/n/w?infoTypeId=A1459145516533`。其中 `global` 即为 **全球** 对应的地区代码，`A1459145516533` 即为 **国际** 对应的分类代码。",
  "example": "/52hrtt/global",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 129,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新闻",
  "parameters": {
    "area": "地区，默认为全球",
    "type": "分类，默认为新闻"
  },
  "path": "/:area?/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "全球 - 新闻 - 华人头条 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59115434638189568",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.52hrtt.com/global/n/w",
      "title": "全球 - 新闻 - 华人头条",
      "type": "feed",
      "url": "rsshub://52hrtt/global"
    },
    {
      "description": "全球 - 新闻 - 华人头条 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67739090904930304",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.52hrtt.com/global/n/w",
      "title": "全球 - 新闻 - 华人头条",
      "type": "feed",
      "url": "rsshub://52hrtt"
    }
  ]
}
```
