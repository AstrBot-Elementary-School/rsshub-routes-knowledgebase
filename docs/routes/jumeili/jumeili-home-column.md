# 聚美丽 - 首页资讯

## Coverage
`index-only`

## Route
- Namespace: `jumeili`
- Namespace Name: `聚美丽`
- Route Path: `/jumeili/home/:column?`
- Route Name: `首页资讯`
- Example: `/jumeili/home`
- URL: `jumeili.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `kjasn`
- Source Location: `home.ts`
- Source Module: `_None_`

## Description
::: Warning
未登录用户无法获取完整文章内容，只能看到预览内容。想要获取完整文章内容，需要设置`JUMEILI_COOKIE`环境变量。
:::

## Parameters
- `column`: 内容栏, 默认为 `0`（最新）。其他可选：`-1`（头条）、`62073`（精选）、`13243`（年度大会）等。详细可以在开发者工具 Network 面板中找到，如：`https://www.jumeili.cn/ws/AjaxService.ashx?act=index_article&page=1&pageSize=20&column=0`最后的 `column=0` 即为`column` 参数


## Features
- `requireConfig`: [{"description": "用户登录后，可以从浏览器开发者工具 Network 面板中的 jumeili 页面请求获取 Cookie，如：`ASP.NET_SessionId=xxx;jmlweb4=xxx`全部复制并设置为环境变量", "name": "JUMEILI_COOKIE", "optional": true}]
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `www.jumeili.cn/`
- `target`: `/home/:column?`
### Rule 2
- `source`:
  - `jumeili.cn/`
- `target`: `/home/:column?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: Warning\n未登录用户无法获取完整文章内容，只能看到预览内容。想要获取完整文章内容，需要设置`JUMEILI_COOKIE`环境变量。\n:::",
  "example": "/jumeili/home",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "用户登录后，可以从浏览器开发者工具 Network 面板中的 jumeili 页面请求获取 Cookie，如：`ASP.NET_SessionId=xxx;jmlweb4=xxx`全部复制并设置为环境变量",
        "name": "JUMEILI_COOKIE",
        "optional": true
      }
    ]
  },
  "heat": 3,
  "location": "home.ts",
  "maintainers": [
    "kjasn"
  ],
  "name": "首页资讯",
  "parameters": {
    "column": "内容栏, 默认为 `0`（最新）。其他可选：`-1`（头条）、`62073`（精选）、`13243`（年度大会）等。详细可以在开发者工具 Network 面板中找到，如：`https://www.jumeili.cn/ws/AjaxService.ashx?act=index_article&page=1&pageSize=20&column=0`最后的 `column=0` 即为`column` 参数"
  },
  "path": "/home/:column?",
  "radar": [
    {
      "source": [
        "www.jumeili.cn/"
      ],
      "target": "/home/:column?"
    },
    {
      "source": [
        "jumeili.cn/"
      ],
      "target": "/home/:column?"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "聚美丽 - 首页资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "142472750016837632",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "聚美丽 - 首页资讯",
      "type": "feed",
      "url": "rsshub://jumeili/home"
    }
  ]
}
```
