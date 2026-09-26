# 国家发展和改革委员会价格监测中心 - 中华人民共和国国家发展和改革委员会价格监测中心

## Coverage
`index-only`

## Route
- Namespace: `gov/jgjcndrc`
- Namespace Name: `国家发展和改革委员会价格监测中心`
- Route Path: `/gov/jgjcndrc/:columnId?/:subColumnId?`
- Route Name: `中华人民共和国国家发展和改革委员会价格监测中心`
- Example: `/gov/jgjcndrc/1832739866673426433`
- URL: `www.jgjcndrc.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [通知公告](https://www.jgjcndrc.org.cn/list?clmId=1832739866673426433)，网址为 `https://www.jgjcndrc.org.cn/list?clmId=1832739866673426433`。截取 `clmId` 的参数部分 `1832739866673426433` 作为参数填入，此时路由为 [`/gov/jgjcndrc/1832739866673426433`](https://rsshub.app/gov/jgjcndrc/1832739866673426433)。

若订阅 [国内外市场价格监测情况周报](https://www.jgjcndrc.org.cn/list?clmId=1832298113994649601\&sclmId=1832751799531220993)，网址为 `https://www.jgjcndrc.org.cn/list?clmId=1832298113994649601&sclmId=1832751799531220993`。截取 `clmId` 和 `sclmId` 的参数部分 `1832298113994649601` 和 `1832751799531220993` 作为参数填入，此时路由为 [`/gov/jgjcndrc/1832298113994649601/1832751799531220993`](https://rsshub.app/gov/jgjcndrc/1832298113994649601/1832751799531220993)。
:::

## Parameters
- `columnId`: 栏目 id，默认为 `1832739866673426433`，即通知公告，可在对应栏目页 URL 中找到
- `subColumnId`: 子栏目 id，默认为空，可在对应子栏目页 URL 中找到


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
  - `www.jgjcndrc.org.cn/list`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n若订阅 [通知公告](https://www.jgjcndrc.org.cn/list?clmId=1832739866673426433)，网址为 `https://www.jgjcndrc.org.cn/list?clmId=1832739866673426433`。截取 `clmId` 的参数部分 `1832739866673426433` 作为参数填入，此时路由为 [`/gov/jgjcndrc/1832739866673426433`](https://rsshub.app/gov/jgjcndrc/1832739866673426433)。\n\n若订阅 [国内外市场价格监测情况周报](https://www.jgjcndrc.org.cn/list?clmId=1832298113994649601\\&sclmId=1832751799531220993)，网址为 `https://www.jgjcndrc.org.cn/list?clmId=1832298113994649601&sclmId=1832751799531220993`。截取 `clmId` 和 `sclmId` 的参数部分 `1832298113994649601` 和 `1832751799531220993` 作为参数填入，此时路由为 [`/gov/jgjcndrc/1832298113994649601/1832751799531220993`](https://rsshub.app/gov/jgjcndrc/1832298113994649601/1832751799531220993)。\n:::",
  "example": "/gov/jgjcndrc/1832739866673426433",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 21,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "中华人民共和国国家发展和改革委员会价格监测中心",
  "parameters": {
    "columnId": "栏目 id，默认为 `1832739866673426433`，即通知公告，可在对应栏目页 URL 中找到",
    "subColumnId": "子栏目 id，默认为空，可在对应子栏目页 URL 中找到"
  },
  "path": "/:columnId?/:subColumnId?",
  "radar": [
    {
      "source": [
        "www.jgjcndrc.org.cn/list"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "中华人民共和国国家发展和改革委员会 价格监测中心 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72251568820057088",
      "image": "https://www.jgjcndrc.org.cn/_nuxt/logo.nPIpRnSK.svg",
      "ownerUserId": null,
      "siteUrl": "https://www.jgjcndrc.org.cn/list?clmId=1832739866673426433",
      "title": "中华人民共和国国家发展和改革委员会 - 通知公告",
      "type": "feed",
      "url": "rsshub://gov/jgjcndrc/1832739866673426433"
    },
    {
      "description": "监测信息 - 猪料、鸡料、蛋料比价信息 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "112027538201244672",
      "image": "https://www.jgjcndrc.org.cn/_nuxt/logo.nPIpRnSK.svg",
      "ownerUserId": null,
      "siteUrl": "https://www.jgjcndrc.org.cn/list?clmId=1832298113994649601&sclmId=1840280592963387394",
      "title": "中华人民共和国国家发展和改革委员会 - 监测信息-猪料、鸡料、蛋料比价信息",
      "type": "feed",
      "url": "rsshub://gov/jgjcndrc/1832298113994649601/1840280592963387394"
    }
  ],
  "url": "www.jgjcndrc.org.cn"
}
```
