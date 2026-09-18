# 中国军网 - 中国人民解放军专业技术人才网

## Coverage
`index-only`

## Route
- Namespace: `81`
- Namespace Name: `中国军网`
- Route Path: `/81/81rc/:category{.+}?`
- Route Name: `中国人民解放军专业技术人才网`
- Example: `/81/81rc/sy/gzdt_210283`
- URL: `81rc.81.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `81rc/index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [工作动态](https://81rc.81.cn/sy/gzdt_210283)，网址为 `https://81rc.81.cn/sy/gzdt_210283`。截取 `https://81rc.81.cn/` 到末尾的部分 `sy/gzdt_210283` 作为参数填入，此时路由为 [`/81/81rc/sy/gzdt_210283`](https://rsshub.app/81/81rc/sy/gzdt_210283)。
:::

## Parameters
- `category`: 分类，默认为 `sy/gzdt_210283`，即工作动态，可在对应分类页 URL 中找到


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
  - `81rc.81.cn/:category`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n若订阅 [工作动态](https://81rc.81.cn/sy/gzdt_210283)，网址为 `https://81rc.81.cn/sy/gzdt_210283`。截取 `https://81rc.81.cn/` 到末尾的部分 `sy/gzdt_210283` 作为参数填入，此时路由为 [`/81/81rc/sy/gzdt_210283`](https://rsshub.app/81/81rc/sy/gzdt_210283)。\n:::",
  "example": "/81/81rc/sy/gzdt_210283",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 4,
  "location": "81rc/index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "中国人民解放军专业技术人才网",
  "parameters": {
    "category": "分类，默认为 `sy/gzdt_210283`，即工作动态，可在对应分类页 URL 中找到"
  },
  "path": "/81rc/:category{.+}?",
  "radar": [
    {
      "source": [
        "81rc.81.cn/:category"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "欢迎来到军队人才网！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70682485663234048",
      "image": "https://81rc.81.cn/template/tenant207/t582/new.jpg",
      "ownerUserId": null,
      "siteUrl": "https://81rc.81.cn/sy/gzdt_210283",
      "title": "工作动态 - 军队人才网",
      "type": "feed",
      "url": "rsshub://81/81rc/sy/gzdt_210283"
    },
    {
      "description": "欢迎来到军队人才网！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "119419273712365568",
      "image": "https://81rc.81.cn/template/tenant207/t582/new.jpg",
      "ownerUserId": null,
      "siteUrl": "https://81rc.81.cn/wzry/jwjgbmhddwzkdt",
      "title": "中国人民解放军专业技术人才网-文职人员",
      "type": "feed",
      "url": "rsshub://81/81rc/wzry/jwjgbmhddwzkdt"
    }
  ],
  "url": "81rc.81.cn"
}
```
